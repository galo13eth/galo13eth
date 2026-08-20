### Lucas Franca — Senior Web3 Product Engineer

I ship wallet-connected products end to end — Solidity contracts, indexed
onchain data, Go and TypeScript services, React frontends — as one production
system. Currently at [Agora](https://www.agora.xyz), building governance
infrastructure for **Optimism, ENS, and Uniswap**.

12+ years in software · 4+ years shipping Web3 · Ethereum, Optimism,
Arbitrum, Ronin

#### Selected public work

90 merged PRs across Agora's public repos
([agora-next](https://github.com/voteagora/agora-next/pulls?q=is%3Apr+author%3Agalo13eth+is%3Amerged),
[op-atlas](https://github.com/voteagora/op-atlas/pulls?q=is%3Apr+author%3Agalo13eth+is%3Amerged)).
A few worth reading:

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
- **Safe SIWE flows** — routed draft-proposal access through the Safe-aware
  SIWE helper and enabled tracked Safe signing across a dozen tenants.
  [agora-next#1488](https://github.com/voteagora/agora-next/pull/1488) ·
  [write-up](https://www.agora.xyz/blogs/15-safe-wallet-improvements)
- **Idempotent onchain attestations** — prevented duplicate EAS citizen
  attestations under concurrent registration.
  [op-atlas#1477](https://github.com/voteagora/op-atlas/pull/1477)
- **Secure push subscriptions** — SIWE-authenticated PWA push registration
  with tenant gating and rollback on failure.
  [agora-next#1384](https://github.com/voteagora/agora-next/pull/1384) ·
  [write-up](https://www.agora.xyz/blogs/9-notification-hub)
- **Go, upstream (under review)** — authenticating incoming Telegram webhooks
  with registered secrets and constant-time comparison.
  [superplane#6702](https://github.com/superplanehq/superplane/pull/6702)

#### Production systems (private repos)

Most of my output lives in Agora's internal repos — 270 merged PRs in the
past year across three systems:

- **[holders.vote](https://holders.vote)** — a web3 take on Reddit:
  communities anchored to ENS/HNS names, where voting weight comes from
  onchain holdings. I hardened authorization boundaries and webhook
  verification, integrated the Notifications Hub, and built an EIP-712
  trust-graph vouching flow with score-driven content ranking.
  *(live product, private code)*
- **Notifications Hub** — the five-channel notification platform (email,
  Discord, Slack, Telegram, browser push) behind Agora's governance products:
  channel verification, per-event preferences, retries, deduplication,
  delivery analytics.
  [write-up](https://www.agora.xyz/blogs/9-notification-hub)
- **TakeAIt** — a managed coding-agent platform where Claude Code and Codex
  agents claim tickets, execute in isolated GCP workspaces, open pull
  requests, and pause for human input. Next.js/PostgreSQL control plane,
  zero-inbound Go runners, journal/replay crash recovery.

#### Beyond Agora (also private code)

- **Lifeverse** (2023–present · DAO council + fractional lead engineering) —
  Arbitrum gaming ecosystem in the Treasure/MAGIC community: built Colosseum
  of Phanes (Remix/React, a deterministic battle simulator with determinism
  tests, SSE notifications, wallet auth, Fly.io), contracts for soulbound
  ERC-721s with onchain metadata, commit-reveal randomness, and ERC-20 reward
  claims, The Graph indexers, a Snapshot voting strategy, and the Python
  pipeline behind a 4,686-token art collection.
- **Sekai Glory** (2024–2025) — led full-stack delivery of a production
  trading-card game on Ronin: a Next.js PWA in five languages, 16
  UUPS-upgradeable ERC-721A/ERC-1155 contracts with 20 Forge test suites, a
  13-datasource subgraph, real-time PvP matchmaking, and the live migration
  from Blast to Ronin.
- **Realm** (2023–2024) — fully onchain game ecosystem on Arbitrum One,
  delivered across a Solidity monorepo spanning 55 game domains (176
  contracts live on mainnet), three subgraphs indexing 116 contracts, the
  Next.js player app, an AWS Lambda ARB-rewards engine, and
  Terraform-managed infrastructure.
- **Federal District Court of Auditors (TCDF)** (2014–present) — twelve years
  of public-sector systems supporting audits of government spending: leading
  committer on the Court's electronic case-tracking, accounts-rendering, and
  official-gazette platforms (Symfony/API Platform + Vue/TypeScript on SQL
  Server, Docker/Kubernetes), plus ChatTCDF, the Court's internal RAG
  chatbot.

#### Elsewhere

[Portfolio](https://lucasfranca-portfolio-production.up.railway.app) ·
[LinkedIn](https://linkedin.com/in/lucasagfranca) ·
[Web3 résumé](https://lucasfranca-portfolio-production.up.railway.app/resume/Lucas_Franca_Web3_Resume.pdf) ·
[AI-platforms résumé](https://lucasfranca-portfolio-production.up.railway.app/resume/Lucas_Franca_AI_Agent_Platforms_Resume.pdf) ·
lucasagfranca@gmail.com
