Custom vimrc
============

My custom .vimrc


# Features

# Installation

First, you need to install Vundle:
```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

Now you can install the color schemes:
```
git clone https://github.com/flazz/vim-colorschemes.git
mv vim-colorschemes/colors ~/.vim/
rm -Rf vim-colorschemes
```

Then download the base file:
```
curl -s -o ~/.vimrc https://raw.githubusercontent.com/vsmoraes/vimrc/master/.vimrc
```

Now you can start installing the plugins:
```
vim -c PluginInstall -c qall
```
