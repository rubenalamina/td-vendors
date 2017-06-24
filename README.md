# The Division: Weekly Vendor Reset

## Conventions

### Item types
Used in the JSON files.
These fields and values are fixed, don't change them.
* Gear: gear
* Weapons: weapon
* Gear Mods: gear-mod
* Weapon Mods: weapon-mod

### Item rarity
Used in the JSON files to differentiate HE gear and gear set pieces.
You only need to change it if you're working with the **Special Equipment Vendor**.
* High End: header-he
* Gear Sets: header-gs

### Item names
* Capitalize every first letter: **Steadfast Holster**, **Sentry's Knee Pads**.
* Use talent+slot. Examples: **Tenacious Mask, Sturdy Holster, Vigorous Chest**.
* Use full name of the slot. Examples: use **Knee Pads for Pads**, **Backpack for Pack**.
* For gear sets use simplified set name+slot. Examples: **Striker's Mask, Predator's Holster, Nomad Chest**.
* Avoid specific names like **Gunslinger**, **Spec-ops**.
* For mods, just use the simplified name. Examples: **Stamina Mod, Electronics Mod, Performance Mod**.

### Attributes
* Use a hyphen "-" for the fixed main stats on gear items instead of the number 205.
* Use a hyphen "-" if the item doesn't have major, minor attributes, a native weapon bonus or lacks a talent. Don't delete the fields.
* The same for performance mods that don't have a main stat.

Examples for these are Pistols, which don't have a native bonus and just two talents. Holsters and gloves, which doesn't have minor attributes, and so on.

### Abbreviations
* Main stats on mods -> **STA, FA, ELE**

### Item prices
* Regular credits: $
* Phoenix credits: PxC
* DZ funds: DZ
