# Gemini Relay Chain Standard

This repository defines the architecture for "Relay Chains" in Gemini CLI. A Relay Chain is a sequenced workflow where two or more specialized agent configurations (Skills, Gems, or Instructions) pass stateful context to one another to complete complex tasks.

## 🔗 The Relay Concept

In a Relay, agents follow a **Handoff Protocol**:
1.  **Agent A (The Scout/Researcher)**: Gathers data and outputs a `RESEARCH_REPORT.md`.
2.  **Agent B (The Architect/Planner)**: Ingests the report and outputs an `IMPLEMENTATION_PLAN.md`.
3.  **Agent C (The Builder/Implementer)**: Executes the plan and verifies success.

## 📁 Repository Structure

- `/standards/`: Markdown definitions of the Relay protocol.
- `/relays/`: Mapping files that define which Skills/Gems are used in specific chains.
- `/verification/`: Checklists for validating a Skill/Gem before it is added to a relay.

---
*Maintained by DaRipper91*
