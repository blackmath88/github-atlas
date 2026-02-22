# 🌍 GitHub Atlas

**Three Heads. One Mission. Carry Less Weight.**

---

## The Myth

In ancient mythology, Atlas carried the weight of the world on his shoulders — a burden too great for any single person.

GitHub is the same.

Millions of repositories. Thousands of developers. Knowledge scattered across continents. Dependencies that would collapse if anyone dropped the ball. Single-maintainer projects holding up entire ecosystems.

The chaos is real. The weight is real.

**But you don't have to carry it blind. And you don't have to carry it alone.**

---

## Meet the Three Heads: Your Guides

Atlas needed help. So does anyone trying to navigate GitHub. That's why Atlas has three heads — three specialized guides, each for a different journey:

### 🚀 **Head One: The Launchpad**

**For beginners exploring a new ecosystem.**

You don't need to understand architecture. You don't want to spend hours researching. You just need:
- The best tools for what you're trying to do
- Proof they're actually maintained
- How to get started in 30 seconds
- Nothing more. Nothing less.

Launchpad shows you the straight path through the chaos. No distractions. No overthinking.

→ **[Try Launchpad](launchpad.html)** or explore a sample ecosystem

**Who it's for:** AI researchers exploring prompt libraries, developers new to a framework, anyone who just wants to start building.

---

### 🔍 **Head Two: The Navigator**

**For architects, leads, and risk assessors.**

You're not just exploring. You're *betting* on this ecosystem. You need to see:
- The full structure (all repos, all connections)
- Who maintains what (and who's carrying too much)
- Single-maintainer risks (before they become problems)
- Bridge engineers (people holding everything together)
- Activity patterns (is this alive or maintained?)

Navigator shows you the *real* health of an ecosystem — not stars and forks, but signal.

→ **[Launch Navigator](navigator.html)** now (includes sample data)

**What you see:**
- Repos colored by maintenance health (red=risk, gray=stale, blue=healthy)
- Contributors sized by knowledge load
- Risk signals that light up red
- Four analytical lenses (Architecture, Org Mapping, Health, Due Diligence)
- All in one interactive graph

**Who it's for:** Architects evaluating frameworks, org leads inheriting codebases, investment teams assessing risk, anyone who needs to understand what they're standing on.

**Real examples:**
- "This repo has 1 maintainer. If they leave, it dies."
- "These 3 people span 20+ repos. They're bottlenecks."
- "This ecosystem has a healthy bus factor — good distribution."

---

### 🏢 **Head Three: The Hub**

**For maintainers who want to help their communities navigate.**

You maintain an organization or framework. You want your users to *see* your ecosystem instead of reading about it.

Instead of a README that's 10,000 words, embed an interactive map. Your users navigate it. They understand it. They get oriented.

→ **[Setup Hub](docs/hub-guide.md)** in your project

**What it does:**
- Embed in your GitHub Pages or README
- Show all your repos at a glance
- Help users understand what you maintain
- Reduce support burden ("just click the map")
- Look impressive

**Who it's for:** Framework maintainers, open-source orgs, teams managing multiple projects, anyone who wants to showcase their ecosystem professionally.

---

## Quick Start: Three Ways to Get Started

### **Option 1: Try It Right Now (No Token Needed)**

Each tool includes demo data. Explore immediately:

- **Navigator:** [Launch Demo](navigator.html) — 10 repos, 10 contributors, intentional risk patterns
- **Launchpad:** [Launch Demo](launchpad.html) — Sample AI ecosystem
- **Hub:** [Launch Demo](hub.html) — Example org showcase

### **Option 2: Analyze Your Own Ecosystem**

Search any GitHub organization. Need a token for rate limits? Optional — demo works without it.

→ Navigator: Search "microsoft" or "openai" to see real orgs

### **Option 3: Embed in Your Project**

Add Hub to your README or GitHub Pages. Show *your* ecosystem.

→ [Embedding Guide](docs/embedding.md)

---

## What Each Tool Actually Does

### Navigator (✅ **Fully Working**)

**The most mature variant.** Analyzes real GitHub orgs.

**Features:**
- ✅ Real GitHub API integration
- ✅ Four analytical lenses (Architecture, Org Map, Health, Due Diligence)
- ✅ Interactive D3 graph with drag, zoom, click
- ✅ Risk signals (single maintainers, stale repos, burnout risk)
- ✅ Bridge engineer detection (people spanning 3+ repos)
- ✅ Health scoring for repos
- ✅ Filter by risk, bridges, or critical repos
- ✅ Demo data (works without token)
- ✅ Real error handling & rate limit warnings
- ✅ Smooth scenario transitions

**What it tells you:**
- Is this ecosystem stable?
- Who's carrying the load?
- Where would it break?
- What's sustainable vs. fragile?

---

### Launchpad (⚠️ **MVP - In Progress**)

**For beginners getting started.**

*Currently a placeholder. Community contribution opportunity.*

**Vision:**
- Search topics or languages
- Show best repos by activity & adoption
- One-click to README & install commands
- No complexity, no risk analysis
- Pure onboarding

---

### Hub (⚠️ **MVP - In Progress**)

**For org maintainers.**

*Currently a placeholder. Community contribution opportunity.*

**Vision:**
- White-label org ecosystem viewer
- Embed in README or GitHub Pages
- Show repos, teams, relationships
- Customizable branding
- Perfect for promoting your work

---

## Core Beliefs

> "GitHub's chaos isn't a bug. It's a feature. You just need a guide to see the shape of it."

**Atlas is built on these principles:**

- 🗺️ **Maps are more useful than lists** — visualize relationships, not just repos
- 👥 **Community over solo** — the weight is lighter when carried together
- 🎯 **Signal over noise** — red pulses tell you more than stars do
- 🤝 **Open > closed** — this is a foundation for you to build on
- 📊 **Data-driven decisions** — see the risk before it bites you
- 🚀 **Progressive enhancement** — demo works, API is optional, embed anywhere

---

## The Roadmap

### ✅ Done
- Navigator (all four scenarios working)
- Core UI/UX framework
- D3 graph engine
- GitHub API integration
- Demo data generator
- Honest documentation

### ⏳ Coming Soon (Help Wanted)

**Short term:**
- Launchpad implementation
- Hub white-labeling
- Better docs with video walkthroughs
- Community examples

**Medium term:**
- Saved maps & shareable links
- Multi-query overlays (compare ecosystems)
- Dependency chain analysis
- Commit frequency trends
- Issue response time metrics
- Burnout detection algorithms

**Long term (Ambitious):**
- AI-powered insights
- Ecosystem health scoring
- Risk prediction
- GitHub integration (as an app)
- Your ideas here → [Open an Issue](https://github.com/blackmath88/github-atlas/issues)

---

## How to Participate

### 🧪 **Try It**
- [Navigator](navigator.html) — Analyze your org
- [Launchpad](launchpad.html) — Explore a topic
- [Hub](hub.html) — Showcase your ecosystem

### 💬 **Give Feedback**
- What worked? What didn't?
- What did you expect to see?
- [Open an issue](https://github.com/blackmath88/github-atlas/issues)

### 🔨 **Build With Us**
- Want to implement Launchpad or Hub?
- Have an idea for a new lens?
- Fork it, modify it, send a PR
- See [CONTRIBUTING.md](CONTRIBUTING.md)

### 📢 **Spread It**
- Use Navigator in your org
- Embed Hub in your README
- Tell us what you built
- Share in [Discussions](https://github.com/blackmath88/github-atlas/discussions)

---

## Frequently Asked Questions

**Q: Do I need a GitHub token?**  
A: No. All tools include demo data. Tokens unlock higher rate limits (5000 req/hr instead of 60) for larger orgs.

**Q: Can I embed Hub in my README?**  
A: Yes. [See the embedding guide](docs/embedding.md).

**Q: What data does Navigator use?**  
A: Live GitHub API. Your token, your privacy. All queries are client-side — nothing is logged.

**Q: Is this an official GitHub product?**  
A: No. It's a community-built tool built *with* GitHub's API.

**Q: Can I self-host this?**  
A: Yes. It's all static HTML + D3. Clone the repo and serve it yourself.

**Q: What about privacy?**  
A: All processing is client-side. API calls use your token. No tracking, no analytics, no data collection.

More questions? [See the FAQ](docs/faq.md) or [ask in Discussions](https://github.com/blackmath88/github-atlas/discussions).

---

## License

MIT. Use it, modify it, build on it. No permissions needed, just credit appreciated.

---

## Philosophy

> The bottleneck isn't intelligence. The bottleneck is *interface*.

AI can read big messy data. Your LLM understands GitHub architecture. But the GitHub UI and your CLI don't *show* you the shape of things.

**Atlas fills that gap.**

Maps work. Graphs work. Narrative works. When you combine them, complex systems become *visible*.

The weight of GitHub is lighter when you can *see* it.

---

## Get Started

👉 **[Launch Navigator Now](navigator.html)** — no setup, no token, demo data included

👉 **[Learn More](docs/getting-started.md)** — detailed guide for each tool

👉 **[Contribute](CONTRIBUTING.md)** — help build the future

---

**Built by the community. For the community. One visualization at a time.**

🌍 Atlas
