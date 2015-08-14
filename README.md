### Focagrandes Dotfiles

#### PuTTY, colors and Terminal type

```
sudo apt-get install ncurses-term
```

- For 256 color mode, do the following

     - In Window > Colours, check "Allow terminal to use xterm 256-colour mode"
     - In Connection > Data, change your "Terminal-type string" to "putty-256color"

#### Setup

     cd
     git clone https://github.com/focagrande/dotfiles.git
     ln -s ./dotfiles/vim .vim
     ln -s ./dotfiles/vimrc .vimrc
     ln -s ./dotfiles/tmux.conf .tmux.conf
