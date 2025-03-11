# WindowsXPCursorTheme

This is a repository containing a linux cursor theme based on the 3D Golden cursor theme from Windows XP.

## Installation

Simply copy the cursor theme folder to one of the following folders:

```bash
cp -r 3d_golden_windows_xp/ /usr/share/icons/ # Copy to here if want to install system-wide
cp -r 3d_golden_windows_xp/ ~/.icons/ # Copy here if you want to do a user only install
cp -r 3d_golden_windows_xp/ ~/.local/share/icons # This is another user only install possibility
```

## Selecting the cursor theme

This may vary depending on your desktop environment or window manager. but if you want to select the cursor theme directly via X, you can add the following lines to `~/.Xresources`:

```bash
Xcursor.theme: 3DGoldenWindowsXP
Xcursor.size: 32
```

> The cursor name is configured on `./3d_golden_windows_xp/cursor.theme`, and this cursor has e different sizes, 24, 32 and 48.

## Resources

I created this theme using these Windows XP cursor files uploaded by `nibbler` [here](http://www.rw-designer.com/cursor-set/windows-xp-1).

For generating the cursor theme, I used this [repo](https://github.com/carloseabade/cursor-toolbox).

For getting the frames from the animated cursors, I used this [repo](https://github.com/carloseabade/ani_file)
