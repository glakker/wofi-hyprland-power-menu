# wofi-hyprland-power-menu
Power menu for Hyprland using Wofi.

This project is based on [power-menu.sh]([https://github.com/jason9075/rofi-hyprland-keybinds-cheatsheet](https://github.com/acarl005/dotfiles/blob/master/waybar/scripts/power-menu.sh)).

## Preview
![wofi-hyprland-keybinds Preview](./preview.png)

## Remarks
 - For screen lock requires hyprlock.
   
- To toggle the script by e.g. ShiftMod + Q, include in your Hyprland config:
 
  `
  bind = $ShiftMod, Q, exec, pkill wofi || wofi-power-menu.sh #Power menu
  `

  (The script should be made executable by `chmod +x` and placed in a directory included in your `$PATH`.)
