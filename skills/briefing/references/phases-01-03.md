# Phases 01–03: Discovery

Load while running phases 1–3. Ask one decision per interactive-tool call. The option lists below are content for the host's `question`/`AskUserQuestion`/`request_user_input` tool. Keep questions adaptive; skip what's irrelevant.

## Phase 01: Project Discovery
Purpose: understand the project before discussing design and tech.

**Q1.1 Project name.** "What would you like to name this project?" Options: Already have a name / No name yet / Help me find one. If none, don't force it.

**Q1.2 Project goal.** "What is the main goal?" Options: Introduce product/service / Personal branding / Sell products / Manage data / Support work or business / Support learning / AI-based service / Build community / Other.

**Q1.3 Target users.** "Who will use this site?" Options: General public / Students / Developers & designers / Business owners / Companies / Specific community / Internal users / Other. If relevant, explore traits, needs, technical level, devices.

**Q1.4 Core problem.** "What problem should this site solve?" Ask for a short explanation; don't jump to technical solutions.

**Q1.5 User goal.** "When they open the site, what main action do you expect?" Examples: understand product / sign up / create project / upload documents / search / buy / read articles / contact / use tools / manage data.

**Q1.5b Success metric.** "How will you know this succeeded?" Options: more sign-ups / more sales / more contacts / traffic / time saved / brand awareness / not sure (recommend one). Record as a measurable target where possible; skip if the user doesn't care.

**Q1.5c Non-goals.** "What is explicitly out of scope?" Options: nothing, everything in the list / no accounts / no payments / no admin panel / no content editing / not sure (propose a non-goal list for confirmation). An unstated non-goal becomes scope creep later; record it in the brief even when empty.

**Q1.6 References.** "Do you have reference sites?" Options: URL / screenshot / several with different characters / none / help me find. Analyze only genuinely accessible info.

**Q1.7 Additional info.** "Any other info (idea, goal, users, constraints) not covered?" Optional free field.

## Phase 02: Product & Feature Discovery
Purpose: determine features truly needed.

**Q2.1 Core features.** "Which features do you want?" Show options derived from the project type (table below), not a universal checklist. Multiple select. Include "I don't know, help me" and free text.

| Project type | Typical required sections | Usually needed | Usually NOT needed |
|---|---|---|---|
| Landing page | hero, value props, proof, CTA, footer | analytics, contact form | auth, database |
| Portfolio | case studies, about, contact | CMS, image pipeline | payments, auth |
| Blog / publication | index, post, tags, feed | CMS, SEO schema | app dashboard |
| Company profile | services, about, testimonials, contact | contact form, local SEO | auth |
| SaaS | pricing, features, signup, login, onboarding | auth, database, billing | heavy scroll animation |
| Admin dashboard | auth, tables, forms, roles | database, audit log | marketing sections |
| E-commerce | catalog, product page, cart, checkout | payments, auth, stock | long-form blog |
| Marketplace | listings, search, messaging, roles | auth, payments, moderation | single-tenant admin |
| AI app | input, streaming output, history | provider API, rate limit, cost cap | marketing bloat |

Treat the table as defaults to confirm, not a fixed template. Deviations are allowed when the user gives a reason; record the reason.

**Q2.2 User roles.** "Are there distinct user types or access levels?" Options: all public / some require login / users & admin / several roles with different permissions / not sure.

**Q2.3 Feature priority.** Group: MUST HAVE / SHOULD HAVE / COULD HAVE / OUT OF SCOPE. Show a summary for confirmation.

**Q2.4 User flow.** "How should a user use the site from start to finish?" If unknown, propose a recommended flow and request approval.

**Q2.5 Additions.** "Any other features?" Options: none / I'll write / help me recommend.

## Phase 03: Visual Discovery
Important: design is not just picking colors & fonts. Split this phase into sections; never ask all visual questions at once.

Anti-generic rule: an adjective is not a design decision. Whenever the user answers with a mood word ("premium", "modern", "clean"), ask what screen or site made them feel that, then convert the answer into decisions: type scale, spacing density, radius, motion duration, imagery treatment. An answer that cannot be converted stays `UNRESOLVED`, not silently filled with a default.

### Section A: Art direction
**Q3.1 Visual character.** "What visual character?" Options: Minimalist Premium / Editorial / Modern SaaS / Cinematic / Experimental (Awwwards-inspired) / Brutalist / Futuristic / Playful / Corporate Professional / Custom Direction. Note these are not final templates.

**Q3.2 Impression.** "What impression must visitors feel?" (max 3): Professional & trustworthy / Elegant & premium / Bold & experimental / Modern & futuristic / Warm & friendly / Minimal & calm / Cinematic & immersive / Creative & expressive / Other. Explain trade-offs if conflicting.

**Q3.3 Setting direction.** Options: reference site / pick from several visual refs / moodboard / AI recommends / combine refs / describe yourself. Use image browsing if available; never claim references you didn't access. When a reference is given, record what specifically is being borrowed (layout, type, color, motion, tone) and what is rejected — not just the URL.

**Q3.3b Signature element.** "What should a visitor remember after 10 seconds?" Options: the headline / the product visual / one interaction / the typography / the imagery / the data shown / not sure (recommend, explaining why). Exactly one signature element; if everything is emphasized, nothing is. Record it; it drives the design and is checked in Phase 15.

### Section B: Layout
**Q3.4 Layout character.** "What composition?" Options: Clean Grid / Editorial Asymmetric / Bento / Full-screen Immersive / Split / Dashboard Dense / Scrollytelling / Hybrid / Custom. One layout needn't fit every page.

**Q3.5 Density.** Options: very minimal, lots of whitespace / balanced / informative / dense like a dashboard / differs per page.

**Q3.6 Hero.** "How should the first section look?" Options: big typography on a simple background / text + illustration split / full-screen visual / product-as-visual / editorial asymmetric / video or motion background / interactive 3D / simple hero / custom. Video and 3D only when appropriate and performance-safe.

**Q3.7 Additional visuals.** (multi) Photography / Illustration / Product screenshots / Diagrams / Data viz / Icons / 3D / Video / Typography-as-visual / Combination / None / Other. If no assets yet, record the need; don't invent them.

### Section C: Color
**Q3.8 Theme.** Light / Dark / Light with dark sections / Dark with light sections / Light + dark mode / Not sure.

**Q3.9 Color direction.** Monochrome / Neutral + one accent / Cool / Warm / High contrast / Earthy / Vibrant / Brand colors / Custom palette / AI recommends. If custom, ask codes/references. Don't pick by trend.

**Q3.10 Constraints.** None / Mandatory colors / Forbidden colors / Follow brand guideline / Need high contrast / Other.

### Section D: Typography
**Q3.11 Type character.** Modern sans-serif / Editorial serif / Geometric sans-serif / Monospaced/technical / Expressive display / Display heading + body sans / Follow brand / AI recommends.

**Q3.12 Headline.** Large, firm, simple / Elegant editorial / Experimental / Concise professional / Expressive with line breaks / Custom. Avoid experimental type that hurts readability.

**Q3.13 Font.** Yes, decided / Not yet, recommend / Open-source / Must follow brand / Other. Check license & loading strategy.

### Section E: Components
**Q3.14 Buttons.** Minimal & flat / High-contrast solid / Outline / Soft & rounded / Firm geometric / Experimental hover / Follow design system / Custom.

**Q3.15 Cards/containers.** Flat no shadow / Thin border / Soft shadow / Elevated / Glass / Bento-style / Follow content type / No cards unless needed / Custom. Don't assume glass or shadow is always needed.

**Q3.16 Shape.** Sharp corners / Small radius / Rounded / Organic / Geometric / Combination by function.

**Q3.17 Navigation.** Simple top nav / Sticky navbar / Sidebar / Floating / Full-screen menu / Contextual / Differs per page / Custom. Derive from project type and user flow.

**Q3.18 Component details.** May specify: dropdowns, tables, search bar, modal, tooltip, tabs, accordion, pagination, form fields, toast, empty/loading states. Don't force all components.

### Section F: Motion
**Q3.19 Intensity.** Minimal / Subtle Premium / Balanced / Cinematic / Immersive / Experimental / None. Intensity ≠ quality.

**Q3.20 Types.** (multi) Hover / Button micro-interactions / Text reveal / Page transitions / Scroll-triggered / Scrollytelling / Parallax / Animated counters / Carousel / Timeline / Cursor / 3D / Loading transitions / Custom / AI decides. Don't add irrelevant motion.

**Q3.21 Libraries.** CSS / GSAP / GSAP ScrollTrigger / Lenis / Motion (Framer) / Three.js / React Three Fiber / Lottie / AutoAnimate / Recommended combo / Not sure / None. Briefly explain each; check compatibility, need, performance cost, maintenance.

**Q3.22 Scroll.** Native / Smooth / Scroll-triggered / Scrollytelling / Pinned / Horizontal storytelling / Combination / Not sure. If Lenis + ScrollTrigger, integrate properly; don't break keyboard, anchors, accessibility, reduced motion.

**Q3.23 Constraints.** Light on mobile / Support reduced motion / No interference / High performance / Complex if optimized / Other.

### Section G: Responsive & accessibility
**Q3.24 Device priority.** Mobile-first / Desktop-first / Both equal / Tablet & desktop / Special needs. Desktop-first ≠ license to ignore mobile.

**Q3.25 Responsive behavior.** Same structure, scaled / Layout may change / Different mobile nav / Simplified elements / Per-page.

**Q3.26 Accessibility.** High contrast / Keyboard nav / Screen reader / Reduced motion / Readable text size / Language support / Follow relevant practices / Other. If unknown, apply sensible defaults.

### Section H: Assets
**Q3.27 Availability.** (multi) Logo / Photos / Illustrations / Screenshots / Video / Custom font / Brand guideline / None / Combination.

**Q3.28 If no assets.** Temporary placeholder / Licensed open-source / Custom illustrations / CSS/SVG decorative / Image generator if available / User assets / Recommend. Don't treat placeholders as final; don't claim assets without verification.

**Q3.29 Constraints.** Avoid: excessive gradients / too many cards / excessive animation / decorative fonts / certain colors / too-dense layout / 3D effects / template-like / unlicensed assets. Allow free input.

### Section I: Visual customization (must be last)
Don't end the visual phase after animation/responsiveness. Ask: "Any remaining visual preferences or design details?" Options: None / More colors / Other references / Borrow UI-detail principles / Special animation / 3D or interactive / Design constraints / I'll write everything / AI recommends additions.

If "I'll write": show a guided free field; analyze, group, flag conflicts, explain consequences, clarify only if needed, and update the brief. Never ignore free-form answers.

**Visual summary.** After all sections, present a summary: art direction, brand personality, impression, signature element, layout, hero, palette, typography, component style, navigation, animation intensity/libraries, scroll, responsive strategy, accessibility, asset strategy, constraints, additions. Mark each decision `CONFIRMED` / `PROPOSED` / `NEEDS CONFIRMATION`. Ask "Is this visual direction right?" Never treat answered questions as approval.
