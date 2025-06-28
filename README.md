# Dot.Files

This repository contains my personal dotfiles configured for Arch Linux with the Hyperland window manager.

## Overview

These dotfiles include configurations for:

- **Rofi**: A window switcher, run dialog, and dmenu replacement.
- **Waybar**: A highly customizable status bar for Wayland compositors.

## Contents

- `rofi/` — Configuration files for Rofi.
- `waybar/` — Configuration files for Waybar.
- `README.md` — This documentation.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Osyna/Dot.Files.git

    '''

2. Copy or link the dotfiles to their appropriate locations.

3. Restart your session or reload configurations to apply changes.

restart waybar : killall waybar && waybar & 
rofi is auto reloaded at each launch / open
