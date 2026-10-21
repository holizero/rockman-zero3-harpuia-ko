# Rockman Zero 3 · Playable Harpuia Korean Mod

[한국어](./README.md)

A fan mod that replaces the playable Zero with Harpuia in Rockman Zero 3. Harpuia's combat animations, wind blades and tornado assets from the Zero series are adapted to the player combat system.

**[Download the v1.0.0 release ZIP](https://github.com/holizero/rockman-zero3-harpuia-ko/releases/download/v1.0.0/harpuia-ko-v1.0.0.zip)** · [Release notes](https://github.com/holizero/rockman-zero3-harpuia-ko/releases/tag/v1.0.0) · [ZIP checksum](https://github.com/holizero/rockman-zero3-harpuia-ko/releases/download/v1.0.0/harpuia-ko-v1.0.0.zip.sha256)

Use the release ZIP above. GitHub's automatically generated **Source code (zip)** is not the playable patch package. The game translation and patcher interface are in Korean.

![Actual Harpuia title screen](./title.png)

## Included features

- Harpuia body graphics, portraits, title artwork, Korean text, menu icons and attack/hurt voices.
- Twin-sword and wind-blade attacks, inertial movement, heel-flame hovering, horizontal and vertical flight.
- A new game starts with basic equipment. Additional equipment and progression elements are earned during gameplay; hidden elements require specific conditions.
- An offline browser patcher with installation and restoration to the Japanese original.

## Installation

1. Extract every file from `harpuia-ko-v1.0.0.zip` into a new folder.
2. Open `하르퓨이아_패치도구.html` in Edge or Chrome.
3. Select your supported Japanese original `.gba` file.
4. Save the patched output as a new file using the patcher's save button.
5. Open the new ROM in your emulator and restart. Check with a new game first.

No installation, local server or internet connection is needed to apply the patch. Processing happens in the browser and does not overwrite the selected input. Korean translation and the mod are applied together; do not apply a separate Korean patch first.

## Supported original

| Field | Value |
|---|---|
| Game | Rockman Zero 3 (Japan) |
| Game code | BZ3J |
| Size | 8,388,608 bytes |
| SHA-1 | `ff7a801776dc76e6d8c7ef73a6660ae732934a3f` |

Korean or US versions, development builds and other modified ROMs are not supported installation inputs. Renaming a file does not make its contents compatible.

## Restoration and saves

Choose Japanese-original restoration in the patcher and select the completed ROM produced by this release. Restoration returns the original Japanese bytes and also removes the translation. It does not modify saves.

Close the emulator and back up battery saves (`.sav`) before reusing them. Restart the new ROM and use in-game saves instead of old save states. Compatibility with every save combination has not been verified.

## Package and validation

The ZIP contains the offline HTML patcher, installation/restoration IPS files, Korean instructions, controls, screenshots and verification records. **No original or completed game ROM, save or emulator is distributed.**

Included records cover 9 mGBA scenarios and 21,450 frames for new-game inventory, menu transitions, title/return, movement, attacks, graphics and sound. Reward acquisition was checked separately with 3 test-result conditions and 7,500 frames. This is not an end-to-end playthrough. Full-stage completion, all terrain/effect combinations and save compatibility remain outside that coverage. See the included verification records for the setup and limits.

ZIP SHA-256:

```text
836d474990fa3a2199739470c6936b13f1cff91cc839d09409cbcbc345102204
```

## Related mod

- [Omega Zero Korean Mod](https://github.com/holizero/rockman-zero3-omega-ko). It is a separate mod; do not stack its patch with Harpuia.

## Credits

Original game: CAPCOM / INTI CREATES. This fan mod uses the existing project's Korean translation, Harpuia assets from the Zero series and game-analysis materials. This repository is for patch distribution and documentation.
