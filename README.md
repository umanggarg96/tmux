# Sessions
```bash

tmux # launch tmux with an unnamed session

exit # to exit-out of the session. this will close/kill that session too
 
# creates a new session with the name 'basic'
tmux new-session -s basic
tmux new -s basic # short for above

# create a new session but do not attach
tmux new -s new_session -d

# create a new session with named window
# creates a new session windwos with a window named shell
tmux new -s windows -n shell


# list running sessions
tmux list-sessions 
tmux ls # short for above

# attach to a session
tmux attach # attach to last connected session
tmux attach -t <session> # connect to named session

# kill session
tmux kill-session # kills the last active session
tmux kill-session -t <session> # kills the named session
```
