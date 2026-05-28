# 🔬 CI Quality Dashboard

A **zero-build, single-file** GitHub Actions CI status dashboard — see pass rates, job statuses and trends across all your QA repos at a glance.

**[Live Demo → sharika8.github.io/ci-quality-dashboard](https://sharika8.github.io/ci-quality-dashboard)**

## Features
- Real-time GitHub Actions status for all repos
- Pass rate with colour indicators (green/amber/red)
- Per-job chips (✅ ❌ 🔄 ⏭) for each workflow
- Run trend sparkbars — last 8 runs per repo
- Filter: All / Passing / Failing / No CI
- Zero build step — vanilla React via CDN

## Setup
1. Fork/clone this repo and enable GitHub Pages (Settings → Pages → main branch)
2. Open the deployed URL and enter your GitHub username + a PAT with `public_repo` scope
3. Your credentials are saved to localStorage — never sent anywhere else

## Local Dev
```bash
open src/dashboard.html
```

## Licence
MIT
