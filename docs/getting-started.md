# Getting Started with GitHub Atlas

Three tools. Three different journeys. Pick yours.

---

## 🧭 Navigator — For Beginners & AI/LLM Explorers

**You want to:** Find the best AI/LLM tools for what you're trying to do, fast.

**Start here:** [Launch Navigator](../navigator.html)

**What it does:**
- Search any GitHub topic — live results as a force-directed graph
- Browse 28 hand-curated AI/LLM repos across 10 intent clusters
- Pick a persona to filter what's relevant to you
- One-click to README, difficulty level, and how to get started
- 🌲 Dark Forest mode hides sensitive/leaked prompt collections by default

**Example journey:**
1. Search "langchain" or pick a topic chip like "rag pipelines"
2. See top repos in an interactive map — trust level and star count included
3. Click a node → instant description, difficulty, and first steps
4. Hit "Explore inside →" to navigate the repo's README as a map
5. Start building in minutes

**Perfect for:** Beginners, AI researchers, prompt engineers, developers new to LLMs

---

## 📡 Radar — For Architects & Risk Assessors

**You want to:** Understand the *real* health of an ecosystem before betting on it.

**Start here:** [Launch Radar](../radar.html)

**What it does:**
- Real GitHub org analysis (or use demo data — no token needed)
- Four analytical lenses:
  - **Architecture Review:** Is it stable? Single maintainers?
  - **Org Map:** Who knows what? Knowledge concentration?
  - **Ecosystem Health:** Is this sustainable?
  - **Due Diligence:** What's the investment risk?
- Interactive graph with risk signals
- Filter by risk, bridges, critical repos
- Detail panel with health scores 0–100
- Drill inside repos — navigate README structure as an interactive map

**Getting real data:**
1. Open [Radar](../radar.html)
2. Choose an analytical lens
3. Search an organization (e.g., "microsoft", "openai", "langchain-ai")
4. Optionally add a GitHub token for higher rate limits (60 → 5,000 req/hr)
5. Explore the graph

**Understanding the graph:**
- **Node color:** Maintenance health (red = risk, blue = healthy, gray = stale)
- **Node size:** Criticality or knowledge load (depends on lens)
- **Red pulse:** Single maintainer — risk signal
- **Gold ring:** Bridge engineer — person spanning 3+ repos
- **Lines:** Connections (who contributes to what)

**Real use cases:**
- "Evaluate a framework before committing our team"
- "Inherit a codebase and understand the risk"
- "Audit our org's dependencies"
- "Due diligence before an acquisition"

**Perfect for:** Architects, org leads, security audits, investment decisions

---

## 🏢 Hub — For Org Maintainers

**You want to:** Help your community *see* your ecosystem instead of reading about it.

**Start here:** [Launch Hub](../hub.html)

**What it does:**
- Interactive map of any org's or user's public repos
- Three view modes: by topic, by language, by activity
- Repository health scoring
- Auto-generate embeddable iframe code
- URL params (`?org=yourorg`) for direct linking
- Drill inside repos — navigate README structure as an interactive map

**Example: embed in your project's README**

```markdown
## 🗺️ Explore Our Ecosystem

<iframe src="https://blackmath88.github.io/github-atlas/hub.html?org=yourorg" width="100%" height="800"></iframe>

Browse all our repos and understand how they fit together.
```

**Perfect for:** Framework maintainers, open-source orgs, teams managing multiple projects
