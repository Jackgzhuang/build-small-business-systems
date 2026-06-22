# Build Small Business Systems

This is a public Build in Public project about turning real small-business problems into practical systems.

It is not a portfolio of completed software products. It documents problems observed through real conversations with founders and small business owners, the thinking used to understand them, and the solutions that may follow.

Not every case will reach implementation. Some may remain at the analysis or system-design stage, and their status will be shown plainly.

## Why This Repository Exists

Small businesses often do not have a software problem first. They have an operational bottleneck:

- Too many decisions depend on the founder
- Leads are not followed up consistently
- Calls and customer requests are missed
- Customer information is difficult to manage
- Booking and approval workflows are unclear
- Important processes exist only in people's heads

The most valuable skill is identifying the bottleneck. Software is one possible implementation layer.

## The Journey

Each case can move through the following stages:

```text
Business Problem
       ↓
Analysis
       ↓
System Design
       ↓
MVP
       ↓
Implementation
       ↓
Results
```

Progress is not assumed. The current state of every case is documented in its `status.md` file.

## What Each Case Explores

1. The business challenge
2. The observations and possible root causes
3. Potential system solutions
4. MVP ideas, when appropriate
5. Implementation and lessons learned, when they exist

## Cases

| Case | Current stage |
| --- | --- |
| [001 — Founder Decision Bottleneck](cases/001-founder-decision-bottleneck/) | Solution concept defined; no implementation yet |

New cases will be added only when there is a real observation or conversation to document.

## Repository Structure

```text
cases/       Real business problems and their evolving solutions
templates/   Reusable documentation templates
docs/        Repository-wide notes and supporting documentation
systems/     Early system concepts retained as the project evolves
```

A case normally begins with:

```text
problem.md
observations.md
possible-solution.md
status.md
```

If the work advances, it may also include `mvp/`, `screenshots/`, or `results/`.

## Integrity Principles

- Do not invent customers, projects, results, or case studies.
- Separate observations from assumptions.
- Label untested ideas as potential solutions.
- State clearly when no implementation or validation exists.
- Update results only when there is real evidence.

The goal is credibility through an honest record of the work.

## Long-Term Direction

Over time, some cases may evolve into working MVPs, open-source tools, consulting frameworks, client projects, or commercial products. This repository is intended to make that evolution visible—from identifying a business bottleneck to designing and implementing a useful system.
