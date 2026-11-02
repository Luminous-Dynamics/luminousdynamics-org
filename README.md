# Luminous Dynamics Website

Public homepage for [luminousdynamics.org](https://luminousdynamics.org/).

## Purpose

The site introduces the Luminous Dynamics mission, links visitors to the active software and research portfolio, explains the working principles, and provides a contact route for contributors, research collaborators, and potential deployment partners.

## Source

- `index.html` — static single-page site, styles, portfolio cards, contact form, and lightweight background animation.
- `CNAME` — custom domain.
- `.nojekyll` — GitHub Pages publishing marker.

The site is published through GitHub Pages. Verify repository Pages settings and the deployment configuration before changing the publishing layout.

## Portfolio links

The homepage links to the public organization repositories. Each project's own README is the source of truth for its implementation status, build instructions, license, known limitations, and security posture.

## Editing guidelines

- Keep product names, links, and project status aligned with the [Luminous Dynamics GitHub organization](https://github.com/Luminous-Dynamics).
- Do not describe research prototypes as production software.
- Do not publish unverified performance, safety, consciousness, regulatory, or customer-traction claims.
- Prefer specific capabilities and evidence over broad superlatives.
- Preserve responsive behavior, keyboard focus visibility, and reduced-motion accessibility.
- Do not remove the contact form's anti-spam field or change its endpoint without testing the form.

## Local preview

This is a static HTML page. Open `index.html` in a browser or serve the repository root with a local static HTTP server.

Review the page at desktop and mobile widths before merging. Check browser-console output, contact form behavior, keyboard navigation, reduced-motion behavior, and external links.
