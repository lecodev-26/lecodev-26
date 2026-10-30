<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/hero.svg"><img src="assets/light/hero.svg" alt="LECODEV BUILDS · Software, infrastructure and backend · Barcelona" width="100%"></picture>

<a href="https://lecodev-portafolio.vercel.app"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-web.svg"><img src="assets/light/b-web.svg" alt="Live portfolio" width="144"></picture></a>&nbsp;<a href="https://github.com/lecodev-26?tab=repositories"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-repos.svg"><img src="assets/light/b-repos.svg" alt="Repositories" width="132"></picture></a>&nbsp;<a href="mailto:lecodev@outlook.es"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-mail.svg"><img src="assets/light/b-mail.svg" alt="Email me" width="106"></picture></a>&nbsp;<a href="https://github.com/Basekick-Labs/arc/pulls?q=is%3Apr+author%3Alecodev-26+is%3Amerged"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-arcprs.svg"><img src="assets/light/b-arcprs.svg" alt="My PRs in Arc" width="141"></picture></a>

**Software, infrastructure and backend engineer in Barcelona.**<br>I build the machinery behind the product: AI gateways, post-quantum cryptography and systems languages.

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/marquee.svg"><img src="assets/light/marquee.svg" alt="Go · Rust · Python · TypeScript · PostgreSQL · Redis · Kubernetes · Docker · MCP · Linux · Termux" width="100%"></picture>

</div>

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/h-que.svg"><img src="assets/light/h-que.svg" alt="What I do" width="100%"></picture>

</div>

I am interested in the layer between software and infrastructure: the part that makes systems useful, controllable and resilient. I would rather build the machinery behind the product than another thin wrapper around an API.

| What I do | Where |
|---|---|
| AI gateways and LLM infrastructure | SentinelFlow |
| Security and cryptographic systems | NEXUS-Q · NEXUS-Q Tools |
| Programming languages and compilers | AXIOM |
| Runtime, compute and simulation | DINAH |
| Agents, tools and MCP | Genie |
| Time-series databases | Arc |
| Local and self-hosted software | Linux · Android · Termux |

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/h-proyectos.svg"><img src="assets/light/h-proyectos.svg" alt="Projects" width="100%"></picture>

</div>

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/r-sentinelflow.svg"><img src="assets/light/r-sentinelflow.svg" alt="SENTINELFLOW · Ai gateway and control plane for llms" width="100%"></picture>

</div>

OpenAI-compatible gateway for teams that run several model providers. It brings intelligent routing, provider failover, policies, AI FinOps, security and observability into a single open source layer. Authentication, tenant isolation, quotas, audit and events.

`Go` `PostgreSQL` `Redis` `Docker` `Kubernetes` `Prometheus`

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/l-sentinelflow.svg"><img src="assets/light/l-sentinelflow.svg" alt="Go 87% · HTML 9% · Shell 2% · others 2%" width="100%"></picture><br>
<sub>Go 87% · HTML 9% · Shell 2% · others 2%</sub>

- **Status:** V5.0.1 stable · V6 in development on the `v6` branch
- **License:** MIT
- **Last activity:** Oct 16, 2026

<a href="https://github.com/lecodev-26/sentinelflow"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-repo.svg"><img src="assets/light/b-repo.svg" alt="b-repo" width="159"></picture></a>

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/r-nexus-q.svg"><img src="assets/light/r-nexus-q.svg" alt="NEXUS-Q · Post-quantum security engine" width="100%"></picture>

</div>

Rust post-quantum cryptographic security engine for data, keys and identities, with key lifecycle management, authenticated encryption, signatures, credentials, policy enforcement, audit logging and hardware-provider abstractions. The project includes security CI, fuzz targets, documented threat models, benchmarks and a PQC Benchmark Arena. **v4.1.2 is the current release.** It is an audit-ready release, not a production-readiness claim; no independent external audit or FIPS validation is claimed. The native ML-KEM/ML-DSA backend remains experimental and opt-in; RustCrypto is the default path.

`Rust` `ML-KEM-768` `ML-DSA-65` `SLH-DSA` `RISC-V` `Android` `SDKs`

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/l-nexus-q.svg"><img src="assets/light/l-nexus-q.svg" alt="Rust 94% · C 3% · C++ 1% · Go, Shell, PHP, Ruby 2%" width="100%"></picture><br>
<sub>Rust 94% · C 3% · C++ 1% · Go, Shell, PHP, Ruby 2%</sub>

- **V1:** frozen baseline `v1.0.0`
- **V2:** frozen on `nexusqv2` (`v2.0.0`)
- **V3:** merged into `main` (PR #45)
- **V4:** `v4.1.2` current release · Audit-Ready Release · no production-readiness claim, no FIPS validation, external audit pending. Native backend remains experimental and opt-in; RustCrypto is the default.
- **Companion tools:** 25 independent Rust CLI tools built on the public `nexusq-core` API; all 25 crates are published on crates.io at `0.1.0`.
- **Last activity:** Oct 28, 2026

<a href="https://github.com/lecodev-26/nexus-q"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-repo.svg"><img src="assets/light/b-repo.svg" alt="NEXUS-Q repository" width="159"></picture></a>&nbsp;<a href="https://github.com/lecodev-26/nexus-qtools"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-repo.svg"><img src="assets/light/b-repo.svg" alt="NEXUS-Q Tools repository" width="159"></picture></a>&nbsp;<a href="https://nexus-q.link"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-site.svg"><img src="assets/light/b-site.svg" alt="NEXUS-Q website" width="160"></picture></a>&nbsp;<a href="https://github.com/lecodev-26/nexus-qtools/releases/latest"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-release.svg"><img src="assets/light/b-release.svg" alt="NEXUS-Q Tools release" width="148"></picture></a>

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/r-axiom.svg"><img src="assets/light/r-axiom.svg" alt="AXIOM · Programming language and systems ecosystem" width="100%"></picture>

</div>

A general-purpose language with a small syntax and a deep semantic model. The long-term goal is its own compiler, runtime, ABI and self-hosted toolchain, so that AXIOM compiles AXIOM. Python and Rust are the transition infrastructure.

`Python` `Rust` `Compiler` `Runtime` `Systems`

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/l-axiom.svg"><img src="assets/light/l-axiom.svg" alt="Python 51% · Rust 49%" width="100%"></picture><br>
<sub>Python 51% · Rust 49%</sub>

- **Status:** architecture closed, now being implemented
- **License:** MIT
- **Last activity:** Oct 3, 2026

<a href="https://github.com/lecodev-26/axiom"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-repo.svg"><img src="assets/light/b-repo.svg" alt="b-repo" width="159"></picture></a>

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/r-dinah.svg"><img src="assets/light/r-dinah.svg" alt="DINAH · Modular Rust runtime, compute and simulation foundation" width="100%"></picture>

</div>

A Rust-first foundation for runtime execution, memory, compute, ECS, deterministic simulation and early networking. Core/runtime/memory/compute/ECS foundations, five bounded simulation models, initial blocking TCP wrappers and prediction/reconciliation/replay primitives are implemented. Networking wire encoding and full protocol integration remain unfinished; this is not a production-ready runtime or game engine.

`Rust` `Runtime` `Compute` `ECS` `Simulation` `Networking`

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/l-dinah.svg"><img src="assets/light/l-dinah.svg" alt="Rust 100%" width="100%"></picture><br>
<sub>Rust 100%</sub>

- **Status:** pre-alpha · active development
- **License:** MIT OR Apache-2.0
- **Last activity:** Oct 19, 2026

<a href="https://github.com/lecodev-26/dinah"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-repo.svg"><img src="assets/light/b-repo.svg" alt="b-repo" width="159"></picture></a>&nbsp;<a href="https://github.com/lecodev-26/dinah/blob/main/roadmap.md"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-release.svg"><img src="assets/light/b-release.svg" alt="b-release" width="148"></picture></a>

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/r-genie.svg"><img src="assets/light/r-genie.svg" alt="GENIE · An ai-powered akinator" width="100%"></picture>

</div>

A `SKILL.md` file with instructions that let an AI guess what you are thinking of, with no app and nothing to install. The questions adapt to your answers, a "not sure" counts as neither yes nor no, and it only takes a guess when it has enough evidence. It also includes a minimal remote MCP server for compatible AI clients.

`Markdown` `TypeScript` `MCP`

- **License:** MIT
- **Last activity:** Sep 29, 2026

<a href="https://github.com/lecodev-26/genie"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-repo.svg"><img src="assets/light/b-repo.svg" alt="b-repo" width="159"></picture></a>&nbsp;<a href="https://github.com/lecodev-26/genie/releases/latest"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-release.svg"><img src="assets/light/b-release.svg" alt="b-release" width="148"></picture></a>

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/r-nuvora.svg"><img src="assets/light/r-nuvora.svg" alt="NUVORA · Experimental project" width="100%"></picture>

</div>

An experimental project with a Python backend and a JavaScript interface, deployed on Vercel. I keep it lightweight while the implementation evolves.

`Python` `JavaScript` `Vercel`

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/l-nuvora.svg"><img src="assets/light/l-nuvora.svg" alt="Python 74% · JavaScript 26%" width="100%"></picture><br>
<sub>Python 74% · JavaScript 26%</sub>

- **Last activity:** Sep 28, 2026

<a href="https://nuvora-chi.vercel.app"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-demo.svg"><img src="assets/light/b-demo.svg" alt="b-demo" width="147"></picture></a>&nbsp;<a href="https://github.com/lecodev-26/nuvora"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-repo.svg"><img src="assets/light/b-repo.svg" alt="b-repo" width="159"></picture></a>

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/r-arc.svg"><img src="assets/light/r-arc.svg" alt="ARC · Contributions to the time-series database" width="100%"></picture>

</div>

I contribute to Arc, by Basekick Labs: an open, SQL-native time-series database written in Go on top of DuckDB, built for high-throughput telemetry, Parquet storage and analytical SQL. I have **8 PRs merged into `main`**, covering the WAL, file replication, ingestion, retention policies, the tiering API and configuration.

`Go` `DuckDB` `WAL` `Parquet` `Ingestion`

- **PRs merged into main:** 8
- **Last merge:** Oct 29, 2026

<a href="https://github.com/Basekick-Labs/arc"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-arc.svg"><img src="assets/light/b-arc.svg" alt="b-arc" width="103"></picture></a>

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/h-arc.svg"><img src="assets/light/h-arc.svg" alt="Arc · contributions" width="100%"></picture>

</div>

Arc (Basekick Labs) is an AGPL-3.0 licensed SQL time-series database written in Go, with 686 stars. These are my changes that the maintainer has merged into its `main` branch, with the context of each review.

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/stats.svg"><img src="assets/light/stats.svg" alt="8 PRs merged, 52 files changed, +3,237 lines, 5 areas of the codebase" width="100%"></picture>

</div>

#### [#1052](https://github.com/Basekick-Labs/arc/pull/1052) · `feat(tiering): support filtered manual migrations`

**Merged into main** · Oct 29, 2026 · +319 −16 · 7 files

Adds database- and measurement-filtered manual tier migrations, validates the source and destination tiers while keeping the supported direction explicit as hot → cold, and makes `dry_run` report candidate count and bytes without moving files. The scheduled migration path remains unchanged. The PR adds focused coverage for filtered candidates and preview non-mutation; it was merged by the Arc maintainer after review.

#### [#1241](https://github.com/Basekick-Labs/arc/pull/1241) · `fix(config): remove dead license.enabled key`

**Merged into main** · Oct 13, 2026 · +12 −6 · 2 files · Closes #1195

Removed `license.enabled` from the config struct, loader and defaults because it was read but never used. Enterprise licensing continues to be driven by `license.file_path` or `license.key`; any leftover `license.enabled` setting or `ARC_LICENSE_ENABLED` environment variable remains ignored, so this is a cleanup with no behavior change.

#### [#1053](https://github.com/Basekick-Labs/arc/pull/1053) · `feat(retention): apply policies to cold tier`

**Merged into main** · Retention · Cold-tier storage

Retention policies now apply to data in the cold tier as well, bringing cold-tier lifecycle handling in line with Arc's retention rules instead of limiting policy enforcement to the hot tier.

#### [#1073](https://github.com/Basekick-Labs/arc/pull/1073) · `fix(filereplication): make rewritten files immutable`

**Merged into main** · Oct 8, 2026 · +623 −101 · 16 files · After 26.09.3 · Closes #975 · unblocks #1092

Partial DELETE rewrites no longer mutate the existing manifest entry: they publish a fresh Parquet file, register the new path and delete the old one in a single Raft batch, with the rewritten checksum and size and the rewriting node as the new origin. Before, a same-size rewrite could leave replicas trusting a stale file, because presence was checked by size only. It covers the live, replay and snapshot catch-up paths, and serializes concurrent partial DELETEs so they cannot publish several survivors from the same source. The maintainer noted that the approach was right from the first push. Benchmark on existing data: +0.26%, within the noise margin.

#### [#1051](https://github.com/Basekick-Labs/arc/pull/1051) · `fix(api): validate tiering file limits`

**Merged into main** · Oct 7, 2026 · +129 −21 · 2 files · After 26.09.3 · Fixes #1135

`GET /api/v1/tiering/files` rejects non-integer or negative `limit` values, which used to cause a panic when slicing with a negative index. I added a structural guard with a positive limit at the point of use, kept `limit=0` as an explicit empty result, and dropped the proposed cap of 1000 so the API stays backward compatible.

#### [#1055](https://github.com/Basekick-Labs/arc/pull/1055) · `fix(wal): line-protocol WAL entries carry their database envelope`

**Merged into main** · Oct 4, 2026 (merged Oct 5) · +137 −4 · 3 files · Release 26.09.3 · Fixes #889

Line-protocol writes reached the buffer as columns with no raw client bytes, so their WAL entry went out without a database and a receiver always filed it under "default". The row-format path now writes the same envelope that msgpack uses. It is safe for replay, receiver, checkpoints and large sizes, and readable by any binary since 26.05.1. During review the maintainer narrowed the scope: the change in `cmd/arc/main.go` (#886), which depended on #888, was dropped and only the #889 envelope was kept.

#### [#1056](https://github.com/Basekick-Labs/arc/pull/1056) · `fix(wal): purge only data proven flushed`

**Merged into main** · Oct 4, 2026 · +884 −156 · 8 files · Release 26.09.3 · Resolves #1009 / #966

Closes the remaining gap in WAL purging. It tracks pending identities through durable flush checkpoints, exposes a real minimum-unflushed sequence and uses `PurgeFlushed` instead of wall-clock age for periodic and recovery cleanup, so a file is deleted only once its data has been flushed. After review, a maintainer commit bounds the purge floor and reclaims files it cannot describe.

#### [#769](https://github.com/Basekick-Labs/arc/pull/769) · `fix(ingest): log numeric host coercion at debug level`

**Merged into main** · Sep 13, 2026 · +58 −2 · 3 files · Release 26.09.2 · Fixes #768

The fallback that coerces numeric values into `host_<num>` strings is intentional and stays, but it hid a sign of misconfigured clients. I added a debug-level log when it fires, so the hot ingest path is not flooded, and two test cases (float and boolean host) that fall through to the default branch. It went through three review rounds and the merge added me to the project contributors list.


<sub>Source: the public PR and release pages of Arc on GitHub and its API, as of October 29, 2026. All merges were done by the project maintainer. #769 shipped in 26.09.2, #1055 and #1056 in 26.09.3, and #1051, #1073, #1241 and #1052 were merged after 26.09.3, the latest published release.</sub>

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/h-crono.svg"><img src="assets/light/h-crono.svg" alt="Timeline" width="100%"></picture>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/timeline.svg"><img src="assets/light/timeline.svg" alt="Timeline: AXIOM, SentinelFlow, Nuvora, Genie, NEXUS-Q; DINAH is listed in the project timeline below" width="100%"></picture>

</div>

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/h-stack.svg"><img src="assets/light/h-stack.svg" alt="Stack" width="100%"></picture>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/stack.svg"><img src="assets/light/stack.svg" alt="Go, Rust, Python, TypeScript, PostgreSQL, Redis, Docker, Kubernetes, Linux, Termux, MCP, DuckDB, Assembly" width="100%"></picture>

</div>

## 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/lecodev-26/lecodev-26/gh-pages/github-contribution-grid-snake-dark.svg" width="95%" alt="GitHub contribution snake" />

</div>

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/h-hablemos.svg"><img src="assets/light/h-hablemos.svg" alt="Let's talk" width="100%"></picture>

<a href="mailto:lecodev@outlook.es"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/dark/b-email2.svg"><img src="assets/light/b-email2.svg" alt="lecodev@outlook.es" width="193"></picture></a>

<sub>lecodev · Barcelona · © 2026</sub>

</div>
