```
# mac-init
# ####################
# initialization script for macOS
# mac-init [fhlv] [list-directory]
# curl https://raw.githubusercontent.com/leannafen/mac-init/main/mac-init | \
# bash -s -- [fhlv] [list-directory]
# 
# I used Mike McQuaid's strap but constantly had
# issues with it (it not using my Brewfile, 
# git not being configured automatically, etc.)
# so I just made my own script. It's still missing
# quite a few things, but that comes later.
#
# options
# ####################
# f - Directory to read lists from..
# 	if omitted, script will look for lists in
# 	~/.config/mac-init/programs/
# h - Print help text.
# l - Print license.
# v - Print software version and exit.
#
# todo
# ####################
# * Neovim setup functions
# 	* need a find a way to run neovim headless
# * automated git config
# * initialize function (creates files & folders for you)
# * pull from gh repo?
```
