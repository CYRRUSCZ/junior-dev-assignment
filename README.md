# Testovací úkol – Kanban Board

## Cíl
Vytvořit jednoduchou aplikaci pro správu úkolů pomocí **Vue.js 3** (TypeScript) na frontendové straně a **NestJS** (TypeScript) na backendu.  
Aplikace bude zobrazovat jednoduchý **Kanban board se třemi sloupci** (*To Do*, *In Progress*, *Done*).  

---

## Funkcionalita

### Frontend (Vue.js 3, TypeScript)
- Zobrazení 3 kanban sloupců reprezentujících stav úkolu.  
- Možnost:  
  - **přidat** novou kartičku (titulek + obsah),  
  - **upravit** existující kartičku (titulek, obsah, stav),  
  - **smazat** kartičku.  
- Stylování pomocí čistého **Bootstrap (poslední verze)**, bez dalších knihoven pro UI.  

### Backend (NestJS, TypeScript)
- REST API pro CRUD operace nad úkoly.  
- Každý úkol obsahuje:  
  - `id`  
  - `title`  
  - `content`  
  - `status` (`todo`, `in-progress`, `done`).  
- Uložení dat v databázi: libovolná volba (**SQLite**, **MongoDB** nebo **PostgreSQL**).  

---

## Technické požadavky
- **Frontend:** Vue.js 3 + TypeScript (např. Vite).  
- **Backend:** NestJS + TypeScript.  
- **Styling:** čistý Bootstrap (bez dalších UI knihoven nebo CSS frameworků).  
- **Projektová struktura a nástroje:**  
  - Struktura projektu i použití nástrojů pro kvalitu kódu (**lint, prettier, testy apod.**) je plně na vás.  
  - Je povoleno využít **AI nástroje** (Copilot, ChatGPT, Claude apod.).  
- **README:** stručný popis řešení a postup pro spuštění frontendové i backendové části.  

---

## Bonusové úkoly *(nepovinné, ale vítané)*
1. **Dockerizace aplikace** – připravit `Dockerfile` a případně `docker-compose.yml` pro spuštění celé aplikace (frontend + backend + databáze).  
2. **Drag & Drop** – podpora pro přetahování kartiček mezi sloupci.  
3. **Řazení úkolů ve sloupci** – možnost měnit pořadí kartiček.  
4. **Testy** – základní unit/integration testy (backend nebo frontend).  
5. **Další vylepšení** – validace formulářů, lepší UX, apod.  

---

## Odevzdání
- Odevzdání formou **veřejného GitHub repozitáře**.  
- README musí obsahovat:  
  - stručný popis řešení a postupu při vývoji,  
  - postup pro lokální spuštění (Frontend + Backend, případně docker-compose).  
