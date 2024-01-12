# Tmux config

This is not the best config overall, just my basic mine.

## Why Tmux ?

try it and you figure out.

## Installation

### Install Tmux

You can install tmux with your favorite package manager.
[See there](https://github.com/tmux/tmux/wiki/Installing) for more details.

### Install TMP

Tmp is tmux's package manager. Git will be required to install it.
[See there](https://github.com/tmux-plugins/tpm).

## Configuration

You can store the configuration at :

1. `$HOME.tmux.conf`
2. `XDG_CONFIG_HOME/tmux/tmux.conf`
3. `$HOME/.config/tmux/tmux.conf`
   (the option 2 is an alias for the option 3. I use the opt 3 directly.)

### Plugins

| name          | find it                                                   | why                                                                                                                                                                    |
| ------------- | --------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| tpm           | [here](https://github.com/tmux-plugins/tpm)               | the package manager itself                                                                                                                                             |
| tmux-sensible | [here](https://github.com/tmux-plugins/tmux-sensible)     | Add option / fix some bug in basic tmux option                                                                                                                         |
| vim-navigator | [here](https://github.com/christoomey/vim-tmux-navigator) | Allow moove in Tmux pan as in Nvim. You will find this package in my [nvim config](https://github.com/romainpostel/nvim) too, to allow nvim to moove to next tmux pan. |

Don't forget to `tmux source ~/.config/tmux/tmux.conf` to reload your config when adding plugins or setting some opt.
Or restart tmux.

## How to use

Too long to write. Go there : [tmuxcheatsheet](https://tmuxcheatsheet.com)
