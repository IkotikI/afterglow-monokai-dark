# Change Log

All notable changes to the "afterglow-monokai-dark" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

Color naming gets from [ArtyClick Colors](https://colors.artyclick.com/color-name-finder/).


## TODO
- PHP nowdoc support

## Unreleased

## [0.0.7] - 03.10.2025

### Changed
- Changed PHP **trait** keyword from $\color{#249D5F}{Clover \space Green \sim}$ (#249D5F) to $\color{#B05279}{Raspberry\space Rose \sim}$. Now it match other type definitions.

## [0.0.6] - 03.10.2025

### Added
- Added PHP 8 meta attributes support. For meta name and variables used $\color{#AAAAAA}{Grey \space Chateau \sim}$ (#AAAAAA) and *Italic* font style. Internal variable types keep it's type highlight. Keep it distinguishable, but no very prominent.

### Changed
- Changed PHP custom types (classes) coloring and custom namespaces from $\color{#249D5F}{Clover \space Green \sim}$ (#249D5F) to $\color{#7CC39E}{Summer \space Green \sim}$ (#7CC39E). Thats easier to distinct build-in and custom definitions.
- Changed PHP build-in variables from $\color{#B05279}{Raspberry\space Rose \sim}$ (#B05279) to $\color{#249D5F}{Clover \space Green \sim}$ (#249D5F). Rose color suite for keywords, not for build-in types.

### Limitation

- Limitation to change constant color in C language to $\color{#9e86c8}{Lavender \space Purple \sim}$ (#9e86c8) like constants in other language. \
Official [C/C++ Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools) have a semantic tokenizer, that overall improve syntax highlighting, but provide **equal scope** for both *function calls* and *constants* inside a function. In VS Code *Semantic* scope is fully override *Text Mate* scopes, and these **scopes can't be combined**. Disabling semantic scope for a language (like C) can solve the constant coloring problem, but other semantic losses doesn't worth it.

## [0.0.4] - 27.10.2024

### Changed 

- Change colors of **Status (Bottom) Bar** to $\colorbox{#ddd}{\color{#222}{Raisin \space Black }} \sim$ (#222) in \
`"statusBar.background": "#222", "statusBarItem.remoteBackground": "#222" `
- Fixed colors for **Components in JS Frameworks** (Svelte, React) \
  Example: `<Button \>` tag name shall be $\color{#7CC39E}{Summer \space Green \sim}$ (#7CC39E)

## [0.0.3] - 27.10.2024

### Added

- CHANGELOG.md with all 3 existing version to this moment
- **Git only:** Exported all existing theme settings using "Generate Color Theme From Current Settings" to
  "theme-from-settings.jsonc" for development stuff.

### Changed

- Scopes "support.type", "support.class" changed to $\color{#249D5F}{Clover \space Green \sim}$ (#249D5F).\
  It affects **basic types**, such as `number`, `string`, `boolean`, etc in JavaScript.
  - **interface** in TypeScript now match other keywords with $\color{#B05279}{Raspberry\space Rose \sim}$ (#B05279).


## [0.0.2] - 18.10.2024

### Added

- LICENSE file with Unlicensed (because vsce's packaging caution is annoying).

### Changed
- Fixed misspelling in package.json.
- Minor theme fixes.

## [0.0.1] - 18.10.2024

### Added

- VS Code theme project generated, based on import from [alpenglow-monokai](https://marketplace.visualstudio.com/items?itemName=kaicataldo.alpenglow-monokai) theme
- README.md with basic description.
- assets/icon.png - created logo of the extension. 
- .gitignore and .vscodeignore set up to filter project files of assets.
