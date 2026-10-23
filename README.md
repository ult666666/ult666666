# Charles Dai

**Software developer · Fintech research tools · AI systems**

I'm a **Carnegie Mellon University student** building full-stack products and AI-assisted workflows. I care about clear interfaces, deterministic logic and evidence that a reviewer can inspect.

[**Portfolio & case studies ↗**](https://ult666666.github.io/) · [Fintech portfolio](https://ult666666.github.io/fintech.html) · [Public repositories](https://github.com/ult666666?tab=repositories) · [MOTIONX](https://madebymotionx.com/)

## Engineering lab: reliability, evaluation and useful reporting

Three independent, AI-assisted portfolio builds connect backend engineering and applied AI with clear operational reporting. Each includes synthetic examples, automated boundary tests, architecture notes, a reproducible quickstart and a Chinese handoff guide.

| Project | Problem it explores | Start the review |
| --- | --- | --- |
| **[RelayBox](https://github.com/ult666666/relaybox)** | Signed webhook ingestion, idempotent delivery IDs, transactional SQLite leases, stale-worker fencing and bounded retries. | [Architecture](https://github.com/ult666666/relaybox/blob/main/docs/ARCHITECTURE.md) · [Verification](https://github.com/ult666666/relaybox/blob/main/docs/VERIFICATION.md) |
| **[TraceBench](https://github.com/ult666666/tracebench)** | Reproducible offline evaluation of recorded AI outputs, bilingual cases, explicit token pricing and baseline regression gates. | [Method and architecture](https://github.com/ult666666/tracebench/blob/main/docs/ARCHITECTURE.md) · [Verification](https://github.com/ult666666/tracebench/blob/main/docs/VERIFICATION.md) |
| **[Impact Ledger](https://github.com/ult666666/impact-ledger)** | A TypeScript/Python reporting dashboard that separates unique people, attendance and session spending, with atomic CSV validation. | [Synthetic demo](https://ult666666.github.io/impact-ledger/) · [Verification](https://github.com/ult666666/impact-ledger/blob/main/docs/VERIFICATION.md) |

[**Explore the engineering lab ↗**](https://ult666666.github.io/projects/engineering-lab.html). The hosted reporting preview uses a synthetic snapshot; persistent imports run through the local API. These educational projects have explicit deployment limits and make no claims of production use or customer adoption.

## Featured: Frontier AI Valuation Lab

**Capital decisions, made inspectable.** An independent, AI-assisted full-stack fintech workspace connecting an explicit capital objective to hypothetical financing plans, scenario analysis and a portable business decision. Define the tradeoff, compare alternatives, verify the complete calculation through the API, and keep the reasoning behind a choice.

[**Open Capital Strategy Studio ↗**](https://frontier-ai-valuation-lab.vercel.app/capital.html#worked-decision) · [Engineering case study](https://ult666666.github.io/projects/frontier-ai-valuation-lab.html) · [Source](https://github.com/ult666666/frontier-ai-valuation-lab)

1. **Define and compare.** Enter a capital objective and a starting-stake retention floor. Inspect eligible plans, exact pricing and the equivalent accessible table. A funding shortfall, an ownership constraint and an invalid input have different meanings.
2. **Challenge the assumptions.** Compare the same plans across explicit operating scenarios. Inspect dominance, finite-scenario regret and switching values. Scenario counts are not probabilities; the comparison rule does not choose for the analyst.
3. **Record the judgment.** Name a preferred plan, its tradeoff, missing information and a review trigger. Keep an exact share link, recalculated JSON record or standalone brief. Late API responses cannot verify newer inputs.

| Engineering question | Where to look |
| --- | --- |
| How is the capital arithmetic checked? | A [pure calculation engine](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/public/lib/capital-strategy.js), [separate Python reference](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/scripts/check_capital_reference.py) and [boundary tests](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/tests/capital-strategy.test.js). |
| Can the entire decision cross the browser/API boundary? | The [API contract](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/docs/API.md), [real HTTP checks](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/tests/capital-api.test.js) and [browser workflow](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/tests/capital-browser.mjs). |
| What is a calculation versus a business judgment? | The [capital method and limits](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/docs/CAPITAL_STRATEGY.md) and [reproducible decision walkthrough](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/docs/DEMO_WALKTHROUGH.md). |

Application **4.0.0** retains financial engine **3.0.0** and the **18 October 2026 research snapshot**. Financing quotes and capital objectives are hypothetical inputs. Browser/API agreement establishes consistency, and the separate reference checks arithmetic; neither establishes forecast accuracy or investment returns. The earlier Model, Thesis Lab, Value Horizon and Research Casebook remain supporting workspaces. See the [verification record and its scope](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/docs/VERIFICATION.md).

## Agent engineering: LineageGuard Studio

**Compose a review. Understand every decision.** The Studio turns the original schema-change demo into an executable, typed workflow with evidence contracts, real step states, bounded retries and recovery. The hosted preview runs in the browser with synthetic tools; the separate local Node service adds durable SQLite checkpoints, revision checks and writer leases.

Try the source-outage scenario, restore its synthetic source and resume the same run. Inspect which evidence was reused, compare an additive alternative, and export the exact review. No paid inference, catalog mutation or SQL execution is enabled; deterministic components are not represented as an autonomous LLM team.

**Verify what leaves the workflow.** Review Inspector replays an exported review locally: evidence contracts, result-to-step agreement, deterministic conclusions and draft regeneration. It separates the recorded decision from current evidence freshness and guards JSON, Markdown and SQL exports. Files are not uploaded or restored as runnable state. Consistent is not authenticated; no execution is authorized.

[Inspector method and limits](https://github.com/ult666666/lineageguard-datahub-agent/blob/6ed607b5c9ff6f46f2bb3214b04d040b04c02c52/docs/REVIEW_INSPECTOR.md) · [Semantic verifier](https://github.com/ult666666/lineageguard-datahub-agent/blob/6ed607b5c9ff6f46f2bb3214b04d040b04c02c52/public/studio/core/inspection.js) · [Negative-case tests](https://github.com/ult666666/lineageguard-datahub-agent/blob/6ed607b5c9ff6f46f2bb3214b04d040b04c02c52/test/studio/inspection.test.mjs) · [Three-minute portfolio walkthrough](https://ult666666.github.io/projects/lineageguard.html#try-workflow)

[**Open Studio ↗**](https://lineageguard-datahub-agent.vercel.app/) · [Execution architecture](https://github.com/ult666666/lineageguard-datahub-agent/blob/main/docs/ARCHITECTURE.md) · [Recovery test](https://github.com/ult666666/lineageguard-datahub-agent/blob/main/test/studio/process-recovery.test.mjs) · [Verification and limits](https://github.com/ult666666/lineageguard-datahub-agent/blob/main/docs/VERIFICATION.md)

## More selected work

| Project | What it demonstrates | Explore |
| --- | --- | --- |
| **LineageGuard Studio** | A typed workflow composer and bounded execution runtime: source-bound evidence, cancellation/recovery, a separate SQLite local service and reproducible policy evaluations. | [Studio](https://lineageguard-datahub-agent.vercel.app/) · [Source](https://github.com/ult666666/lineageguard-datahub-agent) · [Case study](https://ult666666.github.io/projects/lineageguard.html) |
| **MOTIONX Studio** | A motion-first Next.js/TypeScript website, with a separate Python workflow for validated outreach drafts. | [Source](https://github.com/ult666666/motionx-studio) · [Live site](https://madebymotionx.com/) |
| **Agentic Trading Research** | A curated public architecture snapshot: model proposals, deterministic Python gates and evidence provenance. Research-only, with no automated order execution. | [Public snapshot](https://github.com/ult666666/agentic-trading-research) · [Case study](https://ult666666.github.io/projects/trading-research.html) |
| **ProofCast** | Local narration and accessible cover generation, SHA-256 asset provenance and opt-in Backblaze B2 integration. | [Source](https://github.com/ult666666/proofcast-backblaze) |

**Also built:** [Blast Radius Daily](https://github.com/ult666666/blast-radius-daily), a deterministic TypeScript/Devvit puzzle; [Teen Budgeting](https://github.com/ult666666/teen-budgeting-hw3), a Node.js classroom demo with server-computed totals; and [JUST-QR](https://github.com/ult666666/JUST-QR), a focused browser QR generator.

## Tools and approach

**Languages and interfaces:** Python, TypeScript, JavaScript, SQL, HTML/CSS, React, Next.js and Tailwind CSS.

**Systems and verification:** Node.js, REST APIs, JSON Schema, automated tests, GitHub Actions, Playwright, source provenance and human review boundaries.

I aim to make a project easy to try, its claims easy to inspect, and its failure states understandable. The [portfolio checks](https://github.com/ult666666/ult666666.github.io/actions/workflows/portfolio.yml) and [LineageGuard engineering review](https://github.com/ult666666/lineageguard-datahub-agent/blob/main/docs/ENGINEERING_REVIEW.md) provide further entry points into the implementation.

## Shipping the work responsibly

The portfolio itself has an [inspectable publication boundary](https://github.com/ult666666/ult666666.github.io/blob/main/docs/PUBLICATION_BOUNDARY.md): an exact public-file inventory, negative-case tests for accidental disclosure, and a byte-checked static release. The [engineering evidence routes](https://ult666666.github.io/#engineering-proof) connect the visible demos to methods, code and tests—not unsupported usage or performance claims.

## Let's connect

I'm interested in software engineering, AI engineering and product-focused internship opportunities. Visit the [portfolio contact section](https://ult666666.github.io/#contact) or explore the [public projects](https://github.com/ult666666?tab=repositories).

<sub>Projects include deployed interfaces, research snapshots, coursework and prototypes. Their READMEs explain what can be run and what remains out of scope. Company names in the valuation demo identify independent research subjects and do not imply affiliation or endorsement.</sub>
