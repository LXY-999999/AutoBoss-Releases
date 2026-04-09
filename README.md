# AutoBoss

[中文说明](./README.zh-CN.md)

AutoBoss is a closed-source macOS desktop app distributed through GitHub Releases.

This repository is the official download page for:
- macOS installer packages
- installation instructions
- release notes

Source code is not published in this repository.

## Download

Latest version: `v1.0.0`

Choose the installer that matches your Mac:

- [Apple Silicon Download](https://github.com/LXY-999999/AutoBoss-Releases/releases/download/v1.0.0/AutoBoss-1.0.0-arm64.dmg)
- [Intel Mac Download](https://github.com/LXY-999999/AutoBoss-Releases/releases/download/v1.0.0/AutoBoss-1.0.0-x64.dmg)
- [View All Releases](https://github.com/LXY-999999/AutoBoss-Releases/releases)

## Which Version Do I Need

- `arm64` is for Apple Silicon Macs: M1, M2, M3, and M4
- `x64` is for Intel-based Macs

Quick check on your Mac:
- Open `Apple menu > About This Mac`
- If you see `Apple M1/M2/M3/M4`, download `arm64`
- If you see `Intel`, download `x64`

## Install In 1 Minute

1. Download the correct `.dmg` file.
2. Open the disk image.
3. Drag `AutoBoss` into `Applications`.
4. Open `Applications` and launch `AutoBoss`.
5. If macOS shows a security warning, go to:
   `System Settings > Privacy & Security`
6. Allow the app to run, then open it again.

## First Launch

On first launch, AutoBoss may ask for permissions required for local automation.

Typical steps:
- keep Google Chrome installed and visible
- follow the in-app environment check
- grant the required macOS permissions when prompted
- return to the app and re-check the environment

Detailed Chinese installation instructions:
- [INSTALL-zh-CN.txt](./INSTALL-zh-CN.txt)

## Troubleshooting

If the app does not open on macOS:

1. Open `System Settings > Privacy & Security`
2. Scroll to the security warning near the bottom
3. Click the button to allow AutoBoss
4. Launch the app again

If you downloaded the wrong build:
- Apple Silicon Macs should use `arm64`
- Intel Macs should use `x64`

## Repository Scope

- This repository is for binary distribution only
- It contains installers and documentation
- It does not contain source code

## License

This software is closed-source.

See [LICENSE.txt](./LICENSE.txt) for the distribution terms.
