# Filla - Color Palette Extrator

A Figma plugin that automatically detects all unique color fills used within a selected frame and organizes them into a visual palette.

## Features

- **Deep Layer Analysis**: Recursively analyzes all layers within a selected frame, no matter how deeply nested they are
- **Unique Color Detection**: Identifies and extracts all unique solid color fills
- **Visual Palette Generation**: Creates a neatly organized grid of color swatches
- **Color Labeling**: Labels each color with its hexadecimal value
- **Color Style Creation**: Option to quickly convert extracted colors into Figma Color Styles

## Installation

### Development Installation
1. Clone or download this repository
2. Open Figma desktop app
3. Go to Plugins > Development > Import plugin from manifest
4. Navigate to the downloaded folder and select the `manifest.json` file

### From Figma Community (Coming Soon)
1. Visit the plugin page on Figma Community
2. Click "Install" button
3. The plugin will be available in your Figma plugins list

## How to Use

1. Select a frame or component in your Figma workspace
2. Run the plugin from Plugins > Color Palette Extractor
3. Click the "Extract Colors" button in the plugin dialog
4. The plugin will create a new frame with your extracted color palette
5. Optionally, click "Create Color Styles" to add the colors to your document's styles

## Files in this Repository

- `manifest.json`: Plugin configuration
- `code.js`: Main plugin code
- `ui.html`: User interface

## Requirements

- Figma desktop app or Figma web (in compatible browsers)

## Troubleshooting

If you're not seeing all colors from your design:
- Make sure you've selected a parent frame that contains all the elements you want to analyze
- The plugin only detects solid color fills (not gradients, images, or effects)
- Check that layers aren't hidden or locked

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improvements.

## License

MIT