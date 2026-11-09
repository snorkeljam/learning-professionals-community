# learningprofessionalscommunity.org

The public site for **The Learning Professionals Community** — a cross-sector community
(corporate L&D, higher education, K-12, consulting, association management, workforce
development) working out what AI means for the profession. Convened by Jackrabbit LX.

Static HTML, no build step. GitHub Pages serves this repo's root.

## Pages

| File | What it is |
|---|---|
| `index.html` | The whole pitch: hero, why join, live events calendar, research, join form |
| `research.html` | The Future Skills survey results (197 respondents, six sectors) |
| `reading-list.html` | Related skills research from across the field, 2024–2026 |
| `assets/style.css` | Shared design system (`index.html` only — the two research pages are self-contained) |

## The two embeds

- **Events** — Luma calendar `cal-mXmLGOjZAUvTh31` (<https://luma.com/jlx>), embedded with
  `?theme=light` so it matches the page. It updates itself; new events on Luma appear here
  with no code change.
- **Join form** — the HubSpot form *JLX AI Forum Slack Registration Form*, embedded via its
  share URL. Submissions land in HubSpot portal 4852423 and notify james@jackrabbitlx.com.

## Editing

Edit the HTML and push to `main`. Pages redeploys in about a minute.
