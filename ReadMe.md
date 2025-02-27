# Glitch Flipper Firmware

> [!WARNING]
> This software is intended solely for experimental purposes and is not meant for any illegal activities.
> We do not condone unlawful behavior and strongly encourage you to use it only within the bounds of the law.
>
> This project is developed independently and is not affiliated with Flipper Devices.
>
> Also be aware, DarkFlippers/unleashed-firmware is the only official page of the project, there is no paid, premium or closed source versions and if someone contacts you and say they are from our team and try to offer something like that - they are scammers, block that users ASAP

<br/>

## 🚀 Usage

Before getting started:
- **Review the Official Documentation:** [docs.flipper.net](https://docs.flipper.net)

- **Installation Guide & Version Info:**  
  How to install the firmware by following the [Installation Guide](/documentation/HowToInstall.md) and check the [version information](/CHANGELOG.md#recommended-update-option---web-updater) (`r`, `e`, ` `, `c`)

- **FAQ:**  
  Find answers to common questions in the [FAQ](/documentation/FAQ.md)

## 📦 Releases

### Release builds (stable)

### Dev builds (unstable)

## 🆕 What's New

> Soon.

Also check the [changelog in releases](https://github.com/geeknik/glitch-flipper-firmware/releases) for latest updates!

### Current modified and new Sub-GHz protocols list:
Thanks to Official team (to their SubGHz Developer, Skorp) for implementing support (decoder + encoder / or decode only) for these protocols in OFW.  

> [!NOTE]
> Not all Keeloq systems are supported for decoding or emulation!
> <details>
> <summary><strong>Supported Keeloq manufacturers include</strong></summary>
> <br/>
>
> | Column 1          | Column 2     | Column 3         | Column 4          | Column 5               |
> |-------------------|--------------|------------------|-------------------|------------------------|
> | Alligator         | Comunello    | GSN              | Magic_4           | SL_A2-A4               |
> | Alligator_S-275   | Dea_Mio      | Guard_RF-311A    | Mongoose          | SL_A6-A9/Tomahawk_9010 |
> | APS-1100_APS-2550 | DTM_Neo      | Harpoon          | Mutanco_Mutancode | SL_B6,B9_dop           |
> | Aprimatic         | DoorHan      | IronLogic        | NICE_MHOUSE       | Sommer(fsk476)         |
> | Beninca           | EcoStar      | JCM_Tech         | NICE_Smilo        | Stilmatic              |
> | BFT               | Elmes_Poland | KEY              | Normstahl         | Teco                   |
> | Came_Space        | FAAC_RC,XT   | Kingates_Stylo4k | Pantera           | Tomahawk_TZ-9030       |
> | Cenmax            | FAAC_SLH     | KGB/Subaru       | Pantera_CLK       | Tomahawk_Z,X_3-5       |
> | Cenmax_St-5       | Faraon       | Leopard          | Pantera_XS/Jaguar | ZX-730-750-1055        |
> | Cenmax_St-7       | Genius_Bravo | Magic_1          | Partisan_RX       |                        |
> | Centurion         | Gibidi       | Magic_2          | Reff              |                        |
> | Monarch           | Jolly Motors | Magic_3          | Sheriff           |                        |
> </details>
<br/>

<details>
<summary><code><strong>Decoders/Encoders or emulation (+ programming mode) support made by @xMasterX</strong></code></summary>
<br/>

- ReversRB2 / RB2M (static 64 bit) with add manually support
- Marantec24 (static 24 bit) with add manually support
- GangQi (static 34 bit) with button parsing and add manually support (thanks to @mishamyte for captures and testing, thanks @Skorpionm for help)
- Hollarm (static 42 bit) with button parsing and add manually support (thanks to @mishamyte for captures, thanks @Skorpionm for help)
- Hay21 (dynamic 21 bit) with button parsing
- Nero Radio 57bit (+ 56bit support)
- CAME 12bit/24bit encoder fixes (Fixes are now merged in OFW)
- Keeloq: Dea Mio, Genius Bravo, GSN, HCS101, AN-Motors, JCM Tech, MHouse, Nice Smilo, DTM Neo, FAAC RC,XT, Mutancode, Normstahl, Beninca + Allmatic, Stilmatic, CAME Space, Aprimatic (model TR and similar), Centurion Nova (thanks Carlos !), Hormann EcoStar, Novoferm, Sommer, Monarch (thanks @ashphx !), Jolly Motors (thanks @pkooiman !)
</details>

<details>
<summary><code><strong>Protocols support made by Skorp (original implementation) and @xMasterX (current version)</strong></code></summary>
<br/>
- CAME Atomo → Update! check out new [instructions](/documentation/SubGHzRemoteProg.md)
- Nice Flor S → How to create new remote - [instructions](/documentation/SubGHzRemoteProg.md)
- FAAC SLH (Spa) → Update!!! (Programming mode!) Check out new [instructions](/documentation/SubGHzRemoteProg.md)  
- Keeloq: BFT Mitto → Update! Check out new [instructions](/documentation/SubGHzRemoteProg.md)
- Star Line
- Security+ v1 & v2
</details>

<details>
<summary><code><strong>Encoders made by @assasinfil and @xMasterX</strong></code></summary>
<br/>
- Somfy Telis → How to create new remote - [instructions](/documentation/SubGHzRemoteProg.md)
- Somfy Keytis
- KingGates Stylo 4k
- Alutech AT-4N → How to create new remote - [instructions](/documentation/SubGHzRemoteProg.md)
- Nice ON2E (Nice One) → How to create new remote - [instructions](/documentation/SubGHzRemoteProg.md)
</details>

## 📱 Community Apps

Enhance your Flipper Zero with apps and plugins created by the community:

- **Extra Plugins & Packs:**  
  Check out the latest extra plugins and plugin packs (Extra Pack and Base Pack) on [GitHub](https://github.com/xMasterX/all-the-plugins/releases/latest).

- **Source Code & Full List:**  
  Find the complete list and source code at [xMasterX/all-the-plugins](https://github.com/xMasterX/all-the-plugins/tree/dev).

- **Official Apps Catalog:**  
  Browse the official Flipper Zero Apps Catalog on the [web](https://lab.flipper.net/apps) or via the [mobile app](https://flipperzero.one/downloads).


## 📁 Where I can find IR, Sub-GHz, ... files, DBs, and other stuff?
- [UberGuidoZ Playground - Large collection of files - Github](https://github.com/UberGuidoZ/Flipper)
- [Awesome Flipper Zero - Github](https://github.com/djsime1/awesome-flipperzero)


## 📘 Instructions

### ![Tools Icon Badge] Firmware & main Apps feature

- System: [How to change Flipper name](/documentation/CustomFlipperName.md)
- BadUSB: [How to add new keyboard layouts](https://github.com/dummy-decoy/flipperzero_badusb_kl)
- Infrared: [How to make captures to add them into Universal IR remotes](/documentation/InfraredCaptures.md)  

### ![SubGhz Icon Badge] Sub-GHz

- [How to use Flipper as new remote (Nice FlorS, BFT Mitto, Somfy Telis, Aprimatic, AN-Motors, etc..)](/documentation/SubGHzRemoteProg.md)  
- External Radio: [How to connect CC1101 module](https://github.com/quen0n/flipperzero-ext-cc1101)  
- Transmission is blocked? [How to extend Sub-GHz frequency range](/documentation/DangerousSettings.md)
- [How to add extra Sub-GHz frequencies](/documentation/SubGHzSettings.md)
- [~~Configure Sub-GHz Remote App~~](/documentation/SubGHzRemotePlugin.md) ⚠️ Not recommended, please use embedded configurator

### ![Plugins Icon Badge] Plugins

- TOTP (Authenticator): [config description](https://github.com/akopachov/flipper-zero_authenticator/blob/master/docs/conf-file_description.md) 
- Barcode Generator: [How to use](/documentation/BarcodeGenerator.md)
- Multi Converter: [How to use](/documentation/MultiConverter.md)
- WAV Player: [sample files & how to convert](https://github.com/UberGuidoZ/Flipper/tree/main/Wav_Player#readme)  
- Sub-GHz playlist: [generator script](https://github.com/darmiel/flipper-scripts/blob/main/playlist/playlist_creator_by_chunk.py)

### ![GPIO Icon Badge] GPIO - Plugins that works with external hardware

- Unitemp - Temperature sensors reader: [How to use & supported sensors](https://github.com/quen0n/unitemp-flipperzero#readme)
- [NMEA] GPS: [How to use](https://github.com/xMasterX/all-the-plugins/blob/dev/base_pack/gps_nmea_uart/README.md)  
- i2c Tools [How to use](https://github.com/xMasterX/all-the-plugins/blob/dev/base_pack/flipper_i2ctools/README.md)  
- [NRF24] plugins: [How to use](/documentation/NRF24.md)  
- [WiFi] Scanner: [How to use](https://github.com/SequoiaSan/FlipperZero-WiFi-Scanner_Module#readme) | [Web Flasher](https://sequoiasan.github.io/FlipperZero-WiFi-Scanner_Module/)
- [ESP8266] Deauther: [How to use](https://github.com/SequoiaSan/FlipperZero-Wifi-ESP8266-Deauther-Module#readme) | [Web Flasher](https://sequoiasan.github.io/FlipperZero-Wifi-ESP8266-Deauther-Module/)
- [ESP32] WiFi Marauder: [How to use](https://github.com/UberGuidoZ/Flipper/tree/main/Wifi_DevBoard)<sub> docs by UberGuidoZ</sub> | [Marauder repo](https://github.com/justcallmekoko/ESP32Marauder)
- [ESP32-CAM] Camera Suite: [How to use](https://github.com/CodyTolene/Flipper-Zero-Camera-Suite)
- How to Upload `.bin` to ESP32/ESP8266: [Windows](https://github.com/SequoiaSan/Guide-How-To-Upload-bin-to-ESP8266-ESP32) | [FAP "ESP flasher"](https://github.com/0xchocolate/flipperzero-esp-flasher)
- [GPIO] SentrySafe plugin: [How to use](/documentation/SentrySafe.md)


## 👨‍💻 Firmware & Development

- **Developer Documentation** - [developer.flipper.net](https://developer.flipper.net/flipperzero/doxygen)  
- **[How to build](/documentation/HowToBuild.md#how-to-build-by-yourself) | [Project-structure](#project-structure)**
- **CLion IDE** - How to setup workspace for flipper firmware development [by Savely Krasovsky](https://krasovs.ky/2022/11/01/flipper-zero-clion.html)
- **"Hello world!"** - plugin tutorial [English<sub> by DroomOne</sub> ](https://github.com/DroomOne/Flipper-Plugin-Tutorial) | [Russian<sub> by Pavel Yakovlev</sub>](https://yakovlev.me/hello-flipper-zero)
- [How to write your own app](https://flipper.atmanos.com/docs/overview/intro).

### Project structure

- `applications`    - Applications and services used in firmware
- `assets`          - Assets used by applications and services
- `furi`            - Furi Core: OS-level primitives and helpers
- `debug`           - Debug tool: GDB-plugins, SVD-file and etc
- `documentation`   - Documentation generation system configs and input files
- `firmware`        - Firmware source code
- `lib`             - Our and 3rd party libraries, drivers and etc...
- `site_scons`      - Build helpers
- `scripts`         - Supplementary scripts and python libraries home

Also, pay attention to the `ReadMe.md` files inside those directories.


## 🔗 Links
- Soon

## Note
This firmware is a fork of [Unleashed Firmware](https://github.com/DarkFlippers/unleashed-firmware/) which is a fork of the original (OFW) version of [flipperdevices/flipperzero-firmware](https://github.com/flipperdevices/flipperzero-firmware) and represents the **most stable** custom build, incorporating **new features** and **improvements** to the original components while remaining **fully compatible** with the API and applications of the original firmware.
