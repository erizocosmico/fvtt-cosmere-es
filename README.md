# fvtt-cosmere-es

Unofficial spanish translation of the [Cosmere RPG](https://github.com/the-metalworks/cosmere-rpg) system for FoundryVTT.

### Project status

This is a work in progress. Feel free to contribute. This first version translates the system's user interface strings; compendium content (via Babele) is not translated yet.

### Install

For now, manually using the following link:

```
https://raw.githubusercontent.com/erizocosmico/fvtt-cosmere-es/main/module.json
```

Then enable the module in Foundry and set your client language to *Español*.

### How to contribute

The keys in `lang/es.json` that start with `_` are untranslated. When you translate its content, remove the leading `_`.

### Update translation

To update the spanish translation you can do the following:

Download the latest `en.json` language file from the Cosmere RPG system.

```
npm run update
```

Sync the keys in the `en.json` file with `es.json`.

```
npm run sync
```

## Disclaimer

The **Cosmere Roleplaying Game** is published by Dragonsteel Entertainment and Brotherwise Games. All original content, mechanics, and intellectual property related to the Cosmere and the Cosmere RPG are © their respective owners.

This project is intended for personal or non-commercial use. All rights to the Cosmere RPG's original materials remain with their respective owners.

This project is an unofficial fan creation and is not affiliated with or endorsed by Dragonsteel Entertainment or Brotherwise Games.
