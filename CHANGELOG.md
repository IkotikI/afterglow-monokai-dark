# Change Log

All notable changes to the "afterglow-monokai-dark" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

Color scheme gets from [ArtyClick Colors](https://colors.artyclick.com/color-name-finder/).

## [0.0.3] - 27.10.2024

### Changed 

- Change colors of **Status (Bottom) Bar** to $\colorbox{#ddd}{\color{#222}{Raisin \space Black }} \sim$ (#222) in \
"statusBar.background": "#222", "statusBarItem.remoteBackground": "#222" 
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
