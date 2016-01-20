# Role: tmux

Configuration of tmux for SOSETH use.
Differences to vanilla tmux:
- Alt-x as an additional prefix
- M-x or M-b to send prefix (useful for nested tmux in, say, ssh)
- mouse support: Click on tabs or use your mouse wheel to scroll. Can be disabled using M-M and reenabled using M-m
- Powerline configured

## TODO: custom powerline config
- In theory, powerline loads it's config from /usr/share or ~/.config/<something> but according to https://github.com/powerline/powerline/blob/develop/powerline/config.py there is a DEFAULT_SYSTEM_CONFIG_DIR which looks promising but is completely undocumented as far as I can see. I'll look into this as I don't want to edit package-provided files ;)
- We probably only need load, hostname and maybe the current time