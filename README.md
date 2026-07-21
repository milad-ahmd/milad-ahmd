<!-- Hand-crafted profile. header.svg & metrics.svg live in this repo — no third-party widget services. -->

<a href="https://www.linkedin.com/in/milad-ahmadi"><img width="100%" src="./header.svg" alt="Terminal running neofetch — Milad Ahmadi, Senior Software Engineer, full-stack backend-heavy. Backend: Java, Spring Boot, Go, NestJS, Kafka. Frontend: React, Next.js, React Native, TypeScript. Relocating Tehran to Amsterdam. Click to open LinkedIn." /></a>

<p align="center">
  <a href="https://www.linkedin.com/in/milad-ahmadi">LinkedIn</a> ·
  <a href="mailto:miladahmadi803@gmail.com">miladahmadi803@gmail.com</a>
</p>

<br/>

## `$ java -jar milad-ahmadi.jar`

```
  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/

 :: Milad Ahmadi ::                       (v9.x.RELEASE — Senior Software Engineer)

INFO  --- [main] MiladApplication           : Starting on JVM 21 (LTS) — profile: production
INFO  --- [main] ExperienceAutoConfiguration: 9+ years of production systems detected
INFO  --- [main] DomainScanner              : Domains found: [fintech, logistics, mobility, e-commerce]
INFO  --- [main] KafkaMeshBean              : 25+ topics wired — exactly-once semantics enabled
INFO  --- [main] SettlementEngine           : Clearing 100K+ trades/day · P99 < 100 ms — SLO met
INFO  --- [main] ReactorPipeline            : Backpressure healthy @ 60K concurrent sessions
INFO  --- [main] FullStackBridge            : React/Next.js consoles · NestJS services · React Native field apps
INFO  --- [main] ResilienceConfig           : Circuit breakers armed — outage blast radius −60%
INFO  --- [main] GkitPublisher              : OSS toolkits online: [gkit-java, gkit-go, gkit-nestjs]
INFO  --- [main] MentorshipService          : PR review-to-merge −50% · team coverage 85%+
WARN  --- [main] RelocationService          : Instance ready to migrate → eu-west-1 (Amsterdam, NL)
INFO  --- [main] MiladApplication           : Started MiladApplication in 9.2 years (worth every ms)
```

<a href="https://github.com/milad-ahmd?tab=repositories"><img width="100%" src="./metrics.svg" alt="Production dashboard — 100K+ trades/day at P99 under 100ms, 60K concurrent sessions, Lighthouse 96/100 frontend vitals, cloud spend −27%, 99.9% uptime SLO. Stack mix: Java, TypeScript, JavaScript, Go, SQL. Click to browse repositories." /></a>

## `$ kafka-console-consumer --topic milad.career.events --from-beginning`

```json
[
  { "offset": 0, "ts": "2017-01", "key": "manage-petro", "value": {
      "role": "Backend Developer", "domain": "fuel-delivery logistics",
      "highlights": ["offline-first React Native + Spring CQRS — 1M+ tx/day, 100% data integrity",
                     "Stripe + PSP integrations — GMV +18%",
                     "PWA Lighthouse 68 → 96 — service workers + background sync"] } },

  { "offset": 1, "ts": "2018-11", "key": "hashthink", "value": {
      "role": "Full-Stack Engineer", "domain": "web3 / real-time platform",
      "highlights": ["Spring WebFlux + Reactor — 60K concurrent < 150 ms",
                     "React-Three-Fiber 3D UI — WebSocket-synced live auction floor",
                     "event-sourced, idempotent Kafka processors — zero financial mismatches"] } },

  { "offset": 2, "ts": "2020-04", "key": "sanay-systems", "value": {
      "role": "Senior Software Engineer", "domain": "capital markets / fintech",
      "highlights": ["monolith → 40+ Java microservices on EKS — throughput +40%",
                     "settlement engine — 100K+ trades/day · P99 < 100 ms",
                     "React/Next.js exchange consoles — Module Federation micro-frontends",
                     "GitOps canary deploys — MTTR 40 → 22 min"] } },

  { "offset": 3, "ts": "2025-02", "key": "hich", "status": "CURRENT", "value": {
      "role": "Senior Software Engineer", "domain": "ride-hailing / mobility",
      "highlights": ["event-driven ride & payment platform on Kafka",
                     "PostgreSQL hot-path tuning — p95 −35%",
                     "rider & ops web apps — React/TypeScript behind feature flags",
                     "ClickHouse pipeline — batch reporting → near real-time"] } }
]
```

## `$ helm ls --namespace open-source`

| RELEASE | CHART | STATUS | NOTES |
| :--- | :--- | :--- | :--- |
| **[gkit-java](https://github.com/milad-ahmd/gkit-java)** | `java-21 / spring-boot-3` | ✅ deployed | Production-grade resilience toolkit — retry, circuit breaker, **saga**, caching, validation, observability |
| **[gkit-go](https://github.com/milad-ahmd/gkit-go)** | `go` | ✅ deployed | The Go edition — idiomatic reliability primitives for microservices |
| **[gkit-nestjs](https://github.com/milad-ahmd/gkit-nestjs)** | `typescript / nestjs` | ✅ deployed | Same building blocks for Node services |
| **[nest-postgres-boilerplate](https://github.com/milad-ahmd/nest-postgres-boilerplate)** | `typescript / nestjs` | ✅ deployed | NestJS + PostgreSQL starter — TypeORM & migrations |
| **[go-clean-arch](https://github.com/milad-ahmd/go-clean-arch)** | `go` | ✅ deployed | Clean Architecture reference implementation in Go |

<details>
<summary>&nbsp;<code>application.yml</code> — full skill manifest</summary>

```yaml
milad:
  languages: [java-21, typescript, javascript-es6, go, sql]
  backend:
    spring: [boot-3, webflux-reactor, security, data-jpa]
    concurrency: [virtual-threads, executor-service, completable-future]
    node: [nestjs, express, graphql]
    go: [net-http, gin, grpc, goroutines, errgroup]
  frontend:
    react: [nextjs-ssr-isr, react-native, redux, zustand, tanstack-query]
    ui: [tailwind, styled-components, storybook, d3]
    quality: [core-web-vitals, lighthouse-96, module-federation]
  messaging:
    kafka: { streams: true, connect: true, exactly-once: true }
    also: [rabbitmq, redis-streams, websockets, socket-io]
  data: [postgresql, mongodb, redis, clickhouse, cassandra, elasticsearch]
  cloud:
    aws: [eks, ecs, lambda, rds, s3]
    platform: [kubernetes, helm, terraform, docker, argocd-gitops]
  testing: [junit5, testcontainers, mockito, gatling, jest, cypress, playwright, react-testing-library]
  observability: [prometheus, micrometer, grafana, opentelemetry, elk]
  architecture: [microservices, event-driven, cqrs, ddd, clean-architecture]
```
</details>

## `$ curl -s https://milad.dev/v1/contact | jq .`

```json
{
  "name": "Milad Ahmadi",
  "role": "Senior Software Engineer — full-stack (Java / Go / TypeScript · React)",
  "location": { "current": "Tehran, IR", "next": "Amsterdam, NL", "visa": "sponsorship-required" },
  "links": {
    "linkedin": "https://www.linkedin.com/in/milad-ahmadi",
    "github": "https://github.com/milad-ahmd",
    "email": "miladahmadi803@gmail.com"
  },
  "status": "open_to_opportunities",
  "response_time_slo": "< 24h"
}
```

<p align="center">
  <a href="https://www.linkedin.com/in/milad-ahmadi"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:miladahmadi803@gmail.com"><img src="https://img.shields.io/badge/-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

<p align="center"><sub>⎈ This README is a self-hosted production system: two hand-written animated SVGs, zero external widget dependencies. Uptime guaranteed.</sub></p>
