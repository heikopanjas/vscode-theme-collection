# Ultralove Theme Collection

A sophisticated collection of VS Code themes featuring carefully crafted color palettes for different coding environments and preferences.

## Available Themes

### Ultralove Black
A sophisticated dark theme inspired by the GitHub Dark Colorblind theme with deep black backgrounds for comfortable low-light coding.

### Ultralove White
A clean light theme based on GitHub Light Colorblind with crisp whites and high contrast for bright environment coding.

## Features

- **Multiple Variants**: Black and White themes for different lighting conditions
- **Deep Black Background**: Ultra-dark editor background (#010409) for reduced eye strain in low-light environments
- **Clean White Background**: Pure white editor background (#ffffff) for bright, high-contrast environments
- **High Contrast**: Carefully balanced contrast ratios for excellent readability across all variants
- **Comprehensive Coverage**: Full theming of all VS Code UI elements including editor, sidebar, terminal, and panels
- **Syntax Highlighting**: Rich color palette for code syntax highlighting across multiple programming languages
- **Git Integration**: Clear visual indicators for git status and diff highlighting
- **Terminal Colors**: Complete ANSI color palette for integrated terminal
- **Error Lens Support**: Built-in support for Error Lens extension with custom colors

## Color Palettes

### Ultralove Black
The dark theme uses a refined color palette based on GitHub's dark design system:

- **Primary Background**: `#010409` - Deep black for main editor
- **Secondary Background**: `#0d1117` - Slightly lighter for tabs and headers
- **Accent Color**: `#f78166` - Orange accent for active elements
- **Text Primary**: `#c9d1d9` - High contrast white for main text
- **Text Secondary**: `#8b949e` - Muted for secondary text

### Ultralove White
The light theme uses a clean color palette based on GitHub's light design system:

- **Primary Background**: `#ffffff` - Pure white for main editor
- **Secondary Background**: `#f6f8fa` - Light gray for tabs and headers
- **Accent Color**: `#fd7e14` - Orange accent for active elements
- **Text Primary**: `#1f2328` - High contrast black for main text
- **Text Secondary**: `#656d76` - Muted for secondary text

### Syntax Colors (Both Themes)
- **Keywords**: Red tones for language keywords
- **Strings**: Blue tones for string literals
- **Functions**: Purple tones for function names
- **Numbers**: Blue tones for numeric literals
- **Comments**: Gray tones with italic styling

## Installation

### From Source
1. Clone this repository
2. Copy the theme files to your VS Code extensions directory
3. Open VS Code and go to Preferences > Color Theme
4. Select "Ultralove Black" or "Ultralove White" from the list

### Development Installation
1. Open this project in VS Code
2. Press `F5` to launch Extension Development Host
3. In the new window, select "Ultralove Black" or "Ultralove White" theme

## Customization

You can customize specific colors by adding overrides to your VS Code settings:

```json
{
  "workbench.colorCustomizations": {
    "[Ultralove Black]": {
      "editor.background": "#000000"
    },
    "[Ultralove White]": {
      "editor.background": "#f8f9fa"
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
