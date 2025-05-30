# .zterm – Terminal as a File (VS Code Extension)

`.zterm` is a custom Visual Studio Code extension that transforms your terminal workflows into an interactive, editable file format.

## 📄 File Type

- `.zterm` – stores terminal sessions as JSON
- Each command and its logs are saved as individual blocks

## 🔧 Core Features

- Custom WebView editor for `.zterm` files
- JSON-based structure: `{ command, output, status, timestamp }`
- Bottom input bar for running commands
- Inline terminal execution (`vscode.Terminal.sendText`)
- Scrollable logs inside draggable, resizable blocks
- Autocomplete from command history
- Split view for side-by-side command comparison
- Delete command/log blocks
- Persistent log storage within the file

## 🌟 Bonus Features (Free)

- Pin command blocks
- Tag with labels (e.g. #build, #test)
- Collapsible command folders
- One-click replay
- Fuzzy search in logs
- Execution stats
- Export session as Markdown or JSON
- Diff view between command runs
- Save/load snippets

## 🚀 Bonus Features (If You Want to Go Premium)

- Run multiple commands in sequence
- Save command groups as templates
- Export `.zterm` to CI-friendly formats
- Plugin system for logs (Jest, Webpack, etc.)
- Real-time output stream
- Git integration
- Snapshot mode
- Scheduled command runners
- Secure/hidden output blocks
- Result-based command filtering

---

## 📦 File Format Example

```json
{
  "sessionName": "dev-setup",
  "commands": [
    {
      "id": "001",
      "command": "npm run dev",
      "output": ["Starting...", "Compiled successfully."],
      "timestamp": "2025-05-10T10:00:00Z",
      "status": "done"
    }
  ]
}
```

---

## 💡 Ideal Use Cases

- Dev server setup logs
- CI/CD test runners
- Terminal-based debugging history
- Documenting and sharing command sessions

## 🧪 Extension Status

- MVP in progress
- Planned release: TBD

## 🖼 UI Mockups

UI designs coming soon — to be prototyped via PowerPoint or Figma.
