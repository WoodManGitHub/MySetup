# MySetup
Place my various environment configuration files and installation scripts.

# Linux
## Dependencies
- clang
- unzip

## Lists
### Shell
- [Fish Shell](https://github.com/fish-shell/fish-shell)
  <details>

  ```
  sudo apt-add-repository ppa:fish-shell/release-4
  sudo apt update
  sudo apt install fish
  ```
  
  </details>

- [Starship](https://github.com/starship/starship)
  <details>

  ```
  curl -sS https://starship.rs/install.sh | sh -s -- -b ~/.local/bin
  ```

  </details>

### Tools
- [tmux](https://github.com/tmux/tmux)
- [fastfetch](https://github.com/fastfetch-cli/fastfetch)

### Setup
- [Chezmoi](https://www.chezmoi.io/)
  <details>

  ```
  sh -c "$(curl -fsLS get.chezmoi.io/lb)" -- init --apply git@github.com:$GITHUB_USERNAME/dotfiles.git
  ```

  </details>

- [Nix](https://nixos.org/)

### Editor
- [Neovim](https://github.com/neovim/neovim)
  <details>
  
  ```
  curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux-x86_64.tar.gz
  sudo rm -rf /opt/nvim
  sudo tar -C /opt -xzf nvim-linux-x86_64.tar.gz
  ```

  </details>

- [NvChad](https://nvchad.com/)
  <details>

  ```
  git clone https://github.com/NvChad/starter ~/.config/nvim && nvim
  ```

  </details>

- [Visual Studio Code](https://code.visualstudio.com/)
