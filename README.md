# Job Tracker — Federica

A mobile-first PWA for tracking job opportunities in **developmental neuropsychology** (neuropsicologia dello sviluppo) across the Milan/Monza-Brianza area and surroundings.

Built for personal use — no server, no login, no internet connection needed after the first load.

---

## What it does

- Tracks **67 structures** (private clinics, IRCCS, ASST hospitals, cooperatives, universities) across 7 provinces: MI, MB, LC, CO, BG, PV, LO
- Filter by structure type, position type, province, distance from Monza, and application status
- Mark each opportunity with a personal status: *to apply*, *applied*, *reply received*, *interview*, *rejected*
- Add personal notes per structure
- Export/import progress as JSON — so you can reload your statuses when the app is updated with new data
- Works offline as a PWA — installable on iPhone/iPad home screen

## Tech

Pure HTML + Vanilla JS, no dependencies. Data stored locally via **IndexedDB**. Service worker for offline support.

## Live app

[https://rcarloni93.github.io/jobtracker/](https://rcarloni93.github.io/jobtracker/)
