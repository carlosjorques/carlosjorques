# Project Brief

## Goals

Create the first version of Carlos Jorques's personal professional website.

The site should position Carlos as an Embedded Control Systems Architect with the brand phrase "Control Intelligence for Physical Systems." It should support contact-oriented conversion for technical leadership roles, embedded control systems architecture opportunities, automotive software/control projects, and professional collaboration.

## Site structure

Primary navigation:

- Home
- Cases
- Writing
- About
- Contact

Secondary page:

- Research

Homepage order:

1. Hero
2. Expertise snapshot
3. Machine nervous system / control chain model
4. Selected experience cases
5. Featured writing
6. Research foundation
7. Contact CTA

## Content model

Cases are stored in `src/content/cases/`.

Each case supports:

- `title`
- `summary`
- `role`
- `capabilities`
- `standards`
- `domain`
- `confidentialityNote`
- `featured`
- `order`

Writing is stored in `src/content/writing/`.

Each article supports:

- `title`
- `description`
- `publishDate`
- `category`
- `tags`
- `featured`
- `draft`

Research is currently implemented as a secondary static page with placeholders for thesis, publications, research themes, and external links.

## Launch scope

This first version includes:

- Full page structure
- Shared layout, header, footer, and reusable components
- Public-safe placeholder case studies
- Draft article placeholders
- Contact page with email, LinkedIn, and CV placeholders
- Basic SEO metadata support
- Minimal Nordic technical styling
- Repository guidance for future agents

## Future improvements

- Replace email, LinkedIn, and CV placeholders with real links.
- Add approved CV file under `public/`.
- Add final case study language after confidentiality review.
- Replace draft writing placeholders with full articles.
- Add thesis, publications, Google Scholar, ORCID, and other research links.
- Add site URL to `astro.config.mjs` when deployment target is known.
- Add automated checks or formatting once preferred tooling is decided.
