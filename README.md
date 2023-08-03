# Base16 for Windows Terminal

See the [Base16 repository](https://github.com/chriskempson/base16) for more information.
This theme was built with [base16-builder-python](https://github.com/InspectorMustache/base16-builder-python).

## Installation

1. Copy the content of the desired scheme `.json` file from the `colors` directory.
2. Go to Settings in Windows Terminal.
3. Click the gear button at the bottom left to open the JSON settings file.
4. Paste the content of clipboard under `schemes`.
5. Set the `colorScheme` of your profile to the file name of the scheme (without the `.json` extension).

## "256" Variants

**TL;DR:** If you don't want your ANSI Bright Yellow color to look like your background colour, use the "256" variants.

*Acknowledgement:* The following is taken from [base16-item2](https://github.com/tinted-theming/base16-iterm2).

The 256 variations are provided for those people who use a lot of
colored command line programs and wish to keep the default 16 ANSI
colors intact. If this means nothing to you please make use of the
default 16 color versions (the files without 256 in them). On the other
hand if you'd like to keep your 16 ANSI colors intact, go ahead and use
the 256 color variations but please note you'll need to modify some of
the 256 colorspace with the [base16-shell](https://github.com/tinted-theming/base16-shell) script.

