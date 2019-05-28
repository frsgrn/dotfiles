# dotfiles
Clone the dotfiles repository to your home directory.
```bash
$ git clone https://github.com/frsgrn/dotfiles.git
```
Create symlinks for all the config files. Make sure to remove previously existing config files.
```bash
$ ln -sf ~/dotfiles/.config/polybar ~/.config/
$ ln -sf ~/dotfiles/.config/i3 ~/.config/
$ ln -sf ~/dotfiles/.config/compton.conf ~/.config/compton.conf
```
