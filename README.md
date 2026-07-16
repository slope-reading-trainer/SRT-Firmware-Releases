# Slope Reading Trainer – Firmware Releases

Official public downloads for the Slope Reading Trainer.

This repository contains only released user firmware and the machine-readable
firmware catalog used by the SRT Firmware Updater. Debug builds, manufacturer
tools, and application source code are not published here.

## Updater downloads

- [macOS 13+ · Intel and Apple Silicon](https://github.com/slope-reading-trainer/SRT-Firmware-Releases/releases/latest/download/SRT.Firmware.Updater.macOS.dmg)
- [Windows 10/11 · x64](https://github.com/slope-reading-trainer/SRT-Firmware-Releases/releases/latest/download/SRT.Firmware.Updater.Windows.exe)
- [Release notes and checksums](https://github.com/slope-reading-trainer/SRT-Firmware-Releases/releases/latest)

## Firmware

| Hardware | Current firmware | File |
| --- | ---: | --- |
| S01 | 0.92 | `firmware/SRT-S01.092.bin` |
| S02 | 1.31 | `firmware/SRT-S02.131.bin` |

The updater must always match the `hardware` field before downloading or
installing a firmware image. An S01 image must never be installed on S02
hardware, or vice versa. File size and SHA-256 checksum are published in
`manifest.json`.

---

Offizielle öffentliche Downloads für den Slope Reading Trainer.

Dieses Repository enthält ausschließlich freigegebene Nutzer-Firmware und den
maschinenlesbaren Firmwarekatalog für den SRT Firmware Updater. Debug-Versionen,
Herstellerwerkzeuge und Quellcode werden hier nicht veröffentlicht.

Die aktuellen Nutzer-Updater für macOS und Windows stehen oben unter
**Updater downloads** bereit.
