# My .vimrc

In this repo you can find my [vim](https://www.vim.org/) configuration file and how to setup vim on your own machine.

## Description

### Plugins
This config uses [vim-plug](https://github.com/junegunn/vim-plug.git) plugin manager.
The following plugins are used:
- [NERDTree](https://github.com/preservim/nerdtree.git) as file system explorer,
- [Asynchronous Lint Engine (ALE)](https://github.com/dense-analysis/ale.git) for syntax checking and semantic errors,
- [gruvbox](https://github.com/morhetz/gruvbox.git) color theme

### Useful links
- freeCodeCamp's [article](https://www.freecodecamp.org/news/vimrc-configuration-guide-customize-your-vim-editor/) on how to setup vim,


## Installation

To install on your device

1. In the folder where you want to clone the repo enter:
``` 
$ git clone https://github.com/Niceural/my-vimrc.git 
```

2. Copy the file `.vimrc` into your home directory:
``` 
$ cp ./my-vimrc/.vimrc ~/.vimrc 
```

3. Create the folders to hold the dependencies:
``` 
$ mkdir -p ~/.vim ~/.vim/autoload ~/.vim/backup ~/.vim/colors ~/.vim/plugged 
```

4. Install vim-plug:
``` 
$ curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim 
```

5. Install the plugins:
``` 
$ vim ~/.vimrc 

:source % 

:PlugInstall 

:q 

:w 

:source % 

:q 
```

You're good to go!

## Commands cheatsheet

### NERDTree

- `Ctrl` + `w` + `w` cycle though all windows
- `Ctrl` + `w` + `h` takes you left a window
- `Ctrl` + `w` + `j` takes you down a window
- `Ctrl` + `w` + `k` takes you up a window
- `Ctrl` + `w` + `l` takes you right a window
