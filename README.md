## Milktea

milktea is a theme generated by [tmuxline](https://github.com/edkolev/tmuxline.vim).

It's a config file of tmux which has to be loaded to tmux.conf

## Installation
1. Install tmux

    - Mac users:
        ```brew install tmux```

    - Unix users:
        ```sudo apt-get install tmux```
2. copy milktea to a folder e.g. ~/tmux_themes/
3. edit .tmux.conf in your home fold:er (if it doesn't exist, create one)
4. add ```if-shell "test -f tmux_themes/milktea" "source tmux_themes/milktea"``` at the end of the file. (tmux_themes can be any folder where milktea is).

Ok, done. Now you have a stylish tmux theme! Enjoy it.