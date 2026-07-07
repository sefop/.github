# SEFOP — Software Engineering Framework for Optimization Programs

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Discussions](https://img.shields.io/badge/GitHub-Discussions-9b59b6?logo=github)](https://github.com/orgs/sefop/discussions)

---

## What is SEFOP?

SEFOP is a framework that brings software engineering techniques (architecture, design, testing, CI/CD) to optimization software (also known as decision-support software).

### The problem
I built it out of a recurring frustration: decision-support software is rarely written with professional software standards. It may lack modularity, automated tests, deployment pipelines or all of them. Some consequences are:
- It may work on your machine, but it may not on another one. 
- It is difficult to maintain and extend by your peers and even by yourself.

### Root causes
The lack of profesional software standards in decision-support software problem has 2 root causes ([Kanewala & Bieman, 2014](https://pubmed.ncbi.nlm.nih.gov/25125798/)): 
1. Cultural: scientists are not trained in software engineering, and/or they think they should not learn it.
2. Technical: designing and testing this type of software has some unique challenges that are different from 'non-scientific' software.

### What if I use an agent?
AI-coding assistants are becoming very popular. In fact, as of 2025 > 70% of scientific programmers code with LLM-based tools according to [O'Brien & Eisty, 2026](https://www.computer.org/csdl/magazine/cs/2026/01/11482007/2fJHVugY5UY). Nonetheless, according to recent studies ([Google Cloud DORA 2025](https://dora.dev/research/2025/dora-report/)), we have learned that an AI-coding assistant "primarly role in software development is that of an amplifier". In other words, these tools amplify the strengths and weaknesses of your engineering practices. If you have strong engineering practices, you will capture the benefits of them. If you don't, you will "likely have a hard time".

### Goals of SEFOP
SEFOP addresses the previous problems with these 3 goals:
1. Provide you training materials so you can learn software engineering specifically for decision-support software. 
2. Provide you code templates to set the right technical foundations for your decision-support software.
3. Prepare your decision-support software to benefit from agentic development.

### Where has this been presented?
SEFOP has been presented at:
- Informs Annual Meeting 2025 (Atlanta, GA)
- MIP Workshop 2025 (Chile)
- Agentic Quality Summit 2026 (Atlanta, GA)
- Informs Annual Meeting 2026 (San Francisco, CA) - to be presented

### Connect with me
- https://www.linkedin.com/in/francisco-zenteno-smith/

## Who is this for?

SEFOP is designed for two audiences:

- **Academy**: graduate students, postdocs or professors who write optimization code and want to adopt software engineering practices without having a formal SE background.
- **Industry**: operations research practitioners who already know some elements of software engineering and want a structured guide to level-up their code with production-software standards.

The repositories in this organization are designed as a learning path. Start where you are.


## Learning Path

The repositories in this organization are structured as a progression:

### 1. [`sefop-python-starter`](https://github.com/sefop/sefop-python-starter)
**Start here if you are new to software engineering.**

A CLI-based Python implementation focused purely on modularity and testing — no web infrastructure, no deployment complexity. You bring an optimization problem; SEFOP gives you the scaffold to build it right.

### 2. [`sefop-python-advanced`](https://github.com/sefop/sefop-python-advanced)
**Move here when you are ready for production infrastructure.**

A full-stack Python implementation with a web application layer, CI/CD configuration, suggested architecture and software design. This is what a production-grade optimization system could look like.

### 3. [`sefop-training-hub`](https://github.com/sefop/sefop-training-hub)
**Use this as your guided path through both.**

Exercises, tutorials, and worked examples that walk you through the SEFOP concepts in sequence, referencing the starter and advanced repos as you go.

## Roadmap

**Phase 1 — Python** *(in progress)*
Deliver `sefop-python-starter`, `sefop-python-advanced`, and populate `sefop-training-hub` with foundational content.

**Phase 2 — Java**
Release `sefop-java`, bringing the same framework to JVM-based optimization stacks (Xpress, CPLEX, Gurobi via Java APIs).

**Phase 3 — Agentic Patterns**
Document how SEFOP's structure and test coverage enable safe agentic development workflows — where AI coding agents can contribute to optimization codebases reliably because the guardrails exist.


## Join the Discussion

SEFOP is in active development. The framework is being shaped by real deployment experience, and I want it to be shaped by yours too.

If you work with optimization software — whether you are a data scientist frustrated with brittle scripts, an OR engineer trying to bring rigor to your team's codebase, or a researcher interested in the methodology — **[join the discussion](https://github.com/orgs/sefop/discussions)**.

That is where the community lives. Contributions, new patterns, and new language implementations will grow from there.


## License

MIT — see [LICENSE](LICENSE).
