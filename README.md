# my-keymaps
A backup for the config file of my computer.

## Usage ##

Change <kbd>Capslock</kbd> to <kbd>Ctrl_R</kbd> in console.
Change <kbd>Alt_R</kbd> to <kbd>Esc</kbd> in console.

**NOTE:** Only work in console.
NOT X11.
See [Freed-Wu/my-x11-keymaps](http://www.github.com/Freed-Wu/my-x11-keymaps) to
know keymaps in X11.

## Install ##

```{bash}
cd /usr/share/keymaps/i386/qwerty/
sudo chown $USERNAME .
sudo chgrp $USERNAME .
git clone git@github.com:Freed-Wu/my-keymaps.git
mv my-keymaps/* . && rm my-keymaps
sudo echo KEYMAP=us-custom >> /etc/vconsole.conf
```

