# SEFOP: Software Engineering Framework for Optimization Programs

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Discussions](https://img.shields.io/badge/GitHub-Discussions-9b59b6?logo=github)](https://github.com/orgs/sefop/discussions)

> **A practical framework for building decision-support software that is maintainable, testable, deployable, and ready for production.**

Operations Research (OR) creates business value by helping organizations make better decisions. That value is delivered through
**decision-support software**: software that runs repeatedly to turn data, mathematical models, and business rules into recurring
business decisions.

**SEFOP** brings software engineering practices into the particular needs of decision-support software, from theory to practice, and is 
directed to the engineering managers and the scientists/developers building this system.

---

## Contents

- [Context: what are we building?](#context-what-are-we-building)
- [Why: what goes wrong, and why?](#why-what-goes-wrong-and-why)
- [Can't AI agents solve this?](#cant-ai-agents-solve-this)
- [What is SEFOP?](#what-is-sefop)
- [Who maintains SEFOP](#who-maintains-sefop)
- [Resources: where to start](#resources-where-to-start)
- [Community: how to take part](#community-how-to-take-part)
- [License](#license)

---

## Context: what are we building?

Decision-support software turns data, mathematical models, and business rules into decisions. It may support operational, tactical, or
strategic decisions, and unlike a one-off analysis it is designed to run repeatedly.

Examples include:

- Planning the **annual** extraction of resources from a mine.
- Building the **monthly** shift schedules of a retail store.
- Planning the **weekly** delivery of cargo across a transportation network.
- Recovering the **daily** operation from a weather disruption in an airline.

These systems are often developed by Operations Research scientists and other decision-science practitioners. Because decision-support
software runs on a cadence rather than ending at a deliverable, it must be maintained, tested, deployed and evolved.

> 💡 **The value is not in producing one analysis. It is in building a sustainable decision-making tool.**

---

## Why: what goes wrong, and why?

Decision-support software often has weak software engineering practices, especially in the components surrounding the mathematical model.
The literature has already mentioned it:

- [Vidoni (2021)](https://doi.org/10.1080/01605682.2020.1865848): recognizes the need of an 'Operations Research Engineering' practice to
specifically tackle the software perspective.
- [Kanewala & Bieman (2014)](https://doi.org/10.1016/j.infsof.2014.05.006): shows scientists are typically not trained in software testing, and 
testing scientific software comes from cultural and technical challenges.

I have seen the same 2 reasons Kanewala & Bieman (2014) mention in the industry:

1. **Cultural.** OR scientists are not trained in software engineering, and often do not believe they should be or are not aware of the benefits.
2. **Technical.** Designing decision-support software is difficult: it has challenges that ordinary business software does not.

What are the consequences of poorly engineered software?

- Code that works on one machine but is difficult to reproduce elsewhere.
- Systems that are difficult for peers, and even for their original authors, to maintain or extend.
- Developers who are afraid of modifying the system, because the consequences are unpredictable.
- Applications that eventually need to be rewritten rather than evolved.

These are not mathematical problems. They are software engineering problems.

> 💡 **The business value of the decision-support project investment is constrained by the software used to deliver it.**

---

## Can't AI agents solve this?

AI coding assistants are already the default. A 2026 study of scientific programmers reports that more than 70% now write code with
LLM-based tools ([O'Brien & Eisty, 2026](https://www.computer.org/csdl/magazine/cs/2026/01/11482007/2fJHVugY5UY)). **But they do not
replace engineering practices.**

The [2025 DORA report](https://dora.dev/research/2025/dora-report/) found that an AI coding assistant's _"primary role in software
development is that of an amplifier"_: it amplifies the strengths and the weaknesses of the practices already around it.

- Teams with strong engineering practices move faster at good quality.
- Teams without them ship more software with higher technical debt.

Most OR teams are already working with coding agents, which means the amplifier is already switched
on. That is the reason the practices below matter now, not a reason to postpone them.

> 💡 **Solid engineering practices are the prerequisite for capturing value from agentic development.**

---

## What is SEFOP?

What would software engineering look like if we adapted it deliberately around the needs of applied operations research? The answer is
**SEFOP**, a framework specifically designed for this task. It is built to help OR teams move from _"we built a model that works today"_ to
_"we built a system that can be deployed, maintained, and evolved efficiently over time"_.

<p align="center">
  <img src="https://raw.githubusercontent.com/sefop/.github/main/assets/sefop-framework.png"
       alt="SEFOP framework: Train Skills, Lead Culture, Deliver Engineering, Go Agentic AI" width="900">
</p>

SEFOP develops capability across four dimensions. Three of them build on each other. The fourth multiplies whatever the other three
produce:

- **Train — skills.** Material to train operations research scientists and data science managers in the practices of software engineering.
- **Lead — culture.** How to staff and lead a team that builds decision-support software.
- **Deliver — engineering.** Examples of how professional decision-support software looks like, as working reference implementations.
- **Go agentic — AI.** How to use AI coding assistants on this class of software to maximize the business value.

---

## Who maintains SEFOP

I'm [Francisco Zenteno Smith](https://www.linkedin.com/in/francisco-zenteno-smith/), and I build and maintain SEFOP. The framework
comes out of building decision-support software in practice, not out of a literature survey.

### Presented

- **INFORMS Annual Meeting**, Oct 2025, Atlanta
  *ATOM: Automated Testing for Optimization Models*
- **MIP Workshop**, Dec 2025, Chile
  *Deploying Optimization Models with Confidence: Automatic Testing for Optimization Models*
- **Agentic Quality Summit**, May 2026, Atlanta
  *Faster Delivery through Higher Quality in Decision-Support Software*

### Upcoming

- **AGIFORS Annual Symposium**, Oct 2026, Istanbul
  *Rethinking the Embedded OR Team as a Software Factory*
- **DSI Annual Conference**, Nov 2026, San Francisco
  *Why Operations Research Practitioners Resist Software Engineering Practices and What Changes Their Behavior*
- **INFORMS Annual Meeting**, Nov 2026, San Francisco
  *SEFOP: A Software Engineering Framework for Optimization Programs*

---

## Resources: where to start

SEFOP is developed as an open collection of **training material, reference implementations, and tools**. Start from your situation
rather than from the framework:

| If you… | Start here                                                                                                                                                                                                                                       |
|---|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **write the models** | [sefop-training-hub](https://github.com/sefop/sefop-training-hub) — learn and practice software engineering in the context of decision-support software                                                                                          |
| **lead the team that writes them** | [sefop-training-hub/lead](https://github.com/sefop/sefop-training-hub/tree/main/lead) — how to staff and lead a team building decision-support software                                                                                          |
| **are starting a new project** | [sefop-python-starter](https://github.com/sefop/sefop-python-starter) · [`sefop-python-advanced`](https://github.com/sefop/sefop-python-advanced) · [`sefop-java-advanced`](https://github.com/sefop/sefop-java-advanced) *(under construction)* |
| **use AI coding agents on this work** | [sefop-agentic](https://github.com/sefop/sefop-agentic) — guides and tools for agentic development                                                                                                                                               |

---

## Community: how to take part

SEFOP is an open initiative, shaped by real decision-support software development experience. **I want it shaped by yours too.**
If you have ideas to share, please **[join the discussion](https://github.com/orgs/sefop/discussions)**.

Contributions are welcome: new practices, ideas, reference implementations, and implementations in additional languages.

---

## License

MIT. See [LICENSE](https://github.com/sefop/.github/blob/main/profile/LICENSE).
