# gnord
Nord GTK and GNOME Shell theme

## Prerequisites

- GNOME Tweaks
- [User Themes GNOME extension](https://extensions.gnome.org/extension/19/user-themes/)

## Install
1.
    ```bash
    # Download theme
    git clone https://github.com/rohanssrao/gnord.git ~/.local/share/themes/gnord
    # Move config (this replaces ~/.config/gtk-3.0 if it already exists)
    mv -fT ~/.local/share/themes/gnord/gtk-3.0-config ~/.config/gtk-3.0
    # Make symlink for GTK 4
    ln -s ~/.config/gtk-3.0 ~/.config/gtk-4.0
    ```
1. Open GNOME Tweaks. Under Appearance, set both **Shell** and **Legacy Applications** to **Gnord**.
