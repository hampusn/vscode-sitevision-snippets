# SiteVision snippets for VSCode

Contains snippets for developing WebApps, RESTApps and script modules in [SiteVision][sitevision].

## Installation

### Download extension and install through Command Palette 

1. Download the extension file (.VSIX) from [the latest release][latest-release].
2. Open up VS Code and run `Extensions: Install from VSIX...` in the **Command Palette**.
3. Select the extension file from _Step 1_.

### Download source and build

_Requires `git`, `node` ([Node.js][node-js]), `npm` (Part of Node.js) and `code` ([VS Code CLI][vscode-cli])._

Begin with cloning, installing dependencies, building and installing extension.

```sh
git clone git@github.com:hampusn/vscode-sitevision-snippets.git
cd vscode-sitevision-snippets
npm i
npm run build-and-install
```

Finish with reloading open windows of VS Code by running `Developer: Reload Window` in the **Command Palette**.


[sitevision]: https://www.sitevision.se
[latest-release]: ../../releases/latest
[node-js]: https://nodejs.org/en
[vscode-cli]: https://code.visualstudio.com/docs/editor/command-line
