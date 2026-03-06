# Claw Ecosystem Master Design System (v2.0)
Based on UI-UX Pro Max Generation

## Global Identity
- **Name**: Claw Intelligence Ecosystem
- **Core Pattern**: AI OS / Platform-centric Dashboard
- **Vertical**: Developer Tools / Artificial Intelligence

## Design Tokens
- **Colors**:
  - `bg-primary`: #020617 (OLED Black/Deep Navy)
  - `bg-secondary`: #0f172a (Slate Navy)
  - `accent`: #38bdf8 (Sky Blue - Default)
  - `text-primary`: #f8fafc (Clean White)
  - `text-muted`: #94a3b8 (Slate Gray)
- **Typography**: 
  - Sans: 'Inter', sans-serif (Headers & UI)
  - Mono: 'JetBrains Mono', monospace (Technical data & links)
- **Corner Radius**: 
  - Buttons/Cards: 12px (Premium sleek)
  - Large containers: 24px

## Interaction Guidelines
- **Icons**: Lucide SVG Components (strictly no emojis)
- **Cursors**: `cursor-pointer` on all interactive nodes
- **Transitions**: `transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1)`
- **Hover States**:
  - Buttons: Subtle scale (1.02) + background shift
  - Links: Underline reveal or accent color shift

## Anti-Patterns (To Avoid)
- No bright neon base colors (keep premium dark).
- No harsh rapid animations (use ease-out).
- No standard browser default buttons.
- No low-contrast text on dark backgrounds.

## Pre-Delivery Checklist
- [ ] Responsive Breakpoints: 375, 768, 1024, 1440.
- [ ] WCAG AA contrast (4.5:1).
- [ ] Focus rings for keyboard navigation.
- [ ] Skeleton loading states simulated for heavy data.
