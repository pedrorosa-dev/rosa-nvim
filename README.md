# Rosa-Nvim: A Custom Neovim Distribution

#### **LICENSE:** This repository is licensed under the [MIT License](LICENSE).

<img src="/assets/images/tela.png" alt="home screen" width="">

# Coming Soon:

**Please note that there will soon be updates on shortcuts and tips on how to better use Rosa Neovim. Stay tuned for these enhancements!**

## Overview:

Rosa-Nvim is a personalized Neovim distribution that combines the flexibility of Neovim with the ready-made configurations and plugins from [Lunarvim](https://www.lunarvim.org/). It focuses on practicality and performance, providing an enjoyable code editing experience.

## Features:

- Autocompletion for various programming languages
- Integrated file explorer
- Language Server Protocol (LSP) integration
- Treesitter support for advanced syntax highlighting
- Customizable dashboard and notification messages
- Multiple ways to access files
- Easy shortcuts
- Implemented artificial intelligence like Copilot and Codeium
- Multiple themes
- Lazygit
- Gitsings
- Linters

## Photos:

access the [PHOTOS](/assets/pages/photos.md).

---

## Installation Requirements:

- [Neovim](https://neovim.io/)
- [Lunarvim](https://www.lunarvim.org/docs/installation)
- [GNU Stow](https://www.gnu.org/software/stow/)

Make sure to install **Lunarvim** by following the instructions available at [Lunarvim](https://www.lunarvim.org/docs/installation).

Additionally, you'll also need to have GNU Stow installed on your system. You can install Stow using your Linux distribution's package manager or Homebrew if you're using macOS.

## Examples:

**Ubuntu**

```bash
sudo apt install stow
```

**MacOS**

```bash

brew install stow
```

**Arch linux**

```bash
sudo pacman -Syu stow
```

---

## Steps for Installation:

### 1. Clone the Repository:

```bash
git clone https://github.com/pedrorosa-dev/.dotfiles.git
```

- Note: This repository contains my dotfiles, including configurations for Tmux, Zsh, and Powerlevel10k. For more details, explore the [my Dotfiles](https://github.com/pedrorosa-dev/.dotfiles) repository.

### 2. Remove existing configuration files (if necessary): Before applying the configurations, ensure that the original files are removed to avoid conflicts:

```bash

rm -rf ~/.config/lvim && rm -rf ~/.local/share/lunarvim/lvim/lua/lvim/core
```

### 3. Setting Up Rosa-Nvim:

1. Navigate to the `~/.dotfiles` directory.
2. Execute the following commands:

#### **IMPORTANT:**

- Make sure you are inside the ~/.dotfiles directory before running the stow commands.

### 4. To apply the Rosa-Nvim:

**Run the command**

```bash
stow lvimRoot && stow LvimUser

```

**Done, now enjoy your Rosa-Nvim like never before**

## To Start:

- open your terminal
- and write **lvim**

**Note: You can create an alias as you wish, if by chance you use zsh you can check out [my Dotfiles](https://github.com/pedrorosa-dev/.dotfiles)**

### **If you use Zsh, you can add this command to your `.zshrc` file:**

```bash
alias rn='lvim'
```

---

**Feel free to explore and adapt Rosa-Nvim to your liking!** 🌟
