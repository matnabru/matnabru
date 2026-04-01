# Matnabru // Mateusz Urbanek

Fullstack engineer specializing in AI-native systems, multi-agent workflows, and high-performance architectures. I build things that have to stay up: event-driven pipelines, low-latency data layers, developer tooling, and the occasional C++ simulation engine at midnight.

I like building systems where orchestration, state, and performance actually matter. Finance trackers, game engines, self-hosted infrastructure, weird automation projects — the domain changes, the fun part doesn't.

**Matnabru** is my personal scratchpad: the stuff that doesn't make it into a Jira ticket.

---

### 💼 The Day Job

* **Orange Polska** // Fullstack Engineer, AI Engineering & Automation — Building web/mobile apps and microservices that integrate AI orchestration, STT/TTS pipelines, and enterprise APIs (Microsoft 365, OAuth 2.0) into production-grade internal tooling.
* **Aexol** // Software Engineer — Outsourced across multiple client projects (3–5 months each), building and expanding products across different domains and stacks. Highlights: eliminated Stripe rate-limit bottlenecks via event-driven sync (Webhooks + MongoDB), increasing read throughput 200×; contributed to bare-metal K8s migration (Hetzner), significantly reducing infrastructure OPEX.
* **Deloitte** // Salesforce Intern — Where the first commit happened (2021).

### 🛠 The Stack

* **Primary:** TypeScript (Node.js/Next.js/NestJS), Python (AI/Automation/Lazy side projects), C++ (low-level, heavily optimized systems).
* **Infrastructure:** Kubernetes, Docker, GCP/AWS (Serverless & Event-driven), Linux Internals.
* **Data & AI:** Postgres/Mongo/Firebase for the truth, Redis/Valkey for the speed, RAG pipelines, Vector DBs, GraphQL/Swagger for the interface.

---

### 📂 Projects

#### 🌍 [LeetCode World](https://github.com/matnabru/leetcode-world) // Multi-Agent Learning System
A Google ADK + A2A-powered LeetCode learning system that routes between cached knowledge, similarity search, explanation, and fresh multi-agent solving workflows.
* **Architecture:** Hybrid policy layer over a deterministic `Parser → Architect → Coder → Librarian` execution path.
* **State:** Persists solved problems, pattern notes, and similarity links into an Obsidian-backed knowledge base with ChromaDB.
* **Tooling:** Distributed A2A services, inspectable Agent Cards, ADK Web observability, and a clean dev workflow for tracing multi-agent runs.

#### 🏢 [Pale Office](https://github.com/matnabru/immortal-architect) // Automation Tower Defense
A darkly comic factory builder / tower defense game about a burned-out grim reaper managing a bureaucratic afterlife skyscraper.
Private repo — code walkthrough available on request.
* **Architecture:** Three-tier game stack — C++ GDExtension simulation layer → C# gameplay systems → Godot rendering and tools.
* **Systems:** Vertical floor-by-floor factory building, drafted soul-wave defense, workforce recruitment from defeated enemies, and persistent office infrastructure across failed runs.
* **Tooling:** In-engine worldbuilding and simulation tooling designed to author large, highly systemic game spaces from inside the game itself.

#### 📈 [Asset-Tracker](https://github.com/matnabru/asset-tracker) // Real-time Wealth Engine
Data ingestion engine for unified portfolio state across fragmented financial markets.
Private repo — code walkthrough available on request.
* **Integrations:** Interactive Brokers (Stocks/Options), PKO BP (Open Banking/PSD2), Binance/Bybit (WebSockets).
* **Challenge:** Merging high-frequency WebSocket streams with asynchronous, rate-limited Banking APIs into a single low-latency query layer.
* **Stack:** Node.js, TypeScript, Redis, MongoDB.

#### 🌐 [BetBros](https://github.com/matnabru/betbros-betting-bot) // Discord Betting Bot
Built in a day for live football watch parties with friends. Scrapes today's fixtures via proxy rotation, pulls live event odds from a dedicated API, and tracks user predictions and scores in MongoDB.

---

### 🔗 Connect
[mateuszurbanek.com](https://mateuszurbanek.com) • [LinkedIn](https://www.linkedin.com/in/mateusz-urbanek-427559201)
