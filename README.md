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

- `SetChoiceImage`
- `SetMultipleChoiceImages`

## Parameter Summary

- choiceIndex: 1-based choice index.
- pictureName
- xOffset
- yOffset
- selectedScale
- transitionSpeed

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

@command SetChoiceImage
@text Set Choice Image
@desc Assign image to a single choice with optional scale/speed.

@arg choiceIndex
@type number
@min 1
@desc Choice number (1-based).

@arg pictureName
@type file
@dir img/pictures
@desc Image filename (no extension).

@arg xOffset
@type number
@default 0

@arg yOffset
@type number
@default 0

@arg selectedScale
@type number
@decimals 2
@default 1.1

@arg transitionSpeed
@type number
@decimals 2
@min 0.01
@max 1
@default 0.1

@command SetMultipleChoiceImages
@text Set Multiple Choice Images
@desc Assign images and parameters to multiple choices.

@arg choices
@type struct<ChoiceImage>[]
@desc A list of choice image entries.

## Source

This standalone repository is generated from the latest PSYCHRONIC plugin source in the RPG Reactor Complex template.

## License

MIT. See `LICENSE`.
