# Git Command Palette

A handy command palette for common Git commands in the VS Code terminal.

## Features

- Open a palette with frequently used Git commands
- Select a command and execute it directly in the integrated terminal

## Usage

1. Open the command palette (`Ctrl+Shift+P`)
2. Search for **"Git Command Palette"**
3. Select a Git command from the list – it will be sent to the terminal

## Installation

1. You can either:
   - Package the extension yourself with [`vsce`](https://code.visualstudio.com/api/working-with-extensions/publishing-extension):
     ```
     vsce package
     ```
     and use the generated `.vsix` file,
   - **or** download a prebuilt `.vsix` file in this repo.
2. Install the `.vsix` file in VS Code:
   - `Ctrl+Shift+P` → **Extensions: Install from VSIX...** → select the file

## Example Commands

- `git status`
- `git add .`
- `git commit -m "Initial commit"`
- `git push -u origin main`
- and more

---

MIT License
