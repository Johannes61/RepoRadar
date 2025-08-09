# RepoRadar — Frontend‑only GitHub Dashboard

RepoRadar is a lightweight, **HTML/CSS/JavaScript** dashboard that lets you track GitHub repositories without any backend. All data is fetched directly from the GitHub API and stored locally in your browser.

## Features
- **Browse by Username** — Enter a GitHub username and pick repositories from a list.
- **No Backend** — Data is fetched client‑side via the GitHub API.
- **Local Storage** — All settings, tokens, and tracked repos stay in your browser.
- **GitHub Token Support** — Optional Personal Access Token for higher rate limits.
- **Repo Cards** — Show stars, forks, open PRs, open issues, and last updated time.
- **Commit Activity Charts** — Visualize commit history for the last 14–90 days.
- **Pin/Unpin Repos** — Keep important repos at the top.
- **Details Modal** — Quick access to releases, pull requests, and full repo page.
- **Export/Import Profile** — Backup or share your configuration.
- **Dark UI** — Modern, responsive, and clean.

## How to Use
1. Open `index.html` in your browser.
2. Enter a GitHub username.
3. Click **Browse Repos** to see available repositories.
4. Click **Add** next to a repository to track it.
5. Use the **Settings** panel to add a GitHub token if needed.

## Technologies
- HTML5
- CSS3 (custom dark theme)
- JavaScript (Vanilla)
- [Chart.js](https://www.chartjs.org/) for commit graphs
- GitHub REST API v3

## License
MIT License
