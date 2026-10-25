# Phases 06–09: Security, Structure, Deployment, Testing

Load while running phases 6–9.

## Phase 06: Security & Privacy
Explain that security is part of architecture, not an add-on.

**Q6.1 Data sensitivity.** "Does the app store sensitive/personal data?" Options: No / Yes, profile / Yes, private files / Yes, financial / Yes, internal business / Yes, other sensitive / Not sure. Never ask for actual sensitive data.

**Q6.2 Security needs.** (multi) Account protection / Roles & permissions / API protection / File protection / Audit log / Rate limiting / Private-data protection / Backup & recovery / Full risk-based audit / AI recommendation.

**Q6.3 Threat model.** Analyze: assets, trust boundaries, entry points, attack surfaces, threat scenarios, security controls, residual risks. Adapt to the app.

**Q6.4 Audit plan.** Determine: dependency scanning / static analysis / secret scanning / auth & authorization testing / API security testing / input validation / file upload testing / configuration review / privacy review. Never claim completed before actually running.

**Q6.5 Privacy & retention.** "Any rules on data storage, deletion, or access?" Explain design consequences if data must be deleted, retained for a period, or owner-only.

## Phase 07: Project Structure & Files

**Q7.1 Repository.** "New project or existing repo?" New / Existing / Continue unfinished. If a repo exists, inspect before recommending.

**Q7.2 Structure preference.** Simple / Modular / Monorepo / Separate frontend & backend / Follow existing / Not sure. Don't separate frontend/backend just to look professional.

**Q7.3 Documentation.** Consider: PROJECT_BRIEF.md, PRD.md, DESIGN.md, WIREFRAME.md, USER_FLOW.md, ARCHITECTURE.md, API_SPECIFICATION.md, DATABASE_SCHEMA.md, SECURITY_PLAN.md, TEST_PLAN.md, IMPLEMENTATION_PLAN.md, ANIMATION.md, AGENTS.md, README.md. Don't create all automatically; choose by need. Skeleton templates are in `templates/`.

**Q7.4 Structure additions.** Free field.

## Phase 08: Deployment & Operations

**Q8.1 Deployment.** "Where will the site run?" Options: Vercel / Netlify / Cloudflare / VPS / Shared hosting / Other / Not sure. Choose by framework, backend needs, service limits.

**Q8.2 Domain.** "Domain available?" Yes / No / Still deciding / Not needed.

**Q8.3 Operations.** Evaluate: environment variables / logging / monitoring / error tracking / backups / migrations / rollback / rate limits / cost monitoring. Don't add complex infrastructure unless justified.

## Phase 09: Testing & QA

**Q9.1 Scope.** "How broad should testing be?" Options: Basic checks / Unit & integration / E2E / Visual regression / Accessibility / Performance / Security / Risk-based combination / AI recommendation.

**Q9.2 Quality checks.** Consider: build verification / type checking / linting / functional / responsive / browser / accessibility / SEO / performance / security.

**Q9.3 Acceptance criteria.** Define verifiable success indicators, not "must be perfect". Examples: all core flows complete / no critical errors on tested scenarios / layout works at defined sizes / access rights tested per role / build succeeds / security findings logged and followed up.
