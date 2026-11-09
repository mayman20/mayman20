# Joe May

I build data pipelines, backend services and web apps in Python and TypeScript. BS in Computer Science from the University of Rhode Island (May 2026) with a data science minor. Based in Stone Harbor, NJ, and open to remote work or relocating.

## Featured projects

| Project | What it is | Try it |
|---|---|---|
| [captain-mikes-charters](https://github.com/mayman20/captain-mikes-charters) | Website for a working charter fishing business, built for a real client. React, TypeScript and Vite, with 51 tests in CI. The earlier self-hosted booking platform is preserved at [`booking-platform-v1`](https://github.com/mayman20/captain-mikes-charters/tree/booking-platform-v1). It used Supabase, database-level double-booking protection and row-level security. | [Live site](https://pushinglimitssportfishing.com/) |
| [financial-data-platform](https://github.com/mayman20/financial-data-platform) | Installable Python research pipeline. Data is ingested and stored in SQLite, then run through research flows. Statistical validation gates (sign randomization, deflated Sharpe, bootstrap) produce a static report. One command runs it offline, with 85 tests in CI. On synthetic controls it passes 0 of 20 pure-noise runs. | [Demo report](https://mayman20.github.io/demos/financial-data-platform/) |
| [spotify-playlist-tools](https://github.com/mayman20/spotify-playlist-tools) | Spotify automation scripts plus a FastAPI backend (OAuth, SQLite or Postgres) and a React dashboard. | [UI preview](https://mayman20.github.io/spotify-playlist-tools/) |
| [Delivery-Tracker](https://github.com/mayman20/Delivery-Tracker) | Driver and dispatcher dashboards on Firebase Auth and Realtime Database. Includes a no-account demo with simulated routes. | [Demo](https://mayman20.github.io/Delivery-Tracker/demo.html) |

## Open source

- [instaloader #2712](https://github.com/instaloader/instaloader/pull/2712), merged July 2026. Caption mentions after a line break were silently dropped. I traced it to a 2022 regex change, fixed it, and added a regression test.
- [spotDL #2751](https://github.com/spotDL/spotify-downloader/pull/2751), merged October 2026. Windows playlist paths ending in a backslash produced hidden `.m3u8` files. I fixed the string-literal check and added a regression test.

## Experience

**Long Point Resources, software engineering intern (summer 2025).** Built a 12-table Power BI model covering about 520 companies on an existing MySQL financial warehouse, using SQL, Jupyter and DAX.

## Stack

| Area | Tools |
|---|---|
| Languages | Python, SQL, TypeScript, C++, C#, R |
| Python and data | pandas, NumPy, FastAPI, pytest |
| Databases | PostgreSQL, MySQL, SQLite |
| Web | React, Vite, Firebase, Supabase |
| Infrastructure | Linux, systemd, GCP, Docker, GitHub Actions |

---

[mayman20.github.io](https://mayman20.github.io) · [LinkedIn](https://linkedin.com/in/joe-may-499a40369) · jmayman2002@gmail.com

I use AI coding tools (Claude and ChatGPT) as development aids. Each project's README notes where.
