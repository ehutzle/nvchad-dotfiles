### Install NVChad 
`git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1`

### Install Nvim Configuration
```
git clone git@github.com:ehutzle/nvchad-dotfiles.git \
  ~/.config/nvim/lua/custom/ --depth 1
```

### Sync Plugins and Update LSP
- Open Neovim and run the following:
  - `:Lazy sync`
  - `:MasonInstallAll`
