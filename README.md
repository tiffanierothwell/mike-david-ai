# Mike David · What They Don't Teach Us About Money

A single-page presentation site for Mike David's 90-minute wealth-building class for 11th graders. Built to be navigated like a slide deck on a classroom smartboard — each Act fits in one viewport, no scrolling required during the talk.

## The Class

Eight Acts, 90 minutes:

1. **What Is Money?** — Money is an emotion delivery system
2. **Where We Come From** — The architecture, then the flip
3. **The Four Paths** — Cashflow Quadrant: E / S / B / I
4. **State, Identity & Wealth** — The Triad + Two Sets Of Habits
5. **The Math Of Freedom** — Compounding, the 10% rule, Joe vs Bob
6. **The Tools You Have** — Wealthsimple + Credit Cards
7. **AI · The Master Skill** — The Business Plan Master Prompt + 5 take-home prompts
8. **Three Commitments** — The Builder's first three moves

The whole course builds toward one identity: **The Builder.**

## Stack

- Static HTML / CSS / JS · zero build step
- Montserrat (Google Fonts) · pure black-and-white palette
- All assets self-contained · single `index.html` + `logo.svg`
- No backend, no auth · safe to host anywhere

## Local Preview

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

## Deployment

Designed for static hosting. Drop the repo into Vercel, Netlify, Cloudflare Pages, or GitHub Pages — no configuration needed.

To wire up the `mikedavid.ai` domain:
1. Connect this repo to Vercel (or your platform of choice)
2. Add `mikedavid.ai` as a custom domain in the project settings
3. Point DNS A/CNAME records as the platform instructs

## Keyboard Shortcuts

- `←` / `→` · Navigate between Acts
- `0`–`8` · Jump directly to any Act
- `ESC` · Close any open modal

## Built By

Tiffanie Rothwell · for Mike David · Little Tree Ventures
