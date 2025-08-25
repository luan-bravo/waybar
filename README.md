# Adaptable Waybar Theme

This is a fork of []() that I found listed in [](). I have modified it heavily on it's workings, mainly:
 - config.jsonc
     - Use plugins for hyprland
     - Get and set the latest weather plugin implementation
     - Customize so that playerctl works with any playing audios, not only spotify
 - style.css
     - Structure configuration into the proper waybar module css selectors
     - Base colorscheme on GTK-3.0 theme css variables.
     - Customize battery module to sign battery status colorfully

## To Do
 - [ ] setup power button properly
 - [ ] fix tray pushing modules-middle when oversized
