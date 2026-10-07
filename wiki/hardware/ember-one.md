# Ember One

> Sources: 256 Foundation (projects page), collected 2026-10-07; 256 Foundation (newsroom: Ember One first grant), collected 2026-10-07; 256 Foundation (grants page), collected 2026-10-07
> Raw: [256foundation.org projects](../../raw/foundation/256foundation-org-projects.md); [Ember One first grant](../../raw/foundation/256foundation-org-newsroom-ember-one-first-grant.md); [grants page](../../raw/foundation/256foundation-org-grants.md)
> Updated: 2026-10-07

## Overview

Ember One is the 256 Foundation's open-source reference design for a Bitcoin mining hash board, the board that holds a series of ASIC chips and does the hashing. It was the foundation's first grant. It is a reference design, not a product: the foundation does not manufacture or sell it.

## The gap it fills

ASIC makers do not sell their chips to builders. They put them inside complete machines and publish no datasheets, documentation or repair manuals. In other chip industries, manufacturers publish reference designs so third parties can build on their silicon. Mining never opened up that way. To build on competitive chips today, you buy a full machine, desolder the chips, and reverse-engineer how to talk to them.

## What it is

- Starts with the Bitmain BM1362, the chip from the S19 J-Pro.
- The plan in the first grant: a modular hash board using 12 chips, drawing roughly 100 watts and producing two to four terahash.
- USB-C data interface and integrated temperature sensors.
- Built to work natively with [Libre Board](libre-board.md) and [Mujina](../mujina/mujina-firmware.md).
- Open PCB design files, bill of materials, and firmware interface spec. GPL-licensed.

The intention is to build further Ember One versions as reference designs for chips from other vendors.

## How it differs from Bitaxe

Bitaxe puts the hash board and control board on one small PCB with a single chip and an ESP32 microcontroller. Ember One is the next step: a multi-chip board with a string of ASICs in series, the way larger industrial machines are built. Tuning voltages and frequencies for a string of chips is a different problem from a single chip.

## People and funding

Skot is the core architect and lead maintainer. He also instigated [Bitaxe](../ecosystem/bitaxe-and-osmu.md). The first grant funds six months of engineering under the Core Projects Program, starting November 2024.

## See Also

- [Libre Board](libre-board.md)
- [Grants and Funding](../foundation/grants-and-funding.md)
- [Bitaxe and Open Source Miners United](../ecosystem/bitaxe-and-osmu.md)
