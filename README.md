# linux-tipsies

 Little things that help me use linux. Also for my own future reference.




## Enable Autoscroll on Chromium/Electron Apps

Add this to the command line argument while opening a program (like brave, discord, etc). [Credits and details](https://medium.com/@1nikolas/linux-enable-middle-mouse-button-scrolling-on-chrome-ium-and-electron-apps-discord-etc-ab2d0a213505).

`--enable-blink-features=MiddleClickAutoscroll`


## Custom Keyboard Layout

Set up and use [kmonad](https://github.com/kmonad/kmonad). You can also set it up to have 'layers' on your keyboard which is very handy.


## Ditch Nautilus

Switch to Nemo or Thunar (or whatever you like) file manager instead of Nautilus if you use gnome. And set it as default using this command.

`xdg-mime default thunar.desktop inode/directory application/x-gnome-saved-search` (or)

`xdg-mime default nemo.desktop inode/directory application/x-gnome-saved-search`

Though it still doesn't set it as default for when you open a file manager through 'Save As' or 'Open' (or etc) from another application. Feel free to contribute a fix.

## Customize Touchpad Gestures

Using `touchegg`. It may be pre-installed on you OS and you can just configure the config file (potentially located at `~/.config/touchegg/touchegg.conf`) with the help of [touchegg's documentation](https://github.com/JoseExposito/touchegg). Or more easily using this GUI app for touchegg called [Touché](https://github.com/JoseExposito/touchegg).

## ???

