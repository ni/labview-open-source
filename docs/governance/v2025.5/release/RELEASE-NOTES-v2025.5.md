# NI Runtime Governance – Release Notes

## Version: v2025.5  
**Runtime Tag:** `v2025.5-runtime`  
**Declared On:** 2025-05-29

---

## 🚀 Overview

NI Runtime Governance v2025.5 is the first fully declared and enforceable governance cycle. It introduces a complete THREAD and CONTRACT model to govern behavior, roles, and runtime safety for contributors, GPTs, and the STEERCO.

This version also formalizes a file structure isolating governance logic, testing output, release history, and human-facing interfaces.

---

## 🧩 Contents

### THREADs  
Located in: `docs/governance/v2025.5/threads/`
- `THREAD-v2025.5-LAUNCH.md`
- `THREAD-v2025.5-GOVERNANCE-SCOPE.md`
- `THREAD-v2025.5-CONTRIBUTING.md`
- `THREAD-v2025.5-ENGAGEMENT-GUIDE.md`
- `THREAD-v2025.5-ROLE-CONTRIBUTORS.md`
- `THREAD-v2025.5-ROLE-GPT.md`
- `THREAD-v2025.5-ROLE-STEERCO.md`

### CONTRACTs  
Located in: `docs/governance/v2025.5/contracts/`
- `CONTRACT-v2025.1-FILE-INSTRUCTION.md`
- `CONTRACT-v2025.1-AGENT-INHERITANCE.md`
- `CONTRACT-v2025.1-README-DOCS.md` (optional)

### System Support  
Located in: `docs/governance/v2025.5/runtime/`
- `governance-manifest.json`
- `gpt-validation-tests.json`
- `GPT-TEST-LOG-v2025.5.md`
- `GPT-TEST-RESULTS-v2025.5.md`

### Contributor Interface  
Located in: `docs/governance/v2025.5/interface/`
- `README.md`
- All GPT integration guides

---

## ✅ Activation

This governance runtime is frozen at:

```
Tag: v2025.5-runtime
Branch: main
```

All GPTs, validators, contributors, and governance tools must interpret governance behavior **strictly under this snapshot**.

Any governance updates must occur under a future version (e.g., `v2025.6`) and declare their own runtime tag.
