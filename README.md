# Ahmad Gamal

Backend engineer from Cairo. I work mostly with Node.js, TypeScript, NestJS and PostgreSQL, and I build in Go too. I like understanding how things work under the hood, and building systems that stay correct when something goes wrong.

Open to backend roles in Cairo or remote · [LinkedIn](https://www.linkedin.com/in/ahmad-mosha) · [ahmadmoshaa3@gmail.com](mailto:ahmadmoshaa3@gmail.com)

## What I've built

**[Prime Market](https://github.com/Ahmad-Mosha/business-system-tenant)**: the operations system of an e-commerce business in Egypt, running in production since August 2026. It holds their inventory, orders, courier shipments, noon and Amazon settlements, purchasing and a double-entry ledger, in Arabic and English. I built it with the owners, from requirements to production.
`NestJS` `PostgreSQL` `Next.js` `Docker` `AWS EC2`

**[Stay Flow](https://github.com/Ahmad-Mosha/stay-flow)**: a booking platform for small hotels. A PostgreSQL exclusion constraint makes double booking impossible, and concurrency tests against a real database prove it. Retries are idempotent and emails go through a transactional outbox. [Live demo](https://stayfloww.duckdns.org)
`NestJS` `Kysely` `PostgreSQL` `Testcontainers`

**[DiskKV](https://github.com/Ahmad-Mosha/kv-store)**: a key-value storage engine in Go. Append-only log, in-memory index, checksummed records, crash recovery and compaction, served over TCP with connection and rate limits.
`Go`

**[RelayEdge](https://github.com/Ahmad-Mosha/http-reverse-proxy)**: an HTTP reverse proxy and load balancer built only on Node's core modules, with stream backpressure, keep-alive pooling, health checks and safe retries.
`TypeScript` `Node.js`

## Open source

Merged

- [nestjs/nest#18090](https://github.com/nestjs/nest/pull/18090): custom param decorators lost their data when it had a `schema` or `pipes` key
- [nestjs/nest#18156](https://github.com/nestjs/nest/pull/18156): `@All()` routes ignored versioning and route options on the Fastify adapter (I reported the issue and fixed it)

In review

- [typeorm/typeorm#12971](https://github.com/typeorm/typeorm/pull/12971): support better-sqlite3 v13
- [honojs/node-server#409](https://github.com/honojs/node-server/pull/409): forward `duplex` to the native `Request`, fixing an illegal invocation error on Node.js 26
- [fastify/fastify-compress#437](https://github.com/fastify/fastify-compress/pull/437): document that `threshold` does not apply to streams

## Tools

TypeScript · Node.js · NestJS · Go · PostgreSQL · Docker · Linux · AWS (EC2, S3) · Next.js
