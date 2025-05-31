# ENGAGEMENT-GUIDE.md

> 💬 This guide outlines how contributors to the NI Open-Source Program should engage via GitHub. It defines how to report issues, propose changes, participate in discussions, and track contributions in a way that aligns with the program’s governance and scoring model.

---

## §1. General Engagement Philosophy

The NI Open-Source Program is designed to:

### §1.1.1 Empower Contributors
Empower contributors to take initiative

### §1.1.2 Avoid Bottlenecks
Minimize approval bottlenecks

### §1.1.3 Encourage Lightweight Structure
Encourage clarity and structure without rigidity

### §1.1.4 Track Public Engagement
Contributions are tracked directly via GitHub and recognized via badges, SteerCo membership, or certification points. All engagement should be public and auditable.

---

## §1.2 Tracking Event Definition

📍 **Tracking Event**

A **tracking event** is a publicly visible action or decision that marks progress in the governance lifecycle of an NI open-source repository. Tracking events are used to:

### §1.2.1 Signal Contributor Engagement
Signal contributor engagement or repo readiness

### §1.2.2 Anchor Governance Artifacts
Anchor discussions, scoring, and evaluation processes to GitHub-visible artifacts

### §1.2.3 Enable Traceability
Ensure transparency and traceability in how program resources are allocated

Tracking events are not votes or approvals; they are markers used by the Program Manager and SteerCo to observe momentum and alignment with program goals.

### §1.2.4 Examples of Valid Tracking Events

| §Ref | Type | Description | Where It Appears |
|------|------|-------------|------------------|
| §1.2.4.1 | **SteerCo Formation** | At least two confirmed participants begin 2hr/week GitHub engagement | GitHub Discussions, Issues, `STEERCO-GUIDELINES.md` updates |
| §1.2.4.2 | **Discussion Kickoff** | A GitHub Discussion scopes a new technical or governance topic | `open-source/discussions` or repo-specific discussions |
| §1.2.4.3 | **Issue Conversion** | A scoped GitHub Issue is created from a discussion, including acceptance criteria | Linked Issues with `enhancement`, `roadmap`, or `governance` labels |
| §1.2.4.4 | **Manual Test Result** | Contributor posts a structured test outcome with traceable metadata | GitHub Issue using `Test Result` template |
| §1.2.4.5 | **Changelog Entry** | A formal change is logged in `GOVERNANCE-CHANGELOG.md` | Markdown commit or published PR |

---

## §2. Where to Post

| Use Case | Use This | Notes |
|----------|----------|-------|
| ❗ Report a bug or technical issue | **GitHub Issue** | Must be actionable, reproducible, and scoped. |
| 💡 Propose a new feature or improvement | **GitHub Issue** | Clearly label as `enhancement`. Include use case. |
| 🧪 Report results of a manual test | **GitHub Issue** | Use the `Test Result` template if available. |
| ❓ Ask a general question or raise uncertainty | **GitHub Discussion** | For open-ended input, community dialogue. |
| 🔁 Propose a PR | **GitHub Pull Request** | Include context: why, how, and how it was tested. |
| 🗣️ Share long-term ideas or meta-program suggestions | **Program Discussion Thread** | Use `open-source/discussions` repo. |

---

## §3. Contributor Best Practices

### §3.1 Use Labels
Always use labels (e.g., `bug`, `enhancement`, `test result`, `documentation`)

### §3.2 Reference Related Issues
Reference related issues in PRs using `Fixes #123` or `Related to #456`

### §3.3 Use Specific Titles
Keep titles specific and meaningful

### §3.4 Include Metadata in Test Reports
For test reports, include:

#### §3.4.1 Test ID
**Test ID** (if defined)

#### §3.4.2 Platform
**Platform/Version**

#### §3.4.3 Behavior Summary
**Expected vs. Actual Behavior**

#### §3.4.4 Outcome
**Outcome** (Pass/Fail/Blocked)

---

## §4. Manual Testing and Structured Test Reports

To improve the reliability of open-source IP, the program uses GitHub Issues to track manual testing by volunteers.

### §4.1 How to Submit a Test Report

When submitting a test report:

#### §4.1.1 Use the Template
Use the `Test Result` issue template if available

#### §4.1.2 Indicate Test Type
Be clear if the test was exploratory or for a known bug

#### §4.1.3 Notify Coordinator
Tag `test-coordinator` if assigned

#### §4.1.4 Link to Context
Link to the relevant milestone or GitHub Project board if applicable

---

## §5. Engagement and Recognition

### §5.1 Award Signals
Consistent GitHub activity is the **main signal** used to award:
- Badges (see `CONTRIBUTOR-RECOGNITION.md`)
- SteerCo invitations
- Certification points (for eligible LabVIEW contributors)

### §5.2 Prioritization Link
Visible GitHub contributions help the Program Manager and NI leadership prioritize effort and evaluate interest across the ecosystem. These contributions also serve as tracking events for future prioritization.

---

## §6. Reporting Inappropriate Use or Abuse

If you experience harassment, inappropriate conduct, or off-topic behavior:

### §6.1 Use GitHub Tools
Use GitHub’s reporting tools or email `sergio.velderrain@emerson.com`

### §6.2 Follow Code of Conduct
All contributors are expected to follow the [Open Source Community Code Of Conduct] (In progress)

---

## §7. Revision History

| Date       | Summary                              |
|------------|--------------------------------------|
| 2025-05-31 | Replaced “governance milestone” with “tracking event”; added term definition |
| 2025-05-22 | Initial version based on contributor workflow analysis |
