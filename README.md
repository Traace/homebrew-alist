# alist-homebrew
Homebrew Formulae for alist https://github.com/alist-org/alist

🗂️A file list program that supports multiple storages, powered by Gin and Solidjs.

## Requierments
- MacOS 13 or better (untested below)
- Homebrew https://brew.sh/

## Installation
1. Install tap: `brew tap traace/alist`
2. Install alist: `brew install traace/alist/alist`

## First Start
1. Start Server to populate data: `$(brew --prefix)/opt/alist/bin/alist server --data $(brew --prefix)/etc/alist-data`
2. Stop Server: `STRG+C in Terminal`
3. Start Service: `brew services start traace/alist/alist`
4. Open `http://127.0.0.1:5244` in Webbrowser on same machine
