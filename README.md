# Norber Theme v1.4

A Theme for [Sublime Text](http://sublimetext.com) editor.  
Source themes: [Numix Theme](https://github.com/nauzethc/sublime-text-numix), [Material Theme](https://github.com/equinusocio/material-theme).

Package Control page: [**Norber Theme**](https://packagecontrol.io/packages/Norber%20Theme).

## Changes

- Space between tabs;
- Different colors for active/inactive tabs;
- Different hover color for sidebar;
- File icons for sidebar items;
- Changed document tab is highlighted with the bottom light line.

## Install
  
  *With Package Control*:
  
  - press **Ctrl + Shift + P**
  - find *Package Control: Install Package*
  - type: *Norber Theme*
  
  *Manually*:
  
  - Download a [**release**](https://github.com/mortalis13/Norber-Theme-Sublime/releases)
  - Unzip the files and rename the folder to **Norber Theme**
  - Find your **Packages** directory using the menu item `Preferences -> Browse Packages...`
  - Copy the folder into your Sublime Text **Packages** directory.
  - Click on `Preferences -> Settings - User` and add the next line:


For **Sublime Text 4**:
```
"theme": "Norber.sublime-theme",
"color_scheme": "NorberMonokai.sublime-color-scheme",
```

For **Sublime Text 3**:
```
"theme": "Norber.sublime-theme",
"color_scheme": "Packages/Norber Theme/NorberMonokai.tmTheme",
```

## Additional Sublime Settings [Optional]

```
"always_show_minimap_viewport" : true,
"show_tab_close_buttons": false,
"enable_tab_scrolling": false,
"hide_new_tab_button": true,

"line_padding_bottom": 1,
"line_padding_top": 1,
"margin": 0,
"highlight_line": true,

"font_size": 11,
"font_options": [
  "subpixel_antialias"
],
// Windows
"theme_font_options": [
  "gdi"
],
```

## Changelog

### 1.4

- new icons adaptation

### 1.3

- theme adapted for Sublime Text 4

### 1.2

- theme name without spaces

### 1.1

- color scheme for Sublime Text 4
- hide "FOLDERS" line in the sidebar
- dark mode for widgets (console, input fields)
- dark title bar
- changed selection border color

### 1.0.5

- updated color scheme for Sublime Text b3147

### 1.0.4

- added panel switcher icon in Status bar
- changed colors for quick panel labels
- fixed colors for Quick Switch Project dialog

### 1.0.3

- changed cursor color
- added styles for Log4j (used for a log4j syntax highlight)

### 1.0.2

- changed style of text fields (search, console, quick panels) + dropdown button style
- changed style of status bar (height, font, buttons highlight, buttons separators)

### 1.0.1

- changed fonts for sidebar items and tab labels to **Verdana** for better view
- changed sidebar selected row color
- added custom color scheme based on Monokai
