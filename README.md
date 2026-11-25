# Hi, I'm TTB8 👋

**Full-stack & Web3 consultant.** I help companies design, build and ship production platforms end to end: from the database and APIs to the frontend, payments, smart contracts and the infrastructure that keeps it all running.

Based in Barcelona 🇪🇸 · Working with teams worldwide

> 💼 **Available for consulting engagements.** If you need a platform built, an MVP taken to production, or a blockchain integration done properly, let's talk.

---

## ⭐ Featured projects

Open-source reference implementations of problems I solve for clients. Each one is tested end to end in CI and explains its design decisions.

**[💳 subscription-billing-engine](https://github.com/TTB8/subscription-billing-engine)**
Stripe subscription billing done properly: fixed-day cycles, prepaid terms, dunning, refunds, and webhooks and renewals that are safe to run twice. An append-only ledger means no charge can ever happen twice.

`TypeScript` `NestJS` `Prisma` `PostgreSQL` `Stripe`

**[⛓️ onchain-settlement-bridge](https://github.com/TTB8/onchain-settlement-bridge)**
Keeps a database ledger authoritative while tokens settle on-chain. Compliance is enforced by the contracts, a transactional outbox handles delivery, reorgs are handled safely, and a reconciler catches anything the ledger didn't authorise.

`Solidity` `Foundry` `viem` `NestJS` `Prisma` `PostgreSQL`

**[🕸️ resilient-scraping-pipeline](https://github.com/TTB8/resilient-scraping-pipeline)**
A polite web data pipeline that is resumable, reproducible and validated: a content-addressed cache, a deterministic offline parse, data contracts with quarantine, and block detection instead of evasion.

`Python` `httpx` `Playwright` `pydantic` `DuckDB`

## 🛠️ What I do

- **Product platforms, end to end.** Monorepo architectures with multiple apps (customer, admin, ops, partner portals) sharing one typed API and data model.
- **Payments & subscriptions.** Stripe billing engines with custom cycles, prepaid terms, dunning and webhooks that reconcile cleanly.
- **Web3 integration that fits real businesses.** Bridging off-chain ledgers with on-chain settlement: compliance-gated token contracts, smart wallets and gasless (sponsored) transactions.
- **Production readiness.** CI/CD, infrastructure as code, monitoring, automated backups with restore drills, E2E and accessibility testing.
- **Data pipelines.** Large-scale scraping and data extraction pipelines in Python that feed analytics and pricing teams.

## 📂 Client work

**🌸 Subscription commerce platform** · *Perth, Australia*
Flower subscription business built from scratch: storefront, customer app, operations dashboard and supplier portal on one NestJS API. 28-day billing cycles on Stripe, prepaid terms, Google sign-in with 2FA, transactional email, Playwright + axe test suite, and automated database backups with scheduled restore drills.

`NestJS` `Next.js` `PostgreSQL` `Prisma` `Stripe` `Sentry` `Render` `GitHub Actions`

**⚡ Tokenized energy investment platform**
A bridge between an off-chain banking/accounting core and on-chain settlement. Investors onboard with embedded smart wallets and sponsored gas; Solidity contracts enforce a KYC whitelist and handle mint, lock and transfer, while background workers handle payouts, notifications and document generation.

`Solidity` `Foundry` `NestJS` `BullMQ` `Redis` `viem` `wagmi` `Privy` `Terraform` `AWS`

**📊 Competitive pricing data pipelines** · *Travel-tech*
Python pipelines that collect and structure product data at scale, with batching, block detection, retries and validation against a data contract.

`Python` `Playwright` `pandas`

## 🧰 Tech stack

**Languages**
<br>
<img src="https://skillicons.dev/icons?i=ts,js,solidity,py" />

**Backend & data**
<br>
<img src="https://skillicons.dev/icons?i=nestjs,nodejs,postgres,prisma,redis" />

**Frontend**
<br>
<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind" />

**Infra & tooling**
<br>
<img src="https://skillicons.dev/icons?i=docker,terraform,aws,githubactions" />

Also: Stripe · Foundry · viem / wagmi / RainbowKit · Chainlink VRF & Automation · Playwright · httpx · pydantic · DuckDB · Sentry · BullMQ · Render · pnpm monorepos · uv

## 🔍 Smaller samples

| Repo | What it shows |
|---|---|
| [lnet-boilerplate](https://github.com/TTB8/lnet-boilerplate) | Foundry template for meta-transaction (trusted forwarder) contracts, with full test suite |
| [foundry-smart-contract-lottery-f23](https://github.com/TTB8/foundry-smart-contract-lottery-f23) | Provably random raffle using Chainlink VRF and Automation |
| [ts-nft-marketplace-cu](https://github.com/TTB8/ts-nft-marketplace-cu) | Full-stack NFT marketplace with indexing and USDC payments |
| [ts-tsender-ui-cu](https://github.com/TTB8/ts-tsender-ui-cu) | Next.js UI for gas-efficient ERC-20 airdrops, with E2E tests |

## 📫 Let's work together

Have a project in mind? Message me on LinkedIn and tell me what you're building.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stefano-goetschel-viniegra-9404239a/)
