# Relay Roles & Tiers

To prevent model drift and ensure grounding, every Agent (Skill, Gem, or Instruction) in a Relay Chain must occupy a defined Tier.

## 🏛️ The Tier Hierarchy

### 🔎 Tier 1: Intelligence (The Eye)
*   **Goal**: Harvest raw data without judgment.
*   **Agents**: `scout`, `recon-agent`, `file-locator`.
*   **Output**: `RAW_AUDIT.md` or `RECON_LOG.json`.

### 🧠 Tier 2: Strategy (The Brain)
*   **Goal**: Convert data into logic and step-by-step plans.
*   **Agents**: `implementation-planner`, `architect`, `dependency-mapper`.
*   **Output**: `PLAN.md` with atomic checkboxes.

### 🛠️ Tier 3: Synthesis (The Hand)
*   **Goal**: Modify the system state or generate code.
*   **Agents**: `code-implementer`, `script-generator`, `sql-builder`.
*   **Output**: Verified code commits or scripts.

### ⚖️ Tier 4: Validation (The Judge)
*   **Goal**: Ensure compliance with standards and safety.
*   **Agents**: `plan-reviewer`, `security-auditor`, `syntax-checker`.
*   **Output**: `REVIEW_REPORT.md` (Approved/Rejected).

### ✍️ Tier 5: Documentation (The Scribe)
*   **Goal**: Translate technical state into human-readable knowledge.
*   **Agents**: `manpage-author`, `readme-writer`, `api-documenter`.
*   **Output**: `man/`, `README.md`, `TROUBLESHOOTING.md`.

### 📞 Tier 6: Support (The Liaison)
*   **Goal**: Provide context-aware assistance for the finalized program.
*   **Agents**: `help-desk-agent`, `user-guide-bot`, `faq-manager`.
*   **Output**: Interactive help prompts or `SUPPORT.md`.

---
*Standards defined by DaRipper91*
