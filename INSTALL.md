### [Windows Terminal](https://github.com/microsoft/terminal)

#### Download

Download using the [GitHub .zip download](https://github.com/anacvignola/windows-terminal/archive/main.zip) option.

#### Install

Start Windows Terminal and click on the down arrow symbol :gear: from menu bar. This will open a drop down menu from which select Settings option. Alternatively use `Ctrl + ,` to open Settings directly.

In the `settings.json` settings file for Windows Terminal, find the `schemes` section and paste the content of `omni.json`.

Example:

```json
"schemes": [
  {
    "name": "Omni",
    "cursorColor": "#F8F8F2",
    "selectionBackground": "#44475A",
    "background": "#191622",
    "foreground": "#E1E1E6",
    "black": "#000000",
    "blue": "#BD93F9",
    "cyan": "#8D79BA",
    "green": "#50FA7B",
    "purple": "#FF79C6",
    "red": "#FF5555",
    "white": "#BFBFBF",
    "yellow": "#EFFA78",
    "brightBlack": "#4D4D4D",
    "brightBlue": "#CAA9FA",
    "brightCyan": "#AA91E3",
    "brightGreen": "#5AF78E",
    "brightPurple": "#FF92D0",
    "brightRed": "#FF6E67",
    "brightWhite": "#E6E6E6",
    "brightYellow": "#EAF08D"
  }
]
```

#### Activating theme

Once the color scheme has been defined, it's time to enable it. Find the `profiles` section and add a `colorScheme` value to the default profile.

Example:

```json
"profiles": {
    "defaults": {
        "colorScheme" : "Omni"
    }
}
```

