# Claude Certified Architect – Foundations: Exam Prep Guide

## About This Guide
This guide is compiled from a detailed Q&A thread analyzing exam-style questions for the **Claude Certified Architect – Foundations** certification. It breaks down multi-agent architectures, context management, tool design, and batch processing principles, focusing heavily on architectural tradeoffs and best practices over raw prompt engineering.

## How the Exam Works
The Claude Architect Foundations exam tests your ability to design resilient, production-ready AI systems. It consists of scenario-based multiple-choice questions focusing. The exam prioritizes structural, deterministic solutions (like schema design and tool boundaries) over probabilistic approaches (like prompt instructions). 

## Scenarios Covered
This guide covers core architectural scenarios you are likely to encounter, including:
- **Agentic Architectures**: Subagent spawning, parallelism, and workflow decomposition.
- **Context Management**: Mitigating "lost in the middle" effects, context bloat, and preserving provenance through summarization.
- **Tool & Schema Design**: Enforcing business rules, standardizing outputs, and designing machine-readable identifiers for tool chaining.
- **Batch Processing & State**: Resuming crashed sessions, optimizing SLA buffers, and handling partial batch failures.

---

## Practice Quiz

An interactive quiz covering 50 questions.

To open it:
```
open quiz.html
```
Or drag `quiz.html` into any browser. It tracks your score, shows explanations after each answer, and reviews missed questions at the end.

---