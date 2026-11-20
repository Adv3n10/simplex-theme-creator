# SimpleX Theme Creator

A visual color editor for [SimpleX Chat](https://simplex.chat) themes. Pick a color for each part of the app, see the result live on a chat list and a conversation, then download the `.theme` file and import it in the app.

**[Open the live version](https://adv3n10.github.io/simplex-theme-creator/)**

> **Unofficial.** This is a community tool and is not affiliated with or endorsed by SimpleX.

## Features

- A color picker, opacity slider and `#AARRGGBB` hex field for every themeable color, plus wallpaper background and tint
- Live preview of a chat list and a conversation
- Click any part of the preview to jump to its color, or hover a color to see where it is used
- Dark and Light base themes, with SimpleX Dark and Light starter presets
- Download the finished theme as a `.theme` file, or copy its text
- Import an existing theme to keep editing it

## Use it

Use the [live version](https://adv3n10.github.io/simplex-theme-creator/), or download this repo and open `index.html` in any browser. It is a single file with no build step and no server needed (fonts load from Google Fonts when online).

1. Choose a base (Dark or Light) or start from a preset.
2. Change colors with the picker, the opacity slider or the hex field.
3. Click **Download .theme** to save `mytheme.theme`. You can also click **Copy theme** and save the text yourself.
4. Import the file in SimpleX Chat under Appearance.

To edit an existing theme, paste its contents into the import box and click **Load into editor**.

## Notes

- The preview is a hand-built approximation of the SimpleX Chat screens. It is not rendered from the app's own code, so check an exported theme once in the real app.
- Colors use the `#AARRGGBB` format found in SimpleX theme files.
- The "SimpleX Dark" preset uses the colors of the app's default dark theme as shown in community theme collections.

## Credits

Built with Claude (Anthropic).

## License

MIT, see [LICENSE](LICENSE).
