# Local Lead Finder

An AI-powered lead discovery and outreach preparation tool for freelancers and agencies offering digital services (websites, e-menus, booking systems, etc.).

## What it does

- **Discovers** local businesses in a given area using real Google Maps data (via Boltscraper API), with automatic radius expansion when results are scarce.
- **Ranks** businesses by an "Opportunity Score" (0–100) based on signals such as missing website, dead website, low rating with high review count, and available contact info.
- **Suggests** personalized service recommendations by searching the web for each business (via Tavily API) to gather social media presence, recent news, and contact details.
- **Generates** either a ready-to-copy AI prompt or a live HTML preview for a website, e-menu, or booking system — tailored to the specific business.
- **Connects** directly via phone, WhatsApp, or Google Maps links.

## Tech Stack

- **Backend:** Python 3.11, FastAPI, SQLAlchemy, PostgreSQL (Neon)
- **Frontend:** Next.js 14, Tailwind CSS, TypeScript
- **APIs:** Boltscraper (Google Maps data), Tavily (web search)
- **Deployment:** Render (backend), Vercel (frontend)

## Status

🚧 Under active development.
