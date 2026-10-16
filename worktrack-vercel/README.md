# WorkTrack — Employee Productivity, Quality & Attendance Tool

A fully interactive UI demo prototype. Deploy instantly on Vercel — no build step needed.

## ⚡ Deploy to Vercel in 60 seconds

```bash
# 1. Clone or init your repo
git init
git add .
git commit -m "feat: WorkTrack UI demo"
git branch -M main
git remote add origin https://github.com/Upendra6367/worktrack.git
git push -u origin main
```

Then go to [vercel.com](https://vercel.com) → New Project → Import `worktrack` repo → Deploy.

No framework, no settings to change. Vercel auto-detects it as a static site.

## Screens

| Screen | Description |
|---|---|
| Login | Role switcher: Admin / Annotator |
| Admin Dashboard | 8 pages: Dashboard, Tasks, Attendance, Productivity, Quality, Projects, Employees, Alerts |
| Annotator View | My Dashboard, Tasks, Attendance, Quality |

## Interactive Features

- Role-based login (Admin vs Annotator)
- Live break timer with countdown
- Real-time clock on attendance screen
- Notification panel (TAT alerts, duplicate IDs, missing hold reasons)
- Google Sheets sync status indicator
- TAT compliance bars (green / orange / red)
- Quality grading per annotator (A+, A, B, C)
- Filter bars: period, project, annotator, status
- Export buttons (CSV/Excel placeholders)

## Project Structure

```
worktrack/
├── index.html      # Self-contained UI demo (no dependencies)
├── vercel.json     # Vercel static deployment config
└── README.md
```

## Implementation Roadmap

- **Phase 1** — Login, RBAC, project workspaces, Google Sheets integration, task tracking
- **Phase 2** — Attendance, leave management, break timers, data validation
- **Phase 3** — Productivity & quality reports, TAT tracking, automated notifications
- **Phase 4** — Advanced dashboards, report exports, audit logs, performance comparisons
