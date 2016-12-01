# Dotfiles

> screenshots, backup, and overview of my dev settings for my own reference. If it's useful to others then that's cool


## Settings Previews


### Desktop

![img](previews/desktop-1.png)

### Vim configuration

#### Custom font and glyphs

![img](previews/custom-glyphs.png)

* Showing
  * file type glyphs from [VimDevIcons][vim-devicons]
  * font from [Nerd Fonts][nerd-fonts]

#### JavaScript development

![img](previews/vim-js-development-1.png)

* Showing
  * custom separators and column number glyphs from [Powerline Extra Symbols][powerline-extra-symbols]
  * file type glyphs from [VimDevIcons][vim-devicons]
  * custom [syntastic][syntastic] glyphs
  ```vim
    let g:syntastic_style_error_symbol = '⚡'
    let g:syntastic_error_symbol = '✗'
    let g:syntastic_warning_symbol = '⚠'
  ```
  * [JSCS][jscs]
  * [JSHint][jshint]
* Vim JS development related plugins in use
  * [Syntastic][syntastic]
  * [JSDoc.vim][vim-jsdoc]

### Terminal

![img](previews/bash-terminal-1.png)

* Showing [Milkbikis' Powerline Shell][powerline-shell]

### Bash Aliases

* git
  * `g`
* git branch
  * `gb`
* git commit -a -m
  * `gcam`
* git checkout
  * `gco`
* git diff
  * `gd`
* git diff --cached
  * `gdc`
* gitk &
  * `gk`
* gitk --all &
  * `gka`
* git pull
  * `gp`
* git rev-parse HEAD | cut -c -7
  * `grev`
* git status
  * `gs`
* git fetch pull
  * `gfpull`
* git fetch push
  * `gfpush`
* git track (create new tracking branch)
  * `gt`
* git version (tag and branch at a specific deploy point)
  * `gv`

### Tmux

* todo

[vim-devicons]:https://github.com/ryanoasis/vim-devicons
[powerline-extra-symbols]:https://github.com/ryanoasis/powerline-extra-symbols
[syntastic]:https://github.com/scrooloose/syntastic
[jscs]:https://github.com/jscs-dev/node-jscs
[jshint]:https://github.com/jshint/jshint
[vim-jsdoc]:https://github.com/heavenshell/vim-jsdoc
[powerline-shell]:https://github.com/milkbikis/powerline-shell
[nerd-fonts]:https://github.com/ryanoasis/nerd-fonts
