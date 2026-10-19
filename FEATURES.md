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

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
2. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
3. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
4. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
5. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
6. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
7. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
8. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
9. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
10. **GNOME Papers** (org.gnome.Papers) — read project and reference PDFs.
11. **Document Scanner** (org.gnome.SimpleScan) — digitize paper notes and forms.
12. **GNOME Contacts** (org.gnome.Contacts) — organize partner and team contacts.
13. **GNOME Clocks** (org.gnome.clocks) — time work sessions and events.
14. **OBS Studio** (com.obsproject.Studio) — record or stream sessions.
15. **Audacity** (org.audacityteam.Audacity) — edit audio recordings.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **Gwenview** (org.kde.gwenview) — review image sets and make quick crop, resize, and annotation edits.
2. **KGeoTag** (org.kde.kgeotag) — add GPS coordinates to photos from a GPX track or map.
3. **Kamoso** (org.kde.kamoso) — capture webcam photos and short video clips.
4. **KolourPaint** (org.kde.kolourpaint) — make quick raster sketches, labels, and simple image edits.
5. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
6. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
7. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
8. **Ark** (org.kde.ark) — open and create common project archive files.
9. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
10. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
11. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
12. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
13. **Marble** (org.kde.marble) — explore maps and a virtual globe for geographic context.
14. **KStars** (org.kde.kstars) — plan sky observations and explore astronomy simulations.
15. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for photo editing. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **Shotcut** (org.shotcut.Shotcut) — Edit multitrack video with filters, transitions, and titles.
2. **HandBrake** (fr.handbrake.ghb) — Transcode video files to common formats and presets.
3. **OpenShot** (org.openshot.OpenShot) — Assemble video clips on a multitrack timeline.
4. **Glaxnimate** (org.kde.glaxnimate) — Create vector animations, motion graphics, and animated SVG assets.
5. **Subtitle Composer** (org.kde.subtitlecomposer) — Create and synchronize captions for video projects.
6. **KPhotoAlbum** (org.kde.kphotoalbum) — Tag and organize large photo collections.
7. **Kid3** (org.kde.kid3) — Edit audio tags and album metadata in batches.
8. **Loupe** (org.gnome.Loupe) — View images and make simple crop, rotate, or flip edits.
9. **Kasts** (org.kde.kasts) — Subscribe to podcasts and manage playback queues.
10. **Jellyfin Desktop** (org.jellyfin.JellyfinDesktop) — Browse and play personal media from a configured Jellyfin server.
11. **KWave** (org.kde.kwave) — Record and edit audio waveforms.
12. **Elisa** (org.kde.elisa) — Organize and play a local music library.
13. **EasyEffects** (com.github.wwmm.easyeffects) — Adjust audio input and output with equalizers and effects.
14. **MuseScore** (org.musescore.MuseScore) — Write and play back musical notation.
15. **Ardour** (org.ardour.Ardour) — Record and mix multitrack audio sessions.
