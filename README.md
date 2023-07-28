# gruvbox.nvim

A truecolor, solarized dark colorscheme using [tjdevries/colorbuddy.vim](https://github.com/tjdevries/colorbuddy.vim) for neovim.
Source from [svrana/neosolarized.nvim](https://github.com/svrana/neosolarized.nvim)

## Limitations

- dark only
- termguicolors only
- neovim only

## Prerequisites

Make sure you have [colorbuddy](https://github.com/tjdevries/colorbuddy.vim) installed.

### Setup

```
lua << EOF
  require('gruvbox').setup({
    comment_italics = true,
    background_set = false,
  })
EOF
```
