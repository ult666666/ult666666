# Charles Dai

**Software developer · Fintech research tools · AI systems**

I'm a **Carnegie Mellon University student** building full-stack products and AI-assisted workflows. I care about clear interfaces, deterministic logic and evidence that a reviewer can inspect.

[**Portfolio & case studies ↗**](https://ult666666.github.io/) · [Public repositories](https://github.com/ult666666?tab=repositories) · [MOTIONX](https://madebymotionx.com/)

## Featured: Frontier AI Valuation Lab

An independent, AI-assisted fintech research workspace. Compare illustrative Anthropic and OpenAI valuations, explain a scenario change, and keep the exact analysis with its rationale and dated evidence.

[**Try the workspace ↗**](https://frontier-ai-valuation-lab.vercel.app/) · [Engineering case study](https://ult666666.github.io/projects/frontier-ai-valuation-lab.html) · [Source](https://github.com/ult666666/frontier-ai-valuation-lab)

1. **Compare and explain.** Apply a stress in the Overview and choose **Explain this change** to carry the exact baseline and alternative into Thesis Lab.
2. **Inspect the assumptions.** Open either case in the Model, edit it and return with the other case, target and comparison settings intact.
3. **Keep the reasoning.** Save to the Research Casebook, record a rationale and review trigger, then export JSON or a printable brief. Notes stay in the current browser unless exported.

### Review the implementation

| Engineering question | Where to look |
| --- | --- |
| How is the calculation checked? | A [shared browser/Node engine](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/public/lib/model.js), [real HTTP tests](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/tests/api.test.js) and [separate Python parity checks](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/tests/reference_parity.py). |
| Can research survive edits and failed saves? | The [journey module](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/public/lib/journey.js) preserves exact comparisons; [storage tests](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/tests/casebook-store.test.js) exercise corrupt data, blocked storage and quota failures. |
| What is reported evidence versus an assumption? | The [contextual evidence method](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/docs/EVIDENCE_CONTEXT.md) keeps source dates, definitions and modeling limits visible. |

Application 3.3 retains financial engine 3.0 and the **18 October 2026 research snapshot**. Browser/API agreement establishes consistency; the independent Python implementation checks arithmetic. These checks do not establish forecast accuracy or investment returns. See the [verification record and its scope](https://github.com/ult666666/frontier-ai-valuation-lab/blob/main/docs/VERIFICATION.md).

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

## Let's connect

I'm interested in software engineering, AI engineering and product-focused internship opportunities. Visit the [portfolio contact section](https://ult666666.github.io/#contact) or explore the [public projects](https://github.com/ult666666?tab=repositories).

<sub>Projects include deployed interfaces, research snapshots, coursework and prototypes. Their READMEs explain what can be run and what remains out of scope. Company names in the valuation demo identify independent research subjects and do not imply affiliation or endorsement.</sub>
