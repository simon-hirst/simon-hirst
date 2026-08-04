hey :)

**CV:** [Download (DOCX)](https://raw.githubusercontent.com/simon-hirst/cv/main/Simon-Hirst-CV.docx)  
**LinkedIn:** https://www.linkedin.com/in/simon-hirst-uk

<!--
---

## Experience

<details>
  <summary><strong>Show experience</strong></summary>

### Freelance — Aug 2024 → present

- **Shopify ↔ ERP stock sync**  
  Node 20 (Express), PostgreSQL, Redis. Webhooks with idempotency keys, outbox pattern, and exponential backoff. k6 baselines, GH Actions matrix tests; images pushed with SBOMs. Reduced duplicate updates and caught race conditions before they hit finance.

- **Bookings + payments revamp**  
  Next.js (server actions) + React, ASP.NET Core API, EF Core on SQL Server. Stripe Checkout + webhooks, rate limits, session-based CSRF, Playwright e2e. CI caching took build times from minutes to seconds. Logs and traces made failures boring.

- **Reporting API + GraphQL gateway**  
  Schema stitching over five REST services, Dataloader caching, persisted queries. OpenTelemetry traces to Grafana Tempo; Prometheus metrics with Grafana boards tied to SLOs. Error budgets wired to alert rules so pages only go off when they should.

- **Live visualiser microsite**  
  WebGL2/GLSL scenes reacting to audio over WebSocket. AudioWorklet analysis; frame budget <4 ms via typed arrays + preallocated buffers. Deployed behind NGINX with static caching.

### IBM — Software Engineer (Jul 2021 → Jul 2024)

Containerised IBM MQ on Kubernetes/OpenShift. Owned Helm chart and manifests, hardened defaults, and made upgrades routine.

- Manifests that behave under load (StatefulSets, probes, resources) with TLS and RBAC sane by default.  
- Go utilities to standardise cluster setup and validate storage/network policy before rollout; cut “first message” failures on fresh clusters.  
- Telemetry people actually use: queue depth, throughput, memory, I/O exported to Prometheus; Grafana dashboards versioned in Git.  
- Sat with customers during go-lives (HA, storage, DR tests) and turned the pain into runbooks and checks.

### Dootrix — Software Engineer (Mar 2020 → Jul 2021)

Shipped user flows and the APIs that feed them.

- .NET 5 + React features with real validation, email flows, and rate limits.  
- Azure Functions + queues replacing manual ops. Clear contracts; helpful errors.  
- Tests that stick: xUnit for services, Jest/Playwright for UI; CI gates that block noisy regressions.

### Zupa — Software Engineer (Sep 2019 → Mar 2020)

Payments in anger.

- Checkout in ASP.NET Core with idempotent Stripe flows and safe retries.  
- SQL tuning to cut the slow-query tail; background jobs for reconciliation and notifications.  
- Alerts on symptoms, not guesses, and dashboards humans can read.

</details>

#### Recent Personal Projects

- **Online Radio Station** — (DEVELOPMENT PAUSED) 24/7 internet radio with AI DJs, single synced stream, hourly news/weather, chat, requests, and admin controls.  
  Backend: Node 20 + Express + Socket.IO, Piper TTS for DJ lines, yt-dlp + FFmpeg for pre-caching and ReplayGain, SQLite for schedule/history, rotation rules, trivia scrape.  
  Frontend: Next.js, responsive UI, admin dashboard (veto/approve, force skip, logs).  

---
-->
  Weather via Open-Meteo. Headlines via BBC RSS. Crossfades and stingers handled in the mixer.  
  `TypeScript, Node 20, Express, Socket.IO, Next.js, SQLite, FFmpeg, yt-dlp, Piper TTS` **(repo private while in active dev)**

- **Mesmerize (WebGL2 visualiser)** — shader scenes, audio-reactive transitions, overlay mode, plugin hooks.  
  `TypeScript, WebGL2, GLSL, AudioWorklet, Vite` — **[GitHub](https://github.com/simon-hirst/Mesmerize)**

- **LemonStand (microservice sketch)** — product, orders, and catalogue services, API gateway, queue-backed jobs, local dev with docker-compose.  
  `Node, Express, MongoDB, Redis, RabbitMQ, Docker, K8s scaffold` — **[GitHub](https://github.com/simon-hirst/lemonstand)**
