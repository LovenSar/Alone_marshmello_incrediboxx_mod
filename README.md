# Alone (Marshmello ModBox Port)

This is a port of the `Alone` ModBox package for iOS, Android, and desktop platforms. It contains the animations, images, audio, and bonus content required for the music loop.

## Package Information

| Item | Value |
| --- | --- |
| Name | Alone |
| Supported platforms | iOS, Android, and desktop |
| Date | 2025-09-23 |
| BPM | 142 |
| Loop duration | 6750 ms |
| Total frames | 322 |
| Track count | 20 |
| Bonus content | 1: Alone |
| Credits | MrF |

## Directory Structure

```text
.
├── anime/             Track animation frames, animation JSON, and low-resolution assets (`-ld`)
├── bonus/             Bonus animation SVG and video files (MP4)
├── image/             Game backgrounds, titles, icons, and other interface images
├── sound/
│   ├── ogg/           OGG audio files
│   └── mp3/           MP3 audio files
├── app.json           ModBox configuration, track order, and color information
├── icon.jpg           Package icon
└── icon.png           Package icon
```

## Track Order

The 20 tracks defined in `app.json` are:

1. `1_kickhit`
2. `2_kick`
3. `3_clap`
4. `4_hithat`
5. `5_drum`
6. `6_superdeepbass`
7. `7_intro`
8. `8_cymbal`
9. `9_transision`
10. `10_crashintro`
11. `11_pluck`
12. `12_bell`
13. `13_leadnormal`
14. `14_droplead`
15. `15_basstungtung`
16. `16_alone`
17. `17_arcade`
18. `18_vokalchop`
19. `19_vokalchopdrop`
20. `20_enola`

## Usage

This is a ported resource package for iOS, Android, and desktop platforms. Use the appropriate ModBox application or launch method for the target platform, and preserve the directory structure. `app.json`, `anime/`, `image/`, and `sound/` must remain at the same directory level.

Audio is provided in both OGG and MP3 formats. Animation files with the `-ld` suffix are low-resolution versions. Bonus configuration is stored in the `bonusarray` field of `app.json`, with the corresponding assets in `bonus/` and `sound/`.

## Copyright and Attribution

This directory does not include a separate license or complete attribution information. Before using, redistributing, or publishing this package, verify the rights for the music, images, animations, and video assets, as well as the requirements of the ModBox platform.
