# vim_configuration

This repository contains a `.vimrc` configuration file for the vim setup that I like to use. This includes:

* No tabs by default, but spaces, for consistency

* Can `ESC` with `jk` or `kj` to require less hand movement

* Relative line number to jump between lines without mental math

* Use same register as regular clipboard by default, so that you can easily copy/paste inside or outside of vim

* Show `$` at the end of each line and `^I` for tabs to more easily check code consistency with white space

* Make `d`, `D`, `c`, `C`, `x`, and `X` not overwrite the register by default, but can still save to register with `,d`, `,D`, `,c`, `,C`, `,x`, and `,X`.

The basic structure comes from http://vim.wikia.com/wiki/Example_vimrc, which gave me a great starting point to customize my vim use.
