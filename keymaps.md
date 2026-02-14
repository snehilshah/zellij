# Zellij Keyboard Shortcuts

> **Leader Key:** `Alt s` (toggles between locked ↔ normal mode)
>
> Zellij starts in **locked mode** — all keys pass through to the terminal/nvim.
> Press `Alt s` to enter zellij normal mode, then a letter to enter a sub-mode.
> Press `Esc` or `Enter` from any sub-mode to return to normal, then `Alt s` to go back to locked.

## Global (always active, all modes except locked)

| Key | Action |
|-----|--------|
| `Alt s` | Toggle locked ↔ normal mode |

## Normal Mode (after `Alt s`)

| Key | Action | | Key | Action |
|-----|--------|-|-----|--------|
| `t` | Enter **Tab** mode | | `p` | Enter **Pane** mode |
| `n` | Enter **Resize** mode | | `h` | Enter **Move** mode |
| `s` | Enter **Scroll** mode | | `o` | Enter **Session** mode |
| `b` | Enter **Tmux** mode | | `q` | Quit zellij |
| `f` | Toggle floating panes → locked | | `w` | New pane → locked |
| `y` | Zellij Forgot plugin → locked | | | |

## Pane Mode (`Alt s` → `p`)

| Key | Action | | Key | Action |
|-----|--------|-|-----|--------|
| `h` / `←` | Focus left | | `l` / `→` | Focus right |
| `j` / `↓` | Focus down | | `k` / `↑` | Focus up |
| `n` | New pane | | `r` | New pane right |
| `d` | New pane down | | `s` | New pane stacked |
| `f` | Toggle fullscreen | | `e` | Toggle embed/float |
| `w` | Toggle floating panes | | `z` | Toggle pane frames |
| `c` | Rename pane | | `i` | Toggle pane pinned |
| `p` | Switch focus | | `x` | Close pane |
| `Ctrl p` | Back to normal | | `Esc` | Back to normal |

## Tab Mode (`Alt s` → `t`)

| Key | Action | | Key | Action |
|-----|--------|-|-----|--------|
| `h` / `←` | Previous tab | | `l` / `→` | Next tab |
| `j` / `↓` | Next tab | | `k` / `↑` | Previous tab |
| `n` | New tab | | `x` | Close tab |
| `r` | Rename tab | | `tab` | Toggle last tab |
| `1-9` | Go to tab 1-9 | | `b` | Break pane to new tab |
| `[` | Break pane left | | `]` | Break pane right |
| `s` | Toggle sync tab | | `Ctrl t` | Back to normal |

## Resize Mode (`Alt s` → `n`)

| Key | Action | | Key | Action |
|-----|--------|-|-----|--------|
| `h` / `←` | Increase left | | `l` / `→` | Increase right |
| `j` / `↓` | Increase down | | `k` / `↑` | Increase up |
| `H` | Decrease left | | `L` | Decrease right |
| `J` | Decrease down | | `K` | Decrease up |
| `+` / `=` | Increase all | | `-` | Decrease all |
| `Ctrl n` | Back to normal | | `Esc` | Back to normal |

## Move Mode (`Alt s` → `h`)

| Key | Action | | Key | Action |
|-----|--------|-|-----|--------|
| `h` / `←` | Move pane left | | `l` / `→` | Move pane right |
| `j` / `↓` | Move pane down | | `k` / `↑` | Move pane up |
| `n` / `tab` | Cycle move | | `p` | Move backwards |
| `Ctrl h` | Back to normal | | `Esc` | Back to normal |

## Scroll Mode (`Alt s` → `s`)

| Key | Action | | Key | Action |
|-----|--------|-|-----|--------|
| `j` / `↓` | Scroll down | | `k` / `↑` | Scroll up |
| `d` | Half page down | | `u` | Half page up |
| `h` / `←` | Page up | | `l` / `→` | Page down |
| `Ctrl b` | Page up | | `Ctrl f` | Page down |
| `PageUp` | Page up | | `PageDown` | Page down |
| `e` | Edit scrollback | | `s` | Enter search mode |
| `Ctrl c` | Scroll to bottom → normal | | `Ctrl s` | Back to normal |

## Search Mode (from scroll → `s`)

| Key | Action | | Key | Action |
|-----|--------|-|-----|--------|
| `n` | Search down | | `p` | Search up |
| `c` | Toggle case sensitivity | | `w` | Toggle wrap |
| `o` | Toggle whole word | | `Esc` | Back to normal |

## Session Mode (`Alt s` → `o`)

| Key | Action | | Key | Action |
|-----|--------|-|-----|--------|
| `w` | Session manager | | `d` | Detach |
| `a` | About | | `c` | Configuration |
| `p` | Plugin manager | | `s` | Share |
| `Ctrl o` | Back to normal | | `Esc` | Back to normal |

## Tmux Mode (`Alt s` → `b`)

| Key | Action | | Key | Action |
|-----|--------|-|-----|--------|
| `h` / `←` | Focus left → normal | | `l` / `→` | Focus right → normal |
| `j` / `↓` | Focus down → normal | | `k` / `↑` | Focus up → normal |
| `"` | Split down → normal | | `%` | Split right → normal |
| `c` | New tab → normal | | `x` | Close pane → normal |
| `n` | Next tab → normal | | `p` | Previous tab → normal |
| `z` | Toggle fullscreen → normal | | `o` | Focus next pane |
| `,` | Rename tab | | `[` | Enter scroll mode |
| `space` | Next swap layout | | `d` | Detach |
| `Ctrl b` | Send raw Ctrl-b → normal | | `Esc` | Back to normal |
