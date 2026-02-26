# GitHub Atlas

> *In Greek mythology, Atlas holds up the sky — giving others a clear view of the world below.*

**Interactive maps for GitHub's ecosystem. Three tools, one mission.**

[![MIT License](https://img.shields.io/badge/license-MIT-6e4f84.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/live-GitHub%20Pages-4d807f.svg)](https://blackmath88.github.io/github-atlas/)
[![Client-side only](https://img.shields.io/badge/client--side-only-cab1df.svg)](#)

![GitHub Atlas preview](preview.png)

---

## The Problem

GitHub has evolved from a developer tool into public infrastructure. But its interface was built for developers — not for the new wave of users arriving from YouTube, LinkedIn, and ChatGPT who need to navigate it without understanding repository conventions.

GitHub's chaos isn't the problem. **Not having a map is.**

---

## The Three Tools

### 🧭 Navigator — Find the Right AI/LLM Tool in 30 Seconds
For AI researchers, prompt engineers, developers new to LLMs, and curious beginners.

- Search any GitHub topic — live results as a force-directed graph
- 20 hand-curated repositories across 10 intent clusters
- Four personas: Explorer, Builder, Prompt Engineer, Org Lead
- Trust levels: Official, Community, Sensitive
- 🌲 Dark Forest mode (hides leaked system prompts by default)
- Drill inside repos — navigate README structure as an interactive map
- Persona-specific guidance: difficulty level, how to get started

**[→ Open Navigator](https://blackmath88.github.io/github-atlas/navigator.html)**

---

### 📡 Radar — Risk & Ecosystem Health Analysis
For architects, org leads, security audits, and investment decisions.

- Four analytical lenses: Architecture Review, Org Map, Ecosystem Health, Due Diligence
- Single-maintainer risk detection
- Burnout signal identification
- Bridge engineer detection (contributors active across 3+ repos)
- Health scoring 0–100
- Drill inside repos — navigate README structure as an interactive map

**[→ Open Radar](https://blackmath88.github.io/github-atlas/radar.html)**

---

### 🏢 Hub — Map Your Org, Share With Your Community
For framework maintainers, open-source orgs, and teams managing multiple projects.

- Real GitHub API integration — search any org or user
- Three view modes: by topic, by language, by activity
- Repository health scoring
- Auto-generate embeddable iframe code
- URL params (`?org=yourorg`) for direct linking
- Drill inside repos — navigate README structure as an interactive map

**[→ Open Hub](https://blackmath88.github.io/github-atlas/hub.html)**

---

## Features

- **100% client-side** — no backend, no tracking, no data collection
- **GitHub API optional** — demo data included, token unlocks higher rate limits (60 → 5,000 req/hr)
- **MIT licensed** — fork it, customize it, embed it
- **D3.js v7** force-directed graphs throughout
- **Single HTML files** — works on GitHub Pages, any static host, or locally
- **Embeddable** — Hub generates iframe code for READMEs and GitHub Pages

## Tech Stack

| Layer | Choice |
|---|---|
| Visualization | D3.js v7 |
| Data | GitHub REST API |
| Fonts | Plus Jakarta Sans · JetBrains Mono |
| Build | None — static HTML |
| Hosting | GitHub Pages |

---

## Running Locally

No build step needed. Just open any file in a browser:

```bash
git clone https://github.com/blackmath88/github-atlas
cd github-atlas
open index.html   # or double-click any .html file
```

For GitHub API calls beyond 60 req/hr, add a personal access token in the tool's token field. Read-only, public scopes only — no write permissions needed.

---

## Project Status

**Live as of February 2026.**

| Item | Status |
|---|---|
| index.html (landing page) | ✅ Live |
| navigator.html | ✅ Live |
| radar.html | ✅ Live |
| hub.html | ✅ Live |
| GitHub Pages | ✅ [blackmath88.github.io/github-atlas](https://blackmath88.github.io/github-atlas/) |
| Social preview (og:image) | ✅ preview.png uploaded |
| README | ✅ This document |
| CONTRIBUTING.md | ✅ [See contribution guide](CONTRIBUTING.md) |
| docs/getting-started.md | ✅ [Getting started guide](docs/getting-started.md) |
| License | ✅ MIT |

---

## Roadmap

Ideas under consideration — contributions welcome:

- **Navigator:** Additional curated repositories; domain-specific maps (ML infra, web3, devtools, design systems)
- **Radar:** New analytical lenses for specific decision types; deeper contributor graph analysis
- **Hub:** New view modes beyond topic/language/activity; enhanced embed parameters
- **All tools:** Keyboard navigation improvements; accessibility pass

The project is intentionally minimal. New features only ship if they make GitHub more navigable without adding complexity or dependencies.

---

## Philosophy

Atlas is a translation layer — not a search engine, not a dashboard, not a metrics tool.

The goal is to take what GitHub contains and make it navigable terrain for people who don't already know the layout. That means maps over lists, signal over noise, and privacy by default.

Three constraints define the project and are never negotiable:

1. **Client-side only.** No server, no tracking, no data leaving the browser.
2. **No build step.** Open the file. It works. That's the whole deployment model.
3. **Built to be forked.** Low lock-in by design. If you want a domain-specific version for your community, the architecture gets out of your way.

---

## Contributing

Contributions welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for full guidelines.

Ideas especially welcome for:
- Additional curated repositories in Navigator
- New analytical lenses in Radar
- Domain-specific Atlas forks (ML infra, web3, devtools, etc.)

---

## License

[MIT](LICENSE) — use it, fork it, build on it.

---

## Created by

**Achim Imboden** · [@blackmath88](https://github.com/blackmath88)

*AI Readiness Architect · University of Basel*

---

*Maps are more useful than lists. Community over solo. Signal over noise.*
