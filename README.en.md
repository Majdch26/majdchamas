<div align="center">

[Français](README.md) | **English**

# Majd Chamas

**First-year Master's student in Machine Learning & Data Mining (MLDM)**<br>
Jean Monnet University, Saint-Étienne, France

*Looking for a Data / Machine Learning internship*

[![Email](https://img.shields.io/badge/Email-majdchamas26%40gmail.com-1b2a6b?style=flat-square&logo=gmail&logoColor=white)](mailto:majdchamas26@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Majdch26-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Majdch26)
[![GitLab](https://img.shields.io/badge/GitLab-Majdch26-FC6D26?style=flat-square&logo=gitlab&logoColor=white)](https://gitlab.com/Majdch26)

</div>

---

## About me

Master's student in MLDM after a Bachelor's degree in Computer Science at Jean Monnet University. I enjoy turning data and business rules into working software: data analysis with SQL and Python, game AI, databases, real-time servers and 3D rendering.

Languages: French (C1), English (C1), Arabic (native).

---

## Skills

**Data & Machine Learning**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)

**Databases**<br>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Backend**<br>
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Frontend**<br>
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

**Systems & tools**<br>
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white)
![OCaml](https://img.shields.io/badge/OCaml-EC6813?style=flat-square&logo=ocaml&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

---

## Projects

### Data & artificial intelligence

#### Retail store network performance analysis (2026)
[Code](https://github.com/Majdch26/analyse-performance-magasins) · [Live dashboard](https://majdch26.github.io/analyse-performance-magasins/)

End-to-end analysis of 110,000 sales records (synthetic data for 15 stores over 2024-2025).

- Data quality checks and cleaning in SQL: duplicates, badly formatted IDs, inconsistent labels, missing values
- Monthly KPIs and year-over-year comparison (CTEs, joins)
- Analysis notebook, interactive dashboard and business recommendations

`SQL` `DuckDB` `Python` `pandas` `Plotly` `Jupyter`

#### Java wargame with artificial intelligence (2025-2026)
[Code](https://github.com/Majdch26/wargame-java) · Third-year team project, reworked and extended

Turn-based strategy game (heroes against monsters) with a Swing interface and fog of war.

- Three AI levels for the monsters (Strategy pattern): shared vision, memory of hero positions, breadth-first pathfinding
- An advisor for the player that scores every possible action and suggests the best one, plus an automatic turn mode
- 200 simulated games per level: the hard AI wins 94.5% of games, against about 55% for the other levels
- 50 automated tests

`Java` `Swing` `OOP` `Search algorithms`

#### Othello / Reversi with a 6-level AI (2025)
[Code](https://github.com/Majdch26/othello-reversi) · Second year

Reversi game in C with an SDL2 interface, a terminal mode and a tournament between AI levels.

- Minimax, alpha-beta pruning, iterative deepening
- Exact endgame solving when 14 or fewer empty squares remain
- Tests checking that alpha-beta finds the same value as a full minimax

`C` `SDL2` `Minimax` `Alpha-beta`

#### NLP and recommender systems (2026)
Natural Language Processing course

Study of the NLP techniques used by Netflix, TikTok and Spotify, and a prototype that recommends movies based on the text of their descriptions.

- Text cleaning, TF-IDF vectorization, cosine similarity (Netflix dataset, Google Colab)
- Comparison of approaches: embeddings, LLM fine-tuning, Semantic IDs
- Ethical issues: filter bubbles, algorithmic bias, GDPR

`Python` `NLP` `TF-IDF` `LaTeX/Beamer`

#### Minimum Set Cover: exact algorithms (2026, in progress)
[Code](https://github.com/farahnyoussef-ctrl/minimum-set-cover) · MLDM Master's, team project

Exact solving of the minimum set cover problem, with instances stored as bitmasks and evaluated on the OR-Library benchmark instances.

`Python` `Combinatorial optimization`

### Web & databases

#### University parking management system (2026)
[Code](https://github.com/Majdch26/parking_stage) · Personal project

Full-stack application with three roles (students, agents, administrators): bookings, waiting list, QR code access control and violation tracking.

- Secure REST API: JWT, role-based access control, BCrypt
- SQL Server database with hand-written SQL queries through Dapper
- Multi-criteria waiting-list prioritization and a rules engine (violation scoring, background alerts)

`C#` `ASP.NET Core` `SQL Server` `Dapper` `React` `Vite`

#### INKLAB: real-time collaborative editing (2026)
[Code](https://gitlab.com/KhayrEddinee/inklab) · Web Development 2 course, team project

Collaborative document editing platform, in the spirit of Notion or Google Docs.

- Live synchronization between users over WebSocket: editing, presence, chat, block locking
- Access levels and version history
- MVC + DAO architecture, thread-safe concurrency handling

`Java 21` `Jakarta EE` `WebSocket` `MySQL` `JSP` `Maven`

#### Real-time multiplayer game inspired by Agar.io (2026)
[Code](https://gitlab.com/projet_tutor1-l3/projet-tutore) · Third-year tutored project, team project

Game shown on a projector: each player scans a QR code and steers their cell from their smartphone with a touch joystick.

- FastAPI server with an asynchronous game loop running at 20 ticks per second
- Two WebSocket channels: display screen and controllers
- 2D rendering with PixiJS, solo and team modes, pytest tests
- Agile workflow: sprints, Kanban board, code reviews on GitLab

`Python` `FastAPI` `asyncio` `WebSockets` `PixiJS` `pytest`

#### Streaming platform database (2024)
[Code](https://github.com/Majdch26/streaming-sql) · Second year, team project

Full design and implementation of a database for a streaming platform.

- 13 tables, 14 stored procedures, 7 functions, 7 triggers, 4 views and roles
- Transactions with error handling, salted and hashed passwords, analysis queries with window functions
- 90 automated tests, passing on MySQL 8 and MariaDB

`SQL` `MySQL` `MariaDB`

#### BING: streaming website (2025)
[Code](https://github.com/Majdch26/bing-streaming) · Second year, Web Development 1

Streaming website built on the data model of the previous project: catalog, subscriptions, profiles, video player and admin area.

- Live search, favorites and resume playback
- Security: CSRF tokens, hashed passwords, access control
- 39 database tests and 75 end-to-end tests with Playwright

`PHP` `SQLite` `JavaScript` `HTML/CSS` `Playwright`

### Systems, compilers & graphics

#### CPYRR compiler (2026)
[Code](https://github.com/Majdch26/compilateur-cpyrr) · Third year

Compiler and virtual machine for a small imperative language with French keywords: lexical, syntactic and semantic analysis, then execution of the generated code.

- User-defined types (structures, multi-dimensional arrays), recursive functions and nested subprograms
- Detailed error messages

`C` `Flex` `Bison`

#### Interactive 3D maze (2026)
[Code](https://gitlab.com/Majdch26/sai) · Computer graphics course

C game with OpenGL: procedurally generated maze, free first-person camera, keys, doors and traps.

- Maze generation with a randomized depth-first search
- Collision detection with sliding along walls
- Dynamic lighting, fog, 2D interface

`C` `OpenGL` `GLUT`

#### Tetris (2024)
[Code](https://github.com/Majdch26/tetris-c) · First year, pair project

Complete Tetris in C with SDL2: rotations with wall kicks, ghost piece, hold, save slots and high scores.

`C` `SDL2`

---

## Education

| Period | |
|---|---|
| **2026 -** | **Master's in Machine Learning & Data Mining (first year)**, Jean Monnet University, Saint-Étienne |
| **2023 - 2026** | **Bachelor's degree in Computer Science**, Jean Monnet University, Saint-Étienne |
| **2023** | **French Baccalaureate**, Mathematics and Life Sciences, Collège Notre-Dame des Lourdes, Frères Maristes, Jbeil, Lebanon |

---

<div align="center">

**Contact:** [majdchamas26@gmail.com](mailto:majdchamas26@gmail.com)

</div>
