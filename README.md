<!-- Source of truth for the README of the PUBLIC download repo github.com/chromogenofficial/chromogen.
     Publish it (from the Windows PC, gh is logged in as chromogenofficial) with:
       SHA=$(gh api repos/chromogenofficial/chromogen/contents/README.md --jq .sha)
       gh api -X PUT repos/chromogenofficial/chromogen/contents/README.md -f message="README: <what changed>" -f content="$(base64 -w0 docs/public-readme.md)" -f sha="$SHA" -f branch=main
     Public copy: the strip list at the top of CHANGELOG.md applies. Describe only features that are in the
     release customers can download today (docs/release-process.md step 7). -->
# Chromogen

**Develop your photos like film.** Chromogen is a standalone photo editor for Windows and macOS built around film emulation.

Website: https://chromogen.app · What's new: https://chromogen.app/changelog · Contact: halide@chromogen.app

This repository carries the release downloads.

## What it is

Instead of dropping a preset on a finished JPEG, Chromogen develops the photo the way film does: 13 film stocks measured from real film, a response that changes with exposure, push and pull development, grain modeled as optical density, linear-light halation and a zone-system darkroom with brush, gradient, radial and luma masks. Around the darkroom sits the rest of a photographer's workflow, from moodboard to print, in the same application. Edits live in a small sidecar file beside each photo; originals are never touched. One licence works on both platforms.

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

## The rest of the workflow

- **Moodboard** for collecting references before a shoot.
- **Library** that uses your existing folders as the catalog: culling, star ratings, filters and smart views, an Organize tool that re-files photos by date, camera or rating, and copy-and-paste of an edit onto one or many selected photos. A Calendar keeps shoots, call sheets and a per-day edit meter; Send to hands a photo to Capture One, Lightroom or Photoshop.
- **Auto Develop** meters exposure and balance for you; the Roll pass applies one consistent treatment across a whole shoot.
- **Retouch** workspace with a Face card by part (skin with Skin Cleanup and Eye bags, outline, eyes, nose, mouth), makeup (eyeliner and lashes, Eyebrow Styles, Lip Makeup) and a Heal tool with Heal, Clone and **Remove**: brush over a thing, or click an object, and the gap fills from the photo itself, with nothing leaving your computer.
- **Lens Sharpen** puts back the detail the lens and the sensor softened, before the film goes on; six grain types, with the colour stocks carrying the grain a lab scanner reads from real film.
- **Motion Blur** (linear, zoom, spin) with its own apply area, and **Lab Scan film frames** from real lab-scanned 35 mm negatives.
- **Variations** deals nine takes of your photo in a grid: click one and eight more are dealt, with the film, develop, finish and tone each lockable. **Text along a drawn shape or line**, inside or outside, above or below.
- **Colour grading** with three-way wheels (lift, gamma and gain), a colour mixer, curves and Colour Unify, alongside live waveform, parade and vectorscope displays and automatic lens correction.
- **Design** tools for the finished image: an editorial text designer, Instagram carousels, split panels, contact sheets and instant film prints.
- **Mockups and books**: the photo drops into device, frame, poster, book and billboard scenes for previews, and Book Studio lays out an editable photo book for print.
- **Export** with ICC colour management (sRGB, Adobe RGB, Display P3, ProPhoto), print sizes, test strips and soft proofing. Develops render on the graphics card.

## Formats and integrations

- 16-bit RAW from the major camera makers, JPEG and TIFF; RAW is developed scene-linear with highlight reconstruction
- Non-destructive editing: a small sidecar file beside each photo, originals untouched
- Lightroom Classic and Capture One: set Chromogen as an external editor; Save & Return writes the developed file straight back
- Presets import as native looks: .xmp, .lrtemplate, .costyle, ICC profiles and .cube LUTs
- Photos are processed on your computer and are not uploaded

## Trial and pricing

Free 4-day trial with the real app: full RAW developing, 5 of the 13 stocks, clean exports up to 2048 px, no credit card. Then $29 a month, $228 a year, or $498 once (lifetime, every future update included). One licence activates both the Windows and the macOS app, on one computer at a time.

## Support

Questions, bug reports and feature requests: halide@chromogen.app. Requests go straight to the person who writes the code.
