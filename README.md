# vsc-prolog README

This is the README for your extension "vscode-swi-prolog". After writing up a brief description, we recommend including the following sections.
## Notes before installation
This extension is developed and tested only in the following environments:
OS: Debian 8.8
Prolog: SWI-Prolog 7.5.2

## Features

Describe specific features of your extension including screenshots of your extension in action. Image paths are relative to this README file.

For example if there is an image subfolder under your extension project workspace:

\!\[feature X\]\(images/feature-x.png\)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.

## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them.

## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: enable/disable this extension
* `myExtension.thing`: set to `blah` to do something

## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension.
### Formatting doesn't work when there are singleton variables including named underscore-starting singleton variables in the scopes to be formatted.
### During debug tracing, prompt for stdin input doesn't display in debug console. When the yellow location arrow in editor disappears and the curren goal is a read from stdin, then the tracer is waiting for your input. Then in the input box at the bottom of the debug console TYPE a COLON (:) followed by the content of input, that is used to defferiate input with the other function of the input box: expressions for evaluation. In the later case, just input valid prolog terms.


## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of ...

### 1.0.1

Fixed issue #.

### 1.1.0

Added features X, Y, and Z.

-----------------------------------------------------------------------------------------------------------

## Working with Markdown

**Note:** You can author your README using Visual Studio Code.  Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on OSX or `Ctrl+\` on Windows and Linux)
* Toggle preview (`Shift+CMD+V` on OSX or `Shift+Ctrl+V` on Windows and Linux)
* Press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (OSX) to see a list of Markdown snippets

### For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**