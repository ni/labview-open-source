# PRIORITY-SCORE.md

> 🛑 **This document defines how NI evaluates and allocates limited R&D effort across eligible open-source repositories.**  
> It is intended for use by NI leadership, the Program Manager, and Steering Committee members to ensure transparency, fairness, and community influence in decision-making.

---

## §1. What “Priority” Means

Priority in the NI Open-Source Program reflects **how much structured effort NI commits** to an open-source repository in a given evaluation cycle.  
It is **not a vote**, nor is it set by an individual—it is the result of:

### §1.1 Community Interest
Measurable community interest

### §1.2 Technical Leadership
Available technical leadership (SteerCo)

### §1.3 Resource Alignment
Internal resource alignment

### §1.4 Objective Scoring
Objective scoring across defined criteria

> ❗ **Note:** A repository cannot be prioritized until a Steering Committee is formed. SteerCo headcount is the gating requirement for priority evaluation.

---

## §2. Scoring Model Overview

The program uses a **4-factor scoring model** to evaluate whether an open-source repo is a good candidate for investment.  
Each factor is assessed independently, then considered together by the Program Manager and NI leadership.

| §Ref | Criterion        | Owner(s)             | Description |
|------|------------------|----------------------|-------------|
| §2.1 | **Practicality** | NI R&D               | Technical readiness of the codebase. Includes licensing, internal dependencies, documentation, and testability without NI-internal tools. |
| §2.2 | **Market Breadth** | Product Management | Breadth of applicability across NI’s audience. Considers whether the repo serves a general or niche use case. |
| §2.3 | **Value**        | Product Management (with user input) | Strategic importance to NI and its users. Informed by customer needs, partner input, and internal roadmap alignment. |
| §2.4 | **Interest**     | Community (required) | Number and quality of contributors expressing leadership interest. Measured through GitHub activity and SteerCo formation. |

> 🔍 *Each score informs program-level decisions but does not guarantee launch. Scores help NI focus its attention where impact is highest.*

---

## §3. What Drives a High Score?

### §3.1 Practicality Signals
No private IP. Public test harness exists. Docs are sufficient for onboarding.

### §3.2 Market Breadth Signals
Many customer types can use it (e.g., Modbus, gRPC). Not tied to a single vertical.

### §3.3 Value Signals
Directly tied to improving time-to-deploy, cross-platform support, or onboarding.

### §3.4 Interest Signals
Active GitHub issues. External contributors proposing PRs. Multiple volunteers in SteerCo.

---

## §4. Who Sets the Score?

Scoring is **not a vote** and **not fixed numerically**. Instead, the score is determined by:

- **Input from domain owners** (R&D, PM, Community)
- **Observed metrics and volunteer leadership**
- **Program Manager discretion**, based on alignment with program goals

The result is a **tiered priority class**:

- **P0:** Maximum investment focus. Must have strong leadership, immediate business impact, and high community support.
- **P1:** Solid candidate. Resources may be allocated when available. Continues to evolve.
- **P2:** Low/no resource commitment from NI. May be community-supported but does not meet current thresholds.

---

## §5. What Increases Priority?

> ✅ These are **the only accepted ways** to raise a repo’s priority:

### §5.1 SteerCo Recruitment
Recruiting SteerCo leadership (must be public, tracked)

### §5.2 Practical Readiness
Demonstrating practical readiness (test pass, release candidate)

### §5.3 Community Growth
Growing community interest (merged PRs, GitHub discussion activity)

### §5.4 Business Impact
Showing business impact via PM input (customer pull, support demand)

---

## §6. What This Document Does Not Cover

- This document does **not** assign project ownership.
- It does **not** define contributor roles (see [STEERCO-GUIDELINES.md](https://github.com/ni/open-source/blob/main/docs/governance/STEERCO-GUIDELINES.md)).
- It does **not** mandate release—priority ≠ launch. Launch decisions occur after full evaluation and community readiness.

---

## §7. Revision History

| Date       | Summary                         |
|------------|----------------------------------|
| 2025-05-31 | Numbered table rows and scoring triggers for GPT traceability |
| 2025-05-22 | Added 4-factor scoring model and role ownership |
| 2025-04-XX | Initial version |
