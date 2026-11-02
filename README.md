# dashboard
My personal visitor dashboard.

**Live:** https://rambharath199727-stack.github.io/dashboard/

This repo holds only the dashboard page (`index.html`). It reads visitor counts recorded by my portfolio website, which lives in its own repo: [rambharathportfolio](https://github.com/rambharath199727-stack/rambharathportfolio).

## What it shows

- **KPI tiles:** total views, today, last 7 days, suggestions sent
- **Daily views:** bar chart of the last 14 days (India time), with a table view
- **Devices:** phone vs computer views
- **Clicks:** Resume, Email, GitHub, LinkedIn, "View projects", switched to Tamil, theme switched

## How it works

The portfolio records each event in free [Abacus](https://abacus.jasoncameron.dev) counters under the namespace `rambharath199727-portfolio`. This page reads those counters in the browser and draws the charts. No build step, no backend, no personal data: only counts.

- Views count once per browser session.
- Daily views, devices, clicks and suggestions are counted from 2 Nov 2026.
- Add `?dev` to the page URL to see the test counters used by local copies of the portfolio.
- Suggestion text is not stored here; it arrives by email.

## Run it

Open `index.html` in a browser, or view the live page above (GitHub Pages, `main` branch).
