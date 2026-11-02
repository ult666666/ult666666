# Charles Dai

**Carnegie Mellon University** · Human-Computer Interaction

I'm a Human-Computer Interaction student at CMU. Most of what I build focuses on order-matching engines, ledgers, data pipelines and tools that check AI output. I mostly write Python, JavaScript, C++, TypeScript, SQL and Rust. I'm always looking for challenges in software engineering, agentic AI engineering, fintech and data science.

[Portfolio](https://ult666666.github.io/) · [Project explorer](https://ult666666.github.io/projects/catalog.html) · [Fintech work](https://ult666666.github.io/fintech.html) · [Agent skills on Agensi](https://agensi.io) · [Email](mailto:hello@madebymotionx.com)

## Featured: agent skills

I also write agent skills: 20 skills in the `SKILL.md` format for Claude Code, Codex and other coding agents. Each is a short workflow plus a small offline script, so the agent works from numbers that come out the same on every run. They cover security checks, API and database migration review, data and finance audits, and LLM evals.

The skills are sold on [Agensi](https://agensi.io), a SKILL.md marketplace.

## Selected projects

| Project | What it is | Try it |
| --- | --- | --- |
| **[crossbook](https://github.com/ult666666/crossbook)** · Rust | An order-matching engine with opening and closing call auctions, crash recovery and a market-data feed. A second, simpler engine checks every event, and the output is the same on every platform, in the browser and on any number of threads. | [Playground](https://ult666666.github.io/crossbook/) · [Case study](https://ult666666.github.io/projects/crossbook.html) |
| **[Frontier AI Valuation Lab](https://github.com/ult666666/frontier-ai-valuation-lab)** · fintech | A valuation and financing tool for illustrative frontier AI lab scenarios, with seeded Monte Carlo value ranges. Separate Python scripts recheck the arithmetic. | [Live studio](https://frontier-ai-valuation-lab.vercel.app/capital.html#worked-decision) · [How the math is checked](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/docs/VERIFICATION.md) |
| **[LineageGuard Studio](https://github.com/ult666666/lineageguard-datahub-agent)** · AI engineering | Reviews a database schema change before it breaks a downstream dashboard, using lineage from DataHub or a dbt manifest. A 105-case labelled benchmark in CI keeps its decisions from getting more lenient. | [Live demo](https://lineageguard-datahub-agent.vercel.app/) · [Case study](https://ult666666.github.io/projects/lineageguard.html) |
| **[SaaS Analytics Warehouse](https://github.com/ult666666/saas-analytics-warehouse)** · data | Revenue and retention metrics for a fictional SaaS company, built and tested in dbt and DuckDB, with incremental loads checked against a full refresh. | [Report](https://ult666666.github.io/saas-analytics-warehouse/) · [Metric definitions](https://github.com/ult666666/saas-analytics-warehouse/blob/main/docs/METRICS.md) |
| **[ledgerline](https://github.com/ult666666/ledgerline)** · backend | A double-entry ledger API with holds (two-phase transfers). Every entry must balance, and a retried request can't post twice. | [API walkthrough](https://github.com/ult666666/ledgerline/blob/main/docs/API_WALKTHROUGH.md) · [Design notes](https://github.com/ult666666/ledgerline/blob/main/docs/DESIGN.md) |
| **[Luma Keys](https://github.com/ult666666/luma-keys)** · product | A piano practice app for macOS with sheet music, falling notes and two 3-D hands that show the fingering. | [Overview](https://ult666666.github.io/#luma-keys) · [Hand motion design](https://github.com/ult666666/luma-keys/blob/main/docs/HAND_MOTION_DESIGN.md) |

## How I work

I check my work against answers I didn't write myself. quantkit reproduces textbook option prices, powerlift matches published sequential-testing tables, and crossbook runs every command through two separate engines.

Each README opens with what the project does and the few commands to run it. Hosted demos use synthetic data, and the READMEs say what a project doesn't do. I use AI coding assistants, then review, test and document what they produce.

<details>
<summary><strong>All 21 projects by area</strong></summary>

#### Agent skills and developer tooling

| Project | What it is | Stack |
| --- | --- | --- |
| Agent skills (on [Agensi](https://agensi.io)) | 20 offline SKILL.md skills for security scans, API and migration checks, data audits and LLM evals | Python |

#### Finance

| Project | What it is | Stack |
| --- | --- | --- |
| [crossbook](https://github.com/ult666666/crossbook) | Order-matching engine with call auctions and a WebAssembly playground | Rust, WebAssembly |
| [Frontier AI Valuation Lab](https://github.com/ult666666/frontier-ai-valuation-lab) | Valuation and financing tool for frontier AI labs, with Monte Carlo value ranges | JavaScript, Node.js, Python |
| [quantkit](https://github.com/ult666666/quantkit) | Option pricing, portfolio optimization, VaR backtests and a backtester that can't see future prices | Python, NumPy, SciPy |
| [ledgerline](https://github.com/ult666666/ledgerline) | Double-entry ledger API with idempotent writes, holds and race-free overdraft checks | FastAPI, PostgreSQL |
| [Agentic Trading Research](https://github.com/ult666666/agentic-trading-research) | Language models suggest stock ideas, and plain Python checks and backtest-overfitting tests decide which survive. It cannot place orders | Python |

#### Data

| Project | What it is | Stack |
| --- | --- | --- |
| [SaaS Analytics Warehouse](https://github.com/ult666666/saas-analytics-warehouse) | MRR, cohort retention and unit economics for a fictional SaaS company, with incremental loads and SCD2 history | dbt, DuckDB, SQL |
| [powerlift](https://github.com/ult666666/powerlift) | A/B and A/B/n test statistics checked against SciPy, statsmodels and published tables | Python, SciPy |
| [Impact Ledger](https://github.com/ult666666/impact-ledger) | Attendance and spending reports for a fictional nonprofit that never count anyone twice, with a hash-chained audit log | TypeScript, Python, SQLite |

#### AI and backend

| Project | What it is | Stack |
| --- | --- | --- |
| [LineageGuard Studio](https://github.com/ult666666/lineageguard-datahub-agent) | Reviews database schema changes, with lineage from DataHub or a dbt manifest, and keeps the evidence behind each verdict | Node.js, SQLite |
| [citecheck](https://github.com/ult666666/citecheck) | Answers questions from your documents and flags any claim its sources don't support | Python, Claude API, SQLite |
| [TraceBench](https://github.com/ult666666/tracebench) | Catches regressions in recorded AI outputs and tells them from noise with statistical gates | Python |
| [RelayBox](https://github.com/ult666666/relaybox) | A webhook inbox that drops duplicate deliveries, and a signed sender with retries and replay | Python, SQLite |
| [searchlite](https://github.com/ult666666/searchlite) | A search engine written from scratch that explains each result's ranking and skips work without changing the results | TypeScript |
| [ProofCast](https://github.com/ult666666/proofcast-backblaze) | Generates narration and cover art locally, hashes every file, signs the manifest and logs it in a Merkle transparency log | Python, Streamlit |

#### Product and design

| Project | What it is | Stack |
| --- | --- | --- |
| [Luma Keys](https://github.com/ult666666/luma-keys) | Piano practice app with sheet music, falling notes and 3-D hands | Electron, React, three.js |
| [MOTIONX Studio](https://github.com/ult666666/motionx-studio) | The website for my motion-design studio, [madebymotionx.com](https://madebymotionx.com/) | Next.js, TypeScript |
| [ContrastKit](https://github.com/ult666666/contrastkit) | Checks color contrast, finds the nearest passing color with the same hue and simulates color vision deficiency at any severity | TypeScript, React |
| [Blast Radius Daily](https://github.com/ult666666/blast-radius-daily) | A one-minute Reddit puzzle about containing a bad schema change, playable by keyboard | TypeScript, Devvit |

#### Small tools and coursework

| Project | What it is | Stack |
| --- | --- | --- |
| [JUST-QR](https://github.com/ult666666/JUST-QR) | A QR code generator with its own ISO/IEC 18004 encoder and PNG export, tested against a scanner | JavaScript |
| [Teen Budgeting](https://github.com/ult666666/teen-budgeting-hw3) | A classroom budgeting demo with fictional data | Node.js |

</details>

## Toolkit

- Languages: Python, TypeScript, C++, JavaScript, SQL, Rust, HTML and CSS
- Backend and data: FastAPI, Node.js, PostgreSQL, SQLite, DuckDB, dbt, pandas, NumPy, SciPy
- AI: Claude API (tool use, prompt caching, refusals), retrieval, offline evals
- Frontend: React, Next.js, Vite, Tailwind CSS, Electron, three.js, WebAssembly
- Testing: pytest, Hypothesis, proptest, Vitest, Playwright, mypy, Clippy, GitHub Actions

## Contact

Email [hello@madebymotionx.com](mailto:hello@madebymotionx.com) or start from the [portfolio](https://ult666666.github.io/#contact).

<sub>None of these projects is in production use. Company names in the valuation demo are research subjects, with no affiliation or endorsement implied.</sub>
