# Ultralove Black Theme

A sophisticated dark theme for Visual Studio Code inspired by the GitHub Dark Colorblind theme with deep black backgrounds and carefully crafted color palette.

## Features

- **Deep Black Background**: Ultra-dark editor background (#010409) for reduced eye strain in low-light environments
- **High Contrast**: Carefully balanced contrast ratios for excellent readability
- **Comprehensive Coverage**: Full theming of all VS Code UI elements including editor, sidebar, terminal, and panels
- **Syntax Highlighting**: Rich color palette for code syntax highlighting across multiple programming languages
- **Git Integration**: Clear visual indicators for git status and diff highlighting
- **Terminal Colors**: Complete ANSI color palette for integrated terminal
- **Error Lens Support**: Built-in support for Error Lens extension with custom colors

## Color Palette

The theme uses a refined color palette based on GitHub's design system:

- **Primary Background**: `#010409` - Deep black for main editor
- **Secondary Background**: `#0d1117` - Slightly lighter for tabs and headers
- **Accent Color**: `#f78166` - Orange accent for active elements
- **Text Primary**: `#c9d1d9` - High contrast white for main text
- **Text Secondary**: `#8b949e` - Muted for secondary text
- **Syntax Colors**:
  - Keywords: `#ff7b72` (Red)
  - Strings: `#a5d6ff` (Light blue)
  - Functions: `#d2a8ff` (Purple)
  - Numbers: `#79c0ff` (Blue)
  - Comments: `#6e7681` (Gray, italic)

## Installation

### From Source
1. Clone this repository
2. Copy the theme files to your VS Code extensions directory
3. Open VS Code and go to Preferences > Color Theme
4. Select "Ultralove Black" from the list

### Development Installation
1. Open this project in VS Code
2. Press `F5` to launch Extension Development Host
3. In the new window, select "Ultralove Black" theme

## Customization

You can customize specific colors by adding overrides to your VS Code settings:

```json
{
  "workbench.colorCustomizations": {
    "[Ultralove Black]": {
      "editor.background": "#000000"
    }
  }
}
```

## Screenshots

*Screenshots will be added here*

## Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

## License

MIT License - see LICENSE file for details.

## Changelog

### 0.1.0
- Initial release
- Complete theme coverage for all VS Code UI elements
- Syntax highlighting for major programming languages
- Error Lens extension support
- Git integration colors
