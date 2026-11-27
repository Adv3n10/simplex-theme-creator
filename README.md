# SimpleX Theme Creator

A visual color editor for [SimpleX Chat](https://simplex.chat) themes. Pick a color for each part of the app, see the result live on a chat list and a conversation, then download the `.theme` file and import it in the app.

**[Open the live version](https://adv3n10.github.io/simplex-theme-creator/)**

> **Unofficial.** This is a community tool and is not affiliated with or endorsed by SimpleX.

## Features

- A color picker, opacity slider and `#AARRGGBB` hex field for every themeable color, plus wallpaper background, tint, scale and scale type
- Live preview of a chat list and a conversation in phone frames
- Hover any part of the preview to see its color name and value, and click it to jump to that color
- All four base themes: Dark, Light, SimpleX and Black
- Eight starter presets, plus a generator that builds a full palette from one accent color (or a random one)
- Readability panel that checks text contrast (WCAG ratios) on bubbles, backgrounds and menus
- Undo and redo, autosave in your browser, and per-color reset to the starting value
- Screen color picker (eyedropper) in Chromium-based browsers
- Share a theme as a link
- Download the finished theme as a `.theme` file named after your theme, or copy its text
- Import an existing theme by dropping the file, choosing it, or pasting its contents
- Light, dark or system appearance for the editor itself
- Keyboard shortcuts: `Ctrl+Z` undo, `Ctrl+Shift+Z` redo, `Ctrl+S` download

## Use it

Best used on a desktop browser.

Use the [live version](https://adv3n10.github.io/simplex-theme-creator/), or download this repo and open `index.html` in any browser. It is a single file with no build step and no server needed (fonts load from Google Fonts when online).

1. Choose a base (Dark, Light, SimpleX or Black), start from a preset, or generate a palette from one color.
2. Change colors with the picker, the opacity slider or the hex field.
3. Name your theme in the top bar, then click **Download** to save the `.theme` file. You can also click **Copy text** and save it yourself.
4. Import the file in SimpleX Chat under Appearance.

To edit an existing theme, drop the file onto the import box, or paste its contents and click **Load into editor**.

## Notes

- The preview is a hand-built approximation of the SimpleX Chat screens. It is not rendered from the app's own code, so check an exported theme once in the real app.
- Colors use the `#AARRGGBB` format found in SimpleX theme files.
- The "SimpleX Dark" preset uses the colors of the app's default dark theme as shown in community theme collections.

## Credits

Built with Claude (Anthropic).

## License

MIT, see [LICENSE](LICENSE).
