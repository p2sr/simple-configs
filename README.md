# simple-configs

A simple set of configuration files for Portal 2 speedrunning with SAR.

## Usage

Place all these config files within the `Portal 2/portal2/cfg` directory, as is;
they should automatically be run by the game as necessary. Ensure [SAR] is
installed.

[SAR]: https://github.com/p2sr/SourceAutoRecord

## Binds

You *must* set the following binds for the configs to function
correctly:
- `bind mwheelup +scrollup`

You can bind the following commands:
- `funneling_toggle` - toggle portal funneling
- `fullbright_toggle` - toggle fullbright
- `sensitivity_toggle` - toggle low sensitivity
- `useswap_toggle` - toggle scrollup being use
- `+supershoot` - hold to enable scrollup being shoot
- `30fps_toggle` - toggle 30fps mode (for coop button glitches and certain SLA tricks)
- `contimes_toggle` - toggle seeing contimes text (e.g. for double dialogue skip)
- `dialogue_toggle` - toggle the dialogue from glados, wheatley, and the announcer
- `do_load <save name>` - load a save only if in non-CM singleplayer
- `do_reset` - reset your run

## Customisation svars

- `no_dialogue_toasts`  - when 1, disable dialogue fade toasts
- `no_auto_category`    - when 1, disable automatic speedrun category selection

## Extra configuration

Rather than modifying this autoexec.cfg directly, it is recommended you
put any "personal" configuration (e.g. setting svars, performing HUD
customisation) in `extra.cfg`. This file will be execed once by the
autoexec.
