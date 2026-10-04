<div align="center">

<!-- Animated Typing Headline -->
<a href="https://github.com/ozanggnr">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=800&color=70A5FD&center=true&vCenter=true&multiline=true&width=700&height=80&lines=Hey+there%2C+I%27m+Ozan+G%C3%BCng%C3%B6r+%F0%9F%91%8B;Full-Stack+Developer+%7C+AI+Enthusiast" alt="Typing SVG" />
</a>

<br/>

<!-- Subtitle tagline cycling -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=2500&pause=1000&color=BF91F3&center=true&vCenter=true&width=600&lines=Building+the+Future+with+Code+%F0%9F%9A%80;Deep+Learning+%7C+Blockchain+%7C+Cloud;Open+to+Collaborations+%26+Opportunities;Always+Learning%2C+Always+Growing+%F0%9F%8C%B1" alt="Typing SVG" />

<br/><br/>

<!-- Social badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ozangngr)
[![Website](https://img.shields.io/badge/Website-%2312100E.svg?style=for-the-badge&logo=firefox-browser&logoColor=white)](https://ozangungor.page)
[![Medium](https://img.shields.io/badge/Medium-%2312100E.svg?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@ozanggnr)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ozanggnr@gmail.com)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=ozanggnr&color=70a5fd&style=for-the-badge&label=Profile+Views)

</div>

---

## 🧑‍💻 About Me

```yaml
name: Ozan Güngör
role: Full-Stack Developer
location: Ankara, Turkey 🇹🇷
university: Bilkent University — Information Systems & Technologies

currently_learning:
  - 🤖 Deep Learning & Machine Learning
  - ⛓️ Blockchain & Web3
  - ☁️ Cloud & DevOps

interests:
  - Building scalable full-stack applications
  - Experimenting with AI/ML models
  - Contributing to open-source projects
  - Every sport in the world ⚽🏀🏊

```

---

## 🛠️ Featured Projects & Technical Deep-Dives

Here is a curated selection of major projects spanning different programming paradigms, languages, and architectures — from AI-driven full-stack platforms and mobile applications to systems programming and empirical data science:

---

### 1. 🐺 Wolfee Analytics — Financial Intelligence & Stock Scanner
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-Framework-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://postgresql.org)
[![Railway](https://img.shields.io/badge/Deploy-Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)](https://railway.app)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-wolfee--analytics.up.railway.app-success?style=flat-square&logo=render)](https://wolfee-analytics.up.railway.app/)

> **Full-stack financial analysis platform providing real-time dual-market tracking, algorithmic opportunity scanning, and AI-driven daily intelligence.**

<p align="center">
  <img src="https://raw.githubusercontent.com/ozanggnr/wolfee-analytic/main/frontend/logo.png" alt="Wolfee Analytics" width="520" />
</p>

* **Dual-Market Aggregation Engine**: Seamlessly tracks top liquid stocks from both **Borsa Istanbul (BIST 100)** and **US Global Markets** (Tech, Pharma, Energy), alongside precious metals (Gold, Silver, Copper) and exchange rates.
* **Algorithmic Indicator & Scanner Pipeline**: Asynchronously computes **RSI (14-day)**, **20-day SMA**, and price volatility risk bands. An opportunity engine scans for favorable entry setups (e.g., oversold pullbacks during macro uptrends).
* **Multi-Tier Caching & Failover Routing**: Built on FastAPI with a resilient scraping router that automatically fails over across market data providers (Yahoo Finance, Google Finance, Finnhub) with progressive client loading (`Quick Load` -> background sync).
* **Hardened Security Architecture**: Enterprise-grade authentication with bcrypt (cost factor 12), sliding-window per-IP rate limiting, anti-enumeration responses, exponential backoff lockout defense, and strictly `HttpOnly SameSite=Strict` cookie session revocation.
* **Reporting**: Automated Excel export system generating professional daily, weekly, and custom portfolio breakdown reports.

🔗 **Repository:** [github.com/ozanggnr/wolfee-analytic](https://github.com/ozanggnr/wolfee-analytic) · 🌐 **Live App:** [wolfee-analytics.up.railway.app](https://wolfee-analytics.up.railway.app/)

---

### 2. 📦 BestBefore — Digital Memory Box Platform
[![JavaScript](https://img.shields.io/badge/JavaScript-ES2024-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38BDF8?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-Parallax-EA4C89?style=flat-square&logo=framer&logoColor=white)](https://framer.com/motion)
[![Senior Project](https://img.shields.io/badge/Bilkent_CTIS-Senior_Design_2026-003366?style=flat-square)](https://bilkent.edu.tr)

> **Bilkent University Senior Design Project: A mobile and web platform preserving memories as context-rich "Digital Memory Boxes" rather than ephemeral social media feeds.**

<p align="center">
  <img src="https://raw.githubusercontent.com/ozanggnr/bestbeforewebsite/main/public/app-screen.png" alt="BestBefore App Screen" width="370" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/ozanggnr/bestbeforewebsite/main/public/room-screen-1.png" alt="BestBefore Memory Room" width="370" />
</p>

* **The Problem**: Conventional social media favors fleeting algorithmic attention and disappearing stories, dispersing memories across disconnected feeds.
* **Contextual Memory Rooms**: BestBefore introduces permanent digital capsules ("Rooms") with fine-grained access control, QR-code invites, and multi-user photo and narrative contributions.
* **AI Semantic Search & Discovery**: Backed by Python microservices using OpenAI 1536-dimensional vector embeddings (`gpt-4o-mini`) and cosine similarity to cluster memories, match interconnected rooms, and surface memories contextually.
* **Real-time Mobile Synchronization**: Instant live synchronization using Firebase Cloud Messaging (FCM) paired with an Express/Node.js API gateway and MongoDB Atlas.
* **Interactive Web Platform**: High-performance showcase website engineered with React 18, Vite, Tailwind CSS, custom glassmorphism design system, and Framer Motion parallax transitions.

🔗 **Repository:** [github.com/ozanggnr/bestbeforewebsite](https://github.com/ozanggnr/bestbeforewebsite)

---

### 3. 🎓 Campus App (Bilkent Campus) — Hyper-Local Campus Activity Hub
[![Status](https://img.shields.io/badge/Status-Actively_Developing_🔨-FFA500?style=flat-square)](#)
[![React Native](https://img.shields.io/badge/React_Native-Expo-61DAFB?style=flat-square&logo=react&logoColor=black)](https://reactnative.dev)
[![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org)
[![PostgreSQL](https://img.shields.io/badge/DB-SQLite_%7C_PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://postgresql.org)
[![Firebase](https://img.shields.io/badge/Auth-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://firebase.google.com)

> **A secure, university-tailored social activity and campus life platform designed specifically for Bilkent University students to connect spontaneously.**

* **Currently in Active Development**: Developing both the native mobile frontend with React Native (Expo) and the modular Node.js REST API backend.
* **Verified Campus Community**: Enforces university domain verification (`@ug.bilkent.edu.tr`) to guarantee a trusted, student-only environment free of outside spam.
* **Dynamic Activity Creation & Matching**: Enables students to initiate spontaneous coffee meetups, library study groups, sports matches, and club events with category filtering and participant limits.
* **Campus Coordinate Engine**: Integrates official Bilkent campus building codes, coordinates, and navigation landmarks directly with the activity feed.
* **Dual-Engine Persistence**: Features an abstraction database adapter supporting embedded SQLite for rapid local testing and PostgreSQL for production concurrency, with full suite integration tests.
* **UX & Localization**: Complete bilingual support (English 🇬🇧 / Turkish 🇹🇷) with theme switching (Light / Dark mode) and haptic response.

---

### 4. 📊 Data Analysis of Chess — Statistical Modeling & Game Analytics
[![R](https://img.shields.io/badge/R-Statistical_Computing-276DC3?style=flat-square&logo=r&logoColor=white)](https://www.r-project.org)
[![ggplot2](https://img.shields.io/badge/ggplot2-Data_Visualization-1A73E8?style=flat-square)](https://ggplot2.tidyverse.org)
[![EDA](https://img.shields.io/badge/Analysis-Exploratory_Data_Analysis-orange?style=flat-square)](#)

> **Empirical statistical analysis investigating decisive outcome factors, opening repertoires, and chess engine rating evolution across decades.**

<p align="center">
  <img src="https://raw.githubusercontent.com/ozanggnr/Data-Analysis-of-Chess/main/365%20data%20%2Cphotos/of_chess_matches.png" alt="Chess Matches Outcome Distribution" width="370" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/ozanggnr/Data-Analysis-of-Chess/main/365%20data%20%2Cphotos/chessEngines.png" alt="Chess Engines Rating Evolution" width="370" />
</p>

* **Hypothesis Testing & Statistical Rigor**: Formulated and tested statistical hypotheses concerning white-piece first-move advantage, draw rates across rating brackets, and decisive outcome drivers.
* **Decadal Rating Progression**: Tracked and modeled historical rating trends of modern chess engines (Stockfish, Komodo, Houdini, Deep Blue) against grandmaster benchmarks over the 1970–2020 timeframe.
* **Visualization Suite**: Programmed custom **lollipop charts**, frequency distribution tables, and cumulative variance plots using R and visualization libraries.
* **Data Processing Pipeline**: Cleaned, filtered, and parsed large raw match datasets into tidy statistical structures for reproducible research and academic publication.

🔗 **Repository:** [github.com/ozanggnr/Data-Analysis-of-Chess](https://github.com/ozanggnr/Data-Analysis-of-Chess)

---

### 5. ☕ Food Ordering System — Object-Oriented Desktop Management Suite
[![Java](https://img.shields.io/badge/Java-OOP_Architecture-ED8B00?style=flat-square&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Java Swing](https://img.shields.io/badge/GUI-Swing_%7C_AWT-5382A1?style=flat-square)](https://docs.oracle.com/javase/tutorial/uiswing/)
[![Design Patterns](https://img.shields.io/badge/Architecture-Clean_OOP_%7C_Interfaces-green?style=flat-square)](#)

> **A desktop restaurant order lifecycle and billing application architected with clean Java object-oriented principles and event-driven Swing GUI.**

* **Strict OOP Architecture**: Built around strict encapsulation, inheritance hierarchies (`People` base class inherited by polymorphic `Customer` and `Worker` classes), and interface-driven design.
* **Polymorphic Billing Engine**: Implements `DiscountInterface` to decouple pricing strategy from checkout, allowing dynamic computation of seasonal promotions, VIP discounts, and worker allowances.
* **Multi-Window Navigation**: Event-driven architecture with clean frame transitions across `MainFrame`, `AddOrderFrame`, `AddRemoveFrame`, `SearchFrame`, and `DisplayFrame`.
* **In-Memory Data System (`PeopleSys`)**: Centralized system manager handling search lookups, real-time cart mutations, address resolution, and order dispatching.

🔗 **Repository:** [github.com/ozanggnr/Food-Ordering-System-](https://github.com/ozanggnr/Food-Ordering-System-)

---

### 6. 🚀 Space Game — 2D Arcade Engine & Vector Physics Simulation
[![C++](https://img.shields.io/badge/C++-ISO_Standard-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)](https://isocpp.org)
[![OpenGL](https://img.shields.io/badge/Graphics-OpenGL_%2F_GLUT-5586A4?style=flat-square&logo=opengl&logoColor=white)](https://www.opengl.org)
[![Physics](https://img.shields.io/badge/Math-Vector_2D_Physics-red?style=flat-square)](#)

> **A real-time 2D space action game engineered in C++ emphasizing vector mathematics, custom collision physics, and game-loop performance.**

* **Custom Vector Mathematics**: Handcrafted 2D coordinate calculations (`vec` math structures) for spaceship thrust, velocity acceleration, friction decay, and projectile trajectory angles.
* **Optimized Collision System**: Real-time bounding-box and circular collision detection routines calculating intersections between high-velocity laser projectiles and celestial hazards.
* **Deterministic Game Loop**: Fixed-timestep update and rendering loop separating physics simulation from graphics rasterization for smooth frame pacing.
* **Direct Hardware Event Handling**: Low-overhead keyboard polling and mouse directional aiming implemented via GLUT/OpenGL callbacks for responsive tactile gameplay.

🔗 **Repository:** [github.com/ozanggnr/Space-Game](https://github.com/ozanggnr/Space-Game)

---

## 📈 Activity Graph

<div align="center">

[![Ozan GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=ozanggnr&theme=tokyo-night&hide_border=true&area=true)](https://github.com/ozanggnr)

</div>

---

## 🌐 Let us Connect

<div align="center">

| Platform | Link |
|---|---|
| 🌍 **Website** | [ozangungor.page](https://ozangungor.page) |
| 💼 **LinkedIn** | [linkedin.com/in/ozangngr](https://linkedin.com/in/ozangngr) |
| ✍️ **Medium** | [medium.com/@ozanggnr](https://medium.com/@ozanggnr) |
| 📧 **Email** | [ozanggnr@gmail.com](mailto:ozanggnr@gmail.com) |

</div>


