# Chrome Util Extension

Inspired by Alfred, Cmd+Shift+P (Vscode, Chrome Devtools), Cmd+Shift+A (Intellij)

1. Install the Extension to Chrome or Edge

2. Open the Extension, by using the hotkey (control + space) or clicking the icon

3. Search and execute a command

## Supported Commands

- `pin unpin tab`
- `unpin all tabs`
- `pin all tabs`
- `close all unpinned tabs`
- `close tabs to the right`
- `move current tab to new window`
- `collect all tabs into one window`
- `move tab highlighted tabs left`
- `move tab highlighted tabs right`
- `move tab highlighted tabs to start`
- `move tab highlighted tabs to end`
- `open extension manager`
- `open extension shortcuts manager`

[Command configuration in code](./src/commands/commands.ts)

## Default Shortcuts (MacOS)

- `Ctrl+Space` - open runner dialogue
- `Cmd+Shift+X` - pin/unpin current tab
- `Ctrl+Shift+Left` - move tab left
- `Ctrl+Shift+Left` - move tab right

To find the shortcuts for your platform see the `"commands"` in [Shortcut configuration in code](./config/manifest.json)

To modify these shortcuts:

- open the runner and search for `open extension shortcuts`
- or navigate to `chrome://extensions/shortcuts`

## Contributing

To get the environment set up locally see [Contributing](./docs/contributing/getting-started.md)
