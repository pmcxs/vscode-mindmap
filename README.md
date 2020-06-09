<p>
  <h1 align="center">vscode-mindmap</h1>
</p>

Forked from: https://github.com/souche/vscode-mindmap

Main difference from the main repo is proper support for other languages (defaulting to English) as the original extension has various dialogs in Chinese.

## Features

-  File Edit(eg: .km), Save, Export
-  Transpile .xmind to .km
-  Support export to image(.png)

## Installation

  Install through VS Code extensions. Search for "vscode-mindmap"

  Visual Studio Code Market Place: vscode-mindmap

## Usage

  open any file with extension of km or xmind after install the plugin

## Keyboard Shortcuts

| Key                              | Command                        |
| -------------------------------- | ------------------------------ |
| cmd + m(mac) / ctrl + m(windows) | open a webview of textDocument |
| cmd + s(mac) / ctrl + s(windows) | save mindmap file              |

## FAQ
  - **File parsed incorrectly, the current webview only show initial mindmap**
  
    close the file and webview, try to reopen this file

  - **Extension invalid when the plugin installed**

    check your vscode version, please ensure the version is 1.29.0 or above


## Acknowledgments

This fork uses code from https://github.com/ACTom/kityminder-editor, which by itself is a fork from https://github.com/fex-team/kityminder-editor to add proper i18n support

