# clone tpm into plugins repo
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm


### just make sure to do the installation related stuff
`Ctrl-a, Shift-i`

tmux packages 
```
git clone https://github.com/tmux-plugins/tmux-continuum
git clone https://github.com/tmux-plugins/tmux-resurrect
git clone https://github.com/jimeh/tmux-themepack
git clone https://github.com/tmux-plugins/tpm
git clone https://github.com/christoomey/vim-tmux-navigator
```

symlink to dotfiles
`sudo ln -s /path/to/dotfiles/* .config/`



### random command to imporve battery when sleeping, not to do with tmux
```
sudo kernelstub -a mem_sleep_default=deep
```
