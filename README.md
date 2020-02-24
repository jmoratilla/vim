This project allows to setup a vim editor for basic development.

Just clone this repository into your $HOME directory:

```shell
$ git clone https://github.com/jmoratilla/vim.git ~/.vim
```

and copy the ~/.vim/my.vimrc into your $HOME/.vimrc file

```shell
$ cp ~/.vim/my.vimrc ~/.vimrc
```

Last steps are to initialize and update the submodules

```shell
$ cd .vim
$ git submodule init
$ git submodule update
```

## Little Vim cheatsheet

I use to forget the short keys to manage screens in Vim.

| keys | use |
|:---- |:--- |
| ^W, S| Horizontal split |
| ^W, v| Vertical split |
| ^W, Q| Close current split |
| ^W, \<cursor\> | Switch to adjacent screen |

Also, you can use :sp or :vsp for splitting.

Now enjoy!

