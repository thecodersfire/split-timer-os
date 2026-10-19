# Built-in features for split-timer-os

Purpose: speedrunning

1. **organize a personal routine** — run split-timer-os-workspace. It creates ~/Documents/split-timer-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run split-timer-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/split-timer-os-session-plans/.
3. **check routine readiness** — run split-timer-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/split-timer-os-workspace features/split-timer-os-plan features/split-timer-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for speedrunning:

1. **Heroic Games Launcher** — com.heroicgameslauncher.hgl
2. **Lutris** — net.lutris.Lutris
3. **Bottles** — com.usebottles.bottles

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for speedrunning:

1. **VLC** — review media files (org.videolan.VLC)
2. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
3. **Blender** — create 3D assets and animations (org.blender.Blender)
4. **VSCodium** — edit code and project files (com.vscodium.codium)
5. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
6. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
7. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
8. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
9. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)
10. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
