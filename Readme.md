## Enable Shell Widget

Navi provides a shell widget that allows opening the cheatsheet picker directly from the terminal.

### Zsh

Add this to your `~/.zshrc`:

```bash
eval "$(navi widget zsh)"
```

Reload your shell:

```bash
source ~/.zshrc
```

Use:

```text
Ctrl+G
```

to open the Navi picker.

Selected commands will be inserted into the shell buffer so they can be reviewed or edited before execution.
