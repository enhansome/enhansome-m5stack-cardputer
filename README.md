# Awesome M5Stack Cardputer with stars

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<img src="m5stack cardputer.jpg" alt="m5stack cardputer" width="400">

M5Stack Cardputer is a S3 Stamp cheap ($30) and complete mini computer in a credit-card size, weighing 92.8g.\
[Official website](https://shop.m5stack.com/products/m5stack-cardputer-with-m5stamps3-v1-1) | [Docs](https://docs.m5stack.com/en/core/Cardputer)

Cardputer Reddit Community: <https://www.reddit.com/r/CardPuter>\
An Unofficial Cardputer Discord Server: <https://discord.gg/zuzSVDgxvx>\
Unofficial Cardputer Development Reference Manual: <https://cardputer.free.nf/>

## Specs

### Processor

From ESP32-S3Fn8 ([Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf)):

* Dual 32bit Xtensa LX7 cores running up to **240Mhz**
* RISC-V Ultra Low Power Co-processor
* ULTRA LOW Deep Sleep Current

### Memory

* 128-bit data bus and SIMD commands
* 384 KB ROM - for booting and core functions
* 512 KB SRAM - for data and instructions, running at a configurable frequency of up to 240 MHz
* 16 KB SRAM in RTC - can retain data in Deep-sleep mode
* 4 Kbit eFuse - reserved for user data, such as encryption key and device ID
* 8 MB Flash
* SPI, Dual SPI, Quad SPI, Octal SPI, QPI and OPI interfaces that allow connection to multiple flash and external RAM

### Devices/Resources

* Bluetooth: 5.0, BLE + Mesh
* Wi-Fi: 802.11b/g/n 2.4Ghz
* Display: ST7789V2 - IPS LCD, 1,14", 240px x 135px
* Battery: internal 120mAh + 1400mAh (in the base) lithium battery
* 1 TF-Card (MicroSD) slot
* 1 USB-C OTG in/out
* 1 Grove 1 x HY2.0-4P input/output
* 4x14 Keyboard: 56 keys, QWERTY type, ortholinear with tactile click switches
* Infrared G44 ∠0° : 410cm, < 90° : 66cm, < 45° : 170cm
* Digital MEMS Microphone PDM-MIC SPM1423
* Sound: I2S-Speaker NS4168 - 8Ω@1W
* 2 magnets on the back to stick it somewhere metallic
* It comes with a little hexagonal screwdriver to open it
* Dimensions: 85mm x 54mm x 19.7mm
* Operating Current: IR transmission mode: DC-4.2V/148.07mA | Key mode: DC-4.2V/138.93mA
* Sleep Current: DC-4.2V @ 0.15uA
* Product Weight: 90g

**Note: no builtin NFC, RFID or LoRa module**

***

## Pre-installed apps

* Wi-Fi Scanner
* Audio recorder
* ESP Chat - to communicate with other cardputers or similars
* IR remote data send manually
* Pika Python REPL
* Set WiFi
* Timer
* Keyboard (USB or Bluetooth) connector

These builtin apps can be found at: <https://github.com/m5stack/M5Cardputer-UserDemo> ⭐ 343 | 🐛 8 | 🌐 C | 📅 2026-07-17

## Community Apps

### Launchers

* [M5 Launcher](https://github.com/bmorcelli/Launcher) ⭐ 2,057 | 🐛 14 | 🌐 C++ | 📅 2026-09-04 - App launcher for M5StickC, M5StickC Plus, M5StickC Plus 2 and M5Cardputer
  * [250+ prebuilt binaries](https://bmorcelli.github.io/Launcher/catalog.html)
  * [Laucher website](https://bmorcelli.github.io/Launcher/)
* [BerylliumOS](https://github.com/beryllium-org/OS) ⭐ 325 | 🐛 3 | 🌐 Python | 📅 2026-08-28 - Another Micro OS for Cardputer
* [MicroHydra Launcher](https://github.com/echo-lalia/MicroHydra) ⭐ 314 | 🐛 20 | 🌐 Python | 📅 2026-03-30
  * [MicroHydra Apps](https://github.com/echo-lalia/MicroHydra-Apps) ⭐ 84 | 🐛 6 | 🌐 Python | 📅 2026-03-30
  * [HydraMenu app](https://github.com/Gabriel-F-Sousa/HydraMenu) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2024-04-01
  * [PicoChat Client](https://github.com/PixelDud/CardPuter-PicoChat) To use with MicroHydra
* [PyDOS + PyBASIC](https://github.com/RetiredWizard/PyDOS) ⭐ 179 | 🐛 0 | 🌐 Python | 📅 2026-02-05
* [Simple App Launcher for Cardputer](https://github.com/shikarunochi/CardputerSimpleLaucher) ⭐ 61 | 🐛 0 | 🌐 C++ | 📅 2023-11-06
* [HydraOS](https://github.com/WauHundeland/HydraOS) ⭐ 25 | 🐛 0 | 🌐 C | 📅 2024-07-22 - Micro OS for Cardputer

### Cybersecurity Related

* [Cardputer Marauder ESP32](https://github.com/justcallmekoko/ESP32Marauder) ⭐ 12,214 | 🐛 328 | 🌐 C++ | 📅 2026-09-04
* [Bruce](https://github.com/pr3y/Bruce) ⭐ 6,643 | 🐛 239 | 🌐 C++ | 📅 2026-08-31
* [ESP32 Bus Pirate](https://github.com/geo-tp/ESP32-Bus-Pirate) ⭐ 5,683 | 🐛 28 | 🌐 C++ | 📅 2026-09-04
* [Evil-M5Project](https://github.com/7h30th3r0n3/Evil-M5Project) ⭐ 2,573 | 🐛 18 | 🌐 C++ | 📅 2026-08-20
* [M5 Stick NEMO](https://github.com/n0xa/m5stick-nemo) ⭐ 1,300 | 🐛 9 | 🌐 C | 📅 2026-07-15 - Hacking tools for cardputer
* [M5PORKCHOP](https://github.com/0ct0sec/M5PORKCHOP) ⭐ 849 | 🐛 39 | 🌐 C++ | 📅 2026-06-27
* [Palnagotchi](https://github.com/viniciusbo/m5-palnagotchi) ⭐ 81 | 🐛 3 | 🌐 C++ | 📅 2026-01-28
* [433Mhz sniffer](https://github.com/bmorcelli/io433) ⭐ 47 | 🐛 0 | 🌐 C++ | 📅 2024-11-07

### Game Related

* [Cardputer Game Station Emulators](https://github.com/geo-tp/Cardputer-Game-Station-Emulators) ⭐ 240 | 🐛 15 | 🌐 C | 📅 2026-06-01 - Emulator for cardputer that supports ten different consoles
* [Gameboy emulator](https://github.com/Mr-PauI/Gameboy-Enhanced-Firmware-m5stack-cardputer-) ⭐ 85 | 🐛 3 | 🌐 C | 📅 2026-02-20
* [Gameboy Emulator Port of Peanut-GB by matthew-5pl](https://github.com/matthew-5pl/gb_cardputer) ⚠️ Archived | [By yonxji](https://github.com/yongxji/cardputer-gameboy-emu) | [By Mr-Paul](https://github.com/Mr-PauI/Gameboy-Enhanced-Firmware-m5stack-cardputer-) ⭐ 85 | 🐛 3 | 🌐 C | 📅 2026-02-20 | By geo-tp (see next on the list)
* [Math Game](https://github.com/seanbutler/M5CardputerMathGame) ⭐ 36 | 🐛 0 | 🌐 C++ | 📅 2024-03-24
* [Tamaputer Tamagotchi P1 Emulator](https://github.com/mindovermiles262/tamaputer) ⭐ 25 | 🐛 0 | 🌐 C++ | 📅 2026-08-29
* [Cave-Mine](https://github.com/question-and-answer/cave-mine-cardputer-alpha1) ⭐ 22 | 🐛 0 | 🌐 C++ | 📅 2026-03-18
* [Anarch Game port from ESPBoy](https://github.com/TheBricktop/Anarch-Cardputer) ⭐ 14 | 🐛 0 | 🌐 C | 📅 2026-08-27
* [Some games experiments](https://github.com/polyphasicdevs/Cardputer-experiments) ⭐ 13 | 🐛 0 | 🌐 C++ | 📅 2024-02-14
* [Sun Rider Game](https://github.com/Treblewolf/M5Cardputer-Sun-Rider) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2025-04-17
* [Classic Snake Game](https://github.com/ostaquet/M5Snake/tree/master/src/M5Snake) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2021-05-01
* [DOOM port](https://github.com/Logimancer/Cardputer-doom) ⭐ 11 | 🐛 0 | 📅 2023-07-11 - Yes, of course we have Doom
* [TinyKnight Game](https://github.com/foopod/tinyKnight) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2024-02-15
* [Hotspot Arcade](https://github.com/genkigenki/hotspot-arcade-cardputer) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2026-09-04 - Several offline party games your guests play from their phones
* [Conway's Game of Life](https://github.com/Mystereon/CardLife) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2025-05-15

### Misc.

* [Universal remote control](https://github.com/geo-tp/Ultimate-Remote) ⭐ 200 | 🐛 13 | 🌐 C++ | 📅 2025-09-11
* [Cardputer WebRadio](https://github.com/cyberwisk/M5Cardputer_WebRadio) ⭐ 130 | 🐛 0 | 🌐 C++ | 📅 2026-08-15
* [Lora Chat App](https://github.com/nonik0/CardputerLoRaChat) ⭐ 121 | 🐛 2 | 🌐 C++ | 📅 2024-12-03
* [MiniAcid](https://github.com/urtubia/miniacid) ⭐ 105 | 🐛 13 | 🌐 C++ | 📅 2026-02-10
  * [Demo site](https://miniacid.mrbook.org)
* [Audio Stream Server](https://github.com/geo-tp/M5Cardputer-Audio-Stream-Server) ⭐ 104 | 🐛 4 | 🌐 C | 📅 2025-08-12
* [Rust firmware hal and examples](https://github.com/Kezii/Rust-M5Stack-Cardputer) ⭐ 69 | 🐛 0 | 🌐 Rust | 📅 2024-03-27
* [SSH Client By aat440z](https://github.com/aat440hz/SSHClient-M5Cardputer) ⭐ 62 | 🐛 3 | 🌐 C++ | 📅 2023-12-30 | [By fernandofatech](https://github.com/fernandofatech/M5Cardputer-SSHClient) ⭐ 67 | 🐛 1 | 🌐 C++ | 📅 2026-09-04 | [By SUB0PT1MAL](https://github.com/aat440hz/SSHClient-M5Cardputer) ⭐ 62 | 🐛 3 | 🌐 C++ | 📅 2023-12-30
* [PDAputer](https://github.com/nishad2m8/PDAputer) ⭐ 62 | 🐛 2 | 🌐 C | 📅 2026-03-25
* [Volos Cardputer TV Remote](https://github.com/VolosR/M5CardRemote/) ⭐ 56 | 🐛 0 | 🌐 C | 📅 2023-12-15
* [ESP Console Emulator Server](https://github.com/IncursioHack/ESP-Game-Server) ⭐ 52 | 🐛 3 | 🌐 JavaScript | 📅 2024-04-29
* [M5CardForth - Forth Programming Language for Cardputer](https://github.com/ryu10/M5CardForth) ⭐ 47 | 🐛 5 | 🌐 C++ | 📅 2026-04-07
* [HID Bluetooth Keyboard](https://github.com/Gitshaoxiang/M5Cardputer-BLE-HID-Keyboard) ⭐ 30 | 🐛 1 | 🌐 C | 📅 2023-10-12
* [M5Cardputer C64 Emulator](https://github.com/iele/M5Cardputer-C64-Emulator) ⭐ 25 | 🐛 0 | 🌐 C++ | 📅 2024-08-22
* [Telnet Client](https://github.com/aat440hz/TelnetClient-M5Cardputer) ⭐ 22 | 🐛 0 | 🌐 C++ | 📅 2023-12-30
* [Weather App](https://github.com/qubiX00/weather-cardputer) ⭐ 22 | 🐛 0 | 🌐 C++ | 📅 2024-02-17
* [User Demo extended with some more apps](https://github.com/JohnZ03/M5Cardputer-UserDemo) ⭐ 19 | 🐛 0 | 🌐 C | 📅 2024-01-30
* [AI Gadget assistant for Cardputer](https://github.com/jeftheone/M5CardputerAIWiFiConnection) ⭐ 17 | 🐛 0 | 🌐 C++ | 📅 2024-04-14
* [Simple StopWatch](https://github.com/qubiX00/stopwatch-cardputer) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2024-02-16
* [M5Cardputer WebRadio Dutch version](https://github.com/rolandbreedveld/M5Cardputer_WebRadio_Dutch/) ⭐ 8 | 🐛 1 | 🌐 C++ | 📅 2024-07-26
* [Eliza Chatbot](https://github.com/Layer812/cardputer_eliza) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2024-07-21
* [Fake Windows XP UI](https://github.com/prashantkamdar/M5StickCPLUS.fakeWinXP) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2022-01-01
* [MDX (mxdrv) file Player for Cardputer](https://github.com/Layer812/mdxPC) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2025-10-26
* [VGM Player for Cardputer](https://github.com/Layer812/vgmPC) ⚠️ Archived

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
