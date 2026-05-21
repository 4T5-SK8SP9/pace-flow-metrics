# PACE Flow Metrics Report Builder

A browser-based tool for Scrum Masters and Delivery Managers at Pandora to upload their Jira CSV export, select flow and quality metrics, and generate a stakeholder-ready report.

Built by **Pandora PACE — Digital & Technology**.

---

## Live tool

👉 **[Open the tool](https://YOUR-USERNAME.github.io/pace-flow-metrics)**

> Replace `YOUR-USERNAME` with your GitHub username once deployed.

---

## What it does

- **Drag & drop** your Jira CSV export directly into the tool
- Automatically calculates: Cycle Time, Throughput, WIP, Lead Time, PERT Forecast, Defect Ratio, and more
- **Select which metrics** to include in the report
- Live **chart previews** for each metric
- **AI-generated coaching summary** based on your data
- Download a **CSV summary** of all calculated metrics

---

## How to use

1. Go to your Jira board
2. Click **···** (top right) → **Export** → **CSV (all fields)**
3. Open the tool and drag your CSV into the upload zone
4. Fill in team name and period
5. Select the metrics you want
6. Click **Generate Report**

---

## Deploy to GitHub Pages (10 minutes)

1. Create a new repository on [github.com](https://github.com/new)
   - Name it `pace-flow-metrics` (or anything you like)
   - Set it to **Public**

2. Upload both files:
   - `index.html`
   - `README.md`

3. Go to **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)**
   - Click **Save**

4. Wait ~2 minutes, then your URL will be:
   ```
   https://YOUR-USERNAME.github.io/pace-flow-metrics
   ```

5. Share the URL with your SMs and DMs — no login required.

---

## Metrics supported

### Flow metrics
| Metric | Description |
|--------|-------------|
| Cycle Time | Average days from work start to done |
| Throughput | Items completed per week |
| WIP Status | Work in progress by column |
| Lead Time | Total time from created to done (P50 / P85) |
| Yesterday's Weather | PERT-based delivery forecast |
| Created vs Resolved | Demand vs delivery trend |

### Quality & testing metrics
| Metric | Description |
|--------|-------------|
| Defect Ratio | Bugs vs stories completed per period |
| Defect Escape Rate | Bugs found after stories marked Done |
| Average Age of Bugs | Days open bugs have existed |
| WIP Age | How long active items have been in progress |

---

## Tech stack

Pure HTML + CSS + JavaScript. No build step, no dependencies to install.

Libraries loaded from CDN:
- [PapaParse](https://www.papaparse.com/) — CSV parsing
- [Chart.js](https://www.chartjs.org/) — Charts
- [Google Fonts](https://fonts.google.com/) — DM Sans + DM Serif Display

---

## Roadmap

- [ ] Direct PowerPoint (.pptx) export from the browser
- [ ] PDF export
- [ ] Save report configuration (team name, metric selection)
- [ ] Multi-team comparison view
- [ ] Sprint-level filtering

---

## Contributing

This tool is maintained by the PACE team. To suggest improvements or report issues, contact your PACE Delivery Lead.

---

*Pandora A/S · PACE — Agile Center of Excellence · Digital & Technology*
