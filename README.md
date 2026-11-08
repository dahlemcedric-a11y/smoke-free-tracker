# Smoke-free Tracker

A single-file, no-build web app to track a smoke-free streak. Open `index.html` in any browser (works offline, mobile-first, light/dark).

## Views
- **Total** – current day number, live smoke-free timer, cigarettes not smoked, money saved, cravings beaten, and health milestones (NHS/WHO timeline) with progress to the next one.
- **Each day** – one card per calendar day since quitting (Day 1 = quit day): smoke-free time that day, a craving counter, and notes. A chain of squares shows every day at a glance.

## Settings (top-right button)
- Last cigarette date/time (default: 7 Nov 2026, 23:00)
- Cigarettes per day, per pack, pack price, currency (defaults: 20/day, €8.50 per 20)
- "I smoked — restart from now" resets the streak; notes are kept.

Data is stored in the browser's `localStorage` only.

## Use it on your phone
Enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root), open the URL on your phone, then "Add to Home Screen".
