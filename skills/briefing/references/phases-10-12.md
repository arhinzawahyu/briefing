# Phases 10–12: Final Requirements, Summary, Documentation

Load while running phases 10–12.

## Phase 10: Final Custom Requirements
MUST be the last question before final review. Don't skip it even if all categories were answered.

Ask: "Before I draft the final specification, are there any other needs not covered? You may add feature ideas, design details, references, animation preferences, technology, extra backend/API, special security, file structure, documentation, implementation constraints, anything else, or write your own."

Options:
A. No additions.
B. I'll write them myself.
C. Have AI analyze gaps and recommend.
D. Review earlier decisions.

- B: show a free field and wait.
- C: analyze the brief: uncovered needs, potential conflicts, technical/security risks, visual inconsistencies, needless complexity, missed features. Don't auto-add every recommendation.
- D: show a decision summary, allow revision.
- New needs: classify, identify affected spec sections, check conflicts, explain trade-offs, update the brief, clarify if needed.

After this, don't code; proceed to final review.

## Phase 11: Final Brief Summary
Summarize the specification:
- **A. Project Overview**: name, type, objective, audience, main problem, success criteria, non-goals.
- **B. Product Scope**: core/additional/excluded features, roles, journeys.
- **C. Visual Direction**: art direction, brand personality, signature element, layout, hero, palette, typography, components, navigation, animation intensity/libraries, scroll, responsive, accessibility, assets, constraints, custom.
- **D. Technical Architecture**: frontend, styling, component library, animation libs, backend, database, API, auth, file storage, deployment.
- **E. Security**: sensitive data, threat model, controls, audit plan, privacy, residual risks.
- **F. Engineering**: structure, docs, testing, performance, SEO, accessibility, deployment, monitoring.
- **G. Open Decisions**: list all unresolved decisions & assumptions. Don't hide uncertainty.

## Phase 12: Specification Documentation
After the brief is complete, produce only the needed documents. Keep them consistent. Skeleton templates are in `templates/`.

- **PROJECT_BRIEF.md**: overview, goal, users, constraints, product direction.
- **PRD.md**: functional & non-functional needs, feature priority, acceptance criteria.
- **DESIGN.md**: design principles, visual direction, tokens, typography, layout, components, responsive rules.
- **WIREFRAME.md**: page structure, content hierarchy, component layout. Include visual representation if diagrams can and should be produced; don't claim a visual wireframe if you only provide text.
- **USER_FLOW.md**: journeys, navigation, interaction flows.
- **ARCHITECTURE.md**: system structure, tech choices, trust boundaries, reasoning.
- **API_SPECIFICATION.md**: API & integration contracts if needed.
- **DATABASE_SCHEMA.md**: entities, relations, constraints, migration strategy if needed.
- **SECURITY_PLAN.md**: threat model, controls, audit plan, residual risk.
- **ANIMATION.md**: motion principles, animations, timeline, triggers, interactions, reduced motion, performance strategy if needed.
- **AGENTS.md**: working instructions for the coding agent.
- **TEST_PLAN.md**: testing strategy, scenarios, acceptance criteria, verification.
- **IMPLEMENTATION_PLAN.md**: work order & dependencies.
- **README.md**: install, config, run, test, build.

Don't create irrelevant documents; ensure all are consistent.
