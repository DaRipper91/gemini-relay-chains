# DAGEM(1) - User Manual

## NAME
dagem - Gemini Context Gem Loader for Fish Shell

## SYNOPSIS
`dagem <gem_name> "<prompt>"`

## DESCRIPTION
**dagem** is a high-speed wrapper for the Gemini CLI that injects a specialized "Gem" (system prompt) before executing a user query. It maintains a persistent chat history in JSONL format for later forensics.

## OPTIONS
*   **gem_name**: The filename (without .md) located in `~/ops/gems/`.
*   **prompt**: The user instructions to be processed by the Gem.

## EXAMPLES
`dagem scout "Audit /usr/bin/python"`

## FILES
*   `~/ops/gems/`: Location of system prompts.
*   `~/ops/archive/raw/chat_history.jsonl`: Persistent audit log.

---

# TRIBBLE(1) - User Manual

## NAME
automatic-tribble - Cross-Filesystem TUI for Termux/Android

## SYNOPSIS
`python3 -m file_manager.app`

## DESCRIPTION
**automatic-tribble** provides a dual-pane terminal interface for managing files between the sandboxed Termux environment and the shared Android storage folders (`/sdcard`).

## KEYBINDINGS
*   **TAB**: Switch active panel.
*   **C**: Copy selected item.
*   **M**: Move selected item.
*   **D**: Delete (requires confirmation).
*   **Q**: Quit application.

## AI MODE
Press **Success** in the Launcher screen to activate Gemini-powered automation for file organization.
