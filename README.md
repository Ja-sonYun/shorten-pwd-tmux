# shorten-pwd-tmux
![Alt text](https://github.com/Ja-sonYun/shorten-pwd-tmux/blob/main/sampleimage.png?raw=true "sample")
===
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
