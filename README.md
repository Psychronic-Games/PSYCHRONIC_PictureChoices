# PSYCHRONIC_PictureChoices

**RPG Maker MZ Plugin**

Display picture-based choices anywhere on screen with smooth zoom transitions and restore default positioning after done.

## What It Does

PSYCHRONIC_PictureChoices.

## Plugin File

- `PSYCHRONIC_PictureChoices.js`
- Target: RPG Maker MZ
- Author: * @url
- URL: * @help

## Plugin Commands

### Set Choice Image

- Command: `SetChoiceImage`
- Description: Assign image to a single choice with optional scale/speed.

Arguments:

- `choiceIndex` (choiceIndex) - type: number: Choice number (1-based).
- `pictureName` (pictureName) - type: file: Image filename (no extension).
- `xOffset` (xOffset) - type: number; default: 0
- `yOffset` (yOffset) - type: number; default: 0
- `selectedScale` (selectedScale) - type: number; default: 1.1
- `transitionSpeed` (transitionSpeed) - type: number; default: 0.1

### Set Multiple Choice Images

- Command: `SetMultipleChoiceImages`
- Description: Assign images and parameters to multiple choices.

Arguments:

- `choices` (choices) - type: struct<ChoiceImage>[]: A list of choice image entries.

## Installation

1. Download `PSYCHRONIC_PictureChoices.js`.
2. Place it in your RPG Maker MZ project's `js/plugins/` folder.
3. Enable it from the RPG Maker Plugin Manager.
4. Configure any plugin parameters or commands listed below.

## Full Plugin Help

### PSYCHRONIC_PictureChoices

### HOW TO USE
- Use SetChoiceImage or SetMultipleChoiceImages before Show Choices if you want picture-based choices.
- If no picture choices are set, normal behavior applies.
- After the picture choices are done, the plugin restores $gameMessage settings and calls updatePlacement().

## Source

This standalone repository is generated from the latest PSYCHRONIC plugin source in the RPG Reactor Complex template.

## License

MIT. See `LICENSE`.
