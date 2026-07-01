# Hero Banner Lab Agent Guide

Hero Banner Lab is a standalone static web component and customization page for animated full-screen hero banner samples.

Keep the package public-safe, reusable, and free of private or personal demo content. Attribution to Marco Policani is allowed and expected in license, README, footer, and repository metadata.

## Boundaries

- This product visualizes synthetic banner concepts.
- It does not include employer, client, project, financial, personnel, or private career data.
- It does not claim to be a design system, CMS, analytics platform, production SaaS product, or portfolio-management tool.
- It does not make decisions, approve work, validate records, or certify delivery status.

## Files

- `index.html` is the browser customization page.
- `assets/hero-banner-lab.js` wires the carousel, renderers, controls, and JSON export.
- `assets/hero-banner-lab.css` controls the page and component presentation.
- `assets/portfolio-signal-field.js` is the reusable Portfolio Signal renderer used by the signal sample.
- `examples/default-config.json` is a neutral sample configuration.

## Editing Rules

- Preserve the no-build static-site model unless Marco explicitly asks for a framework.
- Keep sample copy generic and public-safe.
- Keep each hero stage full-screen at 100vh so capture dimensions stay consistent.
- Maintain visible parallax scroll behavior and pointer/mouseover response for each banner.
- Keep controls banner-specific; do not force every sample to expose the same settings.
- Validate with a browser after visual or interaction changes.

## Product Boundary

This package starts when someone wants a configurable animated hero banner sample for a landing page, portfolio page, dashboard header, or visual prototype.

It ends when the user has selected a banner style, tuned its settings, and exported the current JSON configuration.

It produces a reusable static demo page, live canvas previews, and neutral configuration samples.

It hands off to a site owner, designer, or developer who will embed or adapt the animation into a page.
