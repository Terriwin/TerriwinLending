# Product

## Register

brand

## Users

Prospective clients of Terriwin — a freelance web developer working primarily with
Russian-speaking founders, small business owners, and decision-makers who are
commissioning a website or web app. They arrive from a Telegram link, a referral, or
a direct share, usually on the strength of "show me what you can do." Their context is
evaluative and fast: they are deciding, often in under a minute, whether this person is
worth a conversation. Many browse on mobile. The site is bilingual (RU primary, EN
toggle) because some clients and collaborators are international.

The job to be done: **see proof of taste and capability, then start a conversation**
(the Telegram CTA). Secondary job: explore the work itself — the portfolio drawer and
live demo pieces like `/arcadebuild` ARE the argument.

## Product Purpose

A personal portfolio that sells Terriwin's craft by *being* an example of it. It exists
because for a web developer the strongest sales asset is the portfolio site itself —
every interaction is a live demonstration of the skill on offer. Success looks like a
visitor reaching the Telegram CTA convinced this is a premium, meticulous developer who
ships work that feels expensive and runs flawlessly. The demo pieces (the ArcadeBuild
luxury-construction landing at `/arcadebuild`) carry the same burden: each is a
standalone showcase that has to hold up on its own.

## Brand Personality

Premium and precise. Three words: **expensive, exacting, quiet-confident.** The voice is
restrained and assured — it does not oversell or use startup hype. Tone is calm and
declarative ("Дизайн и разработка сайтов под ключ"), letting the craft speak. The
emotional goal: a visitor should feel they are looking at work for serious clients, made
by someone who sweats every pixel and ships things that simply work. Warmth comes from
the champagne/gold accent and considered motion, never from informality.

## Anti-references

- **Templated freelance.** Tilda/site-builder landing pages, stock illustrations, generic
  "modern" gradients, the interchangeable look that says "this person uses presets." The
  whole point is to read as bespoke.
- **Light / neutral "safe office" look.** White background, gray body text, no
  character. The brand lives in a dark, atmospheric register; a bright neutral palette
  would erase its identity.
- **Corporate SaaS clichés.** Blue-gradient hero, white icon-cards in a grid, the
  hero-metric template (big number + small label + supporting stats). Avoid by reflex.
- **Overloaded / noisy.** Excess neon glow, animation on everything, busy effects that
  read as cheap. Motion must be deliberate and sparse.

## Design Principles

- **The site is the portfolio.** Every interaction is a live audition. Hold demo pieces
  (`/arcadebuild`) to the same bar as the main page — they are the proof, not throwaways.
- **Expensive is in the details.** Tight typography, considered spacing, flawless
  responsive behavior at every resolution (mobile → 2K), zero broken states. "Looks
  premium" is earned by craft, not decoration.
- **Quiet confidence over salesmanship.** Restraint reads as expertise. One memorable
  signature element per surface; everything around it stays disciplined.
- **Motion is intentional.** Parallax, reveals, and micro-interactions exist to express
  cause and effect, never as filler. Respect `prefers-reduced-motion` always.
- **Bilingual without compromise.** RU and EN must both look deliberate; the language
  switch is itself part of the craft on display.

## Accessibility & Inclusion

Target WCAG 2.1 AA. Body text must clear 4.5:1 against the dark background — watch the
muted `--text-2` / `--text-3` ramps on tinted surfaces. `prefers-reduced-motion` is
already honored (orbs and reveals disable) and must stay honored in all new work. Keep
semantic `lang` attributes correct across the RU/EN toggle, visible keyboard focus on
all interactive elements (nav, CTA, custom select, accordion), and real labels on form
fields and icon-only buttons. Touch targets ≥44px on mobile.
