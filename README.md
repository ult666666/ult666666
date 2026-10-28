# Charles Dai

**Carnegie Mellon University** · Business, with a second major in Human-Computer Interaction (in progress)

I build software where the numbers have to be right: matching engines and ledgers, data pipelines, and AI tools whose output gets checked. I work mostly in Python, TypeScript, SQL and Rust, and I'm looking for software engineering, AI engineering, fintech and data internships.

[**Portfolio**](https://ult666666.github.io/) · [**Project explorer**](https://ult666666.github.io/projects/catalog.html) · [Fintech work](https://ult666666.github.io/fintech.html) · [Email](mailto:hello@madebymotionx.com)

## Selected projects

| Project | What it is | Try it |
| --- | --- | --- |
| **[crossbook](https://github.com/ult666666/crossbook)** · Rust | An order-matching engine with price-time priority, IOC, FOK, post-only and self-trade prevention. A second, deliberately simple engine checks every event, and results match bit for bit on Linux, macOS, Windows and in the browser. | [Playground](https://ult666666.github.io/crossbook/) · [Case study](https://ult666666.github.io/projects/crossbook.html) |
| **[Frontier AI Valuation Lab](https://github.com/ult666666/frontier-ai-valuation-lab)** · fintech | A valuation and financing studio for illustrative frontier-AI-lab scenarios, with a separate Python check of the arithmetic. | [Live studio](https://frontier-ai-valuation-lab.vercel.app/capital.html#worked-decision) · [How the math is checked](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/docs/VERIFICATION.md) |
| **[LineageGuard Studio](https://github.com/ult666666/lineageguard-datahub-agent)** · AI engineering | Reviews a database schema change before it breaks a downstream dashboard, and keeps the evidence behind each verdict. | [Live demo](https://lineageguard-datahub-agent.vercel.app/) · [Case study](https://ult666666.github.io/projects/lineageguard.html) |
| **[SaaS Analytics Warehouse](https://github.com/ult666666/saas-analytics-warehouse)** · data | Revenue and retention metrics for a fictional SaaS company, modeled and tested in dbt and DuckDB. | [Report](https://ult666666.github.io/saas-analytics-warehouse/) · [Metric definitions](https://github.com/ult666666/saas-analytics-warehouse/blob/main/docs/METRICS.md) |
| **[ledgerline](https://github.com/ult666666/ledgerline)** · backend | A double-entry ledger API. Every entry has to balance, and a retried request can't post twice. | [API walkthrough](https://github.com/ult666666/ledgerline/blob/main/docs/API_WALKTHROUGH.md) · [Design notes](https://github.com/ult666666/ledgerline/blob/main/docs/DESIGN.md) |
| **[Luma Keys](https://github.com/ult666666/luma-keys)** · product | A piano practice app for macOS with sheet music, falling notes and two 3-D hands that play the planned fingering. | [Overview](https://ult666666.github.io/#luma-keys) · [Hand motion design](https://github.com/ult666666/luma-keys/blob/main/docs/HAND_MOTION_DESIGN.md) |

## How I work

- **Checked against answers I didn't write.** quantkit reproduces textbook option prices, powerlift matches published sequential-testing tables, and crossbook runs every command through two independent engines.
- **Runnable in minutes.** Each README starts with what the project does and the few commands that show it working.
- **Honest scope.** Hosted demos run on synthetic data, and each README says what the project does not do. I build with AI coding assistants, then review, test and document the results.

<details>
<summary><strong>All 20 projects by area</strong></summary>

**Finance**

| Project | What it is | Stack |
| --- | --- | --- |
| [crossbook](https://github.com/ult666666/crossbook) | Deterministic order-matching engine with a WebAssembly playground | Rust, WebAssembly |
| [Frontier AI Valuation Lab](https://github.com/ult666666/frontier-ai-valuation-lab) | Valuation and financing studio for frontier AI labs | JavaScript, Node.js, Python |
| [quantkit](https://github.com/ult666666/quantkit) | Option pricing, portfolio optimization and a backtester that can't peek at tomorrow's prices | Python, NumPy, SciPy |
| [ledgerline](https://github.com/ult666666/ledgerline) | Double-entry ledger API with idempotent writes and race-free overdraft checks | FastAPI, PostgreSQL |
| [Agentic Trading Research](https://github.com/ult666666/agentic-trading-research) | Language models suggest stock ideas and plain Python checks decide which survive; no order execution | Python |

**Data**

| Project | What it is | Stack |
| --- | --- | --- |
| [SaaS Analytics Warehouse](https://github.com/ult666666/saas-analytics-warehouse) | MRR, cohort retention and unit economics for a fictional SaaS company | dbt, DuckDB, SQL |
| [powerlift](https://github.com/ult666666/powerlift) | A/B test statistics checked against SciPy, statsmodels and published tables | Python, SciPy |
| [Impact Ledger](https://github.com/ult666666/impact-ledger) | Attendance and spending reports for a fictional nonprofit that never count the same person twice | TypeScript, Python, SQLite |

**AI and backend**

| Project | What it is | Stack |
| --- | --- | --- |
| [LineageGuard Studio](https://github.com/ult666666/lineageguard-datahub-agent) | Reviews database schema changes and keeps the evidence behind each verdict | Node.js, SQLite |
| [citecheck](https://github.com/ult666666/citecheck) | Answers questions from your documents and flags any sentence its sources don't support | Python, Claude API, SQLite |
| [TraceBench](https://github.com/ult666666/tracebench) | Catches regressions in recorded AI outputs and does the token-cost arithmetic exactly | Python |
| [RelayBox](https://github.com/ult666666/relaybox) | A webhook inbox that won't process the same delivery twice | Python, SQLite |
| [searchlite](https://github.com/ult666666/searchlite) | A search engine written from scratch that explains why each result ranked where it did | TypeScript |
| [ProofCast](https://github.com/ult666666/proofcast-backblaze) | Makes narration and cover art locally and fingerprints every file with SHA-256 | Python, Streamlit |

**Product and design**

| Project | What it is | Stack |
| --- | --- | --- |
| [Luma Keys](https://github.com/ult666666/luma-keys) | Offline piano practice app with sheet music, falling notes and 3-D hands | Electron, React, three.js |
| [MOTIONX Studio](https://github.com/ult666666/motionx-studio) | The website for my motion-design studio, [madebymotionx.com](https://madebymotionx.com/) | Next.js, TypeScript |
| [ContrastKit](https://github.com/ult666666/contrastkit) | Checks color contrast and finds the nearest passing color without changing the hue | TypeScript, React |
| [Blast Radius Daily](https://github.com/ult666666/blast-radius-daily) | A one-minute Reddit puzzle about stopping a bad schema change from spreading | TypeScript, Devvit |

**Small tools and coursework**

| Project | What it is | Stack |
| --- | --- | --- |
| [JUST-QR](https://github.com/ult666666/JUST-QR) | A QR code generator with input recovery and scanner-checked PNG export | JavaScript |
| [Teen Budgeting](https://github.com/ult666666/teen-budgeting-hw3) | A classroom budgeting demo with fictional data | Node.js |

</details>

## Toolkit

- **Languages:** Python, TypeScript and JavaScript, SQL, Rust, HTML and CSS
- **Backend and data:** FastAPI, Node.js, PostgreSQL, SQLite, DuckDB, dbt, pandas, NumPy, SciPy
- **AI engineering:** Claude API (tool use, prompt caching, refusal handling), retrieval, offline evaluation
- **Frontend:** React, Next.js, Vite, Tailwind CSS, Electron, three.js, WebAssembly
- **Quality:** pytest, Hypothesis, proptest, Vitest, Playwright, mypy, Clippy, GitHub Actions

## Contact

Email [hello@madebymotionx.com](mailto:hello@madebymotionx.com), or start from the [portfolio](https://ult666666.github.io/#contact).

<sub>Projects include libraries, deployed demos, research snapshots and coursework, built with AI assistance. Hosted demos use synthetic data, and none claims production use or customers. Company names in the valuation demo identify research subjects and imply no affiliation or endorsement.</sub>
