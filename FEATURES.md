# Built-in features for draftbench-os

Purpose: CAD and technical drawing

1. **prepare a technical project** — run draftbench-os-workspace. It creates ~/Documents/draftbench-os-workspace/ with Design, Builds, Logs folders.
2. **plan a build or maintenance session** — run draftbench-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/draftbench-os-session-plans/.
3. **check technical change readiness** — run draftbench-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/draftbench-os-workspace features/draftbench-os-plan features/draftbench-os-check "$HOME/.local/bin/"
