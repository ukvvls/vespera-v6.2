# VESPERA V6 — Prism Glass

A fresh rebuild of the VESPERA interface focused on clear spacing, real translucent glass layers, a floating glass navigation dock, multiple full-interface accent themes, and an in-app notification center.

## Included
- Home dashboard with player rank, XP, tasks and activity summary.
- Daily tasks, task library, filters and XP progression.
- Activity log, exercise library and seven-day activity chart.
- Local assistant for organizing selected tasks and the day.
- Floating glass navigation bar on mobile and desktop.
- Notification center for task/activity events and due/overdue tasks.
- Optional browser notifications when supported and permitted.
- Six accent themes: blue, pink, violet, cyan, emerald and amber.
- Arabic/English interface, local storage, backup import/export, PWA manifest and offline shell.

## Notifications note
In-app notifications are stored locally. Browser/system notifications require HTTPS, browser support and user permission. Due-task checks run when the app is opened; this package does not include a remote push server or guaranteed background delivery while the app is closed.

## Privacy
No account, cloud AI, external AI API, or external runtime library is used. Data stays in this browser's local storage. Export a backup before clearing browser data.

## Run
Upload all files to the root of a static HTTPS host, or open `index.html` locally. Service-worker/PWA installation requires HTTPS (or localhost).
