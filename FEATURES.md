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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for photo editing:

1. **Blender** — create 3D assets and animations (org.blender.Blender)
2. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
3. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
4. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
5. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
6. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
7. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
8. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
9. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
10. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
