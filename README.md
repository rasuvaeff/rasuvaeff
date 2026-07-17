<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3200&pause=900&color=777BB4&center=true&vCenter=true&width=680&lines=Backend+Engineer+%E2%80%94+PHP+%2F+Yii3;High-load+services+and+ad-tech+(RTB);Clean+Architecture+%C2%B7+DDD+%C2%B7+CQRS;49+open-source+packages+on+Packagist;LLM+integration+via+MCP" alt="Backend Engineer — PHP / Yii3" />

<br>

![Experience](https://img.shields.io/badge/7%2B%20Years-Experience-777BB4?style=for-the-badge)
![Open To Work](https://img.shields.io/badge/Open%20To%20Work-4c1?style=for-the-badge)
![Made with PHP](https://img.shields.io/badge/Made%20with-PHP%208.5-777BB4?style=for-the-badge&logo=php&logoColor=white)
[![Packagist](https://img.shields.io/badge/Packagist-49%20packages-F28D1A?style=for-the-badge&logo=packagist&logoColor=white)](https://packagist.org/packages/rasuvaeff/)

![Profile views](https://komarev.com/ghpvc/?username=rasuvaeff&style=flat-square&color=777BB4&label=profile+views)

</div>

---

### 👨‍💻 About

Backend engineer with 7+ years of commercial PHP. I design and build high-load services and APIs — and I publish the reusable parts as open source.

- **5+ years in ad-tech**: an advertising network with RTB (Real-Time Bidding) integrations, buying and selling traffic — MySQL for operational data, ClickHouse for impression analytics, Redis/Memcached for caching.
- **Now**: product development on Yii3 / PHP 8.5 with Clean Architecture (Domain / Application / Infrastructure / Endpoint, boundaries enforced statically by Deptrac), plus support and refactoring of large Yii2 legacy systems.
- **LLM in production**: the application acts as an MCP server — assistants connect over Model Context Protocol and call domain tools via tool-calling, guarded by per-user RBAC and an audit log.
- I care about the things that are invisible until they break: retries, idempotency, exactly-once delivery, backpressure, mutation-tested code.

---

### ⚡ Tech Stack

**Languages**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**Frameworks**

![Yii3](https://img.shields.io/badge/Yii3-40B3D2?style=for-the-badge&logo=yii&logoColor=white)
![Yii2](https://img.shields.io/badge/Yii2-40B3D2?style=for-the-badge&logo=yii&logoColor=white)
![PSR](https://img.shields.io/badge/PSR%20standards-8892BF?style=for-the-badge&logo=php&logoColor=white)

**Data**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Memcached](https://img.shields.io/badge/Memcached-3D5A80?style=for-the-badge)

**Infrastructure & Real-time**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Centrifugo](https://img.shields.io/badge/Centrifugo%20%2F%20WebSocket-1B1F23?style=for-the-badge)

**Quality**

![Psalm](https://img.shields.io/badge/Psalm-2D2D2D?style=for-the-badge)
![Testo](https://img.shields.io/badge/Testo-testing%20framework-00A3A3?style=for-the-badge)
![Infection](https://img.shields.io/badge/Infection-mutation%20testing-8A2BE2?style=for-the-badge)
![Rector](https://img.shields.io/badge/Rector-6E4C13?style=for-the-badge)
![Deptrac](https://img.shields.io/badge/Deptrac-3B5998?style=for-the-badge)

---

### 📦 Open Source — [49 packages on Packagist](https://packagist.org/packages/rasuvaeff/)

Reusable PHP 8.3+ libraries with hardened CI/CD, SemVer, backward-compatibility checks, and tests on [Testo](https://php-testo.github.io) with mutation testing (MSI 85–100%).

| Package | What it does | |
|---|---|---|
| [**bulkhead**](https://github.com/rasuvaeff/bulkhead) | Cross-process concurrency limiter for PHP-FPM — keeps one slow upstream from eating every worker. Atomic slot acquisition via Redis Lua scripts, APCu spinlocks; tested against real forked processes (`pcntl`). Needs nothing but PHP and Redis | [![v](https://img.shields.io/packagist/v/rasuvaeff/bulkhead?style=flat-square&label=&color=4c1)](https://packagist.org/packages/rasuvaeff/bulkhead) |
| [**rector-datetime-immutable**](https://github.com/rasuvaeff/rector-datetime-immutable) | Rector rules migrating mutable `DateTime` → `DateTimeImmutable` — and auto-fixing the lost mutations the migration silently creates, where `$date->modify('+1 day');` throws the new instance away. Static analysers report those; this fixes them in bulk | [![v](https://img.shields.io/packagist/v/rasuvaeff/rector-datetime-immutable?style=flat-square&label=&color=4c1)](https://packagist.org/packages/rasuvaeff/rector-datetime-immutable) |
| [**property-testing**](https://github.com/rasuvaeff/property-testing) | Property-based testing with **integrated shrinking** (Hedgehog model) and stateful / model-based testing — the two things PHP's PBT libraries don't do. Generates inputs, finds a counterexample, shrinks it to the minimal one. A Testo plugin | [![v](https://img.shields.io/packagist/v/rasuvaeff/property-testing?style=flat-square&label=&color=4c1)](https://packagist.org/packages/rasuvaeff/property-testing) |
| [**yii3-outbox**](https://github.com/rasuvaeff/yii3-outbox) | Transactional outbox — events committed in the same transaction as the data, then relayed. No lost messages on crash, no dual-write. Yii3 had no such thing | [![v](https://img.shields.io/packagist/v/rasuvaeff/yii3-outbox?style=flat-square&label=&color=4c1)](https://packagist.org/packages/rasuvaeff/yii3-outbox) |
| [**yii3-feature-flags**](https://github.com/rasuvaeff/yii3-feature-flags) | Feature flags with percentage rollout and deterministic per-subject bucketing — same user, same variant, every time. Pluggable backends (DB, Redis) + a UI | [![v](https://img.shields.io/packagist/v/rasuvaeff/yii3-feature-flags?style=flat-square&label=&color=4c1)](https://packagist.org/packages/rasuvaeff/yii3-feature-flags) |
| [**yii3-mcp**](https://github.com/rasuvaeff/yii3-mcp) | MCP server for Yii3: expose CQRS handlers as LLM tools, auto-bridge OpenAPI → MCP, and — the part generic MCP servers skip — per-user RBAC and an audit log on everything the model touches | [![v](https://img.shields.io/packagist/v/rasuvaeff/yii3-mcp?style=flat-square&label=&color=4c1)](https://packagist.org/packages/rasuvaeff/yii3-mcp) |

<details>
<summary><b>The rest of the ecosystem</b> — resilience, observability, Yii3 infrastructure</summary>

<br>

| Area | Packages |
|---|---|
| **Resilience** | [retry](https://github.com/rasuvaeff/retry) · [bulkhead](https://github.com/rasuvaeff/bulkhead) · [duration](https://github.com/rasuvaeff/duration) · [result](https://github.com/rasuvaeff/result) |
| **Delivery** | [yii3-outbox](https://github.com/rasuvaeff/yii3-outbox) (+ `-db`, `-clickhouse`) · [yii3-webhooks](https://github.com/rasuvaeff/yii3-webhooks) (+ `-db`) · [yii3-outbox-webhooks-bridge](https://github.com/rasuvaeff/yii3-outbox-webhooks-bridge) · [yii3-idempotency](https://github.com/rasuvaeff/yii3-idempotency) (+ `-db`) — safe request retries via `Idempotency-Key` |
| **Experiments** | [yii3-feature-flags](https://github.com/rasuvaeff/yii3-feature-flags) (+ `-db`, `-ui`) · [yii3-ab-testing](https://github.com/rasuvaeff/yii3-ab-testing) (+ `-db`, `-clickhouse`, `-web`, `-outbox`) |
| **Observability** | [yii3-telemetry](https://github.com/rasuvaeff/yii3-telemetry) (+ `-otel`) · [yii3-metrics](https://github.com/rasuvaeff/yii3-metrics) (+ `-prometheus`) · [yii3-correlation-id](https://github.com/rasuvaeff/yii3-correlation-id) · [yii3-health-check](https://github.com/rasuvaeff/yii3-health-check) · [yii3-audit-log](https://github.com/rasuvaeff/yii3-audit-log) (+ `-db`) · [domain-monitor](https://github.com/rasuvaeff/domain-monitor) |
| **AI / LLM** | [yii3-mcp](https://github.com/rasuvaeff/yii3-mcp) · [yii3-mcp-rbac-bridge](https://github.com/rasuvaeff/yii3-mcp-rbac-bridge) |
| **Yii3 infrastructure** | [yii3-tenancy](https://github.com/rasuvaeff/yii3-tenancy) (+ `-db`) · [yii3-settings](https://github.com/rasuvaeff/yii3-settings) (+ `-db`, `-ui`) · [yii3-api-problem](https://github.com/rasuvaeff/yii3-api-problem) · [yii3-maintenance-mode](https://github.com/rasuvaeff/yii3-maintenance-mode) · [yii3-seo](https://github.com/rasuvaeff/yii3-seo) · [yii3-centrifugo](https://github.com/rasuvaeff/yii3-centrifugo) · [yii3-respect-validation](https://github.com/rasuvaeff/yii3-respect-validation) · [yii3-recaptcha](https://github.com/rasuvaeff/yii3-recaptcha) · [yii3-turnstile](https://github.com/rasuvaeff/yii3-turnstile) |
| **Query & domain** | [specification](https://github.com/rasuvaeff/specification) — Specification pattern, composable type-safe query building |
| **ClickHouse** | [clickhouse-toolkit](https://github.com/rasuvaeff/clickhouse-toolkit) · [yii3-clickhouse-toolkit](https://github.com/rasuvaeff/yii3-clickhouse-toolkit) |
| **Tooling** | [rector-named-literals](https://github.com/rasuvaeff/rector-named-literals) · [rector-datetime-immutable](https://github.com/rasuvaeff/rector-datetime-immutable) |

</details>

---

### 🔭 What I'm building

- **A fitness / training platform backend** (Yii3, PHP 8.5, PostgreSQL) — activity tracking with `.fit` file parsing, duels and leagues, JWT auth, S3 storage, real-time via Centrifugo, transactional outbox for event delivery. Strict Clean Architecture layering enforced by Deptrac; built on my own packages.
- **A Yii3 product backend** (PHP 8.5, MySQL / ClickHouse / Memcached) — admin panel, REST API with OpenAPI, RBAC, multi-language, media pipeline, and an MCP server that lets LLM assistants operate the product safely.

---

### 💡 What I like building

- Low-latency, high-load services where milliseconds and correctness both matter
- Distributed patterns done properly: outbox, idempotency, retries with backoff, bulkheads
- Libraries other people can depend on — documented, versioned, mutation-tested
- Making LLMs a first-class, permission-aware part of a backend rather than a bolt-on

---

### 📫 Contact

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rasuvaeff)
[![Packagist](https://img.shields.io/badge/Packagist-F28D1A?style=for-the-badge&logo=packagist&logoColor=white)](https://packagist.org/packages/rasuvaeff/)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/rasuvaeff)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rasuvaeff@gmail.com)
