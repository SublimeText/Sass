# Sass and SCSS

[Sass](https://sass-lang.com) syntax definitions for [Sublime Text](https://www.sublimetext.com) based on its CSS syntax.

Highlights `.sass` or `.scss` files, and provides

- snippets
- completions
- symbols

## Installation

### Package Control

The easiest way to install is using [Package Control](https://packagecontrol.io). It's listed as `Sass`.

1. Open `Command Palette` using <kbd>ctrl+shift+P</kbd> or menu item `Tools → Command Palette...`
2. Choose `Package Control: Install Package`
3. Find `Sass` and hit <kbd>Enter</kbd>

## Troubleshooting

SCSS extends Sublime Text's CSS syntax definition as of ST4149.

If SCSS syntax highlighting doesn't work and console displays syntax errors, 

1. check if CSS package is enabled.
2. remove any out-dated syntax override.
   
### Enable CSS package

1. Open `Command Palette` using <kbd>ctrl+shift+P</kbd> or menu item `Tools → Command Palette...`
2. Choose `Package Control: Enable Packages`
3. Find `CSS` and hit <kbd>Enter</kbd>

### Remove overrides

1. call _Menu > Preferences > Browse Packages.._
2. Look for _CSS_ folder
3. Remove it or at least delete any _CSS.sublime-syntax_ in it

## Notes

Development on the Sass syntax is currently frozen. It's too high maintenance since it's so different from CSS. Furthermore, the Sass language doesn't support various features that SCSS does: it's not left behind by the Sass team per se, but SCSS is the primary language right now. 
That being said, if you want to improve the Sass syntax, contributions are more than welcome.
