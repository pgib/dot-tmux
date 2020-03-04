# Installing

```sh
cd ~
git clone https://github.com/pgib/dot-tmux.git .tmux
cd .tmux
git submodule init
git submodule update
cd ..
[ -e ~/.tmux.conf ] && mv ~/.tmux.conf ~/.tmux.conf-orig
ln -s .tmux/tmux.conf
```

