<h1 align="center">Jeremy Li</h1>

<p align="center">
  <strong>AI/ML systems, quantitative research tools, and web infrastructure.</strong>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&amp;weight=600&amp;size=18&amp;duration=2800&amp;pause=900&amp;color=0891B2&amp;center=true&amp;vCenter=true&amp;width=760&amp;lines=question+-%3E+model+-%3E+test+-%3E+failure+-%3E+revision;AI%2FML+systems+%7C+quantitative+research+%7C+web+infrastructure;build+small+loops+that+expose+state%2C+uncertainty%2C+and+failure" alt="Typing animation: question to model to test to failure to revision" />
</p>

<p align="center">
  <a href="mailto:jeremyli.ava@gmail.com">Email</a>
  ·
  <a href="https://github.com/JeremyLih">GitHub</a>
  ·
  <a href="https://andromedax.org">Website</a>
</p>

I build systems that connect theory, data, and deployable software.

<p align="center">
  <img src="https://img.shields.io/badge/AI%2FML-systems-0f172a?style=flat-square&amp;labelColor=111827&amp;color=0891b2" alt="AI/ML systems" />
  <img src="https://img.shields.io/badge/quant-research-0f172a?style=flat-square&amp;labelColor=111827&amp;color=0e7490" alt="Quant research" />
  <img src="https://img.shields.io/badge/systems-inspectable-0f172a?style=flat-square&amp;labelColor=111827&amp;color=0369a1" alt="Inspectable systems" />
  <img src="https://img.shields.io/badge/python-modeling-0f172a?style=flat-square&amp;logo=python&amp;logoColor=white&amp;labelColor=111827&amp;color=1d4ed8" alt="Python modeling" />
  <img src="https://img.shields.io/badge/cloudflare-edge-0f172a?style=flat-square&amp;logo=cloudflare&amp;logoColor=white&amp;labelColor=111827&amp;color=ea580c" alt="Cloudflare edge" />
  <img src="https://img.shields.io/badge/typescript-web-0f172a?style=flat-square&amp;logo=typescript&amp;logoColor=white&amp;labelColor=111827&amp;color=2563eb" alt="TypeScript web" />
</p>

| Contact | Link |
| :--- | :--- |
| Email | [jeremyli.ava@gmail.com](mailto:jeremyli.ava@gmail.com) |
| GitHub | [JeremyLih](https://github.com/JeremyLih) |
| Website | [andromedax.org](https://andromedax.org) |

| Profile Map |  |
| :--- | :--- |
| Systems | [Active Systems](#active-systems) |
| Loop | [Working Loop](#working-loop) |
| Philosophy | [Research / Build Philosophy](#research--build-philosophy) |
| Stack | [Tools I Use](#tools-i-use) |
| Focus | [Current Focus](#current-focus) |

> [!NOTE]
> I build systems that make reasoning, uncertainty, and failure visible.

```txt
lab console
-----------
mode      : research-builder
loop      : question -> model -> test -> failure -> revision
systems   : CASI | AndromedaX | AI Engineering Workflow
constraint: inspectability before scale
```

---

## Working Loop

```txt
question -> model -> test -> failure -> revision
```

I try to build in small, inspectable loops. The goal is not to make a system look impressive at the beginning, but to expose where it fails, understand why, and improve the parts that survive testing.

```mermaid
flowchart LR
    Q["question"] --> M["model"]
    M --> T["test"]
    T --> F["failure"]
    F --> R["revision"]
    R --> Q

    D["data"] --> T
    C["constraints"] --> F
    O["observable system"] --> R
```

---

## Current Direction

My current work sits between machine learning, math, physics, trading systems, and full-stack infrastructure.

| Area | What I am trying to make inspectable |
| :--- | :--- |
| **AI / ML systems** | Models, evaluation, calibration, and generalization |
| **Quantitative research** | Market data, features, signals, costs, regimes, and PnL |
| **Web infrastructure** | Interfaces, APIs, edge deployment, and project shipping |

---

## Active Systems

| System | What it is | Pipeline | Status[^status] |
| :--- | :--- | :--- | :--- |
| **CASI** | AI-driven quantitative research system testing weak ML signals under realistic constraints | `market data -> features -> signal -> decision -> pnl` | Active research system |
| **AndromedaX** | Web and infrastructure surface for shipping technical projects with clean interfaces and APIs | `interface -> api -> edge runtime -> deploy` | Active platform |
| **AI Engineering Workflow** | Commander / Implementor / Inspector workflow for AI-assisted software work | `task -> command -> implementation -> audit -> memory` | Experimental workflow |

```mermaid
flowchart TB
    Theory["math / physics / mechanism"] --> Experiment["small experiments"]
    Data["market data"] --> CASI["CASI"]
    Experiment --> CASI
    CASI --> Failure["failure analysis"]
    Failure --> Revision["revision"]

    UI["interfaces"] --> AndromedaX["AndromedaX"]
    APIs["APIs / edge runtime"] --> AndromedaX
    AndromedaX --> Access["public technical surfaces"]

    Task["task"] --> Workflow["AI Engineering Workflow"]
    Workflow --> Audit["audit / verification"]
    Audit --> Memory["memory / notes"]
    Memory --> Revision
```

### CASI

```txt
market data -> features -> signal -> decision -> pnl
```

CASI is an AI-driven quantitative research system focused on testing whether weak machine-learning signals can survive transaction costs, regime shifts, and execution constraints.

<details>

<summary><strong>CASI research notes</strong></summary>

CASI is not just a model. It is a full research pipeline for asking whether a trading signal remains useful after realistic constraints are added.

| Focus | Questions |
| :--- | :--- |
| Signal validity | Can a weak signal remain positive after fees and slippage? |
| Regimes | Does the signal survive different market regimes? |
| Execution assumptions | Are the backtest, paper-trading logic, and execution assumptions consistent? |
| Reproducibility | Can the system be replayed, inspected, and debugged later? |

Current focus:

- Deterministic market data pipeline
- Feature generation and validation
- Signal calibration
- Regime-aware decision logic
- Paper-trading and PnL reconstruction
- Failure analysis before scaling complexity

</details>

### AndromedaX

```txt
interface -> api -> edge runtime -> deploy
```

AndromedaX is my web and infrastructure direction for shipping technical projects with cleaner interfaces, APIs, and deployment surfaces.

Website: [andromedax.org](https://andromedax.org)

<details>

<summary><strong>AndromedaX build notes</strong></summary>

| Use | Current focus |
| :--- | :--- |
| Build small public-facing technical projects | Project landing pages |
| Test UI ideas for AI tools and data systems | AI-assisted tools |
| Connect frontend interfaces with backend APIs | Cleaner routing, authentication, and API structure |
| Deploy through modern web infrastructure | Cloudflare-based deployment |
| Make experimental systems easier to access | Clearer project surfaces and documentation |

</details>

### AI Engineering Workflow

```txt
task -> command -> implementation -> audit -> memory
```

AI Engineering Workflow is a Commander / Implementor / Inspector workflow for using AI agents to build software while preserving scope, state, and verification.

<details>

<summary><strong>AI engineering workflow notes</strong></summary>

| Use | Current focus |
| :--- | :--- |
| Keep AI-assisted engineering scoped and inspectable | Clear task boundaries |
| Separate planning, implementation, and review | Reviewable implementation steps |
| Preserve project state across longer build sessions | Failure notes and memory capture |
| Make verification part of the workflow | Better handoff between ideas, code, tests, and revision |

```mermaid
sequenceDiagram
    participant C as Commander
    participant I as Implementor
    participant R as Inspector
    participant M as Memory

    C->>I: define task, constraints, acceptance checks
    I->>R: produce implementation and evidence
    R->>I: audit scope, behavior, and regressions
    R->>M: capture decisions and failure notes
    M->>C: preserve context for the next loop
```

</details>

---

## Research / Build Philosophy

I am most interested in systems where correctness is not obvious from the first result.

| Surface result | Failure mode |
| :--- | :--- |
| A model can look good | Leakage |
| A backtest can look good | Costs are ignored |
| A web app can look good | Broken state is hidden |
| A theory can look elegant | Weak contact with reality |

One way I think about these systems:

```math
\text{usable edge} \approx \text{signal} - \text{cost} - \text{uncertainty} - \text{implementation error}
```

So I try to build around a few principles:

- Reasoning before implementation
- Small experiments before large systems
- Validation before optimization
- Readable code before clever code
- Reproducibility before speed
- Interfaces that show state, uncertainty, and trade-offs

---

## Thinking Model

| Layer | Question I keep asking | What can go wrong |
| :--- | :--- | :--- |
| **Math / Physics** | What mechanism explains the behavior? | Nice theory, weak contact with reality |
| **ML / DL** | Does the model generalize outside the setup? | Leakage, overfitting, noisy metrics |
| **Quant Systems** | Does the signal survive cost and regime shifts? | Paper alpha that disappears in execution |
| **Infrastructure** | Can this be run, inspected, and changed later? | Prototype code turning into permanent debt |
| **UI** | Does the interface reveal the system state clearly? | Visual polish hiding important uncertainty |

---

## Tools I Use

| Purpose | Tools |
| :--- | :--- |
| **Research / Modeling** | Python, PyTorch, NumPy, Pandas, scikit-learn |
| **Experimentation** | Jupyter, pytest, Parquet, matplotlib |
| **Systems / Infrastructure** | Git, GitHub, bash, TypeScript |
| **Deployment** | Cloudflare, Workers, Pages, KV / D1 |

Workflow:

```txt
experiments -> logs -> validation -> failure notes -> revision
```

I prefer tools that make a system easier to inspect, reproduce, and repair.

---

## Current Focus

- Making CASI more deterministic, replayable, and honest about failure
- Turning AndromedaX into a cleaner home for technical projects
- Improving my ability to connect math, ML, and software into usable systems
- Building projects that can become long-term research and portfolio assets

---

## What I Am Learning

| Area | Direction |
| :--- | :--- |
| **Machine learning and deep learning** | Models, evaluation, and generalization |
| **Quantitative systems** | Signals, regimes, risk, and PnL |
| **Probability, statistics, and optimization** | Better reasoning under uncertainty |
| **Physics and mathematical modeling** | Mechanisms, abstraction, and explanation |
| **Full-stack web infrastructure** | Interfaces, APIs, deployment, and operations |
| **AI-assisted engineering workflows** | Scope control, verification, and memory |

---

## What I Care About

I care less about whether a project looks finished at the surface and more about whether it can answer serious questions.

For me, a good technical project should make it possible to ask:

- What exactly is the system doing?
- What assumptions does it depend on?
- What breaks when the environment changes?
- Can the result be reproduced?
- Can another person understand and improve it later?

---

## Selected Project Directions

| Project | Area | Core Question |
| :--- | :--- | :--- |
| **CASI** | AI / Quant Research | Can weak ML signals survive realistic trading constraints? |
| **AndromedaX** | Web / Infrastructure | Can technical projects be shipped with clean interfaces and deployable structure? |
| **AI Engineering Workflow** | Developer Systems | Can AI agents help build software without losing state, scope, or verification? |
| **Math / Physics Notes** | Theory / Learning | Can abstract mechanisms be turned into usable models and explanations? |

---

## Contact

| Contact | Link |
| :--- | :--- |
| Email | [jeremyli.ava@gmail.com](mailto:jeremyli.ava@gmail.com) |
| GitHub | [JeremyLih](https://github.com/JeremyLih) |
| Website | [andromedax.org](https://andromedax.org) |

[^status]: Status labels describe current direction and working mode, not finished-product claims.
