# VSCode Joomla Snippets

Visual Studio Code Joomla snippets and code examples for Joomla 3 & 4.

All code snippets are based on and follow the Joomla style guide https://docs.joomla.org/Joomla_CodeSniffer

## Snippet Prefixes

| Prefix | Description |
| ------- | ----------|
| j3- | Joomla 3 Snippets |
| j4- | Joomla 4 Snippets |
| jdoc- | Snippets for Templates |

## Usage

All Joomla snippets starts with "j3-", "j4-", or "jdoc-".

## Joomla Snippets

| Snippet | Description |
| ------- | ----------|
| j3-addscriptversion | Adds a linked script to the page with a version to allow to flush it (Joomla 3). |
| j3-addstylesheetversion | Adds a linked stylesheet version to the page (Joomla 3). |
| j3-head | Common template header variables for Joomla 3. |
| j3-text | Expand a JText for Joomla 3. Translates a string into the current language. |
| jdoc-add-module-position | Add a module position to a template. |

## Installation (Mac)

1. Launch VS Code
1. Quick Open (⌘+P)
1. Enter the following command and press enter: 'ext install Angular-BeastCode'
1. Choose extension (Author: Mikael Morlund)
1. Reload VS Code

## Installation (Windows, Linux)

1. Launch VS Code
1. Quick Open (Ctrl-Shift-P)
1. Enter the following command and press enter: 'ext install Angular-BeastCode'
1. Choose extension (Author: Mikael Morlund)
1. Reload VS Code

## Emmets

If you want intellisense to show emmets before the snippets, you can force the emmets suggestions to show up at the top, by add the following to your editor user settings:

```javascript
{
  "emmet.showSuggestionsAsSnippets": true,
  "editor.snippetSuggestions": "top"
}
```

## Feedback

Please send any feedback or suggestions to [@anibal_sanchez](https://twitter.com/anibal_sanchez) (Twitter) or [create an issue](https://github.com/anibalsanchez/VSCode-Joomla-Snippets) on GitHub.

## Open Source

This is an open source project and if you want to contribute I've added issues on github that are easy to start with. [![first-timers-only](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](https://github.com/BeastCode/VSCode-Angular-TypeScript-Snippets/labels/first-timers-only)

## Disclaimer

Important: This extension due to the nature of it's purpose will create
files on your hard drive and if necessary create the respective folder structure.
While it should not override any files during this process, I'm not giving any guarantees or take any responsibility in case of lost data.

## License

MIT

## Acknowledgements

- [Snippets para Visual Studio Code y Joomla](https://www.sergioiglesias.net/blog/joomla/418-snippets-para-visual-studio-code-y-joomla)
