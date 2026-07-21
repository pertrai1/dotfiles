# Herdr Cheat Sheet

## Global Keybindings

| Key | Action |
|-----|--------|
| `ctrl+space` | Prefix mode (default prefix) |
| `prefix+?` | Open help |
| `prefix+s` | Open settings |
| `prefix+q` | Detach |
| `prefix+shift+r` | Reload config |
| `prefix+o` | Open notification target |
| `prefix+w` | Workspace picker |
| `prefix+g` | Goto |
| `prefix+shift+n` | New workspace |
| `prefix+shift+g` | New worktree |
| `prefix+shift+w` | Rename workspace |
| `prefix+shift+d` | Close workspace |
| `prefix+c` | New tab |
| `prefix+shift+t` | Rename tab |
| `prefix+p` | Previous tab |
| `prefix+n` | Next tab |
| `prefix+1..9` | Switch tab |
| `prefix+shift+x` | Close tab |
| `prefix+shift+p` | Rename pane |
| `prefix+e` | Edit scrollback |
| `prefix+h` | Focus pane left |
| `prefix+j` | Focus pane down |
| `prefix+k` | Focus pane up |
| `prefix+l` | Focus pane right |
| `prefix+tab` | Cycle pane next |
| `prefix+shift+tab` | Cycle pane previous |
| `prefix+v` | Split vertical |
| `prefix+minus` | Split horizontal |
| `prefix+x` | Close pane |
| `prefix+z` | Zoom |
| `prefix+r` | Resize mode |
| `prefix+b` | Toggle sidebar |

## File Viewer Keybindings

When the file viewer is active (bound to `prefix+f` or `prefix+shift+f`):

| Key | Action |
|-----|--------|
| `up` / `k` | Move tree cursor up |
| `down` / `j` | Move tree cursor down |
| `right` / `l` | Expand directory or scroll content right |
| `left` / `h` | Collapse directory or scroll content left |
| `H` (Shift+h) | Scroll tree pane left |
| `L` (Shift+l) | Scroll tree pane right |
| `Enter` | Activate selection (open file in zoom mode) |
| `i` | Toggle gitignored files |
| `.` | Toggle hidden files |
| `c` | Toggle changed-files-only |
| `b` | Toggle diff baseline |
| `v` | Cycle content view mode |
| `e` | Open file in `$EDITOR` |
| `f` | Go to file (fuzzy finder) |
| `:` | Go to line |
| `/` | Search in file |
| `n` / `N` | Next/previous search match |
| `y` | Copy repo-relative path to clipboard |
| `Y` | Copy absolute path to clipboard |
| `Tab` | Move focus between tree and content |
| `<` / `>` | Narrow/widen tree column |
| `w` | Toggle line wrapping |
| `z` | Zoom (hide tree) |
| `r` | Refresh git state |
| `W` (Shift+w) | Switch worktree |
| `?` (Shift+/) | Open help overlay |
| `u` | Dismiss update banner |
| `q` / `Esc` | Close zoom or viewer |

## Navigation Mode

While in navigate mode (when `prefix+g` is used to go to a workspace):

| Key | Action |
|-----|--------|
| `up` | Navigate workspace up |
| `down` | Navigate workspace down |
| `h` | Navigate pane left |
| `j` | Navigate pane down |
| `k` | Navigate pane up |
| `l` | Navigate pane right |

## Command Keybindings

| Key | Action |
|-----|--------|
| `prefix+shift+l` | Open lazygit |
| `prefix+shift+y` | Open yazi |
