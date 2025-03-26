# DeadlyDots - Arch Linux Dotfiles

Welcome to **DeadlyDots** – my **custom Arch Linux dotfiles**, fine-tuned for efficiency, minimalism, and a sleek workflow. These configurations enhance productivity while maintaining a **lightweight & aesthetic** setup.

---

## Features
- **Tiling Window Manager (TWM) Setup**
- **Neovim with custom keybindings & plugins**
- **Zsh with powerlevel10k & aliases**
- **Custom Polybar & Rofi Themes**
- **Optimized i3wm / Hyprland / BSPWM**
- **Hyprland Configurations for Wayland Setup**
- **Minimal & Blazingly Fast Workflow**
- **Auto-Scripted Setup for Quick Deployment**

---

## Dotfiles Overview
```
~/.config
  ├── alacritty   # Terminal emulator config
  ├── i3          # i3 window manager setup
  ├── hypr        # Hyprland config (Wayland WM)
  ├── polybar     # Status bar with modules
  ├── rofi        # Application launcher theme
  ├── neofetch    # System info display
  ├── nvim        # Neovim custom setup
  ├── zsh         # Zsh shell configurations
```

---

## Hyprland Configurations
Hyprland is configured for a smooth and modern Wayland experience with:
- **Dynamic Workspaces**
- **Blur & Transparency Effects**
- **Custom Keybindings for Tiling & Floating Windows**
- **Waybar for Status Bar with Modules**
- **Touchpad & Gesture Support**
- **Nvidia & AMD GPU Tweaks**

Configuration files are located in `~/.config/hypr/hyprland.conf`.

---

## Installation & Setup
```sh
# Clone the repository
git clone https://github.com/rupak1005/deadlydots.git ~/.dotfiles

# Navigate to the dotfiles folder
cd ~/.dotfiles

# Run the installation script
./install.sh
```

**Note:** Make sure to back up your existing dotfiles before running the script.

---

## Screenshots
![image](https://github.com/user-attachments/assets/f8ccccd3-ff14-45c5-a0d8-5595ae7554bd)
![image](https://github.com/user-attachments/assets/e79edfd9-3294-43a2-a9d3-89b290175dc7)
![image](https://github.com/user-attachments/assets/1fb56e0d-0e6c-49eb-8e39-a021039eff49)


*Inspired by ML4w*

---

## Customization
Easily modify themes, keybindings, and shell settings by tweaking:
- `~/.config/i3/config`
- `~/.config/hypr/hyprland.conf`
- `~/.config/waybar/config.jsonc`
- `~/.config/polybar/config.ini`
- `~/.zshrc`
- `~/.config/nvim/init.lua`

---

## Contributing
Feel free to fork, submit issues, or suggest improvements. Always happy to improve the **Arch Linux experience**!

---

## License
These dotfiles are available under the **MIT License**.

---

**Power Up Your Arch Experience with DeadlyDots!**

