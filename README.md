<div align="center">

# Awesome Claude Artifacts ✨

**A curated collection of the best things people have built with Claude Artifacts** — games, tools, visualizations, and prompts that generated them.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](LICENSE)

[What are Artifacts?](#what-are-artifacts) •
[Browse](#-the-list) •
[Contribute](#-contributing) •
[Prompt Tips](#-prompt-tips)

</div>

---

## What are Artifacts?

[Claude Artifacts](https://claude.ai) are standalone pieces of content — code, documents, diagrams, interactive apps — that Claude generates in a dedicated window next to the chat, separate from the conversation. They can be games, dashboards, data visualizations, or full working web apps, and they're editable and shareable.

This repo collects the best examples of what people have actually built, along with the prompts that got them there, so you can learn patterns and steal ideas.

## How entries are organized

Each entry includes:
- 🔗 A link to the artifact (live demo or shared Claude link, where shareable)
- 💬 The prompt (or a close paraphrase) that generated it
- 🏷️ Category + complexity tag

> **Note:** Claude-shared links expire or may require login depending on Anthropic's sharing settings at the time. Where possible, entries link to a reproduction hosted independently (CodePen, GitHub Pages, etc.) so the demo stays alive.

---

## 📚 The List

### 🎮 Games
> Playable games built entirely as artifacts — no external assets, single-file.

| Name | Description | Complexity |
|---|---|---|
| _Add the first entry! See [CONTRIBUTING.md](CONTRIBUTING.md)_ | | |

### 📊 Data Visualization & Dashboards
> Interactive charts, dashboards, and data explainers.

| Name | Description | Complexity |
|---|---|---|
| _Add the first entry!_ | | |

### 🛠️ Developer Tools
> Utilities that help with coding, debugging, or workflow tasks.

| Name | Description | Complexity |
|---|---|---|
| _Add the first entry!_ | | |

### 🧮 Productivity & Utility Apps
> Calculators, trackers, planners, converters — small tools that solve one problem well.

| Name | Description | Complexity |
|---|---|---|
| _Add the first entry!_ | | |

### 🎨 Creative & Generative Art
> SVG/Canvas art, generative patterns, visual experiments.

| Name | Description | Complexity |
|---|---|---|
| [Particle Life Simulator](./prompts/particle-life-simulator.md) | Emergent, organic motion from randomized attraction/repulsion rules between particle species. | 🟡 Medium |

### 🧑‍🏫 Education & Explainers
> Interactive explainers that teach a concept better than static text.

| Name | Description | Complexity |
|---|---|---|
| _Add the first entry!_ | | |

### 🤖 Agents & Multi-step Tools
> Artifacts that chain reasoning, use the Claude API from inside the artifact, or simulate agent behavior.

| Name | Description | Complexity |
|---|---|---|
| _Add the first entry!_ | | |

---

## 💡 Prompt Tips

Patterns that consistently produce better artifacts (contribute more via PR):

1. **Specify the interaction model up front** — "single-page, no external dependencies, all state in React hooks" avoids Claude reaching for things that won't render.
2. **Ask for the visual style explicitly** — "dark mode, glassmorphism, generous whitespace" beats "make it look nice."
3. **Iterate in small diffs** — ask for one change at a time on an existing artifact rather than regenerating from scratch; Claude preserves working code better this way.
4. **Give Claude a constraint to push against** — "in under 100 lines," "using only CSS, no JS" — constraints tend to produce more creative solutions.

Full writeups of prompt breakdowns live in [`/prompts`](./prompts).

## 🙌 Contributing

PRs welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for the format. Quick version:

1. Fork this repo
2. Add your entry to the right category table, alphabetically
3. Follow the [entry template](./TEMPLATE.md)
4. Open a PR

## 📄 License

[CC0](LICENSE) — this list is public domain. Linked artifacts retain their own creators' rights.

---

<div align="center">
<sub>Not affiliated with Anthropic. "Claude" and "Artifacts" are products of Anthropic PBC.</sub>
</div>
