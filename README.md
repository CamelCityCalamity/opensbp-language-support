# README

VSCode Syntax highlighting for the OpenSBP language. It might not be complete. It might even have bugs.

This is not published in the extension marketplace. See build instructions.

## Build instructions

You will need node.js

- Install the VSCE tool if you haven't: `npm install -g @vscode/vsce`
- Package the extension: `vsce package`
- This creates a `.vsix` file in your folder.

## Install the extension in VS Code

- If you have a `.vsix` file: `code --install-extension extension-name.vsix`
- Alternatively, use the command pallette: `Extensions: Install from VSIX`
- Or, for development, open the extension source code folder in VS Code and press `F5` to launch a new Extension Development Host window with the extension loaded.