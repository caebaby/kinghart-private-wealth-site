# Kinghart Private Wealth Design System

## Scene

A successful professional opens the site on a laptop between meetings in natural daylight. The page should feel like entering a private, well-considered office: calm, ordered, human, and discreet.

## Color Strategy

Use a committed brand palette with Legacy Midnight and Kinghart Navy carrying the page. Estate Ivory provides breathing room, Heritage Gold marks key decisions and calls to action, Reserve Blue supports secondary content, and Capital Charcoal handles neutral copy.

- Kinghart Navy: `#142A43`
- Heritage Gold: `#B79551`
- Legacy Midnight: `#0D1827`
- Estate Ivory: `#F5F1E8`
- Reserve Blue: `#52687D`
- Capital Charcoal: `#292C30`

Avoid pure white and pure black. Use tinted alpha values derived from the official palette for rules, overlays, and muted text.

## Typography

- Official logo artwork: Legitima, used only inside the supplied logo asset
- Interface and content: Avenir Next / Avenir with system fallbacks
- Headings rely on size, spacing, and weight contrast rather than an imitation luxury serif
- Body line length: 60 to 72 characters
- Navigation and labels: compact Avenir uppercase with restrained tracking

## Layout

- Maximum content width: 1440px
- Desktop uses a rigorous 12-column feel with asymmetric splits and numbered chapters
- Long-form copy remains readable and never spans the full viewport
- Section spacing is fluid and varied to create a deliberate rhythm
- Borders are one-pixel tinted rules, not decorative side stripes
- Mobile sections become single-column without losing the numbered narrative

## Imagery

- Hero: cinematic, believable private office architecture with a calm mountain and tree-line outlook
- Nate: current professional headshot until the replacement arrives
- Legacy: the supplied Neill family portrait as the primary emotional image
- Grandfather story: restrained black-and-white generational image
- Avoid cacti, orange desert landscapes, obvious luxury props, market charts, and staged handshakes

## Components

- Buttons: squared or minimally rounded, strong labels, gold primary and outlined secondary treatments
- Numbered chapters: small numeric marker plus strong title and a thin rule
- Accordions: bordered rows that reveal content in place with a rotating indicator
- Service list: structured rows rather than repeated cards
- Image panels: edge-to-edge crops with subtle overlays only when required for legibility

## Motion

- Use transform and opacity only for hover and reveal movement
- Ease with a restrained quint or expo curve
- Accordions animate their content grid, not explicit heights
- Respect `prefers-reduced-motion`
