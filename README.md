# Config
Configure workflow vim, alacritty, tmux, zsh.
## Installation
1. You'll need install Oh My Zsh:
https://github.com/ohmyzsh/ohmyzsh/wiki
2. cd into your home directory
clone the git repository:
```sh
git clone https://github.com/alexitin/config
```
3. Create soft symlinks to all the configuration files you want to use:
```sh
ln -s ~/.vimrc ~/config/.vimrc
ln -s ~/.zshrc ~/config/.zshrc
ln -s ~/.config/alacritty/alacritty.yml ~/config/allacritty.yml
ln -s ~/.tmux.conf ~/config/tmux.conf
```
5. (Optional) make edits to your configuration files as you see fit.
