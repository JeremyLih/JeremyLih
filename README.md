# Jeremy Li

**AI/ML systems, quantitative research tools, and web infrastructure.**

I build systems that connect theory, data, and deployable software. My current work sits between machine learning, math, physics, trading systems, and full-stack infrastructure.

| Contact | Link |
| :--- | :--- |
| Email | [jeremyli.ava@gmail.com](mailto:jeremyli.ava@gmail.com) |
| GitHub | [JeremyLih](https://github.com/JeremyLih) |
| Website | [andromedax.org](https://andromedax.org) |

> [!NOTE]
> I build systems that make reasoning, uncertainty, and failure visible.

---

## Working Loop

```txt
question -> model -> test -> failure -> revision
```

I try to build in small, inspectable loops. The goal is not to make a system look impressive at the beginning, but to expose where it fails, understand why, and improve the parts that survive testing.

---

## Current Direction

Most of my work falls into three connected areas:

| Area | What I am trying to make inspectable |
| :--- | :--- |
| AI / ML systems | Models, evaluation, calibration, and generalization |
| Quantitative research | Market data, features, signals, costs, regimes, and PnL |
| Web infrastructure | Interfaces, APIs, edge deployment, and project shipping |

---

## Active Systems

| System | Role | Status |
| :--- | :--- | :--- |
| CASI | AI-driven quantitative research system testing weak ML signals under realistic constraints | Active research system |
| AndromedaX | Web and infrastructure surface for shipping technical projects with clean interfaces and APIs | Active platform |
| AI Engineering Workflow | Commander / Implementor / Inspector workflow for AI-assisted software work | Experimental workflow |

| System | Pipeline | Core Question |
| :--- | :--- | :--- |
| CASI | `market data -> features -> signal -> decision -> pnl` | Can weak ML signals survive realistic trading constraints? |
| AndromedaX | `interface -> api -> edge runtime -> deploy` | Can technical projects be shipped with clean interfaces and deployable structure? |
| AI Engineering Workflow | `task -> command -> implementation -> audit -> memory` | Can AI agents help build software without losing state, scope, or verification? |

### CASI

CASI is an AI-driven quantitative research system focused on testing whether weak machine-learning signals can survive transaction costs, regime shifts, and execution constraints.

```txt
market data -> features -> signal -> decision -> pnl
```

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

### AndromedaX

AndromedaX is my web and infrastructure direction for shipping technical projects with cleaner interfaces, APIs, and deployment surfaces.

```txt
interface -> api -> edge runtime -> deploy
```

Website: [andromedax.org](https://andromedax.org)

| Use | Current focus |
| :--- | :--- |
| Build small public-facing technical projects | Project landing pages |
| Test UI ideas for AI tools and data systems | AI-assisted tools |
| Connect frontend interfaces with backend APIs | Cleaner routing, authentication, and API structure |
| Deploy through modern web infrastructure | Cloudflare-based deployment |
| Make experimental systems easier to access | Clearer project surfaces and documentation |

### AI Engineering Workflow

AI Engineering Workflow is a Commander / Implementor / Inspector workflow for using AI agents to build software while preserving scope, state, and verification.

```txt
task -> command -> implementation -> audit -> memory
```

| Use | Current focus |
| :--- | :--- |
| Keep AI-assisted engineering scoped and inspectable | Clear task boundaries |
| Separate planning, implementation, and review | Reviewable implementation steps |
| Preserve project state across longer build sessions | Failure notes and memory capture |
| Make verification part of the workflow | Better handoff between ideas, code, tests, and revision |

---

## Research / Build Philosophy

I am most interested in systems where correctness is not obvious from the first result.

| Surface result | Failure mode |
| :--- | :--- |
| A model can look good | Leakage |
| A backtest can look good | Costs are ignored |
| A web app can look good | Broken state is hidden |
| A theory can look elegant | Weak contact with reality |

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
| Math / Physics | What mechanism explains the behavior? | Nice theory, weak contact with reality |
| ML / DL | Does the model generalize outside the setup? | Leakage, overfitting, noisy metrics |
| Quant Systems | Does the signal survive cost and regime shifts? | Paper alpha that disappears in execution |
| Infrastructure | Can this be run, inspected, and changed later? | Prototype code turning into permanent debt |
| UI | Does the interface reveal the system state clearly? | Visual polish hiding important uncertainty |

---

## Tools I Use

| Purpose | Tools |
| :--- | :--- |
| Research / Modeling | Python, PyTorch, NumPy, Pandas, scikit-learn |
| Experimentation | Jupyter, pytest, Parquet, matplotlib |
| Systems / Infrastructure | Git, GitHub, bash, TypeScript |
| Deployment | Cloudflare, Workers, Pages, KV / D1 |

Workflow:

```txt
experiments -> logs -> validation -> failure notes -> revision
```

I prefer tools that make a system easier to inspect, reproduce, and repair.

---

## Current Focus

Right now I am working on:

- Making CASI more deterministic, replayable, and honest about failure
- Turning AndromedaX into a cleaner home for technical projects
- Improving my ability to connect math, ML, and software into usable systems
- Building projects that can become long-term research and portfolio assets

---

## What I Am Learning

| Area | Direction |
| :--- | :--- |
| Machine learning and deep learning | Models, evaluation, and generalization |
| Quantitative systems | Signals, regimes, risk, and PnL |
| Probability, statistics, and optimization | Better reasoning under uncertainty |
| Physics and mathematical modeling | Mechanisms, abstraction, and explanation |
| Full-stack web infrastructure | Interfaces, APIs, deployment, and operations |
| AI-assisted engineering workflows | Scope control, verification, and memory |

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
| CASI | AI / Quant Research | Can weak ML signals survive realistic trading constraints? |
| AndromedaX | Web / Infrastructure | Can technical projects be shipped with clean interfaces and deployable structure? |
| AI Engineering Workflow | Developer Systems | Can AI agents help build software without losing state, scope, or verification? |
| Math / Physics Notes | Theory / Learning | Can abstract mechanisms be turned into usable models and explanations? |

---

## Contact

| Contact | Link |
| :--- | :--- |
| Email | [jeremyli.ava@gmail.com](mailto:jeremyli.ava@gmail.com) |
| GitHub | [JeremyLih](https://github.com/JeremyLih) |
| Website | [andromedax.org](https://andromedax.org) |
