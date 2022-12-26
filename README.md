# dotfiles

## Prerequisites
Install dependencies:
```
sudo pacman -S xorg-server xorg-xinit \
  i3-gaps i3status dmenu rxvt-unicode \
  ttc-iosevka zsh
```
Copy configuration(s):
```
mkdir -p ~/.config/i3 ~/.config/i3status \
  ~/doc/template ~/doc/share ~/tmp ~/.bin
cp i3-gaps ~/.config/i3/config
cp i3status ~/.conig/i3status/config
sudo cp vimrc /etc
cp Xresources ~/.Xresources
cp user-dirs.dirs ~/.config
cp xinitrc ~/.xinitrc
cp zshrc ~/.zshrc
```
