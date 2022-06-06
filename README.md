# luavimconf

minimalistic neovim config

## Requirements
 - python 3 
 - neovim >=7.0
 - nodejs >=latest-lts
 - fd
 - ripgrep
 - a terminal that supports nerdfonts(preferably alacritty)

## Installation

```
git clone https://github.com/uneconomicalfairy14/luavimconf.git ~/.config/nvim 
```
```
sudo pacman -S python3-pip neovim fd ripgrep
```

## LSP Support

works out of the box
```
nvim +LSPInstall <the language server>
```

## Plugins used
 - use "wbthomason/packer.nvim" -- Have packer manage itself
 - use "nvim-lua/popup.nvim" -- An implementation of the Popup API from vim in Neovim
 - use "nvim-lua/plenary.nvim" -- Useful lua functions used ny lots of plugins
 - use "windwp/nvim-autopairs" -- Autopairs, integrates with both cmp and treesitter
 - use "numToStr/Comment.nvim" -- Easily comment stuff
 - use "kyazdani42/nvim-web-devicons"
 - use "kyazdani42/nvim-tree.lua"
 - use "akinsho/bufferline.nvim"
 - use "nvim-lualine/lualine.nvim"
 - use "akinsho/toggleterm.nvim"
 - use "ahmedkhalf/project.nvim"
 - use "lewis6991/impatient.nvim"
 - use "lukas-reineke/indent-blankline.nvim"
 - use "glepnir/dashboard-nvim"
 - use "antoinemadec/FixCursorHold.nvim" -- This is needed to fix lsp doc highlight
 - use "folke/which-key.nvim"
 
 - use({
        "catppuccin/nvim",
        as = "catppuccin"
  })

 - use "hrsh7th/nvim-cmp" -- The completion plugin
 - use "hrsh7th/cmp-buffer" -- buffer completions
 - use "hrsh7th/cmp-path" -- path completions
 - use "hrsh7th/cmp-cmdline" -- cmdline completions
 - use "saadparwaiz1/cmp_luasnip" -- snippet completions
 - use "hrsh7th/cmp-nvim-lsp"

 - use "L3MON4D3/LuaSnip" --snippet engine
 - use "rafamadriz/friendly-snippets" -- a bunch of snippets to use
 - use {'dsznajder/vscode-es7-javascript-react-snippets',
 - use "neovim/nvim-lspconfig" -- enable LSP
 - use "williamboman/nvim-lsp-installer" -- simple to use language server installer
 - use "tamago324/nlsp-settings.nvim" -- language server settings defined in json for
 - use "jose-elias-alvarez/null-ls.nvim" -- for formatters and linters

 - use "nvim-telescope/telescope.nvim"

 - use {
    "nvim-treesitter/nvim-treesitter",
    run = ":TSUpdate",
  }
 - use "JoosepAlviste/nvim-ts-context-commentstring"

 - use "lewis6991/gitsigns.nvim"

# ScreenShots

- <img src="https://github.com/uneconomicalfairy14/luavimconf/blob/master/assets/Screenshot%20(6).png?raw=false"/>
- <img src="https://github.com/uneconomicalfairy14/luavimconf/blob/master/assets/Screenshot%20(7).png?raw=false"/>
- <img src="https://github.com/uneconomicalfairy14/luavimconf/blob/master/assets/Screenshot%20(8).png?raw=false"/>
- <img src="https://github.com/uneconomicalfairy14/luavimconf/blob/master/assets/Screenshot%20(9).png?raw=false"/>
- <img src="https://github.com/uneconomicalfairy14/luavimconf/blob/master/assets/Screenshot%20(10).png?raw=false"/>
- <img src="https://github.com/uneconomicalfairy14/luavimconf/blob/master/assets/Screenshot%20(11).png?raw=false"/>


