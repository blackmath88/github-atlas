# Getting Started with GitHub Atlas

Three tools. Three different journeys. Pick yours.

---

## 🚀 Launchpad — For Beginners

**You want to:** Find the best tools for what you're trying to do, fast.

**Start here:** [Launch Launchpad](../launchpad.html)

**What it does:**
- Search topics (e.g., "prompt engineering", "machine learning")
- See best repos by activity & community adoption
- One-click to README & install command
- No risk analysis, no complexity
- Pure onboarding

**Example journey:**
1. Search "langchain"
2. See top repos + brief descriptions
3. Click one → instant README + setup
4. Start building in 2 minutes

**Perfect for:** Beginners, quick starts, "just show me what works"

---

## 🔍 Navigator — For Architects & Risk Assessors

**You want to:** Understand the *real* health of an ecosystem before betting on it.

**Start here:** [Launch Navigator](../navigator.html)

**What it does:**
- Real GitHub org analysis (or use demo data)
- Four analytical lenses:
  - **Architecture:** Is it stable? Single maintainers?
  - **Org Mapping:** Who knows what? Knowledge concentration?
  - **Health:** Is this sustainable?
  - **Due Diligence:** What's the investment risk?
- Interactive graph with risk signals
- Filter by risk, bridges, critical repos
- Detail panel with health scores

**Getting real data:**
1. Open [Navigator](../navigator.html)
2. Choose an analytical lens
3. Search an organization (e.g., "microsoft", "openai")
4. Optionally add a GitHub token for higher rate limits
5. Explore the graph

**Understanding the graph:**
- **Node color:** Maintenance health (red=risk, blue=healthy, gray=stale)
- **Node size:** Criticality or knowledge load (depends on scenario)
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

**Start here:** [Hub guide](./hub-guide.md)

**What it does:**
- Interactive map of your repos
- Embed in README or GitHub Pages
- White-label (customize colors, logo)
- Show repos, teams, relationships
- Help users navigate your work

**Example:** Embed in your project's README

```markdown
## 🗺️ Explore Our Ecosystem

<iframe src="https://your-domain.com/atlas-hub.html" width="100%" height="800"></iframe>

Browse all our repos and understand how they fit together.
