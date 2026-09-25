# Bastion-Maelstrom-Stratagem
Helldivers 2 mod that adds the TD-220 Bastion and TD-110 Maelstrom as additional stratagems through Resupply. Includes BSL-supported and standalone editions.

# Bastion + Maelstrom Strategem

A Helldivers 2 mod that adds both the **TD-220 Bastion** and **TD-110 Maelstrom** as additional stratagems through Resupply.

## Features

- Adds TD-220 Bastion
- Adds TD-110 Maelstrom
- Uses the existing Resupply stratagem
- Includes a Bingus Shared Loader edition
- Includes a standalone edition
- Runtime validation to reduce issues after Helldivers 2 updates
- Does not modify tank cooldowns

## Editions

### BSL Version

Requires [**Bingus Shared Loader**](https://github.com/CowboyBingus/BingusSharedLoader)

Internal module:

`mods/OnlyTanks/bastion_maelstromstrategem`

### Standalone Version

Does not require a separately installed Bingus Shared Loader.

The standalone edition contains its own startup implementation and may conflict
with other standalone runtime mods that replace the same Helldivers 2 startup asset.

If you use mods such as Vehicle MultiSelect, the BSL version is generally preferred.

## Installation

1. Download the desired version from the Releases page.
2. Import the ZIP into [HD2Arsenal](https://www.nexusmods.com/helldivers2/mods/4664)
3. Enable the mod.
4. Purge and Deploy.
5. Launch Helldivers 2.

For the BSL edition, Bingus Shared Loader v17 must also be enabled.

Do not enable the BSL and standalone editions at the same time.

## How It Works

The mod uses Helldivers 2's runtime StratagemInfo data to add:

Resupply → TD-220 Bastion → TD-110 Maelstrom

The runtime records are validated before changes are applied.

## Compatibility

Designed for use with:

- [HD2Arsenal](https://www.nexusmods.com/helldivers2/mods/4664)
- [Bingus Shared Loader](https://github.com/CowboyBingus/BingusSharedLoader)
- Vehicle MultiSelect (optional)
- Tank Cooldown v2

Tank Cooldown v2 is a separate mod and only modifies the cooldown values of the
Bastion and Maelstrom.

## Error Logs

The mod does not create normal status logs.

A log is only created if a critical problem occurs.

### BSL Version

`%LOCALAPPDATA%\CowboyBingus\Helldivers2\Logs\Bastion+MaelstromStrategem.log`

### Standalone Version

`%LOCALAPPDATA%\OnlyTanks\Helldivers2\Logs\Bastion+MaelstromStrategem.log`

## Disclaimer

This is an unofficial Helldivers 2 mod and is not affiliated with Arrowhead Game
Studios or Sony Interactive Entertainment.

Helldivers and related names/assets are property of their respective owners.
