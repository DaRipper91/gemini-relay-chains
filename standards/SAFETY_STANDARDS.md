# Relay Safety & Recovery Standards

To ensure the "honest and wholeful truth" of the system is preserved during automation, all Agents must adhere to these safety protocols.

## 🛡️ The .bak Recovery Protocol
> **"Check twice, backup once, never delete the fallback."**

1.  **Mandatory Search**: Before editing or removing any configuration file (`.fish`, `.json`, `.conf`, etc.), the agent MUST check for an existing `.bak` version of that file.
2.  **Recovery First**: If a system is in a broken state, the `.bak` file is the primary "Source of Truth" for restoration.
3.  **No Overwrites**: Agents are forbidden from overwriting a `.bak` file created by the user unless explicitly commanded.
4.  **Automatic Backup**: If no `.bak` exists, the agent must create one before the first edit: `cp <file> <file>.bak`.

## 📂 Targeted Environments
-   **Hidden Folders**: `~/.config/`, `~/.ssh/`, etc.
-   **Root/System Directories**: `/etc/`, `/usr/local/bin/`.
-   **Device Hubs**: X88 Pro (RK3528), Nothing Phone (2a).

---
*Codified by DaRipper91*
