# Breathless-R.E

A C++ port of **Breathless** (Fields of Vision, 1995) for AGA Amigas with a
68030 or better, plus **DEAD AIR**, a new campaign on the same engine.

This repository hosts the releases only. Downloads are under
[Releases](../../releases).

## What's in a release

- **The port of the original game.**
  and you get the 1995 game: original menus, level codes,
  credits and terminals with the shop.
- **DEAD AIR DEMO**: the first two worlds of DEAD AIR, a new campaign with
  new weapons, enemies, levels and rules.

## Requirements

- AGA Amiga (A1200, A4000, CD32 with expansion) with a 68030 or better
- The original Breathless, already installed: the port reads its data
  files, which are **not** included

## Install

Copy the `BreathlessRE` executable and the `mods` folder into the
directory of the original game, then start `BreathlessRE` from there.
Full instructions are in `readme.txt` inside the archive.

**PiStorm / 68060:** start with `--c2p cpu` for a much
higher frame rate.

## What's different from the original

- Faster renderer (Kalms c2p) with no frame cap
- Precise walls renderer (no uv-coord wobbling) [OPTION]
- Faster floors rendering with uv-subsampling [OPTION]
- A better automap [OPTION]
- Your weapon drawn in hand with the hardware sprites
- Mouse look and redefinable keys
- New menus with saved settings, in-game menu on Esc
- Hints on the monitor
- Mod support: campaigns go in the `mods` folder and are picked from the
  MODS menu
- Each mod has its own memory budget defined per level

## Feedback

Bug reports and impressions are welcome in [Issues](../../issues) or in
the thread on English Amiga Board: [https://eab.abime.net/showthread.php?t=124207]

When reporting a performance problem, press F8 in game and attach a photo
of the screen (frame counter and frame profile), together with your
machine (CPU, accelerator, memory).

## Credits

Breathless © 1995 Fields of Vision. Breathless is their work; this project
is an unofficial port and is not affiliated with them.

Port and DEAD AIR by Daniele Vacca (dv-hack).
