# Sublime Text Settings

## Preferences

Here are the settings from my `Preferences.sublime-settings` file:

```json
{
	"bold_folder_labels": true,
	"caret_extra_width": 1,
	"caret_style": "phase",
	"close_windows_when_empty": false,
	"color_scheme": "Catppuccin Frappe.sublime-color-scheme",
	"copy_with_empty_selection": false,
	"drag_text": false,
	"draw_minimap_border": true,
	"draw_white_space": "none",
	"enable_tab_scrolling": false,
	"ensure_newline_at_eof_on_save": true,
	"file_exclude_patterns":
	[
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
	"font_face": "Geist Mono",
	"font_options":
	[
		"no_round"
	],
	"font_size": 15,
	"highlight_line": true,
	"highlight_modified_tabs": true,
	"ignored_packages":
	[
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
		"Vintage",
	],
	"index_files": true,
	"installed_packages":
	[
		"Anaconda",
		"BracketHighlighter",
		"Material Theme",
		"Predawn",
		"SideBarEnhancements"
	],
	"line_padding_bottom": 10,
	"line_padding_top": 10,
	"match_brackets_content": false,
	"match_selection": false,
	"match_tags": false,
	"material_theme_accent_graphite": true,
	"material_theme_compact_sidebar": true,
	"mini_diff": false,
	"open_files_in_new_window": false,
	"overlay_scroll_bars": "enabled",
	"preview_on_click": false,
	"save_on_focus_lost": true,
	"scroll_past_end": true,
	"scroll_speed": 5.0,
	"show_definitions": false,
	"show_encoding": true,
	"show_errors_inline": false,
	"show_full_path": false,
	"sidebar_default": true,
	"swallow_startup_errors": true,
	"theme": "Material-Theme-Palenight.sublime-theme",
	"translate_tabs_to_spaces": true,
	"trim_trailing_white_space_on_save": true,
	"update_check": false,
	"use_simple_full_screen": true,
	"word_wrap": false,
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
- Catppuccin color scheme

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

