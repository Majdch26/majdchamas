<div align="center">

# Majd Chamas

**Étudiant en Master 1 Machine Learning & Data Mining (MLDM)**
Université Jean Monnet · Saint-Étienne, France

*À la recherche d'un stage en Data / Machine Learning*

[![Email](https://img.shields.io/badge/Email-majdchamas26%40gmail.com-1b2a6b?style=flat-square&logo=gmail&logoColor=white)](mailto:majdchamas26@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Majdch26-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Majdch26)

</div>

---

## À propos

Étudiant en Master MLDM après une Licence Informatique à l'Université Jean Monnet. J'aime transformer des données et des règles métier en logiciels qui fonctionnent : du moteur de recommandation au serveur de jeu temps réel, en passant par les bases de données et le rendu 3D.

🇫🇷 Français (C1) · 🇬🇧 Anglais (C1) · 🇱🇧 Arabe (langue maternelle)

---

## Technologies

**Data & ML**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)

**Backend**
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Frontend**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

**Systèmes & outils**
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white)
![OCaml](https://img.shields.io/badge/OCaml-EC6813?style=flat-square&logo=ocaml&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

---

## Projets

### 🅿️ Système intelligent de gestion de parking universitaire · *2026*
> Projet personnel · [**Voir le code →**](https://github.com/Majdch26/parking_stage)

Application full-stack à trois rôles (étudiants, agents, administrateurs) : réservations, liste d'attente, contrôle d'accès par QR code et suivi des infractions.

- API REST sécurisée : JWT, contrôle d'accès par rôles, BCrypt
- Base SQL Server modélisée (utilisateurs, véhicules, places, réservations, sessions, infractions, journaux) et requêtes SQL écrites à la main via Dapper
- Algorithme de priorisation multicritère pour la liste d'attente
- Moteur de règles : détection d'anomalies, scoring des infractions, alertes en tâche de fond

`C#` `ASP.NET Core` `SQL Server` `Dapper` `React` `Vite` `JWT` `Swagger`

---

### 🧮 Minimum Set Cover — algorithmes exacts · *2026, en cours*
> Master MLDM · projet d'équipe · [**Voir le code →**](https://github.com/farahnyoussef-ctrl/minimum-set-cover)

Étude du problème de couverture minimale d'ensembles : représentation des instances par masques de bits et évaluation sur les instances de référence de l'OR-Library.

`Python` `Optimisation combinatoire` `OR-Library`

---

### 🎬 NLP & systèmes de recommandation · *2026*
> UE Traitement Automatique du Langage Naturel

Étude des techniques NLP utilisées par Netflix, TikTok et Spotify, et prototype Python de recommandation de films fondé sur le texte des descriptions.

- Pipeline : nettoyage de texte, vectorisation TF-IDF, similarité cosinus (dataset Netflix, Google Colab)
- Analyse comparative : embeddings, fine-tuning de LLM, Semantic IDs
- Enjeux éthiques : bulles de filtres, biais algorithmique, RGPD
- Présentation en LaTeX/Beamer avec visualisations

`Python` `NLP` `TF-IDF` `Google Colab` `LaTeX/Beamer`

---

### 🟢 Jeu multijoueur temps réel type Agar.io · *2026*
> Projet tutoré · en équipe

Jeu affiché sur vidéoprojecteur : chaque joueur scanne un QR code et pilote sa cellule depuis son smartphone avec un joystick tactile.

- Serveur FastAPI avec boucle de jeu asynchrone (asyncio) à 20 ticks/s
- Deux canaux WebSocket : écran d'affichage et manettes
- Rendu 2D WebGL avec PixiJS · modes solo et équipes
- Méthode Agile : sprints, Kanban, revues de code sur GitLab · tests pytest

`Python` `FastAPI` `WebSockets` `PixiJS` `JavaScript` `pytest`

---

### ✍️ INKLAB — édition collaborative en temps réel · *2026*
> Projet Développement Web

Plateforme d'édition collaborative de documents, dans l'esprit de Notion ou Google Docs.

- Synchronisation live multi-utilisateurs : édition, présence, chat, verrouillage de blocs
- Droits d'accès par niveaux et historique de versions
- Architecture MVC avec `BaseServlet` / `BaseDAO`, concurrence thread-safe

`Java 21` `Jakarta EE` `WebSocket` `MySQL` `JSP` `Maven`

---

### 🧱 Labyrinthe 3D interactif · *2026*
> Synthèse d'images

Jeu en C (C89) avec OpenGL/GLUT : labyrinthe généré procéduralement, caméra libre à la première personne, clés, portes et pièges.

- Génération du labyrinthe par DFS randomisé
- Collisions AABB avec glissement le long des murs
- Éclairage dynamique, brouillard, HUD 2D

`C` `OpenGL` `GLUT` `Makefile`

---

### ⚙️ Compilateur CPYRR · *2026*
Compilateur complet et machine virtuelle : analyse lexicale, syntaxique et sémantique, puis exécution du code produit.

`C` `Compilation`

---

### Autres projets

| Projet | Année | Technologies |
|---|---|---|
| Plateforme de streaming (authentification, abonnements, profils) | 2025 | PHP, JavaScript, MySQL |
| Base de données de films (modélisation, requêtes avancées, vues) | 2024 | SQL, MySQL |

---

## Parcours

| Période | |
|---|---|
| **2026 —** | **Master 1 Machine Learning & Data Mining** — Université Jean Monnet, Saint-Étienne |
| **2023 – 2026** | **Licence Informatique** — Université Jean Monnet, Saint-Étienne |
| **Été 2025** | **Stage Développement Web** — Jbail, Liban · site vitrine d'un restaurant avec réservation en ligne (HTML, CSS, JavaScript, PHP) |
| **2023** | **Baccalauréat français**, spécialités Mathématiques & SVT — Collège Notre-Dame des Lourdes, Frères Maristes, Jbail |

---

<div align="center">

📫 **Me contacter :** [majdchamas26@gmail.com](mailto:majdchamas26@gmail.com)

</div>
