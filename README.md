# LazyVim Configuration

This repository contains my personal configuration for Neovim based on **LazyVim**.

## Installation

Clone this repository into your Neovim configuration directory:

```bash
git clone https://github.com/<username>/<repo-name>.git ~/.config/nvim
```

Then start Neovim:

```bash
nvim
```

On the first launch, **Lazy.nvim** will automatically install LazyVim and all required plugins.

## Structure

```
~/.config/nvim
├── init.lua
├── lazyvim.json
├── lua
│   ├── config
│   │   ├── autocmds.lua
│   │   ├── keymaps.lua
│   │   ├── lazy.lua
│   │   └── options.lua
│   └── plugins
│       └── ...
```

## Credits

This configuration is based on the excellent **LazyVim** distribution.
