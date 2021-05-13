# Bash script for command line music playing with fuzzy finder

## Dependencies
* mpv
* fzf
* bash

## Installation
'''bash
	./install.sh
'''
## Usage
Run fmupl to select music, run with -l for shuffle. 
Inputing no characters when selecting music will quit and spamming ^C (Ctrl-C) in shuffle mode will quit in shuffle mode
### Adding songs
fmupl reads from a file:
`~/.local/share/music_list.csv`
It is created on installing, and is empty by default.

add songs in this format:
<name of song>,<link to songs>

The link can be a youtube link, or a link from any other site.

NOTE: Do not name two songs the same
