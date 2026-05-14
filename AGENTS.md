# AGENTS.md

## Project purpose

This is the personal professional website of Carlos Jorques.

The site positions Carlos as an **Embedded Control Systems Architect** focused on **Control Intelligence for Physical Systems**.

Primary goal: recruiters, engineering managers, and technical peers should quickly understand Carlos's expertise and contact him.

Secondary goal: build long-term authority through technical writing on embedded control systems, physical systems, diagnostics, safety-related development, and technical leadership.

## Target audiences

1. Recruiters and talent partners
2. Engineering managers and technical hiring managers
3. Technical peers in embedded systems, automotive, controls, and mechatronics
4. Potential collaborators

## Positioning

Primary title: **Embedded Control Systems Architect**

Brand phrase: **Control Intelligence for Physical Systems**

Core message: Carlos leads the design of production-ready embedded control systems for vehicles and smart machines, connecting sensing, signal processing, embedded software, control algorithms, diagnostics, actuation, safety, and delivery.

## Tone

Clear, direct, senior, technically credible.

Use:
- precise engineering language
- concise sections
- specific capability claims
- evidence-backed statements
- recruiter-readable phrasing

Avoid:
- hype
- generic portfolio language
- exaggerated claims
- academic-first positioning
- junior developer portfolio framing
- vague phrases such as "passionate problem solver"

## Content hierarchy

Primary:
- Home
- Cases
- Writing
- About
- Contact

Secondary:
- Research
- Publications
- CV

Research supports credibility but must not dominate the site.

## Confidentiality

Do not reveal confidential employer, OEM, Tier 1, product, architecture, calibration, safety, implementation, or internal project details.

Experience cases must be generalized and public-safe. Focus on role, engineering challenge, system scope, standards, and demonstrated capability.

Unsafe details include:
- named customers or OEMs unless explicitly approved
- internal platform names
- unreleased products
- internal architecture diagrams
- calibration data
- diagnostic mechanisms
- safety analysis details
- exact timelines or business-sensitive context

## Technology

Use Astro.
Use TypeScript where useful.
Use Markdown or MDX for content.
Use Astro Content Collections for cases, writing, and research.
Prefer static generation.
Avoid unnecessary JavaScript.
Avoid React, Vue, Svelte, or other UI frameworks unless there is a clear reason.
Prefer plain CSS with design tokens unless the existing template already uses another styling approach.

## Recommended site structure

Pages:
- `/`
- `/cases/`
- `/cases/[slug]/`
- `/writing/`
- `/writing/[slug]/`
- `/about/`
- `/contact/`
- `/research/`

Collections:
- `cases`
- `writing`
- `research`

Components:
- Header
- Footer
- Hero
- ExpertiseCard
- CaseCard
- PostCard
- SystemModel
- ContactCTA
- SectionHeading

## Homepage structure

1. Hero
2. Expertise snapshot
3. Machine nervous system / control chain model
4. Selected experience cases
5. Featured writing
6. Research foundation
7. Contact CTA

## Hero direction

Title: Embedded Control Systems Architect

Main phrase: Control Intelligence for Physical Systems

Body: I lead the design of production-ready embedded control systems for vehicles and smart machines — connecting sensing, signal processing, embedded software, control algorithms, diagnostics, actuation, safety, and delivery.

Credibility line: PhD-trained electrical engineer with automotive OEM and Tier 1 experience across embedded control, diagnostics, safety-related development, and cross-functional delivery.

Buttons:
- Contact me
- View cases
- Download CV

## Design direction

Minimal Nordic technical style.

Use:
- off-white or warm white background
- graphite or near-black text
- cool gray surfaces
- muted blue, green, or steel accent
- generous whitespace
- strong readable typography
- subtle borders
- restrained hover states

Avoid:
- flashy animations
- heavy gradients
- neon colors
- stock illustrations
- excessive icons
- skill bars
- glassmorphism
- SaaS-style marketing clutter
- frontend-developer portfolio cliches

The site should feel calm, precise, technical, mature, and easy to scan.

## SEO focus

Target concepts:
- Embedded Control Systems Architect
- Control Intelligence for Physical Systems
- embedded control systems
- automotive embedded software
- control systems architecture
- diagnostics
- sensing and actuation
- ISO 26262
- A-SPICE
- AUTOSAR-oriented development
- technical leadership

## Quality requirements

Before completing implementation tasks:
- run `npm run build`
- run formatting or linting if configured
- check responsive layout
- check semantic HTML
- check heading hierarchy
- check contact links
- check metadata and page titles
- ensure no confidential information is included

If a command fails, fix the issue or clearly explain what remains unresolved.

## Project-local agent playbooks

This repository includes task-specific playbooks under `agent-playbooks/`. Use them as operating modes when the user asks for that role or when the task clearly matches the playbook.

Strategy and review:
- `project-strategist`: positioning, information architecture, launch scope, recruiter conversion.
- `recruiter-agent`: 7-second, 30-second, and 2-minute recruiter/hiring-manager review.
- `accessibility-quality-agent`: semantic HTML, heading hierarchy, accessibility, responsiveness, quality checks.
- `seo-metadata-agent`: titles, descriptions, Open Graph metadata, headings, slugs, search concepts.

Content:
- `content-strategist`: homepage, About, expertise summaries, article planning, recruiter-readable copy.
- `case-study-agent`: public-safe experience cases from CV/project material.
- `technical-writing-editor`: technical article outlines and edits for authority-building writing.

Implementation:
- `astro-architect`: routes, layouts, content collections, schemas, build structure.
- `frontend-implementation-agent`: Astro components, pages, responsive CSS, layout polish.
- `brand-visual-design-agent`: Nordic visual system, hierarchy, spacing, typography, color.
- `deployment-agent`: Cloudflare Pages/GitHub Pages deployment setup and documentation.

## Project-local skills

This repository includes reusable Codex skills under `.agents/skills/`. Prefer these local skills for this project before using generic guidance, because they encode the site's positioning, confidentiality rules, Astro conventions, and launch priorities.

Astro and implementation:
- `astro-template-adapter`
- `astro-architecture-skill`
- `astro-content-collections`
- `frontend-implementation-skill`
- `template-content-migration`
- `astro-static-deployment`

Positioning, audience, and conversion:
- `personal-brand-positioning`
- `profile-positioning-skill`
- `portfolio-content-strategy`
- `audience-and-conversion-skill`
- `recruiter-scan-audit`
- `recruiter-visitor-simulator`
- `role-fit-analyzer`
- `website-content-gap-audit`
- `linkedin-cv-website-alignment`

Evidence and content transformation:
- `professional-background-intake`
- `cv-evidence-extractor`
- `portfolio-content-transformer`
- `confidential-work-sanitizer`
- `experience-case-builder`
- `experience-case-authoring`
- `research-to-industry-skill`

Writing and authority:
- `technical-writing-starter`
- `technical-authority-content-planner`

Design and quality:
- `nordic-design-system`
- `seo-accessibility-performance`

When multiple local skills apply, use the smallest set that covers the task. For example:
- Default Astro starter to first website version: `astro-template-adapter`, `portfolio-content-strategy`, `astro-content-collections`, `nordic-design-system`.
- Recruiter review and improvement pass: `recruiter-scan-audit`, `website-content-gap-audit`, `audience-and-conversion-skill`.
- Convert CV/project notes into public cases: `cv-evidence-extractor`, `confidential-work-sanitizer`, `experience-case-authoring`.
- Prepare deployment: `astro-static-deployment`, then `seo-accessibility-performance`.
