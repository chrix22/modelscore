# ModelScore — LLM Benchmark Tracker

A self-contained, single-file HTML dashboard tracking frontier LLMs across performance benchmarks, pricing, open/proprietary status, lab transparency & environmental disclosure, EU AI Act systemic-risk presumption, and real-world corporate/developer adoption.

No build step, no dependencies, no external assets. Open `index.html` directly in a browser, or serve it as a static site (GitHub Pages works out of the box — see below).

## What's inside

- **Overview** — stat tiles, an Artificial Analysis Intelligence Index leaderboard chart, a computed "best value" (intelligence-per-dollar) ranking, an efficient-frontier (Pareto) scatter chart, and week-over-week tracking history.
- **Model Comparison** — a sortable, filterable table (14 metrics per model: index score, Arena Elo, SWE-bench Verified, GPQA, speed, context, pricing, cost/task, enterprise spend share, release date) plus a two-model side-by-side comparison tool and CSV export.
- **Recent Releases** — a timeline of models released in the last 8 weeks.
- **Governance & Environment** — per-lab transparency (Stanford FMTI), environmental rating (SINK Project), and EU AI Act Article 51 systemic-risk presumption.
- **Corporate Adoption** — Ramp AI Index business-adoption figures and OpenRouter developer usage rankings.
- **Methodology & Sources** — every disagreement between trackers, every coverage gap, and a link to every source actually used. Nothing on this dashboard is a number we couldn't trace back to a real, cited source.

## Updating it

This dashboard is refreshed weekly by an automated routine that re-fetches each source, rebuilds `index.html`, and (when this repo is connected) should push the new version here. Until that push path is wired up, refreshed copies are delivered by hand.

## Enabling GitHub Pages (optional)

Settings → Pages → Deploy from branch → `main` / root. The dashboard will then be live at `https://chrix22.github.io/modelscore/`.

## Data integrity notes

Every figure on the dashboard is sourced and cited (see the Methodology & Sources tab). Where trackers disagree or data is missing, the dashboard says so explicitly rather than averaging or guessing — see the caveats list before quoting any number from this project elsewhere.
