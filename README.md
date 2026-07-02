<div align="center">

# 🐚 muramasa-zsh-starship

Zsh & Starship configuration files

![Shell](https://img.shields.io/badge/Shell-zsh-F15A24?style=for-the-badge&logo=zsh&logoColor=white)
![Prompt](https://img.shields.io/badge/Prompt-Starship-DD0B78?style=for-the-badge&logo=starship&logoColor=white)
![Theme](https://img.shields.io/badge/Theme-Catppuccin%20Macchiato-8aadf4?style=for-the-badge&logo=catppuccin&logoColor=white)<br>
![Stars](https://img.shields.io/github/stars/Muramasa500/muramasa-zsh-starship?style=for-the-badge)
![Last Commit](https://img.shields.io/github/last-commit/Muramasa500/muramasa-zsh-starship?style=for-the-badge)
![License](https://img.shields.io/github/license/Muramasa500/muramasa-zsh-starship?style=for-the-badge)

</div>

<p align="center">
  <img src="screenshots/screenshot1.png" alt="Muramasa's zsh starship config" width="100%">
</p>

## 📦 Contents

| Folder | Description |
|---|---|
| `zsh/.zshrc` | Zsh shell configuration |
| `starship/.config/starship.toml` | Starship prompt configuration |

## 🔧 Setup

### Requirements

- [Zsh](https://www.zsh.org/)
- [Starship](https://starship.rs/)
- [Nerd Font](https://www.nerdfonts.com/) (for icons)

### Installation with GNU Stow

```bash
git clone https://github.com/Muramasa500/muramasa-zsh-starship.git ~/muramasa-zsh-starship
cd ~/muramasa-zsh-starship
stow zsh starship
```

### Dependencies

Install required packages:

```bash
sudo pacman -S \
  zsh starship ttf-jetbrains-mono-nerd \
  zsh-autosuggestions zsh-history-substring-search \
  zsh-syntax-highlighting eza dust fd bat \
  ripgrep procs fzf zoxide sudo-rs fastfetch
  ```
