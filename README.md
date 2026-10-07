<div align="center">

# Rehan Illahi

### Full-Stack Software Developer
**Mobile · Android TV · Web · SaaS · AI & Data · Business Systems**

I design and build complete software products: Flutter apps on Google Play, Android TV experiences, full-stack web platforms, AI-enabled tools and internal business systems.

[![Portfolio](https://img.shields.io/badge/Portfolio-rehan--illahi.vercel.app-0A66C2?style=for-the-badge&logo=vercel&logoColor=white)](https://rehan-illahi.vercel.app/)
[![All Repositories](https://img.shields.io/badge/GitHub-All%20Projects-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rehann199?tab=repositories)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mrehanilahi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mrehanilahi)
[![Stack Overflow](https://img.shields.io/badge/Stack%20Overflow-Rehan%20Ilahi-F58025?style=for-the-badge&logo=stackoverflow&logoColor=white)](https://stackoverflow.com/users/33178831/rehan-ilahi)

</div>

---

## About

I build software across the full product lifecycle: architecture and UI, development, integrations, testing and release. My public work covers:

- **Full-stack web applications** and SaaS-style products
- **Flutter mobile apps**, several of them live on Google Play
- **Android TV apps** with D-pad focus navigation and remote-first interaction
- **AI-powered applications**: retrieval-augmented assistants, NLP pipelines and ML-based estimation
- **Custom business software**: ledgers, dashboards and operations tools
- **Backends and APIs** on FastAPI, Express, Django, Cloudflare Workers and Firebase

Every project below links to a repository with a README, screenshots and architecture notes.

## What I Build

| | |
|---|---|
| **Web & SaaS** | Full-stack applications, marketing and company sites, admin consoles, dashboards, REST APIs, payment flows (Stripe Checkout) |
| **Mobile & TV** | Flutter apps for Android and iOS, Android TV and Fire TV builds, native Kotlin and Swift bridges, in-app purchases |
| **AI & Data** | LLM-assisted learning tools, retrieval-augmented assistants, OCR and NLP classification, analytics and data-visualisation dashboards |
| **Business Software** | Accounting and ledger systems, ticketing and booking platforms, fleet and delivery dashboards, Excel-to-database migrations |
| **MVP & Product Engineering** | Prototypes through to store-published products, Firebase / Supabase / Cloudflare integration, authentication, subscriptions |

---

## Featured Work

### Kalendra: AI scheduling assistant
Kalendra is a calendar assistant that lets people view, create and adjust events through conversation. It is built as **two distinct projects**:

| Project | What it is | Stack | Links |
|---|---|---|---|
| **Kalendra AI** (the app) | Cross-platform calendar client: unified Google and Outlook accounts, day / week / month / schedule views, overlap-aware layout, and an in-app assistant that proposes actions the user confirms before anything is written. | Flutter · Dart · Firebase Auth · OAuth calendar connect | [Source](https://github.com/rehann199/kalendra-ai) · [Google Play](https://play.google.com/store/apps/details?id=com.calendai.calendai) |
| **Kalendra Website** | Public landing and early-access site with a waitlist form, hand-built SVG / CSS / GSAP animation and in-page legal notices. | React · Vite · GSAP · EmailJS · Netlify | [Source](https://github.com/rehann199/kalendra-website) · [Live site](https://getkalendra.com/) |

**Engineering:** streamed assistant turns with a hard confirmation boundary before destructive actions, centralised OAuth token refresh across multiple accounts, partial vs. full overlap conflict layout, and widget tests around conflicts and confirmations.

### Hearthboard: split-flap social board
A social app for very short messages: friends see posts in-app and on a split-flap-styled home-screen widget. An Android TV companion pairs by QR for ambient display *(engineering build, not publicly released)*.

- **Stack:** Flutter · Dart · Kotlin · Swift · Firebase · Play Billing · StoreKit · Cloudinary
- **Engineering:** native home-screen widgets rendered from off-screen Flutter layouts, Firestore-backed social graph (friends, blocks, reactions), tiered subscriptions, push notifications via serverless handler
- [Source](https://github.com/rehann199/hearthboard) · [Google Play](https://play.google.com/store/apps/details?id=com.hearthboard.hearthboard)

### Al Noor: construction ledger ERP
A web ledger for a construction company that replaces an Excel workbook: a Main Ledger of payments and receipts with Head, Item, Merchant and Account drill-downs showing billed, paid and due.

- **Stack:** React · Vite · Tailwind · Cloudflare Workers · Hono · Drizzle · D1 (SQLite)
- **Engineering:** integer-minor-unit money handling, derived due amounts rolled up across sub-ledgers, JWT sign-in with a read-only role, audit log, and a verified Python Excel-import pipeline
- [Source](https://github.com/rehann199/al-noor) · [Live app](https://app-eight-brown-88.vercel.app/login)

### AI-LMS: learning platform with grounded AI tools
A learning management system where instructors and students get AI tools grounded in the course's own material: quizzes, assignments, summaries, flashcards, practice questions and lecture chat.

- **Stack:** Next.js · React · TypeScript · FastAPI · LangGraph · Supabase (Postgres + pgvector) · Llama models
- **Engineering:** generate-verify-regenerate LangGraph pipelines with instructor feedback, hybrid keyword + vector retrieval scoped to selected documents, LoRA fine-tuned verifier model
- [Source](https://github.com/rehann199/ai-lms)

---

## Selected Projects

| Project | What it does | Stack / Platform | Links |
|---|---|---|---|
| **Price-Matic** | Mobile appliance marketplace: compare new appliances, trade used ones with seller chat, get an ML price estimate. | React Native · Expo · Supabase · FastAPI · scikit-learn | [Source](https://github.com/rehann199/price-matic) |
| **Research-Assistant-X** | AI research-paper recommender with a trends dashboard, retrieval-augmented assistant and citation-graph explorer. | Python · Streamlit · Prefect · PostgreSQL · Milvus · Dgraph · Gemini | [Source](https://github.com/rehann199/research-assistant-x) |
| **Event-Nest** | Event ticket booking: search events, pay with Stripe Checkout, receive QR e-tickets; organiser tools and sales analytics. | React · Express · MongoDB · Stripe · Tailwind | [Source](https://github.com/rehann199/event-nest) |
| **AGRO-SCAN** | Crop-health scanning from a canopy photo: colour-health score, stress heatmap and rule-based next steps. | FastAPI · SQLite · Pillow · NumPy · Chart.js | [Source](https://github.com/rehann199/agro-scan) |
| **Docu-Scan** | Legal document classification and search: OCR intake, NLP tagging by case type and urgency, full-text search. | FastAPI · spaCy · Tesseract · Elasticsearch · Docker Compose | [Source](https://github.com/rehann199/docu-scan) |
| **Code-Spark** | Gamified coding-practice platform with a browser editor, XP, streaks and leaderboard. | Django · DRF · Celery · Redis · Judge0 | [Source](https://github.com/rehann199/code-spark) |
| **FinFlow** | Finance analytics dashboard for transaction monitoring and fraud detection, built around a Kafka / Spark / PostgreSQL streaming design. The included demo runs on generated sample data. | Python · Streamlit · Kafka · PySpark · PostgreSQL · scikit-learn | [Source](https://github.com/rehann199/fin-flow) |
| **Fleet-Track** | Courier and fleet dashboard concept: map, deliveries, vehicles, drivers and analytics in one interface. | JavaScript · Leaflet · Chart.js · Express · Socket.IO | [Source](https://github.com/rehann199/fleet-track) |
| **Edul-Insights** | Academic analytics dashboard surfacing at-risk students, performance trends and suggested interventions. | Python · Dash · Plotly · pandas · scikit-learn | [Source](https://github.com/rehann199/edul-insights) |
| **Mood Screen** | Ambient video app that turns a phone or Android TV into a calm display, with weather-matched scenes, clock overlay and dimming. | Flutter · Riverpod · Kotlin · Android TV & phone | [Source](https://github.com/rehann199/mood-screen) |

[**View all projects →**](https://github.com/rehann199?tab=repositories) · [**Full portfolio →**](https://rehan-illahi.vercel.app/)

---

## Published Products

A selection of apps with public Google Play listings (the full catalogue is on the [portfolio](https://rehan-illahi.vercel.app/)):

| App | What it is | Platform | Links |
|---|---|---|---|
| **Kalendra** | AI calendar assistant | Android · iOS code base | [Play Store](https://play.google.com/store/apps/details?id=com.calendai.calendai) · [Source](https://github.com/rehann199/kalendra-ai) |
| **Hearthboard** | Split-flap social board with home-screen widgets | Android | [Play Store](https://play.google.com/store/apps/details?id=com.hearthboard.hearthboard) · [Source](https://github.com/rehann199/hearthboard) |
| **Smart Transfer** | Phone-to-phone file mover over local Wi-Fi | Android | [Play Store](https://play.google.com/store/apps/details?id=com.futurewatch.smarttransfer) · [Source](https://github.com/rehann199/smart-transfer) |
| **Tranquil** | Ambient video and sound app, five platform builds from three codebases | Mobile · Android TV | [Play Store](https://play.google.com/store/apps/details?id=com.tranquil.androidtv) · [Source](https://github.com/rehann199/tranquil) |
| **2D Turbo Racing** | Top-down racing game with cloud-synced progress | Mobile · Android TV | [Play Store](https://play.google.com/store/apps/details?id=co.futurewatch.turborg2d.racing) · [Source](https://github.com/rehann199/2d-turbo-racing) |
| **Doc Reader** (DocReader Pro) | Document reader, scanner with on-device OCR and PDF toolbox | Android | [Play Store](https://play.google.com/store/apps/details?id=com.docreader.pro) · [Source](https://github.com/rehann199/doc-reader) |
| **Ledgerwise** | Local-first expense tracker with analytics and export | Android | [Play Store](https://play.google.com/store/apps/details?id=com.ledgerwise.app) · [Source](https://github.com/rehann199/ledgerwise) |
| **PulseBP** | Local-first blood-pressure logging with trends and reports | Android | [Play Store](https://play.google.com/store/apps/details?id=co.futurewatch.pulsebp) · [Source](https://github.com/rehann199/pulsebp) |
| **Loan EMI** | Loan calculator with amortisation schedule and 15 interface languages | Android | [Play Store](https://play.google.com/store/apps/details?id=co.futurewatch.emicalculator) · [Source](https://github.com/rehann199/loan-emi) |

---

## Technology Stack

Technologies below are the ones used across the projects above.

**Languages**
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)

**Frontend & Mobile**
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Backend & APIs**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-404040?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)

**Data & Cloud**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

**AI & Data Science**
![LangGraph](https://img.shields.io/badge/LangChain%20%2F%20LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

---

## Available for Software Projects

I take on complete software products as well as focused development engagements, from MVPs and mobile apps to web platforms, AI-enabled tools and internal business systems.

Project types my portfolio supports:

- Flutter apps for Android and iOS, including Android TV versions
- Full-stack web applications and company or product websites
- Dashboards, admin consoles and data-visualisation tools
- AI-assisted features such as retrieval-augmented assistants and document processing
- Business and accounting software, including migration from spreadsheets
- Enhancing or extending an existing app, plus Firebase, Supabase, Stripe and API integrations

<div align="center">

[![View Portfolio](https://img.shields.io/badge/View%20Portfolio-0A66C2?style=for-the-badge&logo=vercel&logoColor=white)](https://rehan-illahi.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-rehann199-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rehann199)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mrehanilahi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mrehanilahi)
[![Stack Overflow](https://img.shields.io/badge/Stack%20Overflow-Rehan%20Ilahi-F58025?style=for-the-badge&logo=stackoverflow&logoColor=white)](https://stackoverflow.com/users/33178831/rehan-ilahi)

To discuss a project, get in touch through the [portfolio](https://rehan-illahi.vercel.app/) or [LinkedIn](https://www.linkedin.com/in/mrehanilahi).

</div>
