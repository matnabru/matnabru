# Matnabru // Mateusz Urbanek

Fullstack engineer specializing in AI-native systems and high-performance architectures. I build things that have to stay up — event-driven pipelines, low-latency data layers, and the occasional C++ simulation engine at midnight.

I just like building things. Finance trackers, game engines, hardware experiments, self-hosted infrastructure — the domain doesn't matter much as long as the problem is interesting.

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

#### 🎮 [10,000 Spirits](https://github.com/matnabru/immortal-architect) // Simulation Engine
A xianxia RPG built on a custom C++ GDExtension simulation layer inside Godot 4.
* **Architecture:** Three-tier stack — C++ GDExtension → C# game systems → Godot multimesh rendering.
* **Performance:** Data-parallel ECS simulating 10,000+ active entities in real time.
* **Tooling:** In-engine WorldCreator with a command palette UI. All world content authored from within the game.

#### 📈 [Asset-Tracker](https://github.com/matnabru/asset-tracker) // Real-time Wealth Engine
Data ingestion engine for unified portfolio state across fragmented financial markets.
* **Integrations:** Interactive Brokers (Stocks/Options), PKO BP (Open Banking/PSD2), Binance/Bybit (WebSockets).
* **Challenge:** Merging high-frequency WebSocket streams with asynchronous, rate-limited Banking APIs into a single low-latency query layer.
* **Stack:** Node.js, TypeScript, Redis, MongoDB.

#### 🌐 [BetBros](https://github.com/matnabru/betbros-betting-bot) // Discord Betting Bot
Built in a day for live football watch parties with friends. Scrapes today's fixtures via proxy rotation, pulls live event odds from a dedicated API, and tracks user predictions and scores in MongoDB.

---

### 🔗 Connect
[mateuszurbanek.com](https://mateuszurbanek.com) • [LinkedIn](https://www.linkedin.com/in/mateusz-urbanek-427559201)
