# Base16 for Windows Terminal

See the [Base16 repository](https://github.com/chriskempson/base16) for more information.
This theme was built with [base16-builder-python](https://github.com/InspectorMustache/base16-builder-python).

## Installation

1. Copy the content of the desired scheme `.json` file from the `colors` directory.
2. Open `%localappdata%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\profiles.json` with a text editor.
3. Paste the content of clipboard under `schemes`.
4. Set the `colorScheme` of your profile to the file name of the scheme (without the `.json` extension).

### Fix Invisible Cursor

1. Copy the line `"foreground": "#xxxxxx"` from the color scheme.
2. Paste the line in your profile with `foreground` changed to `cursorColor`.

### Example

```json
"colorScheme": "base16-default-dark",
"cursorColor": "#d8d8d8"
```
