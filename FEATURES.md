# Built-in features for luma-darkroom-os

Purpose: photo editing

1. **prepare a creative project** — run luma-darkroom-os-workspace. It creates ~/Documents/luma-darkroom-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run luma-darkroom-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/luma-darkroom-os-session-plans/.
3. **check project and export readiness** — run luma-darkroom-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/luma-darkroom-os-workspace features/luma-darkroom-os-plan features/luma-darkroom-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for photo editing:

1. **Inkscape** — org.inkscape.Inkscape
2. **Krita** — org.kde.krita
3. **Kdenlive** — org.kde.kdenlive

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
