# Peek

Fades floating Hyprland windows to minimal opacity so you can see and interact with the content underneath.

![Peek disabled](images/peek1.png)
![Peek enabled](images/peek2.png)

## Install

```bash
omarchy plugin add https://github.com/brianblakely/peek.git
```

## Shortcuts

```lua
o.bind("SUPER + GRAVE", "Toggle floating window peek", "omarchy-shell b.peek toggle")
o.bind("SUPER + ALT + GRAVE", "Enable floating window peek", "omarchy-shell b.peek enable")
o.bind("SUPER + CTRL + GRAVE", "Disable floating window peek", "omarchy-shell b.peek disable")
```

## Update

```bash
omarchy plugin update b.peek
```
