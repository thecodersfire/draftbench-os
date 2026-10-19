# Built-in features for draftbench-os

Purpose: CAD and technical drawing

1. **prepare a technical project** — run draftbench-os-workspace. It creates ~/Documents/draftbench-os-workspace/ with Design, Builds, Logs folders.
2. **plan a build or maintenance session** — run draftbench-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/draftbench-os-session-plans/.
3. **check technical change readiness** — run draftbench-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/draftbench-os-workspace features/draftbench-os-plan features/draftbench-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for CAD and technical drawing:

1. **VSCodium** — com.vscodium.codium
2. **GNOME Builder** — org.gnome.Builder
3. **Wireshark** — org.wireshark.Wireshark

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for CAD and technical drawing:

1. **OpenSCAD** — model parametric 3D parts in code (org.openscad.OpenSCAD)
2. **KiCad** — design circuits and PCBs (org.kicad.KiCad)
3. **Arduino IDE** — write and upload microcontroller sketches (cc.arduino.IDE2)
4. **Blender** — create 3D assets and animations (org.blender.Blender)
5. **PrusaSlicer** — prepare models for 3D printing (com.prusa3d.PrusaSlicer)
6. **DB Browser for SQLite** — inspect SQLite databases (org.sqlitebrowser.sqlitebrowser)
7. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
8. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
9. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
10. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
