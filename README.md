# navi-cheats

My personal [navi](https://github.com/denisidoro/navi) cheatsheet collection for pentesting, CTF/HackTheBox, web hacking, and privilege escalation.

## Prerequisites

- [navi](https://github.com/denisidoro/navi) installed
- [fzf](https://github.com/junegunn/fzf) installed

## Install

```bash
navi repo add https://github.com/teeramaet/navi-cheats
```

## Usage

```bash
# Browse everything interactively
navi

# Print command without executing (useful for reviewing)
navi --print
```

### Shell Widget 

Bind navi to `Ctrl+G` so you can trigger it mid-command from anywhere in your terminal. Add to your `.bashrc` / `.zshrc` / `config.fish`:

```bash
# bash
source <(navi widget bash)

# zsh
source <(navi widget zsh)

# fish
navi widget fish | source
```

**Cheatsheet location** (if you want to edit directly):
```bash
ls ~/.local/share/navi/cheats/
```
