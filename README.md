# Rosa-Nvim: A Custom Neovim Distribution

#### **LICENSE:** This repository is licensed under the [MIT License](LICENSE).

!Rosa-Nvim Logo

## Overview
Rosa-Nvim is a personalized Neovim distribution that combines the flexibility of Neovim with the ready-made configurations and plugins from LunarVim. It focuses on practicality and performance, providing an enjoyable code editing experience.

## Features
- Autocompletion for various programming languages
- Integrated file explorer
- Language Server Protocol (LSP) integration
- Treesitter support for advanced syntax highlighting
- Customizable dashboard and notification messages




## Installation
1. Ensure that you have already installed LunarVim by visiting [Lunarvim Website](https://www.lunarvim.org/docs/installation) 
###  Clone the repository:
```bash
git clone https://github.com/pedrorosa-dev/.dotfiles.git
```
   - Note: This repository contains my dotfiles, including configurations for Tmux, Zsh, and Powerlevel10k. For more details, explore the [my Dotfiles](https://github.com/pedrorosa-dev/.dotfiles) .repository. 

## Setting Up Rosa-Nvim
1. Make sure you have `stow` installed.
2. Navigate to the `~/.dotfiles` directory.
3. Execute the following commands:

#### **IMPORTANT** 
- Make sure you are inside the ~/.dotfiles directory before running the stow commands.

- - -


2. Use `stow` to create symbolic links for the desired configurations. For example:

    ```bash
    stow lvim
    stow core
    stow zsh
    stow p10k
    stow tmux
    ```

3. To apply all configurations at once:

    ```bash
    stow .
    ```

- - -


## Customizing the Dashboard Title
1. Open Neovim.
2. Press `c` to open the dashboard menu.
3. Navigate to the "Dashboard" section.
4. Look for the `title` setting (usually set to "Welcome, Pedro Rosa").
5. Change the title to your desired text.

Alternatively, you can directly edit the `~/.config/lvim/config.lua` file and modify the `title` setting there.

## Customizing Notification Messages
1. Access the `~/.config/lvim/config.lua` file.
2. Look for the `lua/user/notify.lua` section.
3. In that file, you'll find a welcome message. You can replace it with your preferred text or comment out the code to disable the notification.



Feel free to explore and adapt Rosa-Nvim to your liking! 🌟
