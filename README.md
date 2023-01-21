# i3pbw

Miss windows-like list of all windows in your taskbar?

<img src="https://user-images.githubusercontent.com/9664601/56872872-05365f00-6a2e-11e9-8383-1849e5980b48.png">

## Features

* Focus workspace and window on left mouse button click
* Highlight urgent windows
* Overflow the polybar when there is too many windows open :^)

## Example config

```ini
[module/i3pbw]
type = custom/script
exec = ~/ghub/i3pbw/module.py
tail = true
```

The scripts expects font-2 to be the font that should be used for icons. You probably want it to have higher size than your regular font. Example:

```ini
font-0 = NotoSans Nerd Font:size=10;2      
font-1 = siji:pixelsize=16;1 
font-2 = NotoSans Nerd Font:size=16;4
```
