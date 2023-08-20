# tmux shortcuts


tmux new-session  -s mysession

tmux kill-session -t mysession

tmux attach-session  -t mysession

# list all tmux sessions

tmux ls

ctrl + b "

ctrl + b %

# tabs creation

ctrl + b c 

ctrl + b n (next tab)

ctrl + b x (close tab)

# navigation (replacement from mouse scroll)

ctril + b + [ or ]

Esc key to exit from navigation mode



# archive
## enable mouse:

setw -g mouse on

## copy content in tmux window

ctrl + shift + mouse selection

then use ctrl+shift+c

# TMUX plugin manager installation :

https://github.com/tmux-plugins/tpm


ctrl + b + I : will result in updates of the plugins added in tmux configuraiton file


# Saving the session of TMUX

- tmux-continuum
- tmux-resurrect

  Above plugins are used to save the state of the session .. 


