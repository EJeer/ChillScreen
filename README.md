![ChillScreen overview](docs/assets/user-guide/chillscreen-header.png)

ChillScreen is a macOS menu-bar app that gradually adjusts display warmth and
brightness around your daily rhythm.

Every feature remains available. Nothing expires or becomes locked.

It offers:

- a location-aware Automatic daily cycle;
- direct Manual control;
- optional local Learning from evening adjustments;
- optional Ambient Light adaptation with user calibration;
- independent, safe restoration for every connected display.

## Download ChillScreen

### [⬇ Download ChillScreen 1.1.0 for macOS](https://github.com/EJeer/ChillScreen/releases/download/v1.1.0/ChillScreen-1.1.0.dmg)

This is the latest stable version and requires macOS 14 Sonoma or later. Click
the link above to download the app directly — no GitHub knowledge is required.

[Download the SHA-256 checksum](https://github.com/EJeer/ChillScreen/releases/download/v1.1.0/ChillScreen-1.1.0.dmg.sha256)

## Current release

ChillScreen 1.1 adds room-light adaptation, transparent local Learning, deeper
Warmth and Dimming calibration, and substantial reliability and performance
work.

- [Read what is new in 1.1](docs/releases/1.1.0.md)
- [Open the complete User Guide](docs/user-guide.md)

## Requirements

- macOS 14 Sonoma or later.
- Location access is optional and is used only to calculate local sunrise and
  sunset. Coordinates and preferences remain on the Mac.

## Install

1. Download the latest `ChillScreen-*.dmg` from **Releases**.
2. Open the disk image.
3. Drag **ChillScreen** to **Applications**.
4. In Applications, Control-click or right-click **ChillScreen**, then choose
   **Open**.
5. Confirm **Open** in the macOS dialog.

ChillScreen is currently distributed as an unsigned release. Apple may
therefore prevent an ordinary double-click on first launch. If **Open** is not
offered, try opening the app once, then go to **System Settings → Privacy &
Security**, scroll to **Security**, and choose **Open Anyway** for ChillScreen.
After the first confirmation, it opens normally.

## Verify the download

Each release includes a `.sha256` file. To verify a downloaded image in
Terminal:

```sh
shasum -a 256 -c ChillScreen-1.1.0.dmg.sha256
```

## Privacy

ChillScreen does not capture or analyze screen contents. Learning, location,
schedule, and ambient-light preferences are stored locally. See
[Privacy](docs/privacy.md) for details.

## Pay what you think it is worth

ChillScreen is free for:

- personal, self-managed use, including freelancers using it on their own Mac;
- nonprofit organizations;
- government educational organizations.

After two weeks, ChillScreen asks what the app is worth to you. You may choose
any amount or **€0**. Every choice keeps the complete app, with no account,
feature gate, or recurring reminder.

[Choose an amount on Buy Me a Coffee](https://buymeacoffee.com/chillscreen)

## Corporate use

An individual evaluating or using ChillScreen independently may use it under
the free personal terms. A commercial organization that installs, provides, or
manages ChillScreen for employees needs a corporate license.

Corporate licensing and a managed corporate build are available on request:
[chillscreenapp@gmail.com](mailto:chillscreenapp@gmail.com?subject=ChillScreen%20corporate%20licensing).

See the plain-language [Terms of Use](docs/terms-of-use.md).

## The story

[Why I built ChillScreen](docs/story.md)

## Distribution

This repository distributes the ChillScreen application and its public
documentation. The application source code is not published here.

## Feedback

Use this repository's **Issues** section for reproducible bugs and feature
requests. Please include the macOS version and Mac model, but do not post private
location data.
