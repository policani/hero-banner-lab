# Hero Banner Lab

**Hero Banner Lab** is a reusable set of full-screen animated hero banner samples with parallax scroll behavior, pointer response, and exportable JSON settings.

Created by **Marco Policani**, it packages three public-safe visual concepts:

- Portfolio Signal: synthetic portfolio cards, dependency filaments, and operating signals.
- Decision Gates: dark AI/LLM-inspired gate columns with attraction-field filaments.
- Filament Network: blue node, numeric-label, and connection-field hero animation.

## Status

Public-safe standalone prototype. No build step, dependency install, API key, or backend is required.

Live demo target:

https://policani.net/hero-banner-lab.html

## How To Evaluate

Open `index.html` in a browser or serve the folder with a simple static server. Use the selector to switch banners, adjust the controls below the full-screen preview, and export the current JSON configuration.

For consistent screenshots, open one of these URLs at the same browser viewport size:

```text
index.html?banner=signal&capture=1
index.html?banner=decision-gates&capture=1
index.html?banner=filament-network&capture=1
```

## What It Does

- Renders full-screen hero banner samples at a consistent 100vh frame.
- Provides noticeable scroll parallax and pointer/mouse response.
- Gives each banner its own configurable controls.
- Exports reusable JSON settings for the selected banner.
- Keeps sample copy and visual data generic, synthetic, and public-safe.

## What It Does Not Do

- It does not include personal, employer, client, financial, or private project data.
- It does not store, transmit, or analyze user data.
- It does not replace a design system, CMS, production analytics tool, or portfolio-management platform.
- It does not claim that the visual samples represent live systems or real records.

## Folder Structure

```text
hero-banner-lab/
  index.html
  README.md
  AGENTS.md
  LICENSE.md
  .gitignore
  assets/
    hero-banner-lab.css
    hero-banner-lab.js
    portfolio-signal-field.js
    portfolio-site.css
  docs/
    implementation-guide.md
  examples/
    default-config.json
```

## Local Use

The page can run directly from disk. For browser automation or capture workflows, a local static server is usually more reliable:

```bash
python -m http.server 4182
```

Then open:

```text
http://127.0.0.1:4182/
```

## Suggested GitHub Metadata

Repository description:

> Configurable full-screen animated hero banner samples with parallax, pointer response, and JSON settings.

Suggested topics:

```text
hero-banner
landing-page
canvas-animation
parallax
portfolio
javascript
static-site
web-design
data-visualization
frontend
```

## License

Source code and scripts are licensed under MIT. Documentation, examples, and configuration samples are licensed under CC BY 4.0 with attribution to Marco Policani. See `LICENSE.md`.
