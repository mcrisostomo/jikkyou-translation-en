# Jikkyou World Soccer 2 English Translation

This repository contains the development work for an English translation of **Jikkyou World Soccer 2 – Fighting Eleven** for the Super Nintendo Entertainment System (SNES).

## Project status

Early development. Research, reverse engineering, translation, and tooling are not yet complete. No finished translation or functional distribution patch is included at this stage.

## Project goals

The project aims to:

- Translate the game's Japanese text into English.
- Investigate and document text, character encoding, fonts, graphics, and ROM structure.
- Develop reusable Node.js/JavaScript tools as the technical findings are validated.
- Produce translation patches that can be applied to a compatible, original Japanese ROM.
- Preserve compatibility with original SNES hardware where technically feasible.
- Keep the tooling reusable for future language forks after the English version is complete.

## Game and platform

- **Title:** Jikkyou World Soccer 2 – Fighting Eleven
- **Platform:** Super Nintendo Entertainment System (SNES)
- **Source language:** Japanese
- **Target language:** English

## Repository structure

```text
assets/fonts/       Font and related visual research assets
docs/               Reverse-engineering and project documentation
scripts/            Node.js/JavaScript development tools
translations/en/    English translation source files
patches/en/         English patch-generation output
```

Empty directories are retained with `.gitkeep` files until validated project assets or tools are added.

## Technical direction

Tools will be implemented in Node.js/JavaScript. No extraction, insertion, graphics, or patching behavior is assumed until it has been investigated and documented. Technical notes should record relevant ROM addresses, formats, constraints, validation steps, and hardware-compatibility considerations.

## Distribution policy

This project will distribute translation patches and project tools only. Original ROM images, copyrighted game assets, and other material that would substitute for the original game must not be committed or distributed. A patch must be applied to a compatible, legally obtained Japanese ROM by the user.

## Unofficial project notice

This is an unofficial fan translation project. It is not affiliated with or endorsed by the game's developers, publishers, Nintendo, or any related rights holders. All rights to the original game and its assets remain with their respective owners.

## Contributing

Contributors should read the documentation in `docs/` before changing formats or assumptions. Keep research reproducible, document discoveries in English, avoid committing ROM images, and ensure that generated artifacts can be recreated from source. Translation changes should preserve the established terminology and encoding rules once those rules have been validated.
