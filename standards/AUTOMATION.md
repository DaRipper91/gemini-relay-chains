# Relay Automation: The "Auto-Advance" Protocol

To maximize engineering velocity and minimize "Jerry-time," this protocol defines the conditions under which an Agent may bypass the `[STOP_TURN]` mandate.

## ⚡ The Auto-Advance Rule
> **"If a plan has been reviewed and APPROVED by the user or a Validation-Tier agent, the implementation worker MUST proceed to execution immediately without waiting for a new turn."**

## 🛡️ Safety Constraints
1.  **Approval Required**: The `state.json` or `linear_ticket.md` must explicitly show `status: "Ready for Dev"` or `approval: true`.
2.  **Explicit Scope**: The agent must only advance within the *same* ticket. Moving to a new ticket still requires a state reset.
3.  **Audit Trail**: Every auto-advanced step must be logged in the `relay_logs/` directory.

## 🛠️ Implementation
This rule overrides the "Mandatory Stop Protocol" in the `code-implementer` and `ticket-manager` skillsets for all DaRipper91 projects.
