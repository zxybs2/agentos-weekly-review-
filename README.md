# AgentOS Weekly Work Review

This repository stores the **Weekly Work Review system** for AgentOS / ITCubed.

---

## Purpose

The Weekly Work Review is the **weekly business / operations / strategy correction layer** for AgentOS and ITCubed. It runs every week to assess direction, find improvement opportunities, review ideas, and generate a concrete next-week action plan.

---

## What This Repo Is — and What It Is Not

| Layer | Repo / System | Source of Truth For |
|---|---|---|
| **Weekly Work Review** | This repo | Weekly strategic correction, AI industry pulse, business direction review, repeated-work automation review, idea review, next-week action planning |
| **Live State** | Live State system | Current project facts, active client status, team state |
| **Engineering Sequencing** | Engineering Sequencing system | Execution order, sprint priority, task queue |

**This repo does NOT replace Live State or Engineering Sequencing.**

- **Live State** remains the source of truth for project facts.
- **Engineering Sequencing** remains the source of truth for execution order.
- **Weekly Work Review** provides the weekly strategic correction loop above those layers.

---

## What Weekly Work Review Covers

1. **AI Industry Pulse** — Scan Anthropic / Claude, OpenAI / ChatGPT, Microsoft / M365 / Copilot, MSP AI, and Security AI competitive movement. Assess impact and whether direction needs adjustment.
2. **Business Direction Review** — Reflect on the prior work week: what was completed, what created value, what drained energy, what new opportunities appeared, what risks exist.
3. **Repeated-Work SOP / Automation / Agentization Analysis** — Identify manual, repeated work and determine what to SOP, script, or agentize.
4. **Idea Review** — Surface and evaluate ideas by business value, execution cost, risk, and long-term meaning.
5. **Wrap: Weekly Summary and Next-Week Action Guide** — Consolidate findings into a prioritized next-week action plan.

---

## File Format

- **Markdown (.md) files are the editable source-of-truth documents.**
- DOCX / PDF exports are generated only when needed and placed under `exports/`.
- Do not edit DOCX or PDF files directly. Always edit the Markdown source.

---

## Directory Structure

```
agentos-weekly-review-/
  README.md                          <- This file
  templates/
    weekly-work-review-template.md   <- Reusable weekly review template
  reviews/
    YYYY/
      YYYY-MM-DD-weekly-work-review.md  <- Completed weekly reviews
  exports/
    docx/                            <- DOCX exports (generated on demand)
    pdf/                             <- PDF exports (generated on demand)
  assets/                            <- Supporting assets (diagrams, screenshots, etc.)
```

---

## File Naming Convention

Weekly review files are named by the **Monday review date** (not the prior Friday):

```
reviews/YYYY/YYYY-MM-DD-weekly-work-review.md
```

Example:

```
reviews/2026/2026-05-25-weekly-work-review.md
```

---

## Security Notice

> **No secrets, API keys, client secrets, tokens, or credential values should ever be committed to this repository.**

This repo is for strategic review documents only. All sensitive credentials must remain in secure credential management systems.

---

## Reviewer

- **Reviewer:** Jason Huang
- **Review Assistant:** Claude / ChatGPT
- **Organization:** AgentOS / ITCubed
