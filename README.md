# PSYCHRONIC_PictureChoices

Display picture-based choices anywhere on screen with smooth zoom transitions and restore default positioning after done.

## What It Does

PSYCHRONIC_PictureChoices.

## Highlights

- Use SetChoiceImage or SetMultipleChoiceImages before Show Choices if you want picture-based choices.
- If no picture choices are set, normal behavior applies.
- After the picture choices are done, the plugin restores $gameMessage settings and calls updatePlacement().

## Plugin Commands

- SetChoiceImage
- SetMultipleChoiceImages

## Basic Usage

- Use SetChoiceImage or SetMultipleChoiceImages before Show Choices if you want picture-based choices.
- If no picture choices are set, normal behavior applies.
- After the picture choices are done, the plugin restores $gameMessage settings and calls updatePlacement().
@command SetChoiceImage
@text Set Choice Image
@desc Assign image to a single choice with optional scale/speed.
@arg choiceIndex
@type number

## Compatibility

- RPG Maker MZ
- JavaScript plugin for `js/plugins/`

## Installation

1. Download `PSYCHRONIC_PictureChoices.js`.
2. Place it in your RPG Maker MZ project's `js/plugins/` folder.
3. Enable it from the RPG Maker Plugin Manager.

## Source

This version was exported from the RPG Reactor Complex template source plugin folder.

## Author

* @url

* @help

## License

MIT. See `LICENSE`.
