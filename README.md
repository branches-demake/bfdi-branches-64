# BFDI: Branches Commodore 64 port
The unofficial Commodore 64 port of BFDI: Branches [original by Team Branches]

## Disclaimer
This project is unofficial and is not affiliated by Team Branches, jacknjellify or Commodore.

## Why the C64 port?
The Commodore 64 port of BFDI: Branches is my dream port of the game and I am wondering what it feels like. I like experimenting with 8-bit computers like the Commodore 64, and the Commander X16. I absolutely hate how expensive gaming computers are, especially the RAM and SSDs, because of the AI companies, and I refuse to use 9th gen gaming consoles.

# Criteria for the BFDI Branches C64 port
## Programming Language
I would want this port to be written in 6502 assembly or C for the game code because writing the entire game in BASIC could run painfully slow due to being an interpreter.

## Hardware
I would prefer at least to run on an original C64 without any RAM Expansion Units or CPU accelerators like the Turbo Chameleon and the CMD SuperCPU, but if you find RAM limitations hindering the development, you can use REUs, a SuperCPU, or any modern RAM expander. Running on the VICE emulator is recommended for testing. The brand new Commodore 64 Ultimate as well as the Commodore 77 [Cyberpunk 2077 C64] or the Mega65 is highly encouraged.

I would also prefer to support fast load cartridges because loading from or saving to floppy disk on the 1541 disk drive is very slow due to a hardware bug on the C64 as well as the VIC-20 regarding IEC ports in contrast of IEEE-488 ports on the Commodore PET.

Multiple disk drives support can be useful for saving and loading levels, as well as downloading online levels and software updates.

Speaking of downloading levels and updates, I would also have support for modems or networking cartridges to connect to the internet.

Datasettes (data cassette tapes) are alright.

SD2IEC and USB support are recommended.

I would prefer to be running in NTSC, but you can optimize the game for PAL systems.

I would also have the Amiga CD32 controller support as well as TexElec's SNES controller adapter as used in PETSCII Robots.

## Features
I would prefer to have an original story mode (not finished yet), as well as additional side stories, speedrun mode, level editor and online features as the original, but nix the outbound online features like level uploads, completion submissions and online accounts since it's an unofficial port.

## Integrity
I prefer to avoid LLM model coding, known as "vibe-coding," as it is unreliable, unethical, and hated by the community.

**ALL CODE MUST BE WRITTEN IN A TRADITIONAL WAY. NO EXCEPTIONS.**

Any vibe-coded pull requests will be declined without question. Habitual vibe-coding will result in a permanent ban from contributing to the project.

Also, assets must not be AI generated.

## Commodore 128
The Commodore 128 has a C64 mode which makes the C128 into an almost fully compatible C64.

Caveats in C64 mode on the 128: 
- Slower C64 1541 disk speed compared to much faster C128 burst mode
- 64k RAM (C128 has 128k RAM), after all it's a Commodore **64**
- Extra keys disabled
- No Z80 access
- No RGBi output
- BASIC 2.0 (128 has BASIC 7.0), don't worry we won't be using BASIC in the game code
- 1MHz clock speed (128 has 2MHz)
- No 80-column display

But there's a way to expose the C128 components in C64 mode just like how Sonic The Hedgehog C64 port detects whether it's a C128 or not and exploits the use of C128 components, or better yet, make a C128 native port of BFDI: Branches, and even a Commander X16 port.
