# Ghostty

[Ubuntu] fix unrecognized terminal for the root user:

```
infocmp -x xterm-ghostty | sudo tic -x -o /etc/terminfo -
```
