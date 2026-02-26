# Contributing to GitHub Atlas

> *Atlas holds up the sky so others get a clear view.*

**Navigate What You Build**

GitHub's chaos isn't the problem. **Not having a map is.**

Atlas is a translation layer between what people want to accomplish and what GitHub contains. It turns a repository host into navigable terrain — for architects making dependency decisions, for newcomers finding their first LLM tool, for maintainers trying to explain their ecosystem to others.

That work is better done by many cartographers than one.

Contributions are welcome at every level — curation, analysis, interface, and philosophy. Atlas is intentionally a **three-headed tool**, and you can sharpen any one of the three heads. Community over solo is one of the project's core commitments.

---

## 🗺️ Ways to Contribute

### 🧭 Navigator curation

Navigator is a hand-curated map of LLM repositories, not a scraped list. Quality over quantity — every entry is a deliberate recommendation.

To add or update a repository, submit a PR editing `navigator.html` with the following metadata for each entry:

| Field | Description |
|---|---|
| `name` | Short display name |
| `url` | Full GitHub URL |
| `description` | One sentence, written for the intended persona |
| `persona(s)` | One or more of: `Explorer`, `Builder`, `Prompt Engineer`, `Org Lead` |
| `intent cluster` | The use-case group it belongs to |
| `trust` | `Official`, `Community`, or `Sensitive` |

**Dark Forest mode responsibility:** If a repository contains leaked system prompts, internal tool instructions, or any content that was not intentionally published for public use, it **must** be marked `Sensitive`. Sensitive entries are hidden by default behind Dark Forest mode — this is a privacy-first project, and that filter exists for a reason. Do not add sensitive repositories without this designation.

Your PR should explain: why the repo was chosen, which persona(s) it serves, and why it deserves the trust level you assigned.

---

### 📡 Radar lenses

Radar currently ships four analytical lenses: **Architecture Review**, **Org Map**, **Ecosystem Health**, and **Due Diligence**. New lenses are welcome — but a lens is only useful if it enables a specific decision.

Before building a new lens, write its user story:

- Who needs this? (role, context)
- What are they trying to decide?
- What signals does the lens surface?
- Why can't they get that from the existing four?

Your PR should include the user story, the signals used, and what decision the lens enables. Lenses that add noise without enabling action won't be merged.

---

### 🏢 Hub improvements

Hub maps an organization's repositories into a navigable view and generates embeddable output. Contributions here include:

- New view modes (beyond topic / language / activity)
- Embed enhancements (new iframe parameters, layout options)
- URL param features (`?org=`, `?view=`, etc.)
- UX improvements to the org search or health scoring

Hub is the most embeddable of the three tools — improvements here have the widest surface area.

---

### 🐛 Bug reports

File a GitHub Issue. Include:

- What you expected to happen
- What actually happened
- Which tool (Navigator / Radar / Hub)
- Browser and version
- Any console errors (open DevTools → Console)

---

### 💡 Feature suggestions

File a GitHub Issue. Frame it as a user problem, not a feature request:

- Who has this problem?
- What are they trying to accomplish?
- Why does it fit Atlas's mission of making GitHub navigable?

Features that make GitHub more navigable for non-developers are especially welcome.

---

### 🍴 Forks and domains

Atlas was built to be forked. A domain-specific Navigator for ML infrastructure, web3 tooling, design systems, or any other ecosystem is a legitimate and encouraged use of this project.

Single HTML files mean low lock-in by design — you can fork one tool, customize it for your community, and host it anywhere with no build pipeline. If you build a domain fork, open an issue to let us know — we may link to it from the main project.

---

## 🎨 Design System

Required reading for any HTML or CSS change.

Atlas has a fixed visual identity. All UI contributions must respect it.

### Color tokens

All colors are defined as CSS custom properties in `:root`. **Never hardcode a hex value outside of `:root`.**

| Token | Value |
|---|---|
| `--purple` | `#6e4f84` |
| `--purple-mid` | `#8b6aa0` |
| `--lavender` | `#cab1df` |
| `--lav-dim` | `#9d84b8` |
| `--teal` | `#4d807f` |
| `--teal-hi` | `#6aa8a7` |
| `--near-white` | `#f7f1fb` |
| `--charcoal` | `#444444` |
| `--bg` | `#080610` |

### Typography

- **Headings + body:** Plus Jakarta Sans (weights: 400, 500, 600, 700, 800)
- **Monospace / labels:** JetBrains Mono (weights: 300, 400, 500, 600)

### Layout rules

- Border radius: `14px` cards · `10px` why-cards · `6px` buttons
- Base padding: `28px`
- Responsive breakpoints at `900px` and `600px`

### Tool color identities

Each tool has a color identity — don't mix them:

| Tool | Identity |
|---|---|
| Navigator | purple |
| Radar | teal |
| Hub | mint (`#2dd4a0`) |

### Zero-dependency rule

No external CSS frameworks. No Bootstrap, no Tailwind, no utility libraries. The entire visual system lives in the `:root` block of each file. Keep it that way.

---

## 🛠️ Tech Stack Constraints

Atlas is intentionally minimal. These constraints are not accidental — they are what makes it forkable, embeddable, and dependency-free.

- **Single HTML files** — one file per tool, everything inline (HTML + CSS + JS in one file)
- **No npm, no build step, no bundler** — open the file in a browser and it works
- **D3.js v7** for all visualizations, loaded from CDN
- **GitHub REST API** — read-only public scopes only. Personal access tokens are entered by users in the UI and never leave the browser. There is no server.
- **Zero analytics, zero tracking** — no cookies, no beacons, no third-party calls beyond the GitHub API and CDN fonts. This is a privacy-first project.

If a contribution requires npm, a build step, or any form of server-side processing, it won't be merged. The constraints are the feature.

---

## 🔀 PR Process

1. Fork the repo
2. Make your changes in a feature branch
3. Open a PR with a clear description of:
   - What changed
   - Which tool it affects (Navigator / Radar / Hub / all)
   - Why it fits Atlas's mission

**For Navigator curation PRs**, also include: why the repo was chosen, which persona(s) it serves, trust level and justification.

**For Radar lens PRs**, also include: user story, signals used, decision enabled.

Keep PRs focused. One change per PR is preferred — a Navigator curation addition and a Hub layout change belong in separate PRs.

The codebase has no automated test suite. Manual verification in-browser is expected before opening a PR. Test in at least one modern browser and check the browser console for errors.

---

## 🤝 Code of Conduct

- Be direct but respectful
- Critique ideas, not people
- Atlas is a map — contributors are cartographers. Every map reflects choices about what to include, what to highlight, and what to leave out. Defend your choices clearly, and be open to having them questioned.

---

## 🧭 Philosophy Alignment Check

Before submitting, ask yourself:

- Does this make GitHub **more navigable** for someone who isn't a developer?
- Does it add **signal** or **noise**?
- Does it respect **privacy** — client-side only, no tracking?
- Is it **maps-first** or lists-first? (Maps win.)
- Would a **fork** of this be easy to maintain after your change?

If you can answer these questions clearly, you're probably building something that belongs here.

---

*GitHub Atlas is built and maintained by [@blackmath88](https://github.com/blackmath88). MIT licensed — use it, fork it, build on it.*
