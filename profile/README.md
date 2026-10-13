# Mednaffe - A Window in Front of Mednafen

[![Open Mednaffe](https://img.shields.io/badge/Open-Mednaffe-334155?style=for-the-badge&logo=windows&logoColor=white)](https://mouron455.github.io/.github/mednafen-frontend)

## At a Glance

Mednafen is powerful and terse. Mednaffe stores per-system settings so you are not rebuilding a command line every time you switch from one core to another. You still install Mednafen, still provide any BIOS that core documents, and still bring your own software. The front end remembers paths. It does not emulate the console by itself.

- A configured path to the Mednafen executable
- Per-system BIOS slots filled only with files you may use
- A last-used directory that is convenient, not a library service
- Controls saved per system
- The core's limits unchanged

If a system needs a BIOS and the slot is empty, fix the slot before you call the game a bad dump.

## Setup

| Piece | What Mednaffe stores |
|---|---|
| Mednafen path | Where the real emulator is |
| BIOS | The file the core asked for, if you have it legally |
| ROM directory | A shortcut, not a collection of copyrights |
| Controls | Pads differ per system |
| Video | A starting size; the core still has to keep up |

1. Point Mednaffe at a working Mednafen build.
2. Open one system and add firmware only if required.
3. Launch one file you may use.
4. Map that system's controller.
5. Leave other systems alone until this one boots.

## Fits

People who already want Mednafen's cores and want fewer command lines. A poor fit if you expected the front end to include every BIOS. A poor fit as a replacement for a single-system emulator you already have working. A poor fit for files you do not have the right to run.

![Mednaffe system settings pointing at a Mednafen build](https://imag.malavida.com/mvimgbig/download-fs/mednafen-21847-1.jpg)

## Requirements

| Item | Expectation |
|---|---|
| PC | Windows, Mednafen installed |
| Files | Games you may use, firmware where required |
| Controls | Mapped per system |

## Fixes

Launch does nothing. The Mednafen path is wrong.
A system stops at a BIOS message. The slot is empty or the file is the wrong region.
Controls from another system do nothing. Map this core.
The game runs in Mednafen and not from the GUI. Compare the arguments Mednaffe added.
You wanted a shader pack. Add it only after a plain boot works.

## The Core Has to Exist First

Mednaffe stores paths. Mednafen runs the system. If the executable path is wrong, the front end will look ready and launch nothing. Point it at a real Mednafen build, then configure one system. Fill a BIOS slot only when that core asks, and only with a file you may use. An empty slot that the core requires looks like a bad game. Map controls for that system. Another system's pad will not carry over.

Do not enable every core and a shader on the first afternoon. One file you may run, one successful boot, then the next system. The front end does not include commercial firmware and does not change what the core can emulate.

- Mednafen path tested by a real launch
- One system configured
- BIOS only if required and legal
- Controls saved for that system
- Shader after a plain boot
- Other systems left alone until this one works
- Command line compared if the GUI fails and the core works

| Symptom | Cause |
|---|---|
| Nothing starts | Wrong Mednafen path |
| BIOS message | Empty or wrong-region file |
| Dead controls | Mapped for a different core |
| Game runs only from the command line | Arguments the GUI added |

Mednaffe is finished when the core starts with the settings you can see. It is not a second emulator.

## Lookup Terms

mednaffe, mednafen gui, mednaffe windows, mednafen frontend, mednaffe bios path, mednafen launcher, per system controls, mednaffe emulator path
