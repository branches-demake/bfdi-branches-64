# BFDI: Branches Commodore 64 port
The unofficial Commodore 64 port of BFDI: Branches [original by Team Branches]

## Disclaimer
This project is unofficial and is not affiliated by Team Branches, jacknjellify or Commodore.

## Why the C64 port?
The Commodore 64 port of BFDI: Branches is my dream port of the game and I am wondering what it feels like.

# Criteria for the BFDI Branches C64 port
## Programming Language
I would want this port to be written in 6502 assembly for the game code because writing the entire game in BASIC could run painfully slow due to being an interpreter.

## Hardware
I would prefer at least to run on an original C64 without any RAM Expansion Units or CPU accelerators like the Turbo Chameleon and the SuperCPU, but if you find RAM limitations hindering the development, you can use REUs, a SuperCPU, or any modern RAM expansion unit. Running on the VICE emulator is recommended for testing. The brand new Commodore 64 Ultimate as well as the Commodore 77 [Cyberpunk 2077 C64] is highly encouraged.
I would also prefer to support fast load cartridges because loading from or saving to floppy disk on the 1541 disk drive is very slow due to a hardware bug on the C64 as well as the VIC-20 regarding IEC ports in contrast of IEEE-488 ports on the Commodore PET.
Multiple disk drives support can be useful for saving and loading levels, as well as downloading online levels and software updates.
Datasettes (data cassette tapes) are alright.
SD2IEC support.
Speaking of downloading levels and updates, I would also have support for modems or networking cartridges to connect to the internet.

## Features
I would prefer to have an original story mode (not finished yet), as well as additional side stories, speedrun mode, level editor and online features as the original, but nix the outbound online features like level uploads, completion submissions and online accounts since it's an unofficial port.

## Integrity
I prefer to avoid LLM model coding, known as "vibe-coding," as it is unreliable, unethical, and hated by the community.
**ALL CODE MUST BE WRITTEN BY HAND. NO EXCEPTIONS.**
Any vibe-coded pull requests will be declined without question.
Also, assets must not be AI generated.

## Commodore 128
The Commodore 128 has a C64 mode which makes the C128 into an almost fully compatible C64 (slow C64 1541 disk speed, 64k RAM, extra keys disabled, no Z80 access, no RGBi output, BASIC 2.0, 1MHz clock speed and no 80-column display), but there's a way to expose the C128 components just like how Sonic The Hedgehog C64 port used the C128's CPU accelerator.
