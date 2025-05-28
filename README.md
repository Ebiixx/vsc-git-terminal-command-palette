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

1. Package the extension with [`vsce`](https://code.visualstudio.com/api/working-with-extensions/publishing-extension):
   ```
   vsce package
   ```
2. Install the generated `.vsix` file in VS Code:
   - `Ctrl+Shift+P` → **Extensions: Install from VSIX...** → select the file

## Example Commands

- `git status`
- `git add .`
- `git commit -m "Initial commit"`
- `git push -u origin main`
- and more

---

MIT License
