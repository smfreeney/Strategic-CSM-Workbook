# Strategic CSM Workbook

An interactive, browser-based reference tool for Customer Success Managers built on Chad Horenfeldt's [Strategic Customer Success](https://strategiccustomersuccess.com) frameworks.

## Overview

A single-file HTML workbook covering the full strategic CSM practice — from pre-meeting prep to weekly planning to portfolio health tracking. No backend, no dependencies, no login required. Everything runs in the browser and persists via `localStorage`.

## Features

### Reference sections
- **Meeting frameworks** — ACE opener, OARS conversation technique, SOON funnel with motivation matrix, QBR checklist, feature request and de-escalation guides
- **Discovery** — Bob London's radically authentic discovery question bank, vague-to-measurable outcome conversion guide, call assessment scorecard with sliders
- **Risk management** — 3-phase detection/categorization/mitigation system with weekly checklist
- **Renewal & expansion** — JRP development checklist (120-day), SPOON expansion framework
- **90-day onboarding plan** — Phase checklists (Days 1–30, 31–60, 61–90) plus kickoff meeting checklist
- **AI prompts** — PLAN framework with 3 ready-to-use prompts for pre-meeting briefings, discovery questions, and call assessment

### Interactive tools
- **Weekly RFS planner** — Reflect, Focus, Schedule ritual with per-week storage, prioritized focus items, and calendar audit checklist
- **Client health tracker** — Portfolio dashboard with Green/Yellow/Red health status, 11 toggleable risk category flags, renewal dates, segments, and notes
- **Hero journey maps** — Per-customer maps covering quest, obstacles, supporting characters, and personality — multiple maps, dropdown navigation

### Export
All three interactive tools support plain-text export:
- Weekly planner exports as `rfs-YYYY-MM-DD.txt`
- Portfolio exports as `health-tracker-YYYY-MM-DD.txt` sorted by risk level (Red first)
- Hero maps export as `hero-[name]-YYYY-MM-DD.txt`

## Tech

- Pure HTML/CSS/JavaScript — zero frameworks, zero dependencies
- All data stored in browser `localStorage`
- Responsive layout, dark mode supported via `prefers-color-scheme`
- Single file: `index.html`

## Deployment

Deployed as a static site on Vercel. To deploy your own instance:

```bash
# Clone the repo
git clone https://github.com/your-username/csm-workbook.git
cd csm-workbook

# Deploy via Vercel CLI
vercel deploy
```

Or connect the repo to Vercel via the dashboard for automatic deploys on push.

## Data & Privacy

All data entered into the workbook (client names, notes, journal entries, hero maps) is stored exclusively in your browser's `localStorage`. Nothing is sent to any server. Clearing your browser storage will erase workbook data — use the export buttons to back up anything important before clearing.

Data does not sync across devices or browsers. For multi-device use, export from one browser and manually transfer as needed.

## Frameworks referenced

- OARS — Open questions, Affirmations, Reflections, Summaries
- SOON — Success, Obstacles, Options, Next Steps
- ACE — Appreciate, Confirm, Engage
- SPOON — Success, Pain, Obstacles, Options, Next Steps
- RFS — Reflect, Focus, Schedule
- PLAN (AI prompting) — Purpose, Limits, Audience context, Needed output
- 3C research — Company, Customers, Challenges
- Bob London's Radically Authentic Discovery framework

All frameworks sourced from [Strategic Customer Success](https://strategiccustomersuccess.com) by Chad Horenfeldt.

## License

Personal and professional use. Frameworks are the intellectual property of Strategic Customer Success / Chad Horenfeldt.
