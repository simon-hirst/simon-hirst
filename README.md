# Simon Hirst

I write TypeScript and C#. Some Go. Backends, UIs, and the plumbing in between.

**CV:** [Download (DOCX)](https://raw.githubusercontent.com/simon-hirst/cv/main/Simon-Hirst-CV.docx)

---

## Experience

<details>
  <summary><strong>Show experience</strong></summary>

### Freelance — Aug 2024 → present

- **Shopify ↔ ERP stock sync**  
  Node 20, Express, PostgreSQL, Redis. Webhooks with idempotency keys, retries with backoff, outbox pattern for event delivery. k6 perf baseline, GH Actions matrix tests. Docker images pushed with SBOMs.

- **Bookings + payments revamp**  
  Next.js + React with server actions, ASP.NET Core API, EF Core on SQL Server. Stripe Checkout and webhooks, rate limits, session-based CSRF, Playwright e2e. CI caching shaved build times from minutes to seconds.

- **Reporting API + GraphQL gateway**  
  Schema stitching over 5 REST services, Dataloader caching, persisted queries. OpenTelemetry traces to Tempo, metrics to Prometheus, Grafana dashboards keyed to SLOs. Error budgets wired to alert rules.

- **Live visualizer microsite**  
  WebGL2/GLSL scenes reacting to audio over WebSocket. AudioWorklet for analysis, frame budgets under 4 ms with typed arrays and preallocated buffers. Deployed behind NGINX with static caching.

### IBM — Software Engineer (Jul 2021 → Jul 2024)
Containerized IBM MQ for Kubernetes/OpenShift. Owned chart and manifests, helped harden defaults, and made upgrades boring:

- Images and Helm values that behave under real load. Probes, resources, and TLS sane by default.  
- Go utilities that standardize cluster setup, reduce first-run footguns, and validate storage/network policy before rollout.  
- Observability that SREs actually use: queue depth, throughput, memory, and I/O exported to Prometheus, Grafana boards versioned in Git.  
- Worked with customer teams on DR tests and cutover plans, then turned the pain into runbooks and checks.

### Dootrix — Software Engineer (Mar 2020 → Jul 2021)
Shipped user flows and the APIs that feed them:

- .NET 5 + React features with real validation, email flows, and rate limits.  
- Azure Functions and queues to replace manual ops. Clear contracts, useful errors.  
- Tests that stick: xUnit for services, Jest/Playwright for UI, CI gates that block noisy regressions.

### Zupa — Software Engineer (Sep 2019 → Mar 2020)
Payments in anger:

- Checkout in ASP.NET Core with idempotent Stripe flows and safe retries.  
- SQL tuning that removed the slow tail. Background jobs for reconciliation and notifications.  
- Alerts that fire on symptoms, not guesses, and dashboards humans can read.

</details>

---

## Selected projects

- **AI Radio Station v2.0** — 24/7 internet radio with AI DJs, single synced stream, hourly news/weather, chat, requests, and admin controls.  
  Backend: Node 20 + Express + Socket.IO, Piper TTS for DJ lines, yt-dlp + FFmpeg for pre-caching and ReplayGain, SQLite for schedule/history, rotation rules, trivia scrape.  
  Frontend: Next.js, responsive UI, admin dashboard (veto/approve, force skip, logs).  
  Weather via Open-Meteo. Headlines via BBC RSS. Crossfades and stingers handled in the mixer.  
  `TypeScript, Node 20, Express, Socket.IO, Next.js, SQLite, FFmpeg, yt-dlp, Piper TTS`

- **Mesmerize (WebGL2 visualizer)** — shader scenes, audio-reactive transitions, overlay mode, plugin hooks.  
  `TypeScript, WebGL2, GLSL, AudioWorklet, Vite`

- **LemonStand (microservice sketch)** — product, orders, and catalog services, API gateway, queue-backed jobs, local dev with docker-compose.  
  `Node, Express, MongoDB, Redis, RabbitMQ, Docker, K8s scaffold`

- **Quantum-Synth-Ultimate** — experimental visualizer and transport layer for audio experiments.  
  `TypeScript, WebSocket, Web Audio, workerized DSP`

---

## Stack

**Used commercially**

- **Languages:** TypeScript, JavaScript, C#, SQL  
- **Frontend:** React, Next.js, Tailwind, Blazor, Playwright  
- **Backend/APIs:** ASP.NET Core, Node.js, Express, REST, GraphQL, WebSockets  
- **Data:** PostgreSQL, SQL Server, Redis  
- **Messaging/Async:** RabbitMQ, Azure Queues  
- **Payments:** Stripe  
- **Cloud/Infra:** Docker, Docker Compose, Kubernetes, OpenShift, Helm, NGINX, GitHub Actions, Terraform, Azure, AWS  
- **Obs:** OpenTelemetry, Prometheus, Grafana  
- **Testing:** xUnit, Jest, Playwright, k6

**Personal / prototypes**

- **Languages:** Go, Python  
- **Frontend:** WebGL2, GLSL, Socket.IO (client)  
- **Backend/APIs:** Fastify, WebSocket servers  
- **Data:** SQLite, MongoDB, Prisma  
- **Audio/Media:** FFmpeg, yt-dlp, Web Audio API, Piper TTS, NAudio  
- **Ops:** PM2, static exports, small Helm charts

---

## Education

<details>
  <summary><strong>Show education</strong></summary>

**BSc Computer Science — University of Liverpool (2015–2019), 2:1**  
Object detection in OpenCV for project work. Modules: Algorithms, Databases, Distributed Systems, OS, Networks, Software Engineering.

**A-Levels — Isle of Wight College**  
Chemistry A*, Physics A, Mathematics A.

</details>
