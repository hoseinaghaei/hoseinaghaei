# Hossein Aghaei Araei

**Principal Software Engineer — backend systems and relational database performance.**

I own the price and promotion domain at [Digikala](https://www.digikala.com), the largest
e-commerce platform in its market. Six years of making systems cheaper, faster and more
correct while they stay in production — usually by arguing for the change nobody wanted to
own.

My specialism is the database layer: the point where a schema decision, an index, or an
isolation level quietly decides what the whole platform can afford.

```
100M+   events a day through buy-box selection, at 2,000+ req/s on five database CPU cores
8B+     rows in our largest table, split into hot and cold halves that both serve live traffic
                                                     → hot table 32× smaller, zero downtime
40%     less CPU on the main database, after tracing a "caching bug" to the transaction
                                                     isolation level across 10+ live databases
50k+    req/s stock-management microservice with distributed transactions
90→10   minutes for auto-pricing across 1M+ products
800k    concurrent users across three Black Friday campaigns
~200    engineers through an advanced MySQL programme I designed and taught
```

---

## What I work with

**Languages** Java (Spring Boot, Spring Data JPA, Hibernate) · PHP · Python · Go ·
C#/.NET (ASP.NET Core, .NET Framework, Entity Framework) · JavaScript with Node.js and React ·
C · R · SQL · Bash

**Databases** MySQL and PostgreSQL performance — query optimisation · index design ·
transaction isolation and locking · replication, failover and disaster recovery ·
ClickHouse · MongoDB · Elasticsearch · IoTDB/InfluxDB for time series

**Caching & messaging** Redis · Memcached · write-around and write-through caching ·
Apache Kafka · change data capture · REST API design · OAuth 2.0 and JWT · MQTT · WebSocket

**Architecture** Microservices · distributed transactions · CQRS · eventual consistency ·
SOLID · clean architecture · domain-driven design principles ·
hexagonal (ports-and-adapters) separation · vertical slice organisation

**Testing** TDD · unit, integration, contract and load testing, including write load tests run
against production

**AI** Claude Code and Cursor daily on a production codebase · LLM features and agentic
automation in production workflows

**Tooling** Docker · Linux · Git · GitLab CI/CD · Maven · Grafana ·
Percona Monitoring and Management · Jenkins (familiarity)

---

## Selected work

Most of what I build is closed-source and lives inside a marketplace. What is public here is
mainly systems and database work from research and university projects — the fundamentals
underneath the production work.

| Project | Built with | |
|---|---|---|
| **[mariadb-tpcds](https://github.com/hoseinaghaei/mariadb-tpcds)** | C, Python | The full TPC-DS v4.0.0 schema and all 99 queries against MariaDB, with an isolated measurement protocol. Benchmarking done carefully enough to be honest about what the numbers do and do not mean. |
| **[encoding-compression-benchmark](https://github.com/hoseinaghaei/encoding-compression-benchmark)** | Java, Python | Benchmarks comparing numeric encoders, compressors and hybrid pipelines, with analysis scripts. Came out of asking what it actually costs to store a time series. |
| **[kafka](https://github.com/hoseinaghaei/kafka)** | Python, Java, Docker | Server for a Kafka-style message broker — brokers, partitions and delivery|
| **[onlineTicket](https://github.com/hoseinaghaei/onlineTicket)** | JavaScript, Docker | An online ticketing platform with organisations, products and agent assignment, shipped through a full CI pipeline. |
| **[mibench](https://github.com/hoseinaghaei/mibench)** | C, Python, Java | The MiBench embedded suite extended into Python and Java, plus the gem5 &rarr; McPAT toolchain for power, area and timing. The measurement infrastructure behind a thermal-management paper. |
| **[c-minus-compiler](https://github.com/hoseinaghaei/c-minus-compiler)** | Python | A one-pass compiler: scanner, parser, semantic analyser and intermediate code generation, including recursive calls. |
| **[OS_pintos](https://github.com/hoseinaghaei/OS_pintos)** | C | PintOS through three phases, ending in an inode-based filesystem with a buffer cache and the synchronisation to make it safe. |
| **[MIPS-Verilog](https://github.com/hoseinaghaei/MIPS-Verilog)** | SystemVerilog, Assembly | A MIPS processor — the other end of the stack from a query planner. |
| **[SDN](https://github.com/hoseinaghaei/SDN)** | Python, Mininet | Shortest-path routing pushed into a software-defined network controller over a Mininet topology. |

---

## Research

**Lightweight MQTT–Time Series Database Integration for IoT: Optimizing Payloads for Traffic
and Energy Efficiency** — profiling Apache IoTDB in a clustered environment and designing an
MQTT payload format that cuts network and energy overhead. *In preparation.*

**HAMLET: Adaptive Machine Learning-based Thermal Management in Fault-Tolerant Heterogeneous
Multicore Systems** — with A. Ansari and M. Ansari. *Submitted.*

---

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/hossein-aghaei-araei/) ·
h.aghaei.araei@gmail.com

<br>

<p align="left">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=hoseinaghaei&show_icons=true&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hoseinaghaei&layout=compact&hide_border=true&langs_count=8" alt="Top languages" />
</p>
