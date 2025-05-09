# Portfolio Auto-Manager

This n8n automation takes finished projects and auto-uploads them to a GitHub portfolio. It packages the project folder, README, workflow JSON, and screenshots — and even updates the main portfolio index.

## Features
- Reads project metadata (name, level, description)
- Uploads `README.md`, `.json` workflow, and screenshots to GitHub
- Automatically creates structured folders in the repo
- Designed to mirror manual uploads for consistency
- Ready to evolve into a fully auto-updating portfolio site

## Why It Matters
Tired of manually organizing your GitHub portfolio? This automation turns your project workflow into a one-click deployment. Great for freelancers, career-switchers, and anyone showcasing their skills with real automation.

## Tech Stack
- n8n
- GitHub API
- Manual Trigger (with webhook version coming)
- Future-ready for Notion/Sheets sync

## Screenshots

![Portfolio Auto Manager](./screenshots/portfolio%20auto%20manager.png)
