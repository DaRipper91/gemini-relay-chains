# Relay Skill Usage Guide

How to use the most common Relay assets on `gemini-cli-termux`.

## 🛠️ Usage Instructions

### 🔎 Tier 1: Intelligence
**Skill: `code-researcher`**
*   *Usage*: `activate_skill(name="code-researcher")`
*   *Task*: "Audit the current directory for dead code and document discrepancies."
*   *Output*: `research_[date].md`.

**Gem: `Da-Scout`**
*   *Usage*: Load `scout.md` as system instruction.
*   *Task*: "Scan the /usr/include directory and build a Subject Profile for libusb."
*   *Output*: 8-5-4 Standard intel package.

### 🧠 Tier 2: Analysis
**Skill: `critical-analysis`**
*   *Usage*: `activate_skill(name="critical-analysis")`
*   *Task*: "Review the security findings in security_audit.md and find logical fallacies."

### 🏛️ Tier 3: Architecture
**Skill: `implementation-planner`**
*   *Usage*: `activate_skill(name="implementation-planner")`
*   *Task*: "Read research_report.md and create an implementation plan for the new TUI."

### 🛠️ Tier 4: Synthesis
**Skill: `code-implementer`**
*   *Usage*: `activate_skill(name="code-implementer")`
*   *Task*: "Execute Phase 1 of the approved implementation plan."

### ⚖️ Tier 5: Validation
**Gem: `Da-Publisher`**
*   *Usage*: Load `publisher.md`.
*   *Task*: "Audit the final draft against the Mission Spec and prepare for release."

### ✍️ Tier 6: Documentation
**Gem: `Da-Scribe`**
*   *Usage*: Load `scribe.md`.
*   *Task*: "Convert the Engineering Payload JSON into a ManPage."

---
*Created by DaRipper91*
