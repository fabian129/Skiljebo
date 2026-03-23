# Zaitex Web Production Agent

## FIRST: Read the Index
Before doing ANY production work, read `.agent/INDEX.md`.
It contains the full skill pipeline, brain document lookup table, and change budgets.

## How This Project Works
This project uses the **Zaitex Engine** — a skill-based production system for building premium websites.

### Quick Start
1. Read `.agent/INDEX.md` — understand the pipeline and skill routing
2. Identify which **phase** you're in (Inventory → Concept → Production → QA → Polish → Ship)
3. Read the relevant **skill file** in `.agent/skills/` before executing
4. Reference **brain documents** in `.agent/brain/` for templates, patterns, and libraries

### Folder Structure
```
.agent/
├── INDEX.md          ← Start here. Pipeline + skill→brain routing table
├── skills/           ← 26 production skills (how to do things)
└── brain/            ← Reference docs (templates, patterns, identity)
    ├── brand/        ← Workshop system, Zaitex Brand Bible
    ├── communication/← Sales philosophy, communication tone
    ├── production/   ← Layout, motion, polish, SEO, deployment patterns
    └── products/     ← Product manuals (Brand Bible, Website)
```

### Rules
- **Always read the skill file** before executing a skill
- **Check brain references** listed in the skill (e.g., "hämta från brain: production/layout-pattern-library")
- **Respect change budgets** (MICRO/SMALL/MEDIUM/LARGE) defined per skill
- **Stop at STOP POINTs** and present work for user approval
- **Tech stack:** Next.js · React · TypeScript · Tailwind · Framer Motion · GSAP · Vercel
