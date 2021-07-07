
<h1 align="center">
  <br>
  <a href="https://pitchblackrecovery.com"><img src="https://raw.githubusercontent.com/shovon668/xda-template/r3/pbrp3-banner-xda.png" alt="Welcome to PitchBlack Recovery Project 👋" width="600"></a>
  <br>
 Welcome to Bushcats Recovery based on PBRP 👋
  <br>
</h1>

<h4 align="center">The Perfect Android Recovery for your device! PBRP provides the most advanced Open Source Android Recovery to troubleshoot your device on the GO!</h4>


<p align="center">
<a>
  <img alt="Version" src="https://img.shields.io/badge/version-3.1.0-blue.svg?cacheSeconds=2592000" />
  </a>

<a>
  <img alt="Status" src="https://img.shields.io/badge/status-stable-deepgreen.svg" />
  </a>

  <a href="https://pitchblackrecovery.com/docs" target="_blank">
    <img alt="PBRP Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  
  <a href="https://github.com/PitchBlackRecoveryProject/android_bootable_recovery/blob/android-9.0/LICENSE" target="_blank">
    <img alt="License: Apache--2.0" src="https://img.shields.io/badge/License-Apache--2.0-yellow.svg" />
  </a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-build">How To build</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>

<h3 align="center">
  🏠 <a href="https://pitchblackrecovery.com/">Homepage</a> •
  📥 <a href="https://pitchblackrecovery.com/devices">Official Devices</a>
</h3>

## Key Features
* Kang OS Theme
* Resurrection Remix Theme
* Fresh native android like UI
  - New Icons
  - New Accent
  - New Background
  - New Action Screens
* Universal package flasher (zip, ozip, img etc)
* MIUI OTA Support
* Encryption Support
* PBRP in house tweaks:
  - AVB 2.0 disabler
  - Treble checker disabler
  - Easy logger
* Popular public tools:
  - Magisk Installer & Remover
  - Magisk Recovery
  - Finalize for A/B Devices
  - Password Recovery etc

## How To Build


```bash
# (NO THEME) initialize the latest stable branch
$ repo init -u git://github.com/Bush-cat/manifest_pb.git -b android-9.0

# For Resurrection Remix themed Recovery  initialize the latest stable rr branch
$ repo init -u git://github.com/Bush-cat/manifest_pb.git -b android-9.0-rr

# For Kang OS themed Recovery initialize the latest stable kang branch
$ repo init -u git://github.com/Bush-cat/manifest_pb.git -b android-9.0-kang

# Sync the latest stable branch
$ repo sync
```

Follow our omni_device.mk sample

📱 <a href="omni_device.mk.sample.md" target = "_blank">omni_device.mk sample</a>

⚙️ Build

```bash
$ cd <source-dir>
$ . build/envsetup.sh
$ lunch omni_<device>-eng
$ mka recoveryimage
````

## Credits

This software uses the following open source project(s):

* [TWRP](https://github.com/minimal-manifest-twrp)
* [PBRP](https://github.com/PitchBlackRecoveryProject)

## License

Copyright © 2020 [PitchBlack Recovery Project](https://github.com/PitchBlackRecoveryProject).<br />
This project is [Apache 2.0](https://github.com/PitchBlackRecoveryProject/android_bootable_recovery/blob/android-9.0/LICENSE) licensed.

***
> [PitchBlack Recovery Project Team](https://pitchblackrecovery.com/#team)
