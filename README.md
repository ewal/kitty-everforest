# Everforest themes for Kitty terminal

Based on the [vim theme](https://github.com/sainnhe/everforest) made by [sainnhe ](https://github.com/sainnhe).

## Installation
Download the theme(s) and put them in the kitty theme folder.
The themes will be available when running `kitty +kitten themes`.

## (Neo)Vim
The Everforest themes for (neo)vim can be found here https://github.com/sainnhe/everforest

## Tmux
I'd recommend [Tmuxline](https://github.com/edkolev/tmuxline.vim) to automatically create a Tmux theme.
Create a `snapshot` and add it to your tmux conf file to persist the theme on restarts.
Append this line `set -wg mode-style bg=*selection_background,fg=**selection_foreground` to make selections follow the theme in copy mode.

_(*selection_background = eg. #503946)_<br />
_(**selection_foreground = eg. #9da9a0)_
