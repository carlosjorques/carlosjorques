# Carlos Jorques Portfolio Site

This repository contains Carlos Jorques's Astro personal professional website plus reusable agent playbooks and Codex skills for evolving the site.

## How to use

Copy the contents of this folder into the root of your Astro project.

Recommended resulting structure:

```text
astro-project/
├── AGENTS.md
├── PROJECT_BRIEF.md
├── agent-playbooks/
└── .agents/
    └── skills/
```

Then start Codex with a scoped task such as:

```text
Read AGENTS.md and PROJECT_BRIEF.md. Then use the astro-template-adapter, portfolio-content-strategy, astro-content-collections, and nordic-design-system skills to turn this default Astro installation into the first version of the site.
```

## What is included

- Root project instructions for Codex in `AGENTS.md`
- A concise project summary in `PROJECT_BRIEF.md`
- Agent playbooks for role-specific work
- Custom skills under `.agents/skills/`

## Agent playbooks

Use `agent-playbooks/` when you want Codex to adopt a specific role:

- `project-strategist` for site direction, positioning, launch scope, and conversion priorities
- `recruiter-agent` for first-visit recruiter and hiring-manager audits
- `content-strategist` for homepage, About, and expertise copy
- `case-study-agent` for public-safe experience cases
- `technical-writing-editor` for article planning and editing
- `astro-architect` for routing, content collections, schemas, and structure
- `frontend-implementation-agent` for Astro components, pages, and CSS
- `brand-visual-design-agent` for Nordic visual direction
- `seo-metadata-agent` for metadata, headings, and search concepts
- `accessibility-quality-agent` for accessibility, responsiveness, and quality checks
- `deployment-agent` for Cloudflare Pages or GitHub Pages setup

## Project-local skills

Use `.agents/skills/` for reusable workflows specific to this website:

- Astro setup: `astro-template-adapter`, `astro-architecture-skill`, `astro-content-collections`
- Visual implementation: `frontend-implementation-skill`, `nordic-design-system`, `template-content-migration`
- Positioning and conversion: `portfolio-content-strategy`, `personal-brand-positioning`, `profile-positioning-skill`, `audience-and-conversion-skill`
- Recruiter review: `recruiter-scan-audit`, `recruiter-visitor-simulator`, `website-content-gap-audit`, `role-fit-analyzer`
- Evidence handling: `professional-background-intake`, `cv-evidence-extractor`, `portfolio-content-transformer`, `linkedin-cv-website-alignment`
- Confidential case content: `confidential-work-sanitizer`, `experience-case-authoring`, `experience-case-builder`
- Research and writing: `research-to-industry-skill`, `technical-writing-starter`, `technical-authority-content-planner`
- Quality and launch: `seo-accessibility-performance`, `astro-static-deployment`

## Recommended first Codex task

```text
Read AGENTS.md and PROJECT_BRIEF.md. Create the initial Astro site structure with pages for Home, Cases, Writing, About, Contact, and Research. Create content collections for cases and writing. Implement a minimal Nordic visual style. Run npm run build and fix errors.
```
