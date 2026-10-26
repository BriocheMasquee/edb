<div align="center">
  <img src="images/banner.webp" width="660">

  # Exploirateurs de bruines

  Game system for [Encounter+](https://itunes.apple.com/us/app/encounter+/id1170693487?ls=1&mt=8)

  ![Version](https://img.shields.io/badge/version-1.1.0-blue)
  ![Encounter+](https://img.shields.io/badge/Encounter%2B-%E2%89%A5%205.1.0-green)
  ![Languages](https://img.shields.io/badge/languages-FR%20%7C%20EN-lightgrey)

  [🇫🇷 Version française](README.md)
</div>

> [!NOTE]
> This system does not contain any game content (rules, resources, images…). It provides the structure the system needs: sheets, views, theme and settings. Content must be entered manually in the Encounter+ library. The English labels used by the system (Exploiteer, True Tales, Gross-outs…) are unofficial translations.

## What is *Exploirateurs de bruines*?

*Exploirateurs de bruines* is a post-apocalyptic fantasy role-playing game created by [Vivien Féasson](https://vivienfeasson.com) and published by Éditions de L'Averse. You play lost children in the City, a maze under a rain that never stops, where sirens prowl: monsters that take any shape to eat the kids. To survive, the children have built enclaves, and the Exploiteers are those who dare to leave them and search the *bruines* (the "drizzles"), the districts nobody has managed to tame, in search of grub and treasure.

The tone is childlike, funny and unsettling at once. The rules are light: six Resistances rated from 1 to 20 (a test succeeds if you roll no higher than your score on a D20), classes, wear on equipment, and a Deluge Master (MD), the game's GM, who improvises when the rules run out. It borrows ideas from *The Black Hack* and *Macchiato Monsters*, and it encourages recycling old "dungeons" to invent new bruines. It is therefore often compared to the Old School Renaissance (OSR) movement.

## Installation

1. Download `edb.system` from the [latest release](https://github.com/BriocheMasquee/edb/releases/latest).
2. Open the file with Encounter+ (Settings, then Import). The system installs and becomes the primary system.

## System settings

**Initiative.** The game has no initiative system: the Exploiteers act, then the GM reacts. The app still needs initiative values, so one is built in. Choose the formula in the system settings ("Initiative" group) before the game starts:

| Initiative type | Value |
|---|---|
| By the Rules (default) | Exploiteers 1, critters 0. The GM adjusts by hand. |
| Test “You can’t catch me!” | Exploiteers: 7 if the test succeeds, 0 otherwise. Critters: their speed. |
| Speed Value | Critters: their speed. Exploiteers: a kiddo’s speed. |

Speeds range from the turtle (1) to the cheetah (6).

**Maps.** The game counts distances in squares. In each map's settings, set the scale to `1` and the unit to `sq` or `squares`.

**Images.** The system settings ("Interface" group) let you choose which image is shown in lists and in the combat tracker: icon, image or token.

## Using the character sheet

**Level**: if left empty, it counts as level 1. Skills for higher levels appear automatically from level 2.

**Resistances**: the **Test** button rolls a D20, successful if the die is lower than or equal to the score. A selector chooses the type of roll (normal, with advantage or with disadvantage). An alternative advantage/disadvantage rule can be selected when editing the sheet (Stats tab). The log shows **1** for a success and **0** for a failure.

**Hit points**: enter the current hit points, the maximum hit points and the hit die. Tapping the HP box opens Encounter+'s health management.

**Fame**: the sheet shows how many fame points are missing before gaining a level. Resetting fame at level-up is done manually.

**Items**: a button rolls a weapon's damage. The usage menu rolls the usage die and lets you change dice (from D12 down to D4). The checkboxes track the remaining uses of gear and provisions.

**Encumbrance**: the sheet computes the total and flags burdened (4 to 6), overloaded (7 to 9) and crushed (10 or more).

## Credits and licenses

*Exploirateurs de bruines* is a game published by Éditions de L'Averse©. Concept, text and publication: Vivien Féasson. Artistic design, illustrations and layout: Willy Cabourdin.

Fonts: [Merriweather](fonts/OFL-Merriweather.txt), [Oswald](fonts/OFL-Oswald.txt) and [Covered By Your Grace](fonts/OFL-Covered%20By%20Your%20Grace.txt), under the SIL Open Font License.
