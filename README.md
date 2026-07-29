# David's AI Sales System

A browser-based AI sales assistant for B2B field sales — single HTML file, zero backend, zero IT approval needed.

## What it does

Three core sales functions in one tool:

1. **Bid Intake Formatter** — Enter prospect info and materials → AI formats a professional bid request email → send to Gmail Drafts in one click
2. **Follow-Up Email Drafter** — Enter quote details → AI drafts a context-appropriate follow-up email → Gmail Draft + Calendar reminder in two clicks
3. **Lead Gen Engine** — Two ICP versions (project-based buyers / ongoing accounts) → 10 research angles per run → saves to Drive, logs to Sheets

## Tech Stack

| Component | Tool |
|---|---|
| AI engine | DeepSeek API |
| Hosting | GitHub Pages (free) |
| Auth | Google OAuth (GIS token client) |
| Integrations | Gmail Drafts, Google Calendar, Sheets, Drive |

Total cost to run: ~$5 for a 14-day pilot.

## Setup

1. **DeepSeek API key** — Sign up at platform.deepseek.com, add $5 credit, create an API key
2. **Google OAuth** — Connect a personal Gmail account (not a work M365 account) to authorize Gmail, Calendar, Sheets, and Drive access
3. **That's it** — all settings are stored in browser localStorage, nothing on a server

## Run locally

Open `index.html` in any browser. No build step, no dependencies, no server.

Or use the live GitHub Pages site:

**https://hooliganchik27-creator.github.io/davids-sales-tool/**

---

*Built by [NotYourAIDad](https://notyouraidad.ai) | AI-Agnostic. Practitioner-First.*
