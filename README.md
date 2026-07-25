# Peek

Peek fades floating Hyprland windows to ten percent opacity so you can see and interact with the content underneath.

![Peek disabled](images/peek1.png)
![Peek enabled](images/peek2.png)

## Install

```bash
omarchy plugin add https://github.com/brianblakely/peek.git
```

Accept the prompt to enable Peek during installation.

## Optional shortcuts

Global keybindings remain user-owned. Add any of these to your Hyprland bindings:

```lua
o.bind("SUPER + GRAVE", "Toggle floating window peek", "omarchy-shell b.peek toggle")
o.bind("SUPER + ALT + GRAVE", "Enable floating window peek", "omarchy-shell b.peek enable")
o.bind("SUPER + CTRL + GRAVE", "Disable floating window peek", "omarchy-shell b.peek disable")
```

## Update

```bash
omarchy plugin update b.peek
```
