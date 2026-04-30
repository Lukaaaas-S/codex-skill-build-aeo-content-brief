---
name: build-aeo-content-brief
description: Build answer-ready SEO, AEO, and GEO content briefs from existing positioning, value proposition, product facts, proof, target questions, schema needs, and refresh requirements. Use when Codex needs to make content citeable by search and answer engines without inventing GTM messaging or Product decisions.
---

# Build AEO Content Brief

Use this skill to turn approved strategy, positioning, product facts, and proof into content that search engines and answer engines can parse, trust, and cite.

## Owned Inputs

Approved positioning, value proposition, product facts, proof, target queries, page objective, source credibility needs, and refresh requirements.

## Owned Outputs

Answer-ready content brief, page structure, FAQ and schema recommendations, evidence needs, and refresh cadence.

## Shared References

- `references/shared/boundaries/aeo-seo.md`
- `references/shared/boundaries/cross-family.md`
- `references/shared/sources/source-policy.md`

## Hard Boundaries

- Own only this skill's task-triggered output.
- Use shared references instead of copying pattern logic into this skill.
- Hand off new positioning, ICP, channels, or launch motion to GTM, and missing product decisions to Product.
- Read `references/source-map.md` and shared references only when provenance, boundary checks, or deeper pattern detail is needed.

## Workflow

1. Confirm the content objective: answer inclusion, citation, comparison coverage, entity clarity, category education, or conversion support.
2. Load existing ICP, positioning, value proposition, and proof if available.
3. Map target queries and questions to page sections, FAQs, comparison blocks, examples, and proof assets.
4. Define the page or content structure: direct answer, entity facts, use cases, alternatives, limitations, evidence, FAQ, and next action.
5. Specify structured data and machine-readable evidence where useful.
6. Identify source credibility needs: third-party proof, original research, customer evidence, benchmark data, documentation, or community references.
7. Define refresh cadence and facts that must be rechecked.

## Boundary Rules

- Do not create new positioning, value proposition, ICP, or launch narrative.
- Use `value-prop-messaging` only to consume approved message angles, then structure them for answer surfaces.
- Use `positioning-review` only to check consistency, not to produce a new market category.
- If the request asks for launch channels or campaign motion, hand off to `design-gtm-motion` and provide only visibility requirements.
- If product claims are not verifiable, mark them as open Product questions instead of writing around them.

## Output Format

- Content objective
- Target audience and query set
- Source inputs used
- Answer-ready page outline
- Entity facts and proof requirements
- FAQ and schema recommendations
- Internal and external source requirements
- Refresh plan
- Handoff notes

## When To Read References

- Read `references/source-map.md` for source provenance.
- Read these pattern cards when needed:
  - `references/shared/patterns/answer-ready-content.md`
  - `references/shared/patterns/entity-source-credibility.md`
  - `references/shared/patterns/value-prop-messaging.md`
  - `references/shared/patterns/positioning-review.md`
  - `references/shared/patterns/launch-motion-design.md`

## Quality Bar

- The brief answers real questions directly.
- Claims are supported by proof or marked as open.
- Page structure, FAQ, schema, and source requirements are consistent.
- GTM and Product decisions are not invented inside the content brief.
