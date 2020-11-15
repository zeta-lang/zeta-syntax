<p align=right><img alt="Zeta Logo" src="https://raw.githubusercontent.com/zeta-lang/zeta-syntax/master/images/zeta_icon.png" width=25%/></p>

# Zeta Syntax

VS Code syntax highlighting extension for the [Zeta scripting language](https://github.com/zeta-lang/zeta)

## Usage
There are three tasks in the `tasks.json` to facilitate use and development:

+ `Build VS Code Syntax Extension`
  > Create a new `.vsix` package for the extension (It should be kept up to date in source tracking)

  > Requires `vsce` to be available from the command line (installed with `npm install -g vsce`)

+ `Install VS Code Syntax Extension`
  > Install the packaged extension to the version of `code` available from the command line

+ `Build and Install VS Code Syntax Extension`
  > Runs both `Build` and `Install` tasks in sequence

All of these tasks should work on Windows and Linux, provided you have `vsce` and `code` available from the command line.

If you just want to use the extensionm, you can simply run the `Install` command immediately, as the `vsix` package is prebuilt and included in source tracking.

After running `Install`, if the editor does not prompt you to restart, press `Ctrl + Shift + P` and type `Developer: Reload Window`
