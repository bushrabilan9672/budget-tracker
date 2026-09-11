## Week 3 — Visual Design

### Color Palette
A cohesive teal-and-amber palette is defined as CSS variables in `:root`:
- Primary: #0F766E (teal)
- Primary Dark: #0B5A54
- Primary Light: #CCE7E4
- Accent: #F59E0B (amber)
- Background: #F4F7F6
- Surface: #FFFFFF
- Text: #1F2937
- Muted: #6B7280
- Border: #D1D9D6

### Typography
Two Google Fonts are paired for visual hierarchy:
- **Poppins** (headings, buttons, table header, labels) — modern and confident
- **Inter** (body text, inputs, table cells) — highly readable

Both are loaded via Google Fonts with `display=swap`.

### Table and Form Styling
- Table has a teal header with uppercase text, rounded corners, padding, alternating row colors, and a hover highlight.
- Form inputs share consistent padding, border-radius, and a focus glow effect.
- Buttons have hover, active, and shadow states.

### CSS Box Model
- All sections are treated as "cards": white surface, padding, border, border-radius, subtle shadow.
- Spacing uses a consistent 4/8/16/24/32px scale via CSS variables.
- `box-sizing: border-box` is applied globally.