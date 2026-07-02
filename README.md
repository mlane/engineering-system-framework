# Engineering System Framework

A living **meta-framework** for scaling clarity, consistency, and long-term alignment across engineering organizations.  
Designed to unify principles, rhythms, and documentation through a shared, evolving structure - adaptable to any company, any size.

This repository is a **blueprint**, not a prescription.  
It provides structure and language so organizations can define their systems - together.

> This framework does not replace existing documentation - it provides a focused space for shared decision frameworks, initiative tracking, and platform-specific guidance.

---

## What This Means

The ESF is a living framework that aligns how we **build**, **scale**, and **grow** - across domains, across time.  
It surfaces principles to the engineering level through three enduring pillars: Architecture & Systems, Framework & Cadence, and Chapters & Communication.  
It’s not a restart. It’s a reset - a system that remembers, so engineering stays visible, intentional, and durable.

---

## What’s Expected of Engineers

Engineers are expected to build with intent - not just code, but continuity.  
This means surfacing gaps, documenting decisions, and linking source as you work.  
You’re not just contributing - you’re shaping a system that lasts.

## Core Principles

✅ **Systems Over Silos** – Shared structure, localized ownership.  
✅ **Living Documentation** – Everything evolves through review, not decay.  
✅ **Consistency with Flexibility** – Guardrails, not gatekeeping.  
✅ **Simplicity Scales** – Fewer rules, stronger rhythm.  
✅ **Design for Security, Scalability, and Simplicity - not trends.**

**What “Living Documentation” means**  
Documentation is part of the system - not an afterthought.

Every meaningful change (to code, process, or principle) should update its corresponding doc in the same pull request.

This keeps truth centralized, prevents decay, and ensures the framework evolves as the organization does.

> The goal is not to dictate _how_ teams work, but to give them a clear, repeatable way to evolve their systems responsibly.

---

## Pillar Values

Each pillar in the Engineering System Framework is grounded in a single, shared-value quote - guiding how it operates and evolves:

- **Architecture & Systems**
  _“We design for security, scalability, and simplicity - not trends.”_
- **Framework & Cadence**
  _“We scale through rhythm, ownership, and principle - not process.”_
- **Chapters & Communication**
  _“We grow through shared learning, clarity, and visibility - not performance.”_

<img width="1536" height="1024" alt="6B92C537-39CE-4C69-9D21-DBF2199F2DD6" src="https://github.com/user-attachments/assets/117927ec-8a00-4fd8-aa58-fff18eab4e79" />

---

## Engineering Domains

The framework is designed to scale across any organization size or structure.
Most engineering orgs include some or all of the following domains, each connected through shared principles and rhythms.

> Note: In some orgs, DevOps and Infrastructure may operate as shared advisors across multiple domains rather than owning a standalone chapter. That’s fully valid - inclusion and representation can take many forms.

| Domain                        | Purpose                                                                                                           |
| ----------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| **AI / Machine Learning**     | Trains and serves intelligent models. Prioritizes inference quality, feedback loops, and responsible safety.      |
| **Backend (BE)**              | Manages APIs, integrations, and business logic. Prioritizes reliability, scalability, and maintainability.        |
| **Data**                      | Handles analytics, pipelines, and warehousing. Ensures accuracy, lineage, and observability.                      |
| **Frontend (FE)**             | Builds user-facing interfaces and client logic for the web. Focuses on clarity, performance, and accessibility.   |
| **Mobile**                    | Delivers native app experiences across iOS and Android. Ensures parity and cohesion with the broader system.      |
| **Platform / Infrastructure** | Provides tooling, CI/CD, and operational reliability. Enables autonomy and system-wide consistency.               |
| **Security**                  | Protects systems, data, and user trust. Defines policies, audits risk, and reinforces safe development practices. |

> Not every company will have all domains - and that’s expected.
> The framework scales naturally: smaller teams start with a few, larger orgs formalize the rest over time.

---

## Team vs Chapter vs Domain

To reduce confusion, we explicitly distinguish between Domains (architectural boundaries), Chapters (shared learning rhythms), and Teams (execution contexts formed around effort).

| Term        | Purpose                                    | Participation                                    | Notes                                                                             |
| ----------- | ------------------------------------------ | ------------------------------------------------ | --------------------------------------------------------------------------------- |
| **Team**    | Executes scoped product or system outcomes | Dynamic contributors (EMs, PMs, ICs, Architects) | Formed around effort - not a fixed structural layer                               |
| **Domain**  | Defines technical ownership boundaries     | Domain Architect                                 | Used in systems, architecture, and cross-domain initiatives                       |
| **Chapter** | Drives community learning & visibility     | Chapter Lead or Domain Architect                 | Used for rituals like mini trainings, lightning talks, and shared practice growth |

> Teams move the work; Domains shape what we build; Chapters shape how we grow together.
> <img width="1536" height="1024" alt="3EC3D8E9-356C-46C2-A594-154B1E0AF760" src="https://github.com/user-attachments/assets/8a4a3c82-baa5-4649-9205-ed4d4d244f0b" />

---

## Engineering System Core

The following sections define the foundation of how Engineering aligns, evolves, and shares ownership across teams.

### 1. Principles & Direction

> We design for security, scalability, and simplicity - not trends.

This section defines the **engineering mindset** - the principles that guide how we build and evolve systems.
It focuses on clarity, maintainability, and sustainable growth.

**Core Tenets**

- **Stability first, novelty second.**
  Prioritize proven solutions that reduce friction and uncertainty.
- **Security, performance, scalability.**
  Every decision should strengthen at least one of these pillars.
- **Simplicity scales.**
  Minimize concepts, maximize clarity.
- **Team clarity matters.**
  If it’s hard to explain, it’s too complex.
- **Change must be justified.**
  Adopt new tools to solve real problems - not hypothetical ones.

**Decision Filters**

Before adopting a tool, process, or major shift, ask:

1. Does it solve a real pain today?
2. Does it improve security, performance, or scalability?
3. Is it maintainable long-term?
4. Can we test it safely in isolation first?
5. Will it be easy for others to learn and use?

> ✅ If three or more answers are “yes,” move forward.
> 🚫 Otherwise, reconsider.

**Architectural Role**

- Protect system health and clarity.
- Reduce unnecessary change.
- Lead validation and sandboxed experimentation.
- Empower others to build within safe boundaries.

> Architecture is not about control - it’s about continuity.

---

### 2. Initiatives & Ownership

Tracks key initiatives that advance the organization’s systems, visibility, and long-term health.
Each initiative is tied to a clear **owner**, **purpose**, and **review cadence** - but implementation details remain flexible.

| Initiative                              | Status      | Owner       | Domain(s) | Source               |
| --------------------------------------- | ----------- | ----------- | --------- | -------------------- |
| Dependency Health                       | In Progress | Marcus Lane | BE, FE    | https://{ticketLink} |
| ImageData Field Deprecation & Migration | In Progress | John Soon   | BE        | https://{ticketLink} |
| Observability Setup                     | In Progress | Marcus Lane | FE        | https://{ticketLink} |
| Standardization (Phase 1) – Style Guide | In Progress | Federico    | Mobile    | https://{ticketLink} |

> The table is a **living layer**, not a dashboard.
> Its purpose is to create accountability and visibility, not bureaucracy.

---

### 3. Gotchas & Migration Log

Captures significant engineering events, migrations, or unexpected issues that required architectural visibility or coordination.
This log helps teams understand _why_ a change happened - not just _what_ changed.

| Log                                                                             | Date             | Logged By   | Domain(s) |
| ------------------------------------------------------------------------------- | ---------------- | ----------- | --------- |
| Encoded GraphQL Responses (P39: [...]) in Remix                                 | November 6, 2025 | Marcus Lane | BE, FE    |
| React Router 7.6+ Introduced Stricter Type Enforcement on LoaderArgs/ActionArgs | November 6, 2025 | Marcus Lane | BE        |

Each entry should include:

- **Title**
- **Summary** (brief description of what happened)
- **Impact** (who or what was affected)
- **Resolution / Lesson Learned**
- **References** (links to Slack threads, PRs, or related docs)

> This log complements “Initiatives & Ownership.”
> Initiatives define planned evolution - the Gotchas & Migration Log records what we learned while evolving.

---

### 4. Health & Maintenance

Defines how organizations stay healthy over time - through maintenance, automation, and review.
It’s not about perfection; it’s about continuous, visible improvement.

- **Dependencies:** Review quarterly. Regular upgrades prevent drift and reduce the need for risky rewrites later.
- **Documentation:** Keep alive - update as part of normal work.
- **Audits:** Schedule semi-annually to catch drift or tech debt early.
- **Automation:** Use tools to enforce consistency and detect risk.

> Health is a rhythm, not an afterthought.

---

### 5. Visibility & Signals

Visibility defines what we track, how we ensure signal continuity across systems and teams, and how those signals lead to timely, actionable improvement.

A healthy system notices itself.
Visibility ensures that information flows from systems → people → decisions.

- **Error Monitoring:** Standardize alert formats and destinations.
- **Performance Metrics:** Track both technical and user-facing KPIs.
- **Ownership:** Every signal must trace to a responsible team.
- **Continuity:** Review signal noise quarterly; remove stale or redundant alerts.

> Visibility isn’t about blame - it’s about awareness and response.

---

### 6. Culture & Growth

Defines how learning, mentorship, and documentation work together to sustain team growth.

**Product-Minded Engineering**

Every engineer should think critically about _why_ something exists, not just _how_ it’s built.

- Ask questions early; clarify purpose and scope.
- Break projects into small, testable pieces.
- Deprioritize unnecessary polish (80/20 rule).
- Document uncertainty and seek clarity.
- Refactor when already in context - don’t defer small debt.

> We don’t just build code - we build systems that last.

**Shared Architectural Ownership**

Architecture is collective. Even with leads, everyone contributes to long-term structure.

- Every PR is a chance to remove debt or improve patterns.
- Every feature reinforces shared standards.
- Every engineer is empowered to propose improvements.

> Good architecture is invisible - it quietly improves velocity for everyone.

**Mentorship & Onboarding**

- Keep onboarding self-contained, up-to-date, and discoverable.
- Encourage pair sessions for cross-team learning.
- Capture insights as living documentation, not static wikis.

> Culture is the heartbeat of the system - maintain it like code.

**Shared Learning & Visibility**

Formats like **chapter meetings**, **rotations**, and **contribution logs** ensure shared learning stays visible and evenly distributed.
Mentoring and teaching are measured not by volume, but by consistency.

**Review Cadence**

- **Quarterly reviews** → Ensure relevance and alignment.
- **Bi-annual audits** → Reevaluate structure and evolution.
- **Async feedback encouraged** → Small, continuous improvements.
- **Architectural Council (bi-weekly)** → Aligns domain architect (e.g., BE, Data, FE, Mobile) on shared evolution and decisions.

> The system stays alive through rhythm, not ceremony.

---

### Architectural Hierarchy

To scale architectural clarity and ownership, the system defines three levels:

| Level        | Role                      | Scope & Focus                                                                                         |
| ------------ | ------------------------- | ----------------------------------------------------------------------------------------------------- |
| **Org-Wide** | **Architectural Council** | Aligns Domain Architects (e.g., BE, Data, FE, Mobile) on shared evolution and cross-domain decisions. |
| **Domain**   | **Domain Architect**      | Owns technical direction within a domain (e.g., BE, Data, FE, Mobile).                                |
| **Product**  | **Domain Council Member** | Supports architectural quality and direction within a specific product team.                          |

> This hierarchy ensures decisions scale from the ground up - while remaining aligned across Engineering.

---

## Architecture & Systems Layer

Defines how the shared framework translates into concrete systems - across domains (e.g., BE, Data, FE, Mobile).

- **Architect Compass:** How we evaluate tradeoffs and balance constraints.
- **Dependency Health & Deployment:** Safe, maintainable, and automated release cycles.
- **Tooling & Terminology:** Shared language for cross-domain communication.
- **Visibility & Alerting:** Consistent observability practices across domains.
- **Glossary:** Common definitions for clarity across Engineering.

Each subfolder (`/ai`, `/be`, `/data`, `/fe`, `/mobile`, `/platform`, `/security`) extends these standards without redefining the principles.

---

## Chapters Layer

Holds team-level rhythm and communication artifacts - not formal documentation.

Each chapter includes:

- **Meeting Notes** - Lightweight documentation of discussions and decisions.
- **Rotations** - Each engineer is expected to give one Lightning Talk and one Mini Training per year. Chapters own the rotation and timing.
- **Signups** - Signup sheets live in each chapter and are linked in `meeting-format-and-talk-signups.md`.
- **Contribution Logs** - Each chapter maintains a log of engineer talks to support fair rotation - helping avoid back-to-back scheduling and keeping the rhythm healthy.

A separate **Leadership Rotation** complements this system. Instead of joining all seven chapters, executives (e.g. CEO, President, Product, Growth, Engineering) rotate into a single shared sync - bringing alignment without repetition.

> Chapter learning is local. Executive rhythm is shared. Both matter.

---

## Structure Overview

This structure shows one working example of a fully scaffolded ESF system.

```bash
engineering/
├── index.md
├── chapters/
│   ├── index.md
│   ├── ai/
│   │   ├── index.md
│   │   ├── meeting-notes/
│   │   ├── roster-and-contribution-logs
│   │   └── talk-signups.md
│   ├── backend/
│   │   ├── index.md
│   │   ├── meeting-notes/
│   │   ├── roster-and-contribution-logs
│   │   └── talk-signups.md
│   ├── data/
│   │   ├── index.md
│   │   ├── meeting-notes/
│   │   ├── roster-and-contribution-logs
│   │   └── talk-signups.md
│   ├── frontend/
│   │   ├── index.md
│   │   ├── meeting-notes/
│   │   ├── roster-and-contribution-logs
│   │   └── talk-signups.md
│   ├── mobile/
│   │   ├── index.md
│   │   ├── meeting-notes/
│   │   ├── roster-and-contribution-logs
│   │   └── talk-signups.md
│   ├── platform/
│   │   ├── index.md
│   │   ├── meeting-notes/
│   │   ├── roster-and-contribution-logs
│   │   └── talk-signups.md
│   └── security/
│       ├── index.md
│       ├── meeting-notes/
│       ├── roster-and-contribution-logs.md
│       └── talk-signups.md
│
├── architecture/
│   ├── index.md
│   ├── architect-compass.md
│   ├── council.md
│   ├── data-tracking-and-flow/
│   │   ├── index.md
│   │   ├── ai.md
│   │   ├── be.md
│   │   ├── data.md
│   │   ├── fe.md
│   │   ├── mobile.md
│   │   ├── platform.md
│   │   └── security.md
│   ├── dependency-health-and-deployment/
│   │   ├── index.md
│   │   ├── ai.md
│   │   ├── be.md
│   │   ├── data.md
│   │   ├── fe.md
│   │   ├── mobile.md
│   │   ├── platform.md
│   │   └── security.md
│   ├── glossary.md
│   │   ├── index.md
│   │   ├── ai.md
│   │   ├── be.md
│   │   ├── data.md
│   │   ├── fe.md
│   │   ├── mobile.md
│   │   ├── platform.md
│   │   └── security.md
│   ├── performance/
│   │   ├── index.md
│   │   ├── ai.md
│   │   ├── be.md
│   │   ├── data.md
│   │   ├── fe.md
│   │   ├── mobile.md
│   │   ├── platform.md
│   │   └── security.md
│   ├── tooling-and-terminology/
│   │   ├── index.md
│   │   ├── ai.md
│   │   ├── be.md
│   │   ├── data.md
│   │   ├── fe.md
│   │   ├── mobile.md
│   │   ├── platform.md
│   │   └── security.md
│   └── visibility-and-alerting/
│       ├── index.md
│       ├── ai.md
│       ├── be.md
│       ├── data.md
│       ├── fe.md
│       ├── mobile.md
│       ├── platform.md
│       └── security.md
│
├── framework/
│   ├── index.md
│   ├── culture-and-growth.md
│   ├── engineering-support-directory.md
│   ├── engineering-training-material.md
│   ├── initiatives-and-ownership.md
│   ├── meeting-format-and-talk-signups.md
│   ├── mentoring-corner.md
│   ├── migration-log.md
│   ├── review-cadence.md
│   └── principles-and-direction.md
```

---

© 2026 Marcus Lane.
Shared under the Creative Commons Attribution–NonCommercial 4.0 International License (CC BY-NC 4.0).
See https://creativecommons.org/licenses/by-nc/4.0/ for full license text.
