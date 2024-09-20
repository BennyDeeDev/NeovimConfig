# My Neovim Configuration

This is my way of using [Neovim](https://github.com/neovim/neovim), I use
[LazyVim](https://github.com/LazyVim/LazyVim) as a starter.

## Requirements

- GUI Terminal, I use [iTerm2](https://github.com/gnachman/iTerm2) but might
  migrate to [WezTerm](https://github.com/wez/wezterm)
- [LazyGit](https://github.com/jesseduffield/lazygit) installed,
- [Nerdfont](https://www.nerdfonts.com/font-downloads) installed, I use
  [Fira Code](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/FiraCode.zip)
- [Telescope](https://github.com/nvim-telescope/telescope.nvim) needs
  [FD](https://github.com/sharkdp/fd) and
  [RipGrep](https://github.com/BurntSushi/ripgrep) installed, both can be
  installed by `brew`
- `Rust`, `Node`, `Prettier` and `Eslint` installed
  `brew install node rust prettier eslint`

## Fixes

- Markdown Preview doesn't work by default, run
  `~/.local/share/nvim/lazy/markdown-preview.nvim/app/install.sh`

## Helpful Links

- <https://stackoverflow.com/questions/9164405/vim-surround-inserts-extra-space-around-the-word>
- <https://www.reddit.com/r/neovim/comments/13pr3nn/how_to_switch_focus_between_the_terminal_buffer>
- <https://vi.stackexchange.com/questions/39247/how-to-integrate-an-own-vim-color-scheme-into-neovim>
- <https://github.com/iamcco/markdown-preview.nvim/issues/637>
