# AGENTS.md

## Project purpose

This repository is the personal professional website of Carlos Jorques.

The site positions Carlos as an Embedded Control Systems Architect under the brand phrase:

Control Intelligence for Physical Systems

The site should communicate senior technical leadership in embedded control systems for vehicles and smart machines. It should not read or look like a generic frontend developer portfolio.

## Target audiences

Primary audiences:

- Recruiters
- Engineering managers
- Technical hiring managers

Secondary audiences:

- Technical peers
- Collaborators
- Automotive, embedded systems, mechatronics, and control systems professionals

The main conversion goal is contact through LinkedIn, email, and CV download.

## Positioning

Core message:

Carlos leads the design of production-ready embedded control systems for vehicles and smart machines, connecting sensing, signal processing, embedded software, control algorithms, diagnostics, actuation, safety, and delivery.

Relevant concepts include embedded control systems, automotive embedded software, control systems architecture, diagnostics, sensing and actuation, ISO 26262, A-SPICE, AUTOSAR-oriented development, and technical leadership.

## Tone

Use calm, precise, technical language. Emphasize engineering judgment, architecture, production readiness, safety-related thinking, diagnostics, and delivery. Avoid generic phrases such as "passionate engineer", "problem solver", "welcome to my portfolio", "full-stack developer", and "frontend portfolio".

Research is a credibility foundation, but the main identity is industrial technical leadership.

## Confidentiality rules

Do not invent confidential or proprietary details.

Do not mention specific OEMs, suppliers, products, architectures, calibration details, internal requirements, implementation details, or unreleased work unless Carlos explicitly provides approved public copy.

Case studies must remain public-safe and generalized.

## Design direction

Use a minimal Nordic technical style:

- Off-white or warm white background
- Graphite or near-black text
- Cool gray surfaces
- Muted blue, green, or steel accent
- Generous whitespace
- Strong readable typography
- Subtle borders
- Restrained hover states
- No flashy animations
- No skill bars
- No stock illustrations
- No heavy gradients
- No SaaS-like marketing clutter

The site should feel calm, precise, technical, mature, and easy to scan.

## Astro conventions

- Use Astro idiomatically with `.astro` pages and components.
- Keep JavaScript minimal.
- Do not add React, Vue, Svelte, Tailwind, or another UI framework unless there is a clear requirement.
- Prefer plain CSS with design tokens in `src/styles/global.css`.
- Use content collections for cases and writing.
- Keep reusable UI in `src/components/`.
- Keep page-level structure in `src/pages/`.
- Keep public-safe content in `src/content/`.

## Quality checks

Before handing off substantial changes:

- Inspect the project structure.
- Run `npm install` if dependencies are missing and npm is available.
- Run `npm run build`.
- Fix build errors.
- Verify that pages compile.
- Summarize changed files and placeholders.
