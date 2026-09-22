### Aleksandr Efimov

Senior backend developer, 17 years. Payments, high-load systems, legacy modernization. Halifax, Nova Scotia.

**Building now.**

- [**femus**](https://github.com/femus/femus) — hardware for PHP developers. Arduino and Raspberry Pi GPIO, sensors, scales, LCDs, 433 MHz packet radio and GSM, driven from plain PHP: typed device drivers, an event loop, precompiled firmware that flashes with one command, and a `FakeBoard` so hardware logic is unit-testable in CI. The flagship demo is an offline messenger — an iPhone in airplane mode talking to a Mac over radio you assemble yourself, with a SwiftUI terminal on the phone side. There is also an MCP server, so Claude Code and friends can scan ports, flash firmware and read pins.
- [**ApplyWave**](https://applywave.app) — an AI job-search SaaS I built solo from architecture to paying users: Laravel + React/Inertia, a Python/FastAPI aggregation service, multi-model LLM pipelines (Claude / OpenAI) with schema validation and anti-hallucination checks.

**Day job, mostly in private repos.**

*Payments / fintech.* Plaid ACH end to end (bank linking, transfers, idempotent webhooks, duplicate-payment prevention), Stripe billing and subscriptions, an EU-licensed crypto escrow platform (atomic balance operations, fund freezing, disputes), and back-office infrastructure at a forex broker clearing $785B+ a month.

*Scale and legacy.* A top-10 global traffic platform (100M+ daily visitors) through its monolith-to-microservices split. Canada's largest auto marketplace: PHP 5.5 to 8.2, ~3,000 dealer feeds a day, Redis queues, Docker.

**Other open source.** [php-wifi](https://github.com/sanchescom/php-wifi) (Wi-Fi scan, join and hotspot from PHP, verified on real hardware) · [laravel-rest](https://github.com/sanchescom/laravel-rest) (Eloquent-like models over REST APIs, adopted across teams at Exness) · [laravel-cache-memory](https://github.com/sanchescom/laravel-cache-memory) (shmop cache driver shared by PHP-FPM and queue workers) · [php-serial](https://github.com/sanchescom/php-serial) (serial I/O for PHP 8.2+, extracted from femus).

PHP/Laravel (17y) · Go · Python/FastAPI · React · Swift/SwiftUI · PostgreSQL · MongoDB · Redis · RabbitMQ / Kafka / NATS · Docker / Kubernetes · Claude Code daily

[LinkedIn](https://www.linkedin.com/in/sanchescom)
