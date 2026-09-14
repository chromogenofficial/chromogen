# Chromogen

**Develop your photos like film.** Chromogen is a standalone film-emulation photo editor for Windows and macOS.

Website: https://chromogen.app · What's new: https://chromogen.app/changelog · Contact: halide@chromogen.app

This repository carries the release downloads.

## What it is

Instead of dropping a preset on a finished JPEG, Chromogen develops the photo the way film does: 13 film stocks measured from real film, a response that changes with exposure, push and pull development, grain modeled as optical density, linear-light halation and a zone-system darkroom with brush, gradient, radial and luma masks. Around the darkroom sit a photo library (your folders are the catalog), colorist tools, live scopes, lens correction, instant-film prints, print-ready export with soft proofing, and a clean round trip with Lightroom Classic and Capture One. Edits live in a small sidecar file beside each photo; originals are never touched. One licence works on both platforms.

## Download

| Platform | Download | Requirements |
|---|---|---|
| Windows 10 / 11 (64-bit) | [ChromogenSetup.exe](https://github.com/chromogenofficial/chromogen/releases/latest/download/ChromogenSetup.exe) | 8 GB RAM (16 GB for RAW and batch work), about 300 MB of disk |
| macOS 11 or later, Apple Silicon (M1 to M4) | [Chromogen-AppleSilicon.dmg](https://github.com/chromogenofficial/chromogen/releases/download/mac-latest/Chromogen-AppleSilicon.dmg) | 8 GB RAM (16 GB for RAW and batch work), about 400 MB of disk |
| macOS 11 or later, Intel | [Chromogen.dmg](https://github.com/chromogenofficial/chromogen/releases/download/mac-latest/Chromogen.dmg) | 8 GB RAM (16 GB for RAW and batch work), about 400 MB of disk |

The macOS builds are notarized by Apple. Install notes: https://chromogen.app/download. Current version numbers and release notes: https://chromogen.app/changelog

## The film stocks

Aureon 100 (vivid fine-grain negative) · Azura 100 (precise cool slide) · Solia 200 (golden warm scan) · Cira 200 (easy consumer scan) · Meridian 250 (daylight cine) · Viridia 250 (vivid daylight cine) · Verel 400 (soft pastel negative) · Sevra 400 (gentle portrait negative) · Aurex 400 (versatile consumer negative) · Vesper 400 (classic consumer negative) · Argent 400 (true-black mono negative) · Nocta 500T (tungsten cine negative) · Prisma (crisp digital slide look). 36 looks in all.

Every stock is measured from a reference target shot on real film and read on lab scanners, then rebuilt as a characteristic curve and dye-layer colour: https://chromogen.app/accuracy

## Formats and workflow

- 16-bit RAW from the major camera makers, JPEG and TIFF; RAW is developed scene-linear with highlight reconstruction
- Non-destructive editing: a small sidecar file beside each photo, originals untouched
- Lightroom Classic and Capture One: set Chromogen as an external editor; Save & Return writes the developed file straight back
- Presets import as native looks: .xmp, .lrtemplate, .costyle, ICC profiles and .cube LUTs
- Export with ICC colour management (sRGB, Adobe RGB, Display P3, ProPhoto); print-ready export with paper sizes, marks, PDF, test strips and soft proofing
- Develops render on the graphics card on both platforms

## Trial and pricing

Free 4-day trial with the real app: full RAW developing, 5 of the 13 stocks, clean exports up to 2048 px, no credit card. Then $29 a month, $228 a year, or $498 once (lifetime, every future update included). One licence activates both the Windows and the macOS app, on one computer at a time. Photos are processed on your computer and are not uploaded.

## Support

Questions, bug reports and feature requests: halide@chromogen.app. Requests go straight to the person who writes the code.
