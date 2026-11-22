<div align="center">

# AI Interview Simulator
### Adaptive interview practice built around evidence, not generic scores

**Software Engineering · Conversational AI · Product Design**

[← Back to GitHub profile](../README.md) · [See all selected projects](README.md)

</div>

---

> **Portfolio case study.** The implementation repository is private. This page shares only a high-level product description, without publishing source code or sensitive technical configuration.

## The idea

Most basic interview practice tools generate a fixed set of questions. This project explores an alternative: interviews that respond to a candidate's experience and answers, then explain the evidence supporting their evaluation.

## Experience being designed

1. **Start with context** — use a résumé and job description to understand the role and candidate.
2. **Create a competency plan** — choose the skills and experiences the interview should investigate.
3. **Conduct an adaptive interview** — support text and real-time voice interaction, with follow-up questions when needed.
4. **Evaluate evidence** — distinguish skills that were actually tested from those not yet discussed.
5. **Provide feedback** — summarize observed strengths, gaps, and areas to practice.

This is an **in-development project**, and these steps describe its design and engineering goals rather than a claim of a universally available production service.

## Engineering focus

| Area | Approach |
| --- | --- |
| **Application** | Web-based interview experience |
| **Frontend** | Next.js / React / TypeScript |
| **Data** | PostgreSQL-based persistence |
| **Conversation** | AI-assisted question selection and evaluation |
| **Interaction** | Text and voice workflow design |
| **Reliability** | Explicit interview state, reproducible decisions, and traceable evaluation evidence |

## What makes the problem interesting

- A useful interview needs to **react** to answers rather than read from a list.
- Unasked questions should **not** be treated as evidence of weak performance.
- AI-generated feedback is more useful when a reviewer can trace it to what was actually said.
- The application needs to control session state even when external AI or voice services are involved.

## Availability

**Source code:** Private.  
**Public demo:** Not linked here; availability can be discussed directly.  
**Project discussion:** [Contact me](mailto:nizaryousef01@gmail.com).

---

<sub>High-level portfolio overview only. No private source files or API credentials are shared.</sub>
