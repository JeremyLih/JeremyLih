# Jeremy Li

I build AI/ML systems, quantitative research tools, and web infrastructure that connect theory, data, and deployable software.

My current work sits between machine learning, math, physics, trading systems, and full-stack infrastructure. I care about whether an idea can survive contact with real data, real constraints, and real users.

- Email: <jeremyli.ava@gmail.com>
- GitHub: [JeremyLih](https://github.com/JeremyLih)
- Website: [andromedax.org](https://andromedax.org)

## Working Loop

```txt
question -> model -> test -> failure -> revision
```

I try to build in small, inspectable loops. The goal is not to make a system look impressive at the beginning, but to expose where it fails, understand why, and improve the parts that survive testing.

## Current Direction

I am focused on building systems that make reasoning, uncertainty, and failure visible.

Most of my work falls into three connected areas:

- AI / ML systems: models, evaluation, calibration, and generalization
- Quantitative research: market data, features, signals, costs, regimes, and PnL
- Web infrastructure: interfaces, APIs, edge deployment, and project shipping

## Active Systems

### CASI

CASI is an AI-driven quantitative research system focused on testing whether weak machine-learning signals can survive transaction costs, regime shifts, and execution constraints.

```txt
market data -> features -> signal -> decision -> pnl
```

CASI is not just a model. It is a full research pipeline for asking whether a trading signal remains useful after realistic constraints are added.

Core questions:

- Can a weak signal remain positive after fees and slippage?
- Does the signal survive different market regimes?
- Are the backtest, paper-trading logic, and execution assumptions consistent?
- Can the system be replayed, inspected, and debugged later?

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

What it is for:

- Building small public-facing technical projects
- Testing UI ideas for AI tools and data systems
- Connecting frontend interfaces with backend APIs
- Deploying projects through modern web infrastructure

Current focus:

- Project landing pages
- AI-assisted tools
- Cloudflare-based deployment
- Cleaner routing, authentication, and API structure
- Making experimental systems easier to access and understand

## Research / Build Philosophy

I am most interested in systems where correctness is not obvious from the first result.

A model can look good because of leakage.

A backtest can look good because costs are ignored.

A web app can look good while hiding broken state.

A theory can look elegant while making weak contact with reality.

So I try to build around a few principles:

- Reasoning before implementation
- Small experiments before large systems
- Validation before optimization
- Readable code before clever code
- Reproducibility before speed
- Interfaces that show state, uncertainty, and trade-offs

## Thinking Model

| Layer | Question I keep asking | What can go wrong |
| :--- | :--- | :--- |
| Math / Physics | What mechanism explains the behavior? | Nice theory, weak contact with reality |
| ML / DL | Does the model generalize outside the setup? | Leakage, overfitting, noisy metrics |
| Quant Systems | Does the signal survive cost and regime shifts? | Paper alpha that disappears in execution |
| Infrastructure | Can this be run, inspected, and changed later? | Prototype code turning into permanent debt |
| UI | Does the interface reveal the system state clearly? | Visual polish hiding important uncertainty |

## Tools I Use

### Research / Modeling

```txt
Python      PyTorch      NumPy      Pandas      scikit-learn
Jupyter     pytest       Parquet    matplotlib
```

### Systems / Infrastructure

```txt
Git         GitHub       bash       TypeScript
Cloudflare  Workers      Pages      KV / D1
```

### Workflow

```txt
experiments -> logs -> validation -> failure notes -> revision
```

I prefer tools that make a system easier to inspect, reproduce, and repair.

## Current Focus

Right now I am working on:

- Making CASI more deterministic, replayable, and honest about failure
- Turning AndromedaX into a cleaner home for technical projects
- Improving my ability to connect math, ML, and software into usable systems
- Building projects that can become long-term research and portfolio assets

## What I Am Learning

I am actively learning and building around:

- Machine learning and deep learning
- Quantitative systems
- Probability, statistics, and optimization
- Physics and mathematical modeling
- Full-stack web infrastructure
- AI-assisted engineering workflows

## What I Care About

I care less about whether a project looks finished at the surface and more about whether it can answer serious questions.

For me, a good technical project should make it possible to ask:

- What exactly is the system doing?
- What assumptions does it depend on?
- What breaks when the environment changes?
- Can the result be reproduced?
- Can another person understand and improve it later?

## Selected Project Directions

| Project | Area | Core Question |
| :--- | :--- | :--- |
| CASI | AI / Quant Research | Can weak ML signals survive realistic trading constraints? |
| AndromedaX | Web / Infrastructure | Can technical projects be shipped with clean interfaces and deployable structure? |
| AI Engineering Workflow | Developer Systems | Can AI agents help build software without losing state, scope, or verification? |
| Math / Physics Notes | Theory / Learning | Can abstract mechanisms be turned into usable models and explanations? |

## Contact

- Email: <jeremyli.ava@gmail.com>
- GitHub: [JeremyLih](https://github.com/JeremyLih)
- Website: [andromedax.org](https://andromedax.org)
