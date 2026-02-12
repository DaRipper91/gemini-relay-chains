# Relay Verification Checklist

To prevent "AI Drift" and hallucinations, every instruction set must be verified before being used in a Relay.

## 🏁 The Verification Steps

### 1. The Grounding Check
- [ ] Does the agent explicitly reference local files or system hardware?
- [ ] Does it state "Unknown" when data is missing?
- [ ] Does it avoid "As an AI" preambles?

### 2. The Handoff Check
- [ ] Does the agent output its data in a structured block (JSON/XML/Markdown)?
- [ ] Does it use the 4-backtick wrapper (````) for compatibility?
- [ ] Does it provide a prompt for the *next* agent in the chain?

### 3. The Tone Check
- [ ] Does it match the "Cody-Gemini Bond" (Direct, Technical, Gritty)?
- [ ] Is it free of "Polite Filler" and "Robotic Jargon"?

## 🛠️ Root Cause Analysis Protocol
If an agent fails a task, it must output a "Root Cause" block:
```markdown
**Root Cause for Failure**: [e.g. Permission Denied on /usr/bin/X]
**Uncertainty Level**: [High/Low]
**Steps to Resolve**: [1, 2, 3]
```
