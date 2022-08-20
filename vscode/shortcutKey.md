# vscode shortcut key

## keybingdings.json

```json
[
  {
    "key": "Shift+f",
    "command": "explorer.newFile",
    "when": "explorerViewletFocus"
  },
  {
    "key": "shift+d",
    "command": "explorer.newFolder",
    "when": "explorerViewletFocus"
  },
  {
    "key": "shift+r",
    "command": "renameFile",
    "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceIsRoot && !explorerResourceReadonly && !inputFocus"
  },
  {
    "key": "f2",
    "command": "-renameFile",
    "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceIsRoot && !explorerResourceReadonly && !inputFocus"
  },
  {
    "key": "shift+e",
    "command": "deleteFile",
    "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceReadonly && !inputFocus"
  },
  {
    "key": "shift+delete",
    "command": "-deleteFile",
    "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceReadonly && !inputFocus"
  },
  {
    "key": "alt+e",
    "command": "workbench.action.previousEditor"
  },
  {
    "key": "ctrl+pageup",
    "command": "-workbench.action.previousEditor"
  },
  {
    "key": "alt+r",
    "command": "workbench.action.nextEditor"
  },
  {
    "key": "ctrl+pagedown",
    "command": "-workbench.action.nextEditor"
  },
  {
    "key": "alt+oem_period",
    "command": "editor.action.quickFix",
    "when": "editorHasCodeActionsProvider && editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+oem_period",
    "command": "-editor.action.quickFix",
    "when": "editorHasCodeActionsProvider && editorTextFocus && !editorReadonly"
  },
  {
    "key": "alt+o",
    "command": "workbench.action.focusSideBar"
  },
  {
    "key": "ctrl+0",
    "command": "-workbench.action.focusSideBar"
  },
  {
    "key": "alt+i",
    "command": "workbench.action.focusFirstEditorGroup"
  },
  {
    "key": "ctrl+1",
    "command": "-workbench.action.focusFirstEditorGroup"
  },
  {
    "key": "alt+y",
    "command": "workbench.action.terminal.toggleTerminal",
    "when": "terminal.active"
  },
  {
    "key": "ctrl+oem_3",
    "command": "-workbench.action.terminal.toggleTerminal",
    "when": "terminal.active"
  }
]
```
