# ROLES.md – NI-Owned Operational Roles

> 🛠 This document defines all NI-internal (non-volunteer) roles required to operate and scale the NI Open-Source Program.  
> All roles listed here are exclusive to NI employees and must be traceable via changelog updates.

---

## §1.0 Role Structure

Roles in this document are grouped by functional ownership: program design, governance execution, scoring, developer experience, and infrastructure automation. Roles may be held by the same individual until delegation is feasible.

---

## §2.0 Core Roles

### §2.1 Program Architect

The Program Architect is the blueprint owner of the NI Open-Source Program. This role defines the structure, lifecycle systems, role models, scoring phases, and automation enforcement logic that govern how the program operates.

#### §2.1.1 Responsibilities
- Design lifecycle models (e.g., tracking events, scoring criteria)
- Define structural logic for `.md` files (sectioning, numbering, metadata)
- Own changelog and badge system enforcement model
- Architect automation and contributor parsing workflows (e.g., GPT integration)

---

### §2.2 Program Manager

The Program Manager is the operational lead and governance enforcer of the program. This role manages execution, contributor oversight, badge recognition, changelog approval, and integration with NI stakeholders.

#### §2.2.1 Responsibilities
- Enforce governance policy and lifecycle logic
- Approve role assignments, contributor badges, and SteerCo nominations
- Maintain changelog consistency and GPT enforcement

#### §2.2.2 Cross-Functional Integration
- Interface with NI executives, R&D, product management, and legal/compliance
- Translate NI strategic and technical goals into contributor policy

#### §2.2.3 Education Services Integration
- Coordinate with NI Education Services on certification systems
- Audit and maintain GitHub-linked infrastructure for contributor point tracking
- Ensure recognition pathways align with NI recertification rules

#### §2.2.4 Delegation and Tooling
- May temporarily hold other NI roles (Architect, Recognition Lead)
- Own enforcement interface with this governance GPT and automation logic

---

### §2.3 Scoring Coordinator

The Scoring Coordinator integrates scoring signals across NI business and technical domains to inform repository prioritization tiers (P0–P2).

#### §2.3.1 Responsibilities
- Gather scoring inputs from NI R&D (Practicality), Product Management (Value, Breadth), and Community (Interest)
- Normalize scoring across criteria for governance decisions
- Recommend repo readiness to Program Manager for priority classification

---

### §2.4 Developer Relations Lead

The Developer Relations (DevRel) Lead ensures a high-quality contributor experience and maintains transparency across recognition, onboarding, and community momentum signals.

#### §2.4.1 Responsibilities
- Manage contributor onboarding clarity, feedback channels, and trust signals
- Propose contributor badge nominations to Program Manager
- Identify structural barriers to engagement (e.g., confusing repos, missing templates)

---

### §2.5 Infra & Automation Owner

This role owns the automation and infrastructure used to track contributor signals, enforce changelog compliance, and maintain governance integrity at scale.

#### §2.5.1 Responsibilities
- Maintain GitHub Actions, CI templates, changelog parsers, and contributor dashboards
- Ensure `.md` file structure, metadata, and sectioning follow enforcement rules
- Support automation scaling across repositories and governance assets

---

## §3.0 Role Delegation

All roles in this document default to the **Program Manager** unless delegated. Temporary overlap or combination is permitted during early-stage operation but must be documented in `GOVERNANCE-CHANGELOG.md` as assignments evolve.
