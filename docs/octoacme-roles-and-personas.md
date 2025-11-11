```markdown
# OctoAcme Personas (updated)

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
This update expands supporting roles and clarifies interactions to reduce handoff ambiguity and improve accountability.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Testing

(unchanged—ensure QA remains responsible for validating acceptance criteria and release verification)

---

## New / Clarified Personas

### UX Designer
- Role Summary: Owns user experience and interaction design for features; ensures usability and accessibility goals are met.
- Responsibilities:
  - Create user flows, wireframes, and interactive prototypes
  - Run lightweight usability testing and synthesize feedback
  - Produce design acceptance criteria for features
  - Advocate for accessibility and consistency with design system
- Interaction:
  - Works with Product Managers to refine requirements and success criteria
  - Collaborates with Developers to ensure feasibility and with QA on usability verification
  - Presents design reviews to stakeholders

### Business Analyst (BA)
- Role Summary: Translates stakeholder needs into clear, testable requirements and acceptance criteria.
- Responsibilities:
  - Capture and structure functional and non-functional requirements
  - Map business processes and edge cases
  - Ensure acceptance criteria are specific and testable
  - Assist with user-acceptance test (UAT) planning
- Interaction:
  - Bridges Product and Project Managers with delivery teams
  - Works with Developers and QA to clarify scope and test scenarios
  - Escalates ambiguous requirements to PdM for decisions

### Scrum Master
- Role Summary: Facilitates the team’s agile process, helps remove impediments, and fosters continuous improvement.
- Responsibilities:
  - Run sprint ceremonies (planning, standup, retrospective)
  - Coach team on agile practices and team health
  - Monitor team flow and help remove blockers
  - Maintain team-level process documentation and metrics
- Interaction:
  - Works closely with Project Manager, Developers, QA, and PdM
  - Escalates systemic process issues to leadership when needed
  - Coordinates improvements from retrospectives

### Support Engineer (Post-release / Ops-facing)
- Role Summary: First responder for post-release issues and user-facing incidents; ensures feedback loops into backlog.
- Responsibilities:
  - Triage production incidents and user reports
  - Reproduce, classify, and prioritize issues with PdM/PM
  - Prepare incident context, logs, and reproduction steps for devs
  - Track and confirm fixes, and update post-release notes
- Interaction:
  - Communicates with QA and Developers for bug verification and fixes
  - Feeds recurring issues and telemetry into the Product backlog

---

## Role Interaction Guidance

- Clear owners: each artifact (one-pager, risk item, backlog item, release checklist, retrospective actions) should have a named owner.
- Handoff pattern: requirement capture (PdM/BA) → design (UX) → implementation (Dev) → test (QA) → release (PM/Support).
- Escalation: team → Scrum Master/PM → Product Lead → Sponsor.
- When responsibilities overlap, name primary (R) and supporting (A/C) roles using a lightweight RACI entry on the artifact.

---

## How to use this doc
- Reference these personas when filling the "Proposed team / roles" section in the Project One-pager.
- Add or update personas as team needs evolve; record changes in the doc's changelog.
```
