# Template World Moto Moto dnd5e

![Latest Release Download Count](https://img.shields.io/github/downloads/p4535992/foundryvtt-template-world-moto-moto-dnd5e/latest/module.zip?color=2b82fc&label=DOWNLOADS&style=for-the-badge)

[![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Ftemplate-world-moto-moto-dnd5e&colorB=006400&style=for-the-badge)](https://forge-vtt.com/bazaar#package=template-world-moto-moto-dnd5e)

![Foundry Core Compatible Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2Fp4535992%2Ftemplate-world-moto-moto-dnd5e%2Fmaster%2Fworld.json&label=Foundry%20Version&query=$.compatibility.verified&colorB=orange&style=for-the-badge)

![Latest Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2Fp4535992%2Ftemplate-world-moto-moto-dnd5e%2Fmaster%%2Fworld.json&label=Latest%20Release&prefix=v&query=$.version&colorB=red&style=for-the-badge)

[![Foundry Hub Endorsements](https://img.shields.io/endpoint?logoColor=white&url=https%3A%2F%2Fwww.foundryvtt-hub.com%2Fwp-json%2Fhubapi%2Fv1%2Fpackage%2Ftemplate-world-moto-moto-dnd5e%2Fshield%2Fendorsements&style=for-the-badge)](https://www.foundryvtt-hub.com/package/template-world-moto-moto-dnd5e/)

![GitHub all releases](https://img.shields.io/github/downloads/p4535992/foundryvtt-template-world-moto-moto-dnd5e/total?style=for-the-badge)

[![Translation status](https://weblate.foundryvtt-hub.com/widgets/template-world-moto-moto-dnd5e/-/287x66-black.png)](https://weblate.foundryvtt-hub.com/engage/template-world-moto-moto-dnd5e/)

## Do not forget to checkout the [World Smiths Discord community](https://discord.gg/2YCFD8fxG7) if you are interested in doing your own world.

This world is an empty starting world with the configurations of modules and settings used by _Moto Moto_.

Who is Moto Moto ? Moto Moto is a great person very active in the discord server who in his experience has prepared and configured a number of modules for his Dnd5e campaigns.

With his permission I created this "empty" world with all settings and modules ready to used with any third party adventure .

The purpose is to help the "I want to be a master" without driving them crazy with the initial configurations.

## MidQOL advertisement by Moto Moto

### Midi does not work with:

- Ready Set Roll
- Better Rolls for 5e
- Roll Groups
- Fast Rolling by Default
- Fast Rolls or Quick Rolls
- Dice Tooltips
- Taragnor's Gm Paranoia
- WIRE(Whistler's Item Rolls Extended)
- Minimal Roll Enhancements
- Retroactive Advantage/Disadvantage
- Max Crit
- Multiattack 5e

### Midi has Concentration conflicts with these modules:

- Concentration Notifier Module
- Combat Utility Belt Concentrator

### The following modules have template settings that step on midi:

- Spell Template Manager

### Midi Notes:

- Advanced Spell Effects module is in beta in v10 and often the culprit of things...
- Midi requires Item Macro to have its "Character sheet hooks" feature set to unchecked in order for on use macros to work right.
- When editing owned items(items on actors) active effects beware of duplicating active effects that interfere.  Always check the actors effect tab for rogue ae's.
- If you are on dnd5e 2.1.x update to 2.1.5 and you can run the newest midi/dae/dfreds ce 
- Dfreds CE 4.0 requires midi 32+ and dae 22+.
- Midi now requires sight to be setup on all monsters or the players will get unseen attacker advantage.

## Suggested module setting for a Midi Better Behaviour:

### MidiQOL

- Select either "always" or "always ignore defeated" in the "Autotarget on template draw" setting in MidiQOL workflows and turn on autotargeting in Walled Templates.
- Midi QoL config > Workflow > Apply Convenient Effects — select Apply Item effects, if absent apply CE.

### DFreds Convenient Effects 

- Modify Status Effects — select either Replace (preferred) or Add.

### Item Macro 

- Override default macro execution — uncheck this.
- Character Sheet Hook — uncheck this.
- (If installed) Token Action HUD > Item-Macro: item macro, original item, or both — select Show the original item. (Note this is a user setting, so ensure that each user does this or use a module such as Force Client Settings to guarantee it.)

### Automated Animations

File da importare per i vari sistemi

https://discord.com/channels/772596237605011466/9174248893407846

## Adventure Details

**System:** D&D 5e

**Starting Level:** Any

**Length:** Short multi-session (10-12 hours)

**Language:** English


Short description and synopsis

|  |  |  |
| ---- | ---- | ---- |
| ![Pictures & screenshots 1]() | ![Pictures & screenshots 2]() | ![Pictures & screenshots 3]() |


## Installation Wold

It's always easiest to install worlds from the in game add-on browser.

To install this world manually:
1.  Inside the Foundry "Configuration and Setup" screen, click "Worlds"
2.  Click "Install World"
3.  In the "Manifest URL" field, paste the following url:
`https://raw.githubusercontent.com/p4535992/foudnryvtt-template-world-moto-moto-dnd5e/master/world.json`
4.  Click 'Install' and wait for installation to complete

## Installation Module

It's always easiest to install modules from the in game add-on browser.

To install this module manually:
1.  Inside the Foundry "Configuration and Setup" screen, click "Add-on Modules"
2.  Click "Install Module"
3.  In the "Manifest URL" field, paste the following url:
`https://raw.githubusercontent.com/p4535992/foudnryvtt-template-world-moto-moto-dnd5e/master/module.json`
4.  Click 'Install' and wait for installation to complete
5.  Don't forget to enable the module in game using the "Manage Module" button

## Feedback and Contribution

Want to suggest changes or improvements? Notify of errors or bugs?
Want to contribute to this world or similar projects?

[Join the World Smiths Discord community](`put a unique discord invite link here (see https://github.com/World-Smiths/documentation/blob/main/wiki/discord-invite-link.md)`) or open any issues, bugs, or feature requests are always welcome to be reported directly to the [Issue Tracker](https://github.com/p4535992/foundryvtt-template-world-moto-moto-dnd5e/issues ), or using the [Bug Reporter Module](https://foundryvtt.com/packages/bug-reporter/).

## Dependencies

- This template support and use the [Scene Packer](https://foundryvtt.com/packages/scene-packer) library module


## Credits

**Author:**

**Editor:**

**Art Direction:**

**Layout Artist:**

**Playtesters:**

**Cover Art:**

**Sensitivity Reader:**

**Cartography:**

**Interior Art:**

## [Changelog](./changelog.md)

## Issues

Any issues, bugs, or feature requests are always welcome to be reported directly to the [Issue Tracker](https://github.com/p4535992/foundryvtt-template-world-moto-moto-dnd5e/issues ), or using the [Bug Reporter Module](https://foundryvtt.com/packages/bug-reporter/).

## License

Copyright © 2023 XXX. All Rights Reserved.

This package is under the [Foundry Virtual Tabletop Limited License Agreement for module development](https://foundryvtt.com/article/license/).

The World Smiths logo is under the license [here](https://github.com/World-Smiths/documentation#license).
The software component of this world is distributed under the [MIT](./LICENSE) license.
