# Joe May

BS Computer Science, University of Rhode Island (2026), with a minor in Data Science. Based in Stone Harbor, NJ.

## What I build

Data systems and web apps. Some of this work lives in private repos. Short version:

**Research and paper-trading work (historical).** Work spanning market-data ingestion, out-of-sample splits, permutation tests, negative controls, structured logging, and service monitoring. A public case study with the architecture notes and validation module is linked below; it is not a currently running service.

**Recent learning: small ML experiments (October 2026).** NumPy text classifiers on public financial text. Sentence sentiment worked reasonably well; predicting later-session open-to-close price moves from headlines did not beat a simple baseline. The full results are in [ml-experiments](https://github.com/mayman20/financial-data-platform/tree/main/ml-experiments).

**Browser-automation pipeline on Claude Code.** Playwright + Claude subprocess orchestration with LLM scoring, state machines, daily cap enforcement, and Telegram control. Built as a stress test for agent orchestration under real-world failure modes.

**Power BI modeling at Long Point Resources (Summer 2025 SWE internship).** Built a 12-table Power BI model covering about 520 companies on top of an existing MySQL financial warehouse, using SQL, Jupyter, and DAX.

## Stack

Python (pandas, NumPy, FastAPI), SQL (PostgreSQL, MySQL), TypeScript, React, C++, C#, R. GCP, Linux, systemd, Docker, REST APIs. Playwright for browser automation. Firebase and Supabase on the full-stack side.

## Public projects

### [captain-mikes-charters](https://github.com/mayman20/captain-mikes-charters)
React + TypeScript + Vite. Booking site for a working charter fishing business, built for a real client. [Visit the live site](https://pushinglimitssportfishing.com/). Currently a static site backed by a FishingBooker embed for live availability and payment; an earlier self-hosted booking platform (Supabase, database-level double-booking protection, RLS-scoped access control, automated confirmation emails) is preserved in the repo history for anyone who wants to see that version.

### [Delivery-Tracker](https://github.com/mayman20/Delivery-Tracker)
JavaScript + Firebase Auth + Realtime Database. Delivery status tracking with role-based dashboards for drivers and dispatchers. [Try the no-account interactive demo](https://mayman20.github.io/Delivery-Tracker/demo.html) with simulated drivers and routes.

### [financial-data-platform](https://github.com/mayman20/financial-data-platform)
Python. Financial data research case study: architecture notes from historical research and paper-trading work, a statistical validation module (sign-randomization tests, bootstrap distributions, deflated Sharpe, rolling splits) with an offline synthetic example, and sanitized configuration. Not a currently running service; account-connected code and trading journals stay private. Also home to the [ml-experiments](https://github.com/mayman20/financial-data-platform/tree/main/ml-experiments) folder described above.

## AI assistance

I use AI tools, mainly Claude and ChatGPT, as development aids. The financial-data-platform and captain-mikes-charters READMEs note where they were used.

## Reach me

jmayman2002@gmail.com  ·  [LinkedIn](https://linkedin.com/in/joe-may-499a40369)  ·  [mayman20.github.io](https://mayman20.github.io)
