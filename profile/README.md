# SEFOP — Software Engineering Framework for Optimization Programs

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Discussions](https://img.shields.io/badge/GitHub-Discussions-9b59b6?logo=github)](https://github.com/orgs/sefop/discussions)

> **A practical framework for building optimization software that is maintainable, testable, reproducible, and ready for production.**

Operations Research (OR) creates business value through decision-support software. Yet optimization programs are often developed with practices designed for one-off analysis rather than long-lived software systems.

**SEFOP brings software engineering practices into optimization development — from training and team leadership to software delivery and agentic development.**

<p align="center">
  <img src="assets/sefop-framework.png" alt="SEFOP framework: Train Skills, Lead Culture, Deliver Engineering, Go Agentic AI" width="900">
</p>

---

## The SEFOP framework

SEFOP is organized around four complementary capabilities:

| **TRAIN** | **LEAD** | **DELIVER** | **GO AGENTIC** |
|:---:|:---:|:---:|:---:|
| Skills | Culture | Engineering | AI |
| Build software engineering skills within optimization teams. | Establish team practices that support sustainable development. | Apply professional engineering practices to optimization software. | Use AI coding agents effectively on top of strong engineering practices. |

These capabilities span the journey from **people → teams → software → AI**.

---

## Why SEFOP?

Optimization software has characteristics that make its engineering challenges different from those of conventional applications. Mathematical formulations, algorithms, solvers, data, experimentation, and business rules all interact.

When these systems are developed without deliberate software engineering practices, common consequences include:

- Code that works on one machine but is difficult to reproduce elsewhere.
- Systems that are difficult for peers — and even their original authors — to maintain or extend.
- Changes that become risky because developers are afraid of breaking existing behavior.
- Optimization applications that eventually need to be rewritten rather than evolved.

The result is not simply technical debt. **The business value of the optimization investment is constrained by the software used to deliver it.**

---

## Optimization software is software

A decision-support system (DSS) is software that supports business or organizational decision-making. It may support operational, tactical, or strategic decisions and is often executed repeatedly — daily, weekly, monthly, or in response to disruptions.

Examples include:

- Planning the annual extraction of resources from a mine.
- Scheduling retail store shifts.
- Planning cargo flows across a transportation network.
- Recovering airline operations after a disruption.

These systems are often developed by Operations Research scientists and other decision-science practitioners.

A DSS is therefore **not a one-off consulting analysis**. It is a software system that needs to be developed, maintained, tested, deployed, and improved over time.

SEFOP applies engineering practices such as:

- Version control
- Software design and architecture
- Automated testing
- Continuous integration and delivery
- DevOps
- Reproducibility
- Modular development

while accounting for the specific needs of optimization software.

---

## Why not just use AI coding agents?

AI coding assistants can accelerate software development, but they do not replace engineering practices.

Recent software-engineering research describes AI coding tools as an **amplifier**: they can amplify both the strengths and weaknesses of the development practices around them.

If a team has strong engineering practices, AI can help it move faster while preserving quality. If those practices are weak, AI can also make it easier to produce more software that is difficult to understand, test, and maintain.

**SEFOP therefore treats strong engineering practices as the foundation for effective agentic development.**

---

## Who is SEFOP for?

### Academy

- Graduate students, postdocs, and professors who develop optimization software.
- Researchers who want to adopt software engineering practices without a formal software engineering background.

### Industry

- Operations Research practitioners who want a structured path toward professional software engineering practices.
- OR and data science teams responsible for production decision-support systems.
- Engineering managers responsible for delivering optimization software that can be maintained and evolved.

---

## What you'll find here

SEFOP is developed as an open collection of **training material, reference implementations, and tools**.

### TRAIN — Training

Learn and practice software engineering in the context of optimization and decision-support systems.

→ [`sefop-training-hub`](https://github.com/sefop/sefop-training-hub)

### DELIVER — Reference implementations

Reference implementations demonstrate how SEFOP practices can be applied in different languages and at different levels of maturity.

- Python — [starter](https://github.com/sefop/sefop-python-starter)
- Python — [advanced](https://github.com/sefop/sefop-python-advanced)
- Java — [advanced](https://github.com/sefop/sefop-java-advanced) *(under construction)*

### GO AGENTIC — Agentic development

Guides and tools for using AI coding agents in optimization software development.

→ [`sefop-agentic`](https://github.com/sefop/sefop-agentic)

### LEAD — Team practices

Guidance for leaders who want to establish sustainable software engineering practices within optimization teams.

---

## Where has SEFOP been presented?

SEFOP, or aspects of the framework, has been presented or is scheduled to be presented at:

- **INFORMS Annual Meeting — Nov 2026, San Francisco**  
  *SEFOP: A Software Engineering Framework for Optimization Programs*
- **DSI Annual Conference — Nov 2026, San Francisco**  
  *Why Operations Research Practitioners Resist Software Engineering Practices and What Changes Their Behavior*
- **Agentic Quality Summit — May 2026, Atlanta**
- **INFORMS Annual Meeting — Oct 2025, Atlanta**
- **MIP Workshop — Dec 2025, Chile**

---

## Join the discussion

SEFOP is an open and evolving framework shaped by real optimization software development experience.

If you work with optimization software — whether you are a researcher, an OR practitioner, a data scientist working with brittle code, or an engineering leader responsible for decision-support systems — **[join the discussion](https://github.com/orgs/sefop/discussions)**.

Contributions, new practices, reference implementations, and additional language implementations are welcome.

---

## License

MIT — see [LICENSE](LICENSE).

## Connect

[Francisco Zenteno Smith](https://www.linkedin.com/in/francisco-zenteno-smith/)
