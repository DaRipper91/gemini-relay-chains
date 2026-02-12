# Support & FAQ: The Anti-Drift Helpdesk

## 🧠 Core Troubleshooting

### Q: The AI is hallucinating or "drifting." What do I do?
**A:** Immediately command a **"Hard Reset."** Reference the `verification/CHECKLIST.md` and force the agent to state "Unknown" for any missing data.

### Q: A bash command failed with "Permission Denied."
**A:** Check your "Hardware Lock." High-level system commands are often restricted on mobile spoke devices (Pixel/Nothing). Execute these on the **Da-HP Anchor** via SSH if necessary.

### Q: I added a new repository but it's not in the Master Manual.
**A:** Run the **`repomix-manager`** skill to standardize the repo, then trigger the **Tier 6: Documentation** relay.

## 🛠️ Relay Faults

### Error: "Invalid Handoff Artifact"
*   **Cause**: The previous agent in the relay failed to wrap its output in the 4-backtick (````) format.
*   **Fix**: Re-run the previous phase or manually wrap the data before passing it to the next agent.
