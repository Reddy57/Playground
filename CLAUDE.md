# AIOps Architecture Flow

Interactive visualization of the AIOps data pipeline showing data flow from Sources through AI Engines to Business Outcomes.

## Project Structure

```
AIOps-Final.html              # Recommended - All fixes applied
AIOps-Mission-Control.html    # "NASA control room" aesthetic
AIOps-Complete-Flow.html      # Clean dark theme
AIOps-Glass-Modern.html       # Glassmorphism with animated orbs
AIOps-Premium-Light.html      # Light corporate theme
AIOps-Responsive-Fixed.html   # Dark technical theme
```

Reference files (original):
- `Original Working in FUll Screen.html` - Original working version
- `AIOpsNotWorkingFullScreen.html` - Version with full-screen issues

## AI Engine Icons

| Engine | URL | Role |
|--------|-----|------|
| Atlas | https://imgur.com/0ya7Fj7.png | Data Integration |
| Merlin | https://imgur.com/QyrDXOG.png | Correlation & Insights |
| Argus | https://imgur.com/xMcN4Yw.png | Noise Reduction & RCA |
| Hephaestus | https://imgur.com/7QbiKPT.png | Action & Automation |

## Tech Stack

- HTML5, CSS3 (Grid, Flexbox, animations)
- Tailwind CSS (CDN)
- Font Awesome icons
- JavaScript for SVG flow lines and carousel

## Responsive Breakpoints

- Mobile (<1024px): Vertical stack layout
- Desktop (>=1024px): Horizontal pipeline with branches

## GitHub Pages

Published at: https://reddy57.github.io/Playground/

---

## Recent Fixes (Applied to AIOps-Final.html)

### 1. HTML Validation Fixes
- Changed self-closing `<link />` to `<link>` (HTML5 void elements)
- Encoded `&` as `&amp;` in text content (e.g., "Correlation & Insights")

### 2. Flow Line & Arrow Fixes
- **Extended flow lines** with arrow heads pointing in flow direction
- **Arrows start at panel edges** - not inside the panels
- Entry line: `left: calc(-4vw - 20px); width: calc(4vw + 20px);`
- Exit line: `right: calc(-4vw - 20px); width: calc(4vw + 20px);`
- Arrow heads use CSS triangles with `border-left: 12px solid var(--signal)`

### 3. Node Positioning Fixes
- **Atlas moved down** to `top: 54%` so trunk line points at circle center
- **Merlin label above icon** using `flex-direction: column-reverse` to avoid line overlap

### 4. Data Sources Grid
- Added 2 more sources: GitHub (`fa-github`, color: #f0f0f0) and PagerDuty (`fa-bell`, color: #06AC38)
- Total: 12 sources (fills 4 complete rows of 3 on desktop)
- Updated count text: "12 sources connected"

---

## TODO: Apply Same Fixes to Other Files

Files to update (in order):
1. [x] AIOps-Final.html - DONE
2. [ ] AIOps-Mission-Control.html
3. [ ] AIOps-Complete-Flow.html
4. [ ] AIOps-Glass-Modern.html
5. [ ] AIOps-Premium-Light.html
6. [ ] AIOps-Responsive-Fixed.html

### Fixes to Apply to Each File:
1. Flow entry/exit lines - shorten to `calc(-4vw - 20px)` width
2. Add arrow heads with CSS triangles
3. Move Atlas down (~54%) for center alignment
4. Move Merlin label above icon (flex-direction: column-reverse)
5. Add GitHub and PagerDuty to source grid (12 total)
6. Update source count to 12
7. Validate HTML passes

---

## Testing Checklist

Before publishing, verify each file:
- [ ] Flow line animations working
- [ ] Arrow heads visible and pointing right
- [ ] Arrows start at panel edges (not inside)
- [ ] Atlas circle center aligned with trunk line
- [ ] Merlin label above icon (not covered by line)
- [ ] 12 source icons in complete grid
- [ ] Engine icons loading from imgur
- [ ] Responsive layout at mobile/desktop
