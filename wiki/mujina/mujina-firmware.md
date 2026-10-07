# Mujina Firmware

> Sources: 256 Foundation (projects page), collected 2026-10-07; Mujina project (mujina.org status page, current as of July 2026), collected 2026-10-07; Mujina project (mujina.org why-mujina page), collected 2026-10-07; 256 Foundation (newsroom: HRF renews support), collected 2026-10-07
> Raw: [256foundation.org projects](../../raw/foundation/256foundation-org-projects.md); [mujina.org status](../../raw/mujina/mujina-org-explanation-status.md); [mujina.org why Mujina](../../raw/mujina/mujina-org-explanation-why-mujina.md); [HRF renews support](../../raw/foundation/256foundation-org-newsroom-hrf-renews-support.md)
> Updated: 2026-10-07

## Overview

Mujina is the 256 Foundation's open-source Bitcoin mining firmware, described on the foundation's site as "The Linux kernel project of Bitcoin mining firmware": one open codebase for every vendor's hardware. It is licensed GPL-3.0-or-later and charges no dev fee. Its own status page describes it as young software with a working core. It is ready for developers and tinkerers, and not yet for home miners with S19-class machines or for mining operations.

## The gap it fills

Miners choose between two kinds of closed firmware. The manufacturer's firmware does only what the manufacturer decided. Third-party firmware adds tuning and features but charges a dev fee, a cut of hashrate skimmed by the firmware itself, and it can stop mining when the cut does not get through. Either way the operator cannot read or change the software.

## The Linux analogy

Servers once shipped with closed vendor operating systems. Linux replaced them because a shared kernel let each hardware maker support its own devices. Mujina applies the same model. The scheduler, pool protocols, API and monitoring are written once, and each hash board adds a driver, usually written by people who own that hardware.

## What works today

Per the status page, current as of July 2026:

- `mujina-minerd` is a complete miner. It connects to a Stratum v1 pool, negotiates version rolling, schedules jobs across hash threads and submits shares.
- It drives real hardware, using the single-chip Bitaxe Gamma as a developer hash board, with temperature and hashrate monitoring and USB hotplug.
- A CPU-based virtual hash board lets the whole miner run on a Linux machine with no mining hardware.
- A REST API reports live state, can pause and resume mining, and serves its own Swagger UI.
- A published container image runs the daemon.

## What does not exist yet

- No frequency, voltage or power controls, and no autotuning.
- No measured or published J/TH figures.
- No power targets, board scheduling or home automation integration.
- One pool at a time, and only over Stratum v1.
- No prebuilt images. The goal is Mujina OS, complete operating system images for control boards.

## Feature claims that disagree

The foundation's projects page lists as key features: per-chip power targeting and watt budgets, Stratum V1/V2 with DATUM compatibility, drivers for Antminer, Whatsminer and Avalon, and a web dashboard, REST API and CLI.

> **Status: Disputed**
> The mujina.org status page (current as of July 2026) says there are no power controls, that the daemon works only over Stratum v1, and that S19-class support is prototype work in a fork. The 256foundation.org projects page lists per-chip power targeting, Stratum V1/V2 and Antminer, Whatsminer and Avalon drivers as key features. The projects page may describe the target design and the status page the shipped state; neither source says so explicitly.

## Where the work is going

- Making the prototype S19j/S19k Pro fork product-grade and merging it into mainline.
- EmberOne/00 bring-up in mainline, for the foundation's [Ember One](../hardware/ember-one.md) hash board.
- Intel BZM2 drivers, in progress on a contributor branch.

Hardware support often lives in forks first. Bringing up a board involves experiments that may brick hardware and fast iteration that mainline review would slow.

## First product

Mujina is being developed into RY3T's Nova, a home mining product in development that runs surplus solar power straight to hashrate.

## People and community

Ryan Kuester is the core architect and lead maintainer. Biweekly developer calls are ongoing.

## See Also

- [Libre Board](../hardware/libre-board.md)
- [Ember One](../hardware/ember-one.md)
- [Hydrapool](../hydrapool/hydrapool.md)
