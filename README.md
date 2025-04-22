# toggle-fullscreen.nvim

Neovim lua plugin that toggles fullscreen for the selected window

![](media/toggle.gif)

# 📦 Installation

With [lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{
  "propet/toggle-fullscreen.nvim",
  keys = {
    {
      "<leader>f",
      function()
        require("toggle-fullscreen"):toggle_fullscreen()
      end,
      desc = "toggle-fullscreen"
    },
  },
}
```

# 🚀 Usage

Press the keymap (by default `<leader>f`) to toggle fullscreen mode for the currently selected buffer.
