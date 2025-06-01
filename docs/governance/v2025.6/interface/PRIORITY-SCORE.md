> 🛑 **This document defines how NI evaluates and weights contribution value for open-source repositories governed by the program.**  
> It is used by Product Management, NI leadership, and Steering Committees to ensure transparent prioritization and contributor recognition.

---

## §1. What “Priority” Means

Priority in the NI Open-Source Program reflects **how much contribution credit a given GitHub issue or task receives**, based on strategic alignment, impact, and resource demand.

It is:

- A **label applied to GitHub issues**, not entire repositories
- Determined by **Product Management**
- Used to **increase contribution point values** (e.g., for recertification, recognition)

It is **not a vote**, and does not guarantee NI resourcing or roadmap placement.

> ❗ **Note:** P0/P1/P2 labels affect contributor scoring, not launch or funding. They are not assigned by the Program Manager.

---

## §2. Scoring Model Overview

Product Management assigns priority levels based on four independent factors:

| §Ref | Criterion        | Owner(s)             | Description |
|------|------------------|----------------------|-------------|
| §2.1 | **Practicality** | NI R&D               | Technical readiness of the codebase. Includes licensing, testability, and independence from NI-only systems. |
| §2.2 | **Market Breadth** | Product Management | Breadth of applicability across customer segments |
| §2.3 | **Value**        | Product Management (with user input) | Strategic relevance to NI roadmap or customer needs |
| §2.4 | **Interest**     | Community            | Quality and consistency of external contributor participation (esp. SteerCo presence) |

---

## §2.5 Scoring Formula

Certification points awarded for a merged GitHub PR are calculated by combining:

- **T-Shirt Size (Complexity):** Indicates the base effort level.
- **Priority Label (Impact):** Adds a bonus multiplier based on strategic value.

| T-Shirt Size | Description                  | Points |
|--------------|------------------------------|--------|
| XS           | Minor fix                    | 1      |
| S            | Moderate change              | 2      |
| M            | Significant new feature      | 5      |
| L            | Major architecture work      | 10     |
| XL           | Complex system refactor      | 15     |

| Priority | Label | Bonus Points |
|----------|-------|--------------|
| Low      | P2    | +0           |
| Medium   | P1    | +5           |
| High     | P0    | +15          |

> 🧮 **Final Score = T-Shirt Size Points + Priority Bonus**

These values are used in real-time contributor scoreboards and sent automatically to the Certification Team after each merge.

---

## §3. Priority Class Definitions

Each GitHub issue or milestone may be tagged with one of the following labels. These affect the **bonus points** awarded on top of the T-Shirt Size baseline:

| Tier | Label | Bonus Points | Meaning |
|------|-------|--------------|---------|
| §3.1 | **P0** | +15         | Highest strategic alignment |
| §3.2 | **P1** | +5          | Strong candidate for recognition |
| §3.3 | **P2** | +0          | Contributions welcome, but low visibility |

These labels may affect how many recertification points are awarded or how visibility is assigned during program analysis.

---

## §4. Who Assigns Priority?

| Role | Responsibility |
|------|----------------|
| Product Management | Assigns all P0/P1/P2 labels to GitHub issues |
| Program Manager | May highlight readiness signals but does **not assign labels** |
| SteerCo | May advocate for increased readiness via engagement, but does not influence scoring directly |

---

## §5. What Increases Priority?

Product Management may assign higher priority when the following signals are present:

### §5.1 SteerCo Participation
Issue is owned, discussed, or reviewed by an active SteerCo

### §5.2 Practical Readiness
Code or contribution is testable, scoped, and merge-ready

### §5.3 Community Activity
Issue includes merged external PRs, active contributors, or interest discussions

### §5.4 Business Impact
Direct link to customer pull, partner demand, or roadmap acceleration

---

## §6. What This Document Does Not Cover

- It does **not** assign project ownership
- It does **not** define contributor roles (see [`STEERCO-GUIDELINES.md`](./STEERCO-GUIDELINES.md))
- It does **not** guarantee resource allocation — P0 ≠ resourcing commitment

---

## §7. Revision History

| Date       | Summary                                           |
|------------|---------------------------------------------------|
| 2025-05-31 | Clarified that Product Management owns priority labels |
| 2025-05-31 | Defined P0/P1/P2 as issue-level contribution weights |
| 2025-05-31 | **Added §2.5: Scoring Formula using T-Shirt Size + Priority Bonus** |
| 2025-05-22 | Added 4-factor model and owner breakdown |
| 2025-04-XX | Initial version |
