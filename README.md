# shorten-pwd-tmux

add
```
setw -g window-status-format '#(path/to/getshortenpwd.sh "#{pane_current_path}")'
```
to your .tmux.conf and reload your tmux.  
your path will print like below
```
original pwd: /Users/test/Desktop 
with this script: /Us/te/Desktop
```
