### Lucas Franca — Senior Web3 Product Engineer

I ship wallet-connected products end to end — Solidity contracts, indexed
onchain data, Go and TypeScript services, React frontends — as one production
system. Currently at [Agora](https://www.agora.xyz), building governance
infrastructure for **Optimism, ENS, and Uniswap**, and TakeAIt, a managed
coding-agent platform on GCP with isolated Go runners.

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

#### Elsewhere

[Portfolio](https://lucasfranca-portfolio-production.up.railway.app) ·
[LinkedIn](https://linkedin.com/in/lucasagfranca) ·
[Web3 résumé](https://lucasfranca-portfolio-production.up.railway.app/resume/Lucas_Franca_Web3_Resume.pdf) ·
[AI-platforms résumé](https://lucasfranca-portfolio-production.up.railway.app/resume/Lucas_Franca_AI_Agent_Platforms_Resume.pdf) ·
lucasagfranca@gmail.com
