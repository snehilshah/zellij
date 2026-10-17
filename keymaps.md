# Zellij Keyboard Shortcuts

> Zellij starts in passthrough mode: every key goes to the shell/nvim except `Alt s` and `Alt 1-9`.
> `Alt s` is the prefix. Press one key after it; most actions drop you back to passthrough.
> `Esc` (or `Alt s` again) cancels the prefix.

## Global (no prefix)

| Key       | Action         |
| --------- | -------------- |
| `Alt s`   | Prefix         |
| `Alt 1-9` | Go to tab 1-9  |

## Prefix (`Alt s` then …)

| Key          | Action                   |     | Key       | Action               |
| ------------ | ------------------------ | --- | --------- | -------------------- |
| `\|` / `%`   | Split right              |     | `-` / `"` | Split down           |
| `h j k l`    | Focus pane               |     | `H J K L` | Resize (repeatable)  |
| `{` / `}`    | Swap pane back / forward |     | `Space`   | Next swap layout     |
| `x`          | Close pane               |     | `X`       | Close tab            |
| `z`          | Fullscreen pane          |     | `f`       | Toggle floating      |
| `c`          | New tab                  |     | `,`       | Rename tab           |
| `n` / `p`    | Next / previous tab      |     | `Tab`     | Last tab             |
| `[`          | Scroll mode              |     | `/`       | Search scrollback    |
| `w`          | Session manager          |     | `d`       | Detach               |

Resize keys keep the prefix active, so `Alt s H H H Esc` grows the pane three steps.

## Scroll / Search

| Key                 | Action                 |     | Key       | Action              |
| ------------------- | ---------------------- | --- | --------- | ------------------- |
| `j` / `k`           | Line down / up         |     | `d` / `u` | Half page down / up |
| `Ctrl f` / `Ctrl b` | Page down / up         |     | `g` / `G` | Top / bottom        |
| `/`                 | Search                 |     | `e`       | Open in `$EDITOR`   |
| `n` / `N`           | Next / prev match      |     | `q` `Esc` | Exit                |
| `c` / `w` / `o`     | Toggle case / wrap / whole word (search) | | | |
