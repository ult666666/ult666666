# Charles Dai

**Software developer · Fintech research tools · AI systems**

I'm a **Carnegie Mellon University student** building full-stack products and AI-assisted workflows. I care about clear interfaces, deterministic logic and evidence that a reviewer can inspect.

[**Portfolio & case studies ↗**](https://ult666666.github.io/) · [Fintech portfolio](https://ult666666.github.io/fintech.html) · [Public repositories](https://github.com/ult666666?tab=repositories) · [MOTIONX](https://madebymotionx.com/)

## Featured: Frontier AI Valuation Lab

An independent, AI-assisted fintech research workspace. Explore how distant cash flows affect value, how a hypothetical equity round changes ownership, and which assumptions explain a scenario difference. Keep operating cases with their reasoning and dated evidence.

[**Try the workspace ↗**](https://frontier-ai-valuation-lab.vercel.app/) · [Engineering case study](https://ult666666.github.io/projects/frontier-ai-valuation-lab.html) · [Source](https://github.com/ult666666/frontier-ai-valuation-lab)

1. **See how much future is in the value.** [Value Horizon](https://frontier-ai-valuation-lab.vercel.app/horizon.html) keeps the explicit forecast fixed and shows how the valuation changes when later terminal cash flows and residual value are removed.
2. **Explore an ownership constraint.** [Ownership Frontier](https://frontier-ai-valuation-lab.vercel.app/index.html#ownership-example), inside Financing Lens, connects a hypothetical primary round to dilution and the minimum stake retention you enter. Pre-money pricing, post-money pricing and operating enterprise value remain distinct.
3. **Explain and preserve an operating case.** Move exact comparisons through Thesis Lab and the Model, then save the operating case and rationale to the Research Casebook. Casebook notes stay in the browser unless exported; financing links and exports retain their separate scope.

### Review the implementation

| Engineering question | Where to look |
| --- | --- |
| How is the calculation checked? | A [shared browser/Node engine](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/public/lib/model.js), [real HTTP tests](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/tests/api.test.js) and [separate Python parity checks](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/tests/reference_parity.py). |
| Can research survive edits and failed saves? | The [journey module](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/public/lib/journey.js) preserves exact comparisons; [storage tests](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/tests/casebook-store.test.js) exercise corrupt data, blocked storage and quota failures. |
| How are financing and dilution kept separate from operations? | The [Financing Lens method](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/docs/FINANCING_LENS.md) explains the hypothetical equity bridge, round pricing, ownership retention and numeric limits. |
| What is reported evidence versus an assumption? | The [contextual evidence method](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/docs/EVIDENCE_CONTEXT.md) keeps source dates, definitions and modeling limits visible. |

Application **3.6** adds Ownership Frontier while retaining financial engine 3.0 and the **18 October 2026 research snapshot**. Browser/API agreement establishes consistency; the independent Python implementation checks arithmetic. These checks do not establish forecast accuracy or investment returns. See the [verification record and its scope](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/docs/VERIFICATION.md).

## More selected work

| Project | What it demonstrates | Explore |
| --- | --- | --- |
| **LineageGuard** | A metadata-aware schema-change review using DataHub context, downstream impact and migration guidance. | [Source](https://github.com/ult666666/lineageguard-datahub-agent) · [Case study](https://ult666666.github.io/projects/lineageguard.html) |
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
