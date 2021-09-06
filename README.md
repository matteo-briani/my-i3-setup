# My i3 setup
## Swap Esc and Caps-lock
In ```~/.xsessionrc``` (Debian based), add the following
```
setxkbmap -option caps:swapescape
```
## Speed up the keyboard
In ```.xsessionrc``` (Debian based) add the following to adjust the delay and repeat rate
```
xset r rate 180 40
```
