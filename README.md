# lightline-nord-sane

This is forked version of the stock 'nord' color scheme for
[vim-lightline](https://github.com/itchyny/lightline.vim), whose color
switching behaviour is intended to align better with the other stock Lightline
themes.

I made this modified version, to ensure there are three distinct colours on
the right hand side of the stock Lightline toolbar, and to add the 'active mode'
color there, for the sake of consistency.  The mode colour assignments have
been tuned a little.  However, the actual Nord colour values themselves remain
unchanged.

Feedback and pull requests are welcome.

## Installation

Either use your favourite plugin manager to install it, e.g.

`Plug 'benfowler/lightline-nord-sane` (vim-plug)

or put the `autoload/` folder and its contents under `~/.vim/`.


### Configuration

Set the Lightline colour scheme like so:

`let g:lightline.colorscheme="nord_sane"`

If like me, however, you have more extensive Lightline configuration, you can
configure it this way:

```vimscript
let g:lightline = {
  \ 'colorscheme': 'nord_sane',
  \
}
```

If you get stuck, the [Lightline
documentation](https://github.com/itchyny/lightline.vim) is an excellent place
to start.

