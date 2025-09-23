# Simon Hirst

**CV:** [Download (DOCX)](https://raw.githubusercontent.com/simon-hirst/cv/main/Simon-Hirst-CV.docx)

## Experience

<details>
  <summary><strong>Show experience</strong></summary>

  
  ### Now — Freelance (Aug 2024 → present)
  I’ve been taking small to mid-sized builds from kickoff to production. React front ends with real form handling and error states. Node and .NET services with sane auth, input validation, and predictable pagination. PostgreSQL tuned with composite indexes where it matters, Redis on hot paths, and background workers for anything that shouldn’t block a request. CI/CD in GitHub Actions so tests and container builds are quick and deploys roll out behind health checks. Queue-backed jobs replaced brittle nightly scripts, so retries and idempotency are simply how the system works. OpenTelemetry with Prometheus/Grafana added traces and dashboards tied to SLOs; when traffic spikes, p95 stays calm and incidents are boring.

  ### IBM — Software Engineer (Jul 2021 → Jul 2024)
  I worked on the containerised edition of IBM MQ across Kubernetes and OpenShift. The focus was making supported topologies predictable under real traffic: images packaged with sensible defaults, manifests that behave (StatefulSets, probes, resources), and runbooks that match what operators actually see. I wrote small Go tools that standardised cluster setup and removed the common foot-guns, which cut “first message” failures on new clusters. I sat with customers during rollouts to get TLS, storage, network policies, and disaster-recovery rehearsals right, then fed that learning back into scripts and docs. We added the telemetry people needed (queue depth, throughput, memory, storage IOPS), tightened secure defaults with RBAC and secrets handling, and improved release hygiene so upgrades became routine rather than risky.

  ### Dootrix — Software Engineer (Mar 2020 → Jul 2021)
  I shipped onboarding flows in .NET Core and React that people actually completed. Adding email verification, rate limiting, and clearer validation took a lot of noise out of support. I built REST endpoints and the small client pieces the front end needed, with request validation and useful error responses. I automated CRM sync with Azure Functions, webhooks, and queues, which removed manual entry and saved real hours every month. Test-first habits with xUnit, Jest, and Playwright pushed coverage into the 90s and cut rollbacks. With logs, traces, and straightforward dashboards in place, PMs could see where users were falling off and prioritise fixes that moved the needle.

  ### Zupa — Software Engineer (Sep 2019 → Mar 2020)
  I worked on high-traffic checkout in .NET Core handling seven-figure monthly volume. We integrated Stripe with idempotent payment flows, clear error handling, and safe retries; payment processing ran at roughly four-nines uptime. I tuned SQL with the right indexes and query shapes, fixed connection-pooling issues, and cut the slow-query tail. I wrote background jobs for reconciliation and notifications, and added monitoring and alerts so issues surfaced early. We kept PRs small, shipped often, and documented edge cases so handovers stuck.

</details>

## Stack

C#/.NET, TypeScript/Node, React, SQL/EF Core, PostgreSQL, Redis, Docker, Kubernetes/OpenShift, AWS/Azure, GitHub Actions, Playwright, xUnit, Prometheus, Grafana, OpenTelemetry.

## Education

<details>
  <summary><strong>Show education</strong></summary>

  
  **BSc Computer Science — University of Liverpool (2015–2019), 2:1**  
  Project: real-time object detection with OpenCV (C++), experimenting with feature descriptors and basic tracking.  
  Modules: Algorithms & Data Structures; Databases; Distributed Systems; Operating Systems; Networks; Software Engineering.  
  Extras: hackathons and small utilities/scrapers; lab demonstrator for first-year programming workshops.

  **A-Levels — Isle of Wight College (2013–2015)**  
  Chemistry A*, Physics A, Mathematics A.
</details>
