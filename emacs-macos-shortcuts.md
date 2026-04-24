# Emacs and macOS Keyboard Shortcuts Compared

A comprehensive guide to moving between Emacs-style and native macOS keyboard shortcuts.

---

## Moving the Cursor

Move the cursor by character, word, line, and document.

| Movement | Direction | Emacs-ish | macOS Native |
|----------|-----------|-------|--------------|
| **Character** | Left | `⌃B` | `←` |
| | Right | `⌃F` | `→` |
| **Word** | Left | `⌃⌥B` | `⌥←` |
| | Right | `⌃⌥F` | `⌥→` |
| **Line** | Begin | `⌃A` | `⌘←` |
| | End | `⌃E` | `⌘→` |
| | Up | `⌃P` | `↑` |
| | Down | `⌃N` | `↓` |
| **Document** | Begin | — | `⌘↑` |
| | End | — | `⌘↓` |

---

## Selecting Text

Extend selection by character, word, line, and paragraph.

| Selection | Direction | Emacs-ish | macOS Native |
|-----------|-----------|-------|--------------|
| **Character** | Left | `⌃⇧B` | `⇧←` |
| | Right | `⌃⇧F` | `⇧→` |
| **Word** | Left | `⌃⌥⇧B` | `⌥⇧←` |
| | Right | `⌃⌥⇧F` | `⌥⇧→` |
| **Line** | Begin | `⌃⇧A` | `⇧⌘←` |
| | End | `⌃⇧E` | `⇧⌘→` |
| | Up | `⌃⇧P` | `⇧↑` |
| | Down | `⌃⇧N` | `⇧↓` |

---

## Deleting Text

Remove characters, words, and lines.

| Deletion | Direction | Emacs-ish | macOS Native |
|----------|-----------|-------|--------------|
| **Character** | Left (backspace) | `⌃H` | `⌫` |
| | Right (delete) | `⌃D` | `⌦` |
| **Word** | Left | — | `⌥⌫` |
| | Right | — | `Fn+⌥⌫` |
| **Line** | Backwards | `⌃K` | `⌘⌫` |
| | Forwards | `⌃K` | — |

---

## Search

Find text and navigate between search results.

| Action | Emacs-ish | macOS Native |
|--------|-------|--------------|
| **First result** | — | `⌘F` |
| **Next result** | — | `⌘G` |
| **Previous result** | — | `⇧⌘G` |

---

## Scrolling

Move and recenter the viewport.

| Action | Emacs-ish | macOS Native |
|--------|-------|--------------|
| **Page up** | — | `Fn+↑` |
| **Page down** | `⌃V` | `Fn+↓` |
| **Recenter** | `⌃L` | — |

---

## Miscellaneous

Other insertion, editing, and kill ring commands.

| Command | Action | Emacs-ish | macOS Native |
|---------|--------|-------|--------------|
| **Character** | Transpose | `⌃T` | — |
| **Line** | Insert | `⌃O` | — |
| | Kill | `⌃K` | — |
| **Kill Ring** | Yank (paste) | `⌃Y` | — |

---

## Key Legend

- `⌃` = Control
- `⌥` = Option (Alt)
- `⌘` = Command
- `⇧` = Shift
- `Fn` = Function key
- `←` `→` `↑` `↓` = Arrow keys
- `⌫` = Delete/Backspace
- `⌦` = Forward Delete
- `—` = Not available

---

## Tips

- **Emacs users on macOS**: Many macOS text fields support Emacs keybindings natively.
- **Mixed usage**: You can often use both styles interchangeably in modern text editors and terminals.

## Reference
This is based off of [Jason Blevins' (Emacs) Keyboard Shortcuts for Editing Text Fields in OS X](https://jblevins.org/log/kbd)
