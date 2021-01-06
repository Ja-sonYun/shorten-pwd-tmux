# shorten-pwd-tmux

add
```
setw -g window-status-format '#(path/to/getshortenpwd.sh "#{pane_current_path}")'
```
to your .tmux.conf and reload your tmux.
