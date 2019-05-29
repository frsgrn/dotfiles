# dotfiles
Clone the dotfiles repository to your home directory.
```bash
$ git clone https://github.com/frsgrn/dotfiles.git
```
Create symlinks for all the config files in the repository. Make sure to remove existing config files/directories before attempting to symlink.
```bash
$ rm -rf ~/.config/polybar && ln -sf ~/dotfiles/.config/polybar ~/.config/ # If polybar is installed
$ rm -rf ~/.config/i3 && ln -sf ~/dotfiles/.config/i3 ~/.config/ # Config created for i3-gaps
$ ln -sf ~/dotfiles/.config/compton.conf ~/.config/compton.conf # If compton is installed
$ ln -sf ~/dotfiles/.config/gtk-3.0/gtk.css ~/.config/gtk-3.0/gtk.css # If you're using GNOME-terminal
```
