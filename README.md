# Android Setup

Configuration as Code for my Android phones:

- [ ] Evolution X on Xiaomi Redmi K20 Pro
- [ ] One UI on Samsung Galaxy S22 Plus
- [ ] GrapheneOS on Google Pixel 6 Pro

Features:

- [ ] Debloat
- [ ] Install apps on Google Play and F-Droid
- [ ] Optimize battery and performance
- [ ] Enhance privacy

## Prerequisites

### PC

> Only Linux is officially supported

- Install [Docker](https://www.docker.com)
- Open the tools container: `make tools`

### Phone

- Enable [Android Debug Bridge](https://developer.android.com/studio/command-line/adb)
- Connect to PC

### Update configuration

Checkout the following files:

- `defaults/main.yml`

## Installation

Simply run:

```sh
make
```

## Post-installation

- Disable ADB on the phone
