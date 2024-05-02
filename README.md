# dev-environment-files
## Assumptions:
- Mac (primary)
- This should work with modifications for linux/WSL2


## Neovim Setup:
- Heavily inspired from: https://github.com/josean-dev/dev-environment-files

### Setup 
- True Color Terminal Like: [WezTerm](https://github.com/wez/wezterm)
- Neovim (Version 0.9 or Later)
- Nerd Font - I use Meslo Nerd Font
- Ripgrep - For Telescope Fuzzy Finder
- XCode Command Line Tools


Wezterm:
```
brew install --cask wezterm
```
  - Config files in mac are located `~/.config/wezterm/wezterm.lua`
  - Find the config path by starting WezTerm, press `CTRL-SHIFT-L` to open the debug overlay, then type `wezterm.config_file` and press enter

Nerd font: 
```
brew tap homebrew/cask-fonts
brew install font-meslo-lg-nerd-font
```

Neovim:
```
brew install neovim
```

Ripgrep:
```
brew install ripgrep
```

Xcode:
```
xcode-select --install
```
