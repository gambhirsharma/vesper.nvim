# vesper.nvim
Vesper ColorScheme for NeoVim

## Installation
### `lazy.nvim`
```vesper.lua
{
  "gambhirsharma/vesper.nvim",
  lazy = false,
  priority = 1000,
  config = function ()
   vim.cmd([[colorscheme vesper]])
  end
}
```
