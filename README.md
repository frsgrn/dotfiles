# dotfiles
## Installation tips
Clone the dotfiles repository to your home directory.
```bash
$ git clone https://github.com/frsgrn/dotfiles.git
```
Create symlinks for all the config files in the repository. Make sure to remove existing config files/directories before attempting to symlink.
```bash
$ rm -rf ~/.config/polybar && ln -sf ~/dotfiles/.config/polybar ~/.config/ # If polybar is installed
$ rm -rf ~/.config/i3 && ln -sf ~/dotfiles/.config/i3 ~/.config/ # Config created for i3-gaps
$ ln -sf ~/dotfiles/.config/compton.conf ~/.config/compton.conf # If compton is installed
$ ln -sf ~/dotfiles/.Xresources ~/.Xresources # If you're using urxvt
```
## Required packages
```bash
(Available from aptitude)
$ sudo apt-get install rxvt-unicode xclip scrot maim fonts-powerline rofi feh playerctl compton
```
[Polybar](https://www.reddit.com/r/linux4noobs/comments/9690ia/how_do_i_install_polybar_on_ubuntu_1804/ecjh4hn?utm_source=share&utm_medium=web2x)
[I3-gaps](https://gist.github.com/boreycutts/6417980039760d9d9dac0dd2148d4783)
