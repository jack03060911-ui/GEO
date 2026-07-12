---
name: geo-keyword-builder
description: Build GEO keyword, prompt, entity, and question clusters for Generative Engine Optimization. Use this skill when the user wants to discover AI-answer-friendly queries, query fan-out opportunities, comparison prompts, citation opportunities, or content briefs optimized for ChatGPT, Gemini, Perplexity, Copilot, Claude, and Google AI Overviews.
---

# geo-keyword-builder

## Purpose

Use this skill to convert a product, brand, website, niche, audience, or topic into a prioritized GEO keyword and prompt map.

The goal is not just to find search keywords. The goal is to identify:

- Questions users may ask generative engines.
- Sub-queries an AI search engine may fan out into.
- Entities, competitors, use cases, and comparison angles the answer may need.
- Content formats most likely to be cited, summarized, or recommended by AI answers.
- Pages or assets the user should create or improve to increase generative search visibility.

## When to use

Use this skill when the user asks for any of the following:

- GEO keyword research.
- AI search keyword research.
- Prompt clusters for ChatGPT, Gemini, Claude, Perplexity, Copilot, or Google AI Overviews.
- AEO / LLMO / Generative Engine Optimization query planning.
- Keyword-to-content mapping for AI search visibility.
- Comparison, recommendation, “best X for Y”, alternative, FAQ, or entity-based topic discovery.
- Content briefs designed to increase AI answer inclusion, citations, or brand mentions.

## Inputs to collect

Ask for missing information only if it is required. Otherwise, infer reasonable assumptions and label them clearly.

Recommended inputs:

1. Brand / website / product name.
2. URL, if available.
3. Industry or niche.
4. Target market and language.
5. Target audience or buyer personas.
6. Main products, services, or topics.
7. Known competitors or alternatives.
8. Business goal: awareness, leads, sales, trials, local visits, authority, reputation, support deflection, or retention.
9. Geographic focus.
10. Existing content assets, if available.
11. Preferred output size: quick, standard, or deep.

## Operating principles

Follow these rules:

- Treat GEO keywords as natural-language prompts, questions, entities, and query patterns, not only short keywords.
- Prioritize user intent and answer usefulness over keyword volume.
- Do not invent search volume, difficulty, CPC, or ranking data. If no data source is available, mark those fields as `N/A` or estimate qualitatively as Low / Medium / High.
- Avoid doorway-page or thin-page recommendations. Merge overlapping variants into useful topic clusters.
- Prefer pages that provide original evidence, expert reasoning, comparison tables, definitions, workflows, case studies, FAQs, and up-to-date facts.
- Include competitors and alternatives only when relevant to user intent.
- Distinguish between owned content opportunities and third-party / earned-media opportunities.
- For regulated industries such as finance, legal, health, insurance, and education, add a review requirement for expert or legal approval.
- Clearly separate facts, assumptions, and recommendations.

## Workflow

### 1. Scope the market

Summarize the target domain:

- Core offer.
- Audience.
- Use cases.
- Buying or research journey.
- Primary entities.
- Known competitors.
- GEO goal.

If inputs are incomplete, state assumptions in a short `Assumptions` section.

### 2. Build seed topics

Generate seed topics from these sources:

- Product categories.
- Problems and pain points.
- Use cases.
- Personas.
- Industries.
- Locations.
- Features.
- Integrations.
- Competitors.
- Alternatives.
- Pricing and cost questions.
- Reviews and trust questions.
- Implementation and troubleshooting questions.
- Definitions and glossary terms.

### 3. Expand into GEO prompt families

For each seed topic, create prompts across these families:

1. Definition prompts: `What is X?`, `X meaning`, `X explained`.
2. How-to prompts: `How to do X`, `How to choose X`, `How to implement X`.
3. Best / recommendation prompts: `Best X for Y`, `Top X tools for Y`.
4. Comparison prompts: `X vs Y`, `X alternatives`, `X compared to Y`.
5. Evaluation prompts: `Is X worth it?`, `X pros and cons`, `X limitations`.
6. Pricing prompts: `How much does X cost?`, `X pricing`, `X free vs paid`.
7. Use-case prompts: `X for startups`, `X for agencies`, `X for enterprise`, `X for local business`.
8. Problem-solving prompts: `How to fix X`, `Why does X happen?`, `Best way to solve X`.
9. Trust prompts: `X reviews`, `Is X reliable?`, `X case studies`, `X security`.
10. Local prompts, when relevant: `Best X in [city]`, `X near me`, `X provider in [region]`.
11. Entity prompts: `Who is X?`, `X company`, `X founder`, `X product features`.
12. Alternative-source prompts: `What do experts recommend for X?`, `Which tools are commonly cited for X?`.

### 4. Map query fan-out

For each high-value parent prompt, infer likely fan-out sub-queries an AI search system may use to ground its answer.

Include at least 5 fan-out sub-queries per high-priority parent prompt:

- Definition or concept.
- Criteria or evaluation framework.
- Product / service options.
- Competitor or alternative.
- Pricing / cost.
- Reviews / reputation.
- Recentness / updates.
- Case studies / examples.
- Risks / limitations.
- Implementation steps.

### 5. Classify intent

Assign one primary intent and optional secondary intent.

Allowed primary intents:

- Informational.
- Commercial Investigation.
- Transactional.
- Navigational.
- Local.
- Support / Troubleshooting.
- Reputation / Trust.
- Comparison.
- Recommendation.
- Definition.
- Implementation.

Assign funnel stage:

- Awareness.
- Consideration.
- Decision.
- Purchase.
- Retention.
- Advocacy.

### 6. Identify entities

For each opportunity, extract relevant entities:

- Brand.
- Product.
- Competitor.
- Category.
- Feature.
- Persona.
- Industry.
- Location.
- Problem.
- Standard / regulation.
- Integration.
- Author / expert.
- Data source.

### 7. Score GEO opportunity

Use this 0-100 scoring model unless the user provides another one.

`GEO Opportunity Score = Business Value + Citation Potential + Intent Fit + Fan-out Breadth + Content Gap + Feasibility`

Recommended weights:

- Business Value: 0-25.
- Citation Potential: 0-20.
- Intent Fit: 0-15.
- Fan-out Breadth: 0-15.
- Content Gap: 0-15.
- Feasibility: 0-10.

Scoring guidance:

- Business Value is high when the prompt is close to revenue, lead generation, adoption, or strategic authority.
- Citation Potential is high when the answer needs evidence, definitions, tables, data, case studies, expert sources, or comparison criteria.
- Intent Fit is high when the prompt matches the user’s target audience and offer.
- Fan-out Breadth is high when the prompt naturally decomposes into many sub-questions where the user can provide useful content.
- Content Gap is high when competitors or AI answers lack clear, current, authoritative, or structured content.
- Feasibility is high when the user can realistically create, update, or earn the required content.

If no research data is available, score qualitatively and state that the score is a directional prioritization, not measured search demand.

### 8. Cluster opportunities

Cluster prompts into practical content groups. Avoid creating one page per minor keyword variant.

Recommended cluster types:

- Pillar guide.
- Comparison page.
- Alternatives page.
- Best-for persona page.
- Use-case page.
- Industry page.
- Local page.
- Glossary page.
- FAQ page.
- Product feature page.
- Pricing / cost page.
- Case study / proof page.
- Data report / benchmark.
- Troubleshooting / support article.
- Third-party PR / review target.

### 9. Recommend page type and GEO structure

For each cluster, recommend one page type and a GEO-ready structure.

Use these blocks when relevant:

- Direct answer block.
- Definition block.
- Criteria / evaluation framework.
- Comparison table.
- Pros and cons.
- Step-by-step workflow.
- Evidence block with sources or first-party data.
- Expert quote or author note.
- FAQ block.
- Summary block.
- Schema suggestion.
- Internal links.
- External authority / citation targets.

### 10. Deliver outputs

Default output sections:

1. Executive Summary.
2. Assumptions.
3. Priority GEO Clusters.
4. GEO Keyword / Prompt Table.
5. Query Fan-out Map.
6. Entity Map.
7. Content Briefs.
8. Quick Wins.
9. Earned Media / Third-party Opportunities.
10. Measurement Plan.
11. Next Actions.

## Output table schema

Use this table for the main output:

| Priority | Cluster | Seed Keyword | AI Prompt / Query | Intent | Funnel Stage | Entities | Fan-out Subqueries | Recommended Page Type | Citation Potential | Business Value | Difficulty | GEO Opportunity Score | Notes |
|---|---|---|---|---|---|---|---|---|---:|---:|---|---:|---|

Field rules:

- Priority: P1, P2, or P3.
- Cluster: concise topic group name.
- Seed Keyword: short keyword or entity phrase.
- AI Prompt / Query: natural-language prompt users may ask an AI engine.
- Intent: use the allowed intent taxonomy.
- Funnel Stage: awareness, consideration, decision, purchase, retention, or advocacy.
- Entities: comma-separated entities.
- Fan-out Subqueries: concise list of likely subqueries.
- Recommended Page Type: use one of the cluster types.
- Citation Potential: Low / Medium / High, or 0-20.
- Business Value: Low / Medium / High, or 0-25.
- Difficulty: Low / Medium / High / N/A.
- GEO Opportunity Score: 0-100 when enough information exists.
- Notes: include assumptions, risks, or content requirements.

## Content brief template

For each P1 cluster, provide a brief:

```markdown
### Cluster: [Name]

**Primary AI prompt:** [Prompt]
**Secondary prompts:** [Prompt list]
**Target audience:** [Persona]
**Intent:** [Intent]
**Funnel stage:** [Stage]
**Recommended page type:** [Page type]
**Core entities:** [Entities]
**AI answer angle:** [What the AI answer should be able to say]
**Suggested title:** [SEO/GEO title]
**Suggested URL:** [/example-url]

#### Recommended structure
1. Direct answer / executive summary
2. Definition or context
3. Evaluation criteria
4. Detailed answer
5. Comparison / table / workflow
6. Evidence, examples, or case study
7. FAQ
8. Summary and next step

#### GEO enhancements
- Add a clear definition block.
- Add a comparison or criteria table.
- Add first-party data, examples, screenshots, or case study proof if available.
- Add author credentials and update date.
- Add schema where appropriate.
- Add internal links to related clusters.
- Seek third-party mentions from relevant review, media, directory, or expert sources.
```

## Measurement plan

Recommend tracking:

- Brand mention rate in AI answers.
- Citation rate by source URL.
- Prompt-level share of voice.
- Competitor co-mentions.
- Sentiment or recommendation tone.
- Source type distribution: owned site, review site, news, forum, documentation, directory.
- Conversion and referral impact from AI search where measurable.
- Content update impact before and after publishing.

## Quality checklist

Before finalizing, verify:

- The output includes prompts, not only keywords.
- The output includes entities.
- The output includes query fan-out.
- P1 clusters are actionable and not thin variants.
- Scoring is explained and not falsely precise.
- Page recommendations are tied to user intent.
- At least some opportunities are citation-friendly.
- The output distinguishes owned-content work from earned-media work.
- Regulated claims are flagged for review when needed.

