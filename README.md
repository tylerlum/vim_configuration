# vim_configuration

![vim](https://user-images.githubusercontent.com/26510814/107433470-35a19d00-6ade-11eb-9fa6-557bebc9a068.gif)

_Example of Copy-Delete-Paste Workflow_

This repository contains a `.vimrc` configuration file for the vim setup that I like to use. This includes:

* No tabs by default, but spaces, for consistency

* Can `ESC` with `jk` or `kj` to require less hand movement

* Relative line number to jump between lines without mental math

* Use same register as regular clipboard by default, so that you can easily copy/paste inside or outside of vim

* Show `$` at the end of each line and `^I` for tabs to more easily check code consistency with white space

* Make `d`, `D`, `c`, `C`, `x`, and `X` not overwrite the register by default, but can still save to register with `,d`, `,D`, `,c`, `,C`, `,x`, and `,X`.

* Find occurrences of variable by hoving over the variable and pressing `*`

* Enter blank lines from command mode with <Enter>, so you can create 70 blank lines with 70<Enter>

* Autocomplete with `CTRL+n`, then scroll down with `CTRL+n` and scroll up with `CTRL+p`

* Delete and paste word in one click with `r` and `R`

The basic structure comes from http://vim.wikia.com/wiki/Example_vimrc, which gave me a great starting point to customize my vim use.


Check out my blog posts for more information about my vim setup, with example gifs!

* [7 Surprising Vim Tricks That Will Save You Hours](https://levelup.gitconnected.com/7-surprising-vim-tricks-that-will-save-you-hours-b158d23fe9b7)

* [8 Vim Tricks That Will Take You From Beginner to Expert](https://medium.com/swlh/8-vim-tricks-that-will-take-you-from-beginner-to-expert-817ff4870245)
