# Mojave vim theme
## A dark, desert inspired vim theme, optimized for 256-color terminals

Mojave is a dark vim theme optimized for 256-color terminals. The theme takes inspiration from the colors of the desert. You can [preview the mojave theme here](http://vimcolors.com/387/mojave/dark).

This theme is based on the "desert" theme by Hans Fugal <hans@fugal.net> and some subsequent modifications by Henry So, Jr. <henryso@panix.com>.  I've used the original theme for years and introduced a sizable number of modifications to make it run better in 256-color terminals. Personally, I find this theme easy on the eyes and well suited for long sessions of editor use.

Keep in mind that this theme is a constant work in progress. I use editors all day and once in a while I'll stumble on some color combination that I don't quite like. When that happens, I'll update the theme and push a change. Fork this repository if you prefer a theme that will never change, or keep pulling newer versions if you like my fixes and improvements.

# Installation

## Using Vundle

If you're using Vundle, just add the following to your `~/.vimrc` file:

```VimL
Plugin 'marcopaganini/mojave-vim-theme'
colorscheme mojave
```

While still inside vim, type: `<ESC>:PluginInstall`. This should install the theme automatically. Restart vim and the new theme should be the default.

## Manual installation

Manual installation is very simple: Download the [mojave.vim](https://github.com/marcopaganini/mojave-vim-theme/blob/master/colors/mojave.vim) file from the repository and copy it into your `~/.vim/colors` directory. Edit your `~/.vimrc` file and add:

```VimL
colorscheme mojave
```
Restart vim and everything should work.

A better (but slightly more complicated) option is to git clone this repository somewhere in your disk and create a symlink from the `termschool.vim` file inside your working repository to `~/.vim/colors`.

## Caveats

Please note that this theme *requires* a 256-color capable terminal. Most popular terminals are 256-color capable these days, but if things look odd, your terminal might not have this capability.

If you know your terminal is 256-color capable and things still look ugly/weird, try adding the following to your `~/.vimrc` file right before the `colorscheme termschool` line:

```VimL
set t_Co=256                                                                                        
```

This will force vim to use 256 colors.

Note that the theme has been tuned for 256-color terminals (I just can't match the productivity of screen + vim on gvim) but should also work fine for GUI environments.

Feel free to send comments with ideas, suggestions and push requests.

# Related links

* I also maintain [termschool](http://github.com/marcopaganini/termschool-vim-theme), a theme based on codeschool, optimized for 256-color terminals.

* If you have some time to spare, consider a trip to a real desert. It can be a [life](https://goo.gl/StMiB7) [changing](https://goo.gl/QEvm1U) [experience](https://goo.gl/toc5QX). If you like these, visit my page at http://www.paganini.net for many other albums of desert trips.
