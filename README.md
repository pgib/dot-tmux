# Installing

```sh
cd ~
git clone https://github.com/pgib/dot-tmux.git .tmux
cd .tmux
git submodule init
git submodule update
cd ..
[ -e ~/.tmux.conf ] && mv ~/.tmux.conf ~/.tmux.conf-orig
ln -s ~/.tmux/tmux.conf ~/.tmux.conf
ln -s ~/.tmux/tmux-powerline/tmux-powerlinerc.conf ~/.tmux-powerlinerc
```

### Notes

This is intended for use under macOS. Please ensure you have installed
reattach-to-user-namespace.

```
brew install reattach-to-user-namespace
```



