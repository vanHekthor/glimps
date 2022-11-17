# GLIMPS
VS Code extension used in the SoftVR user study (https://git.informatik.uni-leipzig.de/SWS/softvr-user-study)

## Installation

The following commands will create the VSIX package containing the extension:
```
npm install
vsce package
```
This results in a `perf-debug-0.0.1.vsix` inside the root folder.
For installing the extension in VS Code use:
```
code --install-extension perf-debug-0.0.1.vsix
```
You may need to reload the VS Code window.

## Known issues
The extension does not start on Ubuntu 21.10 and 22.04 (but 20.04 is fine) in combination
with VS Code version 1.62+ (october 2021 and newer).
When working on Ubuntu 21.10+, we recommend to install the VS Code version 1.61 (https://code.visualstudio.com/updates/v1_61).
