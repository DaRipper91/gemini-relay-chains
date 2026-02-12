# Relay Handoff Protocol (Anti-Drift)

Every transition between tiers MUST include a physical handoff artifact. This prevents the next agent from "hallucinating" the work done by the previous one.

## 📜 The Golden Rule
> **"If it is not in the Markdown, it did not happen."**

## 📂 The Artifact Chain

1.  **Discovery Artifact**: Produced by Tier 1. Lists every file path and raw observation.
2.  **Logic Artifact**: Produced by Tier 2. Defines the "Why" and "How" before a single line is written.
3.  **Verification Artifact**: Produced by Tier 4. Proves the code matches the plan using actual test logs.
4.  **Knowledge Artifact**: Produced by Tier 5. The final documentation (ManPages, README).

## 🛠️ Termux Implementation
On `gemini-cli-termux`, artifacts should be stored in:
`~/Projects/[Project_Name]/relay_logs/`

This ensures that even if a session is interrupted, the next agent in the relay can read the logs to find the "honest and wholeful truth."
