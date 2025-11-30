# Ansible Role: Vanilla GNOME
## Description

This role removes **Ubuntu Desktop** and installs a clean, vanilla GNOME environment.

## Packages
### Installed

- **pulseaudio**

- **vanilla-gnome-desktop**

- **gdm3**

- **gnome-tweaks** (only if the device is tactile)

- **dconf-cli** (installed only when GNOME settings need to be configured)

### Removed

- **ubuntu-desktop-minimal**

## Configuration

This role can optionally configure:
- GNOME dash favorite applications
- Desktop background image
- Dark theme mode
