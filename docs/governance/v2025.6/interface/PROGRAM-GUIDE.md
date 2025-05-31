# PROGRAM-GUIDE.md

## §0.0 Revision Format

This version applies structured numeric sections (`§X.Y.Z`) to all concepts, bullets, and criteria. This supports unambiguous traceability for governance audits, changelogs, and sync validation.

---

## §1.0 Program Purpose

### §1.1 Why This Program Exists

#### §1.1.1 Enables NI and its community to collaborate on reusable IP  
#### §1.1.2 Accelerates LabVIEW adoption and ecosystem health  
#### §1.1.3 Improves trust and transparency  
#### §1.1.4 Reduces duplication of effort  
#### §1.1.5 Encourages broad-based innovation  
#### §1.1.6 Enables partners and users to tailor NI tools to real-world needs

---

## §2.0 Program Lifecycle

### §2.1 Stage 1: Community Interest Discovery

#### §2.1.1 External demand surfaces via issue discussions, PRs, or direct community proposals  
#### §2.1.2 Program Manager evaluates fit and redirects interest toward reusable internal IP

### §2.2 Stage 2: Evaluation

#### §2.2.1 Governance, IP, and technical readiness are assessed  
#### §2.2.2 Repositories must meet criteria before eligibility for open-sourcing or prioritization

### §2.3 Stage 3: Evaluation Complete

#### §2.3.1 If criteria are met and community leadership is present  
#### §2.3.2 Repository may be prioritized and prepared for public release

---

## §3.0 Candidate Repository Requirements

### §3.1 Characteristics of Good Candidates

#### §3.1.1 Usable and testable outside NI-internal systems  
#### §3.1.2 Fills a documented user need (e.g., protocol integration, scripting, test tooling)  
#### §3.1.3 Attracts interest from external users or contributors  
#### §3.1.4 Can be led by a non-NI technical Steering Committee

---

## §4.0 Contribution Agreements: DCO vs. CLA

### §4.1 Contributor License Agreement (CLA)

#### §4.1.1 Applies to core LabVIEW IP (e.g., frameworks, shipping components)  
#### §4.1.2 Required when deeper licensing guarantees are needed  
#### §4.1.3 Contributor signs a one-time agreement to authorize NI use and redistribution  
#### §4.1.4 CLA is tracked via external signing platform or GitHub bot (planned)

##### §4.1.5 Examples of CLA-Repos

- §4.1.5.1 LabVIEW Actor Framework  
- §4.1.5.2 LabVIEW gRPC Integration  
- §4.1.5.3 Any repo listed as “Core IP” in this document

### §4.2 Developer Certificate of Origin (DCO)

#### §4.2.1 Applies to add-ons, tooling, scripts, or documentation  
#### §4.2.2 Suitable for lightweight, optional, or prototyping projects  
#### §4.2.3 Contributor signs their Git commit using `Signed-off-by:`  
#### §4.2.4 No separate document is required

##### §4.2.5 Examples of DCO-Repos

- §4.2.5.1 LabVIEW Icon Editor  
- §4.2.5.2 Custom Probes Library  
- §4.2.5.3 Build Script Templates

---

## §5.0 Why the CLA/DCO Distinction Matters

| §5.1 Topic | §5.2 CLA | §5.3 DCO |
|-----------|----------|----------|
| §5.1.1 Legal Coverage | §5.2.1 Broad license grant | §5.3.1 Lightweight legal assertion |
| §5.1.2 Contributor Burden | §5.2.2 Requires signature | §5.3.2 Simple commit tag |
| §5.1.3 Recommended For | §5.2.3 Core product repos | §5.3.3 Community-driven utilities |

> ⚠️ **Note:** “CLA” here refers to Contributor License Agreement, not the Certified LabVIEW Architect title.

---

## §6.0 Revision History

| §6.1 Date | §6.2 Summary |
|-----------|--------------|
| §6.1.1 2025-05-22 | §6.2.1 Added DCO vs. CLA logic to clarify contribution models |
| §6.1.2 2025-04-XX | §6.2.2 Initial version |
