# Phases 04–05: Technology & Backend

Load while running phases 4–5. Principle: recommend, don't interrogate. Non-technical users must never be forced to pick a framework; choose, explain why, mark `PROPOSED`, move on.

## Phase 04: Frontend & Technology
Purpose: choose technology by project need.

**Q4.1 Framework.** "Have you chosen a frontend framework?" Options: Astro / React / Next.js / Vue / Nuxt / SvelteKit / HTML+CSS+JS / Other / Not sure. Don't recommend all at once; explain trade-offs by project type.

**Q4.2 Styling.** Tailwind CSS / CSS Modules / Vanilla CSS / Sass / Component library / Combination / Not sure. Check framework compatibility.

**Q4.3 Component library.** shadcn/ui / Radix UI / Headless UI / Material UI / Ant Design / Custom components / None / Recommend. Don't force if the design needs custom visual control.

**Q4.4 Additional tools.** Examples: icons / form validation / schema validation / table / chart / rich-text editor / search / state management / testing. Options: have choices / want recommendations / none.

**Q4.5 Custom technical requirements.** Free field. Don't assume chosen tech is compatible without checking.

## Phase 05: Backend, Database & API

**Q5.1 Backend?** "Does the site need a backend?" Options: No, static is enough / Yes, dedicated / Yes, serverless / Yes, managed / Not sure. If unclear, explain: "A backend handles server processes, data, authentication, and logic that must not be trusted only to the browser."

**Q5.2 Backend tech** (if needed). Node.js / Next.js server-side / Astro server endpoints / Python / PHP / Managed backend / Other / AI recommendation. Don't show irrelevant options.

**Q5.3 Database?** "Does the app store data permanently?" Options: No / Yes, relational / Yes, document / Yes, managed / Not sure. If yes, consider PostgreSQL, MySQL, SQLite, MongoDB, managed services. Don't choose by popularity.

**Q5.4 File storage.** "Do users upload/store files?" Options: No / Yes, public / Yes, private / Yes, images-media / Yes, large documents / Not sure. If yes, define storage, size limits, file types, access, retention, deletion.

**Q5.5 API.** "Does the app connect to APIs?" Options: No / Yes, external / Yes, internal / Yes, AI API / Yes, several / Not sure. If yes, identify providers & integration needs. Don't invent APIs that don't exist.

**Q5.6 Third-party integrations.** Ask: Google OAuth / Email delivery / Payment gateway / AI provider / Object storage / Analytics / Search / Maps / Webhooks / Other. Show only relevant ones.

**Q5.7 Authentication.** "Do users need accounts?" Options: No / Email & password / Google login / Email/password + Google / Magic link / Other / Not sure. If yes, define session, recovery, permissions, account deletion.

**Q5.8 Additions.** "Any other backend/database/API/integration needs?" Options: none / I'll write / ask AI to recommend. Provide a free field.
