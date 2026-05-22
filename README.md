# mz-dotfiles
This are my dotfiles with configurations of some tools I have in daily use. At the moment there are only configs for kitty (terminal emulator) and the zsh shell.
## Getting started
### Prerequisites
- [zsh](https://www.zsh.org/) must be installed
    - please run `zsh --version` to confirm
    - expected result: `zsh 5.0.8` or more recent
- zsh should be set as default shell
    - run `echo $SHELL`from a new terminal window
    - expected result `/usr/bin/zsh`or similar
    - to make zsh your default shell, use `chsh -s $(which zsh)` or on Fedora use `sudo chsh $USER`
- [kitty](https://sw.kovidgoyal.net/kitty/) must be installed
    - install it as described on the website
### Additional
For best use of my [zsh] and [kitty] dotfiles/config-files the following tools are recommended:
- [oh my zsh](https://github.com/ohmyzsh/ohmyzsh) for managing the [zsh] configuration
- [powerlevel10k](https://github.com/romkatv/powerlevel10k) as nice [zsh] theme
- do not forget to install some [Nerd-Fonts](https://github.com/ryanoasis/nerd-fonts/releases/tag/v3.4.0) like Meslo (as used in my config). The user fonts are usually stored under `~/.local/share/fonts` or system wide `/usr/share/fonts/` or `/usr/local/share/fonts/`.
## Installation
To install all the tools, follow the instructions on the responsible websites (see links above).
After that, replace the dotfiles/config-files with the ones from this repository.
- replace `~/.zshrc` with the one from this repo
- replace `~/.config/kitty/kitty.conf` and `~/.config/kitty/current-theme.conf` with the ones from the repo
>[!NOTE] Note
>You can also follow the instructions from the tools like [zsh], [kitty], [oh my zsh] and [powerlevel10k] to make your own config.
## License
MIT
