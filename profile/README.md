# SEFOP: Software Engineering Framework for Optimization Programs

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Discussions](https://img.shields.io/badge/GitHub-Discussions-9b59b6?logo=github)](https://github.com/orgs/sefop/discussions)

> **A practical framework for building decision-support software that is maintainable, testable, deployable, and ready for production.**

Operations Research (OR) creates business value by helping organizations make better decisions. That value is delivered through
**decision-support software**: software that runs repeatedly to turn data, mathematical models, and business rules into recurring business decisions.

SEFOP brings software engineering practices into the development of that software, from training and team leadership to software
delivery and agentic development.

---

## Contents

- [Context: what are we building?](#context-what-are-we-building)
- [Why: what goes wrong, and why?](#why-what-goes-wrong-and-why)
- [Can't AI agents solve this?](#cant-ai-agents-solve-this)
- [What is SEFOP?](#what-is-sefop)
- [Resources: how to apply it](#resources-how-to-apply-it)
- [Community: how to take part](#community-how-to-take-part)
- [License](#license)
- [Connect](#connect)

---

## Context: what are we building?

Decision-support software turns data, mathematical models, and business rules into decisions. It may support operational, tactical, or strategic
decisions, and unlike a one-off analysis it is designed to run repeatedly.

Examples include:

- Planning the **annual** extraction of resources from a mine.
- Scheduling the **monthly** shift schedules of a retail store.
- Planning the **weekly** delivery of cargo across a transportation network.
- Recovering the **daily** operation from a weather disruption in an airline.

These systems are often developed by Operations Research scientists and other decision-science practitioners. Because decision-support 
software runs on a cadence rather than ending at a deliverable, it must be maintained, tested, deployed, reproduced, and evolved. 

> [!NOTE]
> The value is not in producing one analysis. It is in building a sustainable decision-making tool.

---

## Why: what goes wrong, and why?

Decision-support software usually has poor software engineering practices, specially the elements surrounding the applied mathematics. This gap has been
documented and has 2 root causes ([Kanewala & Bieman, 2014](https://pubmed.ncbi.nlm.nih.gov/25125798/)):

1. **Cultural.** OR scientists are not trained in software engineering, and often do not believe they should be.
2. **Technical.** Designing and testing this class of software poses challenges that non-scientific software does not.

What are the consequences of poorly designed software?:

- Code that works on one machine but is difficult to reproduce elsewhere.
- Systems that are difficult for peers, and even for their original authors, to maintain or extend.
- Developers are afraid of modifying the system due to unexpected consequences.
- Applications eventually need to be completely rewritten rather than evolved.

These are not mathematical problems, these are software engineering problems.

> [!NOTE]
> The business value of the decision-support software investment is constrained by the software used to deliver it.

---

## Can't AI agents solve this?

AI coding assistants are already the default. As of 2025, more than 70% of scientific programmers write code with LLM-based tools
([O'Brien & Eisty, 2026](https://www.computer.org/csdl/magazine/cs/2026/01/11482007/2fJHVugY5UY)). **But they do not replace engineering practices**.

The [2025 DORA report](https://dora.dev/research/2025/dora-report/) found that an AI coding assistant's _"primary role in software development 
is that of an amplifier"_: it amplifies the strengths and the weaknesses of the practices already around it. 
- Teams with strong engineering practices move faster while holding quality.
- Teams without them ship more software that is hard to understand, test, and maintain.

> [!NOTE]
> Solid engineering practices are the prerequisite for capturing value from agentic development.

---

## What is SEFOP?

What would software engineering look like if we adapted it deliberately around the needs of applied operations research? The answer is **SEFOP**, 
a framework specifically for this task. It is built to help OR teams move from _"we built a model that works today"_ to _"we built a system that 
can be deployed, maintained, and evolved efficiently over time"_.
SEFOP has 4 pillars:

<p align="center">
  <img src="https://raw.githubusercontent.com/sefop/.github/main/assets/sefop-framework.png"
       alt="SEFOP framework: Train Skills, Lead Culture, Deliver Engineering, Go Agentic AI" width="900">
</p>

SEFOP develops capability across four dimensions, spanning the journey from **people → teams → software → Agentic-development**.

What are the goals of each pillar?:
- **Train**: provide you materials to train operations research scientists in best practices of software engineering.
- **Lead**: show you how you should staff and lead a team building decision-support software.
- **Deliver**: show you examples of how a professional decision-support software looks like.
- **Go agentic**: show you how you can leverage AI-coding assistants to maximize the value of your decision-support software.

---

## Resources: how to apply it

SEFOP is developed as an open collection of **training material, reference implementations, and tools**.

### Training

Learn and practice software engineering in the context of decision-support software.

→ Look into this repository: [`sefop-training-hub`](https://github.com/sefop/sefop-training-hub)

### Lead

How should you staff your team building a decision-support software, and how to lead it?

→ Look into this section of this repository: [`sefop-training-hub`](https://github.com/sefop/sefop-training-hub/tree/main/lead)

### Deliver

Reference implementations demonstrate how SEFOP practices can be applied in different languages and at different levels of maturity.

- [Python starter](https://github.com/sefop/sefop-python-starter)
- [Python advanced](https://github.com/sefop/sefop-python-advanced)
- [Java advanced](https://github.com/sefop/sefop-java-advanced) *(under construction)*

### Go agentic

Guides and tools for using AI coding agents in decision-support software development.

→ Look into this repository: [`sefop-agentic`](https://github.com/sefop/sefop-agentic)

---

## Community: how to take part

SEFOP is an open initiative, shaped by real decision-support software development experience.
**I want it shaped by yours too**.

If you have ideas to share, please **[join the discussion](https://github.com/orgs/sefop/discussions)**.

### Contribute

Contributions, new practices, reference implementations, and additional language implementations are welcome.

### Public presentations

SEFOP, or aspects of the framework, has been presented or is scheduled to be presented at:

- **INFORMS Annual Meeting**, Oct 2025, Atlanta  
  *ATOM: Automated Testing for Optimization Models*
- **MIP Workshop**, Dec 2025, Chile  
  *Deploying Optimization Models with Confidence: Automatic Testing for Optimization Models*
- **Agentic Quality Summit**, May 2026, Atlanta  
  *Faster Delivery through Higher Quality in Decision-Support Software*
- **AGIFORS Annual Symposium**, Oct 2026, Istanbul *(upcoming)*  
  *Rethinking the Embedded OR Team as a Software Factory*
- **DSI Annual Conference**, Nov 2026, San Francisco *(upcoming)*  
  *Why Operations Research Practitioners Resist Software Engineering Practices and What Changes Their Behavior*
- **INFORMS Annual Meeting**, Nov 2026, San Francisco *(upcoming)*  
  *SEFOP: A Software Engineering Framework for Optimization Programs*

---

## License

MIT. See [LICENSE](https://github.com/sefop/.github/blob/main/profile/LICENSE).

## Connect with me

I'm [Francisco Zenteno Smith](https://www.linkedin.com/in/francisco-zenteno-smith/), and I build and maintain SEFOP.
