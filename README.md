<h1 align="center">Adarsh Keshri</h1>
<p align="center"><em>Systems builder working across AI security, scientific computing, quantitative finance, and developer infrastructure.</em></p>

<p align="center">
  <a href="https://github.com/anonymousAAK"><img src="https://img.shields.io/github/followers/anonymousAAK?label=Follow&style=social" alt="GitHub Followers"/></a>
  <a href="https://pypi.org/project/aastf/"><img src="https://img.shields.io/pypi/v/aastf?label=aastf%20on%20PyPI&color=6C63FF" alt="aastf on PyPI"/></a>
  <a href="https://linkedin.com/in/adarshkeshri13"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <img src="https://komarev.com/ghpvc/?username=anonymousAAK&style=flat&color=6C63FF" alt="Profile views"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6C63FF&center=true&vCenter=true&width=620&lines=Systems+builder+across+disciplines;AI+security+%7C+quant+finance+%7C+scientific+computing;Builds+languages%2C+agents%2C+and+simulators;Open+to+hard+problems+that+span+fields" alt="Typing SVG"/>
  </a>
</p>

---

## About

I build systems at the seams between fields. I treat AI agents, financial markets, physical processes, and programming languages as the same kind of object: a thing with state, dynamics, failure modes, and an interface, all of which can be modeled, instrumented, and broken on purpose.

My public work spans:

- **AI security** — `aastf`, an Agentic AI Security Testing Framework published on PyPI that intercepts the agent execution graph and tests it against the OWASP Top 10 for Agentic Applications 2026.
- **Scientific computing** — streaming NASA Kepler-mission data to classify habitability candidates, and a space-mission dashboard.
- **Language and compiler design** — `adarshLang`, a small interpreted language with its own lexer, parser, and evaluator.
- **Algorithmic depth** — a 30-week, four-language curriculum (Java / Python / C++ / Rust) covering everything from binary search to network flow, NP-completeness, and computational geometry.
- **Quantitative finance** — research and tooling around implied-volatility surfaces, SVI / SABR calibration, HMM regime detection, and Monte Carlo VaR. (Most of this work lives outside this GitHub account.)

If a problem requires translating between physics, finance, machine learning, and production code, that is the kind of problem I want.

---

## Background

- **MBA candidate, IIM Raipur — PGP, Class of 2027.**
- **BSc (Hons.) Physics** — undergraduate background in classical mechanics, statistical physics, and computational methods.
- **Published author** — *Realizing a Fully Functional CPU Using Multi-Layer Perceptrons*, **IJARIIT, Vol. 11, Issue 1, pp. 248–256 (21 Feb 2025), ISSN 2454-132X**. The paper introduces **IC 616 Ultra-MLP**, a fully perceptron-based CPU showing that arrays of threshold units, with appropriate weights and biases, can theoretically implement all standard computing tasks — pipeline, memory hierarchy, and on-chip training included. It sits at the boundary of neural-inspired computing and computer architecture.
- **Co-founder, Cosminder Solutions (Deoghar, Jharkhand)** — AI research lab. Led work on large-parameter simulation models, including a multi-country macroeconomic simulation engine. (Most of this work is not in this GitHub account.)
- **Quant interests** — implied volatility surfaces, SVI / SABR fitting, HMM-based regime detection, portfolio optimization, Monte Carlo VaR.

---

## Featured Work

These six repositories are chosen to show **range across domains**, not language stack.

| Repository | Domain | What the system does |
|---|---|---|
| **[aastf](https://github.com/anonymousAAK/aastf)** | AI security | Agentic AI Security Testing Framework. Intercepts the agent execution graph (LangGraph / CrewAI / OpenAI Agents / PydanticAI) and runs 50 attack scenarios mapped to the OWASP Top 10 for Agentic Applications 2026 (ASI01 through ASI10). 224 passing tests, SARIF output for the GitHub Security tab, EU AI Act readiness reporting. On PyPI as `aastf`. |
| **[kepler_Hplanets_using_node](https://github.com/anonymousAAK/kepler_Hplanets_using_node)** | Scientific computing | Streams NASA Kepler-mission CSV data through Node.js and filters habitable-zone candidates using planetary radius (under 1.6 Earth radii) and stellar flux between 0.36 and 1.11 relative to Earth — the conservative habitable-zone bounds from Kopparapu et al. (2013). A small but real physics-data pipeline. |
| **[adarshLang](https://github.com/anonymousAAK/adarshLang)** | Languages and systems | A Hinglish-flavored interpreted language with a full lexer, parser, and interpreter written in Python. Has a hosted online playground. |
| **[my-DSA-journey](https://github.com/anonymousAAK/my-DSA-journey)** | Algorithms and foundations | A 30-week, beginner-to-research algorithms curriculum implemented side-by-side in **Java, Python, C++, and Rust**, with interactive HTML lesson pages per week. Covers DP, flows, computational geometry, amortized analysis, and NP-completeness. |
| **[NASA-PROJECT](https://github.com/anonymousAAK/NASA-PROJECT)** | Scientific computing / systems | Space-mission dashboard built on Node.js with launch and upcoming-mission tracking, plus a separate React client. A larger end-to-end systems project than the Kepler script. |
| **[MERN-Stack-BookApp](https://github.com/anonymousAAK/MERN-Stack-BookApp)** | Full-stack systems | A complete CRUD application across MongoDB, Express, React, and Node. Included to show that the systems above are backed by production-shaped engineering, not just notebooks. |

> The remaining repositories on this account are smaller experiments, learning artifacts, and tooling. See the full list at [github.com/anonymousAAK?tab=repositories](https://github.com/anonymousAAK?tab=repositories).

---

## Domains I build in

```text
AI & Agentic Systems     ████████████████░░░░    aastf, agent harnesses, adapters
AI Security              ███████████████░░░░░    OWASP ASI 2026, prompt and tool injection
Quantitative Finance     ██████████░░░░░░░░░░    IV surfaces, SVI/SABR, HMM, Monte Carlo VaR
Scientific Computing     █████████░░░░░░░░░░░    Kepler data, MLP-CPU research
Languages & Compilers    ████████░░░░░░░░░░░░    adarshLang lexer/parser/interpreter
Systems & Dev Tooling    ████████░░░░░░░░░░░░    CLIs, sandboxes, CI integrations
Algorithms & Foundations ████████████░░░░░░░░    30-week curriculum, 4 languages
```

The bars represent relative emphasis in my public and semi-public work, not a skill self-rating.

---

## Tools I build systems with

I pick the language to match the problem, not the other way round.

**For agents, ML, and analytics:** Python, LangGraph, CrewAI, OpenAI Agents SDK, PydanticAI, FastAPI, Jinja, SARIF, OpenTelemetry.

**For low-level and performance work:** C++17, Rust.

**For services and full-stack systems:** Node.js, Express, React, TypeScript, MongoDB, MySQL, GraphQL.

**For everyday correctness:** Java, pytest, Hypothesis property-based tests, GitHub Actions, Linux, Bash.

---

## GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=anonymousAAK&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anonymousAAK&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=anonymousAAK&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=anonymousAAK&theme=tokyo-night&hide_border=true&area=true" alt="Activity Graph"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/anonymousAAK/anonymousAAK/output/github-snake-dark.svg" alt="Snake animation"/>
</p>

---

## Connect

I'm open to collaborations on hard, cross-disciplinary problems — AI safety and agent security, quantitative-finance research, scientific simulation, and developer tooling that takes correctness seriously. I'm interested in roles where systems thinking across domains is the job, not a side dish.

<p align="center">
  <a href="https://github.com/anonymousAAK"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://linkedin.com/in/adarshkeshri13"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://pypi.org/project/aastf/"><img src="https://img.shields.io/badge/PyPI-aastf-3775A9?style=for-the-badge&logo=pypi&logoColor=white" alt="PyPI"/></a>
</p>

<p align="center"><sub>If something here resonates, send me a message. I prefer specific problems to generic intros.</sub></p>
