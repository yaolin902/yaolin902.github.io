---
layout: post
title: State of My Laptop
date: 2024-12-09 00:00:00
description: What I am running on my Linux laptop
tags: ricing linux
categories: tech
---

The reason I got into Linux is because how customizable it is. I still remember the first time I wiped Windows 10 off of my laptop and installed Manjaro. I have installed Arch in the command line and use i3wm, but I have long moved away from Arch because of the package manager pacman. Here is what I am currently running on:

### Debian + dwm
I have decided to run Debian because of APT. I prefer my package from a stable version. In addition to APT, I use Nix package manager for projects. For example, I need the one library to build for this one project that I might never touch after I finish. I don't want to worry if this one package will interfere other packages in my system.

I love using tiling window manager. I have tried i3wm but it has more feature than I needed. With dwm, it is written in C and is fairly small. If I need additional features, it have numerous patches like fancy bar and grid mode.

{% include figure.liquid path="assets/img/2024-12-09-state-of-laptop/1.png" class="img-fluid rounded z-depth-1" zoomable=true %}

### Suckless software: st, dmenu, surf
Same with dwm, less is more. Before st, I was using Kitty. It works well, but I would like something lightweight. Some of the features I patch st are ligature and w3m support. Dmenu is just something I used to launch applications like the start menu on Windows. Surf is just a web browser in GTK3. I use it as an back up and also a markdown preview.

{% include figure.liquid path="assets/img/2024-12-09-state-of-laptop/2.png" class="img-fluid rounded z-depth-1" zoomable=true %}

### Terminal
What is my development environment? I write code and edit files in neovim with tmux. Tmux allows me to spawn many tabs of zsh session. I uses powerlevel10k theme to customize my prompt. My zsh contain plugins like autocomplete and syntax highlighting.
#### Neovim
I wrote my neovim config by myself with the help of jmbuhr/quarto-nvim-kickstarter git repo. Instead of using LunarVim or NVChad, I want to be conscious of the plugins I use and eliminate ones that I barely use. Sure, it can get frustrating when plugins update and I have to fix my config, but that is the trade off.

{% include figure.liquid path="assets/img/2024-12-09-state-of-laptop/3.png" class="img-fluid rounded z-depth-1" zoomable=true %}

### Closing thoughts
I hope this blog inspire your to customize your Linux. I manage my dotfiles using a bare git repo [here](https://github.com/yaolin902/dotfiles2).

{% include figure.liquid path="assets/img/2024-12-09-state-of-laptop/4.png" class="img-fluid rounded z-depth-1" zoomable=true %}
