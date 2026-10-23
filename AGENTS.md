# AGENTS.md

## Overview
This is a static, single-page landing site for "Loamly", a fictional soil-sensor startup. It was built as an HTML5/CSS3 exercise, so it deliberately has no framework, no build step, and no JavaScript.

## Files
- `index.html`: all markup. HTML comments mark each section (header, features, how, testimonials, CTA, footer).
- `styles.css`: all styles. Design tokens are CSS custom properties in `:root`. Rules follow the page order, with responsive overrides at the end (`max-width: 960px` for tablet, `720px` for mobile).
- `netlify.toml`: publishes the repo root.

## Conventions and decisions
- The exercise requires both layout systems, so each one is used where it fits: **Grid** for 2D layouts (hero, feature bento, testimonials, footer columns) and **Flexbox** for 1D rows (nav, buttons, steps, CTA, footer bar).
- The mobile nav uses the `#nav-toggle` checkbox and the `+` and `~` sibling selectors. Keep the checkbox right before the label and the `ul` in the DOM.
- The app mockup in the hero is pure CSS (a conic-gradient gauge, plus bars driven by the `--w` custom property). It uses no images.
- Keep it dependency-free. Don't add a bundler or JS unless the scope changes.
