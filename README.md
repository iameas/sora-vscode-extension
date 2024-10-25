# Sora Language Support Extension for VS Code

Welcome to the **Sora Language Support** Visual Studio Code extension, providing syntax highlighting, linting, snippets, and build commands for the **Sora** programming language, which is designed for mobile app development.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Syntax Highlighting**: Supports Sora language syntax through `sora.tmLanguage.json`.
- **Code Snippets**: Includes predefined snippets for quick code scaffolding.
- **Linting**: Helps maintain code quality with customizable linting rules.
- **Code Formatting**: Integrated formatter for consistent code styling.
- **Debugging**: Debug support for easier troubleshooting and code analysis.
- **Custom Commands**: Initialize, build, run, and deploy Sora applications directly from VS Code.

## Installation

1. Clone or download this repository.
2. Open the `sora-extension-1.0.0/` folder in VS Code.
3. Run `cargo install` to install dependencies.
4. Press `F5` to start debugging and open a new VS Code window with the extension loaded.

Alternatively, if published on the [VS Code Marketplace](https://marketplace.visualstudio.com/), you can search for **Sora Language Support** and install it directly.

## Usage

1. Open any `.sora` file, and the extension will automatically activate.
2. Utilize syntax highlighting, snippets, linting, and other features while coding.
3. Access custom commands through the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P` on macOS) or context menus.

## Commands

| Command             | Description                    |
|---------------------|--------------------------------|
| `sora.initProject` | Sets up a new Sora project structure. |
| `sora.buildApp`    | Compiles the Sora project for deployment. |
| `sora.runApp`      | Launches the Sora application locally. |
| `sora.deployApp`   | Deploys the Sora application to the specified environment. |

### Keyboard Shortcuts

- **Initialize Project**: `Ctrl+Alt+I` / `Cmd+Alt+I` (macOS)
- **Build App**: `Ctrl+Alt+B` / `Cmd+Alt+B` (macOS)
- **Run App**: `Ctrl+Alt+R` / `Cmd+Alt+R` (macOS)
- **Deploy App**: `Ctrl+Alt+D` / `Cmd+Alt+D` (macOS)

## Contributing

We welcome contributions to enhance and expand the Sora Language Support extension! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on submitting issues, code, or documentation.

### Steps to Contribute

1. Fork this repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make changes and commit: `git commit -m 'Add feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a Pull Request.

## License

This project is licensed under the terms of the [MIT License](LICENSE).

## Contact

For questions or support, please open an issue on the [GitHub Repository](https://github.com/iameas/sora-vscode-extension) or contact us via email.

---

Thank you for using **Sora Language Support**!
