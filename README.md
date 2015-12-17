# Console

This extension will create command `console.open` to Visual Studio Code, and override keybindings `Ctrl/Cmd+Shift+C` with this command.

You must configure a console executable to use this extension.

For example:

```json
{
    "console.executable": "C:\\Program Files\\ConEmu\\ConEmu64.exe",
    "console.args": ["/single"]
}
```

## License

MIT License.
