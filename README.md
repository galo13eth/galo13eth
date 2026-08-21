# Lucas Franca

**Senior Web3 Product Engineer · Solidity, Go, TypeScript, React**
AI-agent platforms as a secondary specialization.

Brasília, Brazil · UTC-3 · Full-time remote · 4h+ U.S. Eastern overlap

I ship wallet-connected products end to end — Solidity contracts, indexed
onchain data, Go and TypeScript services, React frontends — as one production
system. Currently at [Agora](https://www.agora.xyz), building governance
infrastructure for **Optimism, ENS, and Uniswap**.

I also build and operate agent-first development workflows in which Claude
Code, Codex, and pi execute scoped tickets inside isolated workspaces, with
durable state, review-gated pull requests, and human supervision — the
workflow TakeAIt productizes.

#### Selected public engineering

Original systems plus 90 merged PRs across Agora's public repos
([agora-next](https://github.com/voteagora/agora-next/pulls?q=is%3Apr+author%3Agalo13eth+is%3Amerged),
[op-atlas](https://github.com/voteagora/op-atlas/pulls?q=is%3Apr+author%3Agalo13eth+is%3Amerged)).
A few worth reading:

- **[evm-migration-lab](https://github.com/galo13eth/evm-migration-lab)** —
  a deterministic Rust snapshot pipeline, narrowly scoped Solidity claim
  contracts, and a fail-closed React verification app for ERC-721/1155 state
  migration. Public Sepolia → Base Sepolia canary, explicit trust model, and
  cross-language end-to-end evidence.
  [Live app](https://web-production-fab71.up.railway.app) ·
  [v0.1.0](https://github.com/galo13eth/evm-migration-lab/releases/tag/v0.1.0)
- **Embedded wallets without breaking existing Web3 flows** — introduced
  Privy email/social login and embedded wallets for one tenant while
  preserving ConnectKit, Safe, SIWE, and gasless EIP-712 voting and
  delegation for every existing tenant.
  [agora-next#1567](https://github.com/voteagora/agora-next/pull/1567)
- **Auth hardening sweep** — migrated forum actions from per-action custom
  signatures to reusable SIWE JWT, moved attachment/RBAC authorization
  server-side instead of trusting client flags, gated admin APIs.
  [agora-next#1437](https://github.com/voteagora/agora-next/pull/1437)
- **Sybil resistance for Optimism citizenship** — multi-factor trust scoring
  (Human Passport tiers, OpenRank social trust), guided registration wizard,
  seasonal citizenship data model.
  [op-atlas#1465](https://github.com/voteagora/op-atlas/pull/1465)
- **Production relay debugging** — traced failed sponsored `delegateBySig`
  delegations to gas limits set too close to actual usage; fixed relay gas
  policy and frontend completion state from real traces.
  [agora-next#1514](https://github.com/voteagora/agora-next/pull/1514)
- **Resumable contract publishing** — reworked a long-running publishing
  workflow around PostgreSQL bind limits: batched processing, persisted
  progress, idempotent resumption, and UI progress over the whole flow.
  [op-atlas#1441](https://github.com/voteagora/op-atlas/pull/1441)
- **Go, upstream (under review)** — authenticating incoming Telegram webhooks
  with registered secrets and constant-time comparison.
  [superplane#6702](https://github.com/superplanehq/superplane/pull/6702)

Product write-ups:
[Safe Wallet Improvements](https://www.agora.xyz/blogs/15-safe-wallet-improvements) ·
[Notifications Hub](https://www.agora.xyz/blogs/9-notification-hub)

#### Production systems (private repos)

Most of my recent engineering output lives in Agora's private repositories:

- **TakeAIt** — a managed coding-agent platform where Claude Code and Codex
  agents claim tickets, execute in isolated GCP workspaces, open pull
  requests, and pause for human input. Next.js/PostgreSQL control plane,
  zero-inbound Go runners, journal/replay crash recovery.
- **[holders.vote](https://holders.vote)** — a web3 take on Reddit: voting
  weight from onchain holdings. Hardened authorization boundaries and
  webhook verification; built an EIP-712 trust-graph vouching flow with
  score-driven content ranking. *(live product, private code)*
- **Notifications Hub** — the five-channel notification platform behind
  Agora's governance products: verification, per-event preferences, retries,
  deduplication, delivery analytics.

#### Beyond Agora (also private code)

- **[Pingou](https://pingou.xyz)** (solo · in closed pilot) — paid-alerts
  platform for Brazilian streamers, built end to end: Pix and card checkout,
  SSE-driven OBS overlay, ~150k-LOC TypeScript monorepo with ~1,900 tests.
- **Lifeverse** (2023–present · DAO council + fractional lead) — Arbitrum
  gaming ecosystem: deterministic battle simulator, soulbound ERC-721s with
  onchain metadata, commit-reveal randomness, indexers, Snapshot strategy.
- **Sekai Glory** (2024–2025) — led a production trading-card game on Ronin:
  16 UUPS-upgradeable ERC-721A/ERC-1155 contracts, real-time PvP
  matchmaking, five languages, live migration from Blast to Ronin.
- **Realm** (2023–2024) — fully onchain game on Arbitrum One: 55 game
  domains, 176 contracts live on mainnet, three subgraphs, an AWS rewards
  engine, Terraform infra.
- **TCDF, Brazil's Federal District Court of Auditors** (2014–present ·
  long-term part-time) — twelve years of audit systems (Symfony/API Platform,
  Vue/TypeScript, SQL Server, Kubernetes), plus ChatTCDF, the Court's
  internal RAG chatbot.

#### Elsewhere

[Portfolio](https://lucasfranca.dev) ·
[LinkedIn](https://linkedin.com/in/lucasagfranca) ·
[Web3 résumé](https://lucasfranca.dev/resume/Lucas_Franca_Web3_Resume.pdf) ·
[AI-platforms résumé](https://lucasfranca.dev/resume/Lucas_Franca_AI_Agent_Platforms_Resume.pdf) ·
lucasagfranca@gmail.com
