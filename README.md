# openbox-tiling-config
An openbox configuration file, with customization to support keyboard based window tiling. Openbox is a lightweight 
window manager. Openbox is also used a window manager by LXDE, a light weight desktop environment.

### Moving 1 Window:
Super key + Keypad (1 - 9) move windows to the expected screen edge
Super key + Keypad 5 maximizes the window
Super key + Keypad - minimizes the window

### Moving 2 Windows:
Super key + Keypad 0 places 2 windows next to each other (horizontal tiling)
Super key + Keypad Enter places 2 windows above each other (vertical tiling)

### Moving 3 Windows:
Super key + Insert places the current window left, the next window top right and the previous window bottom right
Super key + Home places the current window right, the next window top left and the previous window bottom left
Super key + Pageup places the current window on the top half, the next window bottom left and the previous window bottom right
Super key + Pagedown places the current window on the bottom half, the next window top left and the previous window top right
Super key + End places 3 windows side by side (horizontal tiling)

### Moving the split:
For Super key + Keypad (1, 3, 4, 6, 7, 9) and Super key + (insert, home, pageup, pagedown) the place where windows are
split can be moved, the Alt key moves them to the right (alt is right of superkey on the lefthandside of the kb), 
the Ctrl key moves them to the left.

### Middle window:
Super key + Alt + keypad (2, 5, 8) or Super key + Ctrl + keypad (2, 5, 8) places a window in the horizontal center
the screen.

### Misc:
Super key + Delete toggles window decorations, all multi-window tiling combination disable these decoration, you
can user Super key + Delete to reenable them.
