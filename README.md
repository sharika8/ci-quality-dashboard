# 🔬 CI Quality Dashboard

A **zero-build, single-file** React dashboard that visualises GitHub Actions CI status across all your QA repositories — pass rates, job chips, and run trend sparkbars, auto-deployed to GitHub Pages.

[![Deploy](https://github.com/sharika8/ci-quality-dashboard/actions/workflows/deploy.yml/badge.svg)](https://github.com/sharika8/ci-quality-dashboard/actions/workflows/deploy.yml)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen)](https://sharika8.github.io/ci-quality-dashboard)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**[▶ Live Demo → sharika8.github.io/ci-quality-dashboard](https://sharika8.github.io/ci-quality-dashboard)**

---

## ✨ Features

| Feature | Detail |
|---|---|
| **Real-time CI status** | GitHub Actions status for all repos in your account |
| **Pass rate** | Colour-coded indicator (green / amber / red) |
| **Job chips** | ✅ ❌ 🔄 ⏭ per workflow job |
| **Trend sparkbars** | Last 8 runs visualised per repo |
| **Filters** | All / Passing / Failing / No CI |
| **Auto-deploy** | GitHub Pages on every push to main |
| **Zero build** | Vanilla React via CDN — no npm, no webpack |

---

## 🚀 Setup

1. Fork or clone this repo
2. Enable GitHub Pages: **Settings → Pages → Source: main branch**
3. Open the deployed URL
4. Enter your GitHub **username** and a **Personal Access Token** (public_repo scope)

Your credentials are saved to `localStorage` in your browser — never transmitted anywhere else.

---

## 💻 Local Development

No build step needed:

```bash
# Open directly in browser
open src/dashboard.html

# Or serve locally
python3 -m http.server 8080 --directory src
```

---

## 🔧 Tech Stack

| Layer | Choice |
|---|---|
| UI | Vanilla React 18 (UMD CDN) |
| Data | GitHub REST API v3 (client-side) |
| Hosting | GitHub Pages |
| Build | None — zero toolchain |

---

## 🔗 Related Repos

All QA portfolio repos are displayed in this dashboard:

| Repo | Stack |
|---|---|
| [enterprise-qa-framework](https://github.com/sharika8/enterprise-qa-framework) | Python + Playwright |
| [k6-performance-framework](https://github.com/sharika8/k6-performance-framework) | k6 JS |
| [playwright-typescript-framework](https://github.com/sharika8/playwright-typescript-framework) | Playwright + TypeScript |
| [snowflake-data-pipeline-tests](https://github.com/sharika8/snowflake-data-pipeline-tests) | Python + Snowflake |
| [ios-xcuitest-automation](https://github.com/sharika8/ios-xcuitest-automation) | Swift + XCUITest |
| [android-espresso-automation](https://github.com/sharika8/android-espresso-automation) | Kotlin + Espresso |

---

## 📜 Licence
MIT