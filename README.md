# Charles Dai

**Carnegie Mellon University** · Software, AI and HCI

I build software for finance, data and AI products in Python, TypeScript and SQL. I focus on clear interfaces, reliable data flows and inspectable results. My work connects product engineering with finance, analytics and applied AI; the projects link their demos to implementation, checks and explicit scope.

[**Portfolio & case studies ↗**](https://ult666666.github.io/) · [**Project explorer ↗**](https://ult666666.github.io/projects/catalog.html) · [Fintech work](https://ult666666.github.io/fintech.html) · [Engineering lab](https://ult666666.github.io/projects/engineering-lab.html) · [MOTIONX studio](https://madebymotionx.com/)

**Explore by specialty:** [Fintech](https://ult666666.github.io/#frontier-ai-valuation-lab) · [AI engineering](https://ult666666.github.io/#lineageguard) · [Data analytics](https://ult666666.github.io/projects/catalog.html#saas-analytics-warehouse) · [Product / accessibility](https://ult666666.github.io/projects/catalog.html#contrastkit)

## Selected projects

| Project | What to inspect | Demo and evidence |
| --- | --- | --- |
| **[Frontier AI Valuation Lab](https://github.com/ult666666/frontier-ai-valuation-lab)** · fintech | Illustrative capital decisions, ownership scenarios and a separately checked Python calculation reference. | [Interactive studio](https://frontier-ai-valuation-lab.vercel.app/capital.html#worked-decision) · [Verification](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/docs/VERIFICATION.md) |
| **[LineageGuard Studio](https://github.com/ult666666/lineageguard-datahub-agent)** · AI engineering | Compose typed review workflows, trace evidence and inspect reproducible decisions. | [Live demo](https://lineageguard-datahub-agent.vercel.app/) · [Engineering review](https://github.com/ult666666/lineageguard-datahub-agent/blob/main/docs/ENGINEERING_REVIEW.md) |
| **[SaaS Analytics Warehouse](https://github.com/ult666666/saas-analytics-warehouse)** · data analytics | Synthetic SaaS metrics through dbt, DuckDB, reconciled MRR, cohorts and data-quality tests. | [Report preview](https://ult666666.github.io/saas-analytics-warehouse/) · [Metric definitions](https://github.com/ult666666/saas-analytics-warehouse/blob/main/docs/METRICS.md) |
| **[Impact Ledger](https://github.com/ult666666/impact-ledger)** · data products | Accessible nonprofit participation and spending dashboard with a local SQLite API and atomic imports. | [Synthetic preview](https://ult666666.github.io/impact-ledger/) · [Verification](https://github.com/ult666666/impact-ledger/blob/main/docs/VERIFICATION.md) |
| **[ContrastKit](https://github.com/ult666666/contrastkit)** · HCI | WCAG 2.2 color checks, OKLCH palette fixes and color-vision simulation in a web app, library and CLI. | [Try the app](https://ult666666.github.io/contrastkit/) · [Source and tests](https://github.com/ult666666/contrastkit) |
| **[MOTIONX Studio](https://github.com/ult666666/motionx-studio)** · product engineering | Motion-first Next.js site plus a separately guarded Python outreach-validation workflow. | [Live site](https://madebymotionx.com/) · [Source and architecture](https://github.com/ult666666/motionx-studio) |

## Follow a complete workflow

- **[Operations handoff](https://ult666666.github.io/projects/engineering-lab.html#operations-handoff):** signed event → durable processing → validated import → reporting checks, using installed packages and synthetic records.
- **[Reference-checked foundations](https://ult666666.github.io/projects/foundations.html):** inspect pricing, statistics, ledger invariants, retrieval and contrast calculations alongside their proving code.
- **[Research review gate](https://github.com/ult666666/agentic-trading-research/tree/main/examples):** run six synthetic scenarios and inspect why incomplete evidence blocks a research result.
- **[Compare saved reviews](https://github.com/ult666666/lineageguard-datahub-agent/blob/main/docs/REVIEW_COMPARISON.md):** validate both exported packages before comparing recorded decisions, with current evidence freshness shown separately; internal consistency is not authenticated approval.

[Browse all 19 projects by scenario, technology and area →](https://ult666666.github.io/projects/catalog.html)

<details>
<summary><strong>Complete project index — finance, data, AI, backend and HCI</strong></summary>

## Projects by area

**Finance and fintech**

| Project | What it does | Stack |
| --- | --- | --- |
| [quantkit](https://github.com/ult666666/quantkit) | Options pricing (Black–Scholes–Merton, binomial, Monte Carlo), portfolio optimization and a backtester whose no-look-ahead rule is enforced by tests | Python · NumPy · SciPy · pandas |
| [ledgerline](https://github.com/ult666666/ledgerline) | Double-entry ledger API: balanced, immutable journal entries, idempotent writes and race-free overdraft checks | FastAPI · SQLAlchemy · PostgreSQL |
| [Agentic Trading Research](https://github.com/ult666666/agentic-trading-research) | Research-only architecture plus a [runnable synthetic fail-closed gate](https://github.com/ult666666/agentic-trading-research/tree/main/examples) with negative tests; no automated order execution · [case study](https://ult666666.github.io/projects/trading-research.html) | Python · JSON Schema |

**Data and analytics**

| Project | What it does | Stack |
| --- | --- | --- |
| [saas-analytics-warehouse](https://github.com/ult666666/saas-analytics-warehouse) | Tested dbt warehouse for a fictional SaaS company: MRR movements, cohort retention and unit economics | dbt · DuckDB · SQL · Python |
| [powerlift](https://github.com/ult666666/powerlift) | A/B-test statistics plus a seeded CSV → allocation check → CUPED readout, with power, sequential and Bayesian methods checked against SciPy and statsmodels | Python · SciPy |
| [Impact Ledger](https://github.com/ult666666/impact-ledger) | Reporting dashboard that separates unique people, attendance and session spending, with atomic CSV validation · [synthetic demo](https://ult666666.github.io/impact-ledger/) | TypeScript · Python · SQLite |

**Backend reliability and AI engineering**

| Project | What it does | Stack |
| --- | --- | --- |
| [RelayBox](https://github.com/ult666666/relaybox) | Signed webhook inbox: idempotent ingestion, durable SQLite jobs, fenced worker leases and bounded retries | Python · SQLite |
| [TraceBench](https://github.com/ult666666/tracebench) | Offline evaluation of recorded AI outputs: strict JSONL contracts, bilingual cases, exact token-cost arithmetic and baseline regression gates | Python |
| [citecheck](https://github.com/ult666666/citecheck) | Question answering over documents with the Claude API: every sentence must cite a retrieved passage, a checker flags unsupported claims, and an evaluation harness scores retrieval, citations and abstention | Python · Claude API · SQLite FTS5 |
| [searchlite](https://github.com/ult666666/searchlite) | Search engine built from scratch: BM25F ranking, query parser, phrase and fuzzy search, hybrid retrieval and nDCG evaluation · [relevance workbench](https://ult666666.github.io/searchlite/relevance.html) · [local labelled-query checks](https://github.com/ult666666/searchlite/blob/main/docs/LOCAL_RELEVANCE.md) | TypeScript |
| [LineageGuard Studio](https://github.com/ult666666/lineageguard-datahub-agent) | Typed agent-workflow runtime with evidence contracts, recovery and policy evaluations | Node.js · SQLite |
| [ProofCast](https://github.com/ult666666/proofcast-backblaze) | Local media generation, independent saved-file verification, SHA-256 provenance and opt-in Backblaze B2 storage | Python · Streamlit |

**Product, design and HCI**

| Project | What it does | Stack |
| --- | --- | --- |
| [contrastkit](https://github.com/ult666666/contrastkit) | WCAG contrast checks, perceptual color fixes and color-blindness simulation, as a library, a CI-ready CLI and a [web app](https://ult666666.github.io/contrastkit/) | TypeScript · React |
| [MOTIONX Studio](https://github.com/ult666666/motionx-studio) | Motion-first studio website with a separate Python outreach-validation workflow | Next.js · TypeScript · Python |
| [Blast Radius Daily](https://github.com/ult666666/blast-radius-daily) | One-minute Reddit puzzle game about the blast radius of schema changes · [play the offline incident](https://ult666666.github.io/projects/blast-radius-demo.html), with fictional tab-memory scores and votes | TypeScript · Devvit |
| [Luma Keys](https://github.com/ult666666/luma-keys) | Offline piano practice desktop app: numbered score, sheet music and falling notes, 3-D hands that play a planned fingering, graded sight reading and on-device PDF recognition · [portfolio card](https://ult666666.github.io/#luma-keys) · [isolated browser QA workflow](https://github.com/ult666666/luma-keys/blob/main/docs/BROWSER_QA.md) | Electron · React · three.js · Web Audio |

Also built: [JUST-QR](https://github.com/ult666666/JUST-QR), a browser QR generator with input recovery and scanner-checked PNG exports, and [Teen Budgeting](https://github.com/ult666666/teen-budgeting-hw3), a Node.js classroom demo.

</details>

## Toolkit

- **Languages:** Python, TypeScript/JavaScript, SQL, HTML/CSS
- **Backend and data:** FastAPI, Node.js, SQLAlchemy, PostgreSQL, SQLite, DuckDB, dbt, pandas, NumPy, SciPy
- **AI engineering:** Claude API (strict tool use, prompt caching, refusal handling), retrieval and offline evaluation
- **Frontend:** React, Next.js, Vite, Tailwind CSS, Electron, three.js, Web Audio
- **Quality:** pytest, Hypothesis, Vitest, Playwright, mypy, ESLint, GitHub Actions

## Get in touch

I'm looking for software engineering, AI engineering, fintech and data internships. Reach me through the [portfolio contact section](https://ult666666.github.io/#contact).

<sub>Projects include deployed apps, libraries, research snapshots, coursework and prototypes, built with AI assistance. Each README explains what can be run and what is out of scope; hosted demos use synthetic data, and none claims production use or customer adoption. Company names in the valuation demo identify independent research subjects and do not imply affiliation or endorsement.</sub>
