# dotfiles

dotfiles: bash + vim + git, symlinked by install.sh

## Highlights

- Git aliases I actually use daily
- Sane vim defaults, no plugins required
- One-command setup: ./install.sh
- Bash prompt with git branch indicator

## Examples

```bash
# configs are symlinked, edit here and it applies everywhere
```

## Installation

```bash
git clone <this repo> ~/.dotfiles
cd ~/.dotfiles
./install.sh
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   └── usage.md
├── .bashrc
├── .gitignore
├── .vimrc
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
└── install.sh
```

## Why

Needed this for myself; figured others might too.
