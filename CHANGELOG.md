# Changelog

All notable changes to this theme are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), versions follow [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [1.1.0] - 2026-11-25

### Fixed
- Keyboard focus on tiles (card-mod): a 2 px ring in black (white in dark mode) around the tile. Before, the ring of a solid red tile was white on the light page and could not be seen.

### Changed
- Buttons, links and tabs are black (white in dark mode); red is kept for switched-on states, heating, alarms, errors and the selection, so it stays a signal.
- Warnings are black on pale red, errors red, success and info black on grey.
- One red for text in dark mode (`#ff6b63`) instead of two close shades.
- Darker track for switches that are off, now at least 3:1 against the card.

### Added
- Heading cards are numbered 01, 02, 03 … like the columns of a poster (card-mod).
- The thermostat title is set flush left (card-mod).
- Arimo added to the font stack (ChromeOS).

## [1.0.0] - 2026-11-24

### Added
- First release: one theme with light and dark mode in the International Typographic Style.
- Near-white paper, one signal red and black. Primary colour, switched-on states, heating and selection are red, calm states black, off grey; warning and success scales are mapped to black and grey, so no third hue appears.
- Square corners, no shadows, cards separated by the grid gap and a thin black rule along their top edge. Works without add-ons.
- Neo-grotesque system sans (Helvetica Neue, Arial, Nimbus Sans, Liberation Sans), bold tile names and headings.
- Dark mode derived separately: white and red on deep black-grey.
- Optional card-mod rules: switched-on devices become solid red tiles with white text, big numbers of entity, sensor and weather cards become large and bold, heading cards get a heavier rule and capitals, the dashboard title grows, coloured lights turn red in badges, the selected sidebar entry becomes a red bar.
