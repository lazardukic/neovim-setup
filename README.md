# Neovim setup

Neovim setup that includes:
- tokyonight colorscheme (modified)
- configured options and keymaps
- useful plugins

Credits to the original author: `Josean Martinez`
Here are links to his detailed step by step walkthrough:
Youtube: https://www.youtube.com/watch?v=6pAG3BHurdM
Blog:    https://www.josean.com/posts/how-to-setup-neovim-2024

You will need:
- true color terminal e.g. iterm2
- homebrew

Install with homebrew in the following order:

1. install neovim with `brew install neovim`
verify installation with `nvim --version`

2. install nerd fonts with `brew install font-meslo-lg-nerd-font`
Then, in iterm2, go to settings (cmd+,) - under profile/text select MesloLGS Nerd Font Mono

3. `brew install ripgrep`
verify with `ripgrep --version`

4. install node with `brew install node`
verify with `node -v`

5. clone this repository

6. in your .config/ directory, create a folder called nvim

7. copy the files from this repo to the 'nvim' folder you just created

