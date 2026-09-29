# Mayank Jain

<img src="https://github.com/mayankjain1815-commits.png" width="128" height="128" align="right" alt="">

2nd Year EEE student in Bangalore. Backend & data analytics.
Most of my public work is TypeScript.

Every badge below is a **live** [shields.io](https://shields.io) endpoint that queries
GitHub when the image is rendered — none of them are values I typed in. The one dated
table is labelled as such, with the exact command to reproduce it.

## Live status — `mayankjain1815-commits/OmniRoute`

![CI](https://img.shields.io/github/actions/workflow/status/mayankjain1815-commits/OmniRoute/ci.yml?label=CI) ![Semgrep](https://img.shields.io/github/actions/workflow/status/mayankjain1815-commits/OmniRoute/semgrep.yml?label=Semgrep) ![DAST](https://img.shields.io/github/actions/workflow/status/mayankjain1815-commits/OmniRoute/dast-smoke.yml?label=DAST) ![Last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/OmniRoute?label=last%20commit) ![Commit activity](https://img.shields.io/github/commit-activity/m/mayankjain1815-commits/OmniRoute?label=commits/mo) ![Contributors](https://img.shields.io/github/contributors/mayankjain1815-commits/OmniRoute?label=contributors) ![License](https://img.shields.io/github/license/mayankjain1815-commits/OmniRoute?label=license) ![Open issues](https://img.shields.io/github/issues/mayankjain1815-commits/OmniRoute?label=open%20issues) ![Repo size](https://img.shields.io/github/repo-size/mayankjain1815-commits/OmniRoute?label=size) ![Top language](https://img.shields.io/github/languages/top/mayankjain1815-commits/OmniRoute?label=main%20language)

## OmniRoute

**[OmniRoute](https://github.com/mayankjain1815-commits/OmniRoute)** — a unified AI proxy/router: one endpoint,
291 LLM providers, automatic fallback. TypeScript, MIT-licensed.

![CI](https://img.shields.io/github/actions/workflow/status/mayankjain1815-commits/OmniRoute/ci.yml?label=CI) ![Last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/OmniRoute?label=last%20commit) ![Open issues](https://img.shields.io/github/issues/mayankjain1815-commits/OmniRoute?label=open%20issues) ![Contributors](https://img.shields.io/github/contributors/mayankjain1815-commits/OmniRoute?label=contributors) ![License](https://img.shields.io/github/license/mayankjain1815-commits/OmniRoute?label=license)

## Languages across all public repositories

Measured from the GitHub languages API across all 18 non-fork,
non-archived public repositories (186,875,056 source bytes).
Shares are by bytes, not by file or line count.

| Language | Share | Bytes | |
|----------|------:|------:|:-|
| ![TypeScript](https://img.shields.io/badge/TypeScript-%233178c6.svg?style=flat-square) | 85.0% | 158,904,122 | `█████████████████████····` |
| ![Vue](https://img.shields.io/badge/Vue-%2341b883.svg?style=flat-square) | 4.2% | 7,860,340 | `█························` |
| ![JavaScript](https://img.shields.io/badge/JavaScript-%23f1e05a.svg?style=flat-square) | 3.4% | 6,266,659 | `█························` |
| ![Python](https://img.shields.io/badge/Python-%233572A5.svg?style=flat-square) | 3.1% | 5,829,544 | `█························` |
| ![HTML](https://img.shields.io/badge/HTML-%23e34c26.svg?style=flat-square) | 2.7% | 4,982,070 | `█························` |
| ![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-%23DA5B0B.svg?style=flat-square) | 1.0% | 1,840,229 | `█························` |
| ![SCSS](https://img.shields.io/badge/SCSS-%23c6538c.svg?style=flat-square) | 0.2% | 368,150 | `█························` |
| ![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=flat-square) | 0.2% | 347,015 | `█························` |

Reproduce it:

```sh
gh api graphql -f query='{ user(login: "mayankjain1815-commits") { repositories(first: 100, privacy: PUBLIC, ownerAffiliations: OWNER, isFork: false) { nodes { isArchived languages(first: 100, orderBy: {field: SIZE, direction: DESC}) { edges { size node { name } } } } } } }' \
  --jq '[.data.user.repositories.nodes[]
          | select(.isArchived | not)
          | .languages.edges[] | {name: .node.name, size: .size}]
         | group_by(.name)
         | map({name: .[0].name, bytes: (map(.size) | add)})
         | sort_by(-.bytes)'
```

## Measured snapshot

Taken 2026-09-26 from the GitHub REST/GraphQL APIs. Unlike the badges, these
are point-in-time and will drift.

| Metric | Value |
|--------|-------|
| Public repositories | 18 non-fork, non-archived |
| Languages present | 25 |
| Source size measured | 186,875,056 bytes |
| Merged PRs into OmniRoute | 6 |
| Stars across all repositories | 0 |

## All public repositories

| Repository | Primary language | Last commit |
|------------|------------------|-------------|
| [`Agent-Memory-Guard`](https://github.com/mayankjain1815-commits/Agent-Memory-Guard) | `Python` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/Agent-Memory-Guard?label=commit) |
| [`Agent-Wallet-SDK`](https://github.com/mayankjain1815-commits/Agent-Wallet-SDK) | `TypeScript` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/Agent-Wallet-SDK?label=commit) |
| [`AI-Slop-Detector`](https://github.com/mayankjain1815-commits/AI-Slop-Detector) | `Python` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/AI-Slop-Detector?label=commit) |
| [`AI-Trading-Bot`](https://github.com/mayankjain1815-commits/AI-Trading-Bot) | `HTML` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/AI-Trading-Bot?label=commit) |
| [`CITADEL`](https://github.com/mayankjain1815-commits/CITADEL) | `JavaScript` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/CITADEL?label=commit) |
| [`Doclify`](https://github.com/mayankjain1815-commits/Doclify) | `Python` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/Doclify?label=commit) |
| [`Feature-Engine`](https://github.com/mayankjain1815-commits/Feature-Engine) | `Python` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/Feature-Engine?label=commit) |
| [`Marketinsight`](https://github.com/mayankjain1815-commits/Marketinsight) | `Python` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/Marketinsight?label=commit) |
| [`mayankjain1815-commits`](https://github.com/mayankjain1815-commits/mayankjain1815-commits) | — | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/mayankjain1815-commits?label=commit) |
| [`MirrorGPT`](https://github.com/mayankjain1815-commits/MirrorGPT) | `Python` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/MirrorGPT?label=commit) |
| [`Movie-Recommendation-System`](https://github.com/mayankjain1815-commits/Movie-Recommendation-System) | `Jupyter Notebook` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/Movie-Recommendation-System?label=commit) |
| [`n8n`](https://github.com/mayankjain1815-commits/n8n) | `TypeScript` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/n8n?label=commit) |
| [`Next-Role`](https://github.com/mayankjain1815-commits/Next-Role) | `Python` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/Next-Role?label=commit) |
| [`OmniRoute`](https://github.com/mayankjain1815-commits/OmniRoute) | `TypeScript` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/OmniRoute?label=commit) |
| [`ShoppingGPT`](https://github.com/mayankjain1815-commits/ShoppingGPT) | `HTML` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/ShoppingGPT?label=commit) |
| [`strix`](https://github.com/mayankjain1815-commits/strix) | `Python` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/strix?label=commit) |
| [`Synapse`](https://github.com/mayankjain1815-commits/Synapse) | `Python` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/Synapse?label=commit) |
| [`TrustBoost-PII-Sanitizer`](https://github.com/mayankjain1815-commits/TrustBoost-PII-Sanitizer) | `HTML` | ![last commit](https://img.shields.io/github/last-commit/mayankjain1815-commits/TrustBoost-PII-Sanitizer?label=commit) |

## How to read these badges

- **CI**, **Semgrep** and **DAST** track the most recent completed run on the
  **default branch** (`main`) — they describe `main`, not a pull request. All
  three use `github/actions/workflow/status`, which reads the latest completed
  run; the older `github/workflow/status` endpoint is broken upstream and is not
  used here.
- **Last commit**, **commit activity**, **open issues**, **contributors**,
  **license**, **repo size**, **top language** and every per-repository badge are
  queried from GitHub each time the image is fetched, so they stay current on
  their own with no action from me.
- Workflows that have never completed a run on the default branch are **omitted**
  rather than shown as "no status", which would misrepresent them.
- Star and fork badges are omitted on purpose: every repository here has 0 of
  each, so the badge would add noise and imply activity that is not there.

## License

[MIT](LICENSE) — see the file for the full text.
