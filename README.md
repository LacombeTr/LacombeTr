# Tristan Lacombe

**Développeur Full-Stack · Docteur en Sciences de la Terre**

Je conçois des applications web qui rendent exploitables des données scientifiques et
géographiques — du modèle de données jusqu'à l'interface, en passant par les tests et le déploiement.

Actuellement **développeur full-stack & testeur logiciel en alternance chez MSInsight** (dispositif
médical de diagnostic in vitro, ISO 13485 / IEC 62304). Je recherche un poste à l'interface
**logiciel · données · géosciences**, en agglomération lyonnaise.

---

## Ce que je fais

- **Des applications métier complètes** — authentification, rôles et permissions, migrations de
  base, API documentées, interfaces réactives. Pas de prototype jetable : des produits qui tournent.
- **Du calcul scientifique derrière une interface utilisable** — j'enveloppe des bibliothèques Python
  de pétrologie et de géochimie dans des services web, pour que des géologues les utilisent sans
  écrire une ligne de code.
- **Des tests et une chaîne CI/CD** — tests unitaires, d'intégration et end-to-end, lint, typecheck
  et audits de sécurité bloquants avant chaque déploiement.
- **De l'hébergement que j'administre moi-même** — VPS Linux, Docker Compose, Nginx, runners
  GitHub Actions auto-hébergés, durcissement SSH.

---

## Stack

**Front**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-087EA4?style=flat-square&logo=react&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white) ![React Native](https://img.shields.io/badge/React%20Native-58C4DC?style=flat-square&logo=react&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)


**Back**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Express](https://img.shields.io/badge/Express-404D59?style=flat-square&logo=express&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=flat-square&logo=typeorm&logoColor=white) ![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black) ![Swagger](https://img.shields.io/badge/Swagger-6BA539?style=flat-square&logo=swagger&logoColor=white)


**Qualité**

![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Supertest](https://img.shields.io/badge/Supertest-4B5563?style=flat-square) ![Cypress](https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white) ![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=black)


**Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square) ![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)


**Données & SIG**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white) ![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=flat-square&logo=mapbox&logoColor=white) ![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3&logoColor=white) ![Observable](https://img.shields.io/badge/Observable-353E4B?style=flat-square&logo=observable&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)


**Méthodes** — Agile / Scrum · développement assisté par IA (Claude Code) · environnement réglementé (ISO 13485, IEC 62304)

---

## Projets

### Petro-Geoch Online Tool (PGeoOT) · privé

Plateforme web modulaire de pétrologie et de géochimie. Le premier module expose la bibliothèque
scientifique Python [Thermobar](https://github.com/PennyWieser/Thermobar) (thermobarométrie,
hygrométrie) derrière une interface sans code : import de données, calcul de la norme CIPW,
formules structurales, graphiques interactifs, export Excel. Inscription sur code d'invitation,
administration des comptes.

**Monorepo Turborepo / npm workspaces, trois applications :**
- `web` — React, Vite, Tailwind, TanStack Query, Plotly, ExcelJS
- `api` — NestJS, TypeORM, PostgreSQL, JWT/Passport, Helmet, rate limiting, migrations versionnées
- `calc-svc` — Python 3.12, FastAPI, Thermobar, pyrolite, NumPy/pandas (géré avec `uv`)

**Ce dont je suis le plus satisfait :** la CI exécute lint, typecheck, tests Node, ruff et pytest,
plus `audit-ci` et `pip-audit` en barrières bloquantes ; le déploiement est déclenché par tag sur un
runner auto-hébergé et ne part qu'avec une CI verte. Le dépôt documente un audit de sécurité et un
audit RGPD.

<p align="center">
  <img src="assets/pgeoot-landing.jpg" alt="PGeoOT — page d'accueil" width="820">
</p>

<p align="center">
  <img src="assets/pgeoot-thermobarometrie.png" alt="PGeoOT — assistant de calcul thermobarométrique" width="820">
</p>


### My-HRM · privé

Application de gestion pour hôtel-restaurant : réservations de chambres (arrivées, départs,
recouches, petits-déjeuners), planning des tables du restaurant par salle et par service, suivi du
ménage, gestion du personnel et des rôles, agences partenaires, abonnement Stripe.

L'application fait respecter les règles du métier plutôt que de les laisser passer : jours de
fermeture, créneaux de service, capacité des chambres selon les lits — chaque création est validée
côté serveur.

**Stack :** NestJS, TypeORM, PostgreSQL, Swagger, Stripe · React, Vite, Tailwind, Radix UI,
Zustand, TanStack Query, PWA · monorepo npm workspaces, Docker Compose, déploiement sur VPS par SSH.
Tests Jest + Supertest côté API (unitaires, contrôleurs, e2e) et Vitest côté interface.
Documentation technique : diagramme de classes, modèle de données, architecture de déploiement,
plans de test.

<p align="center">
  <img src="assets/myhrm-planning-tables.png" alt="My-HRM — planning des tables du restaurant" width="820">
</p>

<p align="center">
  <img src="assets/myhrm-reservations-chambres.png" alt="My-HRM — réservations de chambres" width="820">
</p>

### [Unofficial GERM API](https://github.com/LacombeTr/volcapi) · public

API REST qui expose au format JSON les données du **GERM** (Geochemical Earth Reference Model),
jusqu'ici disponibles uniquement sous forme de tableaux HTML — pour les rendre exploitables par
des applications web et des scripts d'analyse.

**Stack :** TypeScript, Express, Drizzle ORM, PostgreSQL, collecte avec Cheerio, documentation
Swagger, tests Jest, conteneurisation Docker.

---

## Parcours & publications

**Docteur en Sciences de la Terre** (Université Clermont Auvergne, 2020–2023) — Laboratoire Magmas
et Volcans. Thèse : *Volcanisme basaltique et phonolitique de Petite-Terre (Mayotte)*, en
collaboration avec l'IPGP, l'Université Lyon 1 et l'OVSG. Quatre campagnes de terrain à Mayotte,
cartographie géomorphologique sous QGIS, plus de 500 échantillons analysés à la microsonde
électronique, traitement des données en Python.

**Développeur Full-Stack — niveau 6** (IT-Akademy, Lyon, 2024–2026, en alternance).

Publications à comité de lecture :

- Lacombe T., Gurioli L., Di Muro A., Médard E., *et al.* (2024) — Late Quaternary explosive
  phonolitic volcanism of Petite-Terre (Mayotte, Western Indian Ocean). *Bulletin of Volcanology*.
  [10.1007/s00445-023-01697-2](https://doi.org/10.1007/s00445-023-01697-2)
- Michaud-Dubuy A., Komorowski J.-C., Lacombe T., Gurioli L. (2024) — Tephra fallout hazard
  assessment for a hydrovolcanic eruptive scenario in Mayotte. *Scientific Reports*.
  [10.1038/s41598-024-83266-x](https://doi.org/10.1038/s41598-024-83266-x)
- Thivet S., Hess K.-U., Dingwell D. B., *et al.*, Lacombe T., Komorowski J.-C. (2023) — Volatiles
  of the active Mayotte volcanic chain: STA & EGA-MS analysis of volcanic products.
  *Chemical Geology*. [10.1016/j.chemgeo.2022.121297](https://doi.org/10.1016/j.chemgeo.2022.121297)

---

## Contact

- **LinkedIn** — [tristan-lacombe](https://www.linkedin.com/in/tristan-lacombe-734168139/)
- **Portfolio** — [lacombet.fr](https://lacombet.fr)
- **Email** — tlacombevulca@outlook.fr

Le code des projets privés peut être présenté sur demande, démonstration à l'appui.

---

<details>
<summary><b>🇬🇧 English version</b></summary>

<br>

**Full-Stack Developer · PhD in Earth Sciences**

I build web applications that make scientific and geospatial data usable — from the data model to
the interface, including tests and deployment.

Currently a **full-stack developer & software tester apprentice at MSInsight** (in-vitro diagnostic
medical device, ISO 13485 / IEC 62304). I am looking for a role at the intersection of
**software, data and geosciences**, in the Lyon area.

### What I do

- **Complete business applications** — authentication, roles and permissions, database migrations,
  documented APIs, reactive interfaces. Not throwaway prototypes: products that actually run.
- **Scientific computing behind a usable interface** — I wrap Python petrology and geochemistry
  libraries in web services so geologists can use them without writing a line of code.
- **Tests and a real CI/CD pipeline** — unit, integration and end-to-end tests, linting, type
  checking and blocking security audits before every deployment.
- **Infrastructure I run myself** — Linux VPS, Docker Compose, Nginx, self-hosted GitHub Actions
  runners, SSH hardening.

### Stack

**Front**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-087EA4?style=flat-square&logo=react&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white) ![React Native](https://img.shields.io/badge/React%20Native-58C4DC?style=flat-square&logo=react&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)


**Back**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Express](https://img.shields.io/badge/Express-404D59?style=flat-square&logo=express&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=flat-square&logo=typeorm&logoColor=white) ![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black) ![Swagger](https://img.shields.io/badge/Swagger-6BA539?style=flat-square&logo=swagger&logoColor=white)


**Quality**

![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Supertest](https://img.shields.io/badge/Supertest-4B5563?style=flat-square) ![Cypress](https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white) ![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=black)


**Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square) ![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)


**Data & GIS**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white) ![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=flat-square&logo=mapbox&logoColor=white) ![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3&logoColor=white) ![Observable](https://img.shields.io/badge/Observable-353E4B?style=flat-square&logo=observable&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)


**Practices** — Agile / Scrum · AI-assisted development (Claude Code) · regulated environments (ISO 13485, IEC 62304)

### Projects

**Petro-Geoch Online Tool (PGeoOT)** · private — Modular web platform for petrology and
geochemistry. Its first module exposes the Python library
[Thermobar](https://github.com/PennyWieser/Thermobar) (thermobarometry, hygrometry) through a
no-code interface: data import, CIPW norm, structural formulae, interactive charts, Excel export.
Turborepo monorepo with three apps — React/Vite/Tailwind front end, NestJS + TypeORM + PostgreSQL
API, and a Python 3.12 FastAPI calculation service. CI runs lint, type checking, Node tests, ruff
and pytest, plus `audit-ci` and `pip-audit` as blocking gates; tag-triggered deployment to a
self-hosted runner. The repository documents a security audit and a GDPR audit.

**My-HRM** · private — Hotel and restaurant management app: room bookings (arrivals, departures,
stayovers, breakfasts), restaurant table planning by room and service, housekeeping tracking, staff
and roles, partner agencies, Stripe subscription. Business rules are enforced server-side rather
than left to the UI: closing days, service time windows, room capacity derived from beds. NestJS +
TypeORM + PostgreSQL + Swagger + Stripe; React + Vite + Tailwind + Radix UI + Zustand + PWA.
Jest/Supertest API tests (unit, controller, e2e) and Vitest on the front end. Docker Compose, SSH
deployment to a VPS.

**[Unofficial GERM API](https://github.com/LacombeTr/volcapi)** · public — REST API serving the
**GERM** (Geochemical Earth Reference Model) dataset as JSON — previously available only as HTML
tables — so web apps and analysis scripts can consume it. TypeScript, Express, Drizzle ORM,
PostgreSQL, Cheerio ingestion, Swagger docs, Jest tests, Docker.

### Background & publications

**PhD in Earth Sciences** (Université Clermont Auvergne, 2020–2023) — Laboratoire Magmas et Volcans.
Thesis: *Basaltic and phonolitic volcanism of Petite-Terre (Mayotte)*, in collaboration with IPGP,
Université Lyon 1 and OVSG. Four field campaigns in Mayotte, geomorphological mapping in QGIS, over
500 samples analysed by electron microprobe, data processing in Python.

**Full-Stack Developer — EQF level 6** (IT-Akademy, Lyon, 2024–2026, apprenticeship).

Peer-reviewed publications:

- Lacombe T., Gurioli L., Di Muro A., Médard E., *et al.* (2024) — Late Quaternary explosive
  phonolitic volcanism of Petite-Terre (Mayotte, Western Indian Ocean). *Bulletin of Volcanology*.
  [10.1007/s00445-023-01697-2](https://doi.org/10.1007/s00445-023-01697-2)
- Michaud-Dubuy A., Komorowski J.-C., Lacombe T., Gurioli L. (2024) — Tephra fallout hazard
  assessment for a hydrovolcanic eruptive scenario in Mayotte. *Scientific Reports*.
  [10.1038/s41598-024-83266-x](https://doi.org/10.1038/s41598-024-83266-x)
- Thivet S., Hess K.-U., Dingwell D. B., *et al.*, Lacombe T., Komorowski J.-C. (2023) — Volatiles
  of the active Mayotte volcanic chain: STA & EGA-MS analysis of volcanic products.
  *Chemical Geology*. [10.1016/j.chemgeo.2022.121297](https://doi.org/10.1016/j.chemgeo.2022.121297)

### Contact

- **LinkedIn** — [tristan-lacombe](https://www.linkedin.com/in/tristan-lacombe-734168139/)
- **Portfolio** — [lacombet.fr](https://lacombet.fr)
- **Email** — tlacombevulca@outlook.fr

Code for the private projects can be walked through on request, with a live demo.

</details>
