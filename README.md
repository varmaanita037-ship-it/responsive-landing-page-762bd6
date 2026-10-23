# Loamly — Responsive Landing Page

A responsive homepage for **Loamly**, a fictional startup that makes a pocket-sized smart soil sensor for home gardeners.

## Sections
- **Header**: a sticky-feel navigation bar with a mobile hamburger menu, and a hero with a headline, calls to action, stats, and a mock app screen
- **Feature highlights**: a bento-style grid of five product features
- **How it works**: three steps
- **Testimonials**: three customer quote cards
- **Call to action**: a pre-order banner
- **Footer**: brand blurb, link columns, copyright, and social links

## Technologies
- HTML5 (semantic elements: `header`, `nav`, `main`, `section`, `article`, `figure`, `footer`)
- CSS3: **CSS Grid** (hero, features, testimonials, footer) and **Flexbox** (nav, buttons, steps, CTA, footer bar), custom properties, `clamp()` for fluid type, and media queries at 960px and 720px
- No JavaScript. The mobile menu uses a CSS-only checkbox toggle.
- Google Fonts: Fraunces and Manrope

## Running locally
There is no build step. Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploying
The included `netlify.toml` publishes the project root on Netlify.
