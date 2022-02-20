# Config
Configure workflow vim, alacritty, tmux, zsh.
## Installation
1. Install Oh My Zsh:
https://github.com/ohmyzsh/ohmyzsh/wiki
2. Install tmux plugin manager:
https://github.com/tmux-plugins/tpm
3. Install vim plugin manager vim-plug:
https://github.com/junegunn/vim-plug
4. cd into your home directory
clone the git repository:
```sh
git clone https://github.com/alexitin/config
```
5. Create soft symlinks to all the configuration files you want to use:
```sh
ln -s ~/config/.vimrc ~/.vimrc
ln -s ~/config/.zshrc ~/.zshrc
ln -s ~/config/alacritty.yml ~/.config/alacritty/alacritty.yml
ln -s ~/config/tmux.conf ~/.tmux.conf
```
You can make edits to your configuration files as you see fit.
