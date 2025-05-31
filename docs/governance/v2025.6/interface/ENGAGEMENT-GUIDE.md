# ENGAGEMENT-GUIDE.md

> 💬 This guide outlines how contributors to the NI Open-Source Program should engage via GitHub. It defines how to report issues, propose changes, participate in discussions, and track contributions in a way that aligns with the program’s governance and scoring model.

## §1. General Engagement Philosophy

The NI Open-Source Program is designed to:
- Empower contributors to take initiative
- Minimize approval bottlenecks
- Encourage clarity and structure without rigidity

Contributions are tracked directly via GitHub and recognized via badges, SteerCo membership, or certification points. All engagement should be public and auditable.

## §2. Where to Post

| Use Case | Use This | Notes |
|----------|----------|-------|
| ❗ Report a bug or technical issue | **GitHub Issue** | Must be actionable, reproducible, and scoped. |
| 💡 Propose a new feature or improvement | **GitHub Issue** | Clearly describe the need and potential impact. |
| 🧪 Report results of a manual test | **GitHub Issue** | Include environment, expected outcome, and pass/fail status. |
| ❓ Ask a general question or raise uncertainty | **GitHub Discussion** | Use for exploratory topics or unclear boundaries. |
| 🔁 Propose a PR | **GitHub Pull Request** | Include issue reference and testing details. |
| 🗣️ Share long-term ideas or meta-program suggestions | **Program Discussion Thread** | Use `open-source/discussions` repo. |

### §2.1 Discord Channel Structure

The NI Open-Source Discord server is publicly accessible to anyone interested in contributing, discussing, or learning about the program. However, some channels are intentionally private to support effective program operations.

| Channel Type | Visibility | Purpose |
|--------------|------------|---------|
| 🌐 Public Channels | Open to anyone with the invite link | General questions, contributor engagement, community announcements |
| 🔒 SteerCo Channels | Restricted to the Program Manager, select NI R&D liaisons, and active SteerCo members | Used to coordinate repo-specific decisions, organize testing, and streamline interaction with internal NI stakeholders |
| 🧑‍💻 Internal Liaison Channels | Viewable only by the Program Manager and NI liaisons | Used to coordinate internal alignment and technical readiness checks |

All private spaces are **moderated directly by the Program Manager (Sergio Velderrain)** to ensure alignment with governance principles and prevent off-record decision-making.

> 🛑 *All governance-affecting decisions must still be documented in public GitHub issues or governance commits, even if discussed in private Discord threads.*

This structure ensures broad community access while enabling scoped, efficient collaboration with contributors serving in leadership roles.

## §3. Contributor Best Practices

- Keep titles specific and meaningful
- Reference relevant issues using GitHub cross-linking
- Include full context for test results or technical suggestions
- Communicate asynchronously whenever possible

## §4. Manual Testing and Structured Test Reports

To improve the reliability of open-source IP, the program uses GitHub Issues to track manual testing by volunteers.

When submitting a test report:
- Provide platform/version details
- Describe expected and actual behavior
- State test outcome clearly (pass/fail/blocked)
- Reference linked issues or milestones if applicable

## §5. Engagement and Recognition

Consistent GitHub activity is the **main signal** used to award:
- Badges (see `CONTRIBUTOR-RECOGNITION.md`)
- SteerCo invitations
- Certification points (for eligible LabVIEW contributors)

## §6. Reporting Inappropriate Use or Abuse

If you experience harassment, inappropriate conduct, or off-topic behavior:
- Use GitHub’s reporting tools or email `sergio.velderrain@emerson.com`
- All contributors are expected to follow the [Open Source Community Code Of Conduct] (In progress)

## §7. Revision History

| Date       | Summary                              |
|------------|--------------------------------------|
| 2025-05-31 | Added §2.1 defining Discord channel structure and access roles |
| 2025-05-22 | Initial version based on contributor workflow analysis |
