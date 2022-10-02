# Hi, I am Darkem

## This repo is for anyone who want to use my dotfiles on my Linux Distro
The distro is Linux Lite. The interface is made with BSPWM as Window Manager, with Polybar and SXHKD. I also use NeoVim as my Editor, with NVChad and the tipically PowerLevel10K and some other plugins.

## Here are some commands you could use to an easy start with my dotfiles:
First, I recommend to move the files to the Documents dir.
~~~
$ ln -s $HOME/Documents/dotfiles/.p10k.zsh ~/.p10k.zsh

$ ln -s $HOME/Documents/dotfiles/.alacritty.yml ~/.alacritty.yml

$ ln -s $HOME/Documents/dotfiles/.vimrc ~/.vimrc

$ ln -s $HOME/Documents/dotfiles/.bashrc ~/.bashrc

$ ln -s $HOME/Documents/dotfiles/.zshrc ~/.zshrc

$ ln -s /home/emmanuel/Documents/dotfiles/.config/nvim/ nvim

$ sudo ln -s $HOME/Documents/dotfiles/.zshrc /root/.zshrc

$ ln -s $Home/Documents/dotfiles/.config/sxhkd/ sxhkd

$ sudo su
$ ln -s /home/(youruser)/Documents/dotfiles/root/.p10k.zsh .p10k.zsh
~~~
