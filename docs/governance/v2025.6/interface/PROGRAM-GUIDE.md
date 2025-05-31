# PROGRAM-GUIDE.md

> 📘 This document outlines the overall structure, intent, and guiding principles of the NI Open-Source Program.

## §1. Why This Program Exists

The NI Open-Source Program enables NI and its community to collaborate on reusable IP that accelerates LabVIEW adoption and ecosystem health. By making high-impact components public, we:
- Improve trust and transparency
- Reduce duplication of effort
- Encourage broad-based innovation
- Enable partners and users to tailor NI tools to real-world needs

## §2. Program Lifecycle (3 Stages)

### 🧭 Stage 1: Community Interest Discovery
- External demand surfaces via issue discussions, PRs, or direct community proposals.
- Program Manager evaluates fit and redirects interest toward reusable internal IP.

### 🔍 Stage 2: Evaluation
- Governance, IP, and technical readiness are assessed.
- Repos must pass criteria before becoming eligible for open sourcing or priority consideration.

### 🚀 Stage 3: Evaluation Complete
- If criteria are met and community leadership is present, the repo can be prioritized and prepared for public release.

## §3. What Makes a Repo a Good Candidate

- Must be usable and testable outside of NI-internal systems
- Should fill a documented user need (such as protocol integration, scripting layer, or test tooling)
- Has interest from external users or contributors
- Can be led by a non-NI technical Steering Committee

## §4. Contribution Agreements: DCO vs. CLA

To streamline contribution and protect both contributors and NI, the NI Open-Source Program uses two legal models depending on the type of intellectual property (IP) involved:

### 🔒 4.1 Contributor License Agreement (CLA)
**When It Applies:**
- Required for **core LabVIEW IP** (such as frameworks, shipping components).
- Any repo directly related to NI product delivery or requiring deeper licensing guarantees.

**What It Means:**
- The contributor signs a one-time agreement authorizing NI to use and redistribute their work.
- CLA is tracked via an external signing platform or GitHub bot (planned).

**Examples of CLA-Repos:**
- LabVIEW Actor Framework  
- LabVIEW gRPC Integration  
- Any repo listed as “Core IP” in `PROGRAM-GUIDE.md`

### 🖊️ 4.2 Developer Certificate of Origin (DCO)
**When It Applies:**
- Used for **add-ons, tooling, scripts, or documentation**.
- Repos that are lightweight, optional, or prototyping in nature.

**What It Means:**
- Contributor signs their Git commit using `Signed-off-by:` and affirms they have the right to contribute.
- No separate document is required.

**Examples of DCO-Repos:**
- LabVIEW Icon Editor  
- Custom Probes Library  
- Build Script Templates  

### 📎 Why This Distinction Matters

| Topic | CLA | DCO |
|-------|-----|-----|
| Legal Coverage | Broad license grant | Lightweight legal assertion |
| Contributor Burden | Requires signature | Simple commit tag |
| Recommended For | Core product repos | Community-driven utilities |

> ⚠️ *“CLA” in this context means “Contributor License Agreement” and is unrelated to NI’s internal Certification program or Certified LabVIEW Architect title.*

## §5. Revision History

| Date       | Summary                                      |
|------------|----------------------------------------------|
| 2025-05-22 | Added DCO vs. CLA logic to clarify contribution models |
| 2025-04-XX | Initial version                              |
