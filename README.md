# ESG Report Submission Tracker

A lightweight, single-file HTML dashboard for monitoring ESG (BRSR & GRI) report data submissions across client companies.

## Live Dashboard

**[View Dashboard](https://kabirsahakabir.github.io/Client-Dashboard/)**

## Features

- **Company-wise tracking** — browse all client companies from a sidebar and view submission progress per business unit
- **Status monitoring** — see pending, in-progress, and completed report submissions at a glance with color-coded status badges
- **Filter & search** — filter reports by status, search by title, and filter by assigned user within each company
- **User-level view** — select a specific user to see all their pending and completed items across business units
- **Company deadlines** — set and track a submission deadline per company with automatic overdue/upcoming alerts
- **Contact actions** — quick-access call and email buttons for assignees and reviewers
- **Fully self-contained** — no server, no dependencies. Just open the HTML file in any browser.

## How It Works

The dashboard is a single `index.html` file with all data, styles, and logic embedded. It runs entirely in the browser with no backend required.

## Usage

1. Open `deploy/index.html` in any modern browser
2. Select a company from the sidebar
3. Expand business units to view individual report submissions
4. Use filters and search to find specific reports or users

## Built With

- HTML / CSS / JavaScript (no frameworks)
- Data processed from source CSVs via Node.js build scripts
