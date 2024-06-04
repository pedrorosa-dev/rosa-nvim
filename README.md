# Rosa-Nvim: A Custom Neovim Distribution

#### **LICENSE:** This repository is licensed under the [MIT License](LICENSE).

<img src="/assets/images/tela.png" alt="home screen" width="">


# Coming Soon
**Please note that there will soon be updates on shortcuts and tips on how to better use Rosa Neovim. Stay tuned for these enhancements!**

## Overview

Rosa-Nvim is a personalized Neovim distribution that combines the flexibility of Neovim with the ready-made configurations and plugins from LunarVim. It focuses on practicality and performance, providing an enjoyable code editing experience.

## Features

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
## Photos

access the [PHOTOS](/assets/pages/photos.md).

## Installation

 Ensure that you have already installed LunarVim by visiting [Lunarvim Website](https://www.lunarvim.org/docs/installation)

### Clone the repository:

```bash
git clone https://github.com/pedrorosa-dev/.dotfiles.git
```

- Note: This repository contains my dotfiles, including configurations for Tmux, Zsh, and Powerlevel10k. For more details, explore the [my Dotfiles](https://github.com/pedrorosa-dev/.dotfiles) repository.

## Setting Up Rosa-Nvim

1. Make sure you have `stow` installed.

```bash
sudo apt install stow
```

```bash

brew install stow
```

2. Navigate to the `~/.dotfiles` directory.
3. Execute the following commands:

#### **IMPORTANT**

- Make sure you are inside the ~/.dotfiles directory before running the stow commands.



## To apply the Rosa-Nvim

```bash
stow lvim

```
```bash
stow core
```
---

**Done, now enjoy your Rosa-Nvim like never before**



## To start
- open your terminal
- and write **lvim**

Note: You can create an alias as you wish, if by chance you use zsh you can check out [my Dotfiles](https://github.com/pedrorosa-dev/.dotfiles) 

## Customizing the Dashboard personal name

1. Open Rosa-nvim. 
2. Press `c` to open the dashboard menu.
3. Navigate to the `dashboard.lua`. Local: `lua/user/dashboard.lua`
4. Look for the `title` setting (usually set to "Welcome, Pedro Rosa").
5. Change the title to your desired text.

Alternatively, you can directly edit the `~/.config/lvim/config.lua` file and modify the `lua/user/dashboard.lua` setting there.

## Customizing Notification Messages

1. Open Rosa-nvim. 
2. Press `c` to open the dashboard menu.
3. Access `notify.lua`. Local:`lua/user/notify.lua`
4. In that file, you'll find a welcome message. You can replace it with your preferred text or comment out the code to disable the notification.
1. Access the `~/.config/lvim/config.lua` file.
2. Look for the `lua/user/notify.lua` section.

Alternatively, you can directly edit the `~/.config/lvim/config.lua` file and modify the `lua/user/notify.lua` setting there.

---

**Feel free to explore and adapt Rosa-Nvim to your liking!** 🌟
