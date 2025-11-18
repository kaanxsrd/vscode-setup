# VS Code Setup

This repository contains my personal Visual Studio Code configuration, including:

- Editor settings
- Theme & icon theme preferences
- Default formatters (Biome or Prettier fallback)
- Auto-save + format-on-save setup
- Installed extensions list

Use this repo to sync your VS Code configuration across multiple machines.

## Installation

### 1. Install extensions
```bash
cat extensions.txt | xargs -L 1 code --install-extension
```

### 2. Apply settings
Replace your VS Code settings.json with the version in this repository:

Windows
```bash
%APPDATA%\Code\User\settings.json
```

macOS
```bash
~/Library/Application Support/Code/User/settings.json
```

Linux
```bash
~/.config/Code/User/settings.json
```
