# dashboard
My personal dashboard: live visitor stats for my portfolio, [rambharath199727-stack.github.io/rambharathportfolio](https://rambharath199727-stack.github.io/rambharathportfolio/).

## What it shows

- **KPI tiles:** total views, today, last 7 days, suggestions sent
- **Daily views:** bar chart of the last 14 days (India time), with a table view
- **Devices:** phone vs computer views
- **Clicks:** Resume, Email, GitHub, LinkedIn, "View projects", switched to Tamil, theme switched

## How it works

The portfolio records each event in free [Abacus](https://abacus.jasoncameron.dev) counters under the namespace `rambharath199727-portfolio`. This page (`index.html`) reads those counters in the browser and draws the charts. No build step, no backend, no personal data: only counts.

- Views count once per browser session.
- Daily views, devices, clicks and suggestions are counted from 2 Nov 2026.
- Add `?dev` to the page URL to see the test counters used by local copies of the portfolio.
- Suggestion text is not stored here; it arrives by email.

## Run it

Open `index.html` in a browser, or host the repo with GitHub Pages.
