<p align="center">
    <img
        width="120"
        src="sublimebundle.png"
        alt="SublimeBundle logo"
    >
</p>

# SublimeBundle

This is portable [Sublime Text](https://www.sublimetext.com/) version optimized
for back-end & front-end development under Windows. It has all required packages
installed and configured with sensible defaults.

Note that the bundle does not include packages that rely on external executables
like `node`, `ruby`, `php`, etc. - the goal is to provide lightweight
"base" installation that can be forked/customized further.

## Installation

1. Create directory `C:\sublimebundle`
2. Enter newly created directory and run `git clone https://github.com/kminek/sublimebundle.git .`
3. Run executable `sublime_text.exe` and wait for Package Control to install all packages
4. Restart Sublime Text and start hacking!

### Installing context menu shortcuts

You can add `Open With SublimeBundle` to Windows context menu for files and
directories by double-clicking file `install_context_menu_shortcuts.reg`.

## What's included

- Sublime Text Version ***3.2.2***, Build ***3.2.1***

### Packages

```
"A File Icon",
"Dockerfile Syntax Highlighting",
"EditorConfig",
"INI",
"nginx",
"SideBarEnhancements",
"Theme - Soda"
```
