# Mi NoteBook 14 Hackintosh - MicBook

### (Tested with macOS Monterey Version 12.7.5)

## Disclaimer

- This README is an extremely simplified and cut-down version of the original by [Abhishek Olkha](https://github.com/itsabhishekolkha/), so I highly suggest you use the files here but follow the steps over at the [original repository](https://github.com/itsabhishekolkha/Mi-notebook-14-Hackintosh)'s README.
- Not responsible for any issues or damages caused on your device.

## Introduction

This repo contains the necessary updated files (as of July 24, 2024 - OpenCore 1.0.0) to run macOS Monterey (and presumeably, any newer and well supported macOS version by the community), on the **Mi Notebook 14** series.

I highly suggest you to follow [Dortania's OpenCore Installation Guide](https://dortania.github.io/OpenCore-Install-Guide/) step-by-step, and use the files here to assist you in quickly gathering the required files and get ready quicker with a previously set-up config.plist file. The guide has basically everything you would possibly need when facing errors or issues.

## Key points to note

- While transferring over config.plist from this repository to your EFI partition, make sure you fill in the PlatformInfo with the device information generated with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) or any other equivalent (use "MacBookPro16,1" (without the quotes) as the SMBIOS name when generating).
- The kext files for Bluetooth have been updated, but couldn't get it working on my device, so I can't comment on whether it would work or not.
- Overall general usability of the laptop is impeccable, with basically no bugs (except BT).

## Credits

- OC - [Abhishek Olkha](https://github.com/itsabhishekolkha/)
- [Daliansky and stevezhengshiqi](https://github.com/daliansky/)
- [Profzie](https://github.com/profzei/Matebook-X-Pro-2018)
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/)
- [Acidanthera](https://github.com/acidanthera)
- [OpenIntelWireless](https://github.com/OpenIntelWireless)
- [CorpNewt](https://github.com/corpnewt)
- [RehabMan](https://github.com/RehabMan)
- [Sniki](https://github.com/Sniki)
- [VoodooI2C](https://github.com/VoodooI2C)
- [Try3D](https://github.com/try3d) for lending me his Mi Notebook 14 to experiment with.
