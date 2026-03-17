<h3 align="center">
    Claude Theme for <a href="https://code.visualstudio.com">VSCode</a> / <a href="https://cursor.sh">Cursor</a>
</h3>

<p align="center">
    <em>A warm, dark theme inspired by Anthropic's Claude interface</em>
</p>

<p align="center">
</p>

## About

Claude Theme brings the warm, focused aesthetic of [Anthropic's Claude](https://claude.ai) into your editor. Built around a neutral dark background with carefully chosen accent colors, it's designed to be easy on the eyes during long coding sessions while keeping syntax clear and readable.

No blue-tinted backgrounds. No harsh contrasts. Just warm, balanced tones that let you focus on what matters.

## Palette

| Color                                                        | Hex       | Role                        |
| ------------------------------------------------------------ | --------- | --------------------------- |
| ![#262624](https://placehold.co/16x16/262624/262624) | `#262624` | Editor background           |
| ![#1E1E1C](https://placehold.co/16x16/1E1E1C/1E1E1C) | `#1E1E1C` | Sidebar & terminal          |
| ![#1A1A18](https://placehold.co/16x16/1A1A18/1A1A18) | `#1A1A18` | Activity bar & title bar    |
| ![#F4845F](https://placehold.co/16x16/F4845F/F4845F) | `#F4845F` | Keywords, tags & accents    |
| ![#F4A58A](https://placehold.co/16x16/F4A58A/F4A58A) | `#F4A58A` | Numbers & constants         |
| ![#7EC699](https://placehold.co/16x16/7EC699/7EC699) | `#7EC699` | Strings                     |
| ![#E8C47C](https://placehold.co/16x16/E8C47C/E8C47C) | `#E8C47C` | Classes & types             |
| ![#7CACE8](https://placehold.co/16x16/7CACE8/7CACE8) | `#7CACE8` | Functions                   |
| ![#C49BE8](https://placehold.co/16x16/C49BE8/C49BE8) | `#C49BE8` | Properties                  |
| ![#7CE8D4](https://placehold.co/16x16/7CE8D4/7CE8D4) | `#7CE8D4` | Interfaces & regex          |
| ![#F28B82](https://placehold.co/16x16/F28B82/F28B82) | `#F28B82` | Errors & deletions          |
| ![#E8E4DC](https://placehold.co/16x16/E8E4DC/E8E4DC) | `#E8E4DC` | Foreground text             |

## Installation

### From VSIX (recommended)

1. Download the `.vsix` file from the [latest release](https://github.com/duca/claude-theme/releases/latest)
2. Open Command Palette (`Cmd+Shift+P`)
3. Select **"Extensions: Install from VSIX..."**
4. Choose the downloaded file

### Manual

```bash
# Clone the repo
git clone https://github.com/duca/claude-theme.git

# Package it
cd claude-theme
npx @vscode/vsce package --skip-license

# Install via CLI
code --install-extension claude-anthropic-theme-1.0.0.vsix

# Or for Cursor
cursor --install-extension claude-anthropic-theme-1.0.0.vsix
```

## Activation

1. Open Command Palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)
2. Search for **"Color Theme"**
3. Select **Claude Dark (Anthropic)**

## Recommended Settings

```jsonc
{
  "editor.semanticHighlighting.enabled": true,
  "terminal.integrated.minimumContrastRatio": 1,
  "window.titleBarStyle": "custom",
  "editor.fontFamily": "'JetBrains Mono', 'Fira Code', Menlo, monospace",
  "editor.fontLigatures": true
}
```

## Language Support

Optimized for syntax highlighting in:

- TypeScript / JavaScript / JSX / TSX
- React Native / Expo
- HTML / CSS / SCSS
- JSON / YAML
- Python
- Go
- Rust
- Shell / Bash
- Markdown

## License

MIT

---

<p align="center">
  <sub>Built with the warmth of Claude's coral by <a href="https://github.com/duca">@duca</a></sub>
</p>
