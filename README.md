# Smoke-free Tracker

A single-file, no-build web app to track a smoke-free streak. Open `index.html` in any browser (works offline, mobile-first, light/dark).

## Views
- **Now** (default) – four KPIs: current phase of the day (Morning 07–12, Afternoon 12–17, Evening 17–22; shows 100% at night), whole current 24h day, 3-day goal and 7-day goal, plus a timeline of today's phases.
- **Total** – current day number (Day 1 = first 24h after the last cigarette, Day 2 = next 24h, …), live smoke-free timer, cigarettes not smoked, money saved, cravings beaten, and health milestones (NHS/WHO timeline) with progress to the next one.
- **Each day** – one card per 24-hour day since quitting (with its exact start → end time): progress through the day, a craving counter, and notes. A chain of squares shows every day at a glance.

## Settings (top-right button)
- Last cigarette date/time (default: 6 Nov 2026, 23:00)
- Cigarettes per day, per pack, pack price, currency (defaults: 20/day, €8.50 per 20)
- "I smoked — restart from now" resets the streak; notes are kept.

Data is stored in the browser's `localStorage` only.

## Use it on your phone
Enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root), open the URL on your phone, then "Add to Home Screen".
