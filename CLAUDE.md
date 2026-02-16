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

## Development Notes

- All HTML files are self-contained (no build step)
- Flow lines use CSS animations with dotted patterns
- Tooltips auto-cycle every 3.5s on desktop
- Outcomes carousel cycles every 3s

## Testing Checklist

Before publishing, verify each file:
- [ ] Flow line animations working
- [ ] Engine icons loading from imgur
- [ ] Responsive layout at mobile/desktop
- [ ] Tooltip cycling on hover/auto
- [ ] Source icons colored correctly

## GitHub Pages

Published at: https://reddy57.github.io/Playground/
