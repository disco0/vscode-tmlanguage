# TextMate Syntax Definitions for Visual Studio Code

This package provides syntax highlighting for the SublimeText JSON/YAML tmlanguage files in Visual Studio Code with additional highlighting for variable defintions in YAML. Forked from [Togusa90.tmlanguage](https://github.com/Togusa09/vscode-tmlanguage), based on grammars from Sublime Text's [PackageDev](https://github.com/SublimeText/PackageDev) package.

## Differences from <code>[Togusa90.tmlanguage](https://github.com/Togusa09/vscode-tmlanguage)</code>

This fork provides improved language and grammar configurations for tmLanguage files only. The original conversion commands and JSON tmLanguage completion/diagnostics have issues—the later even causing issues with regular JSON files—and need to be fixed before returning. At the moment this fork is focused on fixing/improving grammars, but providing diagnostics for YAML/JSON-tmLanuage is something I'd like to do in the future.

Very much WIP, however even just removing the programmatic features will probably improve your experience (especially if you're reading the DevTools console). Some improvements have been made to fix escaped regexes inside JSON values, but its still not perfect.

## Syntax Highlighting Screenshots

`variables` defintion block highlighting in YAML-tmLanguage files:

![YAML-tmLanguage Variables](/images/yaml-variable-definitions-00.png)
