CLI
===

```sh
xdg-user-dir <dirname> # looks up the current path for one of the special XDG user dirs

xdg-user-dirs-update # updates the current state of the users user-dirs.dirs. 
# If none existed before then one is created based on the system default values, or falling back to the old non-translated filenames if such directories exists. 
# The list of old directories used are: ~/Desktop, ~/Templates and ~/Public
```