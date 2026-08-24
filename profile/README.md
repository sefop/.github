# SEFOP — Software Engineering Framework for Optimization Programs

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Discussions](https://img.shields.io/badge/GitHub-Discussions-9b59b6?logo=github)](https://github.com/orgs/sefop/discussions)

---

## What is SEFOP?

SEFOP stands for Software Engineering Framework for Optimization Programs. It is a framework that brings modern software engineering techniques to decision-support 
systems.

## What is a Decision-Support System?

A Decision-support system (DSS) is a **software** that supports business or organizational **decision-making activities**. A DSS can help in operational, tactical, and 
strategic decisions, and is typically **executed at some frequency**, such as daily, weekly, or monthly. Some examples problems that can be solved with a DSS 
include:
- Planning the annual extraction of resources from a mine.
- Scheduling the monthly shift schedules of a retail store.
- Planning the weekly delivery of cargo across a network.
- Recovering the daily operation from a weather disruption in an airline.

Typically, a DSS is developed to some extent by engineers specialized in decision science: operations research scientists. In fact, [Operations Research](https://en.
wikipedia.org/wiki/Operations_research) (OR) is the branch of applied mathematics that specializes in better decision-making.

A DSS is not a one-off consulting project, but a system that needs to be developed, maintained, and improved with modern and professional engineering practices as any
other software system to maximize its business value. Some of these practices include:
- Version control
- Software design & architecture
- Automated testing
- DevOps

## So... what is the problem?
DSS is rarely written with full professional software standards. Some consequences are:
- It may work on your machine, but it may not on another one. 
- It is difficult to maintain and extend by your peers and even by yourself.
- It may generate anxiety or fear to modify it.
- It may need to be re-written due to its difficulty to maintain.

The practical consequence of these problems is what happens to any software with these characteristics: the return on investment does not reach its full potential.

## Root causes
The lack of professional software standards in DSS problem has 2 root causes ([Kanewala & Bieman, 2014](https://pubmed.ncbi.nlm.nih.gov/25125798/)): 
1. Cultural: OR scientists are not trained in software engineering, and/or they think they should not learn it.
2. Technical: designing and testing this type of software has some unique challenges that are different from 'non-scientific' software.

## What if I use an agent to solve these problems?
AI-coding assistants are becoming very popular. In fact, as of 2025 > 70% of scientific programmers code with LLM-based tools according to [O'Brien & Eisty, 2026](https://www.computer.org/csdl/magazine/cs/2026/01/11482007/2fJHVugY5UY).
Nonetheless, according to recent studies ([Google Cloud DORA 2025](https://dora.dev/research/2025/dora-report/)), we have learned that an AI-coding assistant 
"**primarly role in software development is that of an amplifier**". In other words, these tools amplify the strengths and weaknesses of your engineering practices. If 
you have strong engineering practices, you will capture the benefits of them. If you don't, you will "**likely have a hard time**". Thus, as a prerequisite to leverage
AI-coding assistants value, you need to invest in professional practices first.

## How does SEFOP help
SEFOP addresses the previous problems by setting its foundations in 4 pillars:
1. Show you how to **Teach** you and your science team software engineering practices specifically for DSS.
2. Show you how to **Lead** your team of scientists and developers.
3. Show you how to **Deliver** professional software with moder software engineering standards.
4. Show you how to **Go Agentic** to leverage the benefits of AI-assistant coding tools after you have the proper practices in place.

## Where has this been presented?
SEFOP (or aspects of it) has been presented or is going to be presented at:
- Informs Annual Meeting - Nov 2026 (San Francisco, CA) - to present the latest version of the technical framework: *“SEFOP: a Software Engineering Framework for Optimization Programs"*.
- DSI Annual Conference - Nov 2026 (San Francisco, CA) - to present a paper of change management: *"Why operations research practitioners resist software engineering practices and what changes their behavior"*.
- Agentic Quality Summit - May 2026 (Atlanta, GA)
- Informs Annual Meeting - Oct 2025 (Atlanta, GA)
- MIP Workshop - Dec 2025 Chile

## Who is this for?

SEFOP is designed for three personas:

- **Academy**: graduate students, postdocs or professors who write optimization code and want to adopt software engineering practices without having a formal SE background.
- **Industry**:
  - Operations research practitioners who already know some elements of software engineering and want a structured guide to level-up their code with professional standards.
  - Engineering managers who are responsible for delivering decision-support software with professional standards.

## Resources available

The repositories in this organization are structured in 3 types:
- Training: help you practice and/or learn software engineering techniques, tailored for scientists.
- Templates: show you an implementation of SEFOP that you could mimick or use as a starting point.
- Agentic layer: provide you a set of tools to incorporate agentic development in your project.

### Training repositories

Everything related to training is here: [`sefop-training-hub`](https://github.com/sefop/sefop-training-hub).

### Template repositories

SEFOP has some reference implementations of the framework in different languages and depth. Currently, it has:
- SEFOP in python (starter version): https://github.com/sefop/sefop-python-starter
- SEFOP in python (advanced version): https://github.com/sefop/sefop-python-advanced
- SEFOP in java (advanced version): https://github.com/sefop/sefop-python-advanced (under construction)

### Agentic layer

This repository will have guides and tools to leverage agentic development: https://github.com/sefop/sefop-agentic

## Join the Discussion

SEFOP is in active development. The framework is being shaped by real deployment experience, and I want it to be shaped by yours too. If you work with 
optimization software — whether you are a data scientist frustrated with brittle scripts, an OR engineer trying to bring rigor to your team's codebase,
or a researcher interested in the methodology — **[join the discussion](https://github.com/orgs/sefop/discussions)**.

That is where the community lives. Contributions, new patterns, and new language implementations will grow from there.

## License

MIT — see [LICENSE](LICENSE).

## Connect with me
https://www.linkedin.com/in/francisco-zenteno-smith/
