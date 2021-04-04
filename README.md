# Rowan's dotfiles

## Getting started
``` sh
  curl -Lks https://raw.githubusercontent.com/RowanMcDonald/dotfiles/master/.bin/setup_dotfiles | /bin/bash
```

## References

Strategy adopted from: https://www.atlassian.com/git/tutorials/dotfiles


## Todos

projections not working outside of rails?

Create a minimal version of vimrc so we get fast boot
https://www.wezm.net/technical/2019/10/useful-command-line-tools/

setup startify to have a git branches section
https://www.reddit.com/r/neovim/comments/ewgo9g/fzf_floating_tab_select/
# look into lazygit
https://github.com/camspiers/dotfiles/blob/master/files/.config/nvim/init.vim#L445-L522

look at http://boredzo.org/blog/archives/2016-08-15/colorized-man-pages-understood-and-customized

TIL
 1. man bash is great
 2. the meta key for bash readline is `esc` -> CAPS 
 3. cut and paste with ctrl-k ctrl-y
 https://readline.kablamo.org/emacs.html


Setup something that raises if config files are dirty.

rg --vimgrep  |  wc -l

How does `:g/-/norm nD` work?  https://stackoverflow.com/questions/37293734/vim-delete-starting-from-character-to-end-of-line

Navigate quickfix lists
:cold
https://thepugautomatic.com/2014/03/stacked-vim-searches-down-cold/
