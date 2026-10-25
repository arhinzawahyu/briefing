# Briefing: WEBCRAFT INTELLIGENCE

An AI-agent skill that turns a rough web idea into an implementation-ready specification through an adaptive, visual-first, secure interview, before any code is written. Produces only the documents a project earns, and refuses to code until you approve the spec.

## Features

- **Interactive**: every question via the host's native tool (`question`, `AskUserQuestion`, `request_user_input`), with options, recommendations, and free-form answers.
- **Visual-first**: explores art direction, layout, typography, color, motion, and accessibility.
- **Adaptive**: asks only what's relevant, never floods.
- **Security by default**: threat model and controls on every project.
- **Approval first**: no coding until the spec is approved.
- **English**: single-language skill.

## Install

```bash
npx skills add arhinzawahyu/briefing --skill briefing
```

Restart your agent so the skill is detected.

## Usage

Describe an app idea in plain language, e.g.:

```
Build an employee attendance app with GPS location.
```

The skill interviews you step by step, then produces the specification.

## Structure

```
skills/briefing/
├── SKILL.md              # Core identity, rules, tool requirements, phase index
├── references/
│   ├── phases-01-03.md   # Discovery: project, features, visual (A–I)
│   ├── phases-04-05.md   # Frontend & tech, backend, database, API
│   ├── phases-06-09.md   # Security, structure, deployment, testing
│   ├── phases-10-12.md   # Final requirements, summary, documentation
│   └── phases-13-15.md   # Approval, implementation, evaluation
└── templates/            # Skeleton output documents
    ├── PROJECT_BRIEF.md          ├── USER_FLOW.md
    ├── PRD.md                    ├── ARCHITECTURE.md
    ├── DESIGN.md                 ├── API_SPECIFICATION.md
    ├── SECURITY_PLAN.md          ├── DATABASE_SCHEMA.md
    ├── IMPLEMENTATION_PLAN.md    ├── TEST_PLAN.md
    ├── TASKS.md                  └── README.md
```

`SKILL.md` holds core context and the reference-loading table; detailed questions live in `references/` and load progressively (not all at once). Output skeleton templates live in `templates/`.

## Prerequisites

- Node.js & npm (for `npx skills`).
- An agent supporting the `SKILL.md` format (OpenCode, Claude Code, Codex, Cursor, and similar).

## License

MIT (see `LICENSE`).
