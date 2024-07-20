# Tmux Dark Plus Theme

**This is a fork of khanghh's repository here**: https://github.com/khanghh/tmux-dark-plus-theme.

I liked the theme but in the bottom right corner the user wasn't displayed properly (instead showing just '#U').
That was the main reason for forking, but this repo will also be used for any other possible personalized further changes.
For now I've just removed the #U.

The rest of this readme is (almost verbatim) from the upstream repository.

Dark+ theme for Tmux.

## Installation

### Install using [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

1.  Add plugin to the list of TPM plugins in `.tmux.conf`:

        set -g @plugin 'juhoerv/tmux-dark-plus-theme'

2.  Hit `prefix + I` to fetch the plugin and source it. The theme should now be working.

## Themes

**Default:**

<p align="center"><img src="./screenshots/preview2.png"/></p>

## Plugin support

### [tmux-prefix-highlight](https://github.com/tmux-plugins/tmux-prefix-highlight)

Plugin that highlight the tmux _prefix_- key status.

<p align="center"><img src="./screenshots/prefix_highlight.png"/></p>

## License

MIT
