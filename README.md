# My i3 setup
## Swap Esc and Caps-lock
In ```~/.xsessionrc``` (Debian based), add the following
```
setxkbmap -option caps:swapescape
```
If you are a Vim user there is no excuse for not doing it.

## Speed up the keyboard
In ```.xsessionrc``` (Debian based) add the following to adjust the delay and repeat rate
```
xset r rate 180 40
```

## Screen resolution, multiple monitor
Ok, then, mmm, this is actually a very tedious part.
I am still using X.Org but moving towards Wayland.  
Long story short, I have two screen setup, a HD and 4k screens.
At the moment, I just use native resolution, no system scaling, just rescaling the font of each application on my needs.
Waiting for a better solution, but I kind of like it the way it is now.

## Deadkeys i.e. how to write non-us character
Again, Debian based, everything is provided out-of-the-box with intl. keyboard, composite and dead keys.
```
sudo dpkg-reconfigure keyboard-configuration
```

## Edit on i3 config
Extra options and mappings:
- Add specific workspaces
- use back-and-forth 
- remap ```jkl;``` into ```hjkl``` (Vim-like)
- move workspace to another screen
