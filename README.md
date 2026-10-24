<div align="center">
  <img src="images/banner.webp" width="660">

  # Exploirateurs de bruines

  Système de jeu pour [Encounter+](https://itunes.apple.com/us/app/encounter+/id1170693487?ls=1&mt=8)

  ![Version](https://img.shields.io/badge/version-1.0.0-blue)
  ![Encounter+](https://img.shields.io/badge/Encounter%2B-%E2%89%A5%205.1.0-green)
  ![Langues](https://img.shields.io/badge/langues-FR%20%7C%20EN-lightgrey)
</div>

*Exploirateurs de bruines* est un jeu de rôle de fantasy post-apocalyptique inspiré de l'OSR, de Vivien Féasson (éd. L'Averse), où des enfants perdus bravent la pluie et les monstres de la Ville.


> [!NOTE]
> Ce système ne contient pas de contenu du jeu (règles, ressources, images…). Il fournit la structure nécessaire au système : les fiches, les vues, le thème et les réglages. Le contenu doit être saisi manuellement dans la bibliothèque d'Encounter+.

## Installation

1. Téléchargez `edb.system` dans la [dernière version](https://github.com/BriocheMasquee/edb/releases/latest).
2. Ouvrez le fichier avec Encounter+ (Réglages, puis Import, ou touchez le fichier là où votre appareil le propose). Le système s'installe et devient le système principal.

Testé avec Encounter+ 5.1.0 (build 4644).

## Bien démarrer

**Initiative.** Le livre n'a pas d'initiative : les Exploirateurs agissent, puis MD réagit. Le système lance quand même une valeur pour tous les combattants au début du combat, et vous choisissez la formule dans les réglages du système (groupe « Initiative ») :

| Type d'initiative | Valeur |
|---|---|
| Selon la règle (par défaut) | Exploirateurs 1, bestioles 0. Le MD ajuste à la main. |
| Test « Tu m'attraperas pas ! » | Exploirateur : 7 si le test réussit, 0 sinon. Bestiole : sa vitesse. |
| Valeur de vitesse | Bestiole : sa vitesse. Exploirateur : celle d'un gaminot. |

Les vitesses vont de la tortue (1) au guépard (6).

**Cartes.** Le livre compte en cases. Dans les réglages de chaque carte, mettez l'échelle à `1` et l'unité à `sq`.

**Images.** Les réglages du système (groupe « Interface ») permettent de choisir l'image affichée dans les listes et dans le suivi de combat : icône, image ou jeton.

## Limites actuelles

- Le repos (récupération de points de vie) et l'état « foutu » d'un objet usé se gèrent à la main.
- Aucun contenu du jeu n'est fourni.

## Crédits et licences

*Exploirateurs de bruines* est © L'Averse. Concept, textes et publication : Vivien Féasson. Conception artistique, illustrations et mise en page : Willy Cabourdin.

Ce système est un projet de la communauté. Encounter+, son nom et ses ressources visuelles restent la propriété de leurs propriétaires respectifs.

Polices : [Merriweather](fonts/OFL-Merriweather.txt), [Oswald](fonts/OFL-Oswald.txt) et [Covered By Your Grace](fonts/OFL-Covered%20By%20Your%20Grace.txt), sous licence SIL Open Font License.

Système réalisé par Brioche Masquée.

## In short

Encounter+ game system for *Exploirateurs de bruines*, a French post-apocalyptic fantasy RPG by Vivien Féasson (L'Averse). It provides a character sheet, critters, items, classes, powers, rules, a theme and system settings, in French and English. It does not include the game's content. Download `edb.system` from the [latest release](https://github.com/BriocheMasquee/edb/releases/latest) and open it with Encounter+ 5.1.0 or later.



![SOTDL Game System Encounter+](images/sotdl_banner.png)

# Shadow of the Demon Lord (SotDL)
 Shadow of the Demon Lord game system for EncounterPlus.

### Credits
Courtesy of Robert J. Scwhalb.
This game system doesn't include game elements.

_Shadow of the Demon Lord is ©2015 Schwalb Entertainment, LLC. All rights reserved. Shadow of the Demon Lord, Schwalb Entertainment, and their associated logos are trademarks of Schwalb Entertainment, LLC._


<div align="center">
  <img src="branding/mpx-icon-256.png" alt="MPX logo" width="160">

  # Système *Exploirateurs de bruines* pour Encounter+

  A VSCode extension for building [EncounterPlus](https://github.com/encounterplus/encounterplus) modules from Markdown and JSON sources.

  ![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-blue)
  ![Status: beta](https://img.shields.io/badge/status-beta-orange)
  [![VS Code Marketplace](https://img.shields.io/badge/VS%20Code%20Marketplace-v1.3.0-blue)](https://marketplace.visualstudio.com/items?itemName=BriocheMasquee.module-packer-extended)
</div>

> [!WARNING]
> **MPX is currently in beta.** Keep an independent backup of your source project and of your EncounterPlus data — test built modules on a copy first. Between beta versions, project files and settings are **not guaranteed to stay backward compatible**; check the changelog before upgrading an existing project.
>
> **MP project conversion is experimental.** It works — module metadata, pages, groups, images, maps/encounters, and inline ` ```item `/` ```spell `/` ```monster ` blocks all convert — but a converted inline block currently renders through MPX's *current* 5.5e Compendium block style, not a reproduction of the original legacy dnd5e ruleset appearance. Keep your original MP project as the source of truth until you've checked the converted result.

<div align="center">

📖 **[Documentation (Wiki)](https://github.com/BriocheMasquee/module-packer-extended/wiki)**

</div>

## Table of contents

- [Origin](#origin)
- [What MPX is](#what-mpx-is)
- [Documentation and current state](#documentation-and-current-state)
- [License and credits](#license-and-credits)

## Origin

MPX is a personal project that I am making available to the community. It is neither official nor affiliated with EncounterPlus, and it is not intended to replace the original project.

MPX is a community fork of [EncounterPlus Module Packer](https://github.com/encounterplus/module-packer), distributed under the [CC0 1.0 Universal license](https://github.com/encounterplus/module-packer/blob/master/LICENSE); its latest release (`1.0.63`) and latest commit were published on March 3, 2024.

It started from personal needs the original project didn't cover: French/English localization, compatibility with EncounterPlus's redesigned **V5** module format, and a more workable way to manage theme CSS across projects. MPX reworks the original's approach to address those, built as a VSCode extension.

## What MPX is

MPX is a tool for **module content authors**, complementary to [EncounterPlus](https://itunes.apple.com/us/app/encounter+/id1170693487?ls=1&mt=8) itself (which runs the module at the table) and to a rules-reference tool like EncounterLog — it's what you use beforehand, to write and package the content.

Install it from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=BriocheMasquee.module-packer-extended), or search for "Module Packer Extended" in VSCode's Extensions view.

## Documentation and current state

Full documentation — every feature, field, and setting — lives on the **[Wiki](https://github.com/BriocheMasquee/module-packer-extended/wiki)** (English; a French version may follow).

Tested against real EncounterPlus imports. What MPX adds on top of the original Module Packer:

- A Compendium: items, spells, roll tables, and monsters — as standalone files or authored inline in a page.
- A Markdown preview updated to match the current D&D 5.5e visual style, mirroring the real EncounterPlus rendering (theme CSS, compendium cards, stat blocks).
- English and French content, with unit conversion (imperial/metric) and per-project label overrides.
- A selectable project theme (CSS).
- Improved snippets and YAML autocompletion.
- Improved roll table auto-detection.
- Advanced Markdown rendering customization options, via project settings.
- Conversion from a legacy Module Packer V4 project folder into a new MPX project.

Not supported (yet):

- Conversion from an already-built legacy `.module`/`.mpmodule` file — only a V4 project folder (`Module.yaml` + Markdown) converts today.
- PDF export (available in the original Module Packer).
- Opening an already-built `.module` file for editing.

## License and credits

[CC0-1.0](LICENSE.md) for this project's own code and content; bundled theme fonts and the localization catalogs are third-party work under their own terms — see [THIRD-PARTY-LICENSES.md](THIRD-PARTY-LICENSES.md).

Module Packer is the original work of its creator and contributors. EncounterPlus, its name, and its visual resources remain the property of their respective owners.
