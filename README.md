---
created: 2024-06-08T21:19
updated: 2024-06-08T21:50
tags:
  - sublime-text
  - sublime-text-settings
  - settings
---
# Sublime Text Settings

## Preferences

Here are the settings from my `Preferences.sublime-settings` file:

```json
{

"bold_folder_labels": true, // Makes folder labels bold in the sidebar

"caret_extra_width": 1, // Adds extra width to the caret for better visibility

"caret_style": "phase", // Sets the caret style to 'phase', which blinks smoothly

"close_windows_when_empty": false, // Prevents closing the window when the last tab is closed

"color_scheme": "Packages/Base16 Color Schemes/Themes/base16-material.tmTheme", // Sets the color scheme to a material theme

"copy_with_empty_selection": false, // Disables copying when no text is selected

"drag_text": false, // Disables text dragging

"draw_minimap_border": true, // Draws a border around the minimap

"draw_white_space": "none", // Hides white space characters

"enable_tab_scrolling": false, // Disables tab scrolling

"ensure_newline_at_eof_on_save": true, // Ensures a newline at the end of the file upon saving

"file_exclude_patterns": [ // Patterns for files to exclude from the sidebar

"*.pyc",

"*.pyo",

"*.exe",

"*.dll",

"*.obj",

"*.o",

"*.a",

"*.lib",

"*.so",

"*.dylib",

"*.ncb",

"*.sdf",

"*.suo",

"*.pdb",

"*.idb",

".DS_Store",

"*.class",

"*.psd",

"*.sublime-workspace"

],

"font_face": "JetBrains Mono", // Sets the font face to 'JetBrains Mono'

"font_options": [ "no_round" ], // Disables font rounding

"font_size": 18, // Sets the font size to 18

"highlight_line": true, // Highlights the current line

"highlight_modified_tabs": true, // Highlights tabs with unsaved changes

"ignored_packages": [ // Packages to ignore

"ActionScript",

"AppleScript",

"ASP",

"D",

"Diff",

"Erlang",

"Graphviz",

"Groovy",

"Lisp",

"Lua",

"Objective-C",

"OCaml",

"Rails",

"Ruby",

"Vintage"

],

"index_files": true, // Enables file indexing for faster searching

"installed_packages": [ // List of installed packages

"Anaconda",

"BracketHighlighter",

"Material Theme",

"Predawn",

"SideBarEnhancements"

],

"line_padding_bottom": 10, // Adds padding below lines

"line_padding_top": 10, // Adds padding above lines

"match_brackets_content": false, // Disables matching bracket content highlighting

"match_selection": false, // Disables selection matching

"match_tags": false, // Disables tag matching in HTML/XML

"material_theme_accent_graphite": true, // Sets the Material Theme accent to graphite

"material_theme_compact_sidebar": true, // Enables compact sidebar for Material Theme

"mini_diff": false, // Disables mini diff in the gutter

"open_files_in_new_window": false, // Prevents opening files in a new window

"overlay_scroll_bars": "enabled", // Enables overlay scroll bars

"preview_on_click": false, // Disables file preview on click in the sidebar

"save_on_focus_lost": true, // Saves files when focus is lost

"scroll_past_end": true, // Allows scrolling past the end of the file

"scroll_speed": 5.0, // Sets the scroll speed

"show_definitions": false, // Disables showing definitions in the popup

"show_encoding": true, // Shows file encoding in the status bar

"show_errors_inline": false, // Disables inline error messages

"show_full_path": false, // Hides the full file path in the title bar

"sidebar_default": true, // Uses default sidebar settings

"swallow_startup_errors": true, // Suppresses startup error messages

"theme": "Adaptive.sublime-theme", // Sets the theme to Adaptive

"translate_tabs_to_spaces": true, // Translates tabs to spaces

"trim_trailing_white_space_on_save": true, // Trims trailing white space on save

"update_check": false, // Disables update checks

"use_simple_full_screen": true, // Uses simple full screen mode

"word_wrap": false // Disables word wrap

}
```

---
# Custom Keybindings

Below are my custom keybindings for Sublime Text. These bindings help improve my workflow and efficiency:

```json

[

{ "keys": ["shift+ctrl+c"], "command": "cancel_build" }, // Cancels a build with Shift + Ctrl + C

{ "keys": ["§"], "command": "toggle_side_bar" } // Toggles the sidebar with the § key

]

```

---
# Installed Packages

Here is a list of the installed packages that complement my Sublime Text settings:

```
## Color Schemes

- 1337 Color Scheme.sublime-package
- Base16 Color Schemes.sublime-package
- Base16 Eighties Dark Color Scheme.sublime-package
- Color Scheme - Bass.sublime-package
- Material Color Scheme.sublime-package
- Material Monokai.sublime-package
- One Dark Material - Theme.sublime-package
- RailsBase16 Color Schemes.sublime-package

## Themes

- Gruvbox Material Theme.sublime-package
- Material Theme.sublime-package
- Materialize.sublime-package
- Theme - Cyanide.sublime-package
- Theme - Dark Material.sublime-package

## Markdown

- GitHub Flavored Markdown Preview.sublime-package
- MarkSearch.sublime-package
- Markdown Code Blocks.sublime-package
- Markdown Extended.sublime-package
- Markdown HTML Preview.sublime-package
- Markdown Images.sublime-package
- Markdown.sublime-package
- MarkdownAssistant.sublime-package
- MarkdownCodeBlockWrapper.sublime-package
- MarkdownEditing.sublime-package
- MarkdownLivePreview.sublime-package
- MarkdownPreview.sublime-package
- MarkdownTOC.sublime-package

## File Management

- AdvancedNewFile.sublime-package
- AutoFileName.sublime-package

## Enhancement Tools

- A File Icon.sublime-package
- Alignment.sublime-package
- All Autocomplete.sublime-package
- Color Highlight.sublime-package
- Colored Comments.sublime-package
- RainbowBrackets.sublime-package
- SideBarEnhancements.sublime-package
- SideBarMenuAdvanced.sublime-package
- Sublime Input.sublime-package

## Development Tools

- Git.sublime-package
- GitGutter.sublime-package
- Package Control.sublime-package
- Terminus.sublime-package

## External Integrations

- Typora Markdown App (OSX).sublime-package
```

---
# How to Use These Settings

1. Clone the Repository: Download or clone this repository to your local machine.
2. Copy Settings: Replace your existing `Preferences.sublime-settings` and keymap files with the ones provided in this repository.
3. Install Packages: Ensure the listed packages are installed in your Sublime Text. You can do this through Package Control.

---
# Installed User Packages:

```
## A File Icon
- A File Icon.sublime-package

## Color Schemes
- Base16 Color Schemes.sublime-package
- Base16 Eighties Dark Color Scheme.sublime-package
- Color Scheme - Bass.sublime-package
- Material Color Scheme.sublime-package
- Material Monokai.sublime-package

## Default Keymap (OSX)
- Default (OSX).sublime-keymap

## KiteSublime Settings
- KiteSublime.sublime-settings

## Markdown Settings
- Markdown.sublime-settings

## Package Control Settings
- Package Control.sublime-settings
- Package Control.user-ca-bundle

## Preferences
- Preferences.sublime-settings

## Terminus
- Terminus.sublime-package

## Text File with User Packages
- sublime-text-user-packages.txt

## Terminus Build Configuration
- terminus-python.sublime-build
```

---
# Sublime Text Packages

```
## Base16 Color Schemes
- Base16 Color Schemes.sublime-package

## Default Color Scheme
- Color Scheme - Default.sublime-package

## Default Side Bar Mount Point Menu
- Default:Side Bar Mount Point.sublime-menu

## Default Side Bar Menu
- Default:Side Bar.sublime-menu

## Kite Python Autocomplete
- Kite Python Autocomplete.sublime-package

## Python
- Python.sublime-package

## SideBarEnhancements
- SideBarEnhancements.sublime-package

## SublimeAStyleFormatter
- SublimeAStyleFormatter.sublime-package

## SublimeREPL
- SublimeREPL.sublime-package

## User
- User.sublime-package

## A File Icon (zzz)
- zzz A File Icon zzz.sublime-package
```

# Python Build:

```
{
    "cmd": ["/usr/local/bin/python3", "-u", "$file"],
    "selector": "source.python",
    "file_regex": "^\\s*File \"(...*?)\", line ([0-9]*)"
}

```
### **Happy coding!**

