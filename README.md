<div align="center">

# 📡 无线安全研究项目库

**ESP32 / ESP8266 / BW16 (RTL8720) 无线攻击与安全研究开源项目索引**

![Projects](https://img.shields.io/badge/项目总数-1963-blue) 
![Stars](https://img.shields.io/badge/采集日期-2026--11--17-green) 
![Boards](https://img.shields.io/badge/开发板-ESP32·ESP8266·BW16-orange) 
![Domains](https://img.shields.io/badge/领域-WiFi·蓝牙·射频-red)

> 本文档基于 GitHub 公开仓库搜索 API 自动采集整理，收录 **1963** 个去重开源项目，
> 覆盖 WiFi / 蓝牙 / 射频三大攻击领域，按开发板与攻击领域双维度归类。

</div>

## 📑 目录

- [免责声明](#️-免责声明-disclaimer)
- [项目概览](#-项目概览)
- [按开发板分类](#-按开发板分类)
  - [ESP32 系列（669）](#ESP32-系列)
  - [ESP8266（301）](#ESP8266)
  - [BW16 / RTL8720（39）](#BW16--RTL8720)
  - [未明确/通用（986）](#未明确通用)
- [按攻击领域分类](#-按攻击领域分类)
  - [WiFi 攻击（1776）](#WiFi-攻击)
  - [蓝牙攻击（390）](#蓝牙攻击)
  - [射频/RF 攻击（216）](#射频RF-攻击)
  - [攻击/安全工具(其他)（17）](#攻击安全工具其他)
- [数据说明](#-数据说明)
- [许可与使用](#-许可与使用)

## ⚠️ 免责声明（Disclaimer）

> [!IMPORTANT]
> 1. **仅供学习与研究**：本项目库所收录的全部内容均来自 GitHub 等公开渠道的开源项目，仅用于网络安全研究、学习交流与技术分析目的。
> 2. **授权测试**：文中提及的任何工具、固件与技术仅可用于**自己拥有或已获得明确书面授权**的设备与网络。对他人系统实施未授权测试/攻击属于违法行为。
> 3. **风险自担**：使用本项目库中任何项目造成的直接或间接后果（包括但不限于设备损坏、数据丢失、法律纠纷）由使用者本人承担。
> 4. **不构成背书**：收录不等于推荐或认可，项目代码未经安全审计，可能包含恶意代码或漏洞，使用前请自行审查源码。
> 5. **遵守法律**：请遵守您所在国家/地区的法律法规（如《网络安全法》《计算机信息系统安全保护条例》、美国 CFAA 等）。以任何形式将本项目内容用于非法用途，与本项目作者无关。

## 📊 项目概览

| 维度 | 数量 |
|---|---:|
| 项目总数（去重） | 1963 |
| 攻击/安全类项目 | 1873 |
| 带明确描述 | 1831 |

### 按攻击领域

| 领域 | 数量 |
|---|---:|
| WiFi 攻击 | 1776 |
| 蓝牙攻击 | 390 |
| 射频/RF 攻击 | 216 |
| 攻击/安全工具(其他) | 17 |

### 按开发板

| 开发板 | 数量 |
|---|---:|
| ESP32 系列 | 669 |
| ESP8266 | 301 |
| BW16 / RTL8720 | 39 |
| 未明确/通用 | 986 |

### 主要语言 Top 10

| 语言 | 数量 |
|---|---:|
| Python | 494 |
| C++ | 475 |
| 未标注 | 417 |
| C | 211 |
| Shell | 151 |
| HTML | 56 |
| JavaScript | 17 |
| Java | 16 |
| PHP | 13 |
| Kotlin | 12 |

## 🔧 按开发板分类

### ESP32 系列

> 共 **669** 个项目，按 Stars 降序排列。

| # | 项目 | Stars | 语言 | 简介 |
|---:|---|---:|---|---|
| 1 | [EmenstaNougat/ESP32-BlueJammer](https://github.com/EmenstaNougat/ESP32-BlueJammer) | 8,931 | — | The ESP32-BlueJammer (Bluetooth jammer, BLE jammer, WiFi jammer, RC jammer) disrupts 2.4GHz commu… |
| 2 | [geo-tp/ESP32-Bit-Pirate](https://github.com/geo-tp/ESP32-Bit-Pirate) | 6,396 | C++ | A Hardware Hacking Tool with Web-Based CLI That Speaks Every Protocol  |
| 3 | [cifertech/ESP32-DIV](https://github.com/cifertech/ESP32-DIV) | 4,350 | C++ | ESP32DIV is a multi-purpose wireless offensive and defensive toolkit powered by an ESP32 |
| 4 | [risinek/esp32-wifi-penetration-tool](https://github.com/risinek/esp32-wifi-penetration-tool) | 3,159 | C | Exploring possibilities of ESP32 platform to attack on nearby Wi-Fi networks. |
| 5 | [cifertech/nRFBox](https://github.com/cifertech/nRFBox) | 2,140 | C++ | Open-source ESP32-powered tool to scan, jam, spoof, and master BLE, Wi-Fi, and 2.4GHz networks. |
| 6 | [cifertech/RF-Clown](https://github.com/cifertech/RF-Clown) | 1,945 | C++ | BLE and Bluetooth Jammer with nRF24L01 and ESP32 |
| 7 | [JesseCHale/HaleHound-CYD](https://github.com/JesseCHale/HaleHound-CYD) | 1,926 | — | ESP32-DIV HaleHound Edition for Cheap Yellow Display - Multi-protocol offensive security toolkit |
| 8 | [7h30th3r0n3/Raspyjack](https://github.com/7h30th3r0n3/Raspyjack) | 1,343 | Python | Small offensive network toolkit for Raspberry Pi (+ Waveshare 1.44″ LCD HAT) and Cardputer Zero i… |
| 9 | [GhostESP-Revival/GhostESP](https://github.com/GhostESP-Revival/GhostESP) | 1,162 | C | The open-source wireless research platform for ESP32. |
| 10 | [W0rthlessS0ul/nRF24_jammer](https://github.com/W0rthlessS0ul/nRF24_jammer) | 1,022 | C | The nRF24 jammer is a powerful tool that requires an ESP32 and configurable numbers of NRF24 modu… |
| 11 | [Matheus-Garbelini/esp32_bluetooth_classic_sniffer](https://github.com/Matheus-Garbelini/esp32_bluetooth_classic_sniffer) | 617 | C | Active Bluetooth BR/EDR Sniffer/Injector as cheap as any ESP32 board can get. Works with Scapy ;-) |
| 12 | [Matheus-Garbelini/braktooth_esp32_bluetooth_classic_attacks](https://github.com/Matheus-Garbelini/braktooth_esp32_bluetooth_classic_attacks) | 599 | — | A Series of Baseband & LMP Exploits against Bluetooth Classic Controllers |
| 13 | [HighCodeh/TentacleOS](https://github.com/HighCodeh/TentacleOS) | 512 | C | Firmware High Boy |
| 14 | [mcore1976/cc1101-tool](https://github.com/mcore1976/cc1101-tool) | 489 | C++ | RF tool based on CC1101 module and Arduino Pro Micro 8VMHz/3.3V. Allows using CLI with human read… |
| 15 | [tesa-klebeband/ESP32-Deauther](https://github.com/tesa-klebeband/ESP32-Deauther) | 453 | C++ | A project for the ESP32 that allows you to deauthenticate stations connected to WiFi networks |
| 16 | [Alexxdal/ESP32WifiPhisher](https://github.com/Alexxdal/ESP32WifiPhisher) | 327 | C | Headless Wireless Penetration Testing on ESP32 |
| 17 | [EmenstaNougat/BlueJammer-V2](https://github.com/EmenstaNougat/BlueJammer-V2) | 322 | Batchfile | BlueJammer-V2 is a two-board RF research platform combining an ESP32 jamming engine with a BW16 5… |
| 18 | [Teapot174/ESP-HACK](https://github.com/Teapot174/ESP-HACK) | 313 | C++ | Open Source ESP32 Project for Pentesting. |
| 19 | [FernandoHansen666/ScaryRF-315-433mhz](https://github.com/FernandoHansen666/ScaryRF-315-433mhz) | 298 | C |  RF HACK • ESP32 + CC1101 • Sub-GHz RF Tool |
| 20 | [mmMikeKn/ESP32-WiFi-tool](https://github.com/mmMikeKn/ESP32-WiFi-tool) | 276 | C | ESP32 WiFi tool (router, sniffer, deauther) |
| 21 | [ESP-EOS/ESP32-WiFi-Sniffer](https://github.com/ESP-EOS/ESP32-WiFi-Sniffer) | 272 | C++ | Simple WiFi sniffer for boards based on the Espressif Systems ESP32 module |
| 22 | [justcallmekoko/MarauderCentauri](https://github.com/justcallmekoko/MarauderCentauri) | 238 | C++ | A suite of WiFi/Bluetooth offensive and defensive tools for the ESP32 and ESP8266 |
| 23 | [Hiktron/Hizmos](https://github.com/Hiktron/Hizmos) | 228 | C | ⚡ HIZMOS — An open-source, powerful alternative to Flipper Zero. Built on ESP32-S3, designed for … |
| 24 | [Electro-Gamma/ESP32-Quad-nRF24L01-Plus-Jammer-Multi-Band-2-4GHz-RF-Controller](https://github.com/Electro-Gamma/ESP32-Quad-nRF24L01-Plus-Jammer-Multi-Band-2-4GHz-RF-Controller) | 192 | C++ | ESP32-Quad-nRF24L01-Plus-Jammer is an open-source project for controlling four nRF24L01+ modules … |
| 25 | [pepeangell5/ESP32-TOOLS-PRO-480x320-V2.0](https://github.com/pepeangell5/ESP32-TOOLS-PRO-480x320-V2.0) | 191 | C++ | ESP32-TOOLS-PRO-480x320-V2.0 expande la V1.0 con soporte para módulos IR M5Stack y CC1101. Añade … |
| 26 | [ElectronicCats/Minino](https://github.com/ElectronicCats/Minino) | 183 | C++ | Minino is an original multiprotocol and multiband board made for sniffing, communicating, and att… |
| 27 | [dkyazzentwatwa/cypher-jammer-mini](https://github.com/dkyazzentwatwa/cypher-jammer-mini) | 182 | C++ | Tiny WiFi + Bluetooth Jammer w/ ESP32-C3 SuperMini |
| 28 | [0xless/433mhz_jam](https://github.com/0xless/433mhz_jam) | 163 | C++ | Simple WiFi controlled 433Mhz radio jammer based on ESP32/ESP8266 and FS1000A |
| 29 | [aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal) | 158 | C++ | A project that demonstrates how to execute an Evil Twin WiFi Hacking attack using the ESP32. The … |
| 30 | [simondankelmann/Esp32-SubGhz](https://github.com/simondankelmann/Esp32-SubGhz) | 145 | Kotlin |  |
| 31 | [Mxtiv/BlueJammer](https://github.com/Mxtiv/BlueJammer) | 136 | C++ | Simple BlueJammer using ESP32 and nRF24L01. For educational purposes only! |
| 32 | [T-vK/alexa-jammer](https://github.com/T-vK/alexa-jammer) | 135 | C++ | Jamming the Wifi connection and microphones of all Amazon Echo and Google Home devices surroundin… |
| 33 | [mjlee111/esp32_wifi_deauther](https://github.com/mjlee111/esp32_wifi_deauther) | 132 | C++ | A simple ESP32 based wifi hacking tool. Supports mini oled display & test circuit available. |
| 34 | [EmenstaNougat/C3Mini-BlueJammer](https://github.com/EmenstaNougat/C3Mini-BlueJammer) | 125 | — | The C3Mini-BlueJammer (MINI FORMFACTOR) (Bluetooth jammer, BLE jammer, WiFi jammer, RC jammer) di… |
| 35 | [JakeSwiz/flock-you-wifi-recon](https://github.com/JakeSwiz/flock-you-wifi-recon) | 118 | C++ | ESP32 firmware that catches Flock Safety ALPRs by the WiFi probes they spray trying to phone home… |
| 36 | [PNKP237/EHU32](https://github.com/PNKP237/EHU32) | 103 | C++ | ESP32-based bluetooth audio integration for Opel/Vauxhall vehicles. Control bluetooth audio sourc… |
| 37 | [OzInFl/WaveSentinelPublic---Squareline-Studio-UI-CC1101---ESP32](https://github.com/OzInFl/WaveSentinelPublic---Squareline-Studio-UI-CC1101---ESP32) | 100 | C | WT32-SC01-PLUS Module With SubGhz, Wifi and Bluetooth - Using CC1101, Able to play .sub files fro… |
| 38 | [W0rthlessS0ul/CC1101_jammer](https://github.com/W0rthlessS0ul/CC1101_jammer) | 99 | C | CC1101 Jammer is a powerful tool that requires an ESP32 and a CC1101 module to assemble. It is de… |
| 39 | [LxveAce/cyber-controller](https://github.com/LxveAce/cyber-controller) | 97 | Python | The all-in-one security hardware controller for cyberdecks & field deployments — flash, control &… |
| 40 | [infobyte/doggie](https://github.com/infobyte/doggie) | 83 | Rust | Welcome to the Doggie and EvilDoggie repository by Faraday Security! Doggie is a modular DIY CAN … |
| 41 | [colonelpanichacks/Esp32-oui-sniffer](https://github.com/colonelpanichacks/Esp32-oui-sniffer) | 81 | C++ | BLE/WiFi detection over mesh |
| 42 | [mahdamin/esp-idf-injection-ng](https://github.com/mahdamin/esp-idf-injection-ng) | 79 | C | Raw 802.11 frame injection on ESP-IDF v5+/v6+ via a one-command objcopy --weaken-symbol patch. En… |
| 43 | [Evil-Project-Team/ESP32-C5-J4CK3D](https://github.com/Evil-Project-Team/ESP32-C5-J4CK3D) | 73 | C | An advanced WiFi scanning and packet sniffing toolkit for the ESP32-C5, featuring a cyberpunk-ins… |
| 44 | [UserJoo9/WiFi-Nightmare](https://github.com/UserJoo9/WiFi-Nightmare) | 73 | Python |  WiFi-Nightmare: Hybrid WiFi Auditor. Python CLI Control \| ESP32/ESP8266 Hardware Acceleration \… |
| 45 | [michelangelomo/marauder-ui](https://github.com/michelangelomo/marauder-ui) | 69 | Vue | A modern web interface for the ESP32 Marauder firmware. |
| 46 | [dkyazzentwatwa/cypher-pulse](https://github.com/dkyazzentwatwa/cypher-pulse) | 65 | C++ | A versatile ESP32 sub-ghz jammer w/ 2 CC1101 radio modules. |
| 47 | [OCEANOFANYTHINGOFFICIAL/DevilTwin-NodeMCU](https://github.com/OCEANOFANYTHINGOFFICIAL/DevilTwin-NodeMCU) | 60 | C++ | ⚡ Perform Evil Twin Attack Using NodeMCU Board |
| 48 | [dkyazzentwatwa/cypher-jammer-3NRF24](https://github.com/dkyazzentwatwa/cypher-jammer-3NRF24) | 58 | C++ | An ESP32 BT + WiFi Jammer w/ 3 NRF24 modules. |
| 49 | [brianwalczak/BKFZ-SubGHz](https://github.com/brianwalczak/BKFZ-SubGHz) | 54 | C++ | A robust Arduino project for your ESP32 and CC1101 to capture, replay, and analyze nearby SubGHz … |
| 50 | [FadedCantCode/ESP32-wifi-hacking](https://github.com/FadedCantCode/ESP32-wifi-hacking) | 54 | — |  An universal tool for ESP32 platform to perform various Wi-Fi attacks.  |
| 51 | [HoneyHoneyTeam/ESP32.Marauder.Double.Barrel.5G.by.ESP32.C5](https://github.com/HoneyHoneyTeam/ESP32.Marauder.Double.Barrel.5G.by.ESP32.C5) | 53 | — | The version of Double Barrel 5G is packed with 1 * ESP32 chipset & 1 * ESP32 C5 chipset, GPS, Sub… |
| 52 | [arpitxp/Bruce-Smoochie-esp32](https://github.com/arpitxp/Bruce-Smoochie-esp32) | 48 | — | Standalone ESP32-S3 wireless pentesting deck built on Bruce firmware alternate to Flipper Zero, s… |
| 53 | [hadis898/esp32-jammer](https://github.com/hadis898/esp32-jammer) | 48 | — | ESP32-BlueJammer（蓝牙干扰器、BLE干扰器、WiFi干扰器、遥控干扰器）是一种针对2.4GHz通信频段的定向干扰设备。该设备基于ESP32主控芯片与nRF24模块构建，通过发射噪… |
| 54 | [Linuxndroid/Bluetooth-Ducky](https://github.com/Linuxndroid/Bluetooth-Ducky) | 47 | C++ | Bluetooth Ducky is a stealthy HID injection tool built on the ESP32 platform. It emulates a Bluet… |
| 55 | [nocomp/ESP32-Wi-Fi-Penetration-Tool](https://github.com/nocomp/ESP32-Wi-Fi-Penetration-Tool) | 46 | — | Wifi Hacking / DDOS Attacks for the ESP32 |
| 56 | [shizakken/cheetah](https://github.com/shizakken/cheetah) | 44 | Rust | Portable WiFi/Bluetooth/RF-433MHz hacking tool |
| 57 | [soynx/Hacking-PenTesting-Utils](https://github.com/soynx/Hacking-PenTesting-Utils) | 44 | HTML | A collection of scripts, documentation and HTML-Sites that can be used for penetration-testing |
| 58 | [ronaldstoner/ESP32-WifiJammerDectector](https://github.com/ronaldstoner/ESP32-WifiJammerDectector) | 41 | C++ | A simple ESP32 based WiFi detector that assists when jamming efforts may be attempted |
| 59 | [MuhamadJalalDev/ESP32-WiFi-Bluetooth-Jammer](https://github.com/MuhamadJalalDev/ESP32-WiFi-Bluetooth-Jammer) | 38 | — | Wi-Fi and Bluetooth jamming using an ESP32 microcontroller and NRF24L01 modules. This project inc… |
| 60 | [barryblueice/ESP32-Haptic-Precision-TouchPad](https://github.com/barryblueice/ESP32-Haptic-Precision-TouchPad) | 37 | C | Another touchpad hacking project, based on ESP32-S3 + Surface Laptop Studio 1964 Synaptics TouchPad. |
| 61 | [KEI4251/ESP32-Jammer-](https://github.com/KEI4251/ESP32-Jammer-) | 37 | — | KEI JAMMER – A personal project focused on experimenting with wireless security using ESP32 and N… |
| 62 | [b1scuitdev/E07xESP32C5](https://github.com/b1scuitdev/E07xESP32C5) | 36 | — | E07xESP32C5 is a Sub-GHz & ESP32-C5 module for Flipper Zero. It includes an EBYTE E07-433M20S (PA… |
| 63 | [pingequalab/cardputer-adv-hydra-rf](https://github.com/pingequalab/cardputer-adv-hydra-rf) | 36 | — | CC1101 + nRF24 dual-band RF expansion module for M5Stack Cardputer ADV. Supports 433/868/915 MHz … |
| 64 | [autrion/HeimdallRF](https://github.com/autrion/HeimdallRF) | 35 | C++ | HeimdallRF is an open-source, pocket-sized drone detector built on ESP32. It passively scans 868/… |
| 65 | [HoneyHoneyTeam/ESP32-Marauder-Double-Barrel](https://github.com/HoneyHoneyTeam/ESP32-Marauder-Double-Barrel) | 35 | — | The ESP32 Marauder Double Barrel includes two ESP32 chipsets, GPS, Sub-GHz (433 MHz) and an onboa… |
| 66 | [HoneyHoneyTeam/ESP32-Marauder-Double-Barrel-5G](https://github.com/HoneyHoneyTeam/ESP32-Marauder-Double-Barrel-5G) | 35 | — | 1 * ESP32 chipset & 1 * BW16 chipset, GPS, Sub-GHz (433 MHz) and an onboard battery. It works wit… |
| 67 | [SMH17/M5StackWiFiSniffer](https://github.com/SMH17/M5StackWiFiSniffer) | 35 | C++ | M5Stack WiFi packet sniffer for network analysis  |
| 68 | [usamahacker0/RF-Mirage](https://github.com/usamahacker0/RF-Mirage) | 35 | HTML | Sub Ghz Radio Frequency Penetration testing Device. |
| 69 | [Isonimus/adversary](https://github.com/Isonimus/adversary) | 34 | C++ | Red-team wireless pentesting firmware for the ESP32. Audit WiFi, BLE, IR, Sub-GHz, 2.4 GHz, RFID. |
| 70 | [valleytechsolutions/Skid-Detector](https://github.com/valleytechsolutions/Skid-Detector) | 34 | C++ | A wireless LED mood light and passive network security monitor built on the Seeed Studio XIAO ESP… |
| 71 | [yannpom/esp32sniffer](https://github.com/yannpom/esp32sniffer) | 34 | C | Use ESP32 to capture Wifi packets live with Wireshark |
| 72 | [chkndrp/ESPnRF24-Jammer](https://github.com/chkndrp/ESPnRF24-Jammer) | 33 | C++ | A low-power 2,4GHz wireless jammer based on ESP32 and nRF24LO1+PA+LNA (PlatformIO) |
| 73 | [trandi/esp32-thermal_printer](https://github.com/trandi/esp32-thermal_printer) | 33 | Arduino | Hack an Epson TM-T88 thermal printer (the ones that print receipts in a supermarket till) and rem… |
| 74 | [0day1day/Slave_I](https://github.com/0day1day/Slave_I) | 32 | C | Offensive-security firmware for the M5Stack Tab5 — browser-flashable Wi-Fi / BLE / 802.15.4 recon… |
| 75 | [dagnazty/Semi-Evil-M5Dial](https://github.com/dagnazty/Semi-Evil-M5Dial) | 32 | C++ | Advanced firmware for M5Dial devices, enabling WiFi captive portals, SSID management, Karma attac… |
| 76 | [HoneyHoneyTeam/ESP32-Marauder-5G-Apex-5-Module---For-Flipper-Zero](https://github.com/HoneyHoneyTeam/ESP32-Marauder-5G-Apex-5-Module---For-Flipper-Zero) | 32 | — | Apex 5 Module include 5 major functions into one single board, ESP32-C5 (5G Wifi Capabliity), dua… |
| 77 | [NicheSecTech/esp32-micropython-wifi-sniff-inject](https://github.com/NicheSecTech/esp32-micropython-wifi-sniff-inject) | 30 | Python | A ESP32 build of micropython v1.12 using ESP-IDF v4.0 that supports WiFi sniffing and injection. |
| 78 | [sha1cybr/esp32-cc1101-rf-caprep](https://github.com/sha1cybr/esp32-cc1101-rf-caprep) | 30 | C++ | ESP32 + CC1101 RF signal capture and replay tool. Record, analyze, and retransmit radio frequency… |
| 79 | [tesa-klebeband/ESP32-Deauther-ArduinoIDE](https://github.com/tesa-klebeband/ESP32-Deauther-ArduinoIDE) | 30 | C++ | A tool for the ESP32 with the ability to deauthenticate stations connected to WiFi networks |
| 80 | [ASP-29/ZeroX32](https://github.com/ASP-29/ZeroX32) | 29 | HTML | The Multi-tool device has a lot of feature,including WIFi,Bluetooth,HID,Infrared,Sub-Ghz,NRF24L01… |
| 81 | [HoneyHoneyTeam/3in1-WIFI-MultiBoard-with-Screen](https://github.com/HoneyHoneyTeam/3in1-WIFI-MultiBoard-with-Screen) | 29 | — | 3in1 WIFI board for Flipper Zero, ESP32 / Marauder + NRF24 + CC1101 by Honey Honey Lab |
| 82 | [neustarsabbir-max/ESP32-Evil-Twin-Captive-Portal](https://github.com/neustarsabbir-max/ESP32-Evil-Twin-Captive-Portal) | 28 | C++ | ESP32 WiFi Pentesting tool: Scans networks, creates Evil Twin APs, and captures credentials to in… |
| 83 | [Ishanoshada/Esp32-Deauth](https://github.com/Ishanoshada/Esp32-Deauth) | 27 | Python | A Python tool for Wi-Fi deauthentication attacks using ESP32 with webserver firmware |
| 84 | [MarauTech/ESP-GRABER](https://github.com/MarauTech/ESP-GRABER) | 27 | — | ESP-GRABBER is a powerful RF tool for ESP32 + CC1101. It can read, repeat, analyze, store, and ja… |
| 85 | [zeefaad/Jammer-433MHZ-ESP32](https://github.com/zeefaad/Jammer-433MHZ-ESP32) | 27 | C++ | The aim of this project is to design a 433MHz rf jammer using the CC1101 module and the ESP32 (ES… |
| 86 | [GeneralDussDuss/poseidon-tembed](https://github.com/GeneralDussDuss/poseidon-tembed) | 26 | Python | POSEIDON for the LilyGO T-Embed CC1101 Plus - 128 features, 5 onboard radios, browser flasher |
| 87 | [whitewhidow/bboink](https://github.com/whitewhidow/bboink) | 26 | C++ | WiFi handshake/PMKID capture firmware for ESP32 — LilyGo T-Embed CC1101, T-Display C5 & Waveshare… |
| 88 | [krakeninfosec/cyber-noise-blaster](https://github.com/krakeninfosec/cyber-noise-blaster) | 25 | HTML | Noise-based 2.4GHz jammer using ESP32 and NRF24L01 to disrupt Bluetooth, BLE, WiFi, and drone sig… |
| 89 | [PicoShot/ESP32-Deauther](https://github.com/PicoShot/ESP32-Deauther) | 24 | C++ | ESP32 WiFi Deauther - A DoS tool for ESP32 microcontrollers to disconnect   any 2.4GHz WiFi network. |
| 90 | [michelep/ESP32_BeaconSniffer](https://github.com/michelep/ESP32_BeaconSniffer) | 23 | C++ | Beacon monitor for ESP32 with OLED display |
| 91 | [Hex2424/esp32_deauth_patch](https://github.com/Hex2424/esp32_deauth_patch) | 22 | — | Fixed esp32 ieee80211.a lib esp_wifi_80211_tx() function sanity check filter of deauth packets |
| 92 | [justcallmekoko/ROTA](https://github.com/justcallmekoko/ROTA) | 21 | — | A WiFi enabled Xbox One rapid-fire mod |
| 93 | [richstokes/EvilPortal-M5Stack](https://github.com/richstokes/EvilPortal-M5Stack) | 21 | C | 😈 Evil Wi-Fi Portal implementation for the M5Stack Core S3 |
| 94 | [GthiN89/NucleusGateKeeper](https://github.com/GthiN89/NucleusGateKeeper) | 20 | C++ | Nucleus Gate Keeper is a specialized, compact, and cost-effective device for capturing Sub-GHz RF… |
| 95 | [Rubbles-eh/Direwolf_3.5CYD](https://github.com/Rubbles-eh/Direwolf_3.5CYD) | 20 | Python | Multi Device Case for 3.5" CYD with modular options for use with common firmware's (Halehound, Br… |
| 96 | [ccadic/HackZeGarage](https://github.com/ccadic/HackZeGarage) | 19 | C++ | ESP32-S2 and CC1101S 433Mhz usb stick to record and send car gates/garages data keys and open stuff |
| 97 | [GoatsAndMonkeys/monster_mesh](https://github.com/GoatsAndMonkeys/monster_mesh) | 19 | C++ | MonsterMesh: a Game Boy emulator, Gen-1 monster-battling RPG, and WiFi/BLE 'Pentest Pikachu' secu… |
| 98 | [syphr0/wifi32](https://github.com/syphr0/wifi32) | 19 | C++ | A wifi tool using the esp32 |
| 99 | [Th3-Priest/vigilance](https://github.com/Th3-Priest/vigilance) | 19 | C++ | Defensive surveillance HUD firmware for the LilyGo T-Embed CC1101 Plus (a Bruce fork). |
| 100 | [Mausam678/wifi-jammer-tool-for-esp32](https://github.com/Mausam678/wifi-jammer-tool-for-esp32) | 18 | — | This tool is a binary firmware designed for the ESP32 microcontroller, enabling it to perform WiF… |
| 101 | [zer0dayf/Flipper_Jam](https://github.com/zer0dayf/Flipper_Jam) | 18 | C++ | WiFi security research tool for Flipper Zero + ESP32. Deauth, beacon spam, evil twin, targeted & … |
| 102 | [CapibaraZero/BLESniffer](https://github.com/CapibaraZero/BLESniffer) | 17 | C++ | A bluetooth sniffer for ESP32 |
| 103 | [Coreymillia/Shark-Bait-add-on-Bruce-firmware-M5stackc-plus-](https://github.com/Coreymillia/Shark-Bait-add-on-Bruce-firmware-M5stackc-plus-) | 17 | — |   *Features:*  *Real-time WiFi threat detection* *4 targeted counter-attack methods* (Karma poiso… |
| 104 | [Retr0Kr0dy/BeamStalker](https://github.com/Retr0Kr0dy/BeamStalker) | 17 | C | BeamStalker is open-source firmware for esp based board designed for RF experimentation, encourag… |
| 105 | [huaminghuangtw/ESP32WiFiSnifferApp](https://github.com/huaminghuangtw/ESP32WiFiSnifferApp) | 16 | C++ | 📌 An interdisciplinary team project of the course Software Lab at Technical University of Munich … |
| 106 | [RadDad87/C3RB3RU5](https://github.com/RadDad87/C3RB3RU5) | 16 | HTML | C3RB3RU5 web flasher for CiferTech ESP32-DIV (V2, S3) — flash 2.4GHz WiFi/BLE/SubGHz pentest firm… |
| 107 | [CyberDuckyiq/IshtarRF](https://github.com/CyberDuckyiq/IshtarRF) | 15 | Python | IshtarRF — Sub-GHz rx/tx for ESP32 + CC1101. |
| 108 | [nturmose21/MKCOZMO-CONTROLLER](https://github.com/nturmose21/MKCOZMO-CONTROLLER) | 15 | C | A Cozmo-inspired mini robot built on ESP32 with continuous-rotation servos, Bluetooth Xbox contro… |
| 109 | [haKC-ai/CapturedPortal](https://github.com/haKC-ai/CapturedPortal) | 14 | C++ | An ESP32-based captive portal scanner and credential enumerator. Automatically detects hotel styl… |
| 110 | [lucianjames/ESP32WifiHacks](https://github.com/lucianjames/ESP32WifiHacks) | 14 | C++ | Easy to use WiFi tools for the ESP32. Graphical interface provided via IMGUI |
| 111 | [nistordarius26h-ship-it/esp32s3-brucey](https://github.com/nistordarius26h-ship-it/esp32s3-brucey) | 14 | — | Custom ESP32-S3 Bruce handheld with CC1101, NRF24L01+, PN532, SSD1306 OLED, MicroSD, IR and LiPo … |
| 112 | [pingequalab/cardputer-adv-cc1101-nrf24-auto-switch](https://github.com/pingequalab/cardputer-adv-cc1101-nrf24-auto-switch) | 14 | — | Open-source design reference for software-defined dual-band CC1101 + NRF24 RF expansion on M5Stac… |
| 113 | [usamahacker0/WIFI-Uchiha](https://github.com/usamahacker0/WIFI-Uchiha) | 14 | — | A WIFI Pentesting Tool ( WIFI Hacking ) with Powerfull tools. |
| 114 | [7wp81x/NRSuite-firmware](https://github.com/7wp81x/NRSuite-firmware) | 13 | C++ | ESP32 firmware for the NRSuite security research toolkit. Wi-Fi/BLE attack and capture modules (d… |
| 115 | [danya201272/ESP32-4M-WiFi-BLSerial-433Mhz](https://github.com/danya201272/ESP32-4M-WiFi-BLSerial-433Mhz) | 13 | C++ | ESP32 with app interface remoteXY and grab and sent code. Bruteforce Came and Nice. Have a Jammer… |
| 116 | [demining/Bluetooth-Attacks-CVE-2025-27840](https://github.com/demining/Bluetooth-Attacks-CVE-2025-27840) | 13 | Jupyter Notebook | Bitcoin Cryptanalysis: CVE-2025-27840 Vulnerability in ESP32 Microcontrollers Puts Billions of Io… |
| 117 | [omeryos/ESP32-WIFI-JAMMER](https://github.com/omeryos/ESP32-WIFI-JAMMER) | 13 | C++ | 2.4Ghz Wifi networks spot jamming device, utilizing ESP32 and nRF24L01+  |
| 118 | [StepSisStuck/ESP32-Wifi-Hacking](https://github.com/StepSisStuck/ESP32-Wifi-Hacking) | 13 | — | A guide on using ESP32 with Flipper Zero to get your wifi password |
| 119 | [godragun/Marauder-ESP32-S3](https://github.com/godragun/Marauder-ESP32-S3) | 12 | C++ | 📡 ESP32 Marauder v1.11.0 compiled for XIAO ESP32-S3 — WiFi security testing, BLE scanning, and et… |
| 120 | [imayavaramban11/2.4Ghz-Jammer](https://github.com/imayavaramban11/2.4Ghz-Jammer) | 12 | — | 2.4GHz RF Interference Generator — ESP32 + nRF24L01+ A dual-channel 2.4GHz RF noise generator usi… |
| 121 | [mildcrime/VARSYS](https://github.com/mildcrime/VARSYS) | 12 | C | Modular security-research firmware for LILYGO T-Embed CC1101 (ESP32-S3) — Flipper-class multitool… |
| 122 | [rgomez31UAQ/Poseidon-Cardputer-Adv_Firmware](https://github.com/rgomez31UAQ/Poseidon-Cardputer-Adv_Firmware) | 12 | C++ | Firmware de pruebas de penetración con más de 80 funciones para M5Stack Cardputer-Adv. WiFi, BLE,… |
| 123 | [simeononsecurity/esp32-wifi-canary](https://github.com/simeononsecurity/esp32-wifi-canary) | 12 | C++ | Passive ESP32 WiFi canary with RGB LED alerts for deauth spikes, suspicious duplicate SSIDs, open… |
| 124 | [at0m-b0mb/Trident-FlipperZero](https://github.com/at0m-b0mb/Trident-FlipperZero) | 11 | C | Trident — one Flipper Zero app for a 3-in-1 ESP32 + NRF24 + CC1101 expansion board: Wi-Fi/BT via … |
| 125 | [Epickitrolaz/nRF24-Jammer](https://github.com/Epickitrolaz/nRF24-Jammer) | 11 | C++ | A very simple, optimized ESP32 Wroom + nRF24 bluetooth jammer |
| 126 | [Farizrmd/esp32-serangan](https://github.com/Farizrmd/esp32-serangan) | 11 | C++ | ESP32 BT/WiFi Attack Tool v2 MEGA - 16 attack modes (BLE Scanner, Deauth, A2DP Jam, Spam, WiFi De… |
| 127 | [GeneralDussDuss/davey-jones](https://github.com/GeneralDussDuss/davey-jones) | 11 | C | Multi-radio pentesting firmware for Arduino Nesso N1 (ESP32-C6 + SX1262). WiFi/BLE/Sub-GHz/IR/Zig… |
| 128 | [Mr-C4T/EVIL-ESP-AP](https://github.com/Mr-C4T/EVIL-ESP-AP) | 11 | C++ | Rogue wifi AP with fake captive portal login page for pentesting with ESP32. |
| 129 | [nhatprx/Deauther-RTL8720DN-ESP32S3](https://github.com/nhatprx/Deauther-RTL8720DN-ESP32S3) | 11 | C++ | WiFi deauthentication tool for ESP32S3 and RTL8720DN supporting both 2.4GHz and 5GHz bands. Educa… |
| 130 | [romankalyna/RFsquek](https://github.com/romankalyna/RFsquek) | 11 | C++ | ESP32 + CC1101 RF spectrum scanner and Morse communicator |
| 131 | [0xtosh/t-dongle-s3-wifi-guard](https://github.com/0xtosh/t-dongle-s3-wifi-guard) | 10 | PowerShell | Portable passive deauthentication attack detector for 2.4Ghz WiFi networks for LilyGO T-Dongle-S3 |
| 132 | [darkLabz001/ghosttap](https://github.com/darkLabz001/ghosttap) | 10 | C | GhostTap — Wi-Fi/BLE/Zigbee pentest field unit for the Waveshare ESP32-C5-LCD-1.47: scan, sniff, … |
| 133 | [iCounterBOX/ESP32_WiFi_SNIFF_BLE_ANDROID-APP_PathFinderLE_V01](https://github.com/iCounterBOX/ESP32_WiFi_SNIFF_BLE_ANDROID-APP_PathFinderLE_V01) | 10 | C++ | esp32 as wifi Sniffer connected via BLE to Android-App |
| 134 | [Lab217MX/Kraken-Kit](https://github.com/Lab217MX/Kraken-Kit) | 10 | Python | PCB personalizada que expande el proyecto [ESP32-Bus-Pirate](https://github.com/geo-tp/ESP32-Bus-… |
| 135 | [lierda-iot/esp32_lora_driver](https://github.com/lierda-iot/esp32_lora_driver) | 10 | C | ESP-IDF driver for Semtech LR2021 / LR20xx radios: FLRC at 2.6 Mbit/s air rate, about 2.2 Mbit/s … |
| 136 | [rgomez31UAQ/Poseidon_Cardputer-ADV_Firmware](https://github.com/rgomez31UAQ/Poseidon_Cardputer-ADV_Firmware) | 10 | — | Firmware de pruebas de penetración con más de 80 funciones para M5Stack Cardputer-Adv. WiFi, BLE,… |
| 137 | [tworjaga/ESP32Gotchi](https://github.com/tworjaga/ESP32Gotchi) | 10 | C++ | Autonomous WPA/WPA2 handshake sniffer and AP logger for ESP32. Captures 4-way EAPOL exchanges to … |
| 138 | [davlaura/void-esp32-jammer](https://github.com/davlaura/void-esp32-jammer) | 9 | C++ | Project "void": Jammer based on ESP32 and nRF24L01 module that generates interference in the Blue… |
| 139 | [girs1982/GanstaWifiCyberPunker](https://github.com/girs1982/GanstaWifiCyberPunker) | 9 | — | GanstaWifiCyberPunker it firmware on Cardputer M5Stack for crack wifi networks  |
| 140 | [koua29/bruce-ble-finder](https://github.com/koua29/bruce-ble-finder) | 9 | JavaScript | Traqueur de proximité Bluetooth (radar RSSI, script JS) pour le firmware Bruce — LilyGO T-Embed C… |
| 141 | [mynameisnotjohnny/the-jester](https://github.com/mynameisnotjohnny/the-jester) | 9 | C++ | A fully open-source Bluetooth and BLE jammer based on the RF-Clown project by cifertech. This imp… |
| 142 | [rusyln/ESP32-S3-ePaper-1.54-SigBin](https://github.com/rusyln/ESP32-S3-ePaper-1.54-SigBin) | 9 | — | Passive WiFi & BLE recon on a 1.54" e-paper display. PCAP harvest, handshake/PMKID capture, deaut… |
| 143 | [Dextelktro/Black-Crow-ESP32-C5-Firmware](https://github.com/Dextelktro/Black-Crow-ESP32-C5-Firmware) | 8 | C++ | BC Firmware ESP32 C5-Deauth dengan Nuker untuk 2.4Ghz dan 5Ghz yang dikendalikan oleh BLE dengan … |
| 144 | [Evil0ctopus/wigglefish](https://github.com/Evil0ctopus/wigglefish) | 8 | Kotlin | Passive Wi-Fi/BLE field scanner: ESP32-C5 + Android USB controller — metadata-only, authorized ob… |
| 145 | [IT-DIVIDMARK/ESP32-wifi-deauther](https://github.com/IT-DIVIDMARK/ESP32-wifi-deauther) | 8 | C++ | This project utilizes the ESP32 microcontroller to create a powerful Wi-Fi deauther tool. It allo… |
| 146 | [LuxStatera/flock-hunter-cyd-wifi](https://github.com/LuxStatera/flock-hunter-cyd-wifi) | 8 | C++ | WiFi-based Flock Safety camera detector for ESP32 CYD. Passively sniffs 32 OUI prefixes with PCAP… |
| 147 | [Muhammednihalmp/RF-Jammer](https://github.com/Muhammednihalmp/RF-Jammer) | 8 | C++ | ESP32-based RF Jammer  |
| 148 | [nistordarius26h-ship-it/esp32jamm](https://github.com/nistordarius26h-ship-it/esp32jamm) | 8 | C++ | ESP32 Multi-Protocol Wireless Sniffing Platform for passive Wi-Fi, Bluetooth, BLE, and RF signal … |
| 149 | [omairtemurian/Roadstar-TV---IR](https://github.com/omairtemurian/Roadstar-TV---IR) | 8 | — | 📡 Road Star RF Controller for Lilygo T-Embed This repository contains the firmware and web-based … |
| 150 | [rajtilak-2020/ESP32-wifi-sniffer-tool](https://github.com/rajtilak-2020/ESP32-wifi-sniffer-tool) | 8 | C++ | A real-time Wi-Fi packet sniffer built using ESP32. Captures MAC addresses, signal strength (RSSI… |
| 151 | [Theus-Vieira/jammer_2.4ghz_wifi_bluetooth](https://github.com/Theus-Vieira/jammer_2.4ghz_wifi_bluetooth) | 8 | C++ | Projeto de Jammer 2.4 GHz wifi e bluetooth utilizando um ESP32S WROOM e dois módulos nRF24L01. Pr… |
| 152 | [ZeroNodeDIY/gate-control](https://github.com/ZeroNodeDIY/gate-control) | 8 | — | ESP32-C3 Super Mini and CC1101 Sub-GHz gate controller with OLED interface, RAW OOK/ASK signal ca… |
| 153 | [26zl/gadgets-tools](https://github.com/26zl/gadgets-tools) | 7 | Shell | Tools and firmware for various Flipper Zero / ESP32 / phone pentest gadgets — one folder per devi… |
| 154 | [5h4d0wn1k/h2-ble-tracker](https://github.com/5h4d0wn1k/h2-ble-tracker) | 7 | C++ | BLE tracker and sniffer - Bluetooth Low Energy advertising scanning and device fingerprinting. |
| 155 | [aingram702/SubGHzuki](https://github.com/aingram702/SubGHzuki) | 7 | C++ | A firmware project for the LilyGO T-Embed CC1101 Plus ESP32-S3 |
| 156 | [ANIMAALS/WatchDog-2.4](https://github.com/ANIMAALS/WatchDog-2.4) | 7 | C++ | Portable 2.4 GHz wireless security analyser — ESP32 + nRF24L01. Jammer detection, BLE tracker ID,… |
| 157 | [bollgio/BruceIRF](https://github.com/bollgio/BruceIRF) | 7 | C++ | BruceIRF - ESP32 firmware fork (Bruce 1.16) with Universal IR + RF modules, RF+IR Dual Detector, … |
| 158 | [cx693/Rust_ESP32_Dome](https://github.com/cx693/Rust_ESP32_Dome) | 7 | Rust | A collection of Rust bare-metal examples for ESP32 using the `esp-hal` framework. Covers GPIO, UA… |
| 159 | [Eberth-sys/Deauth-Alert-WiFi-IoT-System](https://github.com/Eberth-sys/Deauth-Alert-WiFi-IoT-System) | 7 | TypeScript | Open-source defensive IoT system for real-time detection and alerting of Wi-Fi 802.11 deauthentic… |
| 160 | [Ghael-V/LilyOS](https://github.com/Ghael-V/LilyOS) | 7 | C | Custom LVGL-based firmware for the LilyGo T-Embed CC1101 (ESP32-S3): WiFi auditing (deauth, hands… |
| 161 | [greatgaga/EspViking](https://github.com/greatgaga/EspViking) | 7 | C++ | Firmware made for ESP32 that is made for wifi pentesting. |
| 162 | [JEONTAEMIN2007/Esp32-WiFi-Hacking](https://github.com/JEONTAEMIN2007/Esp32-WiFi-Hacking) | 7 | C++ | Google account hijacking |
| 163 | [KaSaNaa/ESP32-WiFi-Sniffer](https://github.com/KaSaNaa/ESP32-WiFi-Sniffer) | 7 | C |  this tool passively captures and logs probe request packets to demonstrate the potential securit… |
| 164 | [leonrinkel/esp32-mac-sniffer](https://github.com/leonrinkel/esp32-mac-sniffer) | 7 | C |  |
| 165 | [lraton/ESP32-Wardriving-Deauther](https://github.com/lraton/ESP32-Wardriving-Deauther) | 7 | C | ESP32-Wardriving-Deauther is a WiFi security testing tool for the ESP32 platform, allowing for Wi… |
| 166 | [MOG-Developing/MOG-BLEJAMMER](https://github.com/MOG-Developing/MOG-BLEJAMMER) | 7 | C++ | MOG-BLEJAMMER |
| 167 | [MuhamadJalalDev/MIM-attack-ESP32](https://github.com/MuhamadJalalDev/MIM-attack-ESP32) | 7 | C++ | ever thought about hacking wifi passwords with the esp32 ? well now you can  |
| 168 | [Snifi0/Sniffer](https://github.com/Snifi0/Sniffer) | 7 | — | Multitool! |
| 169 | [tasos12/ESP32_WiFiSniffer_with_OLED](https://github.com/tasos12/ESP32_WiFiSniffer_with_OLED) | 7 | C | ESP32 wifi sniffer using oled to select the network to sniff built with arduino core for esp32 |
| 170 | [0xIDA/ESP-SEC-TOOL](https://github.com/0xIDA/ESP-SEC-TOOL) | 6 | C | ESP32 WiFi/BLE Security Testing Toolkit - portable wireless auditing tool with mobile web dashboard |
| 171 | [5h4d0wn1k/h13-wifi-jammer](https://github.com/5h4d0wn1k/h13-wifi-jammer) | 6 | C++ | Wi-Fi jamming and resilience research - interference testing against own-lab networks. |
| 172 | [5h4d0wn1k/h14-lora-attack](https://github.com/5h4d0wn1k/h14-lora-attack) | 6 | C++ | LoRa RF security toolkit - packet capture, replay and demodulation on 433/868 MHz. |
| 173 | [5h4d0wn1k/h3-zigbee-sniffer](https://github.com/5h4d0wn1k/h3-zigbee-sniffer) | 6 | C++ | Zigbee/Thread IEEE 802.15.4 packet sniffer for ESP32-C6 — frame capture, header decoding, device … |
| 174 | [5h4d0wn1k/h5-433-replay](https://github.com/5h4d0wn1k/h5-433-replay) | 6 | C++ | 433 MHz RF replay toolkit - capture and retransmit sub-GHz remote signals for hardware testing. |
| 175 | [5h4d0wn1k/w3-probe-resp](https://github.com/5h4d0wn1k/w3-probe-resp) | 6 | Python | Wi-Fi probe-request responder for wireless security research — ESP32-C6 promiscuous sniffer with … |
| 176 | [5h4d0wn1k/w9-ble-spoofer](https://github.com/5h4d0wn1k/w9-ble-spoofer) | 6 | Python | BLE spoofer for wireless security research — byte-exact ADV PDU forging, CRC-24 validation, lab-s… |
| 177 | [Axagt40/Vandeta](https://github.com/Axagt40/Vandeta) | 6 | C++ | Bruce (1.16.1) modded for the LilyGo T-Embed CC1101 Plus |
| 178 | [AyushGorlawar/ESP-Hidden-Features](https://github.com/AyushGorlawar/ESP-Hidden-Features) | 6 | C++ | Explore hidden features, stealth tricks, and ethical hacks using ESP8266/ESP32 — beyond basic IoT… |
| 179 | [bman46/deauth-esp-rs](https://github.com/bman46/deauth-esp-rs) | 6 | Rust | A rust based WiFi deauther for ESP32. |
| 180 | [BrotherOfJhonny/bleak](https://github.com/BrotherOfJhonny/bleak) | 6 | Python | BLEAK — Bluetooth Link Exploitation & Attack Knowledgebase, Plataforma de pentest Bluetooth BLE/C… |
| 181 | [darkLabz001/grimoire](https://github.com/darkLabz001/grimoire) | 6 | C++ | Self-contained ESP32-C5 Wi-Fi recon and attack console running inside a wizard pet: dual-band (2.… |
| 182 | [ipv4shh/ESPTOOL2](https://github.com/ipv4shh/ESPTOOL2) | 6 | C++ | ESPTOOL2 — Multi-band wireless toolkit based on ESP32. Wi-Fi & BLE attacks, web interface, Master… |
| 183 | [Isonimus/wifi-sapper](https://github.com/Isonimus/wifi-sapper) | 6 | C++ | Autonomous handshake hunter for the ESP-32. |
| 184 | [krishrp0001/esp32-wifi-hacking](https://github.com/krishrp0001/esp32-wifi-hacking) | 6 | — | wifi deauther, wifi penetration tool, evil twin attack, air crack, honeypot wifi hacking, fake wifi |
| 185 | [leingangzj/yui](https://github.com/leingangzj/yui) | 6 | C++ | Pocket comms + pentest companion firmware for the M5Stack Cardputer ADV. Drives a Kenwood TH-D75 … |
| 186 | [mineiwik/CoralWave](https://github.com/mineiwik/CoralWave) | 6 | — | Custom Sub-GHz Transceiver Gateway |
| 187 | [PanduTechLab/Bluetooth-Wifi-scanner-Jammer](https://github.com/PanduTechLab/Bluetooth-Wifi-scanner-Jammer) | 6 | C++ | A portable ESP32-based wireless research tool with BLE, Wi-Fi, and 2.4GHz nRF24 utilities on a 12… |
| 188 | [patrickhaahr/esp32-wifi-sniffer](https://github.com/patrickhaahr/esp32-wifi-sniffer) | 6 | Rust | ESP32 WiFi device tracking system with RSSI-based trilateration. Real-time web dashboard for indo… |
| 189 | [prabhatsoni14/ESP32-WiFi-PenTest-Tool](https://github.com/prabhatsoni14/ESP32-WiFi-PenTest-Tool) | 6 | C++ | Educational ESP32 tool demonstrating WiFi security vulnerabilities — Evil Twin, deauthentication,… |
| 190 | [s-r-e-e-r-a-j/VALAK](https://github.com/s-r-e-e-r-a-j/VALAK) | 6 | C++ | VALAK is a powerful ESP32-based tool that performs real Evil Twin attacks by creating identical c… |
| 191 | [xClem123/ESP32-BLE-FruitBuster](https://github.com/xClem123/ESP32-BLE-FruitBuster) | 6 | C++ | ESP32 BLE project sending malicious packets mimicking Apple devices (AirPods, AppleTV, etc.) or d… |
| 192 | [xiaohe4966/esp32-wifi-sniffer](https://github.com/xiaohe4966/esp32-wifi-sniffer) | 6 | C++ | 基于 ESP32-S3 (支持 2.4GHz/5GHz 双频) 的 WiFi 抓包与字典攻击开源工具，用于无线安全研究。 |
| 193 | [YM2992/Reverb](https://github.com/YM2992/Reverb) | 6 | TypeScript | A web interface to view and replay sub-GHz RF signals, connecting to your ESP32/CC1101 device ove… |
| 194 | [z2labs/Sniff-Sight](https://github.com/z2labs/Sniff-Sight) | 6 | Python | Packet sniffer + RF spectrum side by side: pair 802.15.4/BLE/Wi-Fi packets with their RF bursts u… |
| 195 | [5h4d0wn1k/h10-usb-hid](https://github.com/5h4d0wn1k/h10-usb-hid) | 5 | C++ | USB HID attack tool - programmable keystroke-injection payloads for hardware security testing. |
| 196 | [5h4d0wn1k/h4-mousejack](https://github.com/5h4d0wn1k/h4-mousejack) | 5 | C++ | nRF24 protocol-hacking research lab — ESP32 + nRF24L01+ firmware that scans all 41 channels, snif… |
| 197 | [aidevsurya/ESP8266-Captive-Portal](https://github.com/aidevsurya/ESP8266-Captive-Portal) | 5 | C++ | This is simple program for NodeMCU, ESP8266, ESP32, ESP-12 F/E to perform Captive Portal Attack f… |
| 198 | [Albertokeroro/edge-ai-lora-anomaly-detection](https://github.com/Albertokeroro/edge-ai-lora-anomaly-detection) | 5 | C | Real-time Edge AI LoRa jamming and RF anomaly detector for the Heltec (V3/V4) ESP32-S3 |
| 199 | [ayhamal/ESP32-Wifi-Sniffer](https://github.com/ayhamal/ESP32-Wifi-Sniffer) | 5 | C++ | Wifi sniffer builded with Arduino Framework on board ESP-WROOM-32D (esp32doit-devkit-v1) |
| 200 | [Bulletb8/ESP32-DIV-CarPopper](https://github.com/Bulletb8/ESP32-DIV-CarPopper) | 5 | C++ | Fork of cifertech/ESP32-DIV with Car Popper RKE module added to SubGHz menu |
| 201 | [CyberDuckyiq/IshtarRF-Android](https://github.com/CyberDuckyiq/IshtarRF-Android) | 5 | Kotlin | Android app (Kotlin + Jetpack Compose) for an ESP32 + CC1101 Sub-GHz   RF tool over USB-OTG — rec… |
| 202 | [DX-PE/SurveillanceHound](https://github.com/DX-PE/SurveillanceHound) | 5 | C++ | ESP32 WiFi/BLE Sniffer Game, your pet hound sniffs out surveillance devices like Flock and many m… |
| 203 | [enesehs/esp32-jammer](https://github.com/enesehs/esp32-jammer) | 5 | — | ESP32 Bluetooth Wifi Jammer |
| 204 | [ESP32w/ESP32-Hack-device-](https://github.com/ESP32w/ESP32-Hack-device-) | 5 | C++ | HACK DEVICE ESP32 v2.0.1 |
| 205 | [JeonghunLee/wifisniffer](https://github.com/JeonghunLee/wifisniffer) | 5 | C | ESP32-S3 based on WIFI Sniffer and ReadTheDocs  |
| 206 | [kariemoorman/cyd-wifi-sniffer](https://github.com/kariemoorman/cyd-wifi-sniffer) | 5 | C | WiFi packet sniffer and network traffic classifier for the ESP32-3248S035 (CYD) board. |
| 207 | [Mohnki/dragotchi-flipper](https://github.com/Mohnki/dragotchi-flipper) | 5 | C | Dragotchi — a dragon virtual pet for the Flipper Zero that hunts the real airwaves (sub-GHz + opt… |
| 208 | [Ohminecraft/ESP32-Attack-Tool](https://github.com/Ohminecraft/ESP32-Attack-Tool) | 5 | C | WiFi/BLE Testing/Offensive Tool/Defensive Tool |
| 209 | [oliverstraus246-beep/the-reaper](https://github.com/oliverstraus246-beep/the-reaper) | 5 | C++ | Multi-band ESP32-S3 wireless pentesting toolkit - WiFi, BLE, 2.4GHz, Sub-GHz, IR, RFID/NFC, GPS. … |
| 210 | [oshri-almog/esp32c5-wireshark-sniffer](https://github.com/oshri-almog/esp32c5-wireshark-sniffer) | 5 | Python | ESP32-C5 2.4Ghz + 5.8Ghz Wi-Fi, Zigbee or Thread sniffer interfaces for Wireshark  |
| 211 | [Scissors2099/ScissorsJammer-v6.5-Spectre-Trident-Edition](https://github.com/Scissors2099/ScissorsJammer-v6.5-Spectre-Trident-Edition) | 5 | C++ | Estación portátil de auditoría analítica y defensa de capa física en 2.4 GHz basada en ESP32 y nR… |
| 212 | [sftp-nik/ESP32-WiFi-Jammer](https://github.com/sftp-nik/ESP32-WiFi-Jammer) | 5 | CMake | This is the tool used in Wi-Fi penetration.   |
| 213 | [SomnathGorai/ESP32-Marauder-WiFi-Tool](https://github.com/SomnathGorai/ESP32-Marauder-WiFi-Tool) | 5 | C++ | ESP32-based portable WiFi hacking tool using a 1.8" TFT SPI LCD display |
| 214 | [Thenewmanator15/esp32c6-sniffer](https://github.com/Thenewmanator15/esp32c6-sniffer) | 5 | Python | Passive tri-radio wireless sniffer on an ESP32-C6 (802.15.4 / Wi-Fi / BLE), streaming into Wiresh… |
| 215 | [UruxUs/ANKA-ESP32-MultiTool](https://github.com/UruxUs/ANKA-ESP32-MultiTool) | 5 | C++ | ANKA: ESP32 + SSD1306 OLED Security Tool. Includes WiFi Deauth/Beacon Spam, BLE Spam/Scan & IR. |
| 216 | [yuno009/ESP32S3-USB-Keyboard-To-BLE](https://github.com/yuno009/ESP32S3-USB-Keyboard-To-BLE) | 5 | C++ | 🔄 Transform any USB keyboard into a Bluetooth device with ESP32-S3, allowing seamless connections… |
| 217 | [abir1999/Packet-Sniffer-ESP32](https://github.com/abir1999/Packet-Sniffer-ESP32) | 4 | C++ | Use an ESP32 to sniff WIFI packets |
| 218 | [aMiscreant/ESP32c3-Super-Mini-Scipts](https://github.com/aMiscreant/ESP32c3-Super-Mini-Scipts) | 4 | C | This repository contains a collection of Wi-Fi/Encryption/Bluetooth related scripts designed for … |
| 219 | [Bulletb8/esp32c5-wifi-pentool](https://github.com/Bulletb8/esp32c5-wifi-pentool) | 4 | C++ | ESP32-C5 dual-band 2.4/5GHz WiFi pentesting tool. Scan, deauth, capture, handshake harvest. Softw… |
| 220 | [CapibaraZero/WifiSniffer](https://github.com/CapibaraZero/WifiSniffer) | 4 | C++ | An ESP32 Wifi Sniffer |
| 221 | [chetansaini53/ESP32-C6-Threat-Radar](https://github.com/chetansaini53/ESP32-C6-Threat-Radar) | 4 | C++ | Passive defensive wireless threat radar for ESP32-C6 (2.4GHz) - detects WiFi deauth, pwnagotchi &… |
| 222 | [codebyant/esphome-rf-cloner](https://github.com/codebyant/esphome-rf-cloner) | 4 | Python | Learn and replay sub-GHz RF remote commands at runtime on ESP32 + CC1101, with a Home Assistant i… |
| 223 | [Coreymillia/CYDSentinel](https://github.com/Coreymillia/CYDSentinel) | 4 | C++ | Touchscreen WiFi/BLE scanner, sniffer, and NOAA radar workspace for the ESP32-2432S028R Cheap Yel… |
| 224 | [corporation9/Lifeband-vxOS-WiFi-BLE-Sniffer](https://github.com/corporation9/Lifeband-vxOS-WiFi-BLE-Sniffer) | 4 | C | It detects wireless ESP32 chips as well as Bluetooth Low Energy devices and collects information … |
| 225 | [DIY-Learn/ESP32-DIV](https://github.com/DIY-Learn/ESP32-DIV) | 4 | C | ESP32-DIV: DIY multi‑tool with WiFi, Bluetooth, IR, 2.4GHz attacks and full menu system. |
| 226 | [dnlrs/willy-board](https://github.com/dnlrs/willy-board) | 4 | C++ | ESP32 Probe Request Sniffer |
| 227 | [edward62740/DEFENDER](https://github.com/edward62740/DEFENDER) | 4 | C++ | This is a 2.4GHz Wi-Fi scanner for estimating channel usage and detect deauthentication attacks. … |
| 228 | [eokgnah/SmartED-to-MQTT-with-ESP32](https://github.com/eokgnah/SmartED-to-MQTT-with-ESP32) | 4 | C++ | SmartED CAN-BUS Data Sniffer and Sender to MQTT Server over ESP32 WIFI |
| 229 | [er2g/esp32-wifi-penetration-tool](https://github.com/er2g/esp32-wifi-penetration-tool) | 4 | C | ESP32-S3 WiFi penetration testing tool - auto handshake capture, single target attack, SPIFFS sto… |
| 230 | [Erennkrb/ESP32-and-ESP8266-DeAuthWifi](https://github.com/Erennkrb/ESP32-and-ESP8266-DeAuthWifi) | 4 | C++ | Educational proof-of-concept demonstrating Wi-Fi deauthentication attacks using ESP32 and ESP8266… |
| 231 | [fatihyldz58/nRF24-BT-Jammer](https://github.com/fatihyldz58/nRF24-BT-Jammer) | 4 | C++ | A powerful 2.4GHz RF testing and Bluetooth interference research tool using ESP32 and dual nRF24L… |
| 232 | [Hexamora/ESP32-Wifi-Jammer](https://github.com/Hexamora/ESP32-Wifi-Jammer) | 4 | — | 📡 ESP32 + NRF24L01 PA LNA 2.4GHz RF tester \| No-solder breadboard build \| Webserver control int… |
| 233 | [kqzalf/Rootsignal-ESP32](https://github.com/kqzalf/Rootsignal-ESP32) | 4 | Python | RootSignal-ESP32 is a lightweight, MicroPython-based wireless anomaly detector that runs on moder… |
| 234 | [krolyxon/orion-rf](https://github.com/krolyxon/orion-rf) | 4 | C++ | Portable RF and wireless toolkit built on ESP32-S3 |
| 235 | [luketheluckyloner/nRF24_jammer](https://github.com/luketheluckyloner/nRF24_jammer) | 4 | — | The nRF24 jammer is a powerful tool that requires an ESP32 and configurable numbers of NRF24 modu… |
| 236 | [NodeLabs13/NETHER](https://github.com/NodeLabs13/NETHER) | 4 | — | A robust security testing firmware for ESP32 boards (Lolin32/ESP32). Designed for educational pur… |
| 237 | [omwardhanM/Bluetooth-Wifi-Jammer](https://github.com/omwardhanM/Bluetooth-Wifi-Jammer) | 4 | C++ | Bluetooth, BLE, Wifi - 2.4Ghz ISM Band Jammer / Interference Project with ESP32 and nRf24 |
| 238 | [random-robbie/Flipper-SubGhz-RAW-to-ESP32-C-Array-Converter](https://github.com/random-robbie/Flipper-SubGhz-RAW-to-ESP32-C-Array-Converter) | 4 | Python | Flipper SubGhz RAW to ESP32 C Array Converter |
| 239 | [samdvl/Esp8266-Wifi-Sniffer](https://github.com/samdvl/Esp8266-Wifi-Sniffer) | 4 | C | This software make it possible to scan wifi devices with the esp8266. It contols the TTGO 0.91 ol… |
| 240 | [ssnrshnn/artemisz](https://github.com/ssnrshnn/artemisz) | 4 | C++ | ESP32 Based Wifi Hacking Tool |
| 241 | [the0r4cle/JasperRF](https://github.com/the0r4cle/JasperRF) | 4 | C++ | ESP32 + CC1101 sub-GHz RF multi-tool with web UI. Sniff, record, replay, brute-force (De Bruijn),… |
| 242 | [torgeirn/tvlift-hack](https://github.com/torgeirn/tvlift-hack) | 4 | — | Trying to hack my not-smart tv-lift to be controlled by HomeAssistant |
| 243 | [Trojan1Hex/ESP32-2.4GHz-BLE-WiFi-Jammer-Educational-Project](https://github.com/Trojan1Hex/ESP32-2.4GHz-BLE-WiFi-Jammer-Educational-Project) | 4 | — | This project is developed strictly for educational purposes. Do not use it for unethical or illeg… |
| 244 | [VinavilDev/DeautherDetector](https://github.com/VinavilDev/DeautherDetector) | 4 | C++ | A lightweight and customizable ESP32-based tool to detect deauthentication packets in WiFi networks. |
| 245 | [WR117H/WiFiDucky](https://github.com/WR117H/WiFiDucky) | 4 | C++ | A tool used for HID attacks with an ESP32-S2 |
| 246 | [Zebratic/esp32-433mhz-rf-controller](https://github.com/Zebratic/esp32-433mhz-rf-controller) | 4 | C | ESP32 RF Controller & Repeater - Trigger Sub GHz signals using a RESTful API |
| 247 | [0xnhsec/Luminescence-Network-Sniffer](https://github.com/0xnhsec/Luminescence-Network-Sniffer) | 3 | C++ | ESP32-based Rogue AP with HTTP sniffing capability. Close in concept to Evil Twin crafted for WiF… |
| 248 | [adipundir/deauther-dual-band-god-mode](https://github.com/adipundir/deauther-dual-band-god-mode) | 3 | C | Dual-band (2.4/5 GHz) WiFi deauther firmware for the ESP32-C5, with a phone-hosted web UI for liv… |
| 249 | [Ahmed-Ahmed16/variOne-2](https://github.com/Ahmed-Ahmed16/variOne-2) | 3 | C++ | Handheld ESP32-S3 wireless-security awareness device. Wi-Fi, BLE, Sub-GHz, NFC, IR & more. CIC Ne… |
| 250 | [AlbanoL/Sniffer_WiFi_ESP32_LoRa_TTN](https://github.com/AlbanoL/Sniffer_WiFi_ESP32_LoRa_TTN) | 3 | — | Contador de pessoas usando análise de pacotes WiFi. Projeto para o curso CPS 731/COPPE. |
| 251 | [Aloka-Tek-Teach/ESP32-Wifi-Jammer-Sinhala](https://github.com/Aloka-Tek-Teach/ESP32-Wifi-Jammer-Sinhala) | 3 | C | ESP32 Wifi Jammer Sinhala. |
| 252 | [AnvilBrain/Anvil-f](https://github.com/AnvilBrain/Anvil-f) | 3 | — | Anvil-F is a high-performance, all-in-one Wi-Fi toolkit for the ESP32-C5. It provides fast scanni… |
| 253 | [bigjosh/drone-sniffer](https://github.com/bigjosh/drone-sniffer) | 3 | C | Standalone drone Remote ID sniffer for the Mesh-Detect board: XIAO ESP32-S3 sniffs BLE + WiFi ch6… |
| 254 | [chinese1123243/ESP32-C5-WIFI6-RF-Toolkit](https://github.com/chinese1123243/ESP32-C5-WIFI6-RF-Toolkit) | 3 | C | ESP32-C5 (RISC-V 240MHz, Wi-Fi 6 双频) 射频测试工具。37 条 CLI 覆盖嗅探 / 握手捕获 / 注入 / 钓鱼门户 / Evil Twin / KARMA … |
| 255 | [christianathinshelled7231/cs2-esp-radar-hack-2026](https://github.com/christianathinshelled7231/cs2-esp-radar-hack-2026) | 3 | — | External ESP and radar hack for CS2 — see enemies through walls with health, weapon info, and ful… |
| 256 | [cybermaksx/ESP32-Evil-Twin-Deauth-Captive-Portal](https://github.com/cybermaksx/ESP32-Evil-Twin-Deauth-Captive-Portal) | 3 | C++ |  Educational ESP32 WiFi security lab: deauthentication attack + Evil Twin clone + captive portal … |
| 257 | [danya201272/ESP32-WIFI-WebSerial-433Mhz](https://github.com/danya201272/ESP32-WIFI-WebSerial-433Mhz) | 3 | C++ | ESP32 with app interface remoteXY and grab and sent code. Bruteforce Came and Nice. Have a Jammer… |
| 258 | [DOMN-git/esp32s3-nat-router](https://github.com/DOMN-git/esp32s3-nat-router) | 3 | C | ESP32S3 WiFi NAT Router with client listing, serial deauth, and network monitoring |
| 259 | [EinsPommes/ArithOS](https://github.com/EinsPommes/ArithOS) | 3 | C | ArithOS: A stealth pentesting toolkit disguised as a calculator for PicoCalc hardware. Features W… |
| 260 | [eric-o-s/WIFIPOLICE](https://github.com/eric-o-s/WIFIPOLICE) | 3 | C++ | Deauth monitor for the Waveshare ESP32-S3 147 inch Display Dev Board. This guy passively logs to … |
| 261 | [F6Exp/ESP32-WiFi-Deauth-Indicator](https://github.com/F6Exp/ESP32-WiFi-Deauth-Indicator) | 3 | C++ | ESP32 WiFi-Deauth-Indicator |
| 262 | [FOXIK-Lab/esp-stun](https://github.com/FOXIK-Lab/esp-stun) | 3 | Python | ESP32 Firmware for Pentesting. |
| 263 | [gibins/esp32_wifi_sniffer](https://github.com/gibins/esp32_wifi_sniffer) | 3 | C++ | IEEE802.11 packet capturing using ESP32 |
| 264 | [HelioASjunior/ESP32S3-pentest-tool](https://github.com/HelioASjunior/ESP32S3-pentest-tool) | 3 | C++ | Ferramenta educacional de teste de segurança WiFi para ESP32-S3, com interface web. Escaneia rede… |
| 265 | [HowDidThatHappen1/BT-Wifi-RC-Jammer](https://github.com/HowDidThatHappen1/BT-Wifi-RC-Jammer) | 3 | C++ |  |
| 266 | [Isno-Open/OpenSuperRF](https://github.com/Isno-Open/OpenSuperRF) | 3 | — | Design ouvert de la carte radio ISNO Super v1.0 (ESP32-S3, CC1101 433/868) pour firmwares radio c… |
| 267 | [KlutzyBlade/NetRaze32](https://github.com/KlutzyBlade/NetRaze32) | 3 | C | NetRaze32 is a comprehensive penetration testing tool built for the ESP32-32E platform with a 2.8… |
| 268 | [koua29/wifi-auditor](https://github.com/koua29/wifi-auditor) | 3 | Python | Audit your OWN Wi-Fi: capture WPA/WPA2 handshakes on LilyGO T-Embed (Bruce firmware), crack on Ma… |
| 269 | [kudoej/sentry-rf](https://github.com/kudoej/sentry-rf) | 3 | — | Passive drone RF detection + GNSS jamming/spoofing monitor for ESP32-S3 |
| 270 | [kylecmathias/FlipperInfinity](https://github.com/kylecmathias/FlipperInfinity) | 3 | C | Handheld multi-protocol signal analysis device — NFC, RFID, sub-GHz RF, IR, and WiFi on a custom … |
| 271 | [lank-one/ESPectro](https://github.com/lank-one/ESPectro) | 3 | — | DIY multi-function pentesting device (ESP32 + CC1101 + OLED) built on the ESP-HACK firmware. Hard… |
| 272 | [magikh0e/sprout](https://github.com/magikh0e/sprout) | 3 | C++ | Ambient hacker virtual pet for the 3.5" Cheap Yellow Display (ESP32-3248S035R) — real-time, weath… |
| 273 | [MaxKei/Data-Parsing-from-serial-port](https://github.com/MaxKei/Data-Parsing-from-serial-port) | 3 | Python | If it's promiscuous mode working together with ESP32, it can sniff data packets from the wireless… |
| 274 | [Meshwa428/KIVA](https://github.com/Meshwa428/KIVA) | 3 | C++ | KIVA: A handheld AI hacking assistant born from a love of tinkering. A pen-testing tool built fro… |
| 275 | [MrDepph/Tamafi-CYD-ESP32](https://github.com/MrDepph/Tamafi-CYD-ESP32) | 3 | — | Tamagotchi-inspired WiFi/Bluetooth sniffer firmware for CYD 2.8" ESP32. Creature feeds on network… |
| 276 | [mrnet15/RavenRF](https://github.com/mrnet15/RavenRF) | 3 | C++ | Modular RF & pentest firmware for the M5Stack Cardputer Adv + Cap LoRa-1262 (WiFi, BLE, LoRa, GPS) |
| 277 | [nelsoncarlson/marauder-esp32c5-automation](https://github.com/nelsoncarlson/marauder-esp32c5-automation) | 3 | Python | Suite de automacao para ESP32-C5 Marauder com Attack Manager e WiFi Scanner. |
| 278 | [nicolaij/tpms](https://github.com/nicolaij/tpms) | 3 | C++ | TPMS Geely Coolray (SX11) hack |
| 279 | [nlogallo/esp32-mantisHack](https://github.com/nlogallo/esp32-mantisHack) | 3 | C++ | Project of a small hacking device with Wifi, Bluetooth, NFC, and IR capabilities. |
| 280 | [obstruse/PGNH](https://github.com/obstruse/PGNH) | 3 | C | PolarGraph Network Hack: PolarshieldSD v3.0e modified to use WiFi for communication between contr… |
| 281 | [oscarmh/CC1101-ESP32](https://github.com/oscarmh/CC1101-ESP32) | 3 | C | Sub Ghz scanner with 3 CC1101 and ESP32C6 |
| 282 | [popdoop/Esp32-s3-jammer-for-if-you-only-have-1-nRF24L0-PA-LNA-](https://github.com/popdoop/Esp32-s3-jammer-for-if-you-only-have-1-nRF24L0-PA-LNA-) | 3 | C++ | ***FOR EDUCATIONAL PURPOSES*** code is kinda wack// but it works.  |
| 283 | [pwnk1t/esp32-bluetooth-WiFi-jammer](https://github.com/pwnk1t/esp32-bluetooth-WiFi-jammer) | 3 | — | how to build a simple bluetooth/WiFi-jammer (WiFi only works on 2,4Ghz Network-devices) |
| 284 | [RizzoEng/DevilApe-Tft-cyberdeck](https://github.com/RizzoEng/DevilApe-Tft-cyberdeck) | 3 | — | ESP32-powered cyberdeck interface. WiFi/BLE scanning, packet monitoring, deauth detection, beacon… |
| 285 | [sephallen/esp32-wifi-sniffer-sdcard-sqlite](https://github.com/sephallen/esp32-wifi-sniffer-sdcard-sqlite) | 3 | C++ |  |
| 286 | [shubbrotopaul-max/Spectre-DIV-OS](https://github.com/shubbrotopaul-max/Spectre-DIV-OS) | 3 | C | SPECTRE-DIV OS is a Matrix-themed WiFi Research Suite for ESP32 & ST7789 TFT. 🚀  Features: ✅ Pack… |
| 287 | [Sndcooper/2.4GHZ-jammer](https://github.com/Sndcooper/2.4GHZ-jammer) | 3 | C++ | Educational ESP32 PlatformIO project scaffold for 2.4 GHz RF experimentation and compliance learn… |
| 288 | [stalss/passive-wifi-crowd-counter](https://github.com/stalss/passive-wifi-crowd-counter) | 3 | C | Passive WiFi crowd counter using ESP32 promiscuous mode — counts nearby devices by sniffing 802.1… |
| 289 | [stephanbluitt/-ESP32-Evil-Twin-Attack](https://github.com/stephanbluitt/-ESP32-Evil-Twin-Attack) | 3 | C++ | A proof-of-concept ESP32 Evil Twin attack demo featuring deauthentication and a customizable capt… |
| 290 | [the78mole/moles-integ-dtu-hw](https://github.com/the78mole/moles-integ-dtu-hw) | 3 | — | This is a small module for use of ESP32 with a sub-GHZ transceiver, mainly intended to serve as a… |
| 291 | [timschmolka/esp32-sniffer](https://github.com/timschmolka/esp32-sniffer) | 3 | C | A simple PoC of sniffing raw wifi packets from a pre-defined channel on an ESP32. |
| 292 | [toprakahmetaydogmus/uts-jam](https://github.com/toprakahmetaydogmus/uts-jam) | 3 | C++ | UTS-JAM Ultimate - ESP32-C3 SuperMini Dual nRF24 2.4GHz RF Spectrum Analyzer & Security Lab Device |
| 293 | [uchiha-madara-02/Esp32-jammer-rf](https://github.com/uchiha-madara-02/Esp32-jammer-rf) | 3 | — |  |
| 294 | [VeerDev-hub/esp32-fake-virus-prank](https://github.com/VeerDev-hub/esp32-fake-virus-prank) | 3 | C++ | This project turns your ESP32 into a fake "Hacked" WiFi access point, complete with a full-screen… |
| 295 | [x3nc0n/flipper-fuzzer](https://github.com/x3nc0n/flipper-fuzzer) | 3 | C | FluckFlock - a Flipper Zero chaff broadcaster that floods passive Wi-Fi/BLE/RF tracking with plau… |
| 296 | [xuemian168/esp32-ble-proximity-spoofing](https://github.com/xuemian168/esp32-ble-proximity-spoofing) | 3 | Python | Research artifact for ESP32 BLE proximity advertisement spoofing experiments |
| 297 | [absolute-xero7/kestrel](https://github.com/absolute-xero7/kestrel) | 2 | C++ | Pocket RF & wireless recon multitool firmware for the ESP32 Cheap Yellow Display — WiFi/BLE + CC1… |
| 298 | [AedanJaeson/subghz-sdr-video-telemetry-lab](https://github.com/AedanJaeson/subghz-sdr-video-telemetry-lab) | 2 | Jupyter Notebook | Guided SDR/RF/DSP lab for low-rate ESP32-CAM to CC1101 to RTL-SDR image telemetry |
| 299 | [aingram702/ESP32-Net](https://github.com/aingram702/ESP32-Net) | 2 | C++ | A network of dropable ESP32 devices that all serve an individual purpose. One ESP32-S3 DevKitC-1 … |
| 300 | [Alexxdal/esp_wifi_usb](https://github.com/Alexxdal/esp_wifi_usb) | 2 | C | RTL8188EU USB Wi-Fi driver for ESP32-S3's native USB host — promiscuous sniffing + raw 802.11 inj… |
| 301 | [allegorix/esp-wifi-radar-lab](https://github.com/allegorix/esp-wifi-radar-lab) | 2 | Python | ESP8266 + ESP32 promiscuous sniffers, 3D Wi-Fi radar, active scan, and audit toolkit |
| 302 | [alrayat/ESP32-S3-WiFi-Jammer](https://github.com/alrayat/ESP32-S3-WiFi-Jammer) | 2 | C++ |  |
| 303 | [aniceswan/PhantomRF](https://github.com/aniceswan/PhantomRF) | 2 | C++ | Open-source ESP32-S3 RF research & security testing platform. nRF24L01 + CC1101 jamming, full WiF… |
| 304 | [archrampart/zero-cmd](https://github.com/archrampart/zero-cmd) | 2 | JavaScript | Web-based command center for Flipper Zero — Screen mirror, file manager, Sub-GHz, NFC, IR, Bad US… |
| 305 | [Arxhsz/Project-Skull-Breaker-v1](https://github.com/Arxhsz/Project-Skull-Breaker-v1) | 2 | C++ | ESP32 handheld multi-radio security research device — WiFi, BLE, 2.4GHz & sub-GHz RF. v1 proof of… |
| 306 | [AtaCanYmc/esp32-rf-sword](https://github.com/AtaCanYmc/esp32-rf-sword) | 2 | C++ | ESP32 RF SWORD is an advanced, industrial grade multi-band radio frequency security research, spe… |
| 307 | [bartman081523/CMT2300A](https://github.com/bartman081523/CMT2300A) | 2 | C++ | ESP32 + CMT2300A sub-GHz transceiver: driver, WebUI, iM871A/wmbusmeters HCI shim, STM8 SWIM tooli… |
| 308 | [blakejosephjames1-ctrl/WIFI_Cyberdeck](https://github.com/blakejosephjames1-ctrl/WIFI_Cyberdeck) | 2 | — | This project is a Cyberdeck based from an ESP32-S3 microcontroller designed to perform WIFI attac… |
| 309 | [bsucyber/wifi-hacking](https://github.com/bsucyber/wifi-hacking) | 2 | — | Wifi hacking activity with ESP32-WROOM-ESP boards. |
| 310 | [cashoefman/Resto-Score-for-Hack-2021-for-Positivity](https://github.com/cashoefman/Resto-Score-for-Hack-2021-for-Positivity) | 2 | Python | Resto Score connect a Heltec LoRaWAN 32, Heltec Wifi Kit 32 or Generic ESP32 Devkit to Google IoT… |
| 311 | [ch3ber/esp32-projects](https://github.com/ch3ber/esp32-projects) | 2 | Python | Collection of small, self-contained projects for the ESP32 family of microcontrollers programmed … |
| 312 | [chrislangfitt7/ESP_32_SNIFFER](https://github.com/chrislangfitt7/ESP_32_SNIFFER) | 2 | — | A small handheld device that has 2.4ghz capabilities along with Wifi and Bluetooth scanning. Usin… |
| 313 | [cikolllooid/esp32_wifi](https://github.com/cikolllooid/esp32_wifi) | 2 | C | hack wifi |
| 314 | [CoolJuvenile/esp32-s3-wifi-killer](https://github.com/CoolJuvenile/esp32-s3-wifi-killer) | 2 | C++ | ESP32-S3 掌上 Wi-Fi 测试仪 · Deauth / Beacon Flood / Probe Flood，摇杆 + OLED 脱机操作，已从 ESP8266 Deauther 移植… |
| 315 | [Danucosukosuko/Flipper-devboard-WiFi-Spam](https://github.com/Danucosukosuko/Flipper-devboard-WiFi-Spam) | 2 | C++ | Programa escrito en Arduino para emitir redes Wi-Fi aleatorias en la Wi-Fi DevBoard del Flipper Zero |
| 316 | [darkLabz001/pwni-esp32-c5](https://github.com/darkLabz001/pwni-esp32-c5) | 2 | C | PWNI: Pwnagotchi-style WiFi pet for Waveshare ESP32-C5-Touch-LCD-3.5 with web OTA, SD captures, d… |
| 317 | [DesignGraveyard/V004_ESP32_Global_Control](https://github.com/DesignGraveyard/V004_ESP32_Global_Control) | 2 | C++ | Control your ESP32 globally without WiFi router hacks or port-forwarding. Please check the code a… |
| 318 | [devdanqtuan/esp32-bluetooth-classic-attacks](https://github.com/devdanqtuan/esp32-bluetooth-classic-attacks) | 2 | — |  |
| 319 | [Dhananjay-saxena/Wifi-deAuth-ESP-32](https://github.com/Dhananjay-saxena/Wifi-deAuth-ESP-32) | 2 | — | A lightweight and powerful tool built for the ESP32 that demonstrates Wi-Fi deauthentication atta… |
| 320 | [dimitrisss/ESP32-WiFi-Jammer](https://github.com/dimitrisss/ESP32-WiFi-Jammer) | 2 | — |  |
| 321 | [Eivs/BeeperTX](https://github.com/Eivs/BeeperTX) | 2 | C | ESP32-S3 + Si4463 dual-protocol (POCSAG / FLEX) pager transmitter with a web UI, serial CLI, WiFi… |
| 322 | [G4MEOVER18/heltec-ukfe-rx](https://github.com/G4MEOVER18/heltec-ukfe-rx) | 2 | C++ | Heltec V3 (ESP32-S3+SX1262): 868-FSK+ESP-NOW Satellit/Hub des G4MEOVER-Oekosystems. Handler: WiFi… |
| 323 | [G4MEOVER18/lilygo-ukfe-rx](https://github.com/G4MEOVER18/lilygo-ukfe-rx) | 2 | C++ | G4MEOVER LilyGo T-Dongle S3: ESP-NOW-Satellit. Handler: USB-HID (BadUSB), WiFi (Deauth/Beacon/Sca… |
| 324 | [ghost00318/IshtarRF-Android](https://github.com/ghost00318/IshtarRF-Android) | 2 | Kotlin | Control Sub-GHz radio modules via USB-OTG. The native Android app captures, transmits, and visual… |
| 325 | [GlomarGadaffi/t-mixrf-idf](https://github.com/GlomarGadaffi/t-mixrf-idf) | 2 | C | Pure ESP-IDF driver suite for LILYGO T-MixRF: LR1121 dual-band LoRa, CC1101 sub-GHz, nRF24L01+, S… |
| 326 | [GlomarGadaffi/wifi-ble-marauder](https://github.com/GlomarGadaffi/wifi-ble-marauder) | 2 | C | Pure ESP-IDF 6.0.1 WiFi/BLE security tool: 5GHz deauth, Thread/Matter scanning, BLE 5.0 ext adv. … |
| 327 | [Grostl/esp32-mac-collector](https://github.com/Grostl/esp32-mac-collector) | 2 | C++ | Dual-band (2.4/5 GHz) Wi-Fi & Bluetooth LE sniffer for ESP32-C5. Captures MAC addresses from Prob… |
| 328 | [gurvinny/spectre](https://github.com/gurvinny/spectre) | 2 | Python | WiFi intrusion-detection sensor: ESP32-C5 sniffer to FastAPI detection to Next.js SOC console wit… |
| 329 | [h435er/ESP32-WIFI-PENTESER](https://github.com/h435er/ESP32-WIFI-PENTESER) | 2 | C++ | An wifi penetration testing tool for the ESP32 with some cool functions like an Pwnagotchi or an … |
| 330 | [harsh13pro/ESP32-Evil-Twin-Deauther-WiFi-Pentest-Tool-](https://github.com/harsh13pro/ESP32-Evil-Twin-Deauther-WiFi-Pentest-Tool-) | 2 | — |  |
| 331 | [IAbrahamI/Wifi_Scanner](https://github.com/IAbrahamI/Wifi_Scanner) | 2 | C++ | Multi-boot pocket RF gadget powered by ESP32-S3. Includes a touch-based boot launcher, active fla… |
| 332 | [izaanhussain/Wifi-Death-V1](https://github.com/izaanhussain/Wifi-Death-V1) | 2 | C++ | A ESP32 based wifi hacking tool with esp32 c3 and 0.96 inch oled dsplay |
| 333 | [J1rs/Jir32](https://github.com/J1rs/Jir32) | 2 | — | ESP32-based wireless security & signal research system: Integrated tools for WiFi, Bluetooth, and… |
| 334 | [Joaquin7gg/esp32-pc-monitor](https://github.com/Joaquin7gg/esp32-pc-monitor) | 2 | C++ | Dashboard fisico ESP32-S3 (AMOLED) con metricas del PC en tiempo real y sensor WiFi defensivo (de… |
| 335 | [johnnyk2000/BluetoothRover](https://github.com/johnnyk2000/BluetoothRover) | 2 | C++ | Redo of HAcK 22: Create a rover that is controlled through bluetooth using UART btw arduibno and … |
| 336 | [kazawa392010/Deauth_Attack_WiFi_With_ESP32](https://github.com/kazawa392010/Deauth_Attack_WiFi_With_ESP32) | 2 | C++ | Dùng esp32 wroom |
| 337 | [kes229229/JAM-PACK](https://github.com/kes229229/JAM-PACK) | 2 | C++ | 📡 Ultimate multi-tool firmware for ESP32 · WiFi · BLE · SubGHz · IR · GPIO · BETA |
| 338 | [killindodo/Dodo-RF](https://github.com/killindodo/Dodo-RF) | 2 | Kotlin | ESP32 based open-source, ultra-portable Sub-GHz radio analysis, capture, and replay |
| 339 | [lennarddaw/esp-wifi-tool](https://github.com/lennarddaw/esp-wifi-tool) | 2 | C | A lightweight ESP32-based Wi-Fi tool for scanning, analyzing, and interacting with nearby network… |
| 340 | [LieBtrau/esp32-wifi-sniffer](https://github.com/LieBtrau/esp32-wifi-sniffer) | 2 | C++ | wifi packet analyzer for ESP32 |
| 341 | [Ludmilahttps/Jammer-WiFi-Bluetooth-ESP32](https://github.com/Ludmilahttps/Jammer-WiFi-Bluetooth-ESP32) | 2 | JavaScript | Protótipo de bloqueador de sinais sem fio (Wi-Fi/Bluetooth) na faixa de 2.4 GHz, desenvolvido com… |
| 342 | [mackg1288-pixel/packet-squirrel](https://github.com/mackg1288-pixel/packet-squirrel) | 2 | Python | DIY network interception platform built with NanoPi NEO3 + ESP32. Inline Ethernet bridge with WiF… |
| 343 | [magikh0e/pueo](https://github.com/magikh0e/pueo) | 2 | C++ | A handheld multi-radio field tool. ESP32 firmware for the cheap yellow display, with CC1101 sub-G… |
| 344 | [Mahardika-Tech/mahardika-tech-esp32-wifi-ble-jammer](https://github.com/Mahardika-Tech/mahardika-tech-esp32-wifi-ble-jammer) | 2 | — | Jamming wifi & bluethooth with esp32 support oled or lcd. |
| 345 | [maviaydin044-max/BlueDrogom](https://github.com/maviaydin044-max/BlueDrogom) | 2 | C++ | This software carries out kill attacks using the ESP32's Wi-Fi antennas.    PLEASE ONLY ATTACK YO… |
| 346 | [Maytastico/PSec_RollingCode](https://github.com/Maytastico/PSec_RollingCode) | 2 | C++ | Rolling Code implementation for practical security workshop. The code is based on the CC1101 Sub … |
| 347 | [Mizu-Tech/mizu-tech-esp32-wifi-ble-jammer](https://github.com/Mizu-Tech/mizu-tech-esp32-wifi-ble-jammer) | 2 | — |  |
| 348 | [MohitPatil2402/esp-drone-tracking](https://github.com/MohitPatil2402/esp-drone-tracking) | 2 | Python | Drone-based crowd monitoring using ESP32 WiFi sniffing and trilateration |
| 349 | [mytechnotalent/meshcore-sniffer](https://github.com/mytechnotalent/meshcore-sniffer) | 2 | C++ | A lightweight, dedicated firmware for the ESP32-S3 and SX1262 LoRa module designed to passively s… |
| 350 | [Nadoooor/SnakeHunter](https://github.com/Nadoooor/SnakeHunter) | 2 | — | An ESP32 wifi, bluetooth, IR, etc hacking device with touch screen. |
| 351 | [neilmanfredit/CyberDeck](https://github.com/neilmanfredit/CyberDeck) | 2 | C++ | Portable pentest cyberdeck — NUC-based clamshell with an embedded ESP32-S3 security module (sub-G… |
| 352 | [neohiro/lora-sniffer](https://github.com/neohiro/lora-sniffer) | 2 | C++ | Passive LoRa sniffer firmware for the Heltec WiFi LoRa 32 V4, built to run as its own slot alongs… |
| 353 | [nmicic/URTB](https://github.com/nmicic/URTB) | 2 | C | Encrypted PTY tunnel over ESP-NOW/LoRa radio links or untrusted jump hosts — XChaCha20-Poly1305 |
| 354 | [NNLisk/Wi-fi-sniffer](https://github.com/NNLisk/Wi-fi-sniffer) | 2 | C | A project to build a wifi sniffer on an Espressif ESP32 microcontroller |
| 355 | [P5YB3RN4UT/ESP32-SubGHz-Jammer](https://github.com/P5YB3RN4UT/ESP32-SubGHz-Jammer) | 2 | C++ | Source code for a Sub-GHz Jammer controlled by ESP32 |
| 356 | [Q3hr/Blackout-2.4](https://github.com/Q3hr/Blackout-2.4) | 2 | C | Blackout 2.4 is a 5th Semester Network Security project that explores 2.4 GHz spectrum behavior a… |
| 357 | [raju-prajapat/ESP32-Brute-Force-Attack-To-ByPass-Phone-Lock](https://github.com/raju-prajapat/ESP32-Brute-Force-Attack-To-ByPass-Phone-Lock) | 2 | C++ | Proof-of-concept ESP32 BLE Keyboard script for automated 4-digit and 6-digit PIN testing. |
| 358 | [ravshansaginbaev/ESP32-Wifi-Deauthenticator](https://github.com/ravshansaginbaev/ESP32-Wifi-Deauthenticator) | 2 | C |  |
| 359 | [Rayan-Shareefi/WiFi-Intrusion-Detection-System-with-Encrypted-Cloud-Alerting](https://github.com/Rayan-Shareefi/WiFi-Intrusion-Detection-System-with-Encrypted-Cloud-Alerting) | 2 | Python | An ESP32 that detects Wi-Fi attacks (deauth, evil twin, unknown devices) and sends encrypted aler… |
| 360 | [revjmoney/simian-radar](https://github.com/revjmoney/simian-radar) | 2 | C++ | Listen-only pocket privacy scanner for the Heltec LoRa 32 V4: offline US ALPR camera alerts, trac… |
| 361 | [saravanasai1435/esp32-marauder-wifi-bt-security-tool](https://github.com/saravanasai1435/esp32-marauder-wifi-bt-security-tool) | 2 | — | ESP32 Marauder WiFi/Bluetooth security toolkit: deauth, beacon spam, evil portal, GPS, SD logging… |
| 362 | [shahabmohamadi/ESP32-Twin-WiFi-Hacking-Deauthentication-Captive-Portal](https://github.com/shahabmohamadi/ESP32-Twin-WiFi-Hacking-Deauthentication-Captive-Portal) | 2 | C++ | Disclaimer: This project is for educational purposes only. Use it responsibly and legally. Unauth… |
| 363 | [Tanmay1894/ESP32-Flipper](https://github.com/Tanmay1894/ESP32-Flipper) | 2 | C++ | ESP32 Flipper is a touchscreen-driven toolkit for wireless security testing on ESP32. It features… |
| 364 | [TaxCoding/ESP32-MultiTarget-Deauth-Engine](https://github.com/TaxCoding/ESP32-MultiTarget-Deauth-Engine) | 2 | CMake | Wifi deuther, deauthentication attack. An ESP32-based Wi-Fi research project exploring IEEE 802.1… |
| 365 | [thevixer/ESP32-Promiscuous-osc](https://github.com/thevixer/ESP32-Promiscuous-osc) | 2 | C++ | An esp32 promiscuous mac address sniffer with osc messaging |
| 366 | [Thilakkumar0308/IRUTESAM-Dark-Venom](https://github.com/Thilakkumar0308/IRUTESAM-Dark-Venom) | 2 | C++ | IRUTESAM is an ESP32-based IoT hacking toolkit with a custom hacker-style touchscreen UI. It supp… |
| 367 | [Try-harder-not-smarter/Proyect-EvilTwin-ESP32](https://github.com/Try-harder-not-smarter/Proyect-EvilTwin-ESP32) | 2 | C++ | Educational simulation of a WiFi Evil Twin attack with ESP32 — technical lab documentation |
| 368 | [tworjaga/Esp32watchdog](https://github.com/tworjaga/Esp32watchdog) | 2 | C++ | Passive Wi-Fi threat monitor for ESP32. Detects deauth floods, evil twin APs and beacon floods in… |
| 369 | [uncleNas/wifiSnifferWithESP32](https://github.com/uncleNas/wifiSnifferWithESP32) | 2 | C++ | Cybersecurity hardware device:  implementing packet analyzer using ESP32, LCD, and I2C adapter |
| 370 | [Valbef/DeauthDetectorESP32](https://github.com/Valbef/DeauthDetectorESP32) | 2 | Python | detector de tramas deauth para Linux, usar con modulos wifi con modo monitor o con  ESP32-WROOM-32. |
| 371 | [visionSensor/esp-deauther-detector](https://github.com/visionSensor/esp-deauther-detector) | 2 | C++ | detect wifi deauther with little effort. |
| 372 | [voltwizeshea/DarkMatter_Duck](https://github.com/voltwizeshea/DarkMatter_Duck) | 2 | C++ | Dual-stack HID weapon on ESP32-S3: USB + BLE keystroke injection, WiFi C2, payload chains. One of… |
| 373 | [vslinuxdotnet/ESP32-Evil-Twin](https://github.com/vslinuxdotnet/ESP32-Evil-Twin) | 2 | C++ | ESP32 Evil Twin WiFi Hacking, Deauthentication  |
| 374 | [Vybenclave/wifi-d_vice](https://github.com/Vybenclave/wifi-d_vice) | 2 | C | WIFI D_VICE - passive Wi-Fi / BLE / sub-GHz radio-monitoring tool for the 2.8-inch ESP32 CYD. No … |
| 375 | [wk12100lol-prog/vexhack](https://github.com/wk12100lol-prog/vexhack) | 2 | C++ | VEXHACK - WiFi pentest tool for CYD ESP32-2432S028R. Features: WiFi scanner, deauth attack, clien… |
| 376 | [xerdenx/Spooky-](https://github.com/xerdenx/Spooky-) | 2 | C++ | A customized fork of nRFBox firmware for ESP32.  Changes made: - TV-B-Gone added (IR remote power… |
| 377 | [xiv3r/esp32-deauth-detector](https://github.com/xiv3r/esp32-deauth-detector) | 2 | C++ | esp32 wifi deauth detector with led and buzzer notifications |
| 378 | [xiv3r/esp32-jammer-detector](https://github.com/xiv3r/esp32-jammer-detector) | 2 | C++ | Detect deauthentication frames using esp32 (commonly known wifi jamming) |
| 379 | [YurilLAB/esp32-SnowOwl](https://github.com/YurilLAB/esp32-SnowOwl) | 2 | — | A multi-purpose wireless offensive & defensive security multitool — ESP32-S3 + ARM Linux, with NF… |
| 380 | [0EchoPixel/ESP32-Bluetooth-Jammer](https://github.com/0EchoPixel/ESP32-Bluetooth-Jammer) | 1 | C++ | ESP32 + NRF24L01 That jams WIFI and Bluetooth  |
| 381 | [Aazwd20/deauth-beacon_ESP32](https://github.com/Aazwd20/deauth-beacon_ESP32) | 1 | C++ | trying out different attacks on the wifi with esp32 |
| 382 | [Abhishek1033ubuntu/Dynamic-Speed-Limiter-ESP32](https://github.com/Abhishek1033ubuntu/Dynamic-Speed-Limiter-ESP32) | 1 | C++ | An infrastructure-to-vehicle (I2V) wireless speed-control system that dynamically restricts maxim… |
| 383 | [abocconi/esp32_subghz_sniffer](https://github.com/abocconi/esp32_subghz_sniffer) | 1 | C | Sub-Ghz sniffer |
| 384 | [Aditya5441/Jammer_Adaptive](https://github.com/Aditya5441/Jammer_Adaptive) | 1 | C++ | an ESP32-based WiFi/BLE jamming device that uses chaos-derived entropy (from internal noise/analo… |
| 385 | [adumppp/Esp32-Deauther-](https://github.com/adumppp/Esp32-Deauther-) | 1 | C | this project for Penetration testing using esp32 on wifi |
| 386 | [ahmedhussain006/SIM-Cellular-Jammer](https://github.com/ahmedhussain006/SIM-Cellular-Jammer) | 1 | — | Embedded RF security research project exploring radio frequency interference, wireless communicat… |
| 387 | [Akshit0203/flipper-zero-wifi-security-assessment](https://github.com/Akshit0203/flipper-zero-wifi-security-assessment) | 1 | — | Hands-on WPA2-PSK wireless security assessment with a Flipper Zero + ESP32 Marauder — covering th… |
| 388 | [AlvGJ-UGR/ESP32-WiFi-Security-Research-Lab](https://github.com/AlvGJ-UGR/ESP32-WiFi-Security-Research-Lab) | 1 | Python | Educational adaptation of the ESP32 Wi-Fi Penetration Tool for studying wireless network security… |
| 389 | [AnasAbbasiCode/ESP-WiFi-Toolbox](https://github.com/AnasAbbasiCode/ESP-WiFi-Toolbox) | 1 | C++ | A web-based interface for interacting with an ESP32 over Wi-Fi. Allows users to connect, scan nea… |
| 390 | [anaskhanxada/WifiandBluetoothJammer](https://github.com/anaskhanxada/WifiandBluetoothJammer) | 1 | C | A WiFi and Bluetooth jamming tool built on [ESP32/your hardware] for disrupting wireless signals … |
| 391 | [AndrewChacon/wifi-evil-twin](https://github.com/AndrewChacon/wifi-evil-twin) | 1 | C++ | An ESP32-based wireless phishing simulator that replicates Evil Twin attacks for research and sec… |
| 392 | [Apoorva08-g/Firmware_Integrity_Monitor](https://github.com/Apoorva08-g/Firmware_Integrity_Monitor) | 1 | Python | Hardware-based firmware integrity monitor using Raspberry Pi Pico W + ESP32. Detects supply chain… |
| 393 | [AtherNet29/ESP32-DEAUTHER-DAN-EVILTWIN-AETHERNET](https://github.com/AtherNet29/ESP32-DEAUTHER-DAN-EVILTWIN-AETHERNET) | 1 | — | 🎯 ESP32 Deauther & BT Jammer. Features: Evil Twin, Auto-Password Verify, Beacon Spam, Rogue AP, W… |
| 394 | [BadRat-in/wifikit](https://github.com/BadRat-in/wifikit) | 1 | Python | Single-screen terminal UI + CLI for authorized WiFi security testing with an ESP32 running ESP32 … |
| 395 | [bdini13/esp32-cc1101-multiband](https://github.com/bdini13/esp32-cc1101-multiband) | 1 | Python | Work-in-progress ESP32-WROOM-32E + CC1101 multiband PCB: software-selected 315/433/868/915 MHz pa… |
| 396 | [bhargavvaghasiya12/wifi-deauth-detector-esp32](https://github.com/bhargavvaghasiya12/wifi-deauth-detector-esp32) | 1 | — | Real-Time Wi-Fi Deauthentication Attack Detection System using ESP32 |
| 397 | [bixente11/Waveshare-ESP32-S3-Touch-LCD-3.49-CC1101-LVGL-9.3](https://github.com/bixente11/Waveshare-ESP32-S3-Touch-LCD-3.49-CC1101-LVGL-9.3) | 1 | C++ | SubGhz with Waveshare ESP32-S3-Touch-LCD-3.49  |
| 398 | [BrainRape23/Esp_WIFI](https://github.com/BrainRape23/Esp_WIFI) | 1 | — | Esp32_WIFI Analyzer and proofe of Concept Hacking  |
| 399 | [brandonvader/Sentinel-Watch-OS](https://github.com/brandonvader/Sentinel-Watch-OS) | 1 | C | Passive WiFi + BLE threat monitor for the Waveshare ESP32-S3 AMOLED watch: gravity-driven data-ra… |
| 400 | [brankkoo/wifi-tool](https://github.com/brankkoo/wifi-tool) | 1 | C | esp32 pentesting firmware |
| 401 | [byankush/Ble-wifi-jammer-byankush](https://github.com/byankush/Ble-wifi-jammer-byankush) | 1 | C++ | ESP32-based wireless security research project exploring Wi-Fi and Bluetooth protocols, RF commun… |
| 402 | [ciccirix/koko-v9](https://github.com/ciccirix/koko-v9) | 1 | C++ | ESP32 Marauder C5 — koko V9: WiFi/BT-only build, features reorganized into stock WiFi/Bluetooth m… |
| 403 | [CircuitVortex/Esp32-S3-Jammer](https://github.com/CircuitVortex/Esp32-S3-Jammer) | 1 | C++ | It jams Wifi using just Esp32 s3 N16R8 it self. |
| 404 | [ClemensAtElektor/Bluetooth-LE-ESP32-client-server](https://github.com/ClemensAtElektor/Bluetooth-LE-ESP32-client-server) | 1 | C++ | Simple Bluetooth client-server setup on two ESP32 modules for trying out nRF52840 BLE sniffer. |
| 405 | [COF10/MicroByte](https://github.com/COF10/MicroByte) | 1 | — | MicroByte is a compact handheld wireless tool built around the Waveshare ESP32-C6-LCD-1.47, featu… |
| 406 | [comradezephyr/EvilTwinESP32](https://github.com/comradezephyr/EvilTwinESP32) | 1 | Python | ESP32 Evil Twin- WiFi Penetration Testing Tool \| Captive Portal \| Rogue AP |
| 407 | [crackerbyte/esp-cracker](https://github.com/crackerbyte/esp-cracker) | 1 | — | 🍪 Cracker - DIY pentest device on ESP32-S3 with Wi-Fi, BLE, IR, Sub-GHz, 2.4GHz, GPS, NFC, Bad-US… |
| 408 | [cs-23-sw-7-06/esp32-wifi-sniffer](https://github.com/cs-23-sw-7-06/esp32-wifi-sniffer) | 1 | C++ | ESP32 Wifi sniffer |
| 409 | [D1se0/DetectorAPFisico-Gadget-Hacking](https://github.com/D1se0/DetectorAPFisico-Gadget-Hacking) | 1 | C++ | Detector WiFi con ESP32 y pantalla táctil ILI9341: escanea redes, muestra señal en tiempo real y … |
| 410 | [davidsalden/wifi-deauth-monitor](https://github.com/davidsalden/wifi-deauth-monitor) | 1 | C++ | Moniteur de réseau Wi-Fi pour ESP32 : il écoute le canal de votre box en mode promiscuous, détect… |
| 411 | [Deadbush225/Poltergeist](https://github.com/Deadbush225/Poltergeist) | 1 | Dart | Bluetooth payload attacks using ESP32-S3 |
| 412 | [DEBBUK/bruce-evil-knop-ble](https://github.com/DEBBUK/bruce-evil-knop-ble) | 1 | C++ | Custom Bruce firmware for LilyGO T-Display ESP32 with EVIL KNOP BLE — max-power iPhone BLE attack… |
| 413 | [diptimannxc/dEAUTHER](https://github.com/diptimannxc/dEAUTHER) | 1 | C | a wifi (2.4 Gz and WPA2-personal) scanner and deauther using ESP32 S3 DevkitM (no psram), two NRF… |
| 414 | [drngominhtu/ESP32_Deauther-WifiKiller-](https://github.com/drngominhtu/ESP32_Deauther-WifiKiller-) | 1 | C++ |  |
| 415 | [electgpl/LoFi56kBridge](https://github.com/electgpl/LoFi56kBridge) | 1 | C++ | Sub-GHz 915 MHz GFSK bridge that turns two ESP32-S3 into a ~40 kbps slow internet link — like a 5… |
| 416 | [ELSHAB7UAHED/ghost15](https://github.com/ELSHAB7UAHED/ghost15) | 1 | Shell | ESP32 WiFi Security Testing Tool - Advanced WiFi scanner and penetration testing tool for educati… |
| 417 | [FarhanKhanKakar07/wifideauth](https://github.com/FarhanKhanKakar07/wifideauth) | 1 | — | This is the wifi deauth attack bin files in which you can jam a wifi in your esp32 s3 n16 r8 Mode… |
| 418 | [Fhanafii/ESP32-Mirage](https://github.com/Fhanafii/ESP32-Mirage) | 1 | C++ | My custom ESP32 VROOM Evil twin to harvest wifi credentials |
| 419 | [finnmagnuskverndalen/airpulse](https://github.com/finnmagnuskverndalen/airpulse) | 1 | C++ | WiFi packet intelligence — M5StickC standalone scanner with OS fingerprinting, deauth detection, … |
| 420 | [flandreiii/Neux-Firmware-for-Esp32](https://github.com/flandreiii/Neux-Firmware-for-Esp32) | 1 | C++ | Turn any ESP32 into a pocket-sized wireless security scanner. WiFi/BLE recon, rogue AP detection,… |
| 421 | [foundafreename/wifi-ids-c6](https://github.com/foundafreename/wifi-ids-c6) | 1 | C | Passive 2.4 GHz Wi-Fi intrusion detector for ESP32-C6 (Waveshare LCD 1.47): deauth floods, evil t… |
| 422 | [GeneralDussDuss/hephaestus](https://github.com/GeneralDussDuss/hephaestus) | 1 | C++ | The forge: a Claude Code plugin for discovering, prototyping, and defending novel embedded/RF att… |
| 423 | [ghost00318/ghost00318.github.io](https://github.com/ghost00318/ghost00318.github.io) | 1 | — | Control Sub-GHz signals with an Android device using an ESP32 and CC1101 module connected via USB… |
| 424 | [GlomarGadaffi/deauth-detector](https://github.com/GlomarGadaffi/deauth-detector) | 1 | C | distributed 802.11 attack detector with a LoRa back-haul. sensors flag deauth/flood/evil-twin/EAP… |
| 425 | [govardhanh21/ESP32-Based-Bluetooth-HID-Attack-and-BLE-Scanner-Detection-System](https://github.com/govardhanh21/ESP32-Based-Bluetooth-HID-Attack-and-BLE-Scanner-Detection-System) | 1 | C++ |  |
| 426 | [h4zel-sec/wifi-deauther-with-esp32](https://github.com/h4zel-sec/wifi-deauther-with-esp32) | 1 | C++ | Wi-Fi deauther using ESP32  |
| 427 | [hackerazmi201/Ble-Jammer](https://github.com/hackerazmi201/Ble-Jammer) | 1 | — | Ble-jammer is a hardware-based BLE interference/testing toolkit that uses an ESP32 (for control a… |
| 428 | [hackermanzz/Wifi_Deauth_ESP32](https://github.com/hackermanzz/Wifi_Deauth_ESP32) | 1 | C++ |  |
| 429 | [henriford/wifi_hunter](https://github.com/henriford/wifi_hunter) | 1 | C++ | WiFi Hunter |
| 430 | [hex0gen1/wifi-deauth-detector](https://github.com/hex0gen1/wifi-deauth-detector) | 1 | C | esp32 project, that listening and analyzing network traffic to expose wifi attacks like deauth an… |
| 431 | [hleserg/esp32-flipper-exp](https://github.com/hleserg/esp32-flipper-exp) | 1 | Python | Flipper Zero + ESP32 'chaos from one button': Sub-GHz + IR + BLE. Roadmap: XIAO ESP32-C6 Zigbee/T… |
| 432 | [hoangvu161/ESP32-Penetration-wifi-firmware](https://github.com/hoangvu161/ESP32-Penetration-wifi-firmware) | 1 | — | Headless ESP32 Wi-Fi penetration tool with standalone Web UI, optimized for ESP32-WROOM/D0WD boards. |
| 433 | [iarpan1/wifi_deauther_esp32](https://github.com/iarpan1/wifi_deauther_esp32) | 1 | — |  |
| 434 | [JavierSiliacay/WiFi-Bluetooth-Jammer-Project](https://github.com/JavierSiliacay/WiFi-Bluetooth-Jammer-Project) | 1 | — | A powerful 2.4GHz signal disruptor built with ESP32, capable of jamming wireless communication by… |
| 435 | [jdz99999/sanwa-garage-shutter-esp32-control](https://github.com/jdz99999/sanwa-garage-shutter-esp32-control) | 1 | C++ | Control a Sanwa Speedy garage shutter from Home Assistant with an ESP32 + CC1101. Learns your exi… |
| 436 | [JK-Tmux/Flipper-Zero-Evil-Portal-Guide](https://github.com/JK-Tmux/Flipper-Zero-Evil-Portal-Guide) | 1 | — | Educational captive portal experiment using HTML templates |
| 437 | [Jonathan-0101/skeletonKey](https://github.com/Jonathan-0101/skeletonKey) | 1 | C | BEng Dissertation; Penetration-testing device to highlight security system vulnerabilities |
| 438 | [jR4dh3y/Pico32](https://github.com/jR4dh3y/Pico32) | 1 | C++ | A lightweight, serial-only TUI port of ESP32 Marauder. WiFi/BT testing tool for generic ESP32 mod… |
| 439 | [Justus040/ESP32-DIV-EvilAppleJuice](https://github.com/Justus040/ESP32-DIV-EvilAppleJuice) | 1 | — | EvilAppleJuice BLE Spoofing integrated into ESP32-DIV with TFT display UI |
| 440 | [karthik-nidiginti/nRFBox_v2](https://github.com/karthik-nidiginti/nRFBox_v2) | 1 | C | ESP32 NRF toolbox project with BLE scanner, jammer, analyzer and spoofing ,modules |
| 441 | [Kevin2901/wifi-defense-system-esp32](https://github.com/Kevin2901/wifi-defense-system-esp32) | 1 | HTML | Secure your WiFi from De-auth attacks, and monitor for anomalies and IP sniffing with ESP 32 hard… |
| 442 | [khwaabchawla28/Esp-32-evil-twin](https://github.com/khwaabchawla28/Esp-32-evil-twin) | 1 | C | ESP32 WiFi security research tool -- evil twin + captive portal for IoT coursework |
| 443 | [Luck-One9/rasputian-deauther](https://github.com/Luck-One9/rasputian-deauther) | 1 | C++ | Modular Wi-Fi security research firmware with clean architecture and event-driven design. |
| 444 | [mad0xStrixhadorami/esp32-wifi-security-lab](https://github.com/mad0xStrixhadorami/esp32-wifi-security-lab) | 1 | C | ESP32 evil-twin captive-portal demo for teaching WiFi credential-harvesting risk (lab use only) |
| 445 | [marcucarapangea-cloud/ESP32-WiFi-BLE-Penetration-Tool](https://github.com/marcucarapangea-cloud/ESP32-WiFi-BLE-Penetration-Tool) | 1 | — | WiFi Deauth + BLE Spoofing tool for ESP32 DevKit with OLED 0.96 display (SSD1306 I2C) |
| 446 | [MarkTH191/Esp32-WiFi-Jammer](https://github.com/MarkTH191/Esp32-WiFi-Jammer) | 1 | — | Esp-32 WiFi Jammer 2.4ghz |
| 447 | [MateoQuinteroH/Open-Jammer-V1.0](https://github.com/MateoQuinteroH/Open-Jammer-V1.0) | 1 | — | This project is an ESP32 based WiFi/Bluetooth jammer device. |
| 448 | [Mehflexx17/ESP5-WarBox-ESP32-](https://github.com/Mehflexx17/ESP5-WarBox-ESP32-) | 1 | — | ESP32-based RF security research tool with WiFi deauth, BLE flood, 2.4GHz spectrum analyzer, and … |
| 449 | [mike4x2/braktooth_esp32_bluetooth_classic_attacks-arm64-installer](https://github.com/mike4x2/braktooth_esp32_bluetooth_classic_attacks-arm64-installer) | 1 | — | Installer and compatibility fixes forBraktooth on ARM64 Debian 13 and Armbian |
| 450 | [MikelEscobar123/esp32-rf-jammer](https://github.com/MikelEscobar123/esp32-rf-jammer) | 1 | C++ | ESP32-based dual-band RF jammer using two nRF24L01+ modules over HSPI and VSPI. Features toggle b… |
| 451 | [Mizu-Tech/mizu-tech-esp32-ble-jammer-wifi-deauther](https://github.com/Mizu-Tech/mizu-tech-esp32-ble-jammer-wifi-deauther) | 1 | — |  |
| 452 | [Mizu-Tech/mizu-tech-esp32-wifi-deauther](https://github.com/Mizu-Tech/mizu-tech-esp32-wifi-deauther) | 1 | — |  |
| 453 | [MODARriba/Bluetooth-Jammer_IOT](https://github.com/MODARriba/Bluetooth-Jammer_IOT) | 1 | — | An ESP32-based RF interference research platform designed to analyze Bluetooth communication resi… |
| 454 | [mogtderi/ESP32-WiFi-Resilience-Research](https://github.com/mogtderi/ESP32-WiFi-Resilience-Research) | 1 | C++ | Experimental research framework evaluating wireless network resilience against 802.11 frame injec… |
| 455 | [mohammadajani/Beacongotchi](https://github.com/mohammadajani/Beacongotchi) | 1 | Python | Wireless Security Awareness Platform - Custom ESP32-S3 / BW16 FirmwareBuilt a multi-board WiFi/BL… |
| 456 | [monescuteodor/Blocky-OS-v7.6](https://github.com/monescuteodor/Blocky-OS-v7.6) | 1 | C++ | WiFi security testing suite for ESP8266 and ST7735 display. Device based on ESP8266 for testing n… |
| 457 | [MPunktBPunkt/esp32.bt-analyzer](https://github.com/MPunktBPunkt/esp32.bt-analyzer) | 1 | Python | ESP32-S3 Bluetooth USB/HCI analyzer lab (dongle HCI capture → Debian). Not an RF sniffer. |
| 458 | [N4P1x/YoRHa-Deauther](https://github.com/N4P1x/YoRHa-Deauther) | 1 | C++ | YoRHa Deauther is an ESP32-based Wi-Fi deauthentication tool that floods target access points wit… |
| 459 | [ndpg33/CHICKADEE](https://github.com/ndpg33/CHICKADEE) | 1 | C++ | ESP32 and CC1101 portable sub-GHz RF analysis tool with OLED interface. |
| 460 | [netvader/cyd-guard](https://github.com/netvader/cyd-guard) | 1 | C++ | Passive WiFi deauth + BLE jam detector for the CYD (ESP32-2432S024R) |
| 461 | [night0x1/Learning-C-via-ESP32-](https://github.com/night0x1/Learning-C-via-ESP32-) | 1 | — | I will learn how to code in c and programming esp32 for any cyber security projects that will hel… |
| 462 | [nik-nim/ESP32-Multi-Protocol-Wireless-Analysis-System](https://github.com/nik-nim/ESP32-Multi-Protocol-Wireless-Analysis-System) | 1 | — | ESP32 Multi-Protocol Wireless Analysis System \| Personal R&D Project Arduino, C/C++, ESP32, RF E… |
| 463 | [noweheere/Lumos-BBR-Bluetooth-Sniffer](https://github.com/noweheere/Lumos-BBR-Bluetooth-Sniffer) | 1 | — | ESP32 Bluetooth sniffer for Lumos Matrix helmet communication analysis and trailer indicator rela… |
| 464 | [overlinderosier0-afk/DJA-SCAN](https://github.com/overlinderosier0-afk/DJA-SCAN) | 1 | C++ | Outil de reconnaissance WiFi/Bluetooth passif sur ESP32 (OLED + joystick) - scan, detection deaut… |
| 465 | [P1p2gamer26/Jammer_Hacking_etico](https://github.com/P1p2gamer26/Jammer_Hacking_etico) | 1 | HTML | Laboratorio educativo de seguridad RF 2.4 GHz: ESP32 + nRF24L01+ PA/LNA (consola serial, escaner … |
| 466 | [parzival123-gan/esp32-wifi-ble-scanner](https://github.com/parzival123-gan/esp32-wifi-ble-scanner) | 1 | — | A lightweight RF scanner built with ESP32 that detects nearby Wi-Fi and Bluetooth Low Energy devi… |
| 467 | [Physostegiadragee5952/valorant-esp-items-2026](https://github.com/Physostegiadragee5952/valorant-esp-items-2026) | 1 | — | See dropped weapons, spike, abilities, and enemy economy through walls with real-time Valorant it… |
| 468 | [PigManul/megaware](https://github.com/PigManul/megaware) | 1 | C++ | Firmware for LilyGo T-Embed CC1101 (ESP32-S3) with Wi-Fi, Sub-GHz, NFC, and Lua/JS scripting |
| 469 | [pklosko/WiFiMulti](https://github.com/pklosko/WiFiMulti) | 1 | C++ | Arduino esp32 WiFiMulti fork - Hidden SSID hack |
| 470 | [PrestoDL/Project_ESP32Controller](https://github.com/PrestoDL/Project_ESP32Controller) | 1 | C | Project about esp32 controller, using wifi and ble. hacking research also |
| 471 | [pUrGe12/Wi-Fi-Bunny](https://github.com/pUrGe12/Wi-Fi-Bunny) | 1 | CMake | A Wifi-deauth + evil twin framework for ESP32 and ESP8266 |
| 472 | [Rain26t/Bluetooth-Wifi-RC-RF-Jammer-using-ESP32-and-NRF24L01](https://github.com/Rain26t/Bluetooth-Wifi-RC-RF-Jammer-using-ESP32-and-NRF24L01) | 1 | C++ |  |
| 473 | [ravdahuzaif88-hub/2.4GHz-Wireless-Security-Analysis-System](https://github.com/ravdahuzaif88-hub/2.4GHz-Wireless-Security-Analysis-System) | 1 | C++ | ESP32-based wireless security toolkit for 2.4GHz spectrum analysis, BLE spoofing and Wi-Fi deauth… |
| 474 | [rewalo/RowBoy](https://github.com/rewalo/RowBoy) | 1 | C++ | A tiny, hackable handheld powered by the ESP32-S3 WROOM-1, designed for gaming, emulation, and mo… |
| 475 | [rfypych/ble-wifi-jammer-esp32](https://github.com/rfypych/ble-wifi-jammer-esp32) | 1 | C++ |  |
| 476 | [rgomez31UAQ/WaveSentinelSubGhz-CC1101-V2_ESP32](https://github.com/rgomez31UAQ/WaveSentinelSubGhz-CC1101-V2_ESP32) | 1 | — | Flash WT32-SC01-PLUS  Conecte su placa a través de USB-C y haga clic en Abrir instalador web arri… |
| 477 | [Rhaine2008/WIfi---Bluetooth-Jammer](https://github.com/Rhaine2008/WIfi---Bluetooth-Jammer) | 1 | C++ | This project explores wireless communication, radio-frequency interference, and network security … |
| 478 | [ridhinva/pocket-s](https://github.com/ridhinva/pocket-s) | 1 | C | Toolkit: Pocket-S: Open-source ESP32-S3 multi-tool alternative to Flipper Zero — Sub-1GHz, NFC, R… |
| 479 | [Romemu1810-tech/bluetooth_jammer_experimento](https://github.com/Romemu1810-tech/bluetooth_jammer_experimento) | 1 | HTML | Proyecto personal y experimental para el aprendizaje de electrónica, RF y comunicaciones Bluetoot… |
| 480 | [ryvoxo/nRF-jammer](https://github.com/ryvoxo/nRF-jammer) | 1 | C++ | A Bluetooth and a WIFIA jammer using the ESP32 and two NRF24L01s. |
| 481 | [sariftachamo-cybersec/wifidisrupt-esp32-deauth-lab](https://github.com/sariftachamo-cybersec/wifidisrupt-esp32-deauth-lab) | 1 | Python | A hardware based projects that can be used to disconnect the wifi by sending the deauth packets u… |
| 482 | [saxflx/Esp32-EvilTwinWifiSifresi-EvilTwin-Instagram-WifiDoS-WifiSpam-Turkce](https://github.com/saxflx/Esp32-EvilTwinWifiSifresi-EvilTwin-Instagram-WifiDoS-WifiSpam-Turkce) | 1 | C++ |  |
| 483 | [sebarreto/ESP32-rfid-smartwatch-Lora-TTN-chatbot](https://github.com/sebarreto/ESP32-rfid-smartwatch-Lora-TTN-chatbot) | 1 | JavaScript | Project to improve treatment on children with panic attack. ESP32 + Smartwatch + LoraWan + TTN + … |
| 484 | [ShubhamKanhere307/CloneGuard---RFID-Cloning-Defense-](https://github.com/ShubhamKanhere307/CloneGuard---RFID-Cloning-Defense-) | 1 | — | Attack-and-defend RFID security lab using ESP32 and RC522 to clone MIFARE cards and bypass UID-on… |
| 485 | [Sid214/ESP32_RFID_Wifi_Jammer](https://github.com/Sid214/ESP32_RFID_Wifi_Jammer) | 1 | C++ | A hardware-integrated Wi-Fi security auditor for ESP32 featuring an RFID physical access lock (MF… |
| 486 | [Sid23-oss/grid_attacking](https://github.com/Sid23-oss/grid_attacking) | 1 | Python | grid_attacking is a cybersecurity mini SCADA system. An ESP32 substation (ZMPT and ACS712 sensors… |
| 487 | [siddhu2004bhagat/Esp32-2.4GHz-Ble-WiFi-jammer](https://github.com/siddhu2004bhagat/Esp32-2.4GHz-Ble-WiFi-jammer) | 1 | — |  |
| 488 | [sm2218157-creator/Netprobe](https://github.com/sm2218157-creator/Netprobe) | 1 | Shell | NetProbe - Android Security Toolkit: network scanner, WiFi pentesting, ESP32 control, OSINT tools… |
| 489 | [somelucs/bluetooth-esp32-attack](https://github.com/somelucs/bluetooth-esp32-attack) | 1 | C++ | Windows code injection by HID with bluetooth and ESP32  |
| 490 | [sophatvathana/dt2m](https://github.com/sophatvathana/dt2m) | 1 | C++ | DT2M (Don't T to Me) - ESP32 Multi-Purpose RF Development Platform |
| 491 | [suvo2007/Nrfboom_Btl](https://github.com/suvo2007/Nrfboom_Btl) | 1 | — | NRF BOOM — an ESP32-based multi-tool for nRF24, BLE, and WiFi security testing (scanner, jammer, … |
| 492 | [taleofthelion/esp32-FakeGotchi](https://github.com/taleofthelion/esp32-FakeGotchi) | 1 | — | esp32-FakeGotchi - Oled Nice Kitty that start jamming WiFi Strongest Network around u |
| 493 | [tech-nickk/ESP32Dragonfly](https://github.com/tech-nickk/ESP32Dragonfly) | 1 | C++ | WIFI and bluetooth pentesting tool |
| 494 | [teodorandrei/esp32_blespoof_gui](https://github.com/teodorandrei/esp32_blespoof_gui) | 1 | C++ | Easy to use ESP32 BLE Spoofer with Tkinter GUI |
| 495 | [tharakamruthraj/signal-jammer](https://github.com/tharakamruthraj/signal-jammer) | 1 | — | Description: A portable ESP32-based wireless signal jammer and scanner (NRF Box) designed for edu… |
| 496 | [unlucky666god/ESP32-WiFi-deauther](https://github.com/unlucky666god/ESP32-WiFi-deauther) | 1 | C++ |  |
| 497 | [uriel5523L/ESP32-Deauther-App](https://github.com/uriel5523L/ESP32-Deauther-App) | 1 | C++ | ESP32-Deauther app movil (WiFi/BLE) con login |
| 498 | [Usernameaisnoavailable/Hecker](https://github.com/Usernameaisnoavailable/Hecker) | 1 | — | An ESP32-based multi-tool for WiFi and BLE pentesting, themed around the "Hecker" cat meme. heres… |
| 499 | [vampel/ESP32-BlueJammer](https://github.com/vampel/ESP32-BlueJammer) | 1 | — | BT Jammer Wifi RC 2.4Ghz |
| 500 | [Vardhan0257/BlackPebble](https://github.com/Vardhan0257/BlackPebble) | 1 | C++ | BlackPebble is a modular ESP32-S3–based multi-protocol security research platform integrating Wi-… |
| 501 | [vikrantbasak15-lgtm/esp32-wifi-projects](https://github.com/vikrantbasak15-lgtm/esp32-wifi-projects) | 1 | C++ | ESP32 & Arduino IoT projects by a 13 y/o maker. WiFi-controlled builds, sensors, automation hacks… |
| 502 | [VishnuPrasanth-A/GC---GameChanger-Wifi-Tester](https://github.com/VishnuPrasanth-A/GC---GameChanger-Wifi-Tester) | 1 | C++ | The GC- Toolkit (Game Changer) is an advanced, self-contained Wi-Fi penetration testing and netwo… |
| 503 | [vswanagan/flock-you-also](https://github.com/vswanagan/flock-you-also) | 1 | — | ESP32-S3 firmware that emulates Flock Safety surveillance devices (FS Ext Battery, WiFi AP, Raven… |
| 504 | [vxnuprasad/EVIL-RAB-v2.0---ESP32-Evil-Twin-WiFi-Attack-Device](https://github.com/vxnuprasad/EVIL-RAB-v2.0---ESP32-Evil-Twin-WiFi-Attack-Device) | 1 | — | An ESP32-based evil twin WiFi attack device with 0.96 inch OLED display support (4-pin and 7-pin … |
| 505 | [Yad08/SmartLockV1](https://github.com/Yad08/SmartLockV1) | 1 | HTML | Hacking an Amazon Touchscreen Lock — office door  auto-locks and the touchpad is slow to wake. Bu… |
| 506 | [ymvnby-alt/ESP32MotiondetectionWIP](https://github.com/ymvnby-alt/ESP32MotiondetectionWIP) | 1 | C++ | WiFi CSI + BLE motion detection using an ESP32 and a Qt6 desktop app. Sniffs channel state varian… |
| 507 | [YoungRyx/ESP-32-wifi-deauther-](https://github.com/YoungRyx/ESP-32-wifi-deauther-) | 1 | — | This is ESP-32 wifi deuather, using for disconnect all the device that connecting to the wifi rou… |
| 508 | [ysfhmtky/ESP32-Wifi-Deauther](https://github.com/ysfhmtky/ESP32-Wifi-Deauther) | 1 | C |  |
| 509 | [zidhuxdev/WiSpam](https://github.com/zidhuxdev/WiSpam) | 1 | C++ | WiSpam —ESP32 WiFi Beacon Spammer. Broadcasts fake phone-model hotspot SSIDs. |
| 510 | [41vi4p/WiFi_Monitor](https://github.com/41vi4p/WiFi_Monitor) | 0 | C | WiFi_Monitor — Advanced WiFi security monitoring and threat detection system for ESP32-C6. Real-t… |
| 511 | [4min4yed/WIFI32-ESP32-Embedded-WIFI-Hacking](https://github.com/4min4yed/WIFI32-ESP32-Embedded-WIFI-Hacking) | 0 | C++ | Utilizing ESP32's 2.4 GHz Wifi card to conduct active and passive network sniffinf as welle as Do… |
| 512 | [7yasin/esp-synapse](https://github.com/7yasin/esp-synapse) | 0 | — | A distributed cybersecurity platform using low-cost ESP32/ESP8266 devices as centrally managed ag… |
| 513 | [aayush-xid-su/Esp32-Horcrux](https://github.com/aayush-xid-su/Esp32-Horcrux) | 0 | C++ | A comprehensive collection of ESP32 tools, scripts, and utilities for wireless security research,… |
| 514 | [abdullahmehboob671-pixel/HydroSentinel-EdgeAI-Flood-Warning-Node](https://github.com/abdullahmehboob671-pixel/HydroSentinel-EdgeAI-Flood-Warning-Node) | 0 | C++ | Low-cost, off-grid Edge-AI flood early warning node powered by ESP32-S3, Edge Impulse TinyML, and… |
| 515 | [abhi96bold/esp32-wifi-and-bluetooth-deauther-with-scroling-function](https://github.com/abhi96bold/esp32-wifi-and-bluetooth-deauther-with-scroling-function) | 0 | — |  |
| 516 | [abhinai2244/BLE-WIFI-JAMMER](https://github.com/abhinai2244/BLE-WIFI-JAMMER) | 0 | C++ | This project contains firmware for a Bluetooth jammer using an ESP32 and NRF24L01 radio modules |
| 517 | [Adii3310/ESP32__jammer](https://github.com/Adii3310/ESP32__jammer) | 0 | C++ | this is the code for the ESP32 development board for programming it for the jammer this ESP32 jam… |
| 518 | [AhMahPort/ESP32-Wifi-Attack-Detector](https://github.com/AhMahPort/ESP32-Wifi-Attack-Detector) | 0 | C++ | A defensive Wireless Intrusion Detection System (WIDS) on the ESP32 |
| 519 | [AJ39210/Esp32-based-os-WiFi-jammer](https://github.com/AJ39210/Esp32-based-os-WiFi-jammer) | 0 | — | Nothing to see here maybe read "read me.md |
| 520 | [AkeFPU/RF-Signal-intrution-system-using-ESP32-and-Arduino-](https://github.com/AkeFPU/RF-Signal-intrution-system-using-ESP32-and-Arduino-) | 0 | C++ | An AI-powered RF spectrum monitor and intrusion detection system. Uses an Arduino and nRF24L01s f… |
| 521 | [akshay-j01/esp32-wifi-pentest-eviltwin](https://github.com/akshay-j01/esp32-wifi-pentest-eviltwin) | 0 | C++ | ESP32-based Wi-Fi security awareness project demonstrating rogue access point and captive portal … |
| 522 | [AlanArantes/ESP32-BlueJammer](https://github.com/AlanArantes/ESP32-BlueJammer) | 0 | — | The ESP32-BlueJammer (Bluetooth jammer, BLE jammer, WiFi jammer, RC jammer) disrupts 2.4GHz commu… |
| 523 | [Aley3567/wifi-deauth-sentinel](https://github.com/Aley3567/wifi-deauth-sentinel) | 0 | Python | ESP32 + LLM powered WiFi Deauth attack detection system |
| 524 | [alfredo-allan/EvilTwinAttack](https://github.com/alfredo-allan/EvilTwinAttack) | 0 | HTML | Ataque Via ESP32 Redes Wifi |
| 525 | [Amalhameed-stack/Wifi-Bluetooth-classic-and-BLE-jammer-using-one-nRF24L01-module-and-esp32](https://github.com/Amalhameed-stack/Wifi-Bluetooth-classic-and-BLE-jammer-using-one-nRF24L01-module-and-esp32) | 0 | — | This project is for educational purposes only |
| 526 | [AmazingMoaaz/SpecterOS](https://github.com/AmazingMoaaz/SpecterOS) | 0 | C++ | ESP32 2.4 GHz RF jammer — a dual-radio, dual-core burst-hopping engine driven by 3 buttons and a … |
| 527 | [amirfazari01-commits/ESP32-WiFi-Jammer-Detection-Dashboard](https://github.com/amirfazari01-commits/ESP32-WiFi-Jammer-Detection-Dashboard) | 0 | HTML | Real-time WiFi monitoring and abnormal connectivity detection system using ESP32, Firebase, and a… |
| 528 | [AndiMue/ESP32_NimBLE-Sniffer_v0_Radar](https://github.com/AndiMue/ESP32_NimBLE-Sniffer_v0_Radar) | 0 | C++ | Sniffs Bluetooth devices in your environment |
| 529 | [Ano-sys/ESP32WiFiPolluter](https://github.com/Ano-sys/ESP32WiFiPolluter) | 0 | C | This projects main purpose was to get into ESP-IDF and have some fun with polluting the WiFi spec… |
| 530 | [Anonymousme00/ESP32-Single-nRF24-Remote-Controller](https://github.com/Anonymousme00/ESP32-Single-nRF24-Remote-Controller) | 0 | C++ | Arduino Uno remote controller with 2.4" TFT touch display for ESP32 RF jammer via nRF24L01+ |
| 531 | [ArdNU/OMEGA-Device](https://github.com/ArdNU/OMEGA-Device) | 0 | — | Ultimate ESP32-S3 Multi-tool DIY device: WiFi, Bluetooth, Sub-Ghz RF, IR, NFC, GPS. Open-source f… |
| 532 | [ArjunPavanje/ESP32_WiFi_Attacks](https://github.com/ArjunPavanje/ESP32_WiFi_Attacks) | 0 | C++ |  |
| 533 | [arjuntanwar/espbox](https://github.com/arjuntanwar/espbox) | 0 | C++ | This is a comprehensive ESP32-based multi-tool firmware with 19+ modules including WiFi attacks, … |
| 534 | [Aromalajith8/Bluject](https://github.com/Aromalajith8/Bluject) | 0 | C++ | An open-source, multi-OS BLE HID keystroke injection tool built for the ESP32. Features an air-ga… |
| 535 | [ashikurrafi/esp32s3-wifi-pentest](https://github.com/ashikurrafi/esp32s3-wifi-pentest) | 0 | C |  |
| 536 | [AtaCanYmc/Loki-Esp32](https://github.com/AtaCanYmc/Loki-Esp32) | 0 | C | Esp32 device for basic wifi examples |
| 537 | [avinashyadav143210-lab/-Bt-wifi-jammerr](https://github.com/avinashyadav143210-lab/-Bt-wifi-jammerr) | 0 | — | Bluetooth and wifi  jammer by using ESP32 |
| 538 | [AyushDeep117/Lo-Ra-based-Crowd-Instability-Detector-using-Distributed-Sensor-n-w-](https://github.com/AyushDeep117/Lo-Ra-based-Crowd-Instability-Detector-using-Distributed-Sensor-n-w-) | 0 | C++ | An internet-independent edge-computing sensor network using ESP32, LoRa (SX1278), and multi-senso… |
| 539 | [b-dorsal/arduino-esp32-rf-hacking](https://github.com/b-dorsal/arduino-esp32-rf-hacking) | 0 | C++ | A small project for capturing RF remote control signals and replaying them via ESPHome powered ES… |
| 540 | [bilal-robotics/-WiFi-BLE-Jammer](https://github.com/bilal-robotics/-WiFi-BLE-Jammer) | 0 | C++ | Yeh ek WiFi + BLE Jammer ka Arduino code hai jo ESP32 aur 2x NRF24L01 modules use karta hai. |
| 541 | [billjuv/OMG-ESP32-BLE_govee_sniffer](https://github.com/billjuv/OMG-ESP32-BLE_govee_sniffer) | 0 | — | Monitoring Govee Thermo-Hygrometer sensors using OpenMQTTGateway |
| 542 | [blacksnakeCYS/BlackSnake_wifi](https://github.com/blacksnakeCYS/BlackSnake_wifi) | 0 | C++ | Wifi hack for esp32 |
| 543 | [boydjawun/WiFi-Deauthentication-Attack-ESP32-Aircrack-ng](https://github.com/boydjawun/WiFi-Deauthentication-Attack-ESP32-Aircrack-ng) | 0 | — | Deauthenticating devices from an ESP32 SoftAP using Aircrack-ng on Kali Linux with an AR9271 WiFi… |
| 544 | [brycedc/esp32-blackout](https://github.com/brycedc/esp32-blackout) | 0 | C | ESP32 Pentest Wifi Tool |
| 545 | [bytecod3/RedZone-HackerBadge](https://github.com/bytecod3/RedZone-HackerBadge) | 0 | — | A DIY ESP32 hacker badge with Wi-Fi/Bluetooth meshing, an OLED, and stealthy CTF challenges and p… |
| 546 | [chonada/EmbedOS](https://github.com/chonada/EmbedOS) | 0 | C | A from-scratch ESP-IDF + FreeRTOS OS for the LilyGO T-Embed CC1101 (ESP32-S3): app launcher, sub-… |
| 547 | [claculator/deauther](https://github.com/claculator/deauther) | 0 | C++ | ESP32 Wifi deauther with extra features, uses SSD1306 display and 3 buttons |
| 548 | [clopso/esp32-rfm69-ook-cloner](https://github.com/clopso/esp32-rfm69-ook-cloner) | 0 | C | OOK Cloner with ESP32 and RFM69 |
| 549 | [ComputerScienceHouse/imagine2022-embedded](https://github.com/ComputerScienceHouse/imagine2022-embedded) | 0 | C | The Sniffer ESP32 App. Forms a mesh net and looks for tags. |
| 550 | [cvantienen/Esp32Subghz](https://github.com/cvantienen/Esp32Subghz) | 0 | C++ |  |
| 551 | [cwolfe1080/OpenCircuit](https://github.com/cwolfe1080/OpenCircuit) | 0 | C++ | An open-source arcade racing game for the PyBadge, featuring custom community-made tracks, online… |
| 552 | [Cyber-Squad-CST/WiFi-Pentest-Kit-Flasher](https://github.com/Cyber-Squad-CST/WiFi-Pentest-Kit-Flasher) | 0 | — | ​An automated cross-platform tool to seamlessly flash custom firmware, Deauther scripts, and secu… |
| 553 | [cyph-zz/RF-Pennywise](https://github.com/cyph-zz/RF-Pennywise) | 0 | C++ | ESP32 + nRF24L01x RF toolkit: jamming, WiFi/BLE scanning, spectrum analysis & security-awareness … |
| 554 | [daboynb/wps-catcher](https://github.com/daboynb/wps-catcher) | 0 | C | ESP32 firmware for WPS attacks with captive web UI (SoftAP + WebSocket) |
| 555 | [danaahmadifar/wifi-signal-tester-mit-esp32-support](https://github.com/danaahmadifar/wifi-signal-tester-mit-esp32-support) | 0 | Python | WLAN Signal-Tester und Netzwerk-Diagnosesystem mit ESP32 (Promiscuous Sniffer & Bluetooth SPP) un… |
| 556 | [danialn000876/ESP32-wifi-deauth-detector](https://github.com/danialn000876/ESP32-wifi-deauth-detector) | 0 | C++ | ESP32-based passive Wi-Fi deauth attack detector and instrusion detection system (IDS) |
| 557 | [daykiller-viann/esp32D4yk1ll3rsec](https://github.com/daykiller-viann/esp32D4yk1ll3rsec) | 0 | — | alat peretasan ,jammer bluetooth attack ,deauther,beacon spam ,auth spam |
| 558 | [Denilxavier/esp32-Marauder](https://github.com/Denilxavier/esp32-Marauder) | 0 | — | ESP32-based wireless tool for both offensive testing and defensive detection deauth attacks, rogu… |
| 559 | [Diksha-Deshmukh/wifi-threat-detector](https://github.com/Diksha-Deshmukh/wifi-threat-detector) | 0 | Python | Django-based Wi‑Fi security monitoring system for detecting rogue access points, evil twin attack… |
| 560 | [divisionind/hackquad](https://github.com/divisionind/hackquad) | 0 | HTML | the hackable open-source esp32 wifi controlled quadcopter |
| 561 | [douglasrolim/bruce-gate-relay](https://github.com/douglasrolim/bruce-gate-relay) | 0 | TypeScript | Open your own RF gates from anywhere: a Cloudflare Worker relay + a Bruce firmware module for Sub… |
| 562 | [ducokaptein-cyber/esp-32-sub-ghz-scanner](https://github.com/ducokaptein-cyber/esp-32-sub-ghz-scanner) | 0 | — |  a esp32 u with a 0.96 oled screen and a cc1101 moudle to scan wifi for sub ghz devices. |
| 563 | [eirode/Smart-RFID-lock](https://github.com/eirode/Smart-RFID-lock) | 0 | C++ | simple PCB design for Hack Club Half Life that works as an esp32-c3 controlled RFID lock |
| 564 | [ELSHAB7UAHED/bin](https://github.com/ELSHAB7UAHED/bin) | 0 | C++ | BARA - ESP32 WiFi Security Testing Tool. Advanced WiFi scanner with hacker-style web interface fo… |
| 565 | [embededbuild/Mona-Lisa](https://github.com/embededbuild/Mona-Lisa) | 0 | — | a esp32 device that can do WiFi/BLE base attacks and also have the ability to READ/WRITE to card/… |
| 566 | [Encad/esp32-tram](https://github.com/Encad/esp32-tram) | 0 | — | Compact ESP32-S3 multitool featuring CC1101 (Sub-GHz) and NRF24L01 (2.4 GHz) hardware modules. |
| 567 | [Eren-Oztk/esp32-wifi-bluetooth-scanner](https://github.com/Eren-Oztk/esp32-wifi-bluetooth-scanner) | 0 | C++ | ESP32-based scanner that detects nearby Wi-Fi and Bluetooth devices for local network analysis. |
| 568 | [etherift/esp32-wifi-jammer](https://github.com/etherift/esp32-wifi-jammer) | 0 | — |  |
| 569 | [Fir3n0x/ESPion32](https://github.com/Fir3n0x/ESPion32) | 0 | Kotlin | ESPion32 is an ESP32 project which uses an Android application to set up wifi attacks on the prov… |
| 570 | [GHOST-WEB-spec/SPECTER](https://github.com/GHOST-WEB-spec/SPECTER) | 0 | C++ | ESP32-based handheld pentesting device running JINX OS. WiFi, BLE, IR, Sub-GHz, NFC and more. |
| 571 | [hacking-in-kannada/esp32-wifi-jammer](https://github.com/hacking-in-kannada/esp32-wifi-jammer) | 0 | C++ |  |
| 572 | [haodiy12-code/esp32-c3-mini-jammer-jammer-ir-jammer-wifi-2.4](https://github.com/haodiy12-code/esp32-c3-mini-jammer-jammer-ir-jammer-wifi-2.4) | 0 | C++ | DIY Tactical Multi-Tool using ESP32-C3 SuperMini, nRF24L01+, 0.96" OLED, TV-B-Gone (400+ IR codes… |
| 573 | [harshapentu/esp32-wifi-pentest](https://github.com/harshapentu/esp32-wifi-pentest) | 0 | C | Educational Wi-Fi security testing project using ESP32. This repository focuses on understanding … |
| 574 | [HasanRsool/Simple-Signal-Jammer](https://github.com/HasanRsool/Simple-Signal-Jammer) | 0 | C++ | A simple WiFi & Bluetooth jammer using ESP32 & nRF24L01. |
| 575 | [Hata214/MultitoolEvilWifi](https://github.com/Hata214/MultitoolEvilWifi) | 0 | COBOL | This is the Evil tool for wifi 2.4GHz ( The bad of hardware cannot support for 5Ghz wifi), I'm ma… |
| 576 | [inevitable-lettus/esp32-rf-security-toolkit](https://github.com/inevitable-lettus/esp32-rf-security-toolkit) | 0 | — | Wireless-protocol security research platform on ESP32 — IR / RFID-NFC / sub-GHz / WiFi / BLE capt… |
| 577 | [InoshMatheesha/ZeNeOn-ESP32-WiFi-Framework](https://github.com/InoshMatheesha/ZeNeOn-ESP32-WiFi-Framework) | 0 | C++ | ZeNeOn is an ESP32-based WiFi security assessment framework that provides deauthentication attack… |
| 578 | [Isonimus/dupin](https://github.com/Isonimus/dupin) | 0 | C++ | A passive Wi-Fi security tool for the ESP-32 designed to observe, analyze, and detect anomalies i… |
| 579 | [Isonimus/esp32-arduino-adv-libs](https://github.com/Isonimus/esp32-arduino-adv-libs) | 0 | JavaScript | Patched ESP-IDF 5.5 + Arduino-core precompiled-libraries build. Provenance-pinned drop-in for fra… |
| 580 | [itz-mg/AirKick](https://github.com/itz-mg/AirKick) | 0 | — | Simple Wifi Deauther for Arduino Nano ESP32 |
| 581 | [jaringankantor/ESP32-C3-OpenSourceProject](https://github.com/jaringankantor/ESP32-C3-OpenSourceProject) | 0 | C++ | Kumpulan contoh program open source untuk ESP32-C3 dengan OLED 72x40 I2C. Berisi project Blink LE… |
| 582 | [JKCOM1911/Jammer-wifi-Bluetooth-esp32](https://github.com/JKCOM1911/Jammer-wifi-Bluetooth-esp32) | 0 | C++ |  |
| 583 | [jsuescun/espSAK](https://github.com/jsuescun/espSAK) | 0 | C | ESP32 Swiss Army Knife: wireless multi-tool, Flipper Zero capabilities at a fraction of the cost.… |
| 584 | [Kyzerer/KYZER-jammer-0.1](https://github.com/Kyzerer/KYZER-jammer-0.1) | 0 | C++ | Educational ESP32-based RF experimentation toolkit for exploring wireless communication concepts,… |
| 585 | [Lavictus/DeAuth](https://github.com/Lavictus/DeAuth) | 0 | C | ESP32-Wifi-Deauthentication |
| 586 | [Leakyli/2.4GHz-BLE-WIFI-SNIFFER](https://github.com/Leakyli/2.4GHz-BLE-WIFI-SNIFFER) | 0 | C | A 3-in-1 project that includes the use of ESP32U's built in Bluetooth and Wifi shared radio and a… |
| 587 | [leandrovitormoreira39012/GhostTek-PRE_ALPHA](https://github.com/leandrovitormoreira39012/GhostTek-PRE_ALPHA) | 0 | — | Firmware focado em wifi hacking, bluetooth jammig, nfc, lora e gps. Interface interativa. Inicial… |
| 588 | [Linyings/esp32_wifi_attack](https://github.com/Linyings/esp32_wifi_attack) | 0 | C |  |
| 589 | [LordSA/ESP32_STM32_RF](https://github.com/LordSA/ESP32_STM32_RF) | 0 | C++ | A low-power 2,4GHz wireless jammer based on ESP32 and nRF24LO1+PA+LNA (PlatformIO) |
| 590 | [Louistuis/concierge-phone](https://github.com/Louistuis/concierge-phone) | 0 | Python | A small candybar phone you click and talk to: script-built KiCad board, ESP32-P4, LTE, NFC, sub-G… |
| 591 | [lq-anarchy/open-hsdu](https://github.com/lq-anarchy/open-hsdu) | 0 | C++ | ESP32-S3 + CC1101 open replacement for a 418 MHz, 4800-baud serial-keyed base radio (the HSDU). I… |
| 592 | [Luiz123819/Projeto-Jammer-Bluetooth](https://github.com/Luiz123819/Projeto-Jammer-Bluetooth) | 0 | C++ | Desenvolvi do zero um projeto pessoal de hardware e firmware focado em análise de sinais em RF. O… |
| 593 | [Lukasz-Wrobel/GhostBeacon](https://github.com/Lukasz-Wrobel/GhostBeacon) | 0 | C++ | A WiFi Probe Request Sniffer and Visualizer using an ESP32 and a WS2812 RGB LED Ring. Designed to… |
| 594 | [lve-qw/espen](https://github.com/lve-qw/espen) | 0 | C++ | ESP32 based wifi/bluetooth pentest tool |
| 595 | [M-YiXi/ESP32-BusPirate__Chinese-Localization__A-versatile-hacker-terminal](https://github.com/M-YiXi/ESP32-BusPirate__Chinese-Localization__A-versatile-hacker-terminal) | 0 | C | 它支持通过串口终端或基于网页的CLI与各种数字协议（I2C、UART、1-Wire、SPI等）进行嗅探、发送、脚本编写及交互。它还与蓝牙、Wi-Fi、sub-GHz和RFID等无线协议通信。 |
| 596 | [majeedkhori/mk-oniondao-badge](https://github.com/majeedkhori/mk-oniondao-badge) | 0 | C++ | OnionDAO badge firmware & mods, ESP32-S3 e-paper badge: Onion OS Lua platform, ESP-Duel game, Sol… |
| 597 | [MAK554267/Blackout-2.4](https://github.com/MAK554267/Blackout-2.4) | 0 | C | Blackout 2.4 is a 5th Semester Network Security project that explores 2.4 GHz spectrum behavior a… |
| 598 | [manasashingade3/WiFi-jammer-detection](https://github.com/manasashingade3/WiFi-jammer-detection) | 0 | — | The Wi-Fi Jammer Detection System is an ESP32-based security device designed to detect Wi-Fi jamm… |
| 599 | [manojan282006/ESP-Wireless-Security-Tools](https://github.com/manojan282006/ESP-Wireless-Security-Tools) | 0 | — | ESP32-based wireless security tools and educational projects featuring embedded interfaces, hardw… |
| 600 | [mathish06/Sentinel-IDS](https://github.com/mathish06/Sentinel-IDS) | 0 | C++ | Portable passive WiFi Intrusion Detection System built on the ESP32. Detects Deauthentication flo… |
| 601 | [maviaydin044-max/BlueDrogon](https://github.com/maviaydin044-max/BlueDrogon) | 0 | — | This software carries out kill attacks using the ESP32's Wi-Fi antennas.    PLEASE ONLY ATTACK YO… |
| 602 | [MAvinash24/esp32-iot-fuzzing-lab](https://github.com/MAvinash24/esp32-iot-fuzzing-lab) | 0 | C++ | A comprehensive IoT security project demonstrating protocol fuzzing on ESP32 using both:  Bluetoo… |
| 603 | [mhommet/esp32_wifi](https://github.com/mhommet/esp32_wifi) | 0 | C++ | Ethical hacking ESP32 dev module |
| 604 | [milofrio066/Airlock](https://github.com/milofrio066/Airlock) | 0 | Python | IoT network monitoring system using ESP32, Python, and Flask. Detects Wi-Fi deauthentication atta… |
| 605 | [mriquelmec/ESP32-AI-SIEM-project](https://github.com/mriquelmec/ESP32-AI-SIEM-project) | 0 | Python | AI-powered SIEM that uses an ESP32 running Marauder firmware to collect Wi-Fi/BLE attack telemetr… |
| 606 | [mrsathish2005/Esp32_ble-wifi_jammer](https://github.com/mrsathish2005/Esp32_ble-wifi_jammer) | 0 | C++ |  |
| 607 | [mrsathish2005/Esp32_ble_wifi_jammer](https://github.com/mrsathish2005/Esp32_ble_wifi_jammer) | 0 | — |  |
| 608 | [mynameissami/Spectre](https://github.com/mynameissami/Spectre) | 0 | Python | S.P.E.C.T.R.E. is a hardware-integrated cybersecurity platform combining an ESP32 RF sniffer with… |
| 609 | [nandhakumard06-tech/Wolf-Jammer-IoT-](https://github.com/nandhakumard06-tech/Wolf-Jammer-IoT-) | 0 | — | Wolf Jammer IoT — ESP32-based WiFi security assessment tool for authorized pentesters. Supports d… |
| 610 | [Nikhil-Shivhare/BLE_Attack_ESP32](https://github.com/Nikhil-Shivhare/BLE_Attack_ESP32) | 0 | C++ |  |
| 611 | [NS-Projects-Unina/ESP32_Attack](https://github.com/NS-Projects-Unina/ESP32_Attack) | 0 | Assembly | Attacchi a reti WiFi sfruttando una scheda ESP32 |
| 612 | [Nyos3s/Nyos3s](https://github.com/Nyos3s/Nyos3s) | 0 | — | 0x / Nyos3s Siber Güvenlik Araştırmacısı & Geliştirici RF Sinyal Analizi & ESP32 Donanım Protokol… |
| 613 | [Officialsparxx/ESP32-Multitool](https://github.com/Officialsparxx/ESP32-Multitool) | 0 | — | ESP32-Multitool is an open-hardware, open-firmware handheld built around an ESP32-S3. Think “Flip… |
| 614 | [OjasUpadhyay/rf-flooding-detector](https://github.com/OjasUpadhyay/rf-flooding-detector) | 0 | C++ | Detection of 2.4 GHz RF Flooding and Jamming Using an ESP32 and nRF24L01+ |
| 615 | [open-is-all/berbel-remote](https://github.com/open-is-all/berbel-remote) | 0 | C++ | Berbel BFB 6bT Remote Bridge  ESP32-basiert Emulator für Berbel Dunstabzugshauben. Emuliert die B… |
| 616 | [oscarSardaM/WiFI-Attacks-ESP32](https://github.com/oscarSardaM/WiFI-Attacks-ESP32) | 0 | C++ |  |
| 617 | [OurLadyOfTheRevolution-droid/FOBworks_for_SGP-public](https://github.com/OurLadyOfTheRevolution-droid/FOBworks_for_SGP-public) | 0 | C++ | Standalone firmware for the SGP Card Mini: ESP32-S3 + CC1101 sub-GHz RKE capture, decode, replay … |
| 618 | [ozarkplateautachinidae54/cyber-controller](https://github.com/ozarkplateautachinidae54/cyber-controller) | 0 | — | Manage security hardware and ESP32 devices from a single dashboard for cyberdecks and field opera… |
| 619 | [P-ZINS/-ESP32-Marauder-M5Stick](https://github.com/P-ZINS/-ESP32-Marauder-M5Stick) | 0 | — | Déploiement d'un outil de pentest WiFi/Bluetooth portable sur microcontrôleur ESP32. |
| 620 | [PostboxRetinal/esp32_wifidemo](https://github.com/PostboxRetinal/esp32_wifidemo) | 0 | C++ | ESP32 WiFI pentest demo + OUI API lookup with cache implementation |
| 621 | [pranitdhanade-sys/ESP32-Wifi-attacker](https://github.com/pranitdhanade-sys/ESP32-Wifi-attacker) | 0 | Python |  |
| 622 | [RachappaB/wifi_hacking](https://github.com/RachappaB/wifi_hacking) | 0 | C++ | A hands-on Wi-Fi security research project exploring wireless attacks from beacon frames and pack… |
| 623 | [radoslawsmolinski-byte/ESP32-NetHunter-Pentest](https://github.com/radoslawsmolinski-byte/ESP32-NetHunter-Pentest) | 0 | — | Integrated Android + ESP32 + Backend pentest framework with OTG serial communication and WiFi pen… |
| 624 | [ralfs66/BLE-HID-HoneyPot](https://github.com/ralfs66/BLE-HID-HoneyPot) | 0 | C++ | This example turns the ESP32 into a Bluetooth LE Keyboard - Honeypot that runs RickRoll HID attac… |
| 625 | [recalde/garagewave](https://github.com/recalde/garagewave) | 0 | Python | Local-first ESPHome + CC1101 radio controller for compatible fixed-code garage doors, with Home A… |
| 626 | [retr0-dedsec2/Deauther-Simple-with-esp32](https://github.com/retr0-dedsec2/Deauther-Simple-with-esp32) | 0 | C++ | You want a good project ethical hacking with wifi deauth this repo is for you |
| 627 | [Reuben123t/ESP-Hacker](https://github.com/Reuben123t/ESP-Hacker) | 0 | C++ | ESP32 hacking tool through Wifi and Bluetooth |
| 628 | [rfypych/esp32-wifi-pentesting](https://github.com/rfypych/esp32-wifi-pentesting) | 0 | C |  |
| 629 | [Rima333475/Esp32-wifi-scanner](https://github.com/Rima333475/Esp32-wifi-scanner) | 0 | C++ | ESP32 WiFi scanner with Evil Twin detection |
| 630 | [roh7ops/ESP32-WiFi-Hacking-Lab](https://github.com/roh7ops/ESP32-WiFi-Hacking-Lab) | 0 | Python | ESP32 WiFi Hacking Lab |
| 631 | [rperezll/WiFiDeauthLab](https://github.com/rperezll/WiFiDeauthLab) | 0 | — | 🧪 Laboratorio experimental diseñado para explorar y documentar ataques de Deauth en redes Wi-Fi d… |
| 632 | [rrbaker00/BluetoothBaker](https://github.com/rrbaker00/BluetoothBaker) | 0 | C++ | A 2.4Ghz wifi and bluetooth jammer built on a ESP32 and 2 nrf24l01 antenna moduels that has multi… |
| 633 | [salehabbas99/ESP32-WiFi-Pentest](https://github.com/salehabbas99/ESP32-WiFi-Pentest) | 0 | C++ |  |
| 634 | [samirmakwana/RF-Scanner-SubGHz](https://github.com/samirmakwana/RF-Scanner-SubGHz) | 0 | — | A sub-GHz RF Scanner using ESP32 and C1101 with SMA antenna. |
| 635 | [Samoon19/ESP32-Wifi-Jammer](https://github.com/Samoon19/ESP32-Wifi-Jammer) | 0 | JavaScript |  |
| 636 | [santhoshreddy1600/esp32-deauther](https://github.com/santhoshreddy1600/esp32-deauther) | 0 | — | wifi deauther with esp32 |
| 637 | [scast3/deauth_detect](https://github.com/scast3/deauth_detect) | 0 | C++ | Detection and Localization of a Wifi deauth attack. Wireless communication between ESP32 devices … |
| 638 | [schedutydev/ESP32-S3-WiFi-Interceptor](https://github.com/schedutydev/ESP32-S3-WiFi-Interceptor) | 0 | — | ESP32-S3 WiFi penetration testing tool - Captive Portal, Network Scanner, and Deauthentication at… |
| 639 | [Seemab-Khan2336/Wireless-Interference-Analysis-ESP32](https://github.com/Seemab-Khan2336/Wireless-Interference-Analysis-ESP32) | 0 | Python | An experimental study on wireless interference and signal congestion in the 2.4 GHz ISM band. Usi… |
| 640 | [serplay/FishAI](https://github.com/serplay/FishAI) | 0 | Python | Giving a retro Billy Bass a new brain. ESP32 hardware hack featuring real-time lip-sync, Bluetoot… |
| 641 | [Shashi552/esp32-wifi-and-web-pentest-lab](https://github.com/Shashi552/esp32-wifi-and-web-pentest-lab) | 0 | C++ |  |
| 642 | [Shatwik7/ESP32-Quad-nRF24L01-Plus-Jammer-Multi-Band-2-4GHz-RF-Controller](https://github.com/Shatwik7/ESP32-Quad-nRF24L01-Plus-Jammer-Multi-Band-2-4GHz-RF-Controller) | 0 | — | ESP32-Quad-nRF24L01-Plus-Jammer is an open-source project for controlling four nRF24L01+ modules … |
| 643 | [ShellCMD101/Blackout-2.4](https://github.com/ShellCMD101/Blackout-2.4) | 0 | C | A sophisticated embedded cybersecurity project demonstrating real-world abuse, analysis, and expl… |
| 644 | [ShellCMD101/GHOST-WIRE-Multi-Protocol-IoT-Security-Diagnostic-Toolset](https://github.com/ShellCMD101/GHOST-WIRE-Multi-Protocol-IoT-Security-Diagnostic-Toolset) | 0 | HTML | A comprehensive, handheld IoT security diagnostic toolset built around the ESP32 platform. Ghost … |
| 645 | [ShivamMathtech/ESP32-Dual-NRF24L01-RF-Test-Communication-Platform](https://github.com/ShivamMathtech/ESP32-Dual-NRF24L01-RF-Test-Communication-Platform) | 0 | C++ | > **Safety / legal note:** This project is documented as an RF communication and laboratory test … |
| 646 | [Snyphix/Esp32-MultiTool](https://github.com/Snyphix/Esp32-MultiTool) | 0 | — | Educational purposes tool for wifi attacks build with esp32 with SSD1306 0.96 inch diaplay |
| 647 | [sqralsnwy77-glitch/esp32-wifi-pentest-tool](https://github.com/sqralsnwy77-glitch/esp32-wifi-pentest-tool) | 0 | — |  |
| 648 | [sriramnaidu2006/jammer-using-esp32](https://github.com/sriramnaidu2006/jammer-using-esp32) | 0 | — | A "jammer with ESP" generally refers to a DIY wireless interference or "deauther" project built o… |
| 649 | [StevenSeagalStreams/Cypher32](https://github.com/StevenSeagalStreams/Cypher32) | 0 | C++ | ESP32 Lora Wifi hacking game |
| 650 | [SurhommeLee/scaryrf-plus](https://github.com/SurhommeLee/scaryrf-plus) | 0 | — | The firmware for ESP32 has WiFi, BLE and SubGHz functions. |
| 651 | [susantks/Cam-Cypher-Dual-Recon](https://github.com/susantks/Cam-Cypher-Dual-Recon) | 0 | HTML | 2026 Ultimate WiFi & Bluetooth Pentesting Toolkit for Dual ESP32-CAM Security Audits |
| 652 | [suvo2007/Nrfboom_Btl.](https://github.com/suvo2007/Nrfboom_Btl.) | 0 | — | NRF BOOM — an ESP32-based multi-tool for nRF24, BLE, and WiFi security testing (scanner, jammer, … |
| 653 | [SystemProgrammerWizzard/remote-monitoring-device](https://github.com/SystemProgrammerWizzard/remote-monitoring-device) | 0 | C++ | Sub-GHz LoRa GPS Beacon with Environmental Monitoring and Web Dashboard A low-power ESP32-S3 LoRa… |
| 654 | [tehnomozg/esp32sniffing](https://github.com/tehnomozg/esp32sniffing) | 0 | — | This is a collection of ESP32 WiFi and Bluetooth sniffing tools. They're designed for use with th… |
| 655 | [tellfride/evil-twin-wifi](https://github.com/tellfride/evil-twin-wifi) | 0 | Roff | falso wifi para coleta de dados em ESP-32 |
| 656 | [texalpha973-rgb/Esp32-IR-RF-ble-wifi](https://github.com/texalpha973-rgb/Esp32-IR-RF-ble-wifi) | 0 | C++ |  ​1. CAPTURE IR ​2. SAVED CODES ​3. TV SWEEP ​4. AC KILLER ​5. TV ROULETTE ​6. SIGNAL FUZZER ​7. … |
| 657 | [ThaVEL-FPE12/Flipper-C3](https://github.com/ThaVEL-FPE12/Flipper-C3) | 0 | — | Flipper Zero For ESP32 C3 |
| 658 | [vancipher/Mini-Bluetooth-Jammer](https://github.com/vancipher/Mini-Bluetooth-Jammer) | 0 | — | Educational ESP32+nRF demo showing how RF interference affects Bluetooth devices. |
| 659 | [Vang-er/RF_series_killer](https://github.com/Vang-er/RF_series_killer) | 0 | — | it is a firmware that you lanuch on an esp32  and it starts to deauthincate all the nearby APs ra… |
| 660 | [vigiled/vigiled](https://github.com/vigiled/vigiled) | 0 | C++ | VIGILED is an open-source RGB LED device that turns your dashcam into an active visual deterrent.… |
| 661 | [WalderlanSena/prumoboard](https://github.com/WalderlanSena/prumoboard) | 0 | — | Prumo Board is an open hardware platform designed for education, research, and experimentation in… |
| 662 | [Wasyliy/subghz_live_scope](https://github.com/Wasyliy/subghz_live_scope) | 0 | C | flipper zero esp32 port application |
| 663 | [WomanInStem-Projects/RFID_Secure_Safe_WIth_ESP32](https://github.com/WomanInStem-Projects/RFID_Secure_Safe_WIth_ESP32) | 0 | C | Project where I will code and wire an RFID access controll system, build and 3D print its enclsur… |
| 664 | [Xhanos0/esp32-bleujammer-board-emensta-](https://github.com/Xhanos0/esp32-bleujammer-board-emensta-) | 0 | — | this is a circle vercion of the esp32 ble/low ble/wifi/rc jammer (its not my project but i tought… |
| 665 | [yashwanth270405-creator/ESP32-WiFi-Bluetooth-Jammer](https://github.com/yashwanth270405-creator/ESP32-WiFi-Bluetooth-Jammer) | 0 | — | ESP32-based BLE and Bluetooth jammer project for studying wireless communication, signal interfer… |
| 666 | [yfe404/polar_h10_spoofer](https://github.com/yfe404/polar_h10_spoofer) | 0 | C++ | ESP32 BLE spoofer that emulates a Polar H10 heart rate monitor with ECG streaming |
| 667 | [Yogi-076/ESP32-Evil-Twin-Wifi-Phishing](https://github.com/Yogi-076/ESP32-Evil-Twin-Wifi-Phishing) | 0 | HTML | Using ESP32 Wroom 32 module , Evil twin/wifi Phishing attack |
| 668 | [yohannesfanuel936-cpu/esp32s3-beacon-spammer](https://github.com/yohannesfanuel936-cpu/esp32s3-beacon-spammer) | 0 | C++ | this project its main function is using an esp 32 s3 for an attack called bacon spamming what thi… |
| 669 | [zero7608/wifi-dojo](https://github.com/zero7608/wifi-dojo) | 0 | C | Pocket-sized ESP32-C6 WiFi practice lab: a target AP and a companion attacker that generates 4-wa… |

### ESP8266

> 共 **301** 个项目，按 Stars 降序排列。

| # | 项目 | Stars | 语言 | 简介 |
|---:|---|---:|---|---|
| 1 | [SpacehuhnTech/esp8266_deauther](https://github.com/SpacehuhnTech/esp8266_deauther) | 15,109 | C | Affordable WiFi hacking platform for testing and learning |
| 2 | [martin-ger/esp_wifi_repeater](https://github.com/martin-ger/esp_wifi_repeater) | 5,292 | C | A full functional WiFi NAT Router (and now also a WiFi Repeater) |
| 3 | [SpacehuhnTech/WiFiDuck](https://github.com/SpacehuhnTech/WiFiDuck) | 3,345 | C++ | Wireless keystroke injection attack platform  |
| 4 | [samdenty/Wi-PWN](https://github.com/samdenty/Wi-PWN) | 1,746 | C | ESP8266 firmware for performing deauthentication attacks, with ease. |
| 5 | [spacehuhn/esp8266_beaconSpam](https://github.com/spacehuhn/esp8266_beaconSpam) | 1,393 | C++ | Creates up to a thousand WiFi access points with custom SSIDs. |
| 6 | [SpacehuhnTech/DeauthDetector](https://github.com/SpacehuhnTech/DeauthDetector) | 993 | C++ | Detect deauthentication frames using an ESP8266 |
| 7 | [kalanda/esp8266-sniffer](https://github.com/kalanda/esp8266-sniffer) | 631 | C++ | An easy experiment which uses the ESP8266 wifi module to look for near smartphones around you |
| 8 | [mcore1976/cc1101-tool](https://github.com/mcore1976/cc1101-tool) | 489 | C++ | RF tool based on CC1101 module and Arduino Pro Micro 8VMHz/3.3V. Allows using CLI with human read… |
| 9 | [visualapproach/WiFi-remote-for-Bestway-Lay-Z-SPA](https://github.com/visualapproach/WiFi-remote-for-Bestway-Lay-Z-SPA) | 417 | C++ | Hack - ESP8266 as WiFi remote control for Bestway Lay-Z spa Helsinki |
| 10 | [p3tr0s/PhiSiFi](https://github.com/p3tr0s/PhiSiFi) | 414 | C++ | WiFi Hacking with an ESP8266 - Deauth combined with Evil Twin attack  |
| 11 | [sankethj/ZiFi](https://github.com/sankethj/ZiFi) | 267 | C++ | Wifi hacking tool using ESP8266 ( Evil-twin method ) |
| 12 | [justcallmekoko/MarauderCentauri](https://github.com/justcallmekoko/MarauderCentauri) | 238 | C++ | A suite of WiFi/Bluetooth offensive and defensive tools for the ESP32 and ESP8266 |
| 13 | [BlackTechX011/DeautherX](https://github.com/BlackTechX011/DeautherX) | 210 | C | An open-source ESP8266_Deauther with customizable Evil Twin attack, and WiFi signal strength chec… |
| 14 | [ExploiTR/DeAutherDroid](https://github.com/ExploiTR/DeAutherDroid) | 170 | Java | Additional android app for SpaceHunn's ESP8266 DeAuther. |
| 15 | [0xless/433mhz_jam](https://github.com/0xless/433mhz_jam) | 163 | C++ | Simple WiFi controlled 433Mhz radio jammer based on ESP32/ESP8266 and FS1000A |
| 16 | [T-vK/alexa-jammer](https://github.com/T-vK/alexa-jammer) | 135 | C++ | Jamming the Wifi connection and microphones of all Amazon Echo and Google Home devices surroundin… |
| 17 | [justcallmekoko/ESP8266_Deauth_All](https://github.com/justcallmekoko/ESP8266_Deauth_All) | 106 | C++ | Arduino code for your ESP8266. Deauthenticate all clients from all access points |
| 18 | [DevKitty-io/Nugget-Invader](https://github.com/DevKitty-io/Nugget-Invader) | 101 | C | WiFi Attack + Recon Suite for the ESP8266 WiFi Nugget |
| 19 | [ThomDietrich/SenseoWifi](https://github.com/ThomDietrich/SenseoWifi) | 96 | C++ | Wifi'ify the Senseo coffee maker. Circuit and firmware for an internal Senseo hack to monitor and… |
| 20 | [shinyxn/ZeroTwin](https://github.com/shinyxn/ZeroTwin) | 79 | C++ | ESP8266 EvilTwin & deauther all-in-one WiFi pen-testing tools |
| 21 | [UserJoo9/WiFi-Nightmare](https://github.com/UserJoo9/WiFi-Nightmare) | 73 | Python |  WiFi-Nightmare: Hybrid WiFi Auditor. Python CLI Control \| ESP32/ESP8266 Hardware Acceleration \… |
| 22 | [michelangelomo/marauder-ui](https://github.com/michelangelomo/marauder-ui) | 69 | Vue | A modern web interface for the ESP32 Marauder firmware. |
| 23 | [larsjuhljensen/phatsniffer](https://github.com/larsjuhljensen/phatsniffer) | 67 | Python | Raspberry Pi + ESP8266 pHAT WiFi sniffer |
| 24 | [OCEANOFANYTHINGOFFICIAL/DevilTwin-NodeMCU](https://github.com/OCEANOFANYTHINGOFFICIAL/DevilTwin-NodeMCU) | 60 | C++ | ⚡ Perform Evil Twin Attack Using NodeMCU Board |
| 25 | [AlexLynd/ProbeHunter](https://github.com/AlexLynd/ProbeHunter) | 54 | C | An ESP8266 based promiscuous WiFi sniffer to track devices emitting probe requests |
| 26 | [herwonowr/CatchME](https://github.com/herwonowr/CatchME) | 46 | C | CatchME - WiFi Fun Box "Having Fun with ESP8266" |
| 27 | [shizakken/cheetah](https://github.com/shizakken/cheetah) | 44 | Rust | Portable WiFi/Bluetooth/RF-433MHz hacking tool |
| 28 | [albznw/Logitech-Z906-WiFi](https://github.com/albznw/Logitech-Z906-WiFi) | 43 | C++ | Breathe new life into your Logitech Z906 Surround system with this ESP8266-hack |
| 29 | [br101/esp-monitor](https://github.com/br101/esp-monitor) | 42 | C | Wifi sniffing on the ESP8266 |
| 30 | [Phreak87/ESPeensy-and-Peensy-Payload-Generator-ESP8266-Teensy-3.5-](https://github.com/Phreak87/ESPeensy-and-Peensy-Payload-Generator-ESP8266-Teensy-3.5-) | 42 | Visual Basic | Build your own Bad USB Stick for pentesting with wifi and dip switches |
| 31 | [c1ph3r-fsocitey/Interactive-Wi-Fi-Deauther](https://github.com/c1ph3r-fsocitey/Interactive-Wi-Fi-Deauther) | 41 | Python | Deauther Project can be used to:    Disconnect Devices from Networks,     and       Clone Networks |
| 32 | [techchipnet/WiFiDeauthDetectorNodeMCU](https://github.com/techchipnet/WiFiDeauthDetectorNodeMCU) | 40 | C++ | Detect deauthentication attack using NodeMCU |
| 33 | [Datalux/esp8266-deauther](https://github.com/Datalux/esp8266-deauther) | 37 | C++ | A simple WiFi deauther for ESP8266 |
| 34 | [ASP-29/WifiXv1.3](https://github.com/ASP-29/WifiXv1.3) | 33 | — | Source code for my project on youtube named WifiX Project,its just a simple esp8266 pentesting to… |
| 35 | [kissste/esp8266-Arduino-WifiSniffer](https://github.com/kissste/esp8266-Arduino-WifiSniffer) | 31 | Arduino | esp8266 Adruino Wifi Sniffer |
| 36 | [jah64/Rothult-ESPeasy](https://github.com/jah64/Rothult-ESPeasy) | 29 | — | Hacking an IKEA Rothult NFC lock to be remotely controlled by a ESP8266 WiFi module |
| 37 | [rw950431/ESP8266mini-sniff](https://github.com/rw950431/ESP8266mini-sniff) | 28 | Arduino | Wifi packet sniffer based on the ESP8266 chipset |
| 38 | [Ishanoshada/Esp32-Deauth](https://github.com/Ishanoshada/Esp32-Deauth) | 27 | Python | A Python tool for Wi-Fi deauthentication attacks using ESP32 with webserver firmware |
| 39 | [handiko/ESP12-MQTT-RF-Jammer](https://github.com/handiko/ESP12-MQTT-RF-Jammer) | 25 | C++ | A Simple ESP12 & AD9851 based RF Jammer which can be controlled using MQTT protocol |
| 40 | [johnkimdinh/wifi-jammer](https://github.com/johnkimdinh/wifi-jammer) | 25 | C | Build your own WiFi jammer with an ESP8266.  |
| 41 | [wirebits/WiFiSnare](https://github.com/wirebits/WiFiSnare) | 25 | C++ | A tool that captures 2.4GHz Wi-Fi passwords via Evil Twin attack. |
| 42 | [karanankit01/WifiJammer](https://github.com/karanankit01/WifiJammer) | 24 | C | Using esp8266 Module, attacking the different wifi network and creating fake . |
| 43 | [justcallmekoko/ROTA](https://github.com/justcallmekoko/ROTA) | 21 | — | A WiFi enabled Xbox One rapid-fire mod |
| 44 | [DX4GREY/esp8266_wifitools](https://github.com/DX4GREY/esp8266_wifitools) | 20 | C | This is a WiFi Tool which includes EvilTwin and Deauther, this tool is based on esp8266_deauther,… |
| 45 | [samphoerna/EvilTwin-ESP8266](https://github.com/samphoerna/EvilTwin-ESP8266) | 18 | C | A network attack using Evil Twin Framework paired in NodeMCU ESP8266 device to exploit vulnerabil… |
| 46 | [Luigi-Pizzolito/Sonic-Deauther](https://github.com/Luigi-Pizzolito/Sonic-Deauther) | 16 | C | ESP8266 Pen-testing Deauther made into a sonic screwdriver controller. |
| 47 | [balwantyadav1/WIFI-Deauther](https://github.com/balwantyadav1/WIFI-Deauther) | 15 | C | WiFi-Deauther: Wi-Fi security tool with ESP8266 for deauth attacks and monitoring. |
| 48 | [codewithharit/Deauther_With_Oled_Display](https://github.com/codewithharit/Deauther_With_Oled_Display) | 14 | — | Esp8266 Nodemcu Wifi Development Deauther With Oled Display |
| 49 | [John-Athanasopoulos/Wifi-Deauther-ESP8266-Tutorial](https://github.com/John-Athanasopoulos/Wifi-Deauther-ESP8266-Tutorial) | 14 | — | A tutorial on how to make a Wifi Deauther (with beacon and probe attacks included) with an ESP826… |
| 50 | [sidward35/Deauth-RickRollAP](https://github.com/sidward35/Deauth-RickRollAP) | 14 | Arduino | Performs a deauth attack and sends beacon frames to flood the list of available WiFi networks wit… |
| 51 | [t04glovern/traffic-cop](https://github.com/t04glovern/traffic-cop) | 14 | C++ | WiFi Beacon & Client sniffing pipeline for analysing the movements of Human Traffickers. |
| 52 | [usamahacker0/WIFI-Uchiha](https://github.com/usamahacker0/WIFI-Uchiha) | 14 | — | A WIFI Pentesting Tool ( WIFI Hacking ) with Powerfull tools. |
| 53 | [BlackTechX011/ESP8266_WIFI_PROBE_SNIFFER_Web_tool](https://github.com/BlackTechX011/ESP8266_WIFI_PROBE_SNIFFER_Web_tool) | 13 | HTML | a web based ESP8266 SNIFFER Flasher tool |
| 54 | [Kalmat/DSTIKE-SPACEHUHN-Deauther-Weather](https://github.com/Kalmat/DSTIKE-SPACEHUHN-Deauther-Weather) | 13 | C | WiFi Deauther and OpenWeatherMap station for a DSTIKE&SPACEHUHN V3 wristwatch (Arduino ESP8266) |
| 55 | [Ben-Sassi-Oussema/NODEMCU-DEAUTHER](https://github.com/Ben-Sassi-Oussema/NODEMCU-DEAUTHER) | 12 | — | This software allows you to easily perform a variety of actions to test 802.11 wireless networks … |
| 56 | [dfalt0/NodeMCU-ESP8266](https://github.com/dfalt0/NodeMCU-ESP8266) | 12 | C | This software allows you to perform a deauth attack with an ESP8266 against selected networks. Th… |
| 57 | [graylagx2/Customized_spacehuhn_DeAuther](https://github.com/graylagx2/Customized_spacehuhn_DeAuther) | 12 | HTML | A customized version of spacehuhns Deauther for the esp8266 Wifi module. This folder contains the… |
| 58 | [codewithharit/ESP8266-DEAUTHER-FILE](https://github.com/codewithharit/ESP8266-DEAUTHER-FILE) | 11 | — | WIFI JAMMER FILE ESP8266 |
| 59 | [pitube08642/Fluxion-on-ESP8266](https://github.com/pitube08642/Fluxion-on-ESP8266) | 11 | — | A advance wifi hacking tool on esp8266 |
| 60 | [Ahmadreza1600/FSociety-Tool](https://github.com/Ahmadreza1600/FSociety-Tool) | 10 | — | FSociety Tool: WiFi Deauth, Beacon Spam, RF/IR jammer, code capture, TV-B-Gone, Evil Portal & gam… |
| 61 | [l740416/ESP8266-WifiSniffer](https://github.com/l740416/ESP8266-WifiSniffer) | 9 | Arduino | Wifi Sniffer for ESP8266 |
| 62 | [0x0806/wifi-deauther-esp8266](https://github.com/0x0806/wifi-deauther-esp8266) | 8 | C++ | This comprehensive suite combines cutting-edge WiFi attack vectors, Bluetooth Low Energy (BLE) ca… |
| 63 | [Aayush9029/esp8266_deauther](https://github.com/Aayush9029/esp8266_deauther) | 8 | — | Affordable WiFi hacking platform for testing and learning + Native iOS, watchOS support. |
| 64 | [berkantay/wirect-firmware](https://github.com/berkantay/wirect-firmware) | 8 | C++ | WiFi Sniffer with ESP8266 |
| 65 | [BlackTechX011/DeautherX-lib](https://github.com/BlackTechX011/DeautherX-lib) | 8 | C | The Unified ESP8266 Wi-Fi Security & Testing Library |
| 66 | [dev0root6/EvilTwin-ESP8266](https://github.com/dev0root6/EvilTwin-ESP8266) | 8 | C++ | 100% Working ESP8266 EVIL TWIN ATTACK. This code implements an ESP8266-based WiFi deauthenticatio… |
| 67 | [gdamdam/wifi-deauthdetector](https://github.com/gdamdam/wifi-deauthdetector) | 8 | C++ | WiFi Deauth Detector - a cute deauthentication detector for ESP8266 with OLED display |
| 68 | [gpimblott/ESP8266_Wifi_Analyst](https://github.com/gpimblott/ESP8266_Wifi_Analyst) | 8 | C++ | Command line Wifi utilities on an ESP 8266.  Includes scanning, fake beacons and deauth. |
| 69 | [HiddenSwagMan/ESP8266-BrutalDeauth](https://github.com/HiddenSwagMan/ESP8266-BrutalDeauth) | 8 | Arduino | This allow your ESP8266 to deauth every WiFi devices as long as it's turned on ! |
| 70 | [HUGOW04/FakeWifi](https://github.com/HUGOW04/FakeWifi) | 8 | C++ | Phishing is a type of social engineering where an attacker sends a fraudulent (e.g., spoofed, fak… |
| 71 | [parsapoorsh/waveduino](https://github.com/parsapoorsh/waveduino) | 8 | C++ | replay attack 433Mhz RF using ESP8266 (or arduino) |
| 72 | [bertrik/espwifisniff](https://github.com/bertrik/espwifisniff) | 7 | C++ | Experiment to create a wifi sniffer based on an ESP8266 |
| 73 | [codewithharit/WIFI-Jammer-FILE](https://github.com/codewithharit/WIFI-Jammer-FILE) | 7 | — | ESP8266 Node MCU Jammer File |
| 74 | [nathshobhan/wifijammer_nodemcu](https://github.com/nathshobhan/wifijammer_nodemcu) | 7 | C | code to jam the whole wifi network using cloning technique |
| 75 | [pepeangell5/ESP8266-DEAUTHER](https://github.com/pepeangell5/ESP8266-DEAUTHER) | 7 | C | Deauther de laboratorio para ESP8266 enfocado en pruebas educativas de seguridad WiFi 2.4 GHz, an… |
| 76 | [Qbaa134/Beacon-Spammer](https://github.com/Qbaa134/Beacon-Spammer) | 7 | HTML | The Beacon Spammer is a tool that sends fake Wi-Fi beacon frames, making it look like multiple wi… |
| 77 | [toprakahmetaydogmus/esp8266-nrf24-jammer](https://github.com/toprakahmetaydogmus/esp8266-nrf24-jammer) | 7 | C++ | ESP8266 + nRF24L01 2.4GHz RF Signal Testing, Spectrum Analysis & Simulation Tool with Web UI |
| 78 | [yadhumanikandan/esp8266-wifi-hacking-device](https://github.com/yadhumanikandan/esp8266-wifi-hacking-device) | 7 | Rich Text Format | An all in one wifi hacking tool using esp8266 using micropython |
| 79 | [AtherNet29/Esp8266-Deauther-2.4-Ghz-Jammer-Bluetooth](https://github.com/AtherNet29/Esp8266-Deauther-2.4-Ghz-Jammer-Bluetooth) | 6 | — | 🎯 ESP8266 Deauther & BT Jammer. Features: Evil Twin, Auto-Password Verify, Beacon Spam, Rogue AP,… |
| 80 | [AyushGorlawar/ESP-Hidden-Features](https://github.com/AyushGorlawar/ESP-Hidden-Features) | 6 | C++ | Explore hidden features, stealth tricks, and ethical hacks using ESP8266/ESP32 — beyond basic IoT… |
| 81 | [brighteyekid/ESP8266-WiFi-Pentesting-Tool](https://github.com/brighteyekid/ESP8266-WiFi-Pentesting-Tool) | 6 | C++ | ESP8266-WiFi-Pentesting-Tool  A comprehensive WiFi security testing toolkit for ESP8266 |
| 82 | [david-griffith/esp8266-sniffer](https://github.com/david-griffith/esp8266-sniffer) | 6 | C | A simple sniffer for Aeroscout wifi tags |
| 83 | [Debajyoti0-0/Arduino-WiFi-Deauther-Detector](https://github.com/Debajyoti0-0/Arduino-WiFi-Deauther-Detector) | 6 | C++ | Detect deauthentication attack using NodeMCU without using any external leds. |
| 84 | [Ethical-Vikash/WiFi-Phiser](https://github.com/Ethical-Vikash/WiFi-Phiser) | 6 | C++ | WiFi Hacking with an ESP8266 - Deauther & Evil-Twin Attack |
| 85 | [hermit148/Hermit-ESP8266-Mint-Box-WIFI-Pentest](https://github.com/hermit148/Hermit-ESP8266-Mint-Box-WIFI-Pentest) | 6 | — | Hermit-ESP8266-Mint-Box-Attack And Reserch Tool |
| 86 | [rahuldudi0713/WiFi_hacking_Device](https://github.com/rahuldudi0713/WiFi_hacking_Device) | 6 | C++ | Hack any wifi with NodeMCU esp8266 Board |
| 87 | [saifxionty/Evil-Twin-And-Deauther](https://github.com/saifxionty/Evil-Twin-And-Deauther) | 6 | — | Turns ESP8266 into a WiFi attack tool. Performs deauth attacks, creates Evil Twin hotspots, and c… |
| 88 | [slundell/wifi-presence](https://github.com/slundell/wifi-presence) | 6 | Python | Simple presence detection by passive wifi sniffing. esp8266 and Python |
| 89 | [aidevsurya/ESP8266-Captive-Portal](https://github.com/aidevsurya/ESP8266-Captive-Portal) | 5 | C++ | This is simple program for NodeMCU, ESP8266, ESP32, ESP-12 F/E to perform Captive Portal Attack f… |
| 90 | [anudeepND/esp8266_2.0.0](https://github.com/anudeepND/esp8266_2.0.0) | 5 | — | esp8266 SDK 2.0.0 for ARM architecture.  |
| 91 | [barratt/esp8266-wifi-tracking](https://github.com/barratt/esp8266-wifi-tracking) | 5 | C++ | Gives the ESP8266 the ability to sniff WiFi packets in the air and report back to a server for fu… |
| 92 | [dappoo/PEvilTwin](https://github.com/dappoo/PEvilTwin) | 5 | C++ | ESP8266-based Evil Twin attack tool for WiFi network testing and security research. |
| 93 | [jcldf/deaulth-all-for-wifi-kit-8](https://github.com/jcldf/deaulth-all-for-wifi-kit-8) | 5 | C++ | this a mod from https://github.com/justcallmekoko/ESP8266_Deauth_All |
| 94 | [malvidous/HELLISH](https://github.com/malvidous/HELLISH) | 5 | — | The code is for an ESP8266-based board, offering WiFi management, deauthentication attacks, fake … |
| 95 | [Pa1kumar1997/Wifijammer-Deauther](https://github.com/Pa1kumar1997/Wifijammer-Deauther) | 5 | — | Wifi Jammer code to Flash esp8266 Deauther |
| 96 | [Sandesh-Basnet/Wifi-Jammer-with-ESP-8266](https://github.com/Sandesh-Basnet/Wifi-Jammer-with-ESP-8266) | 5 | C | Wi-Fi jamming with ESP8266 for educational purposes. Disrupts networks. Use responsibly. |
| 97 | [tejasvane/Blu-WIFI_Jammer_Using_ESP8266](https://github.com/tejasvane/Blu-WIFI_Jammer_Using_ESP8266) | 5 | C++ | An ESP8266-based microproject to temporarily disrupt Wi-Fi (deauth) and Bluetooth signals, featur… |
| 98 | [Unresponsive-hydrangeafamily234/DeautherX-lib](https://github.com/Unresponsive-hydrangeafamily234/DeautherX-lib) | 5 | C | Provide a unified ESP8266 library for Wi-Fi security assessment and testing with core tools from … |
| 99 | [yuno009/ESP32S3-USB-Keyboard-To-BLE](https://github.com/yuno009/ESP32S3-USB-Keyboard-To-BLE) | 5 | C++ | 🔄 Transform any USB keyboard into a Bluetooth device with ESP32-S3, allowing seamless connections… |
| 100 | [Amulong1/ESP8266_WiFi_Killer](https://github.com/Amulong1/ESP8266_WiFi_Killer) | 4 | — | A project that utilizes ESP8266 for network attacks and interference. |
| 101 | [cheattheweb/ESP-WiFi-Deauther-and-Detector](https://github.com/cheattheweb/ESP-WiFi-Deauther-and-Detector) | 4 | C++ | This project is a proof of concept on WiFi deauth detection system. |
| 102 | [Erennkrb/ESP32-and-ESP8266-DeAuthWifi](https://github.com/Erennkrb/ESP32-and-ESP8266-DeAuthWifi) | 4 | C++ | Educational proof-of-concept demonstrating Wi-Fi deauthentication attacks using ESP32 and ESP8266… |
| 103 | [heylizz/Wifi-Deauther-with-NodeMCU-ESP8266](https://github.com/heylizz/Wifi-Deauther-with-NodeMCU-ESP8266) | 4 | — | Scan for WiFi devices, block selected connections, create dozens of networks and confuse WiFi sca… |
| 104 | [Informatic/Sming_WiFi_Monitor](https://github.com/Informatic/Sming_WiFi_Monitor) | 4 | C++ | ESP8266 + Sming WiFi Sniffer example |
| 105 | [jaspreet-infosec/WiFi-Deauthenticator](https://github.com/jaspreet-infosec/WiFi-Deauthenticator) | 4 | Shell | The Wi-Fi Jammer Tool is a comprehensive bash script crafted to streamline the management and dep… |
| 106 | [kostandinvllahu/ESP8266-BUG-FIXED](https://github.com/kostandinvllahu/ESP8266-BUG-FIXED) | 4 | — | ESP8266 wifi jammer had a bug so i fixed the bug |
| 107 | [lolue/ESP8266-ZeroTwo-Massive-Deauther](https://github.com/lolue/ESP8266-ZeroTwo-Massive-Deauther) | 4 | C++ | ESP8266 Wifi Deauther Massive With Oled Display (and have the anime waifu zero two😉) |
| 108 | [my-project-droid/Hackbat-MultiToolhacking-OS1](https://github.com/my-project-droid/Hackbat-MultiToolhacking-OS1) | 4 | C++ | An open-source multi-tool firmware for the RP2040 Hackbat. Unifies sub-1GHz RF (CC1101), NFC (PN5… |
| 109 | [peterfillmore/ThreatbuttFreeWifi](https://github.com/peterfillmore/ThreatbuttFreeWifi) | 4 | C | ESP8266 based free wifi point - integrates advanced Threatbutt threaty threat zero day detection … |
| 110 | [samdvl/Esp8266-Wifi-Sniffer](https://github.com/samdvl/Esp8266-Wifi-Sniffer) | 4 | C | This software make it possible to scan wifi devices with the esp8266. It contols the TTGO 0.91 ol… |
| 111 | [xiv3r/esp8266-deauth-detector](https://github.com/xiv3r/esp8266-deauth-detector) | 4 | C++ | esp8266 wifi jammer detector |
| 112 | [balwantyadav1/ESP8266-WiFiPhisher](https://github.com/balwantyadav1/ESP8266-WiFiPhisher) | 3 | C++ | ESP8266‑WiFiPhisher — ESP8266‑based rogue access‑point for Wi‑Fi phishing using captive portal an… |
| 113 | [boubli/Wifi-Jammer-NodeMCU](https://github.com/boubli/Wifi-Jammer-NodeMCU) | 3 | C | ESP8266 WiFi Deauther & Jammer for NodeMCU - Scan networks, perform deauthentication attacks, and… |
| 114 | [codyaj/ReaperBoard](https://github.com/codyaj/ReaperBoard) | 3 | C++ | Wireless pentesting toolkit: ESP8266-based Lite and CM4-based Full version in development. |
| 115 | [darrylburke/heltec_wifi_8_esp8266_LCD_deauth_detector](https://github.com/darrylburke/heltec_wifi_8_esp8266_LCD_deauth_detector) | 3 | C | ESP8266 Deauth Detector using the LCD on the Heltec Wifi 8 board |
| 116 | [dbarzin/FeatherDeauthDetector](https://github.com/dbarzin/FeatherDeauthDetector) | 3 | C++ | This is a tool for security operation teams to detect Wifi Deauth  actions made by attackers on n… |
| 117 | [EinsPommes/ArithOS](https://github.com/EinsPommes/ArithOS) | 3 | C | ArithOS: A stealth pentesting toolkit disguised as a calculator for PicoCalc hardware. Features W… |
| 118 | [Esther7171/ESP8266-Deauther](https://github.com/Esther7171/ESP8266-Deauther) | 3 | — | ESP8266 / NodeMCU WiFi deauther. Scan, deauth, beacon and probe flooding on 2.4GHz. Step by step … |
| 119 | [FuflyPaladium/NodeMCU-WifiJammer](https://github.com/FuflyPaladium/NodeMCU-WifiJammer) | 3 | Python | THIS TOOL IS FOR SETUP NODEMCU WIFI JAMMER  YOU CAN USE THIS TOOL ON WINDOWS  IF IS NOT WORK THEN… |
| 120 | [linglingltd/wifi-remote](https://github.com/linglingltd/wifi-remote) | 3 | C++ | Hacked Ledvance SMART+ Wifi-Remote firmware for ESP8266 |
| 121 | [RFIunknown/BocchiTwin](https://github.com/RFIunknown/BocchiTwin) | 3 | C | WiFi Security Audit Tool (v1.0 Alpha) menggunakan ESP8266. Mendukung scanning, deauth-injection, … |
| 122 | [rzeldent/esp8266-deauther](https://github.com/rzeldent/esp8266-deauther) | 3 | C | Clone from SpaceHuhn wifi deauther |
| 123 | [shasradha/Orbit](https://github.com/shasradha/Orbit) | 3 | C | Wrist-worn WiFi security testing tool — ESP8266 + OLED in a modified SKMEI watch case. KiCad hard… |
| 124 | [terminat0r7031/ESP8266-WIFI-HACKING](https://github.com/terminat0r7031/ESP8266-WIFI-HACKING) | 3 | C++ |  |
| 125 | [thomaswilley/wifioutlets](https://github.com/thomaswilley/wifioutlets) | 3 | C++ | ESP8266/NodeMCU http-based server to control a hacked set of RF outlets from the internet. |
| 126 | [WhiskeyTangoHotel/Portable-ESP8266-WiFi-Sniffer-Arduino-IDE-](https://github.com/WhiskeyTangoHotel/Portable-ESP8266-WiFi-Sniffer-Arduino-IDE-) | 3 | — | Portable ESP8266 WiFi Sniffer (Arduino IDE) |
| 127 | [AaltoAsia/K1WifiGateway](https://github.com/AaltoAsia/K1WifiGateway) | 2 | C++ | Program for using ESP8266 to hack a certain 6LoWPAN to WiFi bridge system to use O-MI. |
| 128 | [akashdip2001/Wi-Fi-deauther-with-ESP8266-OLED-module](https://github.com/akashdip2001/Wi-Fi-deauther-with-ESP8266-OLED-module) | 2 | — | IOT with Cyber Security with WiFi deauther with esp8266 oled module |
| 129 | [allegorix/esp-wifi-radar-lab](https://github.com/allegorix/esp-wifi-radar-lab) | 2 | Python | ESP8266 + ESP32 promiscuous sniffers, 3D Wi-Fi radar, active scan, and audit toolkit |
| 130 | [AmandracOP/wifi-deauther](https://github.com/AmandracOP/wifi-deauther) | 2 | — | This is a program for a network deauther which can deauth,beacon and probe a network through a wi… |
| 131 | [amtzespinosa/esp8266-wifi-deauther](https://github.com/amtzespinosa/esp8266-wifi-deauther) | 2 | C | Today we're doing something different. We will leave the computer for a while and make something … |
| 132 | [AnthonyKNorman/ESP8266-Home-Assistant-RGB-Bulb](https://github.com/AnthonyKNorman/ESP8266-Home-Assistant-RGB-Bulb) | 2 | Python | This Micropython project is to Hack a TYWE3S board in a cheap WiFi RGB Bulb |
| 133 | [AnthonyKNorman/ESP8266-Home-Assistant-Smart-Socket](https://github.com/AnthonyKNorman/ESP8266-Home-Assistant-Smart-Socket) | 2 | Python | This Micropython project is to Hack a Hyleton313 cheap WiFi smart socket |
| 134 | [archrampart/zero-cmd](https://github.com/archrampart/zero-cmd) | 2 | JavaScript | Web-based command center for Flipper Zero — Screen mirror, file manager, Sub-GHz, NFC, IR, Bad US… |
| 135 | [ArtemAvanesov/Arduino-WIFI-Jammer](https://github.com/ArtemAvanesov/Arduino-WIFI-Jammer) | 2 | C | Arduino-WIFI-Jammer based on Nodemcu Lua Wi-Fi (Esp8266) |
| 136 | [AxGHaven/AxG_Haven-WiFi-Tool](https://github.com/AxGHaven/AxG_Haven-WiFi-Tool) | 2 | — | ESP8266-based portable WiFi audit tool with OLED UI, EvilTwin captive portal, deauth attack, NRF2… |
| 137 | [Azhar14/Jam_Digital_Pintar](https://github.com/Azhar14/Jam_Digital_Pintar) | 2 | C++ |  Jam digital "pintar" menggunakan modul WiFi ESP8266 dan display Dot Matrix LED MAX7219. Perangka… |
| 138 | [b-simjoo/esp8266-evil-wifi](https://github.com/b-simjoo/esp8266-evil-wifi) | 2 | — | Some hacking tools for esp8266 with arduino framework |
| 139 | [codesempai/WiFi-Hacking-Using-ESP8266](https://github.com/codesempai/WiFi-Hacking-Using-ESP8266) | 2 | C++ | WiFi Hacking Using ESP8266 Node MCU Wifi Development Board \| Captive portal \| Deauth |
| 140 | [CoolJuvenile/esp32-s3-wifi-killer](https://github.com/CoolJuvenile/esp32-s3-wifi-killer) | 2 | C++ | ESP32-S3 掌上 Wi-Fi 测试仪 · Deauth / Beacon Flood / Probe Flood，摇杆 + OLED 脱机操作，已从 ESP8266 Deauther 移植… |
| 141 | [diegojoel301/PwnArduinoAutomatron](https://github.com/diegojoel301/PwnArduinoAutomatron) | 2 | Python | Esta herramienta se encarga de hacer que tu placa Arduino Leonardo funcione como un Rubber Ducky … |
| 142 | [diyandexperiment/ShadowHawk-Pro](https://github.com/diyandexperiment/ShadowHawk-Pro) | 2 | — | ShadowHawk Pro is a powerful, all-in-one WiFi security testing tool built on the ESP8266 (NodeMCU… |
| 143 | [error0327/ESP8266-Deauther](https://github.com/error0327/ESP8266-Deauther) | 2 | C | ESP8266-Deauther Wifi Hacker |
| 144 | [eshwargit2/Kali_Deauther](https://github.com/eshwargit2/Kali_Deauther) | 2 | Python | Used to a  Esp8266 wifi deather flimeware based api access in to terminal line execution  |
| 145 | [gentlemencoder/Wifi-Jammer](https://github.com/gentlemencoder/Wifi-Jammer) | 2 | Pascal | convert nodemcu esp8266 to wifi signal cutter |
| 146 | [hixmfu/WIFI-TOOLKIT](https://github.com/hixmfu/WIFI-TOOLKIT) | 2 | HTML | 🔍 Simplify WiFi pentesting with WIFI-TOOLKIT, a utility that integrates essential tools like Airc… |
| 147 | [internettrashh/esp8266-wifi-deauter](https://github.com/internettrashh/esp8266-wifi-deauter) | 2 | C | my version of the wifi deauther compatible with chinese display modules |
| 148 | [Jevonte07/WIFI-DEauther-Watch](https://github.com/Jevonte07/WIFI-DEauther-Watch) | 2 | C | The Deauther Watch is a compact, wearable device built using the ESP8266 microcontroller that per… |
| 149 | [joe-speedboat/embedded.esp8266.wifi_deauth](https://github.com/joe-speedboat/embedded.esp8266.wifi_deauth) | 2 | C++ | ESP8266 Wifi Deauth IoT  for Arduino IDE (Tested with ESP-01) |
| 150 | [Mr-Zer00/Driver-nodeMCU-ESP8266](https://github.com/Mr-Zer00/Driver-nodeMCU-ESP8266) | 2 | — | Wifi-deauther em micro-controlador |
| 151 | [ocamposbio/ESP8266Sniff](https://github.com/ocamposbio/ESP8266Sniff) | 2 | C++ | Simple ESP8266 Wifi Sniffer project |
| 152 | [raupulus/esp8266-wifi-spam](https://github.com/raupulus/esp8266-wifi-spam) | 2 | C++ | Demo practicando pentesting y esp8266 creando puntos de acceso (AP) - Mirror de https://gitlab.co… |
| 153 | [Rockyrook96/Esp8266_Wifi_Jammer](https://github.com/Rockyrook96/Esp8266_Wifi_Jammer) | 2 | — | "An open-source ESP8266 Deauther project for testing Wi-Fi network security against deauthenticat… |
| 154 | [Rudii-25/BloodHound_VENOM](https://github.com/Rudii-25/BloodHound_VENOM) | 2 | HTML | BloodHound VENOM is an open-source hackable handheld IoT device for makers and developers. ESP826… |
| 155 | [sumit814/ESP8266-WiFi-Jammer](https://github.com/sumit814/ESP8266-WiFi-Jammer) | 2 | C++ | A web-based Wi-Fi deauthentication tool made using ESP8266. |
| 156 | [SwordsmanStronghold/deautherx-pro](https://github.com/SwordsmanStronghold/deautherx-pro) | 2 | Go | DeautherX Pro — продвинутая утилита для аудита безопасности Wi-Fi сетей (802.11). Инструмент позв… |
| 157 | [t84RT/ESP8266-WiFi-Deauther-Beacon-Spammer-with-Web-UI](https://github.com/t84RT/ESP8266-WiFi-Deauther-Beacon-Spammer-with-Web-UI) | 2 | C++ | Wi-Fi 安全研究与网络管理工具 基于 ESP8266 的 802.11 管理帧注入测试平台，支持 AP/STA 扫描、Deauthentication 攻击模拟、Beacon 广告机及现代化… |
| 158 | [tchaiwanda/wifi-security-lab](https://github.com/tchaiwanda/wifi-security-lab) | 2 | — | Hands-on wireless security lab using ESP8266 Deauther and isolated guest network for ethical hack… |
| 159 | [the-vnx/Wifi-Jammer-With-Node-MCU](https://github.com/the-vnx/Wifi-Jammer-With-Node-MCU) | 2 | — | A simple Wifi jammer with esp8266 or node mcu |
| 160 | [TheKanjiTV/Beacon](https://github.com/TheKanjiTV/Beacon) | 2 | Swift | 📊 Track user behavior in Swift apps easily with Beacon, offering offline persistence, device cont… |
| 161 | [Vola12do/IoT-WiFi-Attack-Tools-ESP8266-Deauther](https://github.com/Vola12do/IoT-WiFi-Attack-Tools-ESP8266-Deauther) | 2 | C++ | "A project leveraging ESP8266 for WiFi Deauth and Evil Twin attacks." |
| 162 | [xiixim101-pixel/sniffus](https://github.com/xiixim101-pixel/sniffus) | 2 | HTML | High-speed ESP8266 WiFi sniffer with real-time Web Serial API dashboard. Captures raw 802.11 fram… |
| 163 | [zest988/ESP8266-nRF24-Jammer](https://github.com/zest988/ESP8266-nRF24-Jammer) | 2 | C++ | 2.4 GHz signal jammer using ESP8266 D1 and nRF24L01+ with web interface |
| 164 | [1mirabbas/esp8266_deauther](https://github.com/1mirabbas/esp8266_deauther) | 1 | C | Description: ESP8266 Deauther is a firmware for testing 802.11 networks on your own 2.4GHz Wi‑Fi.… |
| 165 | [2272799702qq9/visualapproach1](https://github.com/2272799702qq9/visualapproach1) | 1 | — | Hack - ESP8266 as WiFi remote control for Bestway Lay-Z spa Helsinki |
| 166 | [aaemon/wifi-jammer-deauther](https://github.com/aaemon/wifi-jammer-deauther) | 1 | C | Wifi Jammer and Deauther using ESP8266 Wifi Module |
| 167 | [AbhiramKaduduri/ESP8266_Deauthor](https://github.com/AbhiramKaduduri/ESP8266_Deauthor) | 1 | — | Scan for WiFi devices, block selected connections, create dozens of networks and confuse WiFi sca… |
| 168 | [AbinMM/WIFI_esp8266_deauther](https://github.com/AbinMM/WIFI_esp8266_deauther) | 1 | C | ESP8255 WIFI工具器 |
| 169 | [Adarsha24/Esp8266_DEAUTHER](https://github.com/Adarsha24/Esp8266_DEAUTHER) | 1 | — | Attack:wifi-Dauther,Beacon,Probe.WARNING: LEARNING PURPOSE ONLY |
| 170 | [adithyanp2005gt-dotcom/wifi-deauthenticator](https://github.com/adithyanp2005gt-dotcom/wifi-deauthenticator) | 1 | C++ | ESP8266-based WiFi Deauthenticator for educational security research |
| 171 | [Adnan0336/Wifi-Hacking-with-ESP8266](https://github.com/Adnan0336/Wifi-Hacking-with-ESP8266) | 1 | — | Exploring WiFi Security Using ESP8266: Deauthentication & Evil Twin Attacks I'm excited to share … |
| 172 | [Anon505950/esp8266-evil-twin](https://github.com/Anon505950/esp8266-evil-twin) | 1 | C++ | Attempt to phish wifi passwords with a captive portal |
| 173 | [basht0p/WarPebble](https://github.com/basht0p/WarPebble) | 1 | Python | A system for wifi hacking / wardriving, designed for the ESP8266 HW-364A microcontroller, or othe… |
| 174 | [bernie-oss/wifi-jammer-esp8266](https://github.com/bernie-oss/wifi-jammer-esp8266) | 1 | — | Professional Internship Project at UTC2 - 2023 |
| 175 | [byfat1h/ESP8266-WiFi-Jammer](https://github.com/byfat1h/ESP8266-WiFi-Jammer) | 1 | — |  |
| 176 | [Chinmay2845/Wifi-Deauth-attack-detector-](https://github.com/Chinmay2845/Wifi-Deauth-attack-detector-) | 1 | C++ | Real-time Wi-Fi deauthentication attack detector using ESP8266 NodeMCU in promiscuous mode with S… |
| 177 | [cotyloidcavitybutterheadlettuce306/wifi-heatmap](https://github.com/cotyloidcavitybutterheadlettuce306/wifi-heatmap) | 1 | Python | Map WiFi signal strength and coverage gaps locally by plotting measurements onto your floor plans… |
| 178 | [cyberkalki/wifi_deauthentication](https://github.com/cyberkalki/wifi_deauthentication) | 1 | — | A WiFi deauther employing an ESP8266 disrupts wireless connections, rendering devices temporarily… |
| 179 | [cybersewer/WiFi-Deauther-With-ESP8266-NodeMCU-](https://github.com/cybersewer/WiFi-Deauther-With-ESP8266-NodeMCU-) | 1 | — | Guide to make a WiFi Deauther With ESP8266 (NodeMCU) |
| 180 | [cyberwolf6938/evil-twin-attack](https://github.com/cyberwolf6938/evil-twin-attack) | 1 | C++ | ESP8266 Evil Twin WiFi Attack Awareness Project (Educational Only) |
| 181 | [deadblackclover/DSTIKE-SPACEHUHN-HackerWatch](https://github.com/deadblackclover/DSTIKE-SPACEHUHN-HackerWatch) | 1 | C++ | Watch for real hackers |
| 182 | [Dhiraj60/esp8266_wifi_jammer](https://github.com/Dhiraj60/esp8266_wifi_jammer) | 1 | C++ |  |
| 183 | [ferm10n/docking-bay](https://github.com/ferm10n/docking-bay) | 1 | C++ | Control a IoT relay over WiFi with an esp8266, complete with status LEDs, OTA updates, and WiFi m… |
| 184 | [hachimamma/ESP8266-Wifi-Attacks](https://github.com/hachimamma/ESP8266-Wifi-Attacks) | 1 | C++ | Types of evil twin and deauth attacks from my side |
| 185 | [harshalbadgujar1053/wifi_deauthentication_attack_detector](https://github.com/harshalbadgujar1053/wifi_deauthentication_attack_detector) | 1 | C++ | ESP8266-based WiFi Deauthentication Attack Detector that monitors 802.11 management frames in pro… |
| 186 | [henriford/wifi_hunter](https://github.com/henriford/wifi_hunter) | 1 | C++ | WiFi Hunter |
| 187 | [ishindersingh/nodemcu_eviltwin](https://github.com/ishindersingh/nodemcu_eviltwin) | 1 | C++ | This project implements an "Evil Twin" WiFi access point using a NodeMCU (ESP8266) to create a ro… |
| 188 | [Kingisline/deauther-Wifi-jammer-esp8266-](https://github.com/Kingisline/deauther-Wifi-jammer-esp8266-) | 1 | — |  |
| 189 | [Martinxploit/NodeMCU-8266-WiFI-Evil-Jammer-Xploit](https://github.com/Martinxploit/NodeMCU-8266-WiFI-Evil-Jammer-Xploit) | 1 | — | Deauth attack to disconnect devices from WiFi Evil Twin AP to capture passwords No toggling - bot… |
| 190 | [mehraniqbalgp/esp8266_deauther](https://github.com/mehraniqbalgp/esp8266_deauther) | 1 | C | ESP8266 Wi-Fi Deauther v3.0 — WiFi security testing toolkit with deauth, beacon flood, probe atta… |
| 191 | [mohdsaqibqamar/ESP8266-WiFi-Hacking-Bad-Cat-](https://github.com/mohdsaqibqamar/ESP8266-WiFi-Hacking-Bad-Cat-) | 1 | C++ | Blue Cat is a very powerful wifi hacking tool  |
| 192 | [monescuteodor/Blocky-OS-v7.6](https://github.com/monescuteodor/Blocky-OS-v7.6) | 1 | C++ | WiFi security testing suite for ESP8266 and ST7735 display. Device based on ESP8266 for testing n… |
| 193 | [Muneer461/WiFi-Deauthentication-Detection-using-ESP8266](https://github.com/Muneer461/WiFi-Deauthentication-Detection-using-ESP8266) | 1 | C++ |  |
| 194 | [phfu/433RC_TX](https://github.com/phfu/433RC_TX) | 1 | C++ | ESP8266 transmits bits to 433MHz TX module   WEB interface & API for remote control |
| 195 | [Phunkafizer/RFM-gateway](https://github.com/Phunkafizer/RFM-gateway) | 1 | C++ | Hard- and software for the RFM-gateway, a universal platform for integrating sub-GHz radio into y… |
| 196 | [Physostegiadragee5952/valorant-esp-items-2026](https://github.com/Physostegiadragee5952/valorant-esp-items-2026) | 1 | — | See dropped weapons, spike, abilities, and enemy economy through walls with real-time Valorant it… |
| 197 | [piratos/Wifi-Jammer](https://github.com/piratos/Wifi-Jammer) | 1 | C | wifi jammer on esp8266 |
| 198 | [Prajwalpawar1/deauther](https://github.com/Prajwalpawar1/deauther) | 1 | Python | it is the deauther code  which use to program nodemcu  or esp8266 to perform  wifi  jaming attack   |
| 199 | [Pranav-V-20/WiFi_Deauther_ESP8266](https://github.com/Pranav-V-20/WiFi_Deauther_ESP8266) | 1 | C | A compact and powerful tool built using an ESP8266 microcontroller to perform WiFi deauthenticati… |
| 200 | [PratyushMishra-pro/ESP8266_deauther](https://github.com/PratyushMishra-pro/ESP8266_deauther) | 1 | — | ESP8266_deauther/FUNDING.yml |
| 201 | [pUrGe12/Wi-Fi-Bunny](https://github.com/pUrGe12/Wi-Fi-Bunny) | 1 | CMake | A Wifi-deauth + evil twin framework for ESP32 and ESP8266 |
| 202 | [R00TV3X/WiFi-Deauth-EvilTwin](https://github.com/R00TV3X/WiFi-Deauth-EvilTwin) | 1 | C++ | An educational project using NodeMCU (ESP8266) to simulate WiFi Deauthentication and Evil Twin at… |
| 203 | [RafeKhen/NetSuck-esp8266](https://github.com/RafeKhen/NetSuck-esp8266) | 1 | — | Advanced WiFi attack and audit firmware with deauth, beacon spam, evil twin, and packet sniffing. |
| 204 | [razannnnnn/ESP8266-Weather-Clock](https://github.com/razannnnnn/ESP8266-Weather-Clock) | 1 | C | Jam digital berbasis ESP8266 dengan display OLED 128x64, data cuaca real-time dari OpenWeatherMap… |
| 205 | [rickmatthewgerale3fb-cmd/Esp8266-signal-jammer-BLE-Bluetooth-and-Wifi](https://github.com/rickmatthewgerale3fb-cmd/Esp8266-signal-jammer-BLE-Bluetooth-and-Wifi) | 1 | C++ | A esp8266 optional screenless jammer with ONLY 2 supported nrf24's. Code mostly from gemini |
| 206 | [Rohan131293/tinyWiFiHacker](https://github.com/Rohan131293/tinyWiFiHacker) | 1 | — | ESP8266 based WiFi Attacks |
| 207 | [rohitcs1/ESP8266-WiFi-Security-Research](https://github.com/rohitcs1/ESP8266-WiFi-Security-Research) | 1 | C++ | This project uses the ESP8266 (NodeMCU) for WiFi security research and testing. It demonstrates c… |
| 208 | [roycuadra/WiFi-Jamming-Detector](https://github.com/roycuadra/WiFi-Jamming-Detector) | 1 | C++ | This project use a NodeMCU esp8266 It scans specific WiFi channels for deauth packets, When an at… |
| 209 | [schemil053/ESP8266ProbeCounter](https://github.com/schemil053/ESP8266ProbeCounter) | 1 | C++ | A simple wifi-probe sniffer for ESP8266 to count devices in a room. |
| 210 | [Shad0w-X/ESP8266_Deauther](https://github.com/Shad0w-X/ESP8266_Deauther) | 1 | — | Wifi Deauther for ESP8266 chips |
| 211 | [shasradha/epoch](https://github.com/shasradha/epoch) | 1 | — | Retro Gameboy-inspired handheld featuring 20+ games and a dual-firmware ESP8266 WiFi pentesting p… |
| 212 | [shehanweersing/ESP8266-WiFi-Deauther](https://github.com/shehanweersing/ESP8266-WiFi-Deauther) | 1 | — |  |
| 213 | [steve3301/wifi-evil-twin-lab](https://github.com/steve3301/wifi-evil-twin-lab) | 1 | — | Educational Wi-Fi Evil Twin & deauthentication lab with offensive simulation and defensive detect… |
| 214 | [Tanzeel0Hussain/ESP8266-PhiSiFi-Pro](https://github.com/Tanzeel0Hussain/ESP8266-PhiSiFi-Pro) | 1 | C++ | A professional WiFi security testing tool for ESP8266 featuring an automated Evil Twin phishing p… |
| 215 | [Technicalaccent/wifi-deauther-mini-esp8266-arduino-wifi](https://github.com/Technicalaccent/wifi-deauther-mini-esp8266-arduino-wifi) | 1 | — | Android app |
| 216 | [uchihaluckycs/IAITC](https://github.com/uchihaluckycs/IAITC) | 1 | C++ | Final Year Project - WiFi Disassociation and Deauthentication Attacks using NodeMCU ESP8266 |
| 217 | [winzter143/esp2866_wifi](https://github.com/winzter143/esp2866_wifi) | 1 | C++ | This app is custom version of  https://github.com/spacehuhn/esp8266_deauther |
| 218 | [zabszk/ESP8266-WiFi-Deauther](https://github.com/zabszk/ESP8266-WiFi-Deauther) | 1 | C++ | Project at AGH University of Science and Technology.  |
| 219 | [Zebratic/ESP8266-DeAuther](https://github.com/Zebratic/ESP8266-DeAuther) | 1 | C | Wifi Jammer/DeAuther using a NodeMCU ESP8266 board.  |
| 220 | [1F1XDRAGOB/Esp8266-deauther](https://github.com/1F1XDRAGOB/Esp8266-deauther) | 0 | — | ESP8266 Deauther is a WiFi deauthentication tool based on the ESP8266 microcontroller. It sends d… |
| 221 | [7yasin/esp-synapse](https://github.com/7yasin/esp-synapse) | 0 | — | A distributed cybersecurity platform using low-cost ESP32/ESP8266 devices as centrally managed ag… |
| 222 | [abdullahkhan4050/WIFI_HACKING](https://github.com/abdullahkhan4050/WIFI_HACKING) | 0 | — |  🔐 Exploring WiFi Security Using ESP8266: Deauthentication & Evil Twin Attacks I'm excited to sha… |
| 223 | [abhi04anon/Network-Security-Toolkit](https://github.com/abhi04anon/Network-Security-Toolkit) | 0 | C++ | ESP8266 Network Security Toolkit - Educational WiFi security testing tool featuring deauth attack… |
| 224 | [Adityachawan97/Esp8266-Wifi-Deauther](https://github.com/Adityachawan97/Esp8266-Wifi-Deauther) | 0 | — | Contains files about the Esp8266 based Wifi Deauther and Beacon Spammer. |
| 225 | [ahmeddurjoy14-spec/mt2-toolkit](https://github.com/ahmeddurjoy14-spec/mt2-toolkit) | 0 | Python | MT2 WiFi Pentest Toolkit - ESP8266 firmware with deauth fix |
| 226 | [ali-hadak/BHT-](https://github.com/ali-hadak/BHT-) | 0 | C++ | Türk yapımı ESP8266 tabanlı hacker terminali - 16x2 LCD ve WiFi özellikli |
| 227 | [ali-hadak/BTH-v1.0](https://github.com/ali-hadak/BTH-v1.0) | 0 | — | Türk yapımı ESP8266 tabanlı hacker terminali - 16x2 LCD ve WiFi özellikli |
| 228 | [arfuuu/Esp8266_2.5hz_wifi_deauther](https://github.com/arfuuu/Esp8266_2.5hz_wifi_deauther) | 0 | — |  |
| 229 | [BioNos1/WiFi-DeAuth-Detector](https://github.com/BioNos1/WiFi-DeAuth-Detector) | 0 | C++ | ESP8266 Wi-Fi Deauthentication Attack Detector |
| 230 | [bl4k7en/NetSpec](https://github.com/bl4k7en/NetSpec) | 0 | C++ | ESP8266-based WiFi security testing tool with twin AP attack and credential capture via captive p… |
| 231 | [charan10k/wifi-deauther-esp8266](https://github.com/charan10k/wifi-deauther-esp8266) | 0 | — | WiFi deauthentication is a process where a device is disconnected from a WiFi network. This can b… |
| 232 | [CHEN-233/esp8266](https://github.com/CHEN-233/esp8266) | 0 | — | wifi-attack。 |
| 233 | [chrisq-dev/phantom-kit](https://github.com/chrisq-dev/phantom-kit) | 0 | C++ | Suite de auditoría de seguridad y ingeniería social para ESP8266 con dashboard web, evil portal, … |
| 234 | [cod-xio/Growatt-Shine-X](https://github.com/cod-xio/Growatt-Shine-X) | 0 | C | ESP8266 replacement firmware for Growatt SHINE WiFi X dongle. Modbus RTU, MQTT, Home Assistant Au… |
| 235 | [CoreProtectSource/Esp8266-Jammer](https://github.com/CoreProtectSource/Esp8266-Jammer) | 0 | — | Простая глушилка wifi на esp8266. |
| 236 | [Cyber-Squad-CST/WiFi-Pentest-Kit-Flasher](https://github.com/Cyber-Squad-CST/WiFi-Pentest-Kit-Flasher) | 0 | — | ​An automated cross-platform tool to seamlessly flash custom firmware, Deauther scripts, and secu… |
| 237 | [Dhiraj60/esp8266-wifi-jammer](https://github.com/Dhiraj60/esp8266-wifi-jammer) | 0 | — |  |
| 238 | [Dhiraj60/esp8266_wifi_jammer.](https://github.com/Dhiraj60/esp8266_wifi_jammer.) | 0 | — |  |
| 239 | [Durzan12/Pocket-Hydra](https://github.com/Durzan12/Pocket-Hydra) | 0 | C++ | Esp8266 with a bunch of modules and a dream? here you go, IR, SubGHz, Deauther, a hydra of contro… |
| 240 | [el-pablos/TamsDeauth](https://github.com/el-pablos/TamsDeauth) | 0 | C | TamsDeauth - WiFi Deauther untuk ESP8266 dengan SSD1306 OLED, 10+ attack modes, web interface 65 … |
| 241 | [ElectrovillaYt/ESP8266-Wifi-Jammer](https://github.com/ElectrovillaYt/ESP8266-Wifi-Jammer) | 0 | — | For Educational Purpose only! |
| 242 | [FancybearIN/Wifi_jammer](https://github.com/FancybearIN/Wifi_jammer) | 0 | Shell | The Wi-Fi Jammer Tool is a comprehensive bash script designed to automate the management and depl… |
| 243 | [Frendi-X/ESP8266-P10-Digital-Clock-WiFiManager-NTP](https://github.com/Frendi-X/ESP8266-P10-Digital-Clock-WiFiManager-NTP) | 0 | C++ | Sistem ini dirancang sebagai jam digital berbasis ESP8266 dan Panel LED P10 yang mampu menampilka… |
| 244 | [GaniiGanesh/WIFI-Deauther-Pen-Tester](https://github.com/GaniiGanesh/WIFI-Deauther-Pen-Tester) | 0 | — | A simple WiFi Deauthentication tool using ESP8266 |
| 245 | [geetanjalikuwar/Wifi-attack-automation-using-ESP8266](https://github.com/geetanjalikuwar/Wifi-attack-automation-using-ESP8266) | 0 | C++ |  |
| 246 | [h3ides/wifi-deauther](https://github.com/h3ides/wifi-deauther) | 0 | C | esp8266 wifi-deauther |
| 247 | [hamzaasghar2429/Esp8266_Deauther](https://github.com/hamzaasghar2429/Esp8266_Deauther) | 0 | — | Affordable WiFi hacking platform for testing and learning. I recreate my own version it is inspir… |
| 248 | [haniefautophile-official/Arduino-ESP8266-WifiDeauther](https://github.com/haniefautophile-official/Arduino-ESP8266-WifiDeauther) | 0 | C++ |  |
| 249 | [HarshitUmrao/Wifi-Attack-System](https://github.com/HarshitUmrao/Wifi-Attack-System) | 0 | — | Built a practical cybersecurity project simulating real Wi-Fi attacks to study wireless vulnerabi… |
| 250 | [Hotboy2414/Esp8266](https://github.com/Hotboy2414/Esp8266) | 0 | — | WiFi jam |
| 251 | [htrooot/ESP8266-Evil-Twin-Deauthentication-Tool](https://github.com/htrooot/ESP8266-Evil-Twin-Deauthentication-Tool) | 0 | C++ | This is an educational cybersecurity tool designed to demonstrate common WiFi security vulnerabil… |
| 252 | [hygef-v4/wifi-tool-esp8266](https://github.com/hygef-v4/wifi-tool-esp8266) | 0 | C++ | wifi deauth + evil twin esp8266 (educational purpose only) |
| 253 | [IbrahimCR8/wifi-jammer-esp8266](https://github.com/IbrahimCR8/wifi-jammer-esp8266) | 0 | C |  |
| 254 | [JavierSiliacay/Wifi-Deauther-project](https://github.com/JavierSiliacay/Wifi-Deauther-project) | 0 | — | ESP8266-based educational tool for WiFi network exploration and security analysis. For educationa… |
| 255 | [jessnolimit-lgtm/Wifi-Deauther-](https://github.com/jessnolimit-lgtm/Wifi-Deauther-) | 0 | — | A Wi-Fi deauthentication tool built on ESP8266 that scans nearby networks and sends 802.11 deauth… |
| 256 | [jodhanfab/wifi-deauther-esp8266](https://github.com/jodhanfab/wifi-deauther-esp8266) | 0 | C | wifi deauther for esp8266 inspired from @SpacehuhnTech |
| 257 | [jpswensen/esp8266-eap-lowmem](https://github.com/jpswensen/esp8266-eap-lowmem) | 0 | C++ | A working example of Enterprise wifi on the ESP8266 with hacks to move constant TLS data from DRA… |
| 258 | [JSMAKERS015/ESP8266-WIFI-JAMMER](https://github.com/JSMAKERS015/ESP8266-WIFI-JAMMER) | 0 | Pascal |  |
| 259 | [jyotipanchal1922/esp8266-evil-twin](https://github.com/jyotipanchal1922/esp8266-evil-twin) | 0 | C++ | cybersecurity \| esp8266 \| arduino \| wifi-security \| network-security |
| 260 | [ksaswin/esp8266_wifi_deauth](https://github.com/ksaswin/esp8266_wifi_deauth) | 0 | C++ | Wifi Deauther using ESP8266 node mcu |
| 261 | [lamerous/TinySniff](https://github.com/lamerous/TinySniff) | 0 | — | Tool for WiFi and NFC pentest attacks powered by ESP8266. |
| 262 | [lelouch456/esp8266_deauther](https://github.com/lelouch456/esp8266_deauther) | 0 | C | The main feature, the deauthentication attack, is used to disconnect devices from their WiFi netw… |
| 263 | [LordEvron/ESP_wifi_fun](https://github.com/LordEvron/ESP_wifi_fun) | 0 | C | ESP8266 Deauther and SSID flooding.  |
| 264 | [M0D42/Botsec_Badge](https://github.com/M0D42/Botsec_Badge) | 0 | C++ | An esp8266 badge that you can make and help you hack the wifi |
| 265 | [MallocPointer/esp8266_deauther](https://github.com/MallocPointer/esp8266_deauther) | 0 | — | Affordable WiFi hacking platform for testing and learning |
| 266 | [mariusrazvan/impeditor-arduino](https://github.com/mariusrazvan/impeditor-arduino) | 0 | C++ | A firmware for the ESP8266 D1 mini that allows WiFi deauth attacks |
| 267 | [mcbackup058-netizen/deauther-pro](https://github.com/mcbackup058-netizen/deauther-pro) | 0 | Python | Professional WiFi Security Testing Tool for ESP8266 - WPA2 Handshake Capture, Deauth Attack, Stea… |
| 268 | [MevrickNeal/WraG](https://github.com/MevrickNeal/WraG) | 0 | C++ | Esp8266 based Telegram Comm device with wifi hacking capabilities  |
| 269 | [Mfahadb/ESP8266-D1-Mini-Wifi-Deauther](https://github.com/Mfahadb/ESP8266-D1-Mini-Wifi-Deauther) | 0 | C++ |  |
| 270 | [minkione/433Serial-SignalHacker](https://github.com/minkione/433Serial-SignalHacker) | 0 | — | 433MHZ, full duplex, esp8266 based, RFM69HW radio based transceiver. SDR |
| 271 | [MO00X/WiFiPhisher](https://github.com/MO00X/WiFiPhisher) | 0 | — | ESP8266‑WiFiPhisher — ESP8266‑based rogue access‑point for Wi‑Fi phishing using captive portal an… |
| 272 | [nakano1337/ESP8266-Wifi-Deauther](https://github.com/nakano1337/ESP8266-Wifi-Deauther) | 0 | — |  |
| 273 | [Nethravathi1706/WIFI-Deauther-Pen-Tester](https://github.com/Nethravathi1706/WIFI-Deauther-Pen-Tester) | 0 | — | A simple WiFi Deauthentication tool using ESP8266  |
| 274 | [NikolaTesla17/testWifiDictAttack](https://github.com/NikolaTesla17/testWifiDictAttack) | 0 | C | test of esp8266's capacity as a tool for dictionary based wifi attacks |
| 275 | [Nisar1000/wifi-jammer-with-node-mcu-esp8266-](https://github.com/Nisar1000/wifi-jammer-with-node-mcu-esp8266-) | 0 | — |  |
| 276 | [nvinh5064-ctrl/esp8266_deauther.](https://github.com/nvinh5064-ctrl/esp8266_deauther.) | 0 | — | Affordable WiFi hacking platform for testing and learning |
| 277 | [oscarSardaM/WiFI-Attacks-ESP8266](https://github.com/oscarSardaM/WiFI-Attacks-ESP8266) | 0 | C++ |  |
| 278 | [ParthShethia25/wifi-jammer-using-esp8266-](https://github.com/ParthShethia25/wifi-jammer-using-esp8266-) | 0 | C |  |
| 279 | [PawanKumarPandit/Esp8266_Wifi_Deauther](https://github.com/PawanKumarPandit/Esp8266_Wifi_Deauther) | 0 | C | Affordable WiFi hacking platform for testing and learning. |
| 280 | [PedadaSwathiLakshmi/WIFI-Attack-Automation-using-ESP8266](https://github.com/PedadaSwathiLakshmi/WIFI-Attack-Automation-using-ESP8266) | 0 | C++ |  |
| 281 | [Peterisdev/Skill-sync](https://github.com/Peterisdev/Skill-sync) | 0 | C++ | ESP8266-WiFi-Pentesting-Tool A comprehensive WiFi security testing toolkit for ESP8266 |
| 282 | [Phylakes01/wifi-deauther-esp8266-](https://github.com/Phylakes01/wifi-deauther-esp8266-) | 0 | C | ESP8266 OLED device with Wi-Fi AP, web interface, scan menu, show lists, attack simulation/status… |
| 283 | [Pranav-Darwai/wifi_deauther_esp8266](https://github.com/Pranav-Darwai/wifi_deauther_esp8266) | 0 | C++ | The WiFi Deauther ESP8266 is a simple tool designed to perform WiFi deauthentication attacks. It … |
| 284 | [Prateek13421/wifi-deauther-esp8266](https://github.com/Prateek13421/wifi-deauther-esp8266) | 0 | C | deauth any wifi in your network |
| 285 | [R00TV3X/WiFi-Security-Demonstrator](https://github.com/R00TV3X/WiFi-Security-Demonstrator) | 0 | — | A controlled lab simulation of Wi-Fi Deauthentication & Evil Twin attacks using NodeMCU (ESP8266)… |
| 286 | [rabeehpullichola/ESP8266-WiFi-Deauther](https://github.com/rabeehpullichola/ESP8266-WiFi-Deauther) | 0 | C++ |  |
| 287 | [rh45-one/SubGHz-Remote-ESP8266](https://github.com/rh45-one/SubGHz-Remote-ESP8266) | 0 | Python | Authenticated ESP8266 CC1101 Sub-GHz transceiver with Docker GUI and offline simulation |
| 288 | [riturajsingh0001/NodeMCU-WiFi-Security-Lab](https://github.com/riturajsingh0001/NodeMCU-WiFi-Security-Lab) | 0 | C++ | IoT Cybersecurity project demonstrating WiFi Evil Twin attack and deauthentication using NodeMCU … |
| 289 | [ryhnmhrdka/Wraith](https://github.com/ryhnmhrdka/Wraith) | 0 | C | WiFi security auditing tool for the ESP8266 platform. It provides a set of tools for scanning, mo… |
| 290 | [ryvoxo/RamJam-WIFI-Deauther](https://github.com/ryvoxo/RamJam-WIFI-Deauther) | 0 | — | A simple WIFI Deauther using the ESP8266, an OLED screen and 3 buttons. |
| 291 | [sahikkkk/PhiSiFi](https://github.com/sahikkkk/PhiSiFi) | 0 | — | WiFi Hacking with an ESP8266 - Deauth combined with Evil Twin attack  |
| 292 | [sangyapucharathkumar/WiFi-Phishing-Simulation-ESP8266-](https://github.com/sangyapucharathkumar/WiFi-Phishing-Simulation-ESP8266-) | 0 | C++ | WiFi Phishing Simulation is an educational project built using the ESP8266 WiFi module. The goal … |
| 293 | [Sanj274/WiFi-Deauther-using-ESP8266](https://github.com/Sanj274/WiFi-Deauther-using-ESP8266) | 0 | C | Implemented features to scan nearby networks, select targets, and execute deauth and beacon frame… |
| 294 | [Santosh-sudo-update/Wifi-deauther](https://github.com/Santosh-sudo-update/Wifi-deauther) | 0 | — | Custom ESP8266 Deauther firmware with a personalized web interface and default Wi-Fi settings.   … |
| 295 | [sayooj2005/-WiFi-Deauther---802.11-Security-Testing-Tool](https://github.com/sayooj2005/-WiFi-Deauther---802.11-Security-Testing-Tool) | 0 | — | 802.11 deauthentication attack tool built on ESP8266 for wireless security testing. |
| 296 | [seancarroll1999/Smart_Light_Control](https://github.com/seancarroll1999/Smart_Light_Control) | 0 | — | Project that builds a Flask API with ESP8266 to perform a man in the middle attack on RF remote c… |
| 297 | [sohamjuhin/Naughty_Man](https://github.com/sohamjuhin/Naughty_Man) | 0 | C | ESP8266 wifi deauther |
| 298 | [sriramnaidu2006/jammer-using-esp32](https://github.com/sriramnaidu2006/jammer-using-esp32) | 0 | — | A "jammer with ESP" generally refers to a DIY wireless interference or "deauther" project built o… |
| 299 | [swethas274/ESP8266-WiFi-DeAuther-](https://github.com/swethas274/ESP8266-WiFi-DeAuther-) | 0 | — | This project enhances ethical hacking, embedded systems, and network security skills. |
| 300 | [webermohit/wifi_jammer](https://github.com/webermohit/wifi_jammer) | 0 | — | Wi-Fi Jammer using Node MCU ESP8266 |
| 301 | [zneroravi/Wifi-jammer](https://github.com/zneroravi/Wifi-jammer) | 0 | — | wifi jammer with nodemcu esp8266 |

### BW16 / RTL8720

> 共 **39** 个项目，按 Stars 降序排列。

| # | 项目 | Stars | 语言 | 简介 |
|---:|---|---:|---|---|
| 1 | [EmenstaNougat/WiFiX-DualBand-Deauther](https://github.com/EmenstaNougat/WiFiX-DualBand-Deauther) | 378 | Batchfile | A 2.4GHz and 5GHZ Deauther, based on a RTL8720dn BW16 dev kit. |
| 2 | [EmenstaNougat/BlueJammer-V2](https://github.com/EmenstaNougat/BlueJammer-V2) | 322 | Batchfile | BlueJammer-V2 is a two-board RF research platform combining an ESP32 jamming engine with a BW16 5… |
| 3 | [FlyingIceyyds/BW16-Tools](https://github.com/FlyingIceyyds/BW16-Tools) | 319 | C++ | 基于Ai-Thinker BW16-Kit RTL8720DN 的无线安全测试工具。包含WIFI功能：解除身份认证(Deauth)，信道干扰(Channel Interference)，Deau… |
| 4 | [pingequalab/5ghost-wifi-lab](https://github.com/pingequalab/5ghost-wifi-lab) | 77 | C | Dual-band 2.4/5 GHz Wi-Fi research tool for the Flipper Zero, built on the Realtek RTL8720DN (BW1… |
| 5 | [xiv3r/Deauther-RTL8720DN](https://github.com/xiv3r/Deauther-RTL8720DN) | 58 | — | 2.4G/5Ghz WiFi deauther firmware for RTL8720DN BW16 MCU |
| 6 | [alexus2033/RTL8720-Sniffer](https://github.com/alexus2033/RTL8720-Sniffer) | 45 | C++ | Presence detection using RTL8720DN 2.4G/5G Dual Bands Wifi Module |
| 7 | [rustb0ne/RTL8720dn-5GHz-Wifi-Deauther](https://github.com/rustb0ne/RTL8720dn-5GHz-Wifi-Deauther) | 40 | C++ | 5GHz wifi deauther!!! |
| 8 | [HoneyHoneyTeam/ESP32-Marauder-Double-Barrel-5G](https://github.com/HoneyHoneyTeam/ESP32-Marauder-Double-Barrel-5G) | 35 | — | 1 * ESP32 chipset & 1 * BW16 chipset, GPS, Sub-GHz (433 MHz) and an onboard battery. It works wit… |
| 9 | [mehedishakeel/WiFi-Pentest-Kit](https://github.com/mehedishakeel/WiFi-Pentest-Kit) | 35 | — | WiFi Pentest Kit is a toolkit designed for wireless network security testing and auditing. It pro… |
| 10 | [pepeangell5/BWifiKill-BW16-5Ghz](https://github.com/pepeangell5/BWifiKill-BW16-5Ghz) | 35 | C++ | BWifiKill para BW16 RTL8720DN es un firmware educativo enfocado en análisis WiFi, pruebas de deau… |
| 11 | [vorchris/NullBeacon](https://github.com/vorchris/NullBeacon) | 33 | Python | A WiFi Deauther & Scanner for the BW16 (RTL8720DN) with a Python-based TUI. |
| 12 | [Emersonmafra/f](https://github.com/Emersonmafra/f) | 22 | — | #!/bin/bash  ########## DEBUG Mode ########## if [ -z ${FLUX_DEBUG+x} ]; then FLUX_DEBUG=0     el… |
| 13 | [mehedishakeel/WiFi-Deauther-BW16](https://github.com/mehedishakeel/WiFi-Deauther-BW16) | 21 | C++ | Dual Band WiFi Deauther For Both 2.4GHz & 5GHz WiFI Networks with BW16 RTL8720DN Module |
| 14 | [FL0WL0W/HumiditySnifferRTL8720](https://github.com/FL0WL0W/HumiditySnifferRTL8720) | 12 | C++ | A 2.4/5 Ghz WiFi Sniffer that also captures Temperature and Humidity from a HDC1080 using an RTL8720 |
| 15 | [nhatprx/Deauther-RTL8720DN-ESP32S3](https://github.com/nhatprx/Deauther-RTL8720DN-ESP32S3) | 11 | C++ | WiFi deauthentication tool for ESP32S3 and RTL8720DN supporting both 2.4GHz and 5GHz bands. Educa… |
| 16 | [AtherNet29/BW-16-RTL8720DN-DEAUTHER-EVILTWIN-NRF24](https://github.com/AtherNet29/BW-16-RTL8720DN-DEAUTHER-EVILTWIN-NRF24) | 9 | — | Advanced WiFi (2.4GHz & 5GHz) & Bluetooth Security Audit Tool Single-module design integrating du… |
| 17 | [iwheeliemycbr/5G_WiFi_Deauth_Attack_Flipper0](https://github.com/iwheeliemycbr/5G_WiFi_Deauth_Attack_Flipper0) | 7 | — | BW16 Flipper0 5g WiFi Deauth Attack files |
| 18 | [wirebits/DeauthEye](https://github.com/wirebits/DeauthEye) | 7 | C++ | A tool that detects deauthentication attacks on WiFi using BW16. |
| 19 | [Exora-Lab/BW16-NRF24-jammer](https://github.com/Exora-Lab/BW16-NRF24-jammer) | 4 | C++ | BW16+ NRF24 constant carrier generator with automatic channel hopping for BW16/RTL8720DN. Creates… |
| 20 | [ibtdev26/WifiRouge](https://github.com/ibtdev26/WifiRouge) | 4 | Python | A powerful Python-based RTL8720DN WiFi Deauther tool based on tesa-klebeband 5GHZ Deauther. Basic… |
| 21 | [MallocPointer/BW16-Tools](https://github.com/MallocPointer/BW16-Tools) | 4 | — | 基于Ai-Thinker BW16-Kit RTL8720DN 的无线安全测试工具。包含WIFI功能：解除身份认证(Deauth)，信道干扰(Channel Interference)，Deau… |
| 22 | [krrr/BW16-Stealth-Deauther](https://github.com/krrr/BW16-Stealth-Deauther) | 3 | C++ | BW16 WiFi Killer |
| 23 | [xiaohe4966/BW16-WiFi-Scan-WebUI](https://github.com/xiaohe4966/BW16-WiFi-Scan-WebUI) | 3 | C++ | BW16 (RTL8720DN) WiFi 扫描与Deauther工具 — Web UI版。手机连接AP热点即可操作，支持WiFi扫描、目标选择、多种攻击模式，无需OLED屏幕。 |
| 24 | [lumingmmlm/BW16-5GHZ-WiFi--Deauther](https://github.com/lumingmmlm/BW16-5GHZ-WiFi--Deauther) | 2 | C++ | 关于BW16的WiFi杀手 |
| 25 | [unnamedperson488/BlackHoleV1.0](https://github.com/unnamedperson488/BlackHoleV1.0) | 2 | C++ | A dual-band WiFi deauther built for power, stealth, and simplicity — powered by the RTL8720DN (BW… |
| 26 | [Kaushalsuvarna/bw16_deauther_v1.0.0_cli_only](https://github.com/Kaushalsuvarna/bw16_deauther_v1.0.0_cli_only) | 1 | C++ | Dual-band (2.4 + 5 GHz) WiFi deauther for the Realtek RTL8720DN (BW16), driven entirely via seria… |
| 27 | [Luck-One9/rasputian-deauther](https://github.com/Luck-One9/rasputian-deauther) | 1 | C++ | Modular Wi-Fi security research firmware with clean architecture and event-driven design. |
| 28 | [mohammadajani/Beacongotchi](https://github.com/mohammadajani/Beacongotchi) | 1 | Python | Wireless Security Awareness Platform - Custom ESP32-S3 / BW16 FirmwareBuilt a multi-board WiFi/BL… |
| 29 | [MR-ABID07/BW16_5G-WIFI_DEAUTHER](https://github.com/MR-ABID07/BW16_5G-WIFI_DEAUTHER) | 1 | C++ |  |
| 30 | [shark551151/Wifi-Deauthentication-Password-Capture-Evil-Twin-and-Other-Attacks-Ddos-Attack-Station-sniffing](https://github.com/shark551151/Wifi-Deauthentication-Password-Capture-Evil-Twin-and-Other-Attacks-Ddos-Attack-Station-sniffing) | 1 | Python | Buy Dual-Band (5 GHz and 2.4 GHz) RTL8720DN WiFi Deauther or Jammer device from - https://hacksho… |
| 31 | [SODAVK/BW16-CTS-SLEEP](https://github.com/SODAVK/BW16-CTS-SLEEP) | 1 | C++ | CTS and Sleep frame attack use BW16 (RTL8720DN) board |
| 32 | [SODAVK/BW16-SmartDeauther](https://github.com/SODAVK/BW16-SmartDeauther) | 1 | C++ | Deauth networks using BW16 (RTL8720DN). Deauth+Dissoc+CTS. Using Serial Terminal for communicate |
| 33 | [gabriel-re-pires/Deauther_BW16_5GHz_2.0](https://github.com/gabriel-re-pires/Deauther_BW16_5GHz_2.0) | 0 | C | Ataques em redes Wi-Fi de 5GHz e 2.4GHz, projetado para uso em ambientes controlados. |
| 34 | [GamerFuryAction/Deauth-testing-device](https://github.com/GamerFuryAction/Deauth-testing-device) | 0 | — | Cybersecurity testing device based on the BW16 development board, designed for testing the securi… |
| 35 | [IshanShrestha77/Wifi-Jammer-Bw16](https://github.com/IshanShrestha77/Wifi-Jammer-Bw16) | 0 | — | Wi-Fi Security Research Device using BW16 This project builds a Wi-Fi security research device fr… |
| 36 | [jvnwq6ctgw-max/https-github.com-n0tAv1ru5-RTL8720dn-5GHz-Wifi-Deauther](https://github.com/jvnwq6ctgw-max/https-github.com-n0tAv1ru5-RTL8720dn-5GHz-Wifi-Deauther) | 0 | — |  |
| 37 | [konaaakonaaa/bw16-deauth-detector](https://github.com/konaaakonaaa/bw16-deauth-detector) | 0 | C++ | Пассивный монитор WiFi (BW16/RTL8720DN), обнаруживающий deauth/disassoc-атаки |
| 38 | [leduy100414/Code-Hack-Wifi-RTL8720DN-BW16-Vietsub](https://github.com/leduy100414/Code-Hack-Wifi-RTL8720DN-BW16-Vietsub) | 0 | C++ | Code hack nên mình sẽ không chịu các hành vi, vi phạm mọi người, mọi người làm sẽ có trách nhiệm … |
| 39 | [study-room-lab/WiFi-Pentest-Kit](https://github.com/study-room-lab/WiFi-Pentest-Kit) | 0 | — | WiFi Pentest Kit is a toolkit designed for wireless network security testing and auditing. It pro… |

### 未明确/通用

> 共 **986** 个项目，按 Stars 降序排列。

| # | 项目 | Stars | 语言 | 简介 |
|---:|---|---:|---|---|
| 1 | [bettercap/bettercap](https://github.com/bettercap/bettercap) | 20,304 | Go | The Swiss Army knife for 802.11, BLE, HID, CAN-bus, IPv4 and IPv6 networks reconnaissance and MIT… |
| 2 | [wifiphisher/wifiphisher](https://github.com/wifiphisher/wifiphisher) | 14,978 | Python | The Rogue Access Point Framework |
| 3 | [brannondorsey/wifi-cracking](https://github.com/brannondorsey/wifi-cracking) | 12,742 | — | Crack WPA/WPA2 Wi-Fi Routers with Airodump-ng and Aircrack-ng/Hashcat |
| 4 | [DanMcInerney/wifijammer](https://github.com/DanMcInerney/wifijammer) | 4,323 | Python | Continuously jam all wifi clients/routers |
| 5 | [cirosantilli/china-dictatorship](https://github.com/cirosantilli/china-dictatorship) | 3,350 | HTML | 反中共政治宣传库。Anti Chinese government propaganda. 住在中国真名用户的网友请别给星星，不然你要被警察请喝茶。常见问答集，新闻集和饭店和音乐建议。卐习万岁卐。… |
| 6 | [P0cL4bs/WiFi-Pumpkin-deprecated](https://github.com/P0cL4bs/WiFi-Pumpkin-deprecated) | 3,150 | Python | DEPRECATED, wifipumpkin3 -> https://github.com/P0cL4bs/wifipumpkin3 |
| 7 | [7h30th3r0n3/Evil-M5Project](https://github.com/7h30th3r0n3/Evil-M5Project) | 2,887 | C++ | Evil-M5Project is an innovative tool developed for ethical  hacking and exploration of WiFi netwo… |
| 8 | [esc0rtd3w/wifi-hacker](https://github.com/esc0rtd3w/wifi-hacker) | 2,849 | Shell | Shell Script For Attacking Wireless Connections Using Built-In Kali Tools. Supports All Securitie… |
| 9 | [ankit0183/Wifi-Hacking](https://github.com/ankit0183/Wifi-Hacking) | 2,799 | Python | Cyber Security Tool For Hacking Wireless Connections Using Built-In Kali Tools. Supports All Secu… |
| 10 | [calebmadrigal/trackerjacker](https://github.com/calebmadrigal/trackerjacker) | 2,745 | Python | Like nmap for mapping wifi networks you're not connected to, plus device tracking |
| 11 | [k4m4/kickthemout](https://github.com/k4m4/kickthemout) | 2,687 | Python | 💤 Kick devices off your network by performing an ARP Spoof attack. |
| 12 | [P0cL4bs/wifipumpkin3](https://github.com/P0cL4bs/wifipumpkin3) | 2,530 | Python | Powerful framework for rogue access point attack. |
| 13 | [koutto/pi-pwnbox-rogueap](https://github.com/koutto/pi-pwnbox-rogueap) | 2,117 | Shell | Homemade Pwnbox :rocket: / Rogue AP :satellite: based on Raspberry Pi — WiFi Hacking Cheatsheets … |
| 14 | [gege-circle/.github](https://github.com/gege-circle/.github) | 2,106 | — | 这里是GitHub的草场，也是戈戈圈爱好者的交流地，主要讨论动漫、游戏、科技、人文、生活等所有话题，欢迎各位小伙伴们在此讨论趣事。This is GitHub grassland, and th… |
| 15 | [insightglacier/Dictionary-Of-Pentesting](https://github.com/insightglacier/Dictionary-Of-Pentesting) | 2,089 | Shell | Dictionary collection project such as Pentesing, Fuzzing, Bruteforce and BugBounty. 渗透测试、SRC漏洞挖掘、… |
| 16 | [xdavidhu/mitmAP](https://github.com/xdavidhu/mitmAP) | 1,692 | Python | 📡 A python program to create a fake AP and sniff data. |
| 17 | [xploitstech/Xteam](https://github.com/xploitstech/Xteam) | 1,365 | Python | Xteam All in one Instagram,Android,phishing osint and wifi hacking tool available  |
| 18 | [TermuxHackz/wifi-hacker](https://github.com/TermuxHackz/wifi-hacker) | 1,340 | Shell | Shell Script For Attacking Wireless Connections Using Built-In Kali Tools. Supports All Securitie… |
| 19 | [hubert3/iSniff-GPS](https://github.com/hubert3/iSniff-GPS) | 1,287 | Python | Passive sniffing tool for capturing and visualising WiFi location data disclosed by iOS devices |
| 20 | [xchwarze/wifi-pineapple-cloner](https://github.com/xchwarze/wifi-pineapple-cloner) | 1,276 | Shell | Port WiFi Pineapple NANO/TETRA in generic hardware |
| 21 | [blackhillsinfosec/WifiForge](https://github.com/blackhillsinfosec/WifiForge) | 1,237 | Python | WifiForge is a tool developed by Black Hills InfoSec to help train Pentesters on different Wi-Fi … |
| 22 | [daviddias/awesome-hacking-locations](https://github.com/daviddias/awesome-hacking-locations) | 1,140 | — | :computer: :coffee: List of Awesome Hacking Locations, organised by Country and City, listing if … |
| 23 | [hash3liZer/WiFiBroot](https://github.com/hash3liZer/WiFiBroot) | 1,135 | Python | A Wireless (WPA/WPA2) Pentest/Cracking tool. Captures & Crack 4-way handshake and PMKID key. Also… |
| 24 | [sensepost/mana](https://github.com/sensepost/mana) | 1,118 | HTML | *DEPRECATED* mana toolkit for wifi rogue AP attacks and MitM |
| 25 | [flashnuke/wifi-deauth](https://github.com/flashnuke/wifi-deauth) | 952 | Python | A deauth attack that disconnects all devices from the target wifi network (2.4Ghz & 5Ghz), WPA3 a… |
| 26 | [FLOCK4H/Freeway](https://github.com/FLOCK4H/Freeway) | 944 | Python | WiFi Penetration Testing & Auditing Tool |
| 27 | [3xploitGuy/lazyaircrack](https://github.com/3xploitGuy/lazyaircrack) | 929 | Shell | Automated tool for WiFi hacking. |
| 28 | [mkdirlove/WI-TOOLKIT](https://github.com/mkdirlove/WI-TOOLKIT) | 855 | Python | Hack WiFi in Termux ( ROOTED DEVICES ONLY) |
| 29 | [kumpulanremaja/wifi](https://github.com/kumpulanremaja/wifi) | 850 | Shell | Tutorial Cara Bobol Hack WIFI dengan termux Android jaringan yang dienkripsi WEP, WPA, dan WPS se… |
| 30 | [unixpickle/JamWiFi](https://github.com/unixpickle/JamWiFi) | 796 | Objective-C | A GUI, easy to use WiFi network jammer for Mac OS X |
| 31 | [Cyber-Dioxide/Wifi-Brute](https://github.com/Cyber-Dioxide/Wifi-Brute) | 780 | Python | A tool to crack a wifi password with a help of wordlist. This may take long to crack a wifi depen… |
| 32 | [aydinnyunus/WifiPassword-Stealer](https://github.com/aydinnyunus/WifiPassword-Stealer) | 778 | Python | Get All Registered Wifi Passwords from Target Computer. |
| 33 | [landy22granatt/Kumpulan-Script-Termux](https://github.com/landy22granatt/Kumpulan-Script-Termux) | 776 | Python | Ok, Langsung Saja Ke Materi. Sesuai Judul, Disini Saya Akan Memberikan Kumpulan Script Termux Yan… |
| 34 | [ricardojoserf/wifi-pentesting-guide](https://github.com/ricardojoserf/wifi-pentesting-guide) | 760 | Python | WiFi Penetration Testing Guide |
| 35 | [HKSSY/Drone-Hacking-Tool](https://github.com/HKSSY/Drone-Hacking-Tool) | 703 | Python | Drone Hacking Tool is a GUI tool that works with a USB Wifi adapter and HackRF One for hacking dr… |
| 36 | [drau6/KawaiiDeauther](https://github.com/drau6/KawaiiDeauther) | 670 | Shell | Jam all wifi clients/routers. |
| 37 | [aress31/wirespy](https://github.com/aress31/wirespy) | 660 | Shell | Framework designed to automate various wireless networks attacks (the project was presented on Pe… |
| 38 | [sensepost/hostapd-mana](https://github.com/sensepost/hostapd-mana) | 641 | C | SensePost's modified hostapd for wifi attacks. |
| 39 | [AleksaMCode/WiFi-password-stealer](https://github.com/AleksaMCode/WiFi-password-stealer) | 610 | PowerShell | Simple Windows and Linux keystroke injection tool that exfiltrates stored WiFi data (SSID and pas… |
| 40 | [Taoviqinvicible/Tools-termux](https://github.com/Taoviqinvicible/Tools-termux) | 606 | — | 1.[Script Termux] -Cmatrix *apt-get update *apt-get upgrade *apt-get install nmap *apt-get instal… |
| 41 | [WiPi-Hunter/PiDense](https://github.com/WiPi-Hunter/PiDense) | 569 | Python | 🍓📡🍍Monitor illegal wireless network activities. (Fake Access Points), (WiFi Threats: KARMA Attack… |
| 42 | [akashblackhat/wifi-hacking.py](https://github.com/akashblackhat/wifi-hacking.py) | 555 | Python | Cyber Security Tool For Hacking Wireless Connections Using Built-In Kali Tools. Supports All Secu… |
| 43 | [adamff-dev/WiFi-Spam](https://github.com/adamff-dev/WiFi-Spam) | 537 | Shell | :email::satellite: Spam thousands of WiFi access points with custom SSIDs |
| 44 | [sevagas/swap_digger](https://github.com/sevagas/swap_digger) | 535 | Shell |  swap_digger is a tool used to automate Linux swap analysis during post-exploitation or forensics… |
| 45 | [clu3bot/owt](https://github.com/clu3bot/owt) | 505 | Shell | Update Version 3.1 added free SMS messaging. |
| 46 | [priyankgada/The-Complete-Practical-Certified-Ethical-Hacking-Course-in-English](https://github.com/priyankgada/The-Complete-Practical-Certified-Ethical-Hacking-Course-in-English) | 490 | — | Welcome this comprehensive course on Ethical Hacking! This course assumes you have NO prior knowl… |
| 47 | [theahmadov/NIVOS](https://github.com/theahmadov/NIVOS) | 483 | Python | NIVOS is a hacking tool that allows you to scan deeply , crack wifi, see people on your network. … |
| 48 | [uday-khan/Termux](https://github.com/uday-khan/Termux) | 463 | — | KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau hp lu gw… |
| 49 | [whatotter/pwnhyve](https://github.com/whatotter/pwnhyve) | 460 | Python | A low cost, jack-of-all-trades hacking tool, taking inspiration from FlipperZero and P4wnP1, usin… |
| 50 | [0x0XDev/JamWiFi](https://github.com/0x0XDev/JamWiFi) | 442 | Swift | A GUI, easy to use WiFi network jammer for Mac OS X |
| 51 | [r4ulcl/WiFiChallengeLab-docker](https://github.com/r4ulcl/WiFiChallengeLab-docker) | 442 | Shell | Virtualized Wi-Fi pentesting laboratory without the need for physical Wi-Fi cards, using mac80211… |
| 52 | [TheBATeam/Batch-WI-FI-Brute-Forcer](https://github.com/TheBATeam/Batch-WI-FI-Brute-Forcer) | 394 | Batchfile | This project is based upon the trick that, how to hack WI-FI with CMD. The main purpose behind, c… |
| 53 | [cirosantilli/china-dictatroship-7](https://github.com/cirosantilli/china-dictatroship-7) | 391 | HTML | 反中共政治宣传库。Anti Chinese government propaganda. https://github.com/cirosantilli/china-dictatorship 的… |
| 54 | [DH-AL/Dh-All](https://github.com/DH-AL/Dh-All) | 389 | Python | This is a package of all hacking tools., This tool contain over 300+ Advance and professional Hac… |
| 55 | [W0rthlessS0ul/FZ_nRF24_jammer](https://github.com/W0rthlessS0ul/FZ_nRF24_jammer) | 388 | C | The Flipper Zero nRF24 jammer is a powerful tool that requires an Flipper Zero and nRF24 module t… |
| 56 | [grugnoymeme/flipperzero-CLI-wifi-cracker](https://github.com/grugnoymeme/flipperzero-CLI-wifi-cracker) | 379 | Python | CLI - Analyze WPA/WPA2 handshakes from FlipperZero's captured .pcaps to find out the WiFi Passwords. |
| 57 | [zszszszsz/.config](https://github.com/zszszszsz/.config) | 372 | Shell | # # Automatically generated file; DO NOT EDIT. # OpenWrt Configuration # CONFIG_MODULES=y CONFIG_… |
| 58 | [Esser50K/EvilTwinFramework](https://github.com/Esser50K/EvilTwinFramework) | 365 | Python | A framework for pentesters that facilitates evil twin attacks as well as exploiting other wifi vu… |
| 59 | [V0lk3n/WirelessPentesting-CheatSheet](https://github.com/V0lk3n/WirelessPentesting-CheatSheet) | 359 | — | This repository contain a CheatSheet for OSWP & WiFi Cracking. |
| 60 | [U7P4L-IN/WIFI-HACKING](https://github.com/U7P4L-IN/WIFI-HACKING) | 351 | Python | ⚡Cyber Security Tool For Hacking Wireless Connections Using Built-In Kali Tools. Supports All Sec… |
| 61 | [rfquack/RFQuack](https://github.com/rfquack/RFQuack) | 350 | C++ | RFQuack: the versatile RF-analysis tool that quacks! |
| 62 | [xdavidhu/probeSniffer](https://github.com/xdavidhu/probeSniffer) | 342 | Python | 🔍 A tool for sniffing unencrypted wireless probe requests from devices. |
| 63 | [warengonzaga/wifi-passview](https://github.com/warengonzaga/wifi-passview) | 341 | Batchfile | An open source batch script based WiFi Passview for Windows! |
| 64 | [tnt-wolve/ch3r0](https://github.com/tnt-wolve/ch3r0) | 333 | — | Hackingtool Menu 🧰 AnonSurf Information Gathering Password Attack Wireless Attack SQL Injection T… |
| 65 | [NORMA-Inc/AtEar](https://github.com/NORMA-Inc/AtEar) | 330 | JavaScript | Wireless Hacking, WiFi Security, Vulnerability Analyzer, Pentestration |
| 66 | [MrSanZz/pandora](https://github.com/MrSanZz/pandora) | 322 | Python | -= Has features =-  =============== -DDoS -Web Scanning -Phone Hunter -CCTV Hunter -Deface -Mass … |
| 67 | [adde88/openwrt-useful-tools](https://github.com/adde88/openwrt-useful-tools) | 308 | Standard ML | A repo containing different tools compiled specifically for the Hak5 WiFi Pineapple MK6 and MK7. |
| 68 | [o7-machinehum/flipper-blackhat](https://github.com/o7-machinehum/flipper-blackhat) | 305 | Python | Linux based WiFi pentesting device for the Flipper Zero. |
| 69 | [thehackingsage/fluxion](https://github.com/thehackingsage/fluxion) | 292 | HTML | WiFi Cracking Tool (Using Evil Twin Attack) With Some Modification. (Only For Legal Purposes) |
| 70 | [psyb0t/piraterf](https://github.com/psyb0t/piraterf) | 291 | Go | PIrateRF transforms your Raspberry Pi Zero W into a portable RF signal generator that spawns its … |
| 71 | [adamff-dev/PwrDeauther](https://github.com/adamff-dev/PwrDeauther) | 285 | Shell | :zap: Deauth a specific WiFi access point or an entire channel |
| 72 | [SkypLabs/probequest](https://github.com/SkypLabs/probequest) | 280 | Python | Toolkit for Playing with Wi-Fi Probe Requests |
| 73 | [veerendra2/wifi-deauth-attack](https://github.com/veerendra2/wifi-deauth-attack) | 280 | Python | An automated script for deauthentication attack  |
| 74 | [Ymsniper/KTO](https://github.com/Ymsniper/KTO) | 273 | Rust | Rust WiFi deauth tool that kicks every device off a target network except the MACs you whitelist,… |
| 75 | [AnonymousAt3/piracy](https://github.com/AnonymousAt3/piracy) | 272 | Shell | Automated WIFI Hacking Tool |
| 76 | [brannondorsey/sniff-probes](https://github.com/brannondorsey/sniff-probes) | 254 | Shell | Plug-and-play bash script for sniffing 802.11 probes requests :nose:  |
| 77 | [DeaDHackS/WiFiSpy](https://github.com/DeaDHackS/WiFiSpy) | 247 | Python | The best WiFi spy avalaible for hire! Made for hackers, for hackers |
| 78 | [WiPi-Hunter/PiSavar](https://github.com/WiPi-Hunter/PiSavar) | 241 | Python | 📡 🍍Detects activities of PineAP module and starts deauthentication attack (for fake access points… |
| 79 | [itsdarklikehell-interactive/pwnagotchi-plugins](https://github.com/itsdarklikehell-interactive/pwnagotchi-plugins) | 234 | Python | Collectie van Pwnagotchi-plugins voor Wi-Fi auditing en pentesting op Raspberry Pi. |
| 80 | [ente0/hashCrack](https://github.com/ente0/hashCrack) | 226 | Python | Interactive Python CLI that wraps Hashcat with guided menus for wordlist, rule-based, brute-force… |
| 81 | [hash3liZer/wifijammer](https://github.com/hash3liZer/wifijammer) | 226 | Python | Wireless Jammer to Disconnect Nearby Access-Points and Stations.  |
| 82 | [SHUR1K-N/WiFi-Mangoapple-Resources](https://github.com/SHUR1K-N/WiFi-Mangoapple-Resources) | 219 | — | Helpful resources regarding the cheap DIY Wi-Fi Pineapple, AKA Wi-Fi Mangoapple to help with supp… |
| 83 | [mRFWq7LwNPZjaVv5v6eo/cihna-dictattorshrip-8](https://github.com/mRFWq7LwNPZjaVv5v6eo/cihna-dictattorshrip-8) | 217 | HTML | 反中共政治宣传库。Anti Chinese government propaganda. https://github.com/cirosantilli/china-dictatorship 的… |
| 84 | [panbinibn/OpenPacketFix_](https://github.com/panbinibn/OpenPacketFix_) | 215 | — | 大陆修宪香港恶法台湾武统朝鲜毁约美中冷战等都是王沪宁愚弄习思想极左命运共同体的大策划中共窃国这半个多世纪所犯下的滔天罪恶，前期是毛泽东策划的，中期6.4前后是邓小平策划的，黄牛数据分析后期是毛的… |
| 85 | [hak5peaks/Hackers-Nightlight](https://github.com/hak5peaks/Hackers-Nightlight) | 211 | C | Turning smart lights into Wifi Hacking implants.  |
| 86 | [PentHertz/grimoire](https://github.com/PentHertz/grimoire) | 206 | Python | Offensive knowledge, offline. One search box for every playbook. |
| 87 | [flancast90/wifi-bf](https://github.com/flancast90/wifi-bf) | 205 | Python | A (completely native) python3 wifi brute-force attack using the 100k most common passwords (2021) |
| 88 | [grugnoymeme/flipperzero-GUI-wifi-cracker](https://github.com/grugnoymeme/flipperzero-GUI-wifi-cracker) | 202 | Python | GUI - Analyze WPA/WPA2 handshakes from FlipperZero's captured .pcaps to find out the WiFi Passwords. |
| 89 | [digiampietro/hacking-gemtek](https://github.com/digiampietro/hacking-gemtek) | 201 | Shell | hacking-gemtek is a reverse engineering project for a Gemtek home router (WVRTM-127ACN), distribu… |
| 90 | [Rizalcahdemak/akun-termux](https://github.com/Rizalcahdemak/akun-termux) | 198 | — | Skip to content arysandi/kumpulan kode di termux Created 3 years ago • Report abuse Code Revision… |
| 91 | [Gurpreet06/Wifi-Crack](https://github.com/Gurpreet06/Wifi-Crack) | 193 | Python | Python Tool to automate WIFI attacks to obtain handshake, PMKID attack, make networks temporarily… |
| 92 | [wifiphisher/roguehostapd](https://github.com/wifiphisher/roguehostapd) | 191 | C | Hostapd fork including Wi-Fi attacks and providing Python bindings with ctypes. |
| 93 | [B3ND1X/air-script](https://github.com/B3ND1X/air-script) | 186 | Shell | Air Script is a powerful Wi-Fi auditing tool with optional email alerts for captured handshakes. |
| 94 | [ElectronicCats/BomberCat](https://github.com/ElectronicCats/BomberCat) | 186 | HTML | BomberCat is the latest security tool that combines the most common card technologies: NFC techno… |
| 95 | [pineapple-pager-projects/pineapple_pager_loki](https://github.com/pineapple-pager-projects/pineapple_pager_loki) | 184 | Lua | LAN Orchestrated Key Infiltrator - Autonomous network recon payload for the Hak5 WiFi Pineapple P… |
| 96 | [hacker3983/pyrit-installer](https://github.com/hacker3983/pyrit-installer) | 181 | Python | This shows how to install pyrit for fluxion or other wifi hacking tools if you don't have pip ins… |
| 97 | [ANDRVV/gapcast](https://github.com/ANDRVV/gapcast) | 180 | Go | 📡 802.11 broadcast analyzer & injector |
| 98 | [wlmosv-png/wpaforge](https://github.com/wlmosv-png/wpaforge) | 180 | Java | 智能字典破解 WiFi：按 SSID 与线索现场生成候选、逐条真实关联验证；含 WPS PIN、局域网侦察、.cap/.hc22000 离线校验、信道诊断；收尾自动写回目标原网络配置并回读确认。… |
| 99 | [devilvimalkumar/wibr_pro](https://github.com/devilvimalkumar/wibr_pro) | 171 | — | Wibr+ pro version for WiFi bruteforce hacking apk With dictionary attack tools. Easily hack any W… |
| 100 | [W00t3k/Awesome-WiFi-Hacking](https://github.com/W00t3k/Awesome-WiFi-Hacking) | 170 | — | Wifi Hacking |
| 101 | [ZKAW/wifi-deauther](https://github.com/ZKAW/wifi-deauther) | 170 | Python | 802.11 deauthentication tool for Wi-Fi security testing and research |
| 102 | [Whomrx666/Wifi-crackerX](https://github.com/Whomrx666/Wifi-crackerX) | 167 | Python | Wifi-crackerX is a tool for hacking a WPS/WPA/WPA2 Networks |
| 103 | [latonita/tenda-reverse](https://github.com/latonita/tenda-reverse) | 159 | Shell | Reverse engineering, getting root access to Tenda MW6 wifi mesh router |
| 104 | [TermuxHackz/wifi-cracker](https://github.com/TermuxHackz/wifi-cracker) | 157 | Python | Wifi-Cracker.py to Hack WPS/WPA/WPA2 Networks |
| 105 | [Don-No7/Hack-SQL](https://github.com/Don-No7/Hack-SQL) | 153 | — | -- -- File generated with SQLiteStudio v3.2.1 on Sun Feb 7 14:58:28 2021 -- -- Text encoding used… |
| 106 | [andrewhilts/snifflab](https://github.com/andrewhilts/snifflab) | 152 | Python | Scripts to create your own MITM'ing, packet sniffing WiFi access point |
| 107 | [FLOCK4H/AtomDucky](https://github.com/FLOCK4H/AtomDucky) | 150 | Python | WiFi Rubber Ducky with a web interface using CircuitPython |
| 108 | [MGz-Staze/tools-Termux](https://github.com/MGz-Staze/tools-Termux) | 150 | — | Cara Update dan Upgrade Termux  pkg update && pkg upgrade  Tools Pendukung untuk Termux  Tools pe… |
| 109 | [Matrix07ksa/EvilNet](https://github.com/Matrix07ksa/EvilNet) | 149 | Python | Network Attack  wifi attack vlan attack arp attack Mac Attack Attack revealed etc../ |
| 110 | [xchwarze/AR150-WiFiPineapple](https://github.com/xchwarze/AR150-WiFiPineapple) | 143 | — | Converting your AR150 to a Wifi Pineapple NANO |
| 111 | [jspw/Crack-WIFI-WPA2](https://github.com/jspw/Crack-WIFI-WPA2) | 141 | C | Get handshake and crack wpa/wpa2 security wifi passwords |
| 112 | [Danyalkhattak/wifi-attack-tool](https://github.com/Danyalkhattak/wifi-attack-tool) | 138 | Python | Wi-Fi Attack Automation Tool for Kali Linux and Termux automates Wi-Fi attacks like Deauthenticat… |
| 113 | [phenotypic/WiFiCrack](https://github.com/phenotypic/WiFiCrack) | 138 | Shell | Automated Wi-Fi cracker for macOS |
| 114 | [zpc1314521/PCL2](https://github.com/zpc1314521/PCL2) | 135 | — | [stays mad] 反PCL宣传库。Anti PCL propaganda. 大陆修宪香港恶法台湾武统朝鲜毁约美中冷战等都是王沪宁愚弄习思想极左命运共同体的大策划中共窃国这半个多世纪所犯下的… |
| 115 | [pineapple-pager-projects/pineapple_pager_pagergotchi](https://github.com/pineapple-pager-projects/pineapple_pager_pagergotchi) | 132 | Python | Pwnagotchi ported to the hak5 wifi pineapple pager with some added features, uses pineAP |
| 116 | [Kidd3n/WifiPwnedd](https://github.com/Kidd3n/WifiPwnedd) | 131 | PHP | Tool for Wifi Network Attacks  |
| 117 | [ivan-sincek/evil-twin](https://github.com/ivan-sincek/evil-twin) | 129 | PHP | Learn how to set up a fake authentication web page on a fake WiFi network. |
| 118 | [altaga/Portable-Hacking-Station-RPI](https://github.com/altaga/Portable-Hacking-Station-RPI) | 123 | — | Station to perform WiFi network audits, using Raspberry Pi Zero W or Raspberry Pi 3, with connect… |
| 119 | [ezhil56x/Wifi-Deauthentication-Tool](https://github.com/ezhil56x/Wifi-Deauthentication-Tool) | 117 | Shell | Wi-Fi Deauthentication Tool is a command-line utility for educational purposes, enabling users to… |
| 120 | [Geovation/wifispy](https://github.com/Geovation/wifispy) | 115 | Python | Sniff Wifi traffic, log device addresses. |
| 121 | [bkerler/DroneID](https://github.com/bkerler/DroneID) | 113 | Python | OpenDrone ID sniffer/spoofer for Bluetooth + WIFI |
| 122 | [HighTeckMan/wifijammer](https://github.com/HighTeckMan/wifijammer) | 110 | Python | Raspberry Pi Wifi Jammer Project |
| 123 | [hiteshchoudhary/Airvengers](https://github.com/hiteshchoudhary/Airvengers) | 110 | Python | A GUI to pentest wifi Network, based on Aircrack-ng tools |
| 124 | [aegis1980/WifiHotSpot](https://github.com/aegis1980/WifiHotSpot) | 108 | Java | A bit of a hack I wrote to fix Trigger's issue with not controlling wifi hotspot in Oreo. Turned … |
| 125 | [zall-4RT/kumpulan-code-termuxs-lenkap](https://github.com/zall-4RT/kumpulan-code-termuxs-lenkap) | 108 | — | termux KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau h… |
| 126 | [Manisso/wifisky](https://github.com/Manisso/wifisky) | 107 | Python | wifisky Python script for pentesting wireless networks |
| 127 | [KatzeMau/wifite2-requirements](https://github.com/KatzeMau/wifite2-requirements) | 105 | Shell | This bash script will install wifite2 and its other tools Pyrit, bully, wireshark, hcxtools, hcxd… |
| 128 | [SValkanov/wifivoid](https://github.com/SValkanov/wifivoid) | 105 | Ruby | Ruby script for continuously jam all wifi clients and access points within range |
| 129 | [NickJongens/PiEvilTwin](https://github.com/NickJongens/PiEvilTwin) | 103 | HTML | Raspberry Pi WiFi Evil Twin Captive Portal  |
| 130 | [bad-antics/nullsec-pineapple-suite](https://github.com/bad-antics/nullsec-pineapple-suite) | 102 | Shell | 96+ WiFi Pineapple Pager payloads across 13 categories \| Attack, Recon, Capture, Stealth, Interc… |
| 131 | [oblique/wificurse](https://github.com/oblique/wificurse) | 102 | C | WiFi Jamming tool |
| 132 | [iamhellaweiri/EXPLOIT-FRAMEWORK-v1.0](https://github.com/iamhellaweiri/EXPLOIT-FRAMEWORK-v1.0) | 100 | Python | EXPLOIT-FRAMEWORK is a very powerfull hacking tool and have dangerous hacks like  Payload Creator… |
| 133 | [tzun4mi/android-hack-pack](https://github.com/tzun4mi/android-hack-pack) | 98 | — | FaceNiff latest  Droidsheep APK zAnti APK DroidJack dSploit APK SpyMax v2  Spynote v6.4. dendroid… |
| 134 | [Cyb0r9/network-attacker](https://github.com/Cyb0r9/network-attacker) | 95 | Shell | Programmed For Penetration Testing Beginners . This Program Based on Mdk3 . "WiFi Stress Testing … |
| 135 | [k0r0pt/Project-Tauro](https://github.com/k0r0pt/Project-Tauro) | 95 | Java | A Router WiFi key recovery/cracking tool with a twist. |
| 136 | [majdsassi/Pico-WIFI-Duck](https://github.com/majdsassi/Pico-WIFI-Duck) | 95 | Python | Pico WiFi Duck is a project that enables the emulation of a USB Rubber Ducky over Wi-Fi using the… |
| 137 | [rofl0r/oneshot](https://github.com/rofl0r/oneshot) | 95 | Python | try a single WPS pin/pixiedust attack with wpa_supplicant |
| 138 | [xchwarze/wifi-pineapple-cloner-builds](https://github.com/xchwarze/wifi-pineapple-cloner-builds) | 94 | — | Build repo from Universal Wifi pineapple hardware cloner |
| 139 | [DarkSyntax7/Wifi-Jammer](https://github.com/DarkSyntax7/Wifi-Jammer) | 93 | Shell | Tool to Jam Full WiFi Network Near-You! |
| 140 | [TW-D/WiFi-Pineapple-MK7_REST-Client](https://github.com/TW-D/WiFi-Pineapple-MK7_REST-Client) | 92 | Ruby | WiFi Hacking Workflow with WiFi Pineapple Mark VII API |
| 141 | [hugorezende/nRF24L01-WiFi-Jammer](https://github.com/hugorezende/nRF24L01-WiFi-Jammer) | 91 | C++ | Code to create some noise with nRF24L01 and interfere on the 2.4GHz spectrum |
| 142 | [sh1n3sec/WiCrackFi](https://github.com/sh1n3sec/WiCrackFi) | 90 | Python | Python Script to help/automate the WiFi hacking exercises. |
| 143 | [whxitte/white-netkit](https://github.com/whxitte/white-netkit) | 89 | Python | This is  a multipurpose tool which is useful in networking or network hacking. |
| 144 | [TechnicalUserX/batch_wifi_brute_forcer](https://github.com/TechnicalUserX/batch_wifi_brute_forcer) | 88 | Batchfile | An active attack tool against Wi-Fi networks with internal CMD commands |
| 145 | [ericpd/mr.wifibrute](https://github.com/ericpd/mr.wifibrute) | 87 | C | Get handshake and crack wpa/wpa2 security wifi passwords  |
| 146 | [trmxvibs/wifi-audit-tool](https://github.com/trmxvibs/wifi-audit-tool) | 87 | Python | A user-friendly command-line toolkit for WiFi network scanning, handshake capture, and vulnerabil… |
| 147 | [aleen42/hack-wifi](https://github.com/aleen42/hack-wifi) | 85 | Shell | :gun: a wifi hacker tool |
| 148 | [Kalihackz/Wifi_Tool](https://github.com/Kalihackz/Wifi_Tool) | 85 | Python | This is a python3 tool for scanning nearby Wifi and connecting to it either by normal manual pass… |
| 149 | [adityashrm21/RaspberryPi-Packet-Sniffer](https://github.com/adityashrm21/RaspberryPi-Packet-Sniffer) | 84 | Shell | An HTTP and HTTPS sniffing tool created using a Raspberry Pi |
| 150 | [mgp25/Probe-Hunter](https://github.com/mgp25/Probe-Hunter) | 83 | Python | Probe Request sniffer + Wigle |
| 151 | [flankerhqd/wifimonster](https://github.com/flankerhqd/wifimonster) | 82 | Python | Wifi sniffing and hijacking tool |
| 152 | [NSM-Barii/NetCracker](https://github.com/NSM-Barii/NetCracker) | 82 | Python | WiFi Hacking Suite |
| 153 | [bad-antics/nullsec](https://github.com/bad-antics/nullsec) | 79 | Shell | 💀 NullSec — Offensive Security Framework \| 200+ tools, AI lab, mesh net, WiFi Pineapple, Flipper… |
| 154 | [LinkClink/Rainbow-Wifi-Hack-Utility-Android](https://github.com/LinkClink/Rainbow-Wifi-Hack-Utility-Android) | 79 | Java |  The program implements brute Wi-Fi network method on platform Android |
| 155 | [momenbasel/AutoWIFI](https://github.com/momenbasel/AutoWIFI) | 79 | Python | Wireless penetration testing framework. Automates WPA/WPA2/WEP/WPS attacks - recon to exploitatio… |
| 156 | [ShlomiRex/wifi-deauth-rpi-wardrive](https://github.com/ShlomiRex/wifi-deauth-rpi-wardrive) | 79 | Python | Wifi deauthenticate all networks with raspberry pi zero w in your backpack. Useful for public places |
| 157 | [david-palma/wifi-cracking](https://github.com/david-palma/wifi-cracking) | 76 | — | A guide to using the Aircrack-ng suite for cracking 802.11 WEP and WPA/WPA2-PSK keys, including t… |
| 158 | [Hack-the-box/wifi-phisher](https://github.com/Hack-the-box/wifi-phisher) | 76 | Python | Automated victim-customized phishing attacks against Wi-Fi clients |
| 159 | [hackcrypto/fluxion](https://github.com/hackcrypto/fluxion) | 75 | Shell | Fluxion is a security auditing and social-engineering research tool. It is a remake of linset by … |
| 160 | [teja156/wifi-hacking-raspberrypi](https://github.com/teja156/wifi-hacking-raspberrypi) | 75 | Python | An automation script written in Python to convert a Raspberry Pi into a WiFi hacking device |
| 161 | [letox4/netpwn](https://github.com/letox4/netpwn) | 73 | Python | Suite grafica de auditoria de redes (pentesting) con interfaz web: descubrimiento, escaneo, MITM,… |
| 162 | [nuncan/wifite2mod](https://github.com/nuncan/wifite2mod) | 73 | Python | Rolling Release Branch for community PR's @Credits to derv82 & the community |
| 163 | [akr3ch/wicker-gui](https://github.com/akr3ch/wicker-gui) | 72 | Shell | automate wifi hacking with wicker |
| 164 | [BadKiko/Tsunami-Fi](https://github.com/BadKiko/Tsunami-Fi) | 72 | Python | Tsunami-Fi is simple multi-tool bash application for Wi-Fi attacks |
| 165 | [dom96/deauther](https://github.com/dom96/deauther) | 72 | Nim | An interactive command-line deauther for macOS. |
| 166 | [linkp2p/WPS-PIN](https://github.com/linkp2p/WPS-PIN) | 72 | Shell |  # This scripts is edited under the General Public License as defined by the Free software founda… |
| 167 | [sensepost/shinai-fi](https://github.com/sensepost/shinai-fi) | 72 | Shell | Docker images for learning wifi hacking |
| 168 | [vi3w-s0urce/xDeauther](https://github.com/vi3w-s0urce/xDeauther) | 71 | Shell | Easy tools for deauthentication attack wifi |
| 169 | [davidpanic/Kali-MiTM-Evil-twin](https://github.com/davidpanic/Kali-MiTM-Evil-twin) | 70 | Shell | A script that creates a wifi hotspot on kali linux that can view usernames and passwords of ssl l… |
| 170 | [micolous/helvetic](https://github.com/micolous/helvetic) | 70 | Python | Hacking / reverse engineering the Fitbit Aria (WiFi enabled bathroom scales) |
| 171 | [Leviathan36/SKA](https://github.com/Leviathan36/SKA) | 69 | Shell | Simple Karma Attack |
| 172 | [Drew-Alleman/autodeauth](https://github.com/Drew-Alleman/autodeauth) | 68 | Python | Automated Linux service that collects information on local Wi-Fi networks and performs deauthenti… |
| 173 | [m4lal0/wifiAttack](https://github.com/m4lal0/wifiAttack) | 67 | Shell | Herramienta ideal para automatizar ataques WiFi (WEP & WPA/WPA2 - PSK) destinados a la obtención … |
| 174 | [ricardojoserf/wpa2-enterprise-attack](https://github.com/ricardojoserf/wpa2-enterprise-attack) | 66 | Shell | Virtual machines and scripts to attack WPA2-Enterprise networks through Rogue Access Points downg… |
| 175 | [z0m31en7/deauthalyzer](https://github.com/z0m31en7/deauthalyzer) | 66 | Python | Deauthalyzer is a script designed to monitor WiFi networks and detect deauthentication attacks. I… |
| 176 | [karthi-the-hacker/WIFIHacker](https://github.com/karthi-the-hacker/WIFIHacker) | 65 | HTML | An all-in-one WiFi pentesting tool designed to automate and simplify WiFi security auditing and a… |
| 177 | [mike01/sledgehammer](https://github.com/mike01/sledgehammer) | 65 | Python | :hammer: :signal_strength: WiFi-Jammer/DoS toolset |
| 178 | [RPxGoon/3TH1C4L-MultiTool](https://github.com/RPxGoon/3TH1C4L-MultiTool) | 65 | Python | A 'Work In-Progress' OSINT, Networking, Discord, and other General Purpose Multi-Tool Written 100… |
| 179 | [r4ulcl/WiFiChallengeLab](https://github.com/r4ulcl/WiFiChallengeLab) | 64 | Shell | WiFi hacking Lab. Virtualized WiFi pentesting laboratory without the need for physical WiFi cards… |
| 180 | [wahid987654321/hecker](https://github.com/wahid987654321/hecker) | 64 | — | KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau hp lu gw… |
| 181 | [zflemingg1/WiFi-Jammer](https://github.com/zflemingg1/WiFi-Jammer) | 63 | Python | Tool to automate wifi jamming |
| 182 | [Touti-Sudo/Touti-Cracker](https://github.com/Touti-Sudo/Touti-Cracker) | 61 | Python | Touti Cracker is a cross-platform ethical hacking toolkit for educational purposes, featuring pas… |
| 183 | [xpz3/airgeddonplugins](https://github.com/xpz3/airgeddonplugins) | 61 | HTML | Plugins for airgeddon |
| 184 | [buke18/5G-WiFi-deauth](https://github.com/buke18/5G-WiFi-deauth) | 60 | Assembly | 2.4Ghz&5Ghz双频WiFi deauth 安全测试模块，并对现有的固件做了小改动和升级处理【2.4Ghz & 5Ghz dual-band WiFi deauth security te… |
| 185 | [hacefresko/EvilPortal](https://github.com/hacefresko/EvilPortal) | 60 | Python | Python script to perform phishing attacks through captive portals, made for learning purposes |
| 186 | [Leviathan36/wifibang](https://github.com/Leviathan36/wifibang) | 60 | Shell | wifi attacks suite |
| 187 | [mvondracek/wifimitm](https://github.com/mvondracek/wifimitm) | 59 | Python | Wi-Fi Machine-in-the-Middle: Automation of MitM Attack on Wi-Fi Networks |
| 188 | [AbhinavBaranwal/wifi-hacking-termux](https://github.com/AbhinavBaranwal/wifi-hacking-termux) | 58 | Python |  |
| 189 | [s0i37/karma](https://github.com/s0i37/karma) | 58 | Python | karma WiFi attack implementation |
| 190 | [silverxcyber/WifiHackBar](https://github.com/silverxcyber/WifiHackBar) | 58 | HTML | WifiHackBar - A powerful WiFi Hacking Tool. Scan networks, perform deauthentication attacks, and … |
| 191 | [cimplesid/Wifi-jammer-service](https://github.com/cimplesid/Wifi-jammer-service) | 57 | Python | A free script by sid that deauth all user from the network contiuosly forever |
| 192 | [gentle-grt/Wifi-Hacker](https://github.com/gentle-grt/Wifi-Hacker) | 57 | — | Hack any wifi with this amazing wifi hack for Android on termux |
| 193 | [hackthebox/PMKID](https://github.com/hackthebox/PMKID) | 56 | PHP | A module for the WiFi Pineapple to facilitate the PMKID attack. |
| 194 | [martian56/venx](https://github.com/martian56/venx) | 56 | Python | Wifi cracking, pentesting tool.  Pre-connection and Post-connection attacks. Capturing handshakes… |
| 195 | [spider863644/Wifi-Hack](https://github.com/spider863644/Wifi-Hack) | 56 | Python | A hacking tool for brute forcing WiFi password |
| 196 | [Vodker/wifimosys](https://github.com/Vodker/wifimosys) | 56 | Shell | Ataque EVIL TWIN |
| 197 | [pupi1985/marfil](https://github.com/pupi1985/marfil) | 54 | PHP | Marfil is an extension of the Aircrack-ng suite, used to assess WiFi network security. It allows … |
| 198 | [4ndreas/WiFI-RGBWW-module](https://github.com/4ndreas/WiFI-RGBWW-module) | 53 | Arduino | Chinse Wifi rgbww controller module hack |
| 199 | [emanuele-f/UsbWifiMonitorApi](https://github.com/emanuele-f/UsbWifiMonitorApi) | 53 | Java | API specification of the USB WiFi Monitor Android app |
| 200 | [atul12354/wifi_bruteforcer_fsecurify_6.0.apk](https://github.com/atul12354/wifi_bruteforcer_fsecurify_6.0.apk) | 52 | — | Hack wifi in bruteforcer app |
| 201 | [jerryryle/rogueportal](https://github.com/jerryryle/rogueportal) | 52 | HTML | Rogue Captive Portal using a Raspberry Pi |
| 202 | [pippianders/wifi-hacking-tools](https://github.com/pippianders/wifi-hacking-tools) | 52 | C |  |
| 203 | [Seyitq/nrf24l01-wifi-jammer](https://github.com/Seyitq/nrf24l01-wifi-jammer) | 52 | C++ | The activity of the nRF24 RF radio board is transmitted to the Arduino board via the serial inter… |
| 204 | [Hariss-Gills/pifi](https://github.com/Hariss-Gills/pifi) | 51 | Shell | Whenever the Raspberry Pi Device is turned on, it attempts to attack all the wifi networks within… |
| 205 | [nugroho466/Hacker-s-Pack-for-termux](https://github.com/nugroho466/Hacker-s-Pack-for-termux) | 51 | — | Special thanks to Ranginang67 for DarkFly (Collection of hack tools), threat9 for routersploit (W… |
| 206 | [pakistanihackergroup/TERMUX-HACKING-](https://github.com/pakistanihackergroup/TERMUX-HACKING-) | 51 | — | list of the best Termux hacking tools  android osint penetration-testing awesome-list wifi-securi… |
| 207 | [ZeroDayArcade/capture-handshake-wpa-wifi-hacking](https://github.com/ZeroDayArcade/capture-handshake-wpa-wifi-hacking) | 51 | Python | A python script for capturing 4-way handshakes for WPA/WPA2 WiFi networks. |
| 208 | [ccyl13/WiFiPentestTool](https://github.com/ccyl13/WiFiPentestTool) | 50 | Python | Herramienta para hacking wifi con múltiples opciones. |
| 209 | [666sempron999/HackRF_ONE-wifi-jammer](https://github.com/666sempron999/HackRF_ONE-wifi-jammer) | 49 | Python | Tis repository is proof of concept wifi denial of service (DOS) on phisical layer |
| 210 | [Kalihackz/Wifi_Ddos_EvilTwin_Combo](https://github.com/Kalihackz/Wifi_Ddos_EvilTwin_Combo) | 49 | HTML | DDos and Evil Twin Combo |
| 211 | [kashmir54/kashmir54.github.io](https://github.com/kashmir54/kashmir54.github.io) | 49 | HTML | Cibersecurity blog. CTFs, writeups, electronics and more! |
| 212 | [NSM-Barii/Yoda](https://github.com/NSM-Barii/Yoda) | 49 | Python | Passive RF monitor — real-time WiFi and BLE surveillance with deauth detection, device tracking, … |
| 213 | [arxhr007/wifistrike](https://github.com/arxhr007/wifistrike) | 48 | Python | Pure-Python WiFi deauth & recon tool, scan access points and clients, launch targeted or broadcas… |
| 214 | [alexivkin/wifipicket](https://github.com/alexivkin/wifipicket) | 47 | Python | Selective wifi jammer - control who can connect where |
| 215 | [gianfelicevincenzo/RoguePortal](https://github.com/gianfelicevincenzo/RoguePortal) | 47 | Shell | A Phishing WIFI Rogue Captive Portal! :smiling_imp: |
| 216 | [0x4156-AV/WiFi-Attack](https://github.com/0x4156-AV/WiFi-Attack) | 46 | Shell | A script to brute force a WiFi networks password |
| 217 | [lucthienphong1120/Aircrack-ng-handbook](https://github.com/lucthienphong1120/Aircrack-ng-handbook) | 46 | — | All in one - Everything useful about Aircrack-ng |
| 218 | [sethleedy/Auto-Besside-Capturer](https://github.com/sethleedy/Auto-Besside-Capturer) | 45 | Shell | Capture WPA handshakes, using besside-ng. Auto upload to http://wpa-sec.stanev.org for cracking t… |
| 219 | [markszabo/Hacktivity2016](https://github.com/markszabo/Hacktivity2016) | 44 | Arduino | Repository for my workshop 'Wifi hacking with a 4 dollar microcontroller' on Hacktivity 2016 |
| 220 | [mr-cybro/WiFisploit](https://github.com/mr-cybro/WiFisploit) | 44 | Python | WiFisploit is a tool designed to scan and attack Wi-Fi networks using variety of powerful and eff… |
| 221 | [Mahfuz-THBD/Wifi_Hack_Installer](https://github.com/Mahfuz-THBD/Wifi_Hack_Installer) | 43 | Python | Hack Wifi With Your Rooted Android Device. |
| 222 | [BigBoss1986/Android-HUAWEISNE-L21](https://github.com/BigBoss1986/Android-HUAWEISNE-L21) | 42 | — | apk wifi hack tool |
| 223 | [iSecur1ty/wifi-jammer](https://github.com/iSecur1ty/wifi-jammer) | 42 | Python | Python automated wifi jammer |
| 224 | [shabir-mp/WiFi-Password-Cracker](https://github.com/shabir-mp/WiFi-Password-Cracker) | 42 | Python | WiFi Security & Router Diagnostics is a cross-platform Python script that retrieves saved WiFi pr… |
| 225 | [domienschepers/wifi-deauthentication](https://github.com/domienschepers/wifi-deauthentication) | 41 | Python | Wi-Fi MFP Deauthentication: proof-of-concepts, security patches, and more. |
| 226 | [PNPtutorials/PNP-WiFi-Jammer](https://github.com/PNPtutorials/PNP-WiFi-Jammer) | 41 | Shell | This script continuously jams all the WiFi networks around you. |
| 227 | [buke18/5G-Wi-Fi-deauth-can-support-flipper-zero-](https://github.com/buke18/5G-Wi-Fi-deauth-can-support-flipper-zero-) | 40 | Assembly | 5G&2.4Ghz Wi-Fi deauth for Flipper zero to easily test the WiFi security |
| 228 | [sighook/refluxion](https://github.com/sighook/refluxion) | 40 | HTML | Refluxion -- MITM WPA attacks tool |
| 229 | [ICSec/airpwn-ng](https://github.com/ICSec/airpwn-ng) | 39 | Python | Packet injection for wifi; simplified. |
| 230 | [LxaNce-Hacker/wifi-jammer](https://github.com/LxaNce-Hacker/wifi-jammer) | 39 | Shell | This tool is used to jam any wifi network in your local area network. |
| 231 | [mattfrias/rpi3-wifijammer](https://github.com/mattfrias/rpi3-wifijammer) | 39 | Python | WiFi Jammer Script for Raspberry Pi 3 Model B |
| 232 | [MikkoParkkola/nowifi](https://github.com/MikkoParkkola/nowifi) | 39 | Go | No WiFi? Now WiFi. One command. 27 techniques. Bypass any captive portal. |
| 233 | [Revimal/WifiDeauth](https://github.com/Revimal/WifiDeauth) | 39 | C++ | A lightweight Wi-Fi auto deauthentication attack tool (libtins/C++) |
| 234 | [victorpreston/HackLab](https://github.com/victorpreston/HackLab) | 39 | Python | Welcome to HackLab, your go-to resource for hands-on cybersecurity projects. This repository is a… |
| 235 | [billpcs/jammer](https://github.com/billpcs/jammer) | 38 | Shell | 📶 A Bash script to automate the continuous circular deauthentication of all the wifi networks in … |
| 236 | [dedsecurity/dedsecurity-framework](https://github.com/dedsecurity/dedsecurity-framework) | 38 | Python | Ded Security Framework is a tool aimed at security professionals |
| 237 | [johnoseni1/Router-hacker-Exploit-and-extract-user-and-password-](https://github.com/johnoseni1/Router-hacker-Exploit-and-extract-user-and-password-) | 38 | Python | This is a python wifi (router) hacker , having ability to search for mikrotic devices around you … |
| 238 | [p0dalirius/WifiListProbeRequests](https://github.com/p0dalirius/WifiListProbeRequests) | 38 | Python | Monitor 802.11 probe requests from a capture file or network sniffing!  |
| 239 | [s0lst1c3/evil_twin](https://github.com/s0lst1c3/evil_twin) | 38 | Python | Python script for peforming basic Evil Twin attacks on open wifi networks. Written for my tutoria… |
| 240 | [h9zdev/EthiFi](https://github.com/h9zdev/EthiFi) | 37 | C | EthiFi is a affordable WiFi pentesting platform for testing and learning  |
| 241 | [jackind424/wifi-hacker](https://github.com/jackind424/wifi-hacker) | 37 | Shell | Shell Script For Attacking Wireless Connections Using Built-In Kali Tools. Supports All Securitie… |
| 242 | [KaraZajac/OVERWATCH](https://github.com/KaraZajac/OVERWATCH) | 37 | Kotlin | Android app that flags nearby Flock ALPRs, Axon body cams, police and surveillance aircraft from … |
| 243 | [mrjuice01/Wifi-Cracker](https://github.com/mrjuice01/Wifi-Cracker) | 37 | Python | Proffesional Wifi Hacking Tool Using Termux, Kali, Ubuntu or any Terminal. Tool Requies Root Accs… |
| 244 | [rootsaid/ducky_over_wifi](https://github.com/rootsaid/ducky_over_wifi) | 37 | Arduino | HID or Human Interface Devices are Devices that takes input from human and pass it on to the devi… |
| 245 | [SagarBiswas-MultiHAT/WiFi-Dictionary-Attack](https://github.com/SagarBiswas-MultiHAT/WiFi-Dictionary-Attack) | 37 | Python | WiFi Dictionary Attack is a compact, Python-based Wi‑Fi security testing script. It scans nearby … |
| 246 | [GISDev01/security-ssid-abi](https://github.com/GISDev01/security-ssid-abi) | 36 | Python | Sniff wifi probes from nearby devices (passive monitoring only) and logs to a Django App/DB (with… |
| 247 | [intuitibits/wifiexplorer-sensor](https://github.com/intuitibits/wifiexplorer-sensor) | 36 | Python | [DEPRECATED] Enables remote scanning in WiFi Explorer Pro |
| 248 | [jerryryle/rogue_ap](https://github.com/jerryryle/rogue_ap) | 36 | Shell | Rogue AP using a Raspberry Pi Zero W |
| 249 | [Mr-pentest/Wifi-Hacking](https://github.com/Mr-pentest/Wifi-Hacking) | 36 | Python | ⚡ A powerful Python-based WiFi brute-force tool for ethical hacking and wireless security testing… |
| 250 | [p0dalirius/crEAP](https://github.com/p0dalirius/crEAP) | 36 | Python | crEAP will identify WPA Enterprise mode EAP types and harvest usernames and/or handshakes if inse… |
| 251 | [Woofydude/wifi_mitm](https://github.com/Woofydude/wifi_mitm) | 36 | C++ | for flipper zero, it is a man-in-the-middle app to be able to spoof a network name and get passwo… |
| 252 | [GiovanniBaccichet/openwrt-multi-sniffer](https://github.com/GiovanniBaccichet/openwrt-multi-sniffer) | 35 | TeX | OpenWrt-based Access Point multi-channel WiFi Probe Request sniffer 📡 |
| 253 | [isecbaz/WiFi-Hack](https://github.com/isecbaz/WiFi-Hack) | 35 | Python | Fake WiFi Hacking Tool for Windows Reverse Shell |
| 254 | [leo-aa88/wifi-jammer](https://github.com/leo-aa88/wifi-jammer) | 35 | Python | Continuously perform deauthentication attacks on all detectable stations |
| 255 | [R3DDY97/KICKthemOUT3](https://github.com/R3DDY97/KICKthemOUT3) | 35 | Python | K1CK  devices off your N3TW0RK by performing an ARP Spoof attack with Python3+ compatability |
| 256 | [tranthangit/crackwifi](https://github.com/tranthangit/crackwifi) | 35 | JavaScript | CRACKWIFI là một ứng dụng máy tính (Desktop App) mạnh mẽ được xây dựng bằng Electron, cung cấp gi… |
| 257 | [GregoryConrad/WirelessEMP](https://github.com/GregoryConrad/WirelessEMP) | 34 | Shell | Wireless EMP (WEMP) - A simple shell script that kicks all devices off of a network for as long a… |
| 258 | [morpheuslord/Brute-Hacking-Framework-SourceCode](https://github.com/morpheuslord/Brute-Hacking-Framework-SourceCode) | 34 | Batchfile | hacking framework complete source-code for web, wifi, url, sql-injection and doing a complete web… |
| 259 | [RonnyDo/Wammer](https://github.com/RonnyDo/Wammer) | 34 | Vala | Jamming your WiFi network |
| 260 | [ip2k/WiFi-Abuse-Autokiller](https://github.com/ip2k/WiFi-Abuse-Autokiller) | 33 | Shell | Finds abusive WiFi users using way too much traffic on public wifi and sends them a sack of hot d… |
| 261 | [kaushalag29/Windows-Hacking-Scripts-With-Python](https://github.com/kaushalag29/Windows-Hacking-Scripts-With-Python) | 33 | Python | Hacking Wifi-Passwords,Chrome-Saved-Passwords,Copying the Scripts to Windows-Startup folder,Index… |
| 262 | [M0M0Sec/MoMo](https://github.com/M0M0Sec/MoMo) | 33 | Python | 🎯 Pi 5 Wardriving & Wireless Pentest Platform \| WiFi/BLE/SDR Attacks \| WPA3 • Evil Twin • Karma… |
| 263 | [naiksrinu/UAV_DataSet_NetworkCommunication](https://github.com/naiksrinu/UAV_DataSet_NetworkCommunication) | 33 | Python | UAV Network Communication Experimental dataset is a collection of network traffic captured from a… |
| 264 | [RLabs-Inc/wifikit](https://github.com/RLabs-Inc/wifikit) | 33 | Rust | WiFi pentesting toolkit for MacOS and Linux*. Pure Rust, single binary, real-time interactive CLI. |
| 265 | [skickar/WiFiHackingWorkshop](https://github.com/skickar/WiFiHackingWorkshop) | 33 | C++ | Files for the WI-Fi hacking workshop |
| 266 | [adde88/krackattacks-pineapple](https://github.com/adde88/krackattacks-pineapple) | 32 | C | WPA2 Key reinstallation attack (KRACK) on the WiFi Pineapples |
| 267 | [Esther7171/WiFi-Hacking-Guide](https://github.com/Esther7171/WiFi-Hacking-Guide) | 32 | Shell | Hands-on WiFi hacking and penetration testing guide: monitor mode, recon, WPA2 handshake capture … |
| 268 | [oyi77/wifi-jammer](https://github.com/oyi77/wifi-jammer) | 32 | Python | Advanced WiFi security testing tool — 10 attack types (deauth, PMKID, evil twin, channel hop), CL… |
| 269 | [sllumenikmati21/misteriusxx](https://github.com/sllumenikmati21/misteriusxx) | 32 | — | KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau hp lu gw… |
| 270 | [Alif0x1/wifiKill](https://github.com/Alif0x1/wifiKill) | 30 | Python | WiFikill Tool is a comprehensive utility designed to help security professionals and ethical hack… |
| 271 | [DubiousCactus/ShockWave](https://github.com/DubiousCactus/ShockWave) | 30 | C++ | ShockWave looks up for every connected device on the local network, then starts sending deauthent… |
| 272 | [j1a2k3e4/wifi-password-hack](https://github.com/j1a2k3e4/wifi-password-hack) | 30 | — | Automatically exported from code.google.com/p/wifi-password-hack |
| 273 | [javi-ln/wifi-spartan](https://github.com/javi-ln/wifi-spartan) | 30 | Python | Smart pentesting toolkit for modern WPA/WPA2 networks ⚔️📡 |
| 274 | [mkdirlove/Wifi_Hacker](https://github.com/mkdirlove/Wifi_Hacker) | 30 | — | Wifi hacker for Termux android. |
| 275 | [0xbitx/DEDSEC_STARSYNC](https://github.com/0xbitx/DEDSEC_STARSYNC) | 29 | PHP | An effective tool for hacking starlink wifi password. |
| 276 | [psibot/wifi_wardriving](https://github.com/psibot/wifi_wardriving) | 29 | Shell | Some scripts and stuff for wardriving and wifi hacks .... works great on kali and ubuntu 32 bit .… |
| 277 | [stetro/ngn-sniffer](https://github.com/stetro/ngn-sniffer) | 29 | CSS | Android APP for NGN to sniff location based rf signals like GSM, Bluetooth or Wifi  |
| 278 | [tajmancrackit/How-to-install-kali-nethunter-in-termux](https://github.com/tajmancrackit/How-to-install-kali-nethunter-in-termux) | 29 | — | What is Kali Nethunter?  Kali Nethunter is a Android ROM which is designed for Penetration Testin… |
| 279 | [6e726d/Native-WiFi-API-Beacon-Sniffer](https://github.com/6e726d/Native-WiFi-API-Beacon-Sniffer) | 28 | C++ | Tool that dumps beacon frames to a pcap file. Works on Windows Vista or Later with any Wireless C… |
| 280 | [NABEGHEHACOM/WifiExtractor](https://github.com/NABEGHEHACOM/WifiExtractor) | 28 | Python | With this  Script you Can Access all Saved WiFi Passwords in Windows |
| 281 | [zexceed12300/rtl8188eu](https://github.com/zexceed12300/rtl8188eu) | 28 | C | RTL8188EU WiFi driver support monitor mode & frame injection |
| 282 | [error434/wirehack](https://github.com/error434/wirehack) | 27 | Python | Scripts for hacking through wireless network [WiFi] |
| 283 | [KylerCondran/WarCappin](https://github.com/KylerCondran/WarCappin) | 27 | Perl | WiFi Hacking: Autonomously man in the middle deauthenticate WPA2 wireless networks and packet cap… |
| 284 | [morpheuslord/passinfo.cmd](https://github.com/morpheuslord/passinfo.cmd) | 27 | Batchfile | contains a bruteforcer wifi hacker an batch to exe converter contains a n verity of usefull tools  |
| 285 | [rampage128/hombot-interface](https://github.com/rampage128/hombot-interface) | 27 | JavaScript | A replacement for the original LG Hombot WIFI-hack web interface. |
| 286 | [ruvnet/wifi-veil](https://github.com/ruvnet/wifi-veil) | 27 | Rust | WiFi Veil — a privacy firewall against unauthorized WiFi sensing. Compliant waveform controls onl… |
| 287 | [ShlomiRex/WiFi-EvilTwin](https://github.com/ShlomiRex/WiFi-EvilTwin) | 27 | Python | Create Evil Twin network that deauthernticates victims to force them to connect to your evil AP. |
| 288 | [taufiks22/new](https://github.com/taufiks22/new) | 27 | — | KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau hp lu gw… |
| 289 | [YogaRmdn/Dos-WiFi](https://github.com/YogaRmdn/Dos-WiFi) | 27 | Python | Easy to use tools for WiFi jamming created in Python |
| 290 | [ZeroDayArcade/RG353-WiFi-Penetration-Tool](https://github.com/ZeroDayArcade/RG353-WiFi-Penetration-Tool) | 27 | Python | Hacking WiFi Networks with the Anbernic RG353 line of hardware and other Retro Gaming Handhelds |
| 291 | [albertyw/indoor-localization](https://github.com/albertyw/indoor-localization) | 26 | Java | Indoor Localization by Wifi/Gyroscope/Accelerometer; made at Dropbox Hack Week 2013 |
| 292 | [dgiese/aerodust](https://github.com/dgiese/aerodust) | 26 | Python | HackBeanpot 2018, Hacks for Xiaomi vaccum cleaning robots: autonomous WiFi heatmap/mapping (very … |
| 293 | [dkyazzentwatwa/cypher-jammer-2nrf-oled](https://github.com/dkyazzentwatwa/cypher-jammer-2nrf-oled) | 26 | C++ | A wifi/bluetooth jammer with an oled screen and buttons. |
| 294 | [emrekybs/Wifi-Purple](https://github.com/emrekybs/Wifi-Purple) | 26 | Python | Automate script for wifi hacking |
| 295 | [Hacker-World0/Wifi-Jammer](https://github.com/Hacker-World0/Wifi-Jammer) | 26 | Python | These are favored by companies who deal with sensitive information to prevent leaks. The 5GHz WiF… |
| 296 | [HasnainDarkNet/Wifi-tester](https://github.com/HasnainDarkNet/Wifi-tester) | 26 | Python | WiFi Tester is a simple cybersecurity tool to test WiFi passwords using a wordlist.  This tool is… |
| 297 | [JulienFink/WiFi-Project](https://github.com/JulienFink/WiFi-Project) | 26 | Python | Pre-connection attacks, gaining access & post-connection attacks on WEP, WPA & WPA2. 🛰✔️ |
| 298 | [msillano/tuyaDAEMON](https://github.com/msillano/tuyaDAEMON) | 26 | — | A generic IOT framework, open for all user node-red devices and for any advanced custom logic, wi… |
| 299 | [N0tA1dan/Crab](https://github.com/N0tA1dan/Crab) | 26 | Python | Network/host scanner and information gatherer |
| 300 | [Quancivillious-Hornswoggle/RAVAGE](https://github.com/Quancivillious-Hornswoggle/RAVAGE) | 26 | Python | A Linux shell tool that has multiple tools such as, Instagram Scraper, Phisher, Network Scanner, … |
| 301 | [urld/wifitracker](https://github.com/urld/wifitracker) | 26 | Go |  |
| 302 | [wickednull/KTOX_Pi](https://github.com/wickednull/KTOX_Pi) | 26 | Python | KTOx_Pi — Network penetration & purple team suite for Raspberry Pi Zero 2W. Joystick-controlled L… |
| 303 | [Ba5hb0y/Deadfi_deauther-](https://github.com/Ba5hb0y/Deadfi_deauther-) | 25 | Shell | This tool will allows u to deauth or kick off an specific device from an given AP  |
| 304 | [mrExploitwriter/WiFi-Password](https://github.com/mrExploitwriter/WiFi-Password) | 25 | Python | Obtain connected WiFi passwords |
| 305 | [Boris-2021/wifi-dictionary-attack](https://github.com/Boris-2021/wifi-dictionary-attack) | 24 | Python | 字典攻击，你懂的 |
| 306 | [javierbu/awitas](https://github.com/javierbu/awitas) | 24 | Shell |  Ataque WPS transparente con rogue AP  |
| 307 | [nbergont/wofea_v10_hack](https://github.com/nbergont/wofea_v10_hack) | 24 | C++ | Low cost wifi alarm Wofea V10 Esphome hack |
| 308 | [salman1123/Wifi-hacking-](https://github.com/salman1123/Wifi-hacking-) | 24 | — |                                              #!/usr/bin/env python import os import subprocess fr… |
| 309 | [WiPi-Hunter/PiNokyo](https://github.com/WiPi-Hunter/PiNokyo) | 24 | Python | 🍓 🤥🍍If threats like wifi pineapple attacks or karma attacks are active around, users will be info… |
| 310 | [digiampietro/hash-capture](https://github.com/digiampietro/hash-capture) | 23 | Perl | Automatically scans nearby WiFi networks, de-authenticates clients and tries to capture the four … |
| 311 | [katandev18/wifiphiser](https://github.com/katandev18/wifiphiser) | 23 | Shell | WiFi phising attack |
| 312 | [malsearchs/Wifi-Hacking-AircrackNG-Cheatsheet](https://github.com/malsearchs/Wifi-Hacking-AircrackNG-Cheatsheet) | 23 | — | AircrackNG commands guide |
| 313 | [Wifimon/Wifimon](https://github.com/Wifimon/Wifimon) | 23 | C | Wi-fi 802.11 Beacon Frame sniffer |
| 314 | [0x90/iSniff](https://github.com/0x90/iSniff) | 22 | Python | Tiny WiFi sniffer with Scapy for MAC OS X |
| 315 | [amibhai/wifi_down](https://github.com/amibhai/wifi_down) | 22 | Python | An automated, menu-driven WiFi security auditing framework with an end-to-end attack, cracking, a… |
| 316 | [arkypita/Vigotech-VG-L7X](https://github.com/arkypita/Vigotech-VG-L7X) | 22 | C++ | VG-L7X Vigotech engraver (WiFi model) resources and hack |
| 317 | [kxyznew/WiFi-Pineapple-Pager-Master-Control-Suite](https://github.com/kxyznew/WiFi-Pineapple-Pager-Master-Control-Suite) | 22 | Python | ## Key Features: - **Tri-Band Attacks**: 2.4GHz, 5GHz, 6GHz simultaneous operations - **Autonomou… |
| 318 | [ZeroDayArcade/capture-pmkid-wpa-wifi-hacking](https://github.com/ZeroDayArcade/capture-pmkid-wpa-wifi-hacking) | 22 | Python | A python script for capturing a PMKID from a WiFi router for cracking WPA/WPA2 passwords. |
| 319 | [byt3n33dl3/NetVenom](https://github.com/byt3n33dl3/NetVenom) | 21 | C | WiFi Pentesting on Mac filters bypass and SSID manipulation. |
| 320 | [CraftyZA/DetectWifiHack](https://github.com/CraftyZA/DetectWifiHack) | 21 | C | based on my previous deauth detection, but will expand to detect other hack types as well. |
| 321 | [ElmanTr/python-wifi-hack-with-subprocess](https://github.com/ElmanTr/python-wifi-hack-with-subprocess) | 21 | Python | A simple program with Python to hack WiFi ! getting WiFi information and passwords from CMD by su… |
| 322 | [i-am-unbekannt/unbekannt-framework](https://github.com/i-am-unbekannt/unbekannt-framework) | 21 | Python | A Hacking and Pentesting Tool for Windows |
| 323 | [imnortheastt/wireless_cracking_tools](https://github.com/imnortheastt/wireless_cracking_tools) | 21 | Python | Wifi cracking tools |
| 324 | [jimbon25/WIFI-TOOLKIT](https://github.com/jimbon25/WIFI-TOOLKIT) | 21 | CSS | A comprehensive, menu-driven utility for Wi-Fi penetration testing and security auditing. |
| 325 | [Whomrx666/Xdeauth-wifi](https://github.com/Whomrx666/Xdeauth-wifi) | 21 | Python | Xdeauth-wifi is a tool used to carry out DDOS attacks on a WiFi or is usually called a WiFi deauther |
| 326 | [GoldSkull-777/GoldJam](https://github.com/GoldSkull-777/GoldJam) | 20 | Python | WiFi jamming tool for Kali Linux using Aircrack-ng & Python. Built for educational and ethical te… |
| 327 | [jakuta-tech/Wifi-Cracker](https://github.com/jakuta-tech/Wifi-Cracker) | 20 | Python | Wifi-Cracker.py to Hack WPS/WPA/WPA2 Networks |
| 328 | [trfahim/WIFI-HACK-LINUX](https://github.com/trfahim/WIFI-HACK-LINUX) | 20 | Python | Powerful WiFi Hacking penetration testing tools for Linux, designed for ethical hacking, security… |
| 329 | [waheeb71/WiFi-Hacking-Tool](https://github.com/waheeb71/WiFi-Hacking-Tool) | 20 | Python | WiFi Hacking Tool is a powerful Python-based tool designed for ethical hacking, network analysis,… |
| 330 | [dotberg/pwnagotchi-zero](https://github.com/dotberg/pwnagotchi-zero) | 19 | Java | Autonomous AI-driven WiFi security tool for rooted Android. Native Qualcomm monitor mode, Thompso… |
| 331 | [xiv3r/uz801-usb-pentest](https://github.com/xiv3r/uz801-usb-pentest) | 19 | — | UZ801 4G USB Modem |
| 332 | [mattlawer/wifipineapple-PMKID](https://github.com/mattlawer/wifipineapple-PMKID) | 18 | HTML |  PMKID Attack Module for the WiFi Pineapple |
| 333 | [mishra9759harshit/wifi-attack-tool](https://github.com/mishra9759harshit/wifi-attack-tool) | 18 | Python | WiFi Attack Tool is an advanced penetration testing and cybersecurity auditing tool that automate… |
| 334 | [OmarVillaWolf/RedTeam-Attack-Library](https://github.com/OmarVillaWolf/RedTeam-Attack-Library) | 18 | — | Red Team Techniques & TTPs: AD, C2, SCADA, PrivEsc, Web Hacking, Buffer Overflow, WiFi. |
| 335 | [p4wnsolo/p4wnsolo-joyterm](https://github.com/p4wnsolo/p4wnsolo-joyterm) | 18 | Python | 🕹️ Enter a command with OLED Joystick  ▶️ Run + Display output on OLED Screen (Works with P4wnP1!) |
| 336 | [sharathc213/wifi_deauth_detector](https://github.com/sharathc213/wifi_deauth_detector) | 18 | CSS | a web interface  to detect deauthentication attack |
| 337 | [socket8088/WiFi-Pentest](https://github.com/socket8088/WiFi-Pentest) | 18 | Shell | Wireless Pentest |
| 338 | [82goober82/fluxionwpacrack](https://github.com/82goober82/fluxionwpacrack) | 17 | Shell | Fluxion is the future of MITM WPA attacks  Fluxion is a security auditing and social-engineering … |
| 339 | [abzicht/heyyou](https://github.com/abzicht/heyyou) | 17 | Python | A simple script demonstrating the power that comes with SSID sniffing |
| 340 | [chargz/DeauthSniff](https://github.com/chargz/DeauthSniff) | 16 | C | DeauthSniff alerts users about potential WiFi deauthentication attacks. |
| 341 | [jiansiting/HotAP-Jammer](https://github.com/jiansiting/HotAP-Jammer) | 16 | Python | Jammer 2.4G and 5G AP wifi |
| 342 | [LagrangianLad/tewcrack](https://github.com/LagrangianLad/tewcrack) | 16 | Shell | Run a dictionary attack on a Wifi network to get it's password |
| 343 | [ra1nb0rn/CDeauth](https://github.com/ra1nb0rn/CDeauth) | 16 | C |  A WiFi deauthentication tool written in C |
| 344 | [sobri3195/Pegabox](https://github.com/sobri3195/Pegabox) | 16 | Python | A collection of Windows, Website and Wifi pentesting scripts and exploits. |
| 345 | [Anamika21/WiHawk](https://github.com/Anamika21/WiHawk) | 15 | — | A wireless router when newly installed has a default admin password depending on its manufacturer… |
| 346 | [anonymous-beta/Wifidaemon](https://github.com/anonymous-beta/Wifidaemon) | 15 | Python | WiFiDAEMON is a next-generation, modular, and demon-themed Wi-Fi pentesting framework. Built from… |
| 347 | [ashrafuljoy62/WiFuX](https://github.com/ashrafuljoy62/WiFuX) | 15 | Python | A powerful tool for hacking WiFi using Termux/Linux. |
| 348 | [FLOCK4H/Cappy](https://github.com/FLOCK4H/Cappy) | 15 | HTML | WiFi Evil Twin Attack - Credential Harvest Tool |
| 349 | [LowSkillDeveloper/AutoWPS-Script](https://github.com/LowSkillDeveloper/AutoWPS-Script) | 15 | Shell | Simple Auto WPS Pixie Dust Attack script for walking (using Wifite2) |
| 350 | [lynalan2/wifi_scripts](https://github.com/lynalan2/wifi_scripts) | 15 | Python | Menu-driven Wi-Fi auditing toolkit: handshake capture, hashcat cracking, and Evil Twin attacks. E… |
| 351 | [MBHudson/APEX-MassAP-Deauth](https://github.com/MBHudson/APEX-MassAP-Deauth) | 15 | Shell | Aggressive Mass AP Deauth/Jammer (PWN ALL WIFI IN RANGE) |
| 352 | [meepmaster360/wifiduck](https://github.com/meepmaster360/wifiduck) | 15 | — | Wireless keystroke injection attack platform # WifiDuck |
| 353 | [mrmonstertown226/wifi-password-stealing](https://github.com/mrmonstertown226/wifi-password-stealing) | 15 | — | A network security auditing tool. It allows for the recovery of saved Wi-Fi credentials and helps… |
| 354 | [aeracoop/dronehole](https://github.com/aeracoop/dronehole) | 14 | Shell | Example of Drone deauthentication attack to Parrot and DJI drones in wifi mode |
| 355 | [danngalann/wifispammer](https://github.com/danngalann/wifispammer) | 14 | Python | A python script to spam a bunch of silly wifi networks |
| 356 | [DenoBY/HandshakeCrack](https://github.com/DenoBY/HandshakeCrack) | 14 | HTML | Module HandshakeCrack v1.1 for WiFi Pineapple |
| 357 | [G4MEOVER18/FlipperJammer](https://github.com/G4MEOVER18/FlipperJammer) | 14 | C | Flipper Zero Jammer Suite: SubGHz/NRF24/BLE/WiFi/IR/RFID/NFC/USB — Momentum API 87.1 |
| 358 | [JNDreviews/est-Smartphones-under-Rs.15000-](https://github.com/JNDreviews/est-Smartphones-under-Rs.15000-) | 14 | — | WHICH ARE THE BEST SMARTPHONES UNDER 15000 . Best Smartphones under Rs.15000 models 2021  Step by… |
| 359 | [minimike86/aircrack-scripts](https://github.com/minimike86/aircrack-scripts) | 14 | Shell | Aircrack-ng Suite Scripts to Easily Demonstrate Wifi Attacks |
| 360 | [Samurai-X-13/wifi-deauther-gui](https://github.com/Samurai-X-13/wifi-deauther-gui) | 14 | Python | This is a gui interface for airmon-ng  |
| 361 | [TeamBlackBerry/WIFI-JAMER](https://github.com/TeamBlackBerry/WIFI-JAMER) | 14 | Python | It,s A Wifi Jamer Tool For Jam Any Connect Wifi Network  |
| 362 | [yaxter/DoSWifi](https://github.com/yaxter/DoSWifi) | 14 | Shell | DoS attack, Ataque DoS a redes Wifi, herramienta capaz de Expulsar a todos los usuarios de una re… |
| 363 | [ztzhang/GoProWifiCommand](https://github.com/ztzhang/GoProWifiCommand) | 14 | — | Gopro wifi command hack---a sniff result of Gopro App . The Json file can be used as a Gopro cont… |
| 364 | [AnandKatariya/WiFi-Jammer](https://github.com/AnandKatariya/WiFi-Jammer) | 13 | — | In this repositories we will learn , How to make WiFi Jammer and how to block the specific WiFi. … |
| 365 | [AuroraError/AuroraDeauth](https://github.com/AuroraError/AuroraDeauth) | 13 | Shell | Deauth and Beacon Spammer Script with Multiple functions. |
| 366 | [Derek1ization/Hack-pack-ON-STRIOD-2020](https://github.com/Derek1ization/Hack-pack-ON-STRIOD-2020) | 13 | — | Tools that i have gatherd and study to see how thay work and learned why theses tools execute the… |
| 367 | [EMLGaming/handshakestealer](https://github.com/EMLGaming/handshakestealer) | 13 | Shell | This is just a basic script that steals handshakes and cleans them this can then be used to crack… |
| 368 | [fulvius31/WpsConnectionLibrary](https://github.com/fulvius31/WpsConnectionLibrary) | 13 | C | An Android library for WiFi WPS (WiFi Protected Setup) security testing. Provides a clean, asynch… |
| 369 | [ginanjaradit354/wifi-hacker](https://github.com/ginanjaradit354/wifi-hacker) | 13 | — | #!/bin/bash#############################################################################   CREDIT… |
| 370 | [indradhar/social-engineering-attack-wifi](https://github.com/indradhar/social-engineering-attack-wifi) | 13 | HTML | Social Engineering Attack Using Phishing in a Local Area Wi-Fi by Creating an Access Point and DN… |
| 371 | [jhannah01/WifiSniffer](https://github.com/jhannah01/WifiSniffer) | 13 | Java | An android-based tool to record and analyze wireless data |
| 372 | [koushikos/Kali-Linux-WiFi-Pentesting-Handbook](https://github.com/koushikos/Kali-Linux-WiFi-Pentesting-Handbook) | 13 | — | Wireless security penetration testing guide built for cybersecurity learning using Kali Linux. In… |
| 373 | [lukius/wifi-deauth](https://github.com/lukius/wifi-deauth) | 13 | Python | WiFi deauthentication attack using Scapy |
| 374 | [nerodtm/BetterBackdoor---A-Backdoor-With-A-Multitude-Of-Features](https://github.com/nerodtm/BetterBackdoor---A-Backdoor-With-A-Multitude-Of-Features) | 13 | — | A backdoor is a tool used to gain remote access to a machine.  Typically, backdoor utilities such… |
| 375 | [quackduck/wif](https://github.com/quackduck/wif) | 13 | C | wifi packet sniffer |
| 376 | [TechnicalUserX/proximoth](https://github.com/TechnicalUserX/proximoth) | 13 | C | Control Frame Attack Vulnerability Detection Tool (GitLab Mirror) |
| 377 | [TheLogeek/WiFi-Hacker](https://github.com/TheLogeek/WiFi-Hacker) | 13 | Python | WiFi-Hacker is a dictionary attack program that tests 2300+ commonly used passwords on a WiFi net… |
| 378 | [waheeb71/WiFiSlayer](https://github.com/waheeb71/WiFiSlayer) | 13 | Python | Advanced WiFi Penetration Testing Framework. WiFiSlayer automates wireless security auditing, WPA… |
| 379 | [Whomrx666/Xdeauth-owner](https://github.com/Whomrx666/Xdeauth-owner) | 13 | Python | Xdeauth-owner is a tool that can place us as the owner of the WiFi by being able to determine who… |
| 380 | [jaybosamiya/wifi-sniffer](https://github.com/jaybosamiya/wifi-sniffer) | 12 | C++ | Find MAC addresses of devices leaving any sort of trace in the air around you |
| 381 | [k1lgor/wifi-dos](https://github.com/k1lgor/wifi-dos) | 12 | Shell | A simple wifi dos attack |
| 382 | [MariyaSha/PacketSniffer](https://github.com/MariyaSha/PacketSniffer) | 12 | Python | Demonstrating with Flask and Scapy What Hackers See on Public WiFi |
| 383 | [N1P0STK4/Wificuak](https://github.com/N1P0STK4/Wificuak) | 12 | Shell | Tool for Wifi Network Attacks (WPA/WPA2 - PSK- Hijacking -  Beacon Flood - DoS Attack - Scanner -… |
| 384 | [purva-patel/WIFI-DOS-Scripts](https://github.com/purva-patel/WIFI-DOS-Scripts) | 12 | Python | This repository contains Python scripts for performing Denial of Service (DoS) attacks on WiFi ne… |
| 385 | [xiv3r/openwrt-deauther](https://github.com/xiv3r/openwrt-deauther) | 12 | Shell | openwrt wifi deauther jammer based on aireplay-ng \| capture 4 way handshake with openwrt router. |
| 386 | [1arlz/fiberRock](https://github.com/1arlz/fiberRock) | 11 | Python | Word lists and dictionaries for burte force attacks |
| 387 | [82goober82/fluxionwpa2](https://github.com/82goober82/fluxionwpa2) | 11 | — | Fluxion is the future of MITM WPA attacks  Fluxion is a security auditing and social-engineering … |
| 388 | [ALBINPRAVEEN/Wifi-jammer](https://github.com/ALBINPRAVEEN/Wifi-jammer) | 11 | Objective-C |  |
| 389 | [CAPSTV/Deauther_0.96-inch-OLED_RGB-LED](https://github.com/CAPSTV/Deauther_0.96-inch-OLED_RGB-LED) | 11 | C | WiFi Deauther with 0.96 inch OLED and RGB LED Integration |
| 390 | [cr4sh-me2/aura](https://github.com/cr4sh-me2/aura) | 11 | Shell | An easy user interface for pentesting tools |
| 391 | [egefeyzioglu/Long-Range-RFID-Sniffer](https://github.com/egefeyzioglu/Long-Range-RFID-Sniffer) | 11 | C++ | Reads RFID cards from a long/medium distance, and displays the card IDs on a web page on a WiFi n… |
| 392 | [ESPboy-edu/ESPboy_WiFiSniffer](https://github.com/ESPboy-edu/ESPboy_WiFiSniffer) | 11 | C++ | ESPboy WiFi sniffer. Sniff WiFi packets. |
| 393 | [Hamed-Gharghi/wifi-deauther](https://github.com/Hamed-Gharghi/wifi-deauther) | 11 | Python | A powerful WiFi deauthentication tool for educational purposes. Features include interactive netw… |
| 394 | [jseric/raspberry-jammer](https://github.com/jseric/raspberry-jammer) | 11 | Python | WiFi Attacking Application With User Interface |
| 395 | [l4f2s4/pyqt5-linux-wifi-jamming-tools](https://github.com/l4f2s4/pyqt5-linux-wifi-jamming-tools) | 11 | Python | Wifi-Jamming is a simple GUI tool, yet highly effective method of causing a DoS on a wireless imp… |
| 396 | [Mehliug-git/Wifi-Mass-DeAuth](https://github.com/Mehliug-git/Wifi-Mass-DeAuth) | 11 | Python | A little script for DeAuth everyone on all wifi arround you  & capture the password hash ! |
| 397 | [Mrb4by/WiFi-Scanner-in-Python-using-Scapy](https://github.com/Mrb4by/WiFi-Scanner-in-Python-using-Scapy) | 11 | Python | In this project, we will do a simple Wi-Fi scanner using Scapy library that sniffs and decode bea… |
| 398 | [Sheikh-Nightshader/Wifire](https://github.com/Sheikh-Nightshader/Wifire) | 11 | Python | Wifire: Automated Wi-Fi Scanner and Attacker. Wifire is a Python-based tool that enables Wi-Fi ne… |
| 399 | [wshen0123/mitm-rogue-WiFi-AP](https://github.com/wshen0123/mitm-rogue-WiFi-AP) | 11 | — | MITM Attack Example Code with Rogue Wi-Fi AP |
| 400 | [aradhyacp/Wifi-dos](https://github.com/aradhyacp/Wifi-dos) | 10 | Python | WiFi-DoS is a Python-based Wi-Fi deauthentication tool for authorized security testing. It automa… |
| 401 | [canack/kismetdeauth](https://github.com/canack/kismetdeauth) | 10 | Python | Kismet plugin for deauth AP |
| 402 | [DataSC3/WIFI-BRUTS](https://github.com/DataSC3/WIFI-BRUTS) | 10 | JavaScript | A powerful WiFi dictionary attack tool with an intuitive graphical interface, designed for penetr… |
| 403 | [deepalgorithm/RFJamming-FMRadio-SDR](https://github.com/deepalgorithm/RFJamming-FMRadio-SDR) | 10 | Python | Wifi Jamming and FM Radio with Software Defined Radio |
| 404 | [defeo/phishing-demo](https://github.com/defeo/phishing-demo) | 10 | HTML | Demonstration of wifi sniffing, dns poisoning, mitm and phishing attack |
| 405 | [ErickBuster/Wi-Fi-Attack](https://github.com/ErickBuster/Wi-Fi-Attack) | 10 | HTML | Una herramienta escrita en bash y python para la automatizacion de diversos ataques a redes Wifi … |
| 406 | [jrdpteam/WiFi_Toolkit](https://github.com/jrdpteam/WiFi_Toolkit) | 10 | Python | WiFi_Toolkit my tiny wifi pentesting multitool. this code is really old and it should not be used… |
| 407 | [kaotickj/WiFi-Security-Testing-Guide---Practical-Red-Team-Pentest-Manual](https://github.com/kaotickj/WiFi-Security-Testing-Guide---Practical-Red-Team-Pentest-Manual) | 10 | Python | This guide provides a practical, command level methodology for red team operators and penetration… |
| 408 | [lutfizp/AirBully](https://github.com/lutfizp/AirBully) | 10 | Shell | Semi-automated toolkit designed to perform targeted WPA3 Transition Mode downgrade attacks |
| 409 | [mavinsi/wifi-deauther](https://github.com/mavinsi/wifi-deauther) | 10 | Shell | ☠️ Bash script to facilitate the use of the aireplay-ng deauth |
| 410 | [MohitPimoli/Net-Ninja](https://github.com/MohitPimoli/Net-Ninja) | 10 | Python | Wi-Fi Jammer Script: A Python tool that performs deauthentication attacks on Wi-Fi networks by di… |
| 411 | [MrEchoFi/EchoFi_8266Deauther](https://github.com/MrEchoFi/EchoFi_8266Deauther) | 10 | — | By this device you can apply Deauthentication attack in wifi and kick out from the network easily. |
| 412 | [PrettyBoyCosmo/DuckyLan](https://github.com/PrettyBoyCosmo/DuckyLan) | 10 | PowerShell | A USB RubberDucky payload that steals Wi-Fi credentials and sends them to the attacker via STMP |
| 413 | [RemaxBoxTeam/RemaxDos](https://github.com/RemaxBoxTeam/RemaxDos) | 10 | C | This is Script tools from all attack Denial of service by C programming |
| 414 | [bad-antics/nullsec-payload-autopwn](https://github.com/bad-antics/nullsec-payload-autopwn) | 9 | Shell | NullSec WiFi Pineapple Pager payload |
| 415 | [benlarsendk/PS03](https://github.com/benlarsendk/PS03) | 9 | C# | Password Sniffer- gets saved WiFi- and Chrome/Firefox passwords, encrypts and transmit to a server. |
| 416 | [Cem-Bas/jammer-detector-flipper-zero](https://github.com/Cem-Bas/jammer-detector-flipper-zero) | 9 | Dart | Dual-band RF jammer detector for Flipper Zero + Flutter companion app — Sub-GHz (315-915 MHz) + W… |
| 417 | [enty8080/denver-camera-backdoor](https://github.com/enty8080/denver-camera-backdoor) | 9 | Python | Backdoor has been discovered by me in Denver Smart Wifi Camera SHC-150. Backdoor allows attacker … |
| 418 | [Foxanthrope/PineAlert](https://github.com/Foxanthrope/PineAlert) | 9 | JavaScript | Firefox extension delivering real-time browser notifications for WiFi Pineapple Mark 7, powered b… |
| 419 | [Fz3r0/Fz3r0_-_Wi-Fi_CTS-Frame-Attack-802.11-Frame](https://github.com/Fz3r0/Fz3r0_-_Wi-Fi_CTS-Frame-Attack-802.11-Frame) | 9 | — | 802.11 WiFi CTS Frame Attack \| PoC \| Ejemplo \| Instrucciones |
| 420 | [hamzabellouch/nethunter](https://github.com/hamzabellouch/nethunter) | 9 | Shell | NetHunter is a Automated wireless security auditing framework supporting WPA/WPA2/WPA3, WPS, PMKI… |
| 421 | [LeucoByte/mcwfcrk](https://github.com/LeucoByte/mcwfcrk) | 9 | Shell | Automated Bash tool for WPA/WPA2/WPA3 handshake & PMKID capture and cracking (aircrack-ng, hcxdum… |
| 422 | [mrblinkybling/wifi2017](https://github.com/mrblinkybling/wifi2017) | 9 | C++ | Mr. Blinky Bling WiFi sniffing badge for 2017 |
| 423 | [ponmudimr/auto-internet-login](https://github.com/ponmudimr/auto-internet-login) | 9 | Shell | Automate login for BIT's WiFi captive portal — one command to deauth your old session and connect… |
| 424 | [scriptedp0ison/Kali-Linux-Wifi-Short-Cut-Scripts](https://github.com/scriptedp0ison/Kali-Linux-Wifi-Short-Cut-Scripts) | 9 | Python | These scripts consist of an easier, shorter way to do things via wireless attacks using Aircrack-… |
| 425 | [starminPIX/sh-kitty](https://github.com/starminPIX/sh-kitty) | 9 | — | sh-kitty is a black hat/grey hat tool it has many options that are great for many things you have… |
| 426 | [Throupy/wifi-jammer](https://github.com/Throupy/wifi-jammer) | 9 | C# | A Wi-Fi Jammer (De-Auther) built to run on a Raspberry Pi 3B+ with Avalonia UI framework, |
| 427 | [TimJ86AU/kali-linux-rpi-mdk3-airmon-ng-wifi-jamming](https://github.com/TimJ86AU/kali-linux-rpi-mdk3-airmon-ng-wifi-jamming) | 9 | — | Wireless - Wifi Jamming - Raspberry PI (RPI) |
| 428 | [tusharkeshav/wifi-jam](https://github.com/tusharkeshav/wifi-jam) | 9 | Python | WiFi Jam. Disconnect anyone from any wifi or Access point. Send crafted packet for disconnecting … |
| 429 | [ty1er4499/reaver-wps](https://github.com/ty1er4499/reaver-wps) | 9 | C | Brute force attack against Wifi Protected Setup |
| 430 | [0xbitx/DEDSEC_WIREMON](https://github.com/0xbitx/DEDSEC_WIREMON) | 8 | PHP | WIREMON is a Linux-based wifi attack framework tool. |
| 431 | [archkhertdev/wifiattack](https://github.com/archkhertdev/wifiattack) | 8 | Shell | A powerful WiFi Distruption tool designed to kick devices that's connected to a network and displ… |
| 432 | [Bilal-Belli/DictionaryWifiAttackTool](https://github.com/Bilal-Belli/DictionaryWifiAttackTool) | 8 | Python | This repository presents a simple Python program for testing a large number of passwords (diction… |
| 433 | [bishwabikash/wifi-autopwn](https://github.com/bishwabikash/wifi-autopwn) | 8 | Shell | WiFi Auto-PWN v1.0 - Advanced Multi-Generation WiFi Penetration Testing Framework \| Complete cov… |
| 434 | [blwhit/WifiReaper](https://github.com/blwhit/WifiReaper) | 8 | Shell | Automate large-scale Wi-Fi deauthentication attacks. Automatically discover vulnerable wireless n… |
| 435 | [Chibald/Esp-WifiSniffer-For-Openhab](https://github.com/Chibald/Esp-WifiSniffer-For-Openhab) | 8 | C++ |  |
| 436 | [Demontager/HoneyWIFI](https://github.com/Demontager/HoneyWIFI) | 8 | Shell | Wi-Fi access point for pentest purposes |
| 437 | [errorfiathck/wifi-Brutefurce](https://github.com/errorfiathck/wifi-Brutefurce) | 8 | Python | in this python code we attack on wifi`s network useing brutefurceing  |
| 438 | [hXR16F/Wi-Fi-Cracker](https://github.com/hXR16F/Wi-Fi-Cracker) | 8 | Batchfile | Slow but working Wi-Fi password recovery tool based on wordlist attack. |
| 439 | [louisvarley/openwrt-probe-request-sniffer-luci](https://github.com/louisvarley/openwrt-probe-request-sniffer-luci) | 8 | Lua | A Wifi Probe Request Python Script with a Luci page to read the contents |
| 440 | [musagithub1/wifiHacking](https://github.com/musagithub1/wifiHacking) | 8 | Python | Ultimate Python-based WiFi hacking and security auditing framework. Automates PMKID, WPA offline … |
| 441 | [OhDamnn/wifi_hack_gui](https://github.com/OhDamnn/wifi_hack_gui) | 8 | Python | Advanced GUI for WiFi Penetration Testing Integrates: wifipumpkin3, airgeddon, KRACK attacks, Cap… |
| 442 | [ripper121/odroidgowifisniffer](https://github.com/ripper121/odroidgowifisniffer) | 8 | HTML | Odroid Go Wifi Sniffer PCAP |
| 443 | [Ro9ueAdmin/wifi-cracking-dictionary-attack-](https://github.com/Ro9ueAdmin/wifi-cracking-dictionary-attack-) | 8 | — | 1.airmon-ng (to know status of N/W) 2.airmon-ng start wlan0 (to enable monitor mode) 3.airodump-n… |
| 444 | [rodolfomarianocy/Tricks-Wi-Fi-Pentest](https://github.com/rodolfomarianocy/Tricks-Wi-Fi-Pentest) | 8 | — | Wi-Fi Penetration Testing |
| 445 | [Slax38/WiFiDeauther](https://github.com/Slax38/WiFiDeauther) | 8 | Python | DDoS attack on wireless networks |
| 446 | [tanc7/Wifi-Attack-Auto-Loader-MANA-](https://github.com/tanc7/Wifi-Attack-Auto-Loader-MANA-) | 8 | Python | Easily walks you through the Mana Evil AP Attack (While eliminating common mistakes). All promise… |
| 447 | [TotallyNotAHaxxer/Red-Rabbit-1.0](https://github.com/TotallyNotAHaxxer/Red-Rabbit-1.0) | 8 | Ruby | Red Rabbit is a framework for Wifi attacks, Fake AP's, and web scanning <still adding some> |
| 448 | [TuHiN22/WiFiT](https://github.com/TuHiN22/WiFiT) | 8 | Python | Professional WPS Testing Toolkit for Rooted Android Devices with Termux - Advanced WiFi penetrati… |
| 449 | [xiv3r/dhcp-starvation](https://github.com/xiv3r/dhcp-starvation) | 8 | C++ | Powerful wifi dhcp starvation attack using termux \| no root |
| 450 | [XrangerCY19/Simple-DOS-Wifi-jammer-aircrack-ng-Kali-linux-NoobEdition](https://github.com/XrangerCY19/Simple-DOS-Wifi-jammer-aircrack-ng-Kali-linux-NoobEdition) | 8 | Shell | Easy to use on-the-go wifi jammer. |
| 451 | [yeahhub/wifidos](https://github.com/yeahhub/wifidos) | 8 | Shell | Wireless Dos Attack with wifidos Bash Script |
| 452 | [accoleon/marauders-map](https://github.com/accoleon/marauders-map) | 7 | JavaScript | WiFi positioning through packet sniffing |
| 453 | [Anonymous40443/SCAN-X](https://github.com/Anonymous40443/SCAN-X) | 7 | Python | ⚔️ SCAN-X v3.0 🩸 The Ultimate Blood-Tiger Recon Engine. Automate 15+ Nmap scans, bypass firewalls… |
| 454 | [Ares-21/AeroSpy](https://github.com/Ares-21/AeroSpy) | 7 | Python | A simple WiFi scanning GUI for scanning the available wireless networks  |
| 455 | [bad-antics/nullsec-pineapple-ops](https://github.com/bad-antics/nullsec-pineapple-ops) | 7 | JavaScript | 🍍 Command & Control Dashboard for WiFi Pineapple Pager & Mark VII — Web-based ops center with rec… |
| 456 | [badcofn/WifiProbeSniffer](https://github.com/badcofn/WifiProbeSniffer) | 7 | Python | Wifi probe request sniffer for logging wifi probes near you into a db. |
| 457 | [emre-h/WIFI-Dictionary-Attack-Tool](https://github.com/emre-h/WIFI-Dictionary-Attack-Tool) | 7 | Java | WIFI Dictionary Attack Tool for Android Operating System. |
| 458 | [faisalfs10x/WiFi-Pentest-Cheat-Sheet](https://github.com/faisalfs10x/WiFi-Pentest-Cheat-Sheet) | 7 | — |  |
| 459 | [IMARv2/iphisher](https://github.com/IMARv2/iphisher) | 7 | Python | Advanced WiFi credential harvester for penetration testers — evil twin, OS-native portals, WPS Pi… |
| 460 | [JizzyRivers/jam](https://github.com/JizzyRivers/jam) | 7 | Shell | Give your de-Amazonized Echo Dot 2 (Biscuit) some Jam — on-device WAN blocking, wake word switchi… |
| 461 | [less-prog/wifi-pentest-handshake](https://github.com/less-prog/wifi-pentest-handshake) | 7 | Shell | Audit de sécurité Wi-Fi : scan WPS, attaque Pixie Dust, capture de handshake WPA2 avec Flipper Ze… |
| 462 | [paolini99/Brute_Force-Dictionary_Attack_on_WiFi](https://github.com/paolini99/Brute_Force-Dictionary_Attack_on_WiFi) | 7 | — | 🔐 WPA2 WiFi Dictionary Attack Capture handshakes and crack passwords using a wordlist. For educat… |
| 463 | [phalloc/phalloc-sniffer](https://github.com/phalloc/phalloc-sniffer) | 7 | C++ | MAC Address sniffer. Captures packets on the WiFi network and outputs the MAC address and RSSI to… |
| 464 | [rff-glitch/wifi-jamming](https://github.com/rff-glitch/wifi-jamming) | 7 | Shell | 🚨 WiFi DEAUTH BLASTER 🔥                   Automated multi-target deauthentication attack system u… |
| 465 | [ricardojoserf/pywisam](https://github.com/ricardojoserf/pywisam) | 7 | Python | A Wifi pentesting framework written in Python |
| 466 | [s0m3-1/wifiBuddy](https://github.com/s0m3-1/wifiBuddy) | 7 | Python | A Buddy u ain't wanna be missing |
| 467 | [Sh7yk/Warwalking](https://github.com/Sh7yk/Warwalking) | 7 | Shell | Simple bash scripts on the Wifite base to automatically check all access points on the go |
| 468 | [Sota-0/VeilCast-Evil-Twin-Framework](https://github.com/Sota-0/VeilCast-Evil-Twin-Framework) | 7 | Python | VeilCast is a semi-automated Evil Twin attack Hacking framework written in Python. It simplifies … |
| 469 | [squidward404/wifi-crasher](https://github.com/squidward404/wifi-crasher) | 7 | Python | just a glorified version of aircrack-ng deauth script. |
| 470 | [TECH7Fox/deauth-detector-hass-addons](https://github.com/TECH7Fox/deauth-detector-hass-addons) | 7 | Python | Detects wifi deauth attacks |
| 471 | [touhidshaikh/Wireless-Pentest-Cheatsheet](https://github.com/touhidshaikh/Wireless-Pentest-Cheatsheet) | 7 | — | The Wireless Pentest cheat sheet was created to provide concise collection of high value informat… |
| 472 | [Tweeks-va/Kali_RPi_RIAB](https://github.com/Tweeks-va/Kali_RPi_RIAB) | 7 | Shell | This is a HOWTO and scripts for turning a RaspberryPi 2/3/4 into a Cyber Range In A Box (RIAB).. … |
| 473 | [vnsh02/Air-Kick](https://github.com/vnsh02/Air-Kick) | 7 | Python | Simple script for Wifi Deauth attack |
| 474 | [0xF35/Disrupt](https://github.com/0xF35/Disrupt) | 6 | Python | A Python-based WiFi deauther. |
| 475 | [5h4d0wn1k/airguard](https://github.com/5h4d0wn1k/airguard) | 6 | Python | Wireless defense & monitoring suite - WIDS sensor, deauth/evil-twin/rogue-AP detection, beacon an… |
| 476 | [5h4d0wn1k/w1-deauth-eng](https://github.com/5h4d0wn1k/w1-deauth-eng) | 6 | Python | 802.11 deauthentication frame parser, spoofed-MAC heuristics, and PMF resilience analysis for aut… |
| 477 | [5h4d0wn1k/w2-evil-twin](https://github.com/5h4d0wn1k/w2-evil-twin) | 6 | Python | Evil-twin and rogue-AP detection lab — 802.11 beacon fingerprinting to identify cloned access poi… |
| 478 | [5h4d0wn1k/w6-beacon-analysis](https://github.com/5h4d0wn1k/w6-beacon-analysis) | 6 | Python | 802.11 beacon analyzer - channel/rate/IE parsing and anomaly fingerprinting. |
| 479 | [5h4d0wn1k/w7-wids-sensor](https://github.com/5h4d0wn1k/w7-wids-sensor) | 6 | Python | WIDS sensor - rogue AP, deauth and beacon-flood detection with alerting. |
| 480 | [adialamsyahardi/Autologin-FreeBiznet](https://github.com/adialamsyahardi/Autologin-FreeBiznet) | 6 | PHP | AutoLogin @FreeBiznetHotspot, GAPERLU LAGI LOGIN MANUAL TIAP 2 JAM ! |
| 481 | [adithya9090/Termux-Deauther](https://github.com/adithya9090/Termux-Deauther) | 6 | — | Use Your Android Phone To Deauth WiFi Networks With Termux |
| 482 | [Anak0nd4/WifiExfiltrateDiscord](https://github.com/Anak0nd4/WifiExfiltrateDiscord) | 6 | PowerShell | A simple powershell script to exfiltrate wifi passwords using discord.  |
| 483 | [bad-antics/nullsec-wifi](https://github.com/bad-antics/nullsec-wifi) | 6 | Kotlin | 📶 NullSec WiFi - Advanced Wireless Security Analyzer \| Channel analysis, deauth detection, secur… |
| 484 | [bad-antics/wifipineapplepager](https://github.com/bad-antics/wifipineapplepager) | 6 | — | 🍍 WiFi Pineapple MK7 automation, pager payloads & mass deployment toolkit \| 100+ payloads \| Nul… |
| 485 | [Calmclireveal/wifi-deauth-attack](https://github.com/Calmclireveal/wifi-deauth-attack) | 6 | Rust | A wireless deauthentication tool that disconnects every connected device from a target Wi-Fi netw… |
| 486 | [Coderxrohan/Wifi-Deauth-Evil-Twin](https://github.com/Coderxrohan/Wifi-Deauth-Evil-Twin) | 6 | C++ | ⚠️ WiFi Deauth & Evil Twin Attack Toolkit is a penetration testing project focused on simulating … |
| 487 | [d33tah/wifibacon](https://github.com/d33tah/wifibacon) | 6 | Python | Sniffs on the WiFi network and generates a graph showing the communication between the devices, i… |
| 488 | [dcrisan/WiFi-802.11-Demo-Sniffer](https://github.com/dcrisan/WiFi-802.11-Demo-Sniffer) | 6 | Python | This 802.11 sniffer written in Python provides a useful tool to raise awareness at the amount of … |
| 489 | [DX4GREY/WiFi_Deauther](https://github.com/DX4GREY/WiFi_Deauther) | 6 | Python | The script is a tool for scanning and attacking wireless networks. It discovers active access poi… |
| 490 | [ericohm/Wifi-sniffer](https://github.com/ericohm/Wifi-sniffer) | 6 | Python | How to store Mac:address, timestamp and gps and signal strength |
| 491 | [Foxlith/strykeross-6.0.1-secure](https://github.com/Foxlith/strykeross-6.0.1-secure) | 6 | Smali | StrykerOSS 6.0.1 APK + fuentes — versión asegurada (F1: decode SSID seguro, filtro control-chars)… |
| 492 | [fuck-standardized-testing/rpi-wifi-jammer](https://github.com/fuck-standardized-testing/rpi-wifi-jammer) | 6 | — | Build your own wifi-jammer with raspberry pi! |
| 493 | [GuruprasadaShridharHegde/Wifi-Jammer-and-Detector](https://github.com/GuruprasadaShridharHegde/Wifi-Jammer-and-Detector) | 6 | — | A hacking mind can hack the hacker. |
| 494 | [Hmkz0x00/wireless-assessment-center](https://github.com/Hmkz0x00/wireless-assessment-center) | 6 | PHP | WiFi-Pineapple-style wireless security assessment platform — a native Frieren/OpenWrt module. Rec… |
| 495 | [jitujak55/WiFi-Pentesting-Tool](https://github.com/jitujak55/WiFi-Pentesting-Tool) | 6 | Python | comprehensive, modular WiFi security auditing framework designed for WEP and WPA2/WPA3 penetratio… |
| 496 | [lsw29475/WifiDestoryer](https://github.com/lsw29475/WifiDestoryer) | 6 | C | A small program running on the wifipineapple, simplifying from the aircrack-ng, by scanning aroun… |
| 497 | [MAAYTHM/deauth_wif_for_windows](https://github.com/MAAYTHM/deauth_wif_for_windows) | 6 | Python | A Python3 tool, which simply sends ∞ deauth packets to wifi becoz of which victim device cannot a… |
| 498 | [Matter0x00/AWESOME-Wifi-Pentest](https://github.com/Matter0x00/AWESOME-Wifi-Pentest) | 6 | — |  |
| 499 | [nd50095800/IISR-A-Secure-Router-for-IoT-Networks](https://github.com/nd50095800/IISR-A-Secure-Router-for-IoT-Networks) | 6 | — | With the increasing popularity of IoT devices, the vulnerabilities & security issues concerned wi… |
| 500 | [NextrixVFX/NRF24-Jammer](https://github.com/NextrixVFX/NRF24-Jammer) | 6 | C++ | NRF24L01-E01 Based Jammer that hits wifi and bluetooth consistantly |
| 501 | [no1se2/no1seWIFI---WiFi-Toolkit-for-Pentesters](https://github.com/no1se2/no1seWIFI---WiFi-Toolkit-for-Pentesters) | 6 | Python | Capture handshakes, conduct deauth attacks, and crack passwords with ease. |
| 502 | [oussamaelaji/DoS_WiFi_Jammer](https://github.com/oussamaelaji/DoS_WiFi_Jammer) | 6 | Python | WiFi DoS (Denial of Service) attack to send deauthentication frame to clients |
| 503 | [s-b-repo/rasberry-lie](https://github.com/s-b-repo/rasberry-lie) | 6 | Python | a tool that will flood deauth packets to all wifi until control + c is pressed |
| 504 | [sifirib/jammerDEAUTHway](https://github.com/sifirib/jammerDEAUTHway) | 6 | Python | I am not responsible for ill-usage |
| 505 | [ToaderMatei/ghostbox](https://github.com/ToaderMatei/ghostbox) | 6 | Python | Modular security research toolkit for Raspberry Pi Zero 2W — USB HID injection, WiFi scanner, Blu… |
| 506 | [Vitor-Oliveira84/WiFi-Pentesting-Guide](https://github.com/Vitor-Oliveira84/WiFi-Pentesting-Guide) | 6 | — | Comprehensive WiFi penetration testing guide - techniques, tools, and defenses |
| 507 | [WorkofAditya/Deauth-Simulator](https://github.com/WorkofAditya/Deauth-Simulator) | 6 | Shell | This script automates WiFi deauth attacks, enabling monitor mode, capturing handshakes, and safel… |
| 508 | [xFreed0m/Wifi_plug](https://github.com/xFreed0m/Wifi_plug) | 6 | Python | short python script to install wifi pentesting tools - made for kali |
| 509 | [5h4d0wn1k/w1-wifi-scanner](https://github.com/5h4d0wn1k/w1-wifi-scanner) | 5 | Python | Wi-Fi scanner - SSID/channel/security-mode discovery and visualization. |
| 510 | [5h4d0wn1k/w10-wpa3-survey](https://github.com/5h4d0wn1k/w10-wpa3-survey) | 5 | Python | WPA3/WPA2 survey tool - security-mode census and transition-vulnerability checking. |
| 511 | [5h4d0wn1k/w2-deauth-detect](https://github.com/5h4d0wn1k/w2-deauth-detect) | 5 | Python | Deauth attack detector - monitor-mode heuristics that flag deauth floods and frame anomalies. |
| 512 | [5h4d0wn1k/w3-probe-audit](https://github.com/5h4d0wn1k/w3-probe-audit) | 5 | Python | Wi-Fi probe-request auditor - passive client-probe collection and SSID-leak analysis. |
| 513 | [5h4d0wn1k/w4-crack-pipeline](https://github.com/5h4d0wn1k/w4-crack-pipeline) | 5 | Python | WPA/WPA2/PMKID password audit pipeline — handshake/PMKID detection, hcxpcapngtool conversion, has… |
| 514 | [5h4d0wn1k/w5-nrf-observer](https://github.com/5h4d0wn1k/w5-nrf-observer) | 5 | Python | nRF observer - Nordic 2.4 GHz sniffing and packet-stream analysis for BLE lab work. |
| 515 | [5h4d0wn1k/w6-beacon-flood](https://github.com/5h4d0wn1k/w6-beacon-flood) | 5 | Python | Beacon flood generator - stress-tests client association and wireless IDS systems. |
| 516 | [5h4d0wn1k/w7-deauth-capture](https://github.com/5h4d0wn1k/w7-deauth-capture) | 5 | Python | Deauth capture utility - hunts handshakes, captures frames and logs offenders. |
| 517 | [5h4d0wn1k/w8-covert-beacon](https://github.com/5h4d0wn1k/w8-covert-beacon) | 5 | Python | 802.11 covert-channel toolkit - vendor-IE payload encoding in beacon/probe-response frames plus S… |
| 518 | [5h4d0wn1k/w8-evil-portal](https://github.com/5h4d0wn1k/w8-evil-portal) | 5 | Python | Evil portal / captive-portal builder - phishing landing pages for wireless security labs. |
| 519 | [5h4d0wn1k/w9-resilient-tele](https://github.com/5h4d0wn1k/w9-resilient-tele) | 5 | Python | Resilient telemetry system - wireless data-link redundancy and failover experiments. |
| 520 | [99stealth/wifi-evil-twin-detection-with-knn](https://github.com/99stealth/wifi-evil-twin-detection-with-knn) | 5 | Jupyter Notebook |  |
| 521 | [abhi-abhi86/spiffy](https://github.com/abhi-abhi86/spiffy) | 5 | Python | Advanced cybersecurity framework combining offensive (WiFi radar, auto-exploit, DNS enum, passwor… |
| 522 | [AplAddict/Arduino-Pentesting-Tool](https://github.com/AplAddict/Arduino-Pentesting-Tool) | 5 | PHP | Arduino MKR 1000 Pentesting Tool |
| 523 | [aryanvish2006/MiniJammer](https://github.com/aryanvish2006/MiniJammer) | 5 | — | a small device which lets you jam anyones wifi |
| 524 | [axosecurity/wanjamer](https://github.com/axosecurity/wanjamer) | 5 | Python | its a wifi jammer.It is made of python script.its just sent dautantication pacakets to jamm the n… |
| 525 | [BabakStars/Wifi_scanner_jammer](https://github.com/BabakStars/Wifi_scanner_jammer) | 5 | — |  |
| 526 | [dawoodkhatri1/Wifi-Jammer-using-arduino-uno](https://github.com/dawoodkhatri1/Wifi-Jammer-using-arduino-uno) | 5 | C | A C-based simulation of WiFi jamming for educational use. It mimics network scanning, displays fa… |
| 527 | [dherl0623/wifi-deauth](https://github.com/dherl0623/wifi-deauth) | 5 | Shell | Automated wifi deauthenticator of clients using MDK3. |
| 528 | [Dhirentek/network_hack](https://github.com/Dhirentek/network_hack) | 5 | Shell | This is my first basic bash script that I am uploading on github, as this was created 1 year ago … |
| 529 | [feisuzhu/wifikiller](https://github.com/feisuzhu/wifikiller) | 5 | C | A tool for tearing down and password sniffing PPPoE connections on open WiFi connections. For Chi… |
| 530 | [GrantPierce94/FlipperZero-WiFi-Attacks](https://github.com/GrantPierce94/FlipperZero-WiFi-Attacks) | 5 | — | Exploring Evil Twin and WiFi Sniffing attacks using Flipper Zero |
| 531 | [InnerFireZ/F-Security-APP](https://github.com/InnerFireZ/F-Security-APP) | 5 | Python | F-Security Nethunter rooted APP for automate pentesting on phone devices. |
| 532 | [jcrvnx/PH-WIFI-WORDLISTS](https://github.com/jcrvnx/PH-WIFI-WORDLISTS) | 5 | — | This is a comprehensive wordlist containing millions of entries from PLDT, Globe, and Converge. C… |
| 533 | [KareemAksh/android-gki-wifi-injection](https://github.com/KareemAksh/android-gki-wifi-injection) | 5 | C | Monitor mode & 802.11 packet injection on a stock Android 13 GKI kernel — no reflash. Cross-built… |
| 534 | [learnwithaq/Hacking-WiFi-using-Aircrack-ng](https://github.com/learnwithaq/Hacking-WiFi-using-Aircrack-ng) | 5 | — | Aircrack-ng is a powerful suite used to audit wireless networks. It captures WPA/WPA2 handshakes … |
| 535 | [luciapintor/WiFi-Sniffer](https://github.com/luciapintor/WiFi-Sniffer) | 5 | Python |  |
| 536 | [mohamadassaf96/WIFI_Jammer](https://github.com/mohamadassaf96/WIFI_Jammer) | 5 | Python | Python application that jams WIFIs by sending deauth packets |
| 537 | [mr-tbot/Shadow-Apple-Installer](https://github.com/mr-tbot/Shadow-Apple-Installer) | 5 | Shell | Interactive installer that turns a GL.iNet AR300M into a self-reporting WiFi Pineapple Cloner app… |
| 538 | [MuAbdullah-sudo/FreeWifi-guard](https://github.com/MuAbdullah-sudo/FreeWifi-guard) | 5 | CSS | 🛡️ Free-Wi-Fi Guard: A Python-based security tool that monitors public airwaves for unencrypted n… |
| 539 | [pingbiqi/Mobile-Phone-Signal-Jammer-5G-LTE-Shielding-System-Pro](https://github.com/pingbiqi/Mobile-Phone-Signal-Jammer-5G-LTE-Shielding-System-Pro) | 5 | Python | 手机屏蔽器 (5G/4G/WiFi/GNSS) 技术方案。针对标准化考场、涉密会议室及监狱安全设计。支持 TDD-LTE/FDD-LTE/5G NR 智能屏蔽。 |
| 540 | [PitHerm/esphome-externalcomponents](https://github.com/PitHerm/esphome-externalcomponents) | 5 | C++ | Solis, Ginlong, S5-GR3P (15k) with wifi S3 Stick sniffer for Homeassistant using ESPHome |
| 541 | [profitpioneer/iphone-protocol-sniffer](https://github.com/profitpioneer/iphone-protocol-sniffer) | 5 | Shell | Reverse-engineer iPhone↔device protocols (BLE/WiFi) without a hardware sniffer. Captures decrypte… |
| 542 | [qsz13/WiFi-Hacker](https://github.com/qsz13/WiFi-Hacker) | 5 | Python | A WiFi Jammer |
| 543 | [redoyrowshon-dotcom/WiFi-RainbowBuffer](https://github.com/redoyrowshon-dotcom/WiFi-RainbowBuffer) | 5 | Python | An automated WiFi penetration testing tool for cracking WPA2 networks via handshake capture and b… |
| 544 | [rixgit/wifisniff](https://github.com/rixgit/wifisniff) | 5 | C++ | Simple C++ Wireless Sniffer.  Wrote it in approximately 3 hours including debugging and testing.   |
| 545 | [slashtechno/wifi-deauth](https://github.com/slashtechno/wifi-deauth) | 5 | Python | A semi-automated python script that can deauth clients from access points. |
| 546 | [streanger/clients-scanner](https://github.com/streanger/clients-scanner) | 5 | Python | Local network clients scanner with deauth feature |
| 547 | [StrongWind1/WiFi_Cracking](https://github.com/StrongWind1/WiFi_Cracking) | 5 | Makefile | Complete technical reference for WPA/WPA2/WPA3 PSK security analysis |
| 548 | [suseong41/SuNiffing](https://github.com/suseong41/SuNiffing) | 5 | C++ | Galaxy S10 nexmon 기반 WiFi 스캐너 · 무선 보안 점검 도구 (Qt) |
| 549 | [Volkov997/pen-card](https://github.com/Volkov997/pen-card) | 5 | — | RF Pentesting tool, but small enough for your wallet. Features: Wifi & Bluetooth, NFC, IR, (Sub G… |
| 550 | [voltsparx/Py-WiFi-Deauther](https://github.com/voltsparx/Py-WiFi-Deauther) | 5 | Python | Py-WiFi-Deauther is an ethical WiFi security testing tool for educational and authorized penetrat… |
| 551 | [w1ld3r/Raspi_Hackbox](https://github.com/w1ld3r/Raspi_Hackbox) | 5 | CSS | Debian Trixie Raspberry Pi 4 image builder for IoT, OT, automotive & RF/SDR pentesting — i3 + zsh… |
| 552 | [whoelse091/WIFI-BLE-JAMMER](https://github.com/whoelse091/WIFI-BLE-JAMMER) | 5 | C++ | WIFI/BLE JAMMER |
| 553 | [ykosaraju/Wifi-Pentesting-Cheatsheet](https://github.com/ykosaraju/Wifi-Pentesting-Cheatsheet) | 5 | — |  |
| 554 | [yofriendfromschool1/GEEKEYES-Flipper-Zero-5G-dualband-Wifi](https://github.com/yofriendfromschool1/GEEKEYES-Flipper-Zero-5G-dualband-Wifi) | 5 | — | GEEKEYES Flipper Zero 5G/dual band Wifi Deauth. |
| 555 | [0x25/piSniff](https://github.com/0x25/piSniff) | 4 | — | sniff packet and access it with wifi (Raspberry) |
| 556 | [Adityaraj6/Wi-Dos](https://github.com/Adityaraj6/Wi-Dos) | 4 | Python | WiFi Deauth Attack |
| 557 | [ahmhabib01/WIFI_PHISHER](https://github.com/ahmhabib01/WIFI_PHISHER) | 4 | C++ | HACK WIFI USING WIFI_PHISHER.  Evil-Twin AP to capture passwords with password verification again… |
| 558 | [aishee/Autopwn-Wifi](https://github.com/aishee/Autopwn-Wifi) | 4 | Shell | Searching and auditing Wifi |
| 559 | [anbdummy/WiFi-Deauth](https://github.com/anbdummy/WiFi-Deauth) | 4 | Shell | 802.11 Deauth BASH Script - Everyone Except You! |
| 560 | [areuhack/Wifi-Deauther](https://github.com/areuhack/Wifi-Deauther) | 4 | Python | A Python-based ethical hacking tool for performing WiFi network deauthentication attacks. This to… |
| 561 | [ArhumUsman9/AirStrike](https://github.com/ArhumUsman9/AirStrike) | 4 | Python | AirStrike-CLI is a powerful, terminal-based WiFi vulnerability assessment tool designed for both … |
| 562 | [ary27x/WIFI_JAMMER](https://github.com/ary27x/WIFI_JAMMER) | 4 | Python | Infinitely disconnects clients one by one from a 802.11 wifi network |
| 563 | [asgardOP/WiFi-Manager](https://github.com/asgardOP/WiFi-Manager) | 4 | Python | Advanced Windows WiFi Management Tool built with Python — includes network scanning, ARP spoofing… |
| 564 | [azph0byte/netmode](https://github.com/azph0byte/netmode) | 4 | Shell | Netmode is a lighweight bash script that use the power of 'iw' which allows users to easily switc… |
| 565 | [cavoq/WiFi-Deauthenticator](https://github.com/cavoq/WiFi-Deauthenticator) | 4 | TypeScript | WiFi deauthentication tool. |
| 566 | [cyber6869/wifi-handshake-cracker](https://github.com/cyber6869/wifi-handshake-cracker) | 4 | Python | Professional WI-FI pentesting tool for analayzing and cracking WPA/WPA2 EAPOL (4-way Handshake) c… |
| 567 | [delvison/Netblock](https://github.com/delvison/Netblock) | 4 | Python | python script that has the ability to jam a single or multiple targets' wifi access. |
| 568 | [dmanierre/PI-Sniffer](https://github.com/dmanierre/PI-Sniffer) | 4 | Python | This project will support using a raspberry pi and meshtastic to sniff out wifi enabled devices a… |
| 569 | [Ethhacks-official/Wireless-Protect](https://github.com/Ethhacks-official/Wireless-Protect) | 4 | Python | An open source tool to detect deauth, Evil Twin, Clonned wifi, Arp Spoofing and Man in the Middle… |
| 570 | [frnAlt/FARHAN-Shot](https://github.com/frnAlt/FARHAN-Shot) | 4 | Python | **About Run WPS PIN attacks (Pixie Dust, online bruteforce, PIN prediction) without monitor mode … |
| 571 | [Glitchboi-sudo/RogueBridge](https://github.com/Glitchboi-sudo/RogueBridge) | 4 | Shell | Access Point WiFi para laboratorio/pentesting y configura NAT para dar salida a Internet a los cl… |
| 572 | [h2so0o4/CameraSniffer](https://github.com/h2so0o4/CameraSniffer) | 4 | Java | 基于WIFI的室内设备检测技术 |
| 573 | [iahunter/wifisniffer](https://github.com/iahunter/wifisniffer) | 4 | Shell | Wireshark Wifi Sniffing  - 802.11 plus radiotap header on Windows - Bridged Wireless NIC Adapter … |
| 574 | [iamEzmuth/DeAuthImposter](https://github.com/iamEzmuth/DeAuthImposter) | 4 | Python | Best tool to deauthenticate (disconnect) everyone in wifi network you are... |
| 575 | [jakubkowalski167/wifi-pentesting-tutorial](https://github.com/jakubkowalski167/wifi-pentesting-tutorial) | 4 | Python |  |
| 576 | [Jarukit-PM/Wifi-Authentication-Attack](https://github.com/Jarukit-PM/Wifi-Authentication-Attack) | 4 | Shell | A mini project for studying Wi-Fi security vulnerabilities by simulating authentication bypass te… |
| 577 | [jbenages/diswised](https://github.com/jbenages/diswised) | 4 | Shell | Audit WiFi clients with automated Evil Twin and Rogue AP attacks |
| 578 | [jimididit/wifi-pwn](https://github.com/jimididit/wifi-pwn) | 4 | Python | A script to perform a Wi-Fi deauthentication attack using a network interface controller (NIC) in… |
| 579 | [K3lgy/Flipper-Zero-Audit-Kit-](https://github.com/K3lgy/Flipper-Zero-Audit-Kit-) | 4 | Python | Kit d'audit de sécurité physique pour Flipper Zero. Parse automatiquement les exports de la carte… |
| 580 | [Kilouu/NowThisWifiIsMine](https://github.com/Kilouu/NowThisWifiIsMine) | 4 | Python | Outil d'attaque sur les réseaux Wifi avec 2 Mode : Attaque sur WPA, WEP, WPS ou en simulant un Ro… |
| 581 | [levouinse/deauther](https://github.com/levouinse/deauther) | 4 | Python | Sofinco Deauther v5.0 is a certified, cross-platform WiFi and Bluetooth penetration testing frame… |
| 582 | [MicrochipTech/atsamr34_lorawan_wifi_ap_scan](https://github.com/MicrochipTech/atsamr34_lorawan_wifi_ap_scan) | 4 | C | “IoT Made Easy!" - Adding Wi-Fi Sniffing to an existing LoRaWAN Application |
| 583 | [mkdirlove/DEADLY-DEAUTH](https://github.com/mkdirlove/DEADLY-DEAUTH) | 4 | Shell | A deadly WiFi deauthentication attack tool powered by MDK3. |
| 584 | [mmustaqim/RF_WiFi_jammer_detector](https://github.com/mmustaqim/RF_WiFi_jammer_detector) | 4 | Python |  |
| 585 | [pect0ral/kismet_parser](https://github.com/pect0ral/kismet_parser) | 4 | Python | Some Random Scripts to Parse Kismet output for useful info |
| 586 | [ph4ntonn/wifi_attacker](https://github.com/ph4ntonn/wifi_attacker) | 4 | Python |  |
| 587 | [pirrofra/wifiSniffer](https://github.com/pirrofra/wifiSniffer) | 4 | Python |  |
| 588 | [PranitThorat/WiFire](https://github.com/PranitThorat/WiFire) | 4 | Python | :  🔥 WiFire – A blazing-fast automated Wi-Fi attack tool! Scan networks, send deauths, capture WP… |
| 589 | [Quantika14/logika14](https://github.com/Quantika14/logika14) | 4 | Python | Sniffer de clientes wifi y buscador de vendors. |
| 590 | [ripmeep/wifi-deauther](https://github.com/ripmeep/wifi-deauther) | 4 | C++ | A WiFi/Wireless Network Deauthentication attack  |
| 591 | [rouze-d/wificrack](https://github.com/rouze-d/wificrack) | 4 | Shell | Simple Tool For Crack WiFi Handshake file <.ivs/.cap> |
| 592 | [sayak-brm/DeauthAttack](https://github.com/sayak-brm/DeauthAttack) | 4 | C | Disconnects user from Wifi network using ESP microcontrollers. |
| 593 | [SequoiaSan/wifi_pentest_utils](https://github.com/SequoiaSan/wifi_pentest_utils) | 4 | Shell | WiFi pentest utilities |
| 594 | [ShaolinGardener/wsniff](https://github.com/ShaolinGardener/wsniff) | 4 | — | A WiFi sniffer for the Raspberry Pi - can be controlled remotely 🌱 |
| 595 | [ShlomiRex/WiFi-Deauthernticator](https://github.com/ShlomiRex/WiFi-Deauthernticator) | 4 | Python |  |
| 596 | [Sk-Traitor/ZOREX-WiFi-Cracker](https://github.com/Sk-Traitor/ZOREX-WiFi-Cracker) | 4 | — | ZOREX: All-in-one wireless security testing tool. Scan networks, capture handshakes, crack passwo… |
| 597 | [SriteXcode/alienwifidetector](https://github.com/SriteXcode/alienwifidetector) | 4 | Python | AlienWiFiDetector is your digital watchdog 👁️ — silently sniffing out WiFi clones and SSID spoofe… |
| 598 | [Swimming-Monkey-Games/Shroomed](https://github.com/Swimming-Monkey-Games/Shroomed) | 4 | ShaderLab | Shroomed is a small game created for Wisniowa WIFI Game Jam. The entire project was completed in … |
| 599 | [udhaybhat00/airscope](https://github.com/udhaybhat00/airscope) | 4 | Python | Cross-platform USB Wi-Fi security auditor: WPA/WPA2 handshake + PMKID capture, WPS PixieDust, WPA… |
| 600 | [Van-Ziegelstein/airkick](https://github.com/Van-Ziegelstein/airkick) | 4 | C | C implementation of the classic WLAN deauthentication attack |
| 601 | [voltwu/WIFI-Deauthentication-Attack](https://github.com/voltwu/WIFI-Deauthentication-Attack) | 4 | Python | Forcing devices disconnect with wireless access point with wifi deauthentication attack |
| 602 | [zuzu59/wifi-sniffer](https://github.com/zuzu59/wifi-sniffer) | 4 | Lua |  |
| 603 | [8nt0n/Bl8ck0ut](https://github.com/8nt0n/Bl8ck0ut) | 3 | C++ | A 2.4Ghz Wifi Jammer pentesting tool |
| 604 | [ABHAYKUMARTRIPATHI/WiFi_Sniffer_Evil_Twin_Detector](https://github.com/ABHAYKUMARTRIPATHI/WiFi_Sniffer_Evil_Twin_Detector) | 3 | Python | A Python-based Wi-Fi Sniffer and Evil Twin Detector that passively monitors nearby wireless netwo… |
| 605 | [AlldDev/Wifi-Hacking-Example](https://github.com/AlldDev/Wifi-Hacking-Example) | 3 | — | Este projeto demonstra como testar a vulnerabilidade de redes wireless e simular operações de Red… |
| 606 | [asing012/Wifi_Jammer](https://github.com/asing012/Wifi_Jammer) | 3 | Python | This program uses aireplay to deauthenticate clients and jam the wifi. It makes it easier to run … |
| 607 | [ASP-29/WiFi-deauther-Mod-Bahasa-Indonesia](https://github.com/ASP-29/WiFi-deauther-Mod-Bahasa-Indonesia) | 3 | — |  |
| 608 | [astianmuchui/wifi-sniffer](https://github.com/astianmuchui/wifi-sniffer) | 3 | Python | Get all the Wifi networks ever connected to your device and their passwords at the time of connec… |
| 609 | [bad-antics/nullsec-mobile](https://github.com/bad-antics/nullsec-mobile) | 3 | Kotlin | 📱 NullSec Mobile - Security toolkit for Android & iOS \| Network scanner, WiFi analyzer, hash too… |
| 610 | [berodcdev/alive-netscan](https://github.com/berodcdev/alive-netscan) | 3 | Python | Descoberta de hosts na rede local (macOS + Linux): enumera quem e o quê está conectado — IP, MAC,… |
| 611 | [BlackTesseract/Wifi-Jammer](https://github.com/BlackTesseract/Wifi-Jammer) | 3 | Python |  |
| 612 | [darknecrocities/Python-Bruteforce-Attack-Script-for-Pentesting-Wifi](https://github.com/darknecrocities/Python-Bruteforce-Attack-Script-for-Pentesting-Wifi) | 3 | Python |  |
| 613 | [drubaby/pi-probe-sniffer](https://github.com/drubaby/pi-probe-sniffer) | 3 | Python | Raspberry Pi-hosted wifi probe monitor with mqtt and supabase connections. |
| 614 | [DX4GREY/deauther-s](https://github.com/DX4GREY/deauther-s) | 3 | Python | This is a tool for wifi deauther, please use it as wisely as possible, don't use it for illegal a… |
| 615 | [ethicalhackeragnidhra/Wifi-jammer-1](https://github.com/ethicalhackeragnidhra/Wifi-jammer-1) | 3 | Python |  |
| 616 | [F1DEL05/Wifi-Jammer_05](https://github.com/F1DEL05/Wifi-Jammer_05) | 3 | Python | Wifi handshake capturer (automation tool for airmon-ng) in Linux For pentesters |
| 617 | [Flyzone84/DeAuther](https://github.com/Flyzone84/DeAuther) | 3 | Shell | Deauther |
| 618 | [garrettmiller/WiFIDS](https://github.com/garrettmiller/WiFIDS) | 3 | Python | A Wireless-Physical IDS with Jam Detection - 18-731, Spring 2015, Carnegie Mellon University |
| 619 | [Gax-n2o/Wifi-Attack](https://github.com/Gax-n2o/Wifi-Attack) | 3 | Shell | WiFi MultiAttack - Herramienta de Auditoría WiFi  WiFi MultiAttack es un script integral en Bash … |
| 620 | [GEEKSUMAN/TL-WN722N](https://github.com/GEEKSUMAN/TL-WN722N) | 3 | — | TP-Link Nano USB WiFi Dongle 150Mbps High Gain Wireless Network Wi-Fi Adapter setting up for Kali… |
| 621 | [Gopalakrishnan20/WiJAMMER](https://github.com/Gopalakrishnan20/WiJAMMER) | 3 | Shell | WiJAMMER is a Hacking tool for deauthentication attack wifi with mdk4 or aireplay-ng. Easy and fa… |
| 622 | [goyalnish26/wifi_pentest_writeup](https://github.com/goyalnish26/wifi_pentest_writeup) | 3 | — | Documented authorized wireless security assessments on personally owned and permitted networks us… |
| 623 | [gregoirener/WIFIRE](https://github.com/gregoirener/WIFIRE) | 3 | — | WIFIRE is a Wi-Fi hacking tool for ethical penetration testing. It supports attacks like Evil Twi… |
| 624 | [hackerazmi201/wifi_killler](https://github.com/hackerazmi201/wifi_killler) | 3 | Shell | WiFiKiller is a Bash-based penetration testing tool for Kali Linux that automates Evil Twin attac… |
| 625 | [honestcorrupt/PROJECT-wifi-jammerhc4](https://github.com/honestcorrupt/PROJECT-wifi-jammerhc4) | 3 | Python | Wi-Fi jamming 📡 is a disruptive technique that intentionally interferes with wireless communicati… |
| 626 | [hubb22/Wi-Fi-Bluetooth-and-RTL-SDR-Jamming-Alarm-System](https://github.com/hubb22/Wi-Fi-Bluetooth-and-RTL-SDR-Jamming-Alarm-System) | 3 | — | WiFi Jammer Alarm. Detects attacks on Wi-Fi, Bluetooth and 433 MHz frequency devices. Wi-Fi Jamme… |
| 627 | [impclaw/wifi-sniff](https://github.com/impclaw/wifi-sniff) | 3 | C | Custom wifi sniffer with only the data I want as output. Does not sniff ethernet at all.  |
| 628 | [jshearer/wifi-sniffer](https://github.com/jshearer/wifi-sniffer) | 3 | Python | A set of python scripts to sniff specific wifi packets for use in positioning. |
| 629 | [jshingler/Pi-Wifi-Sniff](https://github.com/jshingler/Pi-Wifi-Sniff) | 3 | Java | Raspberry Pi Wifi Sniffer |
| 630 | [Kidd3n/wifiphisher](https://github.com/Kidd3n/wifiphisher) | 3 | PHP | Evil Twin |
| 631 | [laoheimao/mac-address-harvester](https://github.com/laoheimao/mac-address-harvester) | 3 | Python | Python script to use your wifi adapter to sniff wifi packet traffic for mac addresses and then gr… |
| 632 | [manishmarahatta/wifijammer-v1.0](https://github.com/manishmarahatta/wifijammer-v1.0) | 3 | Python | WIFI JAMMER |
| 633 | [MarcusProgram/Wifi-Jammer](https://github.com/MarcusProgram/Wifi-Jammer) | 3 | Python | python script to create random wifi  |
| 634 | [MarvinCS/DNS_Sniffer](https://github.com/MarvinCS/DNS_Sniffer) | 3 | Python | A dns sniffing tool. Only works in public wifis |
| 635 | [masssubash240/WIFI-Pentesting](https://github.com/masssubash240/WIFI-Pentesting) | 3 | HTML |  |
| 636 | [matb4r/wifi-sniffer](https://github.com/matb4r/wifi-sniffer) | 3 | C | IEEE 802.11/Wi-Fi sniffer |
| 637 | [mdtomo/wispy](https://github.com/mdtomo/wispy) | 3 | Python | Wifi probe request packet sniffer. |
| 638 | [meetsoni15/deadair](https://github.com/meetsoni15/deadair) | 3 | Go | Continuously jam all wifi clients/routers |
| 639 | [menashe12346/Evil_Twin](https://github.com/menashe12346/Evil_Twin) | 3 | Python | A tool for performing and detecting Evil Twin Wi-Fi attacks via fake AP creation and SSID duplica… |
| 640 | [mhaskar/wifi-jammer](https://github.com/mhaskar/wifi-jammer) | 3 | Python | Python automated wifi jammer |
| 641 | [MrDestroyer0/Wifi_Jamme3r](https://github.com/MrDestroyer0/Wifi_Jamme3r) | 3 | Shell | Wifi Jammer \| Best For Wifi Jamming |
| 642 | [Nikita465-dev/wifinet-creds-inspector](https://github.com/Nikita465-dev/wifinet-creds-inspector) | 3 | HTML | Wi-Fi Password Auditor: Secure Credential Recovery & Network Vulnerability Scanner for 2026 |
| 643 | [Ola-Kaznowska/PyWiFi-Pentest](https://github.com/Ola-Kaznowska/PyWiFi-Pentest) | 3 | Python | PyWiFi Pentest - Wi-Fi Security Analysis Tool. |
| 644 | [pingbiqi/GPS-shield-jammer-cellphone-signal-blocker](https://github.com/pingbiqi/GPS-shield-jammer-cellphone-signal-blocker) | 3 | JavaScript | 专业GPS屏蔽器与手机信号屏蔽器方案。支持5G/4G/WiFi信号拦截，适用于会议室、考场及无人机防护 |
| 645 | [pressure679/mySimpleSniffer](https://github.com/pressure679/mySimpleSniffer) | 3 | Java | Jnetpcap 1.3 wifi monitor/sniffer |
| 646 | [project-1871/hailhound-laptop](https://github.com/project-1871/hailhound-laptop) | 3 | Python | GTK4 Linux security toolkit — WiFi, BLE, SubGHz, RFID, jamming detection |
| 647 | [pt-mastermind/WifiMaster](https://github.com/pt-mastermind/WifiMaster) | 3 | Shell | Bash Automation tool for evil twin attack. |
| 648 | [romaneviil/Reviltwin](https://github.com/romaneviil/Reviltwin) | 3 | — | An opensource Python3 script for pentesters that facilitates evil twin attacks against wifi vulne… |
| 649 | [rootsid/Wifi-Jammer](https://github.com/rootsid/Wifi-Jammer) | 3 | Objective-C | Jam Wifi Networks  |
| 650 | [saherm0hamed/wifi-networks-scanner](https://github.com/saherm0hamed/wifi-networks-scanner) | 3 | Python | Python script designed to scan and display nearby Wi-Fi networks using a specified network interf… |
| 651 | [saikat-rog/Hack-WiFi](https://github.com/saikat-rog/Hack-WiFi) | 3 | — | How to collect and crack any handshake file of a access point. |
| 652 | [sakearzoo/WiFi-Jammer](https://github.com/sakearzoo/WiFi-Jammer) | 3 | Python | WiFI Jammer |
| 653 | [samatt/Sniffer](https://github.com/samatt/Sniffer) | 3 | C++ | barebones wifi sniffer for pi and mac |
| 654 | [sarandia/WiFi_Jammer](https://github.com/sarandia/WiFi_Jammer) | 3 | Python |  |
| 655 | [sobri3195/pegasus-sniffer](https://github.com/sobri3195/pegasus-sniffer) | 3 | Python | A comprehensive WiFi pentesting suite with multiple modules for network analysis and security tes… |
| 656 | [Somashekharh/Ethical-Hacking-GadgetHub](https://github.com/Somashekharh/Ethical-Hacking-GadgetHub) | 3 | — | A collection of hardware-based ethical hacking tools and guides for penetration testing, includin… |
| 657 | [The-Lxx-CLoUD/CLoUD-JAM](https://github.com/The-Lxx-CLoUD/CLoUD-JAM) | 3 | Python | wifi jammer❗(for pentest) |
| 658 | [Unknownx007/WI-JAM-X](https://github.com/Unknownx007/WI-JAM-X) | 3 | Python | WI-JAM-X is a wifi jamming tool used for jam the targated wifi device which will deauth all the c… |
| 659 | [usama7628674/Wifijammer](https://github.com/usama7628674/Wifijammer) | 3 | Python | Wifi Jammer in python utilizing scapy (2.4/5) Ghz with channel hop. |
| 660 | [XanderStrike/wifido](https://github.com/XanderStrike/wifido) | 3 | Python | Mobile Wifi Sniffer |
| 661 | [younisrahman/WifiJammerUI](https://github.com/younisrahman/WifiJammerUI) | 3 | Java | A Wifi jammer UI for Onu |
| 662 | [0x00-0x00/netcracker](https://github.com/0x00-0x00/netcracker) | 2 | Python | WiFi auditing tool to monitor, capture and crack WPA handshakes. |
| 663 | [1337leets/WiFi-Wardriving-Logger](https://github.com/1337leets/WiFi-Wardriving-Logger) | 2 | Python | Termux Wi-Fi and GPS logger with a Leaflet map, security classes and evil-twin hints |
| 664 | [84KaliPleXon3/wifi-pentesting-guide](https://github.com/84KaliPleXon3/wifi-pentesting-guide) | 2 | Python |  |
| 665 | [Aalok000/WIFI-Deauther](https://github.com/Aalok000/WIFI-Deauther) | 2 | Python |  |
| 666 | [actonetor/WifiTool](https://github.com/actonetor/WifiTool) | 2 | Python | Plusieurs Tool python pour du pentesting en wifi (wps cracking wpa cracking dos)  |
| 667 | [ahmkrby/karabay_wifi_pentest_device](https://github.com/ahmkrby/karabay_wifi_pentest_device) | 2 | — | Proje dosyaları yakında yüklenecektir. |
| 668 | [Ajay-Bommidi/WiFiSentry](https://github.com/Ajay-Bommidi/WiFiSentry) | 2 | Python | WiFiSentry is a lightweight Python-based wireless pentesting tool that helps ethical hackers dete… |
| 669 | [andrejliadov/Wifi-Sniffer](https://github.com/andrejliadov/Wifi-Sniffer) | 2 | Python | This programme uses socket in python to sniff for ethernet frames. The ethernet frames are then u… |
| 670 | [Ankitkushwaha90/wifi_jammer_hijacking](https://github.com/Ankitkushwaha90/wifi_jammer_hijacking) | 2 | — | This note provides a concise, practical overview of wireless communications, SDR, and ethical Wi-… |
| 671 | [annk15/Deauth](https://github.com/annk15/Deauth) | 2 | Java | A jammer written in java to perform deauthentication attacks on wifi networks. |
| 672 | [antonionard/Evil-Twin-Attack-on-Eduroam](https://github.com/antonionard/Evil-Twin-Attack-on-Eduroam) | 2 | Shell | Implementation of a MITM attack using Evil Twin, Captive Portal, and mitmproxy for HTTPS traffic … |
| 673 | [aoluggo/word-list-pentest](https://github.com/aoluggo/word-list-pentest) | 2 | — | Spanish word list (plain text) for use in pen-test. WIFI Try with wifite // Lista de palabras en … |
| 674 | [austinbenincasa/PiFiHacker](https://github.com/austinbenincasa/PiFiHacker) | 2 | Python | CLI for deploying a Evil Twin Wifi network |
| 675 | [AydanBedingham/deauth-wifi-jammer](https://github.com/AydanBedingham/deauth-wifi-jammer) | 2 | Shell | Script to automate the usage of the aircrack-ng to perform the Wi-Fi deauthentication denial-of-s… |
| 676 | [bad-antics/nullsec-hak5-toolkit](https://github.com/bad-antics/nullsec-hak5-toolkit) | 2 | Python | Universal Hak5 device management toolkit - CLI suite for WiFi Pineapple, Bash Bunny, Rubber Ducky… |
| 677 | [bagdigourav3/Air_wifi_craker](https://github.com/bagdigourav3/Air_wifi_craker) | 2 | Python | Air_wifi_craker is a Python 3 WiFi security testing tool. It scans nearby networks, lists them in… |
| 678 | [Chap010/Alpha-Auto-Fix](https://github.com/Chap010/Alpha-Auto-Fix) | 2 | Python | Wifi Pentesting |
| 679 | [CorePySystems/-WarCappin](https://github.com/CorePySystems/-WarCappin) | 2 | Perl | WiFi Hacking: Autonomously man in the middle deauthenticate WPA2 wireless networks and packet cap… |
| 680 | [CristianT71/HackRell](https://github.com/CristianT71/HackRell) | 2 | Shell | HackRell es una suite de hacking ético profesional, funcional y modular, escrita en Bash, diseñad… |
| 681 | [Cyb3rPh4nt0n/EvilTwin-PortalFramework](https://github.com/Cyb3rPh4nt0n/EvilTwin-PortalFramework) | 2 | Python | Script en Python para automatizar auditorías WiFi mediante la orquestación de hostapd, dnsmasq y … |
| 682 | [cyberoscyber427-netizen/cyberoscyber427wifi-Abdul-Mateen-Suite](https://github.com/cyberoscyber427-netizen/cyberoscyber427wifi-Abdul-Mateen-Suite) | 2 | Python | Official repository for cyberoscyber427wifi. A professional tool for wifi-hacking, pentesting, an… |
| 683 | [CyberRoninX1/AirStrike](https://github.com/CyberRoninX1/AirStrike) | 2 | — | wifi-security, penetration-testing, cybersecurity, wpa2-handshake, evil-twin, deauthentication-at… |
| 684 | [DeaDHackSTeam/HSHunter-1.0.0-Fixed](https://github.com/DeaDHackSTeam/HSHunter-1.0.0-Fixed) | 2 | Shell |  HSHunter Atomated Wireless Key Hacking Tool, handshakes are the wifi keys. When having a key in … |
| 685 | [dela-99/WIFI-HACKING](https://github.com/dela-99/WIFI-HACKING) | 2 | Python | Ethical WiFi pentesting. OFFENSIVE (explicit written permission) to spot flaws like weak encrypti… |
| 686 | [Dev-Lahrani/Evil-Twin_Wifi-Detection](https://github.com/Dev-Lahrani/Evil-Twin_Wifi-Detection) | 2 | Python | Deterministic Wi-Fi evil-twin detector for Raspberry Pi/Linux: explainable rule engine and RF fin… |
| 687 | [DiamondsBattle/Sqkele](https://github.com/DiamondsBattle/Sqkele) | 2 | — | A python all-in-one toolkit packed with tons of different features, including iOS and Android app… |
| 688 | [digenaldo/h4kfi](https://github.com/digenaldo/h4kfi) | 2 | Python | Wireless penetration testing framework with MCP integration built for OpenCode (Claude Code suppo… |
| 689 | [DrEggdwarf/Argos](https://github.com/DrEggdwarf/Argos) | 2 | Kotlin | Android WiFi security auditing app — pentesting, GPS trilateration, Evil Twin, AI captive portals |
| 690 | [ElusiveFoxie/WiFi-Password-Phishing](https://github.com/ElusiveFoxie/WiFi-Password-Phishing) | 2 | PHP | Simple PHP code for stealing WiFi passwords using evil twin attacks |
| 691 | [erkanrzgc/wlan-dumper](https://github.com/erkanrzgc/wlan-dumper) | 2 | Python | Terminal WiFi cracking toolkit: scan 802.11, deauth, capture WPA handshakes, crack. Textual TUI. … |
| 692 | [Ethhacks-official/Wireless-Protect_Service_Version](https://github.com/Ethhacks-official/Wireless-Protect_Service_Version) | 2 | Python | An open source tool to detect deauth, Evil Twin, Clonned wifi, Arp Spoofing and Man in the Middle… |
| 693 | [favian-jpt/wiCrack](https://github.com/favian-jpt/wiCrack) | 2 | Shell | WiFi pentest is a penetration testing tool that can be used in the field of security testing |
| 694 | [Figarow/eapol-hunter-flipper](https://github.com/Figarow/eapol-hunter-flipper) | 2 | C | EAPOL/PMKID Hunter für Flipper Zero - analysiert WiFi-Marauder-Captures direkt am Gerät, exportie… |
| 695 | [Ghost-Bx1/ghost-wifi](https://github.com/Ghost-Bx1/ghost-wifi) | 2 | Python | WiFi attack framework - monitor mode, deauth, WPA/WPA2 handshake, PMKID, WPS Pixie Dust, Evil Twi… |
| 696 | [giridarane/Wifi-Jamer](https://github.com/giridarane/Wifi-Jamer) | 2 | Python | his tool is a **Wi-Fi deauthentication (deauth) jammer** that can send deauth packets to a target… |
| 697 | [gn0sys11root/bluetm-wifi-osint-toolkit](https://github.com/gn0sys11root/bluetm-wifi-osint-toolkit) | 2 | Shell | WiFi pentesting framework with OSINT capabilities, DNS spoofing, captive portal, and handshake ca… |
| 698 | [gyf304/occupancy-sniffer](https://github.com/gyf304/occupancy-sniffer) | 2 | C | A secure wifi sniffer |
| 699 | [hackingyseguridad/jammerwifi](https://github.com/hackingyseguridad/jammerwifi) | 2 | Shell | Denegacion de servicio a punto de acceso Wifi  |
| 700 | [Hareesh-Rajput/WiFi-Pentest](https://github.com/Hareesh-Rajput/WiFi-Pentest) | 2 | — | A structured and actionable Excel-based checklist for WiFi penetration testing, covering every ph… |
| 701 | [Harsh-Parasharj/Aerosniff-x3](https://github.com/Harsh-Parasharj/Aerosniff-x3) | 2 | C++ | AeroSniff X3: WiFi, BLE, drone, jamming & packet sniffing tool with OLED & web UI, controls via b… |
| 702 | [Harsh-Tagra/wifi_jamer](https://github.com/Harsh-Tagra/wifi_jamer) | 2 | Shell | wifi jam dos attack |
| 703 | [hassanzprofile/wifi-jammer](https://github.com/hassanzprofile/wifi-jammer) | 2 | Shell | A Wi-Fi jammer script or tool is designed to disrupt and disable wireless communications between … |
| 704 | [hdog27/airgeddon-evil-twin-captive-portal](https://github.com/hdog27/airgeddon-evil-twin-captive-portal) | 2 | — | Evil Twin captive portal WiFi attack using Airgeddon v11.61 on Kali Linux with Panda Wireless AC6… |
| 705 | [hisham1665/Wifi_Pentester](https://github.com/hisham1665/Wifi_Pentester) | 2 | Python |  |
| 706 | [Hoanqnguyen292/Oled-Deauther](https://github.com/Hoanqnguyen292/Oled-Deauther) | 2 | C++ | Affordable WiFi hacking platform for testing and learning |
| 707 | [JoeSaf/Rouge_AP](https://github.com/JoeSaf/Rouge_AP) | 2 | Shell | A man in the middle tools which also creates evil twins and rouge WiFi’s (still in development) |
| 708 | [Join-Exception/Wifi-BLE-Jammer](https://github.com/Join-Exception/Wifi-BLE-Jammer) | 2 | C++ |  |
| 709 | [jrdnlrs/Pentacles](https://github.com/jrdnlrs/Pentacles) | 2 | Kotlin | Expected Thesis Output - an Android app that protects Filipino mobile users from fake WiFi networ… |
| 710 | [jrsmile/ODROID-GO-WIFI-SNIFFER](https://github.com/jrsmile/ODROID-GO-WIFI-SNIFFER) | 2 | C | Custom Firmware for the ODROID-GO to save pcap files to sd-card |
| 711 | [Juanx65/WifiSniffing](https://github.com/Juanx65/WifiSniffing) | 2 | Python | Testing A Case Study of WiFi Sniffing of Probe request |
| 712 | [k4u5h4L/CrackEasy](https://github.com/k4u5h4L/CrackEasy) | 2 | Shell | A WiFi cracking script which eases the process of bruteforcing and capturing handshakes. |
| 713 | [kaangoksal/wifi_device_stalker](https://github.com/kaangoksal/wifi_device_stalker) | 2 | Python | This piece of software is designed to sniff wifi packets and gather information about the sources… |
| 714 | [KevinDevSecOps/WifiKiller](https://github.com/KevinDevSecOps/WifiKiller) | 2 | Python | ### ⚡ **WiFiKiller (Educational)**   *"Aprende pentesting WiFi como un profesional"*   **Descripc… |
| 715 | [Kim-San04/Wireless-Hacking-Concepts-Methods-Security](https://github.com/Kim-San04/Wireless-Hacking-Concepts-Methods-Security) | 2 | — | WPA2/WPA3, Aircrack-ng, Handshake attacks, Evil Twin — Wireless Security \| ESMT Dakar |
| 716 | [Kry9toN/Wifi-Deauther-app](https://github.com/Kry9toN/Wifi-Deauther-app) | 2 | Java |  |
| 717 | [LiamJ74/5g-wifi-deauther-app-for-flipper-for-backpack-board](https://github.com/LiamJ74/5g-wifi-deauther-app-for-flipper-for-backpack-board) | 2 | — | 5g wifi deauther app for flipper for backpack board |
| 718 | [lukepereira/WiFiJammer](https://github.com/lukepereira/WiFiJammer) | 2 | Arduino |  |
| 719 | [m6c7l/tepsots](https://github.com/m6c7l/tepsots) | 2 | Python | Lightweight IEEE 802.11 Packet Sniffer |
| 720 | [ManojKumar-ind001/wifi-attaking-tool-easy-to-use](https://github.com/ManojKumar-ind001/wifi-attaking-tool-easy-to-use) | 2 | Python | MxAI WiFi Tool - A powerful cross-platform WiFi security assessment tool for penetration testing.… |
| 721 | [marcelomd/wifi-lateration](https://github.com/marcelomd/wifi-lateration) | 2 | C | Packet sniffer and trilateration to locate devices using wifi |
| 722 | [marpelskiy/pySniff---smart-wifi-sniffer](https://github.com/marpelskiy/pySniff---smart-wifi-sniffer) | 2 | Python | A smart Wi-Fi sniffer with the ability to send data to your Telegram bot and log it. |
| 723 | [matiaslahore/wifi-sniffer](https://github.com/matiaslahore/wifi-sniffer) | 2 | C | track people through a mall through smart devices |
| 724 | [michanisani/wifi_sniffer](https://github.com/michanisani/wifi_sniffer) | 2 | Python | wifi sniffer |
| 725 | [MikeRicketts/wifi-wpa2-handshake-cracking](https://github.com/MikeRicketts/wifi-wpa2-handshake-cracking) | 2 | — | Hands-on WPA2 4-way handshake capture-and-crack (Wireshark to hcxtools to hashcat), and how WPA3-… |
| 726 | [NGDSA-Lab/WiFi-CTF](https://github.com/NGDSA-Lab/WiFi-CTF) | 2 | HTML | Self-hosted virtual WiFi pentesting environment using Docker and mac80211_hwsim kernel module. Id… |
| 727 | [OttPeterR/Trakr](https://github.com/OttPeterR/Trakr) | 2 | Python | WiFi MAC Address sniffer that tracks when devices enter and exit areas regardless of wifi connect… |
| 728 | [paran0ids0ul/hubbIT-sniffer](https://github.com/paran0ids0ul/hubbIT-sniffer) | 2 | Python | Simple application that listens for WIFI-frames and records the mac-address of the sender and pos… |
| 729 | [pedroasr/Sniffer_Wifi](https://github.com/pedroasr/Sniffer_Wifi) | 2 | JavaScript |  |
| 730 | [possiblinkz/Wifite](https://github.com/possiblinkz/Wifite) | 2 | Python | an open-source, automated Python script designed to audit the security of Wi-Fi networks (WEP, WP… |
| 731 | [PranavGajjar0305/WifiJammer](https://github.com/PranavGajjar0305/WifiJammer) | 2 | Python |  |
| 732 | [prosaugat/wifi-jammer](https://github.com/prosaugat/wifi-jammer) | 2 | Python | Wifi jammer source code in python. |
| 733 | [PythonJu80/sniffymapp](https://github.com/PythonJu80/sniffymapp) | 2 | — | In a Nutshell 🛰️  This is a **comprehensive GPS security analysis toolkit** that combines passive… |
| 734 | [r00thex/wifi-jammer](https://github.com/r00thex/wifi-jammer) | 2 | Python |  |
| 735 | [R09Aditya/ESP-Marauder](https://github.com/R09Aditya/ESP-Marauder) | 2 | — | ESP Marauder is a cybersecurity tool used to jam, analyze and do alot of things on wifi or blueto… |
| 736 | [R0b1nary/radiosniffer](https://github.com/R0b1nary/radiosniffer) | 2 | Python | tool to sniff for wifi and bluetooth devices |
| 737 | [r0ug3/WiFi_Jammer](https://github.com/r0ug3/WiFi_Jammer) | 2 | Python | Jam all wifi clients and access points within range. |
| 738 | [RaymondReddington479/Wi-PWN](https://github.com/RaymondReddington479/Wi-PWN) | 2 | C | Wi-Deauther, open source project, test on wifi, project based on the samdenty project. |
| 739 | [rrrahat/Wifi-Jammer](https://github.com/rrrahat/Wifi-Jammer) | 2 | Python | A Wi-Fi testing tool for educational purposes |
| 740 | [rukstovv-hash/Alfa-AWUS036ACH](https://github.com/rukstovv-hash/Alfa-AWUS036ACH) | 2 | Python | Offensive WiFi toolkit for the ALFA AWUS036ACH — deauth, PMKID capture, WPS PIN brute, evil twin,… |
| 741 | [sagikandleker/WiFi-Evil-Twin](https://github.com/sagikandleker/WiFi-Evil-Twin) | 2 | Python | Fraudulent access point with phishing website |
| 742 | [SaifKhan2002/Wifi_Jammer_System_8086](https://github.com/SaifKhan2002/Wifi_Jammer_System_8086) | 2 | C |  |
| 743 | [salvul/Arduino_JammerWiFi](https://github.com/salvul/Arduino_JammerWiFi) | 2 | C | Create Wifi Jammer |
| 744 | [SantiagoRR2004/APS-WiFiSniffer](https://github.com/SantiagoRR2004/APS-WiFiSniffer) | 2 | C | Contador de personas |
| 745 | [secuRefeds/wifi-deauth](https://github.com/secuRefeds/wifi-deauth) | 2 | Python | wifi  deauther |
| 746 | [shahafel/wifi-jammer](https://github.com/shahafel/wifi-jammer) | 2 | — | python script using hackrf to jam wifi signals |
| 747 | [Shibasish-Dalui/Evil-Twin-Attack](https://github.com/Shibasish-Dalui/Evil-Twin-Attack) | 2 | C++ | Wifi network's security test using de-authentication and fake access point |
| 748 | [sidak/WiFi-Sniffing-and-Distributed-Computing](https://github.com/sidak/WiFi-Sniffing-and-Distributed-Computing) | 2 | C | Packet Sniffing and Distributed Computing tools for WiFi |
| 749 | [siul72/ksoft-wifi-serial-spy](https://github.com/siul72/ksoft-wifi-serial-spy) | 2 | C++ | Embedded device software for sniffing RS-485 bus communication lines and publish the serial data … |
| 750 | [sUbc0ol/deauth](https://github.com/sUbc0ol/deauth) | 2 | Python | wifi jammer written in python |
| 751 | [Swastika27/WiFi-password-crack](https://github.com/Swastika27/WiFi-password-crack) | 2 | Python | A custom tool for WiFi password cracking from captured WPA2 handshake frames and smart wordlist  |
| 752 | [tanvir-ahamed04/wifi-packet-sniffer](https://github.com/tanvir-ahamed04/wifi-packet-sniffer) | 2 | Python |  |
| 753 | [Th4ntis/Evil-Portals](https://github.com/Th4ntis/Evil-Portals) | 2 | CSS | Evil-Portals for WiFi Pineapples and other WiFi Pentesting |
| 754 | [The-SPARK-Initiative-Labs/Symbiosis-WiFiArsenal](https://github.com/The-SPARK-Initiative-Labs/Symbiosis-WiFiArsenal) | 2 | Python | A WiFi penetration testing platform with attack automation, evil twin portals, wardrive integrati… |
| 755 | [The90Frank/PresenceChecker](https://github.com/The90Frank/PresenceChecker) | 2 | Python | WiFi 802.11 packet sniffer and device detector for Linux with signal analysis and XML logging |
| 756 | [TheImposterz/RaspPunzel](https://github.com/TheImposterz/RaspPunzel) | 2 | Shell | RaspPunzel is a Raspberry Pi-based penetration testing platform that transforms a Pi into a porta… |
| 757 | [thex1le/py80211](https://github.com/thex1le/py80211) | 2 | Python | pure python wifi sniffer |
| 758 | [ThinkEE/python-WiFiSniffer](https://github.com/ThinkEE/python-WiFiSniffer) | 2 | Python | Small python script to use a wifi chip in monitor mode to send packets received through UDP |
| 759 | [Trsak/WifiSniffer](https://github.com/Trsak/WifiSniffer) | 2 | C++ | Tool for sniffing Wi-Fi data packets between client and access point. Uses libtins and libpcap li… |
| 760 | [truemorganss/wraithnet](https://github.com/truemorganss/wraithnet) | 2 | Python | A multitool for pentesting WiFi networks |
| 761 | [uffea/wifi_sniffer_setup](https://github.com/uffea/wifi_sniffer_setup) | 2 | Shell |  |
| 762 | [Vagalam88/FreqSniff](https://github.com/Vagalam88/FreqSniff) | 2 | C++ | Combined WiFi + LoRa/Meshtastic passive sniffer for the Heltec WiFi LoRa32 V2 |
| 763 | [vaibhavhere2003/wifi-autopwn](https://github.com/vaibhavhere2003/wifi-autopwn) | 2 | — | 🔍 Enhance WiFi security with this advanced penetration testing tool, covering generations from Wi… |
| 764 | [WU-AetherCore/airgeddon-evil-twin-lab](https://github.com/WU-AetherCore/airgeddon-evil-twin-lab) | 2 | Python | Airgeddon Evil Twin Lab - WiFi安全攻防实战实验室：Evil Twin自动化钓鱼系统（Web控制台一键攻击+密码自动验证）+ 8篇详细中文教程 + 一键部署脚本。仅限… |
| 765 | [xuananbui/wifi-pentesting-cheatsheet](https://github.com/xuananbui/wifi-pentesting-cheatsheet) | 2 | — |  |
| 766 | [yNeoo/wireless-hacking](https://github.com/yNeoo/wireless-hacking) | 2 | Shell | Auditoría WiFi en laboratorio: monitor mode, handshake/PMKID, WPA/WPA2/WPA3, WPS, Evil-Twin + det… |
| 767 | [yt2600/WiFry](https://github.com/yt2600/WiFry) | 2 | — | WiFry is a simple PAsrberry Pi based wifi jammer. The idea of the project is to create a easy to … |
| 768 | [Zer0D0wn/Jammer](https://github.com/Zer0D0wn/Jammer) | 2 | Perl | A perl wifi jammer who use an packet injection capable interface. Tested with Alfa AWUS1900. |
| 769 | [0000000O0Oo/Wifi-Deauther](https://github.com/0000000O0Oo/Wifi-Deauther) | 1 | Python | Script made by me and ec404-cool => htts://github.com/ec404-cool |
| 770 | [0xHadiRamdhani/wifi-deauther](https://github.com/0xHadiRamdhani/wifi-deauther) | 1 | Rust |  |
| 771 | [0xStr1k3r/AeroStrike](https://github.com/0xStr1k3r/AeroStrike) | 1 | Python | Wifi Pentesting Tool |
| 772 | [123tool/Wifi-Spy-Hacking](https://github.com/123tool/Wifi-Spy-Hacking) | 1 | Python | Alat audit keamanan jaringan nirkabel dan pengujian penetrasi jaringan yang komprehensif. Diranca… |
| 773 | [1destroyer100yt/PiFi-network-pentest](https://github.com/1destroyer100yt/PiFi-network-pentest) | 1 | HTML | every thing you need for wifi pentesting on a pi 0 w |
| 774 | [810810810/Tell-My-Wifi-Love-Her](https://github.com/810810810/Tell-My-Wifi-Love-Her) | 1 | Python | Written in python for automating wifi pentesting on a pentesting box. Do not use if you dont have… |
| 775 | [Abhay-Mahanta/Wifi-Deauther](https://github.com/Abhay-Mahanta/Wifi-Deauther) | 1 | Python | This tool can be used to deauth an access point or client from the network. |
| 776 | [ABHAYKUMARTRIPATHI/WiFi-Deauther-Simulator](https://github.com/ABHAYKUMARTRIPATHI/WiFi-Deauther-Simulator) | 1 | Python | A powerful Wi-Fi Deauther Simulator that emulates deauthentication attacks in a safe, educational… |
| 777 | [adamLevAri/EvilTwin](https://github.com/adamLevAri/EvilTwin) | 1 | Python | Evil Twin hacking WiFi network exploit |
| 778 | [affiqadha/Wifi-Security-Scanner](https://github.com/affiqadha/Wifi-Security-Scanner) | 1 | Dart | Advanced Android WiFi security scanner for detecting MITM attacks and Evil Twin networks - FYP Un… |
| 779 | [Afrochemist/WifiPentesting](https://github.com/Afrochemist/WifiPentesting) | 1 | — |  |
| 780 | [AGESILAS3118/wpa2-tp-link-writeup](https://github.com/AGESILAS3118/wpa2-tp-link-writeup) | 1 | — | 🛡️ Write-up complet — Crack d'un réseau WPA2 par capture de handshake (TP-Link_0124). Pentest WiF… |
| 781 | [ahsan-latif-tech/WifiMeNow](https://github.com/ahsan-latif-tech/WifiMeNow) | 1 | Python | Python tool that automates Wi-Fi hacking by capturing WPA/WPA2 handshakes and cracking them using… |
| 782 | [aksrivastava/wifi-deauther-advance](https://github.com/aksrivastava/wifi-deauther-advance) | 1 | C++ |  |
| 783 | [AlexisDuran/AutoCrackWifi](https://github.com/AlexisDuran/AutoCrackWifi) | 1 | — | Herramienta que automatiza el ataque a wifi de tipo handshake y PKMID |
| 784 | [alihaider998/Wifi-Deauther](https://github.com/alihaider998/Wifi-Deauther) | 1 | Python |  |
| 785 | [An0nMac/Wifi-Pentesting](https://github.com/An0nMac/Wifi-Pentesting) | 1 | Shell | The tools i use to pentest wifi |
| 786 | [Ananyapulluri/wifi-security-analyzer](https://github.com/Ananyapulluri/wifi-security-analyzer) | 1 | Python | Evil Twin & Rogue AP Detector with K-Means ML clustering |
| 787 | [aproxtimedev/wifi.id-deauther](https://github.com/aproxtimedev/wifi.id-deauther) | 1 | Shell | Wifi.ID Deauther using Aireplay-ng  |
| 788 | [armnsec/wireless-security-lab-wifi-pentesting](https://github.com/armnsec/wireless-security-lab-wifi-pentesting) | 1 | — | Wireless security lab demonstrating WPA2 attacks, handshake capture, password cracking, deauthent… |
| 789 | [AshmitThakur23/wifi-security-analyzer](https://github.com/AshmitThakur23/wifi-security-analyzer) | 1 | Python | WiFi Security Analyzer — A Windows-based personal network security tool that scans your WiFi for … |
| 790 | [AslamMahi/WiFi-Pentesting](https://github.com/AslamMahi/WiFi-Pentesting) | 1 | — | This guide offers a thorough, step-by-step approach to WiFi pentesting, designed for both beginne… |
| 791 | [baishakh22/Cracking-WiFi-WPA2-Handshake](https://github.com/baishakh22/Cracking-WiFi-WPA2-Handshake) | 1 | — |  |
| 792 | [BG7YWL/Wifi-Deauther-Oled-V4-Fake](https://github.com/BG7YWL/Wifi-Deauther-Oled-V4-Fake) | 1 | — |  |
| 793 | [boogiegainz/AirStrike-WiFi](https://github.com/boogiegainz/AirStrike-WiFi) | 1 | — | ⚡ Next-gen WiFi auditing platform — crack captured handshakes on Windows, full attack suite on Li… |
| 794 | [BVBGurke/wifi-handshaker](https://github.com/BVBGurke/wifi-handshaker) | 1 | Python | Passive WPA/WPA2 handshake capture on Linux + GPU cracking with hashcat on a Windows host over Ta… |
| 795 | [chinthajayanth/Wifi_Evil_Twin](https://github.com/chinthajayanth/Wifi_Evil_Twin) | 1 | Python | A graphical user interface (GUI) application built with Python and PyQt5. It's designed as a proo… |
| 796 | [cybrly/wifiscan](https://github.com/cybrly/wifiscan) | 1 | Rust | Wireless network scanner TUI with monitor mode, handshake capture, deauth, and evil twin |
| 797 | [DaayZMA/wifiCrack](https://github.com/DaayZMA/wifiCrack) | 1 | Shell | Bash script for WiFi network penetration testing, enabling handshake capture and PMKID attacks to… |
| 798 | [DevHrefTry/deauther](https://github.com/DevHrefTry/deauther) | 1 | Shell | Wifi deauter in bash |
| 799 | [dkprasad-surati/wifi-deauther](https://github.com/dkprasad-surati/wifi-deauther) | 1 | C | wifi jam and wifi attack |
| 800 | [ec404-cool/wifi_deauther](https://github.com/ec404-cool/wifi_deauther) | 1 | Python |  |
| 801 | [elansarialmahdi/Evil-Twin-Attack-PFA](https://github.com/elansarialmahdi/Evil-Twin-Attack-PFA) | 1 | HTML | Academic simulation of Evil Twin WiFi attack using EVE-NG, pfSense, Kali Linux and Ubuntu Server … |
| 802 | [ellipsys/WIFIRock](https://github.com/ellipsys/WIFIRock) | 1 | Dockerfile | Container centered in all the common tools for pentesting wifi networks. |
| 803 | [ELRame/Auditorias-Wifi](https://github.com/ELRame/Auditorias-Wifi) | 1 | — | Auditorias, reportes e informes sobre auditorias y pentests de redes wifi realizadas por mi. |
| 804 | [EmeshTheRipper/AI-WIFI-threat-detection-centre](https://github.com/EmeshTheRipper/AI-WIFI-threat-detection-centre) | 1 | Python | An AI-powered real-time security system that detects and mitigates wireless network threats using… |
| 805 | [Esteban4-CRo/Crock](https://github.com/Esteban4-CRo/Crock) | 1 | C++ | Wifi Pentesting Tool |
| 806 | [Falconmx1/WifiCannon](https://github.com/Falconmx1/WifiCannon) | 1 | Python | ⚡ Cross-platform WiFi attack framework. Crack WPA/WPA2, capture handshakes, Evil Twin, WPS pwn. W… |
| 807 | [firmware404/wifideauth](https://github.com/firmware404/wifideauth) | 1 | Python | Simple Wi-Fi Deauthentication Attack (wifi deauth) |
| 808 | [gerbsec/WIFI-Pentesting](https://github.com/gerbsec/WIFI-Pentesting) | 1 | — |  |
| 809 | [grimh3xx/aircracking-win-x64](https://github.com/grimh3xx/aircracking-win-x64) | 1 | Python | TUI orchestrator for authorized Wi-Fi audits: WPA/WPA2 handshake capture and offline cracking via… |
| 810 | [guzzt/wifi-pentest-framework](https://github.com/guzzt/wifi-pentest-framework) | 1 | Shell | Um simples bash script que possui alguns ataques a redes wifi |
| 811 | [heisnabil/WiChain-The-Wifi-Threat-Detector](https://github.com/heisnabil/WiChain-The-Wifi-Threat-Detector) | 1 | JavaScript | Decentralized real-time Wi-Fi threat detection & Evil Twin prevention engine combining cross-plat… |
| 812 | [Hemansh-Varshney/wifi-evil-twin-detector](https://github.com/Hemansh-Varshney/wifi-evil-twin-detector) | 1 | HTML |  |
| 813 | [hemapriyaperugu-hub/wifi-evil-twin-detection](https://github.com/hemapriyaperugu-hub/wifi-evil-twin-detection) | 1 | — |  |
| 814 | [Hexacon-labs/Portable_WiFi_Deauther](https://github.com/Hexacon-labs/Portable_WiFi_Deauther) | 1 | — |  |
| 815 | [Hs2aH/EAPOL-4way-Handshake-Pkt-Sniffer](https://github.com/Hs2aH/EAPOL-4way-Handshake-Pkt-Sniffer) | 1 | C++ | This project sniffes the network traffic that transmits the WIFI-Password in your regualar commer… |
| 816 | [hwac121/SniperCrack](https://github.com/hwac121/SniperCrack) | 1 | Shell | Wifi capture/cracking tool for educational purposes and pentesting |
| 817 | [ibrahimalakeel/wifi-pentesting](https://github.com/ibrahimalakeel/wifi-pentesting) | 1 | — |  |
| 818 | [ImLilDev/Evil-Twin-Collection](https://github.com/ImLilDev/Evil-Twin-Collection) | 1 | CSS | A collection of a few Evil Portals made for WiFi Pineapple based on well-known French ISPs and more! |
| 819 | [InitOneTeam/pentest-DockerWifi](https://github.com/InitOneTeam/pentest-DockerWifi) | 1 | — | This is project which aims to create a 'docker' which contains a lot of pentest wifi tools |
| 820 | [itsHareeshx01/Cybersecurity-project](https://github.com/itsHareeshx01/Cybersecurity-project) | 1 | — | Wi-Fi-Deauther wifi network Second project by nikhil (Nikto on a local lab vm) and third project … |
| 821 | [jaidanmaity/free-honey-wifi](https://github.com/jaidanmaity/free-honey-wifi) | 1 | Python | automating something like evil twin attack but creating a fake honey pot like wifi access point |
| 822 | [jailideaid/DeautherV2](https://github.com/jailideaid/DeautherV2) | 1 | Python | Deauth tool script adaptor wifi usb |
| 823 | [janelhuang28/Evil-Twin-Attack-with-Airgeddon](https://github.com/janelhuang28/Evil-Twin-Attack-with-Airgeddon) | 1 | — | Evil twin is similar to a social engineering attack that steals the WiFi password |
| 824 | [JavierSiliacay/2.4GHz-5GHz-WiFi-deauther](https://github.com/JavierSiliacay/2.4GHz-5GHz-WiFi-deauther) | 1 | — | A full-featured 2.4GHz & 5GHz WiFi deauther with web-based controls, real-time scanning, multi-ta… |
| 825 | [jayzonesec-ops/crack-wifi-password](https://github.com/jayzonesec-ops/crack-wifi-password) | 1 | Shell | Ferramenta automatizada para captura de handshake WPA/WPA2 e quebra de senha WiFi com wordlists, … |
| 826 | [JPJ-89/Fluxion-Spanish-Orange-Livebox-Router-Portal-Translation-Evil-Twin-Attack---WiFi-](https://github.com/JPJ-89/Fluxion-Spanish-Orange-Livebox-Router-Portal-Translation-Evil-Twin-Attack---WiFi-) | 1 | — | This Fluxion template functions as a cloned visual bait whose sole purpose is to deceive the user… |
| 827 | [juanga333/Netattack](https://github.com/juanga333/Netattack) | 1 | Python | A wifi pentesting tool using scapy |
| 828 | [JustFernandezz/Wireless-Hacking](https://github.com/JustFernandezz/Wireless-Hacking) | 1 | PowerShell | Wireless deauther and wifi cloner |
| 829 | [kamelisas/wifi-forensics-toolkit](https://github.com/kamelisas/wifi-forensics-toolkit) | 1 | Python | Kismet .netxml WiFi capture triage tool with rogue-AP/evil-twin detection |
| 830 | [Kaniga-sri/ai-powered-evil-twin-wifi-detection-system](https://github.com/Kaniga-sri/ai-powered-evil-twin-wifi-detection-system) | 1 | — | AI-powered system for detecting suspicious Evil Twin Wi-Fi access points using real-time Wi-Fi an… |
| 831 | [kapo-hacker/evil-twin-hack-wifi-kapo](https://github.com/kapo-hacker/evil-twin-hack-wifi-kapo) | 1 | — | I'm kapo. I'm making hacking tools and adjusting other tools to make them powerful. It's a tool s… |
| 832 | [karthik9810/wifi-network-pentesting-tool](https://github.com/karthik9810/wifi-network-pentesting-tool) | 1 | Python | 📡 Advanced WiFi Network Pentesting Tool \| Port Scanner \| Device Scanner \| DNS Leak Test \| Fir… |
| 833 | [karthik9810/wifi-ultimate-pentesting-tool-v5](https://github.com/karthik9810/wifi-ultimate-pentesting-tool-v5) | 1 | Python | 📡 Ultimate WiFi Pentesting Tool v5.0 \| 20 Features \| AI Threat Analysis \| Deep Port Scanner \|… |
| 834 | [Kashyap2way/Humming-Beta](https://github.com/Kashyap2way/Humming-Beta) | 1 | JavaScript | A wifi hacker app which works on .cap file of any network handshake then uses brute force and pas… |
| 835 | [kiboiesther/WiFi-Scanner](https://github.com/kiboiesther/WiFi-Scanner) | 1 | HTML | WiFi scanner for evil twin attacks |
| 836 | [kilam994/CryFi](https://github.com/kilam994/CryFi) | 1 | Python | A local web dashboard for the aircrack-ng suite - scan, capture handshakes, crack, and generate w… |
| 837 | [KiltzX/Wifi-Deauth-Python](https://github.com/KiltzX/Wifi-Deauth-Python) | 1 | Python | Wifi deauther using aireplay and airodump |
| 838 | [KONERI-VISHNU/Wireless-Network-Security-Assessment](https://github.com/KONERI-VISHNU/Wireless-Network-Security-Assessment) | 1 | — | A practical wireless security lab project demonstrating WiFi penetration testing techniques such … |
| 839 | [Landull/wifiscan](https://github.com/Landull/wifiscan) | 1 | Python | Lists nearby Wi-Fi networks and flags open, WEP, WPA/TKIP and possible evil-twin access points. P… |
| 840 | [mandoof1/WiFi-Pentest-Assistant-Script](https://github.com/mandoof1/WiFi-Pentest-Assistant-Script) | 1 | Shell | Menu-driven Bash assistant for authorized WiFi security testing — monitor mode, airodump scanning… |
| 841 | [mitthu786/wifijam](https://github.com/mitthu786/wifijam) | 1 | Shell | pentest toolkit whose goal is to perform jam on WiFi clients/routers and spam many fake AP for te… |
| 842 | [Mr-Beta-Version/WIFI-PENTEST](https://github.com/Mr-Beta-Version/WIFI-PENTEST) | 1 | C | Wifi Penetration Testing Tools |
| 843 | [MRGcodex/WipanFi](https://github.com/MRGcodex/WipanFi) | 1 | Python | An advanced Linux WiFi auditing toolkit by MRGcodex. Features auto monitor mode, PMKID & Handshak… |
| 844 | [ms604/wifi-pentest-tool](https://github.com/ms604/wifi-pentest-tool) | 1 | Python | Wi-Fi pentesting tool with deauth, handshake capture, and cracking features |
| 845 | [mw-darksword/Wifi-Pentest](https://github.com/mw-darksword/Wifi-Pentest) | 1 | Python | Automated Wi-Fi penetration testing tool using Aircrack-ng suite. Detects wireless adapters, capt… |
| 846 | [NETERBIL/Cracking-WiFi-WPA2-Handshake](https://github.com/NETERBIL/Cracking-WiFi-WPA2-Handshake) | 1 | — |  |
| 847 | [Nimpo714/WifiDeauther](https://github.com/Nimpo714/WifiDeauther) | 1 | Python | Скрипт для отключения всех устройств от Wifi (скрипт проверен на Arch Linux) |
| 848 | [noushad27/Dog_Trail](https://github.com/noushad27/Dog_Trail) | 1 | Python | 🐾 Your WiFi's guard dog. Detects evil twin attacks & rogue access points — then explains it in pl… |
| 849 | [OblivionDH/oblivion-wifi-auditor](https://github.com/OblivionDH/oblivion-wifi-auditor) | 1 | Python | Modular WiFi security auditing toolkit in Python: scan networks, test WPA/WPA2, capture handshake… |
| 850 | [ohyoxo/wifi-adapter-tool](https://github.com/ohyoxo/wifi-adapter-tool) | 1 | Shell | AI-enhanced Wi-Fi adapter tool for ethical pentesting. |
| 851 | [Omchireddy/wifi-evil-twin-detector](https://github.com/Omchireddy/wifi-evil-twin-detector) | 1 | Python | Evil Twin Wi-Fi Detector is a lightweight command-line tool designed to detect potential Evil Twi… |
| 852 | [OsteenK/netcheck](https://github.com/OsteenK/netcheck) | 1 | Shell | Network diagnostic & security scanner for Linux. Single Bash script — WiFi analysis, evil twin de… |
| 853 | [owlsecx/OKarma](https://github.com/owlsecx/OKarma) | 1 | Go | OKarma: Evil-Twin/KARMA Analyzer |
| 854 | [oycillessen/ETD-Bire](https://github.com/oycillessen/ETD-Bire) | 1 | Python | This program is used for evil twin attackes detection. |
| 855 | [PARIKAKUGOD1/WIFI-Deauther](https://github.com/PARIKAKUGOD1/WIFI-Deauther) | 1 | Python | WIFI-Deauther – A Python-based tool for performing WiFi deauthentication attacks using aircrack-n… |
| 856 | [paumnoz/WifiHackingStuff](https://github.com/paumnoz/WifiHackingStuff) | 1 | Python | a set of tools and scripts used for pentesting wifi networks |
| 857 | [pcabdou37-collab/DMT-CyberFang-Ultimate-Security-Tool-](https://github.com/pcabdou37-collab/DMT-CyberFang-Ultimate-Security-Tool-) | 1 | C++ | DMT-CyberFang جهاز أمن سيبراني محمول يجمع بين Dr Password لحفظ وتشفير 50 تطبيقاً وموقعاً، وDr Hac… |
| 858 | [philiWeitz/wifiSniffer](https://github.com/philiWeitz/wifiSniffer) | 1 | C |  |
| 859 | [PhoniexCoder/wifi-pentest-tool](https://github.com/PhoniexCoder/wifi-pentest-tool) | 1 | Python | A Python-based WiFi penetration testing tool that automates various security assessments like net… |
| 860 | [ProgramingFactory/SignalStrength](https://github.com/ProgramingFactory/SignalStrength) | 1 | C# | WiFi-SignalStrength app for tracking signal strength; WiFi-Sniffer; |
| 861 | [R-S-Nithesh/Aircrack-Mcp](https://github.com/R-S-Nithesh/Aircrack-Mcp) | 1 | Python | MCP server that wraps aircrack-ng, enabling AI assistants to run and automate WiFi security asses… |
| 862 | [rafaelharzer/Guia_Pentest_WiFi_PT_BR](https://github.com/rafaelharzer/Guia_Pentest_WiFi_PT_BR) | 1 | — | Um guia pratico para auxiliar meus colegas profissionais da área a realizar um Pentest em redes W… |
| 863 | [rahimmahamane/wifi-app](https://github.com/rahimmahamane/wifi-app) | 1 | Python | Pentest pour wifi a titre éducatif . |
| 864 | [RajeshSagar2912/wifi-testing](https://github.com/RajeshSagar2912/wifi-testing) | 1 | — | This repo will contains all my wifi pentesting useful commands |
| 865 | [RANAJIIIII/Wifi-Broot](https://github.com/RANAJIIIII/Wifi-Broot) | 1 | Python | Crack WPA/WPA2 passwords using brute-force attacks. Supports handshake capture and crack, PMKID c… |
| 866 | [Raunaksplanet/WiFi-Security-Pentesting-Learning-Notes](https://github.com/Raunaksplanet/WiFi-Security-Pentesting-Learning-Notes) | 1 | — | Personal documentation of my WiFi security research |
| 867 | [Rayenthestrongest/wifi-spectre-mcp](https://github.com/Rayenthestrongest/wifi-spectre-mcp) | 1 | HTML | Aircrack-MCP WiFi Pentesting Suite Automated 2026 |
| 868 | [Rexturnull/WiFi-PenTest](https://github.com/Rexturnull/WiFi-PenTest) | 1 | — | WiFi-PenetrationTest |
| 869 | [rezaul1773/Wifi-penetesting-with-password-cracking](https://github.com/rezaul1773/Wifi-penetesting-with-password-cracking) | 1 | — | Here is demo wifi pentesting and password cracking. If want pentest your network don't hesitate t… |
| 870 | [rizkyngrh23/wifi-cracking-with-aircrack](https://github.com/rizkyngrh23/wifi-cracking-with-aircrack) | 1 | — | This repository provides a comprehensive guide and scripts for cracking WPA/WPA2 WiFi passwords u… |
| 871 | [ronnymboumba1-maker/J4thniel_Evil_twin](https://github.com/ronnymboumba1-maker/J4thniel_Evil_twin) | 1 | Python | EVIL TWIN ULTIME est un outil de test de sécurité WiFi qui simule une attaque Evil Twin. Il perme… |
| 872 | [s3al4er/wifi-deauther](https://github.com/s3al4er/wifi-deauther) | 1 | Python |  |
| 873 | [sachintha82288-cpu/WiFi-Evil-Twin](https://github.com/sachintha82288-cpu/WiFi-Evil-Twin) | 1 | Python | Can be used to perform Evil Twin attacks for WiFi testing. |
| 874 | [saherkhizr123/wifi_evil_twin_detector](https://github.com/saherkhizr123/wifi_evil_twin_detector) | 1 | — | Detect fake wifi network that mimic real ones . Ethical hacking tool for awareness |
| 875 | [Salvatore-droid/web-interface-wifi-deauther](https://github.com/Salvatore-droid/web-interface-wifi-deauther) | 1 | HTML |  |
| 876 | [Sandeep3062/wifi-handshake-capture-and-crack-demo](https://github.com/Sandeep3062/wifi-handshake-capture-and-crack-demo) | 1 | — | "Educational project demonstrating Wi-Fi handshake capture and cracking using Aircrack-ng and Kal… |
| 877 | [Sanjeewa-Karunarathna/Wifi_Pentest_Automation_Scripts](https://github.com/Sanjeewa-Karunarathna/Wifi_Pentest_Automation_Scripts) | 1 | Python |  |
| 878 | [saranb565/EthicalHacking](https://github.com/saranb565/EthicalHacking) | 1 | — | Doc with commands and screenshots of Hacking Tasks involving WiFi - Password Cracking, Evil Twin … |
| 879 | [SecuredByKC/wifi-deauth-attack-red](https://github.com/SecuredByKC/wifi-deauth-attack-red) | 1 | — | My hands-on WPA2 handshake capture and cracking using deauthentication attacks on Kali Linux. Inc… |
| 880 | [seva009/WiFi-jammer](https://github.com/seva009/WiFi-jammer) | 1 | C++ | А это уже не deauther :) |
| 881 | [SharadS28N/Netguard](https://github.com/SharadS28N/Netguard) | 1 | TypeScript | NetGuard Nepal detects and neutralizes evil twin WiFi networks in real-time. Enterprise-grade sec… |
| 882 | [sidharth-v-s/Wifi-Evil-Twin](https://github.com/sidharth-v-s/Wifi-Evil-Twin) | 1 | Python |  |
| 883 | [sifatnotes/secbyte-wifi-security-wpa2-wpa3-rogue-ap-embedded-iot-ctf-labs](https://github.com/sifatnotes/secbyte-wifi-security-wpa2-wpa3-rogue-ap-embedded-iot-ctf-labs) | 1 | — | A practical collection of cybersecurity CTF labs covering wireless network security (Wi-Fi fundam… |
| 884 | [silverbulletex0-debug/All-Wifi-Jacking-](https://github.com/silverbulletex0-debug/All-Wifi-Jacking-) | 1 | Shell | Advanced wireless security auditing framework featuring persistent scanning, automated deauth att… |
| 885 | [SleepTheGod/LinuxNetworkPentesting](https://github.com/SleepTheGod/LinuxNetworkPentesting) | 1 | Python | A gui for linux wifi network penetration testing |
| 886 | [SleepTheGod/Wifi-Pentesting](https://github.com/SleepTheGod/Wifi-Pentesting) | 1 | — | How to hack wifi and log it |
| 887 | [sobri3195/pegasus-wifi-sobri](https://github.com/sobri3195/pegasus-wifi-sobri) | 1 | — | a tool designed for various WiFi network operations such as scanning networks, capturing handshak… |
| 888 | [stefaslsfij/Deauther.Wifi](https://github.com/stefaslsfij/Deauther.Wifi) | 1 | Python |  |
| 889 | [sulthanbathusha852-commits/AI-Based-Wifi-Evil-Twin-Detection-System](https://github.com/sulthanbathusha852-commits/AI-Based-Wifi-Evil-Twin-Detection-System) | 1 | HTML |  |
| 890 | [SupCom-Cyber-Security/Wifi-Pentest-Workshop-25-26](https://github.com/SupCom-Cyber-Security/Wifi-Pentest-Workshop-25-26) | 1 | HTML |  |
| 891 | [the-hollowclan/Sneak-Into-Wifi](https://github.com/the-hollowclan/Sneak-Into-Wifi) | 1 | CSS | An AP setup utility, with captive portal to perform a controlled Evil-Twin. Use this responsibly |
| 892 | [thund3rb0lt0x1/wifi-pentesting-notes](https://github.com/thund3rb0lt0x1/wifi-pentesting-notes) | 1 | — | A comprehensive reference guide for WiFi penetration testing and OSWP (PEN-210) exam preparation. |
| 893 | [TM-Mehrab-Hasan/Iot-based-secure-wifi-deauthering-system](https://github.com/TM-Mehrab-Hasan/Iot-based-secure-wifi-deauthering-system) | 1 | C |  |
| 894 | [tmvwin/WIFI--PENTESTING-ADDED-Cyber-security-with-AI-VI](https://github.com/tmvwin/WIFI--PENTESTING-ADDED-Cyber-security-with-AI-VI) | 1 | Python | 8TH module with voice assissents  + AI  |
| 895 | [ToraGaming/wifi-pentest-lab](https://github.com/ToraGaming/wifi-pentest-lab) | 1 | Shell | 📡 Wi-Fi 6 pentesting lab: Alfa AWUS036AXML (MT7921U) on Kali for WPA3/SAE Dragonblood analysis |
| 896 | [toutpuissantged/hacktools-cpp](https://github.com/toutpuissantged/hacktools-cpp) | 1 | C++ | wifi pentest tools can exploit free trial vulnerability  |
| 897 | [tr4m0ryp/iot-evil-twin-lab](https://github.com/tr4m0ryp/iot-evil-twin-lab) | 1 | C++ | IoT evil-twin WiFi attack + defense lab (personal-network security education) |
| 898 | [unrealistic-reality/wifi-wordlists](https://github.com/unrealistic-reality/wifi-wordlists) | 1 | — | A Philippine based wordlist for cracking wifi passwords captured from handshakes. |
| 899 | [usersdsa/wifi](https://github.com/usersdsa/wifi) | 1 | — | Wifi deauther layther |
| 900 | [v-aryank/NRF_Box-WiFi_Bluetooth_Deauther](https://github.com/v-aryank/NRF_Box-WiFi_Bluetooth_Deauther) | 1 | — |  |
| 901 | [victor22-te/wifi_pentest](https://github.com/victor22-te/wifi_pentest) | 1 | — | prueba de Hacking ético de wifi |
| 902 | [vperron/snow](https://github.com/vperron/snow) | 1 | C | WiFi packets sniffer |
| 903 | [W0rKiska/wlab](https://github.com/W0rKiska/wlab) | 1 | Shell | WLAB — лабораторный набор для Wi-Fi / BLE / OSINT: скан, деаут, хендшейк, PMKID, evil twin, BLE-с… |
| 904 | [WarGod5o5/Arduino-WiFi-Deauther-Detector](https://github.com/WarGod5o5/Arduino-WiFi-Deauther-Detector) | 1 | C++ |  |
| 905 | [willlccasey/kali-wifi-pentest-kit](https://github.com/willlccasey/kali-wifi-pentest-kit) | 1 | Python | WiFi Pentest Kit GUI — scanner, deauth, evil twin, beacon spam, handshake capture |
| 906 | [xiv3r/handshake-bruteforce](https://github.com/xiv3r/handshake-bruteforce) | 1 | — | bruteforce the 4 way wifi handshake using air-crack via github action workflow |
| 907 | [YanivHaliwa/WifiSec](https://github.com/YanivHaliwa/WifiSec) | 1 | Shell | WiFi auditing toolkit with multi-target capture, PMKID/deauth dual-path attacks, handshake triple… |
| 908 | [zadkiel9067-hash/WifiSecurityScanner](https://github.com/zadkiel9067-hash/WifiSecurityScanner) | 1 | Kotlin | Advanced WiFi Security Scanner with Evil Twin Detection |
| 909 | [zeleron7/Wi-Fi-security-risks](https://github.com/zeleron7/Wi-Fi-security-risks) | 1 | — | Thesis project exploring security risks in open Wi-Fi networks, demonstrating Evil Twin attacks i… |
| 910 | [ZorvWolf/EvilJam](https://github.com/ZorvWolf/EvilJam) | 1 | Python | So guys this is asicly a wifi tool which helps in deauth attack and Cracking wpa2 handshake files… |
| 911 | [0xfL0ki/wifiee](https://github.com/0xfL0ki/wifiee) | 0 | Shell | WiFi EAP Evil-twin & PEAP Relay Toolkit |
| 912 | [1uci1er/Evil-Twin-Attack](https://github.com/1uci1er/Evil-Twin-Attack) | 0 | — | WIFI Evil Twin Attack Guide |
| 913 | [Abdelkarim-mourad/evolution-of-wifi-security-wpa2-wpa3](https://github.com/Abdelkarim-mourad/evolution-of-wifi-security-wpa2-wpa3) | 0 | — | Wireless security research project analyzing WPA2 weaknesses, WPA3 improvements, SAE handshake, D… |
| 914 | [Aishah205/wifi-security-lab](https://github.com/Aishah205/wifi-security-lab) | 0 | — | WiFi Security Lab (simulated, no USB adapter) : conceptual walkthrough of WPA2 handshake capture … |
| 915 | [AlexNaskida/WiFi-Evil-Twin](https://github.com/AlexNaskida/WiFi-Evil-Twin) | 0 | Shell |  |
| 916 | [alungal-sinan/WiFi-EvilTwin-Emulator](https://github.com/alungal-sinan/WiFi-EvilTwin-Emulator) | 0 | Python | A simulation tool written in Python that emulates an Evil Twin access point with fake DHCP and DN… |
| 917 | [anishaSawant0409/EvilTwin-wifi-access-point-detector](https://github.com/anishaSawant0409/EvilTwin-wifi-access-point-detector) | 0 | HTML | An intelligent Wi-Fi security tool that detects Evil Twin access points by monitoring network par… |
| 918 | [apexmaniac/Wi-Fi-SCC](https://github.com/apexmaniac/Wi-Fi-SCC) | 0 | Python | scripts to scan wifi networks , capture handshakes & cracking passwords |
| 919 | [aymannijamuddeen/WIFI-EvilL-twin-detection-](https://github.com/aymannijamuddeen/WIFI-EvilL-twin-detection-) | 0 | Python |  |
| 920 | [B34tF34T/fluxion-original](https://github.com/B34tF34T/fluxion-original) | 0 | — | wifi evil twin pentesting |
| 921 | [bangladeshcyberspectre/WIFI-SCANNER](https://github.com/bangladeshcyberspectre/WIFI-SCANNER) | 0 | Shell | wifi-scanner, cybersecurity, penetration-testing, ethical-hacking, aircrack-ng,  reaver, wps-atta… |
| 922 | [Ben-Big/wifiCrackGUI](https://github.com/Ben-Big/wifiCrackGUI) | 0 | Python | BOG'S WiFi Attack Suite is a GUI-based WiFi security testing tool that enables network scanning, … |
| 923 | [berkaybnc/EvilTwinWifi](https://github.com/berkaybnc/EvilTwinWifi) | 0 | HTML |  |
| 924 | [bmitay4/WiFiEvilTwin](https://github.com/bmitay4/WiFiEvilTwin) | 0 | — | ‫‪WiFi‬‬ ‫‪Attack‬‬ ‫&‬ ‫‪Defense‬‬ ‫‪Module‬‬ |
| 925 | [catx0rr/wifiphisher-mod](https://github.com/catx0rr/wifiphisher-mod) | 0 | C | Evil-Twin for wireless penetration tests |
| 926 | [chukwupg/wireless-security-audit-lab](https://github.com/chukwupg/wireless-security-audit-lab) | 0 | — | Wireless Security Assessment Lab simulating WPA/WPA2 attacks, including handshake capture, deauth… |
| 927 | [Cipher-Sheild/WiFiStrike-FW](https://github.com/Cipher-Sheild/WiFiStrike-FW) | 0 | Shell | Modular wireless penetration testing framework for WPA/WPA2 assessment, handshake capture, deauth… |
| 928 | [ciscothehackergod/Wpa2_cracking](https://github.com/ciscothehackergod/Wpa2_cracking) | 0 | — | i simulated a wifi handshake capture attack on my home lab and cracked the captured hash  |
| 929 | [cnaqxc/evil-twin-wifi](https://github.com/cnaqxc/evil-twin-wifi) | 0 | Python |  |
| 930 | [Cuberzing/wifi-pentest-lab](https://github.com/Cuberzing/wifi-pentest-lab) | 0 | — | Full WPA2 penetration test — TP-Link monitor mode setup, live handshake capture via deauth attack… |
| 931 | [cuzoisrael/izywifi](https://github.com/cuzoisrael/izywifi) | 0 | Python | Python wrapper for WiFi auditing: Scan, capture handshakes, and prep for cracking (ethical lab to… |
| 932 | [daniel-mwendwa/WiFi-Security-and-PenTesting](https://github.com/daniel-mwendwa/WiFi-Security-and-PenTesting) | 0 | — | A comprehensive report on WiFi security and penetration testing techniques, covering WPA & WPA2 e… |
| 933 | [darkrider88/wifi-auditor](https://github.com/darkrider88/wifi-auditor) | 0 | Python | A python tool to capture Wireless network handshake and crack it |
| 934 | [denethsec/evil-twin-wifi-lab](https://github.com/denethsec/evil-twin-wifi-lab) | 0 | Python |  |
| 935 | [dheerajramasahayam/Model_Training](https://github.com/dheerajramasahayam/Model_Training) | 0 | Python | Train model on wifi handshakes and try to crack passwords |
| 936 | [dhruvnotcyber2005/WPA-WPA2-WiFi-Password-Cracking](https://github.com/dhruvnotcyber2005/WPA-WPA2-WiFi-Password-Cracking) | 0 | — | Educational WPA2 Wi-Fi security assessment project demonstrating handshake capture and password a… |
| 937 | [dome-hub/WiFi-Security-Auditing-Project](https://github.com/dome-hub/WiFi-Security-Auditing-Project) | 0 | — | WPA2 Handshake Cracking |
| 938 | [ethanrunn/Simulated-WiFi-Hacking-Report-WPA2-Handshake-Capture-and-Crack](https://github.com/ethanrunn/Simulated-WiFi-Hacking-Report-WPA2-Handshake-Capture-and-Crack) | 0 | — |  |
| 939 | [G1thu8D4LL45/WIFIght](https://github.com/G1thu8D4LL45/WIFIght) | 0 | Shell | One single tool to catch handshakes and crack wifi passwords with a bunch of tools. |
| 940 | [giri068/evil-twin-wifi](https://github.com/giri068/evil-twin-wifi) | 0 | PHP | This project demonstrates how an Evil Twin Wi-Fi attack works by simulating a fake Access Point w… |
| 941 | [HarshRajSinghania/AirPhantom](https://github.com/HarshRajSinghania/AirPhantom) | 0 | Python | Wifi Deauther |
| 942 | [HelixCipher/wifi-penetration-testing](https://github.com/HelixCipher/wifi-penetration-testing) | 0 | Python | WiFi penetration testing guide with hardware-based and hardware-free setups. Includes handshake c… |
| 943 | [HikmatAsifli/wifi_auth_tool](https://github.com/HikmatAsifli/wifi_auth_tool) | 0 | Shell | Modular bash toolkit for WiFi recon, WPA/WPA2 handshake capture & cracking — built for authorized… |
| 944 | [imanfatimz/wifi_evil_twin_detector](https://github.com/imanfatimz/wifi_evil_twin_detector) | 0 | Python |  |
| 945 | [JackTheTripperr/WiFi-Hack](https://github.com/JackTheTripperr/WiFi-Hack) | 0 | — | Basic guide outlining the process to capture a handshake, convert it to a Hashcat compatible hash… |
| 946 | [jagaor/Auditoria-WiFi-EvilTwin-Python](https://github.com/jagaor/Auditoria-WiFi-EvilTwin-Python) | 0 | — | Herramienta de ciberseguridad en Python para auditar redes WiFi, detectar ataques Evil Twin y val… |
| 947 | [jagdishtripathy/WIFI-Password-Cracking](https://github.com/jagdishtripathy/WIFI-Password-Cracking) | 0 | — | This documentation demonstrates how to perform a WPA/WPA2 Wi-Fi handshake capture and password cr… |
| 948 | [jenish78/fake-wifi-evil-twin-detection-tool](https://github.com/jenish78/fake-wifi-evil-twin-detection-tool) | 0 | Python | fake wifi |
| 949 | [Jexasa/wifighter](https://github.com/Jexasa/wifighter) | 0 | Python | A Python CLI tool to capture and crack WPA/WPA2 handshakes using Kali Linux and `aircrack-ng` or … |
| 950 | [kayShahbaaz/thm-wifi-hacking101](https://github.com/kayShahbaaz/thm-wifi-hacking101) | 0 | — | Notes from TryHackMe's WiFi Hacking 101 room. Capturing WPA/WPA2 4 way handshakes with the aircra… |
| 951 | [kogmau/gatonet](https://github.com/kogmau/gatonet) | 0 | Python | GatoNet — avaliacao autorizada de redes WiFi: scan, assess, capture (PMKID/handshake/WPS), crack … |
| 952 | [LamarCS1337/wifitraining](https://github.com/LamarCS1337/wifitraining) | 0 | Shell | Evil Twin Training |
| 953 | [liavgu/WifiMaster](https://github.com/liavgu/WifiMaster) | 0 | — | Automation tool for evil twin attack. |
| 954 | [mahashakshuki/Network-Security-Project-WiFi-Evil-Twin-and-KRACK-Attack-](https://github.com/mahashakshuki/Network-Security-Project-WiFi-Evil-Twin-and-KRACK-Attack-) | 0 | — | WIFI Evil Twin and Krack Attack  |
| 955 | [MinArchie/evil-twin-wifi](https://github.com/MinArchie/evil-twin-wifi) | 0 | C |  |
| 956 | [Mun-dus/Memory-Forensics-of-NMEA-2000-Wireless-De-Auth-Attack-Keyword-Search-Script](https://github.com/Mun-dus/Memory-Forensics-of-NMEA-2000-Wireless-De-Auth-Attack-Keyword-Search-Script) | 0 | Python | A keyword search tool built for the project Cracking the Maritime Handshake. It scans RAM dumps f… |
| 957 | [mystry112000/wifi-analyzer](https://github.com/mystry112000/wifi-analyzer) | 0 | Python | WiFi Analyzer - Educational aircrack-ng wrapper with WiFi network scanner. Scan networks and crac… |
| 958 | [Nandahh14/Evil-Twin-Wifi-Detection](https://github.com/Nandahh14/Evil-Twin-Wifi-Detection) | 0 | SCSS | Behaviour-Aware Evil Twin Wi-Fi Detection System with adaptive risk analysis. |
| 959 | [nishk28/Wifi-password-hack](https://github.com/nishk28/Wifi-password-hack) | 0 | Python | A comprehensive Python-based automation tool for conducting authorized Wi-Fi security assessments… |
| 960 | [nn1626/pwrlvl9000-pager](https://github.com/nn1626/pwrlvl9000-pager) | 0 | — | WiFi Pineapple Pager pentest console — 9-tab hacker web UI with WiFi, WPS, evil twin, probe sniff… |
| 961 | [omairtemurian/Wifi-HS-Cracker](https://github.com/omairtemurian/Wifi-HS-Cracker) | 0 | Python | WPA/WPA2 handshake cracker — performs dictionary attacks against captured .cap files using pure P… |
| 962 | [Onurcanblkn/wifi-pentest-project](https://github.com/Onurcanblkn/wifi-pentest-project) | 0 | — | WPA2 Handshake Cracking and Security Analysis |
| 963 | [outgrow2029/macOS-WiFi-Pentest](https://github.com/outgrow2029/macOS-WiFi-Pentest) | 0 | Python | An automated script for cracking wifi handshakes, specific for MacOS via dictionary attack (for now) |
| 964 | [p4oT09/p4oT09](https://github.com/p4oT09/p4oT09) | 0 | — | 🔥 p4oT09 is an advanced WiFi exploitation toolkit ⚡ Made for pentesters, ethical hackers & resear… |
| 965 | [phuongntmlc/NetworkII_WifiPwdCracking](https://github.com/phuongntmlc/NetworkII_WifiPwdCracking) | 0 | Python | Used brute-force method to create a tool can find WiFi password based on analyzing packets of the… |
| 966 | [Pitchouneee/wifi-evil-twin](https://github.com/Pitchouneee/wifi-evil-twin) | 0 | PHP |  |
| 967 | [Prajwalpawar1/evil-twin-wifi-](https://github.com/Prajwalpawar1/evil-twin-wifi-) | 0 | C++ | it is program which use to search all avilable wifi near to us and cheak password is valid or not… |
| 968 | [RaviNayyar/WifiAutoEvilTwin](https://github.com/RaviNayyar/WifiAutoEvilTwin) | 0 | Python | Automatically executes an wifi evil twin attack |
| 969 | [ridhinva/wifi-audit](https://github.com/ridhinva/wifi-audit) | 0 | Python | Tool: WiFi security auditor — WPA/WPA2/WPA3 handshake capture, PMKID, deauth, and cracking in Python |
| 970 | [rooster197/wifi-deauther](https://github.com/rooster197/wifi-deauther) | 0 | — | wifi deauther |
| 971 | [Rwalhussain/WiFiTrap](https://github.com/Rwalhussain/WiFiTrap) | 0 | Python | WiFiTrap - Evil Twin Attack Simulator |
| 972 | [sadiqgarba2553/wifi-master](https://github.com/sadiqgarba2553/wifi-master) | 0 | Python | **WiFi Master** automates aircrack-ng for wireless penetration testing. Handles monitor mode, net… |
| 973 | [SaidSec/Wifi-Password-Cracker](https://github.com/SaidSec/Wifi-Password-Cracker) | 0 | Shell | Greps the WPA handshake from one device after deauth attacking and cracks it with given wordlist |
| 974 | [salahezzat120/auto_aircrack](https://github.com/salahezzat120/auto_aircrack) | 0 | Python | ⚡ Automated WiFi Handshake Capture & Cracking (for **legal lab testing only**) ⚡ |
| 975 | [santipicon/WiFi-Penetration-Testing-Lab](https://github.com/santipicon/WiFi-Penetration-Testing-Lab) | 0 | — | WPA2 Handshake Capture & Cracking |
| 976 | [shackablacka/wifi-cracking](https://github.com/shackablacka/wifi-cracking) | 0 | HTML | evil twin wifi cracking with capture portal |
| 977 | [shahnowaz/wifi-handshake-cracker](https://github.com/shahnowaz/wifi-handshake-cracker) | 0 | — | "A complete guide and command workflow for capturing and cracking WPA/WPA2 Wi-Fi handshakes using… |
| 978 | [sridhar-sec/Advanced-Cybersecurity-Toolkit](https://github.com/sridhar-sec/Advanced-Cybersecurity-Toolkit) | 0 | Python | The Advanced Cybersecurity Toolkit is a powerful command-line tool designed for penetration teste… |
| 979 | [Srihari-Narayan/WiFi-Security-Research](https://github.com/Srihari-Narayan/WiFi-Security-Research) | 0 | — | Performed research on WPA2 security, which involved capturing the Handshake packet and performing… |
| 980 | [stricklandpreston/EvilTwin](https://github.com/stricklandpreston/EvilTwin) | 0 | — | Unfinished script to automate EvilTwin Wifi Attack using the aircrack suite. |
| 981 | [Sviatko124/wifi-wordlists](https://github.com/Sviatko124/wifi-wordlists) | 0 | — | Some wordlists I created for WiFi handshake cracking.  |
| 982 | [thefat-fox/fatfox-dual-attack-tool](https://github.com/thefat-fox/fatfox-dual-attack-tool) | 0 | Python | WiFi Deauth + Evil Twin Attack Tool |
| 983 | [ThelzenGroup/wifistrike](https://github.com/ThelzenGroup/wifistrike) | 0 | Python | Offline Wi-Fi auditing toolkit — capture, extract, crack, and report on WPA/WPA2/WEP handshakes. … |
| 984 | [usmanraees614-web/Evil-Twin](https://github.com/usmanraees614-web/Evil-Twin) | 0 | — | A fake wifi detector  |
| 985 | [willlccasey/kali-wifite](https://github.com/willlccasey/kali-wifite) | 0 | Python | Wifite Wi-Fi auditor — GUI launcher with offline handshake cracking |
| 986 | [worm00dat/wifireaper](https://github.com/worm00dat/wifireaper) | 0 | — | AIO Evil Twin Attack |

## 🎯 按攻击领域分类

### WiFi 攻击

> 共 **1776** 个项目，按 Stars 降序排列。多标签项目会出现在多个分组。

| # | 项目 | Stars | 语言 | 简介 |
|---:|---|---:|---|---|
| 1 | [bettercap/bettercap](https://github.com/bettercap/bettercap) | 20,304 | Go | The Swiss Army knife for 802.11, BLE, HID, CAN-bus, IPv4 and IPv6 networks reconnaissance and MIT… |
| 2 | [SpacehuhnTech/esp8266_deauther](https://github.com/SpacehuhnTech/esp8266_deauther) | 15,109 | C | Affordable WiFi hacking platform for testing and learning |
| 3 | [wifiphisher/wifiphisher](https://github.com/wifiphisher/wifiphisher) | 14,978 | Python | The Rogue Access Point Framework |
| 4 | [brannondorsey/wifi-cracking](https://github.com/brannondorsey/wifi-cracking) | 12,742 | — | Crack WPA/WPA2 Wi-Fi Routers with Airodump-ng and Aircrack-ng/Hashcat |
| 5 | [EmenstaNougat/ESP32-BlueJammer](https://github.com/EmenstaNougat/ESP32-BlueJammer) | 8,931 | — | The ESP32-BlueJammer (Bluetooth jammer, BLE jammer, WiFi jammer, RC jammer) disrupts 2.4GHz commu… |
| 6 | [geo-tp/ESP32-Bit-Pirate](https://github.com/geo-tp/ESP32-Bit-Pirate) | 6,396 | C++ | A Hardware Hacking Tool with Web-Based CLI That Speaks Every Protocol  |
| 7 | [martin-ger/esp_wifi_repeater](https://github.com/martin-ger/esp_wifi_repeater) | 5,292 | C | A full functional WiFi NAT Router (and now also a WiFi Repeater) |
| 8 | [cifertech/ESP32-DIV](https://github.com/cifertech/ESP32-DIV) | 4,350 | C++ | ESP32DIV is a multi-purpose wireless offensive and defensive toolkit powered by an ESP32 |
| 9 | [DanMcInerney/wifijammer](https://github.com/DanMcInerney/wifijammer) | 4,323 | Python | Continuously jam all wifi clients/routers |
| 10 | [cirosantilli/china-dictatorship](https://github.com/cirosantilli/china-dictatorship) | 3,350 | HTML | 反中共政治宣传库。Anti Chinese government propaganda. 住在中国真名用户的网友请别给星星，不然你要被警察请喝茶。常见问答集，新闻集和饭店和音乐建议。卐习万岁卐。… |
| 11 | [SpacehuhnTech/WiFiDuck](https://github.com/SpacehuhnTech/WiFiDuck) | 3,345 | C++ | Wireless keystroke injection attack platform  |
| 12 | [risinek/esp32-wifi-penetration-tool](https://github.com/risinek/esp32-wifi-penetration-tool) | 3,159 | C | Exploring possibilities of ESP32 platform to attack on nearby Wi-Fi networks. |
| 13 | [P0cL4bs/WiFi-Pumpkin-deprecated](https://github.com/P0cL4bs/WiFi-Pumpkin-deprecated) | 3,150 | Python | DEPRECATED, wifipumpkin3 -> https://github.com/P0cL4bs/wifipumpkin3 |
| 14 | [7h30th3r0n3/Evil-M5Project](https://github.com/7h30th3r0n3/Evil-M5Project) | 2,887 | C++ | Evil-M5Project is an innovative tool developed for ethical  hacking and exploration of WiFi netwo… |
| 15 | [esc0rtd3w/wifi-hacker](https://github.com/esc0rtd3w/wifi-hacker) | 2,849 | Shell | Shell Script For Attacking Wireless Connections Using Built-In Kali Tools. Supports All Securitie… |
| 16 | [ankit0183/Wifi-Hacking](https://github.com/ankit0183/Wifi-Hacking) | 2,799 | Python | Cyber Security Tool For Hacking Wireless Connections Using Built-In Kali Tools. Supports All Secu… |
| 17 | [calebmadrigal/trackerjacker](https://github.com/calebmadrigal/trackerjacker) | 2,745 | Python | Like nmap for mapping wifi networks you're not connected to, plus device tracking |
| 18 | [k4m4/kickthemout](https://github.com/k4m4/kickthemout) | 2,687 | Python | 💤 Kick devices off your network by performing an ARP Spoof attack. |
| 19 | [P0cL4bs/wifipumpkin3](https://github.com/P0cL4bs/wifipumpkin3) | 2,530 | Python | Powerful framework for rogue access point attack. |
| 20 | [cifertech/nRFBox](https://github.com/cifertech/nRFBox) | 2,140 | C++ | Open-source ESP32-powered tool to scan, jam, spoof, and master BLE, Wi-Fi, and 2.4GHz networks. |
| 21 | [koutto/pi-pwnbox-rogueap](https://github.com/koutto/pi-pwnbox-rogueap) | 2,117 | Shell | Homemade Pwnbox :rocket: / Rogue AP :satellite: based on Raspberry Pi — WiFi Hacking Cheatsheets … |
| 22 | [gege-circle/.github](https://github.com/gege-circle/.github) | 2,106 | — | 这里是GitHub的草场，也是戈戈圈爱好者的交流地，主要讨论动漫、游戏、科技、人文、生活等所有话题，欢迎各位小伙伴们在此讨论趣事。This is GitHub grassland, and th… |
| 23 | [insightglacier/Dictionary-Of-Pentesting](https://github.com/insightglacier/Dictionary-Of-Pentesting) | 2,089 | Shell | Dictionary collection project such as Pentesing, Fuzzing, Bruteforce and BugBounty. 渗透测试、SRC漏洞挖掘、… |
| 24 | [cifertech/RF-Clown](https://github.com/cifertech/RF-Clown) | 1,945 | C++ | BLE and Bluetooth Jammer with nRF24L01 and ESP32 |
| 25 | [JesseCHale/HaleHound-CYD](https://github.com/JesseCHale/HaleHound-CYD) | 1,926 | — | ESP32-DIV HaleHound Edition for Cheap Yellow Display - Multi-protocol offensive security toolkit |
| 26 | [samdenty/Wi-PWN](https://github.com/samdenty/Wi-PWN) | 1,746 | C | ESP8266 firmware for performing deauthentication attacks, with ease. |
| 27 | [xdavidhu/mitmAP](https://github.com/xdavidhu/mitmAP) | 1,692 | Python | 📡 A python program to create a fake AP and sniff data. |
| 28 | [spacehuhn/esp8266_beaconSpam](https://github.com/spacehuhn/esp8266_beaconSpam) | 1,393 | C++ | Creates up to a thousand WiFi access points with custom SSIDs. |
| 29 | [xploitstech/Xteam](https://github.com/xploitstech/Xteam) | 1,365 | Python | Xteam All in one Instagram,Android,phishing osint and wifi hacking tool available  |
| 30 | [7h30th3r0n3/Raspyjack](https://github.com/7h30th3r0n3/Raspyjack) | 1,343 | Python | Small offensive network toolkit for Raspberry Pi (+ Waveshare 1.44″ LCD HAT) and Cardputer Zero i… |
| 31 | [TermuxHackz/wifi-hacker](https://github.com/TermuxHackz/wifi-hacker) | 1,340 | Shell | Shell Script For Attacking Wireless Connections Using Built-In Kali Tools. Supports All Securitie… |
| 32 | [hubert3/iSniff-GPS](https://github.com/hubert3/iSniff-GPS) | 1,287 | Python | Passive sniffing tool for capturing and visualising WiFi location data disclosed by iOS devices |
| 33 | [xchwarze/wifi-pineapple-cloner](https://github.com/xchwarze/wifi-pineapple-cloner) | 1,276 | Shell | Port WiFi Pineapple NANO/TETRA in generic hardware |
| 34 | [blackhillsinfosec/WifiForge](https://github.com/blackhillsinfosec/WifiForge) | 1,237 | Python | WifiForge is a tool developed by Black Hills InfoSec to help train Pentesters on different Wi-Fi … |
| 35 | [daviddias/awesome-hacking-locations](https://github.com/daviddias/awesome-hacking-locations) | 1,140 | — | :computer: :coffee: List of Awesome Hacking Locations, organised by Country and City, listing if … |
| 36 | [hash3liZer/WiFiBroot](https://github.com/hash3liZer/WiFiBroot) | 1,135 | Python | A Wireless (WPA/WPA2) Pentest/Cracking tool. Captures & Crack 4-way handshake and PMKID key. Also… |
| 37 | [sensepost/mana](https://github.com/sensepost/mana) | 1,118 | HTML | *DEPRECATED* mana toolkit for wifi rogue AP attacks and MitM |
| 38 | [W0rthlessS0ul/nRF24_jammer](https://github.com/W0rthlessS0ul/nRF24_jammer) | 1,022 | C | The nRF24 jammer is a powerful tool that requires an ESP32 and configurable numbers of NRF24 modu… |
| 39 | [SpacehuhnTech/DeauthDetector](https://github.com/SpacehuhnTech/DeauthDetector) | 993 | C++ | Detect deauthentication frames using an ESP8266 |
| 40 | [flashnuke/wifi-deauth](https://github.com/flashnuke/wifi-deauth) | 952 | Python | A deauth attack that disconnects all devices from the target wifi network (2.4Ghz & 5Ghz), WPA3 a… |
| 41 | [FLOCK4H/Freeway](https://github.com/FLOCK4H/Freeway) | 944 | Python | WiFi Penetration Testing & Auditing Tool |
| 42 | [3xploitGuy/lazyaircrack](https://github.com/3xploitGuy/lazyaircrack) | 929 | Shell | Automated tool for WiFi hacking. |
| 43 | [mkdirlove/WI-TOOLKIT](https://github.com/mkdirlove/WI-TOOLKIT) | 855 | Python | Hack WiFi in Termux ( ROOTED DEVICES ONLY) |
| 44 | [kumpulanremaja/wifi](https://github.com/kumpulanremaja/wifi) | 850 | Shell | Tutorial Cara Bobol Hack WIFI dengan termux Android jaringan yang dienkripsi WEP, WPA, dan WPS se… |
| 45 | [unixpickle/JamWiFi](https://github.com/unixpickle/JamWiFi) | 796 | Objective-C | A GUI, easy to use WiFi network jammer for Mac OS X |
| 46 | [Cyber-Dioxide/Wifi-Brute](https://github.com/Cyber-Dioxide/Wifi-Brute) | 780 | Python | A tool to crack a wifi password with a help of wordlist. This may take long to crack a wifi depen… |
| 47 | [aydinnyunus/WifiPassword-Stealer](https://github.com/aydinnyunus/WifiPassword-Stealer) | 778 | Python | Get All Registered Wifi Passwords from Target Computer. |
| 48 | [landy22granatt/Kumpulan-Script-Termux](https://github.com/landy22granatt/Kumpulan-Script-Termux) | 776 | Python | Ok, Langsung Saja Ke Materi. Sesuai Judul, Disini Saya Akan Memberikan Kumpulan Script Termux Yan… |
| 49 | [ricardojoserf/wifi-pentesting-guide](https://github.com/ricardojoserf/wifi-pentesting-guide) | 760 | Python | WiFi Penetration Testing Guide |
| 50 | [HKSSY/Drone-Hacking-Tool](https://github.com/HKSSY/Drone-Hacking-Tool) | 703 | Python | Drone Hacking Tool is a GUI tool that works with a USB Wifi adapter and HackRF One for hacking dr… |
| 51 | [drau6/KawaiiDeauther](https://github.com/drau6/KawaiiDeauther) | 670 | Shell | Jam all wifi clients/routers. |
| 52 | [aress31/wirespy](https://github.com/aress31/wirespy) | 660 | Shell | Framework designed to automate various wireless networks attacks (the project was presented on Pe… |
| 53 | [sensepost/hostapd-mana](https://github.com/sensepost/hostapd-mana) | 641 | C | SensePost's modified hostapd for wifi attacks. |
| 54 | [kalanda/esp8266-sniffer](https://github.com/kalanda/esp8266-sniffer) | 631 | C++ | An easy experiment which uses the ESP8266 wifi module to look for near smartphones around you |
| 55 | [AleksaMCode/WiFi-password-stealer](https://github.com/AleksaMCode/WiFi-password-stealer) | 610 | PowerShell | Simple Windows and Linux keystroke injection tool that exfiltrates stored WiFi data (SSID and pas… |
| 56 | [Taoviqinvicible/Tools-termux](https://github.com/Taoviqinvicible/Tools-termux) | 606 | — | 1.[Script Termux] -Cmatrix *apt-get update *apt-get upgrade *apt-get install nmap *apt-get instal… |
| 57 | [WiPi-Hunter/PiDense](https://github.com/WiPi-Hunter/PiDense) | 569 | Python | 🍓📡🍍Monitor illegal wireless network activities. (Fake Access Points), (WiFi Threats: KARMA Attack… |
| 58 | [akashblackhat/wifi-hacking.py](https://github.com/akashblackhat/wifi-hacking.py) | 555 | Python | Cyber Security Tool For Hacking Wireless Connections Using Built-In Kali Tools. Supports All Secu… |
| 59 | [adamff-dev/WiFi-Spam](https://github.com/adamff-dev/WiFi-Spam) | 537 | Shell | :email::satellite: Spam thousands of WiFi access points with custom SSIDs |
| 60 | [sevagas/swap_digger](https://github.com/sevagas/swap_digger) | 535 | Shell |  swap_digger is a tool used to automate Linux swap analysis during post-exploitation or forensics… |
| 61 | [clu3bot/owt](https://github.com/clu3bot/owt) | 505 | Shell | Update Version 3.1 added free SMS messaging. |
| 62 | [priyankgada/The-Complete-Practical-Certified-Ethical-Hacking-Course-in-English](https://github.com/priyankgada/The-Complete-Practical-Certified-Ethical-Hacking-Course-in-English) | 490 | — | Welcome this comprehensive course on Ethical Hacking! This course assumes you have NO prior knowl… |
| 63 | [theahmadov/NIVOS](https://github.com/theahmadov/NIVOS) | 483 | Python | NIVOS is a hacking tool that allows you to scan deeply , crack wifi, see people on your network. … |
| 64 | [uday-khan/Termux](https://github.com/uday-khan/Termux) | 463 | — | KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau hp lu gw… |
| 65 | [whatotter/pwnhyve](https://github.com/whatotter/pwnhyve) | 460 | Python | A low cost, jack-of-all-trades hacking tool, taking inspiration from FlipperZero and P4wnP1, usin… |
| 66 | [tesa-klebeband/ESP32-Deauther](https://github.com/tesa-klebeband/ESP32-Deauther) | 453 | C++ | A project for the ESP32 that allows you to deauthenticate stations connected to WiFi networks |
| 67 | [0x0XDev/JamWiFi](https://github.com/0x0XDev/JamWiFi) | 442 | Swift | A GUI, easy to use WiFi network jammer for Mac OS X |
| 68 | [r4ulcl/WiFiChallengeLab-docker](https://github.com/r4ulcl/WiFiChallengeLab-docker) | 442 | Shell | Virtualized Wi-Fi pentesting laboratory without the need for physical Wi-Fi cards, using mac80211… |
| 69 | [visualapproach/WiFi-remote-for-Bestway-Lay-Z-SPA](https://github.com/visualapproach/WiFi-remote-for-Bestway-Lay-Z-SPA) | 417 | C++ | Hack - ESP8266 as WiFi remote control for Bestway Lay-Z spa Helsinki |
| 70 | [p3tr0s/PhiSiFi](https://github.com/p3tr0s/PhiSiFi) | 414 | C++ | WiFi Hacking with an ESP8266 - Deauth combined with Evil Twin attack  |
| 71 | [TheBATeam/Batch-WI-FI-Brute-Forcer](https://github.com/TheBATeam/Batch-WI-FI-Brute-Forcer) | 394 | Batchfile | This project is based upon the trick that, how to hack WI-FI with CMD. The main purpose behind, c… |
| 72 | [cirosantilli/china-dictatroship-7](https://github.com/cirosantilli/china-dictatroship-7) | 391 | HTML | 反中共政治宣传库。Anti Chinese government propaganda. https://github.com/cirosantilli/china-dictatorship 的… |
| 73 | [DH-AL/Dh-All](https://github.com/DH-AL/Dh-All) | 389 | Python | This is a package of all hacking tools., This tool contain over 300+ Advance and professional Hac… |
| 74 | [W0rthlessS0ul/FZ_nRF24_jammer](https://github.com/W0rthlessS0ul/FZ_nRF24_jammer) | 388 | C | The Flipper Zero nRF24 jammer is a powerful tool that requires an Flipper Zero and nRF24 module t… |
| 75 | [grugnoymeme/flipperzero-CLI-wifi-cracker](https://github.com/grugnoymeme/flipperzero-CLI-wifi-cracker) | 379 | Python | CLI - Analyze WPA/WPA2 handshakes from FlipperZero's captured .pcaps to find out the WiFi Passwords. |
| 76 | [EmenstaNougat/WiFiX-DualBand-Deauther](https://github.com/EmenstaNougat/WiFiX-DualBand-Deauther) | 378 | Batchfile | A 2.4GHz and 5GHZ Deauther, based on a RTL8720dn BW16 dev kit. |
| 77 | [zszszszsz/.config](https://github.com/zszszszsz/.config) | 372 | Shell | # # Automatically generated file; DO NOT EDIT. # OpenWrt Configuration # CONFIG_MODULES=y CONFIG_… |
| 78 | [Esser50K/EvilTwinFramework](https://github.com/Esser50K/EvilTwinFramework) | 365 | Python | A framework for pentesters that facilitates evil twin attacks as well as exploiting other wifi vu… |
| 79 | [V0lk3n/WirelessPentesting-CheatSheet](https://github.com/V0lk3n/WirelessPentesting-CheatSheet) | 359 | — | This repository contain a CheatSheet for OSWP & WiFi Cracking. |
| 80 | [U7P4L-IN/WIFI-HACKING](https://github.com/U7P4L-IN/WIFI-HACKING) | 351 | Python | ⚡Cyber Security Tool For Hacking Wireless Connections Using Built-In Kali Tools. Supports All Sec… |
| 81 | [rfquack/RFQuack](https://github.com/rfquack/RFQuack) | 350 | C++ | RFQuack: the versatile RF-analysis tool that quacks! |
| 82 | [xdavidhu/probeSniffer](https://github.com/xdavidhu/probeSniffer) | 342 | Python | 🔍 A tool for sniffing unencrypted wireless probe requests from devices. |
| 83 | [warengonzaga/wifi-passview](https://github.com/warengonzaga/wifi-passview) | 341 | Batchfile | An open source batch script based WiFi Passview for Windows! |
| 84 | [tnt-wolve/ch3r0](https://github.com/tnt-wolve/ch3r0) | 333 | — | Hackingtool Menu 🧰 AnonSurf Information Gathering Password Attack Wireless Attack SQL Injection T… |
| 85 | [NORMA-Inc/AtEar](https://github.com/NORMA-Inc/AtEar) | 330 | JavaScript | Wireless Hacking, WiFi Security, Vulnerability Analyzer, Pentestration |
| 86 | [Alexxdal/ESP32WifiPhisher](https://github.com/Alexxdal/ESP32WifiPhisher) | 327 | C | Headless Wireless Penetration Testing on ESP32 |
| 87 | [EmenstaNougat/BlueJammer-V2](https://github.com/EmenstaNougat/BlueJammer-V2) | 322 | Batchfile | BlueJammer-V2 is a two-board RF research platform combining an ESP32 jamming engine with a BW16 5… |
| 88 | [MrSanZz/pandora](https://github.com/MrSanZz/pandora) | 322 | Python | -= Has features =-  =============== -DDoS -Web Scanning -Phone Hunter -CCTV Hunter -Deface -Mass … |
| 89 | [FlyingIceyyds/BW16-Tools](https://github.com/FlyingIceyyds/BW16-Tools) | 319 | C++ | 基于Ai-Thinker BW16-Kit RTL8720DN 的无线安全测试工具。包含WIFI功能：解除身份认证(Deauth)，信道干扰(Channel Interference)，Deau… |
| 90 | [Teapot174/ESP-HACK](https://github.com/Teapot174/ESP-HACK) | 313 | C++ | Open Source ESP32 Project for Pentesting. |
| 91 | [adde88/openwrt-useful-tools](https://github.com/adde88/openwrt-useful-tools) | 308 | Standard ML | A repo containing different tools compiled specifically for the Hak5 WiFi Pineapple MK6 and MK7. |
| 92 | [o7-machinehum/flipper-blackhat](https://github.com/o7-machinehum/flipper-blackhat) | 305 | Python | Linux based WiFi pentesting device for the Flipper Zero. |
| 93 | [thehackingsage/fluxion](https://github.com/thehackingsage/fluxion) | 292 | HTML | WiFi Cracking Tool (Using Evil Twin Attack) With Some Modification. (Only For Legal Purposes) |
| 94 | [psyb0t/piraterf](https://github.com/psyb0t/piraterf) | 291 | Go | PIrateRF transforms your Raspberry Pi Zero W into a portable RF signal generator that spawns its … |
| 95 | [adamff-dev/PwrDeauther](https://github.com/adamff-dev/PwrDeauther) | 285 | Shell | :zap: Deauth a specific WiFi access point or an entire channel |
| 96 | [SkypLabs/probequest](https://github.com/SkypLabs/probequest) | 280 | Python | Toolkit for Playing with Wi-Fi Probe Requests |
| 97 | [veerendra2/wifi-deauth-attack](https://github.com/veerendra2/wifi-deauth-attack) | 280 | Python | An automated script for deauthentication attack  |
| 98 | [mmMikeKn/ESP32-WiFi-tool](https://github.com/mmMikeKn/ESP32-WiFi-tool) | 276 | C | ESP32 WiFi tool (router, sniffer, deauther) |
| 99 | [Ymsniper/KTO](https://github.com/Ymsniper/KTO) | 273 | Rust | Rust WiFi deauth tool that kicks every device off a target network except the MACs you whitelist,… |
| 100 | [AnonymousAt3/piracy](https://github.com/AnonymousAt3/piracy) | 272 | Shell | Automated WIFI Hacking Tool |
| 101 | [ESP-EOS/ESP32-WiFi-Sniffer](https://github.com/ESP-EOS/ESP32-WiFi-Sniffer) | 272 | C++ | Simple WiFi sniffer for boards based on the Espressif Systems ESP32 module |
| 102 | [sankethj/ZiFi](https://github.com/sankethj/ZiFi) | 267 | C++ | Wifi hacking tool using ESP8266 ( Evil-twin method ) |
| 103 | [brannondorsey/sniff-probes](https://github.com/brannondorsey/sniff-probes) | 254 | Shell | Plug-and-play bash script for sniffing 802.11 probes requests :nose:  |
| 104 | [DeaDHackS/WiFiSpy](https://github.com/DeaDHackS/WiFiSpy) | 247 | Python | The best WiFi spy avalaible for hire! Made for hackers, for hackers |
| 105 | [WiPi-Hunter/PiSavar](https://github.com/WiPi-Hunter/PiSavar) | 241 | Python | 📡 🍍Detects activities of PineAP module and starts deauthentication attack (for fake access points… |
| 106 | [justcallmekoko/MarauderCentauri](https://github.com/justcallmekoko/MarauderCentauri) | 238 | C++ | A suite of WiFi/Bluetooth offensive and defensive tools for the ESP32 and ESP8266 |
| 107 | [itsdarklikehell-interactive/pwnagotchi-plugins](https://github.com/itsdarklikehell-interactive/pwnagotchi-plugins) | 234 | Python | Collectie van Pwnagotchi-plugins voor Wi-Fi auditing en pentesting op Raspberry Pi. |
| 108 | [ente0/hashCrack](https://github.com/ente0/hashCrack) | 226 | Python | Interactive Python CLI that wraps Hashcat with guided menus for wordlist, rule-based, brute-force… |
| 109 | [hash3liZer/wifijammer](https://github.com/hash3liZer/wifijammer) | 226 | Python | Wireless Jammer to Disconnect Nearby Access-Points and Stations.  |
| 110 | [SHUR1K-N/WiFi-Mangoapple-Resources](https://github.com/SHUR1K-N/WiFi-Mangoapple-Resources) | 219 | — | Helpful resources regarding the cheap DIY Wi-Fi Pineapple, AKA Wi-Fi Mangoapple to help with supp… |
| 111 | [mRFWq7LwNPZjaVv5v6eo/cihna-dictattorshrip-8](https://github.com/mRFWq7LwNPZjaVv5v6eo/cihna-dictattorshrip-8) | 217 | HTML | 反中共政治宣传库。Anti Chinese government propaganda. https://github.com/cirosantilli/china-dictatorship 的… |
| 112 | [panbinibn/OpenPacketFix_](https://github.com/panbinibn/OpenPacketFix_) | 215 | — | 大陆修宪香港恶法台湾武统朝鲜毁约美中冷战等都是王沪宁愚弄习思想极左命运共同体的大策划中共窃国这半个多世纪所犯下的滔天罪恶，前期是毛泽东策划的，中期6.4前后是邓小平策划的，黄牛数据分析后期是毛的… |
| 113 | [hak5peaks/Hackers-Nightlight](https://github.com/hak5peaks/Hackers-Nightlight) | 211 | C | Turning smart lights into Wifi Hacking implants.  |
| 114 | [BlackTechX011/DeautherX](https://github.com/BlackTechX011/DeautherX) | 210 | C | An open-source ESP8266_Deauther with customizable Evil Twin attack, and WiFi signal strength chec… |
| 115 | [PentHertz/grimoire](https://github.com/PentHertz/grimoire) | 206 | Python | Offensive knowledge, offline. One search box for every playbook. |
| 116 | [flancast90/wifi-bf](https://github.com/flancast90/wifi-bf) | 205 | Python | A (completely native) python3 wifi brute-force attack using the 100k most common passwords (2021) |
| 117 | [grugnoymeme/flipperzero-GUI-wifi-cracker](https://github.com/grugnoymeme/flipperzero-GUI-wifi-cracker) | 202 | Python | GUI - Analyze WPA/WPA2 handshakes from FlipperZero's captured .pcaps to find out the WiFi Passwords. |
| 118 | [digiampietro/hacking-gemtek](https://github.com/digiampietro/hacking-gemtek) | 201 | Shell | hacking-gemtek is a reverse engineering project for a Gemtek home router (WVRTM-127ACN), distribu… |
| 119 | [Rizalcahdemak/akun-termux](https://github.com/Rizalcahdemak/akun-termux) | 198 | — | Skip to content arysandi/kumpulan kode di termux Created 3 years ago • Report abuse Code Revision… |
| 120 | [Gurpreet06/Wifi-Crack](https://github.com/Gurpreet06/Wifi-Crack) | 193 | Python | Python Tool to automate WIFI attacks to obtain handshake, PMKID attack, make networks temporarily… |
| 121 | [wifiphisher/roguehostapd](https://github.com/wifiphisher/roguehostapd) | 191 | C | Hostapd fork including Wi-Fi attacks and providing Python bindings with ctypes. |
| 122 | [B3ND1X/air-script](https://github.com/B3ND1X/air-script) | 186 | Shell | Air Script is a powerful Wi-Fi auditing tool with optional email alerts for captured handshakes. |
| 123 | [ElectronicCats/BomberCat](https://github.com/ElectronicCats/BomberCat) | 186 | HTML | BomberCat is the latest security tool that combines the most common card technologies: NFC techno… |
| 124 | [pineapple-pager-projects/pineapple_pager_loki](https://github.com/pineapple-pager-projects/pineapple_pager_loki) | 184 | Lua | LAN Orchestrated Key Infiltrator - Autonomous network recon payload for the Hak5 WiFi Pineapple P… |
| 125 | [ElectronicCats/Minino](https://github.com/ElectronicCats/Minino) | 183 | C++ | Minino is an original multiprotocol and multiband board made for sniffing, communicating, and att… |
| 126 | [dkyazzentwatwa/cypher-jammer-mini](https://github.com/dkyazzentwatwa/cypher-jammer-mini) | 182 | C++ | Tiny WiFi + Bluetooth Jammer w/ ESP32-C3 SuperMini |
| 127 | [hacker3983/pyrit-installer](https://github.com/hacker3983/pyrit-installer) | 181 | Python | This shows how to install pyrit for fluxion or other wifi hacking tools if you don't have pip ins… |
| 128 | [ANDRVV/gapcast](https://github.com/ANDRVV/gapcast) | 180 | Go | 📡 802.11 broadcast analyzer & injector |
| 129 | [wlmosv-png/wpaforge](https://github.com/wlmosv-png/wpaforge) | 180 | Java | 智能字典破解 WiFi：按 SSID 与线索现场生成候选、逐条真实关联验证；含 WPS PIN、局域网侦察、.cap/.hc22000 离线校验、信道诊断；收尾自动写回目标原网络配置并回读确认。… |
| 130 | [devilvimalkumar/wibr_pro](https://github.com/devilvimalkumar/wibr_pro) | 171 | — | Wibr+ pro version for WiFi bruteforce hacking apk With dictionary attack tools. Easily hack any W… |
| 131 | [ExploiTR/DeAutherDroid](https://github.com/ExploiTR/DeAutherDroid) | 170 | Java | Additional android app for SpaceHunn's ESP8266 DeAuther. |
| 132 | [W00t3k/Awesome-WiFi-Hacking](https://github.com/W00t3k/Awesome-WiFi-Hacking) | 170 | — | Wifi Hacking |
| 133 | [ZKAW/wifi-deauther](https://github.com/ZKAW/wifi-deauther) | 170 | Python | 802.11 deauthentication tool for Wi-Fi security testing and research |
| 134 | [Whomrx666/Wifi-crackerX](https://github.com/Whomrx666/Wifi-crackerX) | 167 | Python | Wifi-crackerX is a tool for hacking a WPS/WPA/WPA2 Networks |
| 135 | [0xless/433mhz_jam](https://github.com/0xless/433mhz_jam) | 163 | C++ | Simple WiFi controlled 433Mhz radio jammer based on ESP32/ESP8266 and FS1000A |
| 136 | [latonita/tenda-reverse](https://github.com/latonita/tenda-reverse) | 159 | Shell | Reverse engineering, getting root access to Tenda MW6 wifi mesh router |
| 137 | [aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal) | 158 | C++ | A project that demonstrates how to execute an Evil Twin WiFi Hacking attack using the ESP32. The … |
| 138 | [TermuxHackz/wifi-cracker](https://github.com/TermuxHackz/wifi-cracker) | 157 | Python | Wifi-Cracker.py to Hack WPS/WPA/WPA2 Networks |
| 139 | [Don-No7/Hack-SQL](https://github.com/Don-No7/Hack-SQL) | 153 | — | -- -- File generated with SQLiteStudio v3.2.1 on Sun Feb 7 14:58:28 2021 -- -- Text encoding used… |
| 140 | [andrewhilts/snifflab](https://github.com/andrewhilts/snifflab) | 152 | Python | Scripts to create your own MITM'ing, packet sniffing WiFi access point |
| 141 | [FLOCK4H/AtomDucky](https://github.com/FLOCK4H/AtomDucky) | 150 | Python | WiFi Rubber Ducky with a web interface using CircuitPython |
| 142 | [MGz-Staze/tools-Termux](https://github.com/MGz-Staze/tools-Termux) | 150 | — | Cara Update dan Upgrade Termux  pkg update && pkg upgrade  Tools Pendukung untuk Termux  Tools pe… |
| 143 | [Matrix07ksa/EvilNet](https://github.com/Matrix07ksa/EvilNet) | 149 | Python | Network Attack  wifi attack vlan attack arp attack Mac Attack Attack revealed etc../ |
| 144 | [xchwarze/AR150-WiFiPineapple](https://github.com/xchwarze/AR150-WiFiPineapple) | 143 | — | Converting your AR150 to a Wifi Pineapple NANO |
| 145 | [jspw/Crack-WIFI-WPA2](https://github.com/jspw/Crack-WIFI-WPA2) | 141 | C | Get handshake and crack wpa/wpa2 security wifi passwords |
| 146 | [Danyalkhattak/wifi-attack-tool](https://github.com/Danyalkhattak/wifi-attack-tool) | 138 | Python | Wi-Fi Attack Automation Tool for Kali Linux and Termux automates Wi-Fi attacks like Deauthenticat… |
| 147 | [phenotypic/WiFiCrack](https://github.com/phenotypic/WiFiCrack) | 138 | Shell | Automated Wi-Fi cracker for macOS |
| 148 | [Mxtiv/BlueJammer](https://github.com/Mxtiv/BlueJammer) | 136 | C++ | Simple BlueJammer using ESP32 and nRF24L01. For educational purposes only! |
| 149 | [T-vK/alexa-jammer](https://github.com/T-vK/alexa-jammer) | 135 | C++ | Jamming the Wifi connection and microphones of all Amazon Echo and Google Home devices surroundin… |
| 150 | [zpc1314521/PCL2](https://github.com/zpc1314521/PCL2) | 135 | — | [stays mad] 反PCL宣传库。Anti PCL propaganda. 大陆修宪香港恶法台湾武统朝鲜毁约美中冷战等都是王沪宁愚弄习思想极左命运共同体的大策划中共窃国这半个多世纪所犯下的… |
| 151 | [mjlee111/esp32_wifi_deauther](https://github.com/mjlee111/esp32_wifi_deauther) | 132 | C++ | A simple ESP32 based wifi hacking tool. Supports mini oled display & test circuit available. |
| 152 | [pineapple-pager-projects/pineapple_pager_pagergotchi](https://github.com/pineapple-pager-projects/pineapple_pager_pagergotchi) | 132 | Python | Pwnagotchi ported to the hak5 wifi pineapple pager with some added features, uses pineAP |
| 153 | [Kidd3n/WifiPwnedd](https://github.com/Kidd3n/WifiPwnedd) | 131 | PHP | Tool for Wifi Network Attacks  |
| 154 | [ivan-sincek/evil-twin](https://github.com/ivan-sincek/evil-twin) | 129 | PHP | Learn how to set up a fake authentication web page on a fake WiFi network. |
| 155 | [EmenstaNougat/C3Mini-BlueJammer](https://github.com/EmenstaNougat/C3Mini-BlueJammer) | 125 | — | The C3Mini-BlueJammer (MINI FORMFACTOR) (Bluetooth jammer, BLE jammer, WiFi jammer, RC jammer) di… |
| 156 | [altaga/Portable-Hacking-Station-RPI](https://github.com/altaga/Portable-Hacking-Station-RPI) | 123 | — | Station to perform WiFi network audits, using Raspberry Pi Zero W or Raspberry Pi 3, with connect… |
| 157 | [JakeSwiz/flock-you-wifi-recon](https://github.com/JakeSwiz/flock-you-wifi-recon) | 118 | C++ | ESP32 firmware that catches Flock Safety ALPRs by the WiFi probes they spray trying to phone home… |
| 158 | [ezhil56x/Wifi-Deauthentication-Tool](https://github.com/ezhil56x/Wifi-Deauthentication-Tool) | 117 | Shell | Wi-Fi Deauthentication Tool is a command-line utility for educational purposes, enabling users to… |
| 159 | [Geovation/wifispy](https://github.com/Geovation/wifispy) | 115 | Python | Sniff Wifi traffic, log device addresses. |
| 160 | [bkerler/DroneID](https://github.com/bkerler/DroneID) | 113 | Python | OpenDrone ID sniffer/spoofer for Bluetooth + WIFI |
| 161 | [HighTeckMan/wifijammer](https://github.com/HighTeckMan/wifijammer) | 110 | Python | Raspberry Pi Wifi Jammer Project |
| 162 | [hiteshchoudhary/Airvengers](https://github.com/hiteshchoudhary/Airvengers) | 110 | Python | A GUI to pentest wifi Network, based on Aircrack-ng tools |
| 163 | [aegis1980/WifiHotSpot](https://github.com/aegis1980/WifiHotSpot) | 108 | Java | A bit of a hack I wrote to fix Trigger's issue with not controlling wifi hotspot in Oreo. Turned … |
| 164 | [zall-4RT/kumpulan-code-termuxs-lenkap](https://github.com/zall-4RT/kumpulan-code-termuxs-lenkap) | 108 | — | termux KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau h… |
| 165 | [Manisso/wifisky](https://github.com/Manisso/wifisky) | 107 | Python | wifisky Python script for pentesting wireless networks |
| 166 | [justcallmekoko/ESP8266_Deauth_All](https://github.com/justcallmekoko/ESP8266_Deauth_All) | 106 | C++ | Arduino code for your ESP8266. Deauthenticate all clients from all access points |
| 167 | [KatzeMau/wifite2-requirements](https://github.com/KatzeMau/wifite2-requirements) | 105 | Shell | This bash script will install wifite2 and its other tools Pyrit, bully, wireshark, hcxtools, hcxd… |
| 168 | [SValkanov/wifivoid](https://github.com/SValkanov/wifivoid) | 105 | Ruby | Ruby script for continuously jam all wifi clients and access points within range |
| 169 | [NickJongens/PiEvilTwin](https://github.com/NickJongens/PiEvilTwin) | 103 | HTML | Raspberry Pi WiFi Evil Twin Captive Portal  |
| 170 | [bad-antics/nullsec-pineapple-suite](https://github.com/bad-antics/nullsec-pineapple-suite) | 102 | Shell | 96+ WiFi Pineapple Pager payloads across 13 categories \| Attack, Recon, Capture, Stealth, Interc… |
| 171 | [oblique/wificurse](https://github.com/oblique/wificurse) | 102 | C | WiFi Jamming tool |
| 172 | [DevKitty-io/Nugget-Invader](https://github.com/DevKitty-io/Nugget-Invader) | 101 | C | WiFi Attack + Recon Suite for the ESP8266 WiFi Nugget |
| 173 | [iamhellaweiri/EXPLOIT-FRAMEWORK-v1.0](https://github.com/iamhellaweiri/EXPLOIT-FRAMEWORK-v1.0) | 100 | Python | EXPLOIT-FRAMEWORK is a very powerfull hacking tool and have dangerous hacks like  Payload Creator… |
| 174 | [tzun4mi/android-hack-pack](https://github.com/tzun4mi/android-hack-pack) | 98 | — | FaceNiff latest  Droidsheep APK zAnti APK DroidJack dSploit APK SpyMax v2  Spynote v6.4. dendroid… |
| 175 | [LxveAce/cyber-controller](https://github.com/LxveAce/cyber-controller) | 97 | Python | The all-in-one security hardware controller for cyberdecks & field deployments — flash, control &… |
| 176 | [ThomDietrich/SenseoWifi](https://github.com/ThomDietrich/SenseoWifi) | 96 | C++ | Wifi'ify the Senseo coffee maker. Circuit and firmware for an internal Senseo hack to monitor and… |
| 177 | [Cyb0r9/network-attacker](https://github.com/Cyb0r9/network-attacker) | 95 | Shell | Programmed For Penetration Testing Beginners . This Program Based on Mdk3 . "WiFi Stress Testing … |
| 178 | [k0r0pt/Project-Tauro](https://github.com/k0r0pt/Project-Tauro) | 95 | Java | A Router WiFi key recovery/cracking tool with a twist. |
| 179 | [majdsassi/Pico-WIFI-Duck](https://github.com/majdsassi/Pico-WIFI-Duck) | 95 | Python | Pico WiFi Duck is a project that enables the emulation of a USB Rubber Ducky over Wi-Fi using the… |
| 180 | [rofl0r/oneshot](https://github.com/rofl0r/oneshot) | 95 | Python | try a single WPS pin/pixiedust attack with wpa_supplicant |
| 181 | [xchwarze/wifi-pineapple-cloner-builds](https://github.com/xchwarze/wifi-pineapple-cloner-builds) | 94 | — | Build repo from Universal Wifi pineapple hardware cloner |
| 182 | [DarkSyntax7/Wifi-Jammer](https://github.com/DarkSyntax7/Wifi-Jammer) | 93 | Shell | Tool to Jam Full WiFi Network Near-You! |
| 183 | [TW-D/WiFi-Pineapple-MK7_REST-Client](https://github.com/TW-D/WiFi-Pineapple-MK7_REST-Client) | 92 | Ruby | WiFi Hacking Workflow with WiFi Pineapple Mark VII API |
| 184 | [hugorezende/nRF24L01-WiFi-Jammer](https://github.com/hugorezende/nRF24L01-WiFi-Jammer) | 91 | C++ | Code to create some noise with nRF24L01 and interfere on the 2.4GHz spectrum |
| 185 | [sh1n3sec/WiCrackFi](https://github.com/sh1n3sec/WiCrackFi) | 90 | Python | Python Script to help/automate the WiFi hacking exercises. |
| 186 | [whxitte/white-netkit](https://github.com/whxitte/white-netkit) | 89 | Python | This is  a multipurpose tool which is useful in networking or network hacking. |
| 187 | [TechnicalUserX/batch_wifi_brute_forcer](https://github.com/TechnicalUserX/batch_wifi_brute_forcer) | 88 | Batchfile | An active attack tool against Wi-Fi networks with internal CMD commands |
| 188 | [ericpd/mr.wifibrute](https://github.com/ericpd/mr.wifibrute) | 87 | C | Get handshake and crack wpa/wpa2 security wifi passwords  |
| 189 | [trmxvibs/wifi-audit-tool](https://github.com/trmxvibs/wifi-audit-tool) | 87 | Python | A user-friendly command-line toolkit for WiFi network scanning, handshake capture, and vulnerabil… |
| 190 | [aleen42/hack-wifi](https://github.com/aleen42/hack-wifi) | 85 | Shell | :gun: a wifi hacker tool |
| 191 | [Kalihackz/Wifi_Tool](https://github.com/Kalihackz/Wifi_Tool) | 85 | Python | This is a python3 tool for scanning nearby Wifi and connecting to it either by normal manual pass… |
| 192 | [adityashrm21/RaspberryPi-Packet-Sniffer](https://github.com/adityashrm21/RaspberryPi-Packet-Sniffer) | 84 | Shell | An HTTP and HTTPS sniffing tool created using a Raspberry Pi |
| 193 | [mgp25/Probe-Hunter](https://github.com/mgp25/Probe-Hunter) | 83 | Python | Probe Request sniffer + Wigle |
| 194 | [flankerhqd/wifimonster](https://github.com/flankerhqd/wifimonster) | 82 | Python | Wifi sniffing and hijacking tool |
| 195 | [NSM-Barii/NetCracker](https://github.com/NSM-Barii/NetCracker) | 82 | Python | WiFi Hacking Suite |
| 196 | [colonelpanichacks/Esp32-oui-sniffer](https://github.com/colonelpanichacks/Esp32-oui-sniffer) | 81 | C++ | BLE/WiFi detection over mesh |
| 197 | [bad-antics/nullsec](https://github.com/bad-antics/nullsec) | 79 | Shell | 💀 NullSec — Offensive Security Framework \| 200+ tools, AI lab, mesh net, WiFi Pineapple, Flipper… |
| 198 | [LinkClink/Rainbow-Wifi-Hack-Utility-Android](https://github.com/LinkClink/Rainbow-Wifi-Hack-Utility-Android) | 79 | Java |  The program implements brute Wi-Fi network method on platform Android |
| 199 | [mahdamin/esp-idf-injection-ng](https://github.com/mahdamin/esp-idf-injection-ng) | 79 | C | Raw 802.11 frame injection on ESP-IDF v5+/v6+ via a one-command objcopy --weaken-symbol patch. En… |
| 200 | [momenbasel/AutoWIFI](https://github.com/momenbasel/AutoWIFI) | 79 | Python | Wireless penetration testing framework. Automates WPA/WPA2/WEP/WPS attacks - recon to exploitatio… |
| 201 | [shinyxn/ZeroTwin](https://github.com/shinyxn/ZeroTwin) | 79 | C++ | ESP8266 EvilTwin & deauther all-in-one WiFi pen-testing tools |
| 202 | [ShlomiRex/wifi-deauth-rpi-wardrive](https://github.com/ShlomiRex/wifi-deauth-rpi-wardrive) | 79 | Python | Wifi deauthenticate all networks with raspberry pi zero w in your backpack. Useful for public places |
| 203 | [pingequalab/5ghost-wifi-lab](https://github.com/pingequalab/5ghost-wifi-lab) | 77 | C | Dual-band 2.4/5 GHz Wi-Fi research tool for the Flipper Zero, built on the Realtek RTL8720DN (BW1… |
| 204 | [david-palma/wifi-cracking](https://github.com/david-palma/wifi-cracking) | 76 | — | A guide to using the Aircrack-ng suite for cracking 802.11 WEP and WPA/WPA2-PSK keys, including t… |
| 205 | [Hack-the-box/wifi-phisher](https://github.com/Hack-the-box/wifi-phisher) | 76 | Python | Automated victim-customized phishing attacks against Wi-Fi clients |
| 206 | [hackcrypto/fluxion](https://github.com/hackcrypto/fluxion) | 75 | Shell | Fluxion is a security auditing and social-engineering research tool. It is a remake of linset by … |
| 207 | [teja156/wifi-hacking-raspberrypi](https://github.com/teja156/wifi-hacking-raspberrypi) | 75 | Python | An automation script written in Python to convert a Raspberry Pi into a WiFi hacking device |
| 208 | [Evil-Project-Team/ESP32-C5-J4CK3D](https://github.com/Evil-Project-Team/ESP32-C5-J4CK3D) | 73 | C | An advanced WiFi scanning and packet sniffing toolkit for the ESP32-C5, featuring a cyberpunk-ins… |
| 209 | [letox4/netpwn](https://github.com/letox4/netpwn) | 73 | Python | Suite grafica de auditoria de redes (pentesting) con interfaz web: descubrimiento, escaneo, MITM,… |
| 210 | [nuncan/wifite2mod](https://github.com/nuncan/wifite2mod) | 73 | Python | Rolling Release Branch for community PR's @Credits to derv82 & the community |
| 211 | [UserJoo9/WiFi-Nightmare](https://github.com/UserJoo9/WiFi-Nightmare) | 73 | Python |  WiFi-Nightmare: Hybrid WiFi Auditor. Python CLI Control \| ESP32/ESP8266 Hardware Acceleration \… |
| 212 | [akr3ch/wicker-gui](https://github.com/akr3ch/wicker-gui) | 72 | Shell | automate wifi hacking with wicker |
| 213 | [BadKiko/Tsunami-Fi](https://github.com/BadKiko/Tsunami-Fi) | 72 | Python | Tsunami-Fi is simple multi-tool bash application for Wi-Fi attacks |
| 214 | [dom96/deauther](https://github.com/dom96/deauther) | 72 | Nim | An interactive command-line deauther for macOS. |
| 215 | [linkp2p/WPS-PIN](https://github.com/linkp2p/WPS-PIN) | 72 | Shell |  # This scripts is edited under the General Public License as defined by the Free software founda… |
| 216 | [sensepost/shinai-fi](https://github.com/sensepost/shinai-fi) | 72 | Shell | Docker images for learning wifi hacking |
| 217 | [vi3w-s0urce/xDeauther](https://github.com/vi3w-s0urce/xDeauther) | 71 | Shell | Easy tools for deauthentication attack wifi |
| 218 | [davidpanic/Kali-MiTM-Evil-twin](https://github.com/davidpanic/Kali-MiTM-Evil-twin) | 70 | Shell | A script that creates a wifi hotspot on kali linux that can view usernames and passwords of ssl l… |
| 219 | [micolous/helvetic](https://github.com/micolous/helvetic) | 70 | Python | Hacking / reverse engineering the Fitbit Aria (WiFi enabled bathroom scales) |
| 220 | [Leviathan36/SKA](https://github.com/Leviathan36/SKA) | 69 | Shell | Simple Karma Attack |
| 221 | [michelangelomo/marauder-ui](https://github.com/michelangelomo/marauder-ui) | 69 | Vue | A modern web interface for the ESP32 Marauder firmware. |
| 222 | [Drew-Alleman/autodeauth](https://github.com/Drew-Alleman/autodeauth) | 68 | Python | Automated Linux service that collects information on local Wi-Fi networks and performs deauthenti… |
| 223 | [larsjuhljensen/phatsniffer](https://github.com/larsjuhljensen/phatsniffer) | 67 | Python | Raspberry Pi + ESP8266 pHAT WiFi sniffer |
| 224 | [m4lal0/wifiAttack](https://github.com/m4lal0/wifiAttack) | 67 | Shell | Herramienta ideal para automatizar ataques WiFi (WEP & WPA/WPA2 - PSK) destinados a la obtención … |
| 225 | [ricardojoserf/wpa2-enterprise-attack](https://github.com/ricardojoserf/wpa2-enterprise-attack) | 66 | Shell | Virtual machines and scripts to attack WPA2-Enterprise networks through Rogue Access Points downg… |
| 226 | [z0m31en7/deauthalyzer](https://github.com/z0m31en7/deauthalyzer) | 66 | Python | Deauthalyzer is a script designed to monitor WiFi networks and detect deauthentication attacks. I… |
| 227 | [karthi-the-hacker/WIFIHacker](https://github.com/karthi-the-hacker/WIFIHacker) | 65 | HTML | An all-in-one WiFi pentesting tool designed to automate and simplify WiFi security auditing and a… |
| 228 | [mike01/sledgehammer](https://github.com/mike01/sledgehammer) | 65 | Python | :hammer: :signal_strength: WiFi-Jammer/DoS toolset |
| 229 | [RPxGoon/3TH1C4L-MultiTool](https://github.com/RPxGoon/3TH1C4L-MultiTool) | 65 | Python | A 'Work In-Progress' OSINT, Networking, Discord, and other General Purpose Multi-Tool Written 100… |
| 230 | [r4ulcl/WiFiChallengeLab](https://github.com/r4ulcl/WiFiChallengeLab) | 64 | Shell | WiFi hacking Lab. Virtualized WiFi pentesting laboratory without the need for physical WiFi cards… |
| 231 | [wahid987654321/hecker](https://github.com/wahid987654321/hecker) | 64 | — | KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau hp lu gw… |
| 232 | [zflemingg1/WiFi-Jammer](https://github.com/zflemingg1/WiFi-Jammer) | 63 | Python | Tool to automate wifi jamming |
| 233 | [Touti-Sudo/Touti-Cracker](https://github.com/Touti-Sudo/Touti-Cracker) | 61 | Python | Touti Cracker is a cross-platform ethical hacking toolkit for educational purposes, featuring pas… |
| 234 | [xpz3/airgeddonplugins](https://github.com/xpz3/airgeddonplugins) | 61 | HTML | Plugins for airgeddon |
| 235 | [buke18/5G-WiFi-deauth](https://github.com/buke18/5G-WiFi-deauth) | 60 | Assembly | 2.4Ghz&5Ghz双频WiFi deauth 安全测试模块，并对现有的固件做了小改动和升级处理【2.4Ghz & 5Ghz dual-band WiFi deauth security te… |
| 236 | [hacefresko/EvilPortal](https://github.com/hacefresko/EvilPortal) | 60 | Python | Python script to perform phishing attacks through captive portals, made for learning purposes |
| 237 | [Leviathan36/wifibang](https://github.com/Leviathan36/wifibang) | 60 | Shell | wifi attacks suite |
| 238 | [OCEANOFANYTHINGOFFICIAL/DevilTwin-NodeMCU](https://github.com/OCEANOFANYTHINGOFFICIAL/DevilTwin-NodeMCU) | 60 | C++ | ⚡ Perform Evil Twin Attack Using NodeMCU Board |
| 239 | [mvondracek/wifimitm](https://github.com/mvondracek/wifimitm) | 59 | Python | Wi-Fi Machine-in-the-Middle: Automation of MitM Attack on Wi-Fi Networks |
| 240 | [AbhinavBaranwal/wifi-hacking-termux](https://github.com/AbhinavBaranwal/wifi-hacking-termux) | 58 | Python |  |
| 241 | [dkyazzentwatwa/cypher-jammer-3NRF24](https://github.com/dkyazzentwatwa/cypher-jammer-3NRF24) | 58 | C++ | An ESP32 BT + WiFi Jammer w/ 3 NRF24 modules. |
| 242 | [s0i37/karma](https://github.com/s0i37/karma) | 58 | Python | karma WiFi attack implementation |
| 243 | [silverxcyber/WifiHackBar](https://github.com/silverxcyber/WifiHackBar) | 58 | HTML | WifiHackBar - A powerful WiFi Hacking Tool. Scan networks, perform deauthentication attacks, and … |
| 244 | [xiv3r/Deauther-RTL8720DN](https://github.com/xiv3r/Deauther-RTL8720DN) | 58 | — | 2.4G/5Ghz WiFi deauther firmware for RTL8720DN BW16 MCU |
| 245 | [cimplesid/Wifi-jammer-service](https://github.com/cimplesid/Wifi-jammer-service) | 57 | Python | A free script by sid that deauth all user from the network contiuosly forever |
| 246 | [gentle-grt/Wifi-Hacker](https://github.com/gentle-grt/Wifi-Hacker) | 57 | — | Hack any wifi with this amazing wifi hack for Android on termux |
| 247 | [hackthebox/PMKID](https://github.com/hackthebox/PMKID) | 56 | PHP | A module for the WiFi Pineapple to facilitate the PMKID attack. |
| 248 | [martian56/venx](https://github.com/martian56/venx) | 56 | Python | Wifi cracking, pentesting tool.  Pre-connection and Post-connection attacks. Capturing handshakes… |
| 249 | [spider863644/Wifi-Hack](https://github.com/spider863644/Wifi-Hack) | 56 | Python | A hacking tool for brute forcing WiFi password |
| 250 | [Vodker/wifimosys](https://github.com/Vodker/wifimosys) | 56 | Shell | Ataque EVIL TWIN |
| 251 | [AlexLynd/ProbeHunter](https://github.com/AlexLynd/ProbeHunter) | 54 | C | An ESP8266 based promiscuous WiFi sniffer to track devices emitting probe requests |
| 252 | [FadedCantCode/ESP32-wifi-hacking](https://github.com/FadedCantCode/ESP32-wifi-hacking) | 54 | — |  An universal tool for ESP32 platform to perform various Wi-Fi attacks.  |
| 253 | [pupi1985/marfil](https://github.com/pupi1985/marfil) | 54 | PHP | Marfil is an extension of the Aircrack-ng suite, used to assess WiFi network security. It allows … |
| 254 | [4ndreas/WiFI-RGBWW-module](https://github.com/4ndreas/WiFI-RGBWW-module) | 53 | Arduino | Chinse Wifi rgbww controller module hack |
| 255 | [emanuele-f/UsbWifiMonitorApi](https://github.com/emanuele-f/UsbWifiMonitorApi) | 53 | Java | API specification of the USB WiFi Monitor Android app |
| 256 | [HoneyHoneyTeam/ESP32.Marauder.Double.Barrel.5G.by.ESP32.C5](https://github.com/HoneyHoneyTeam/ESP32.Marauder.Double.Barrel.5G.by.ESP32.C5) | 53 | — | The version of Double Barrel 5G is packed with 1 * ESP32 chipset & 1 * ESP32 C5 chipset, GPS, Sub… |
| 257 | [atul12354/wifi_bruteforcer_fsecurify_6.0.apk](https://github.com/atul12354/wifi_bruteforcer_fsecurify_6.0.apk) | 52 | — | Hack wifi in bruteforcer app |
| 258 | [jerryryle/rogueportal](https://github.com/jerryryle/rogueportal) | 52 | HTML | Rogue Captive Portal using a Raspberry Pi |
| 259 | [pippianders/wifi-hacking-tools](https://github.com/pippianders/wifi-hacking-tools) | 52 | C |  |
| 260 | [Seyitq/nrf24l01-wifi-jammer](https://github.com/Seyitq/nrf24l01-wifi-jammer) | 52 | C++ | The activity of the nRF24 RF radio board is transmitted to the Arduino board via the serial inter… |
| 261 | [Hariss-Gills/pifi](https://github.com/Hariss-Gills/pifi) | 51 | Shell | Whenever the Raspberry Pi Device is turned on, it attempts to attack all the wifi networks within… |
| 262 | [nugroho466/Hacker-s-Pack-for-termux](https://github.com/nugroho466/Hacker-s-Pack-for-termux) | 51 | — | Special thanks to Ranginang67 for DarkFly (Collection of hack tools), threat9 for routersploit (W… |
| 263 | [pakistanihackergroup/TERMUX-HACKING-](https://github.com/pakistanihackergroup/TERMUX-HACKING-) | 51 | — | list of the best Termux hacking tools  android osint penetration-testing awesome-list wifi-securi… |
| 264 | [ZeroDayArcade/capture-handshake-wpa-wifi-hacking](https://github.com/ZeroDayArcade/capture-handshake-wpa-wifi-hacking) | 51 | Python | A python script for capturing 4-way handshakes for WPA/WPA2 WiFi networks. |
| 265 | [ccyl13/WiFiPentestTool](https://github.com/ccyl13/WiFiPentestTool) | 50 | Python | Herramienta para hacking wifi con múltiples opciones. |
| 266 | [666sempron999/HackRF_ONE-wifi-jammer](https://github.com/666sempron999/HackRF_ONE-wifi-jammer) | 49 | Python | Tis repository is proof of concept wifi denial of service (DOS) on phisical layer |
| 267 | [Kalihackz/Wifi_Ddos_EvilTwin_Combo](https://github.com/Kalihackz/Wifi_Ddos_EvilTwin_Combo) | 49 | HTML | DDos and Evil Twin Combo |
| 268 | [kashmir54/kashmir54.github.io](https://github.com/kashmir54/kashmir54.github.io) | 49 | HTML | Cibersecurity blog. CTFs, writeups, electronics and more! |
| 269 | [NSM-Barii/Yoda](https://github.com/NSM-Barii/Yoda) | 49 | Python | Passive RF monitor — real-time WiFi and BLE surveillance with deauth detection, device tracking, … |
| 270 | [arpitxp/Bruce-Smoochie-esp32](https://github.com/arpitxp/Bruce-Smoochie-esp32) | 48 | — | Standalone ESP32-S3 wireless pentesting deck built on Bruce firmware alternate to Flipper Zero, s… |
| 271 | [arxhr007/wifistrike](https://github.com/arxhr007/wifistrike) | 48 | Python | Pure-Python WiFi deauth & recon tool, scan access points and clients, launch targeted or broadcas… |
| 272 | [hadis898/esp32-jammer](https://github.com/hadis898/esp32-jammer) | 48 | — | ESP32-BlueJammer（蓝牙干扰器、BLE干扰器、WiFi干扰器、遥控干扰器）是一种针对2.4GHz通信频段的定向干扰设备。该设备基于ESP32主控芯片与nRF24模块构建，通过发射噪… |
| 273 | [alexivkin/wifipicket](https://github.com/alexivkin/wifipicket) | 47 | Python | Selective wifi jammer - control who can connect where |
| 274 | [gianfelicevincenzo/RoguePortal](https://github.com/gianfelicevincenzo/RoguePortal) | 47 | Shell | A Phishing WIFI Rogue Captive Portal! :smiling_imp: |
| 275 | [0x4156-AV/WiFi-Attack](https://github.com/0x4156-AV/WiFi-Attack) | 46 | Shell | A script to brute force a WiFi networks password |
| 276 | [herwonowr/CatchME](https://github.com/herwonowr/CatchME) | 46 | C | CatchME - WiFi Fun Box "Having Fun with ESP8266" |
| 277 | [lucthienphong1120/Aircrack-ng-handbook](https://github.com/lucthienphong1120/Aircrack-ng-handbook) | 46 | — | All in one - Everything useful about Aircrack-ng |
| 278 | [nocomp/ESP32-Wi-Fi-Penetration-Tool](https://github.com/nocomp/ESP32-Wi-Fi-Penetration-Tool) | 46 | — | Wifi Hacking / DDOS Attacks for the ESP32 |
| 279 | [alexus2033/RTL8720-Sniffer](https://github.com/alexus2033/RTL8720-Sniffer) | 45 | C++ | Presence detection using RTL8720DN 2.4G/5G Dual Bands Wifi Module |
| 280 | [sethleedy/Auto-Besside-Capturer](https://github.com/sethleedy/Auto-Besside-Capturer) | 45 | Shell | Capture WPA handshakes, using besside-ng. Auto upload to http://wpa-sec.stanev.org for cracking t… |
| 281 | [markszabo/Hacktivity2016](https://github.com/markszabo/Hacktivity2016) | 44 | Arduino | Repository for my workshop 'Wifi hacking with a 4 dollar microcontroller' on Hacktivity 2016 |
| 282 | [mr-cybro/WiFisploit](https://github.com/mr-cybro/WiFisploit) | 44 | Python | WiFisploit is a tool designed to scan and attack Wi-Fi networks using variety of powerful and eff… |
| 283 | [soynx/Hacking-PenTesting-Utils](https://github.com/soynx/Hacking-PenTesting-Utils) | 44 | HTML | A collection of scripts, documentation and HTML-Sites that can be used for penetration-testing |
| 284 | [albznw/Logitech-Z906-WiFi](https://github.com/albznw/Logitech-Z906-WiFi) | 43 | C++ | Breathe new life into your Logitech Z906 Surround system with this ESP8266-hack |
| 285 | [Mahfuz-THBD/Wifi_Hack_Installer](https://github.com/Mahfuz-THBD/Wifi_Hack_Installer) | 43 | Python | Hack Wifi With Your Rooted Android Device. |
| 286 | [BigBoss1986/Android-HUAWEISNE-L21](https://github.com/BigBoss1986/Android-HUAWEISNE-L21) | 42 | — | apk wifi hack tool |
| 287 | [br101/esp-monitor](https://github.com/br101/esp-monitor) | 42 | C | Wifi sniffing on the ESP8266 |
| 288 | [iSecur1ty/wifi-jammer](https://github.com/iSecur1ty/wifi-jammer) | 42 | Python | Python automated wifi jammer |
| 289 | [Phreak87/ESPeensy-and-Peensy-Payload-Generator-ESP8266-Teensy-3.5-](https://github.com/Phreak87/ESPeensy-and-Peensy-Payload-Generator-ESP8266-Teensy-3.5-) | 42 | Visual Basic | Build your own Bad USB Stick for pentesting with wifi and dip switches |
| 290 | [shabir-mp/WiFi-Password-Cracker](https://github.com/shabir-mp/WiFi-Password-Cracker) | 42 | Python | WiFi Security & Router Diagnostics is a cross-platform Python script that retrieves saved WiFi pr… |
| 291 | [c1ph3r-fsocitey/Interactive-Wi-Fi-Deauther](https://github.com/c1ph3r-fsocitey/Interactive-Wi-Fi-Deauther) | 41 | Python | Deauther Project can be used to:    Disconnect Devices from Networks,     and       Clone Networks |
| 292 | [domienschepers/wifi-deauthentication](https://github.com/domienschepers/wifi-deauthentication) | 41 | Python | Wi-Fi MFP Deauthentication: proof-of-concepts, security patches, and more. |
| 293 | [PNPtutorials/PNP-WiFi-Jammer](https://github.com/PNPtutorials/PNP-WiFi-Jammer) | 41 | Shell | This script continuously jams all the WiFi networks around you. |
| 294 | [ronaldstoner/ESP32-WifiJammerDectector](https://github.com/ronaldstoner/ESP32-WifiJammerDectector) | 41 | C++ | A simple ESP32 based WiFi detector that assists when jamming efforts may be attempted |
| 295 | [buke18/5G-Wi-Fi-deauth-can-support-flipper-zero-](https://github.com/buke18/5G-Wi-Fi-deauth-can-support-flipper-zero-) | 40 | Assembly | 5G&2.4Ghz Wi-Fi deauth for Flipper zero to easily test the WiFi security |
| 296 | [rustb0ne/RTL8720dn-5GHz-Wifi-Deauther](https://github.com/rustb0ne/RTL8720dn-5GHz-Wifi-Deauther) | 40 | C++ | 5GHz wifi deauther!!! |
| 297 | [sighook/refluxion](https://github.com/sighook/refluxion) | 40 | HTML | Refluxion -- MITM WPA attacks tool |
| 298 | [techchipnet/WiFiDeauthDetectorNodeMCU](https://github.com/techchipnet/WiFiDeauthDetectorNodeMCU) | 40 | C++ | Detect deauthentication attack using NodeMCU |
| 299 | [ICSec/airpwn-ng](https://github.com/ICSec/airpwn-ng) | 39 | Python | Packet injection for wifi; simplified. |
| 300 | [LxaNce-Hacker/wifi-jammer](https://github.com/LxaNce-Hacker/wifi-jammer) | 39 | Shell | This tool is used to jam any wifi network in your local area network. |
| 301 | [mattfrias/rpi3-wifijammer](https://github.com/mattfrias/rpi3-wifijammer) | 39 | Python | WiFi Jammer Script for Raspberry Pi 3 Model B |
| 302 | [MikkoParkkola/nowifi](https://github.com/MikkoParkkola/nowifi) | 39 | Go | No WiFi? Now WiFi. One command. 27 techniques. Bypass any captive portal. |
| 303 | [Revimal/WifiDeauth](https://github.com/Revimal/WifiDeauth) | 39 | C++ | A lightweight Wi-Fi auto deauthentication attack tool (libtins/C++) |
| 304 | [victorpreston/HackLab](https://github.com/victorpreston/HackLab) | 39 | Python | Welcome to HackLab, your go-to resource for hands-on cybersecurity projects. This repository is a… |
| 305 | [billpcs/jammer](https://github.com/billpcs/jammer) | 38 | Shell | 📶 A Bash script to automate the continuous circular deauthentication of all the wifi networks in … |
| 306 | [dedsecurity/dedsecurity-framework](https://github.com/dedsecurity/dedsecurity-framework) | 38 | Python | Ded Security Framework is a tool aimed at security professionals |
| 307 | [johnoseni1/Router-hacker-Exploit-and-extract-user-and-password-](https://github.com/johnoseni1/Router-hacker-Exploit-and-extract-user-and-password-) | 38 | Python | This is a python wifi (router) hacker , having ability to search for mikrotic devices around you … |
| 308 | [MuhamadJalalDev/ESP32-WiFi-Bluetooth-Jammer](https://github.com/MuhamadJalalDev/ESP32-WiFi-Bluetooth-Jammer) | 38 | — | Wi-Fi and Bluetooth jamming using an ESP32 microcontroller and NRF24L01 modules. This project inc… |
| 309 | [p0dalirius/WifiListProbeRequests](https://github.com/p0dalirius/WifiListProbeRequests) | 38 | Python | Monitor 802.11 probe requests from a capture file or network sniffing!  |
| 310 | [s0lst1c3/evil_twin](https://github.com/s0lst1c3/evil_twin) | 38 | Python | Python script for peforming basic Evil Twin attacks on open wifi networks. Written for my tutoria… |
| 311 | [barryblueice/ESP32-Haptic-Precision-TouchPad](https://github.com/barryblueice/ESP32-Haptic-Precision-TouchPad) | 37 | C | Another touchpad hacking project, based on ESP32-S3 + Surface Laptop Studio 1964 Synaptics TouchPad. |
| 312 | [Datalux/esp8266-deauther](https://github.com/Datalux/esp8266-deauther) | 37 | C++ | A simple WiFi deauther for ESP8266 |
| 313 | [h9zdev/EthiFi](https://github.com/h9zdev/EthiFi) | 37 | C | EthiFi is a affordable WiFi pentesting platform for testing and learning  |
| 314 | [jackind424/wifi-hacker](https://github.com/jackind424/wifi-hacker) | 37 | Shell | Shell Script For Attacking Wireless Connections Using Built-In Kali Tools. Supports All Securitie… |
| 315 | [KaraZajac/OVERWATCH](https://github.com/KaraZajac/OVERWATCH) | 37 | Kotlin | Android app that flags nearby Flock ALPRs, Axon body cams, police and surveillance aircraft from … |
| 316 | [KEI4251/ESP32-Jammer-](https://github.com/KEI4251/ESP32-Jammer-) | 37 | — | KEI JAMMER – A personal project focused on experimenting with wireless security using ESP32 and N… |
| 317 | [mrjuice01/Wifi-Cracker](https://github.com/mrjuice01/Wifi-Cracker) | 37 | Python | Proffesional Wifi Hacking Tool Using Termux, Kali, Ubuntu or any Terminal. Tool Requies Root Accs… |
| 318 | [rootsaid/ducky_over_wifi](https://github.com/rootsaid/ducky_over_wifi) | 37 | Arduino | HID or Human Interface Devices are Devices that takes input from human and pass it on to the devi… |
| 319 | [SagarBiswas-MultiHAT/WiFi-Dictionary-Attack](https://github.com/SagarBiswas-MultiHAT/WiFi-Dictionary-Attack) | 37 | Python | WiFi Dictionary Attack is a compact, Python-based Wi‑Fi security testing script. It scans nearby … |
| 320 | [GISDev01/security-ssid-abi](https://github.com/GISDev01/security-ssid-abi) | 36 | Python | Sniff wifi probes from nearby devices (passive monitoring only) and logs to a Django App/DB (with… |
| 321 | [intuitibits/wifiexplorer-sensor](https://github.com/intuitibits/wifiexplorer-sensor) | 36 | Python | [DEPRECATED] Enables remote scanning in WiFi Explorer Pro |
| 322 | [jerryryle/rogue_ap](https://github.com/jerryryle/rogue_ap) | 36 | Shell | Rogue AP using a Raspberry Pi Zero W |
| 323 | [Mr-pentest/Wifi-Hacking](https://github.com/Mr-pentest/Wifi-Hacking) | 36 | Python | ⚡ A powerful Python-based WiFi brute-force tool for ethical hacking and wireless security testing… |
| 324 | [p0dalirius/crEAP](https://github.com/p0dalirius/crEAP) | 36 | Python | crEAP will identify WPA Enterprise mode EAP types and harvest usernames and/or handshakes if inse… |
| 325 | [Woofydude/wifi_mitm](https://github.com/Woofydude/wifi_mitm) | 36 | C++ | for flipper zero, it is a man-in-the-middle app to be able to spoof a network name and get passwo… |
| 326 | [GiovanniBaccichet/openwrt-multi-sniffer](https://github.com/GiovanniBaccichet/openwrt-multi-sniffer) | 35 | TeX | OpenWrt-based Access Point multi-channel WiFi Probe Request sniffer 📡 |
| 327 | [HoneyHoneyTeam/ESP32-Marauder-Double-Barrel](https://github.com/HoneyHoneyTeam/ESP32-Marauder-Double-Barrel) | 35 | — | The ESP32 Marauder Double Barrel includes two ESP32 chipsets, GPS, Sub-GHz (433 MHz) and an onboa… |
| 328 | [HoneyHoneyTeam/ESP32-Marauder-Double-Barrel-5G](https://github.com/HoneyHoneyTeam/ESP32-Marauder-Double-Barrel-5G) | 35 | — | 1 * ESP32 chipset & 1 * BW16 chipset, GPS, Sub-GHz (433 MHz) and an onboard battery. It works wit… |
| 329 | [isecbaz/WiFi-Hack](https://github.com/isecbaz/WiFi-Hack) | 35 | Python | Fake WiFi Hacking Tool for Windows Reverse Shell |
| 330 | [leo-aa88/wifi-jammer](https://github.com/leo-aa88/wifi-jammer) | 35 | Python | Continuously perform deauthentication attacks on all detectable stations |
| 331 | [mehedishakeel/WiFi-Pentest-Kit](https://github.com/mehedishakeel/WiFi-Pentest-Kit) | 35 | — | WiFi Pentest Kit is a toolkit designed for wireless network security testing and auditing. It pro… |
| 332 | [pepeangell5/BWifiKill-BW16-5Ghz](https://github.com/pepeangell5/BWifiKill-BW16-5Ghz) | 35 | C++ | BWifiKill para BW16 RTL8720DN es un firmware educativo enfocado en análisis WiFi, pruebas de deau… |
| 333 | [R3DDY97/KICKthemOUT3](https://github.com/R3DDY97/KICKthemOUT3) | 35 | Python | K1CK  devices off your N3TW0RK by performing an ARP Spoof attack with Python3+ compatability |
| 334 | [SMH17/M5StackWiFiSniffer](https://github.com/SMH17/M5StackWiFiSniffer) | 35 | C++ | M5Stack WiFi packet sniffer for network analysis  |
| 335 | [tranthangit/crackwifi](https://github.com/tranthangit/crackwifi) | 35 | JavaScript | CRACKWIFI là một ứng dụng máy tính (Desktop App) mạnh mẽ được xây dựng bằng Electron, cung cấp gi… |
| 336 | [GregoryConrad/WirelessEMP](https://github.com/GregoryConrad/WirelessEMP) | 34 | Shell | Wireless EMP (WEMP) - A simple shell script that kicks all devices off of a network for as long a… |
| 337 | [Isonimus/adversary](https://github.com/Isonimus/adversary) | 34 | C++ | Red-team wireless pentesting firmware for the ESP32. Audit WiFi, BLE, IR, Sub-GHz, 2.4 GHz, RFID. |
| 338 | [morpheuslord/Brute-Hacking-Framework-SourceCode](https://github.com/morpheuslord/Brute-Hacking-Framework-SourceCode) | 34 | Batchfile | hacking framework complete source-code for web, wifi, url, sql-injection and doing a complete web… |
| 339 | [RonnyDo/Wammer](https://github.com/RonnyDo/Wammer) | 34 | Vala | Jamming your WiFi network |
| 340 | [valleytechsolutions/Skid-Detector](https://github.com/valleytechsolutions/Skid-Detector) | 34 | C++ | A wireless LED mood light and passive network security monitor built on the Seeed Studio XIAO ESP… |
| 341 | [yannpom/esp32sniffer](https://github.com/yannpom/esp32sniffer) | 34 | C | Use ESP32 to capture Wifi packets live with Wireshark |
| 342 | [ASP-29/WifiXv1.3](https://github.com/ASP-29/WifiXv1.3) | 33 | — | Source code for my project on youtube named WifiX Project,its just a simple esp8266 pentesting to… |
| 343 | [chkndrp/ESPnRF24-Jammer](https://github.com/chkndrp/ESPnRF24-Jammer) | 33 | C++ | A low-power 2,4GHz wireless jammer based on ESP32 and nRF24LO1+PA+LNA (PlatformIO) |
| 344 | [ip2k/WiFi-Abuse-Autokiller](https://github.com/ip2k/WiFi-Abuse-Autokiller) | 33 | Shell | Finds abusive WiFi users using way too much traffic on public wifi and sends them a sack of hot d… |
| 345 | [kaushalag29/Windows-Hacking-Scripts-With-Python](https://github.com/kaushalag29/Windows-Hacking-Scripts-With-Python) | 33 | Python | Hacking Wifi-Passwords,Chrome-Saved-Passwords,Copying the Scripts to Windows-Startup folder,Index… |
| 346 | [M0M0Sec/MoMo](https://github.com/M0M0Sec/MoMo) | 33 | Python | 🎯 Pi 5 Wardriving & Wireless Pentest Platform \| WiFi/BLE/SDR Attacks \| WPA3 • Evil Twin • Karma… |
| 347 | [naiksrinu/UAV_DataSet_NetworkCommunication](https://github.com/naiksrinu/UAV_DataSet_NetworkCommunication) | 33 | Python | UAV Network Communication Experimental dataset is a collection of network traffic captured from a… |
| 348 | [RLabs-Inc/wifikit](https://github.com/RLabs-Inc/wifikit) | 33 | Rust | WiFi pentesting toolkit for MacOS and Linux*. Pure Rust, single binary, real-time interactive CLI. |
| 349 | [skickar/WiFiHackingWorkshop](https://github.com/skickar/WiFiHackingWorkshop) | 33 | C++ | Files for the WI-Fi hacking workshop |
| 350 | [trandi/esp32-thermal_printer](https://github.com/trandi/esp32-thermal_printer) | 33 | Arduino | Hack an Epson TM-T88 thermal printer (the ones that print receipts in a supermarket till) and rem… |
| 351 | [vorchris/NullBeacon](https://github.com/vorchris/NullBeacon) | 33 | Python | A WiFi Deauther & Scanner for the BW16 (RTL8720DN) with a Python-based TUI. |
| 352 | [0day1day/Slave_I](https://github.com/0day1day/Slave_I) | 32 | C | Offensive-security firmware for the M5Stack Tab5 — browser-flashable Wi-Fi / BLE / 802.15.4 recon… |
| 353 | [adde88/krackattacks-pineapple](https://github.com/adde88/krackattacks-pineapple) | 32 | C | WPA2 Key reinstallation attack (KRACK) on the WiFi Pineapples |
| 354 | [dagnazty/Semi-Evil-M5Dial](https://github.com/dagnazty/Semi-Evil-M5Dial) | 32 | C++ | Advanced firmware for M5Dial devices, enabling WiFi captive portals, SSID management, Karma attac… |
| 355 | [Esther7171/WiFi-Hacking-Guide](https://github.com/Esther7171/WiFi-Hacking-Guide) | 32 | Shell | Hands-on WiFi hacking and penetration testing guide: monitor mode, recon, WPA2 handshake capture … |
| 356 | [HoneyHoneyTeam/ESP32-Marauder-5G-Apex-5-Module---For-Flipper-Zero](https://github.com/HoneyHoneyTeam/ESP32-Marauder-5G-Apex-5-Module---For-Flipper-Zero) | 32 | — | Apex 5 Module include 5 major functions into one single board, ESP32-C5 (5G Wifi Capabliity), dua… |
| 357 | [oyi77/wifi-jammer](https://github.com/oyi77/wifi-jammer) | 32 | Python | Advanced WiFi security testing tool — 10 attack types (deauth, PMKID, evil twin, channel hop), CL… |
| 358 | [sllumenikmati21/misteriusxx](https://github.com/sllumenikmati21/misteriusxx) | 32 | — | KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau hp lu gw… |
| 359 | [kissste/esp8266-Arduino-WifiSniffer](https://github.com/kissste/esp8266-Arduino-WifiSniffer) | 31 | Arduino | esp8266 Adruino Wifi Sniffer |
| 360 | [Alif0x1/wifiKill](https://github.com/Alif0x1/wifiKill) | 30 | Python | WiFikill Tool is a comprehensive utility designed to help security professionals and ethical hack… |
| 361 | [DubiousCactus/ShockWave](https://github.com/DubiousCactus/ShockWave) | 30 | C++ | ShockWave looks up for every connected device on the local network, then starts sending deauthent… |
| 362 | [j1a2k3e4/wifi-password-hack](https://github.com/j1a2k3e4/wifi-password-hack) | 30 | — | Automatically exported from code.google.com/p/wifi-password-hack |
| 363 | [javi-ln/wifi-spartan](https://github.com/javi-ln/wifi-spartan) | 30 | Python | Smart pentesting toolkit for modern WPA/WPA2 networks ⚔️📡 |
| 364 | [mkdirlove/Wifi_Hacker](https://github.com/mkdirlove/Wifi_Hacker) | 30 | — | Wifi hacker for Termux android. |
| 365 | [NicheSecTech/esp32-micropython-wifi-sniff-inject](https://github.com/NicheSecTech/esp32-micropython-wifi-sniff-inject) | 30 | Python | A ESP32 build of micropython v1.12 using ESP-IDF v4.0 that supports WiFi sniffing and injection. |
| 366 | [tesa-klebeband/ESP32-Deauther-ArduinoIDE](https://github.com/tesa-klebeband/ESP32-Deauther-ArduinoIDE) | 30 | C++ | A tool for the ESP32 with the ability to deauthenticate stations connected to WiFi networks |
| 367 | [0xbitx/DEDSEC_STARSYNC](https://github.com/0xbitx/DEDSEC_STARSYNC) | 29 | PHP | An effective tool for hacking starlink wifi password. |
| 368 | [HoneyHoneyTeam/3in1-WIFI-MultiBoard-with-Screen](https://github.com/HoneyHoneyTeam/3in1-WIFI-MultiBoard-with-Screen) | 29 | — | 3in1 WIFI board for Flipper Zero, ESP32 / Marauder + NRF24 + CC1101 by Honey Honey Lab |
| 369 | [jah64/Rothult-ESPeasy](https://github.com/jah64/Rothult-ESPeasy) | 29 | — | Hacking an IKEA Rothult NFC lock to be remotely controlled by a ESP8266 WiFi module |
| 370 | [psibot/wifi_wardriving](https://github.com/psibot/wifi_wardriving) | 29 | Shell | Some scripts and stuff for wardriving and wifi hacks .... works great on kali and ubuntu 32 bit .… |
| 371 | [stetro/ngn-sniffer](https://github.com/stetro/ngn-sniffer) | 29 | CSS | Android APP for NGN to sniff location based rf signals like GSM, Bluetooth or Wifi  |
| 372 | [tajmancrackit/How-to-install-kali-nethunter-in-termux](https://github.com/tajmancrackit/How-to-install-kali-nethunter-in-termux) | 29 | — | What is Kali Nethunter?  Kali Nethunter is a Android ROM which is designed for Penetration Testin… |
| 373 | [6e726d/Native-WiFi-API-Beacon-Sniffer](https://github.com/6e726d/Native-WiFi-API-Beacon-Sniffer) | 28 | C++ | Tool that dumps beacon frames to a pcap file. Works on Windows Vista or Later with any Wireless C… |
| 374 | [NABEGHEHACOM/WifiExtractor](https://github.com/NABEGHEHACOM/WifiExtractor) | 28 | Python | With this  Script you Can Access all Saved WiFi Passwords in Windows |
| 375 | [neustarsabbir-max/ESP32-Evil-Twin-Captive-Portal](https://github.com/neustarsabbir-max/ESP32-Evil-Twin-Captive-Portal) | 28 | C++ | ESP32 WiFi Pentesting tool: Scans networks, creates Evil Twin APs, and captures credentials to in… |
| 376 | [rw950431/ESP8266mini-sniff](https://github.com/rw950431/ESP8266mini-sniff) | 28 | Arduino | Wifi packet sniffer based on the ESP8266 chipset |
| 377 | [zexceed12300/rtl8188eu](https://github.com/zexceed12300/rtl8188eu) | 28 | C | RTL8188EU WiFi driver support monitor mode & frame injection |
| 378 | [error434/wirehack](https://github.com/error434/wirehack) | 27 | Python | Scripts for hacking through wireless network [WiFi] |
| 379 | [Ishanoshada/Esp32-Deauth](https://github.com/Ishanoshada/Esp32-Deauth) | 27 | Python | A Python tool for Wi-Fi deauthentication attacks using ESP32 with webserver firmware |
| 380 | [KylerCondran/WarCappin](https://github.com/KylerCondran/WarCappin) | 27 | Perl | WiFi Hacking: Autonomously man in the middle deauthenticate WPA2 wireless networks and packet cap… |
| 381 | [morpheuslord/passinfo.cmd](https://github.com/morpheuslord/passinfo.cmd) | 27 | Batchfile | contains a bruteforcer wifi hacker an batch to exe converter contains a n verity of usefull tools  |
| 382 | [rampage128/hombot-interface](https://github.com/rampage128/hombot-interface) | 27 | JavaScript | A replacement for the original LG Hombot WIFI-hack web interface. |
| 383 | [ruvnet/wifi-veil](https://github.com/ruvnet/wifi-veil) | 27 | Rust | WiFi Veil — a privacy firewall against unauthorized WiFi sensing. Compliant waveform controls onl… |
| 384 | [ShlomiRex/WiFi-EvilTwin](https://github.com/ShlomiRex/WiFi-EvilTwin) | 27 | Python | Create Evil Twin network that deauthernticates victims to force them to connect to your evil AP. |
| 385 | [taufiks22/new](https://github.com/taufiks22/new) | 27 | — | KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau hp lu gw… |
| 386 | [YogaRmdn/Dos-WiFi](https://github.com/YogaRmdn/Dos-WiFi) | 27 | Python | Easy to use tools for WiFi jamming created in Python |
| 387 | [ZeroDayArcade/RG353-WiFi-Penetration-Tool](https://github.com/ZeroDayArcade/RG353-WiFi-Penetration-Tool) | 27 | Python | Hacking WiFi Networks with the Anbernic RG353 line of hardware and other Retro Gaming Handhelds |
| 388 | [albertyw/indoor-localization](https://github.com/albertyw/indoor-localization) | 26 | Java | Indoor Localization by Wifi/Gyroscope/Accelerometer; made at Dropbox Hack Week 2013 |
| 389 | [dgiese/aerodust](https://github.com/dgiese/aerodust) | 26 | Python | HackBeanpot 2018, Hacks for Xiaomi vaccum cleaning robots: autonomous WiFi heatmap/mapping (very … |
| 390 | [dkyazzentwatwa/cypher-jammer-2nrf-oled](https://github.com/dkyazzentwatwa/cypher-jammer-2nrf-oled) | 26 | C++ | A wifi/bluetooth jammer with an oled screen and buttons. |
| 391 | [emrekybs/Wifi-Purple](https://github.com/emrekybs/Wifi-Purple) | 26 | Python | Automate script for wifi hacking |
| 392 | [Hacker-World0/Wifi-Jammer](https://github.com/Hacker-World0/Wifi-Jammer) | 26 | Python | These are favored by companies who deal with sensitive information to prevent leaks. The 5GHz WiF… |
| 393 | [HasnainDarkNet/Wifi-tester](https://github.com/HasnainDarkNet/Wifi-tester) | 26 | Python | WiFi Tester is a simple cybersecurity tool to test WiFi passwords using a wordlist.  This tool is… |
| 394 | [JulienFink/WiFi-Project](https://github.com/JulienFink/WiFi-Project) | 26 | Python | Pre-connection attacks, gaining access & post-connection attacks on WEP, WPA & WPA2. 🛰✔️ |
| 395 | [msillano/tuyaDAEMON](https://github.com/msillano/tuyaDAEMON) | 26 | — | A generic IOT framework, open for all user node-red devices and for any advanced custom logic, wi… |
| 396 | [N0tA1dan/Crab](https://github.com/N0tA1dan/Crab) | 26 | Python | Network/host scanner and information gatherer |
| 397 | [Quancivillious-Hornswoggle/RAVAGE](https://github.com/Quancivillious-Hornswoggle/RAVAGE) | 26 | Python | A Linux shell tool that has multiple tools such as, Instagram Scraper, Phisher, Network Scanner, … |
| 398 | [urld/wifitracker](https://github.com/urld/wifitracker) | 26 | Go |  |
| 399 | [whitewhidow/bboink](https://github.com/whitewhidow/bboink) | 26 | C++ | WiFi handshake/PMKID capture firmware for ESP32 — LilyGo T-Embed CC1101, T-Display C5 & Waveshare… |
| 400 | [wickednull/KTOX_Pi](https://github.com/wickednull/KTOX_Pi) | 26 | Python | KTOx_Pi — Network penetration & purple team suite for Raspberry Pi Zero 2W. Joystick-controlled L… |
| 401 | [Ba5hb0y/Deadfi_deauther-](https://github.com/Ba5hb0y/Deadfi_deauther-) | 25 | Shell | This tool will allows u to deauth or kick off an specific device from an given AP  |
| 402 | [johnkimdinh/wifi-jammer](https://github.com/johnkimdinh/wifi-jammer) | 25 | C | Build your own WiFi jammer with an ESP8266.  |
| 403 | [krakeninfosec/cyber-noise-blaster](https://github.com/krakeninfosec/cyber-noise-blaster) | 25 | HTML | Noise-based 2.4GHz jammer using ESP32 and NRF24L01 to disrupt Bluetooth, BLE, WiFi, and drone sig… |
| 404 | [mrExploitwriter/WiFi-Password](https://github.com/mrExploitwriter/WiFi-Password) | 25 | Python | Obtain connected WiFi passwords |
| 405 | [wirebits/WiFiSnare](https://github.com/wirebits/WiFiSnare) | 25 | C++ | A tool that captures 2.4GHz Wi-Fi passwords via Evil Twin attack. |
| 406 | [Boris-2021/wifi-dictionary-attack](https://github.com/Boris-2021/wifi-dictionary-attack) | 24 | Python | 字典攻击，你懂的 |
| 407 | [javierbu/awitas](https://github.com/javierbu/awitas) | 24 | Shell |  Ataque WPS transparente con rogue AP  |
| 408 | [karanankit01/WifiJammer](https://github.com/karanankit01/WifiJammer) | 24 | C | Using esp8266 Module, attacking the different wifi network and creating fake . |
| 409 | [nbergont/wofea_v10_hack](https://github.com/nbergont/wofea_v10_hack) | 24 | C++ | Low cost wifi alarm Wofea V10 Esphome hack |
| 410 | [PicoShot/ESP32-Deauther](https://github.com/PicoShot/ESP32-Deauther) | 24 | C++ | ESP32 WiFi Deauther - A DoS tool for ESP32 microcontrollers to disconnect   any 2.4GHz WiFi network. |
| 411 | [salman1123/Wifi-hacking-](https://github.com/salman1123/Wifi-hacking-) | 24 | — |                                              #!/usr/bin/env python import os import subprocess fr… |
| 412 | [WiPi-Hunter/PiNokyo](https://github.com/WiPi-Hunter/PiNokyo) | 24 | Python | 🍓 🤥🍍If threats like wifi pineapple attacks or karma attacks are active around, users will be info… |
| 413 | [digiampietro/hash-capture](https://github.com/digiampietro/hash-capture) | 23 | Perl | Automatically scans nearby WiFi networks, de-authenticates clients and tries to capture the four … |
| 414 | [katandev18/wifiphiser](https://github.com/katandev18/wifiphiser) | 23 | Shell | WiFi phising attack |
| 415 | [malsearchs/Wifi-Hacking-AircrackNG-Cheatsheet](https://github.com/malsearchs/Wifi-Hacking-AircrackNG-Cheatsheet) | 23 | — | AircrackNG commands guide |
| 416 | [michelep/ESP32_BeaconSniffer](https://github.com/michelep/ESP32_BeaconSniffer) | 23 | C++ | Beacon monitor for ESP32 with OLED display |
| 417 | [Wifimon/Wifimon](https://github.com/Wifimon/Wifimon) | 23 | C | Wi-fi 802.11 Beacon Frame sniffer |
| 418 | [0x90/iSniff](https://github.com/0x90/iSniff) | 22 | Python | Tiny WiFi sniffer with Scapy for MAC OS X |
| 419 | [amibhai/wifi_down](https://github.com/amibhai/wifi_down) | 22 | Python | An automated, menu-driven WiFi security auditing framework with an end-to-end attack, cracking, a… |
| 420 | [arkypita/Vigotech-VG-L7X](https://github.com/arkypita/Vigotech-VG-L7X) | 22 | C++ | VG-L7X Vigotech engraver (WiFi model) resources and hack |
| 421 | [Emersonmafra/f](https://github.com/Emersonmafra/f) | 22 | — | #!/bin/bash  ########## DEBUG Mode ########## if [ -z ${FLUX_DEBUG+x} ]; then FLUX_DEBUG=0     el… |
| 422 | [Hex2424/esp32_deauth_patch](https://github.com/Hex2424/esp32_deauth_patch) | 22 | — | Fixed esp32 ieee80211.a lib esp_wifi_80211_tx() function sanity check filter of deauth packets |
| 423 | [kxyznew/WiFi-Pineapple-Pager-Master-Control-Suite](https://github.com/kxyznew/WiFi-Pineapple-Pager-Master-Control-Suite) | 22 | Python | ## Key Features: - **Tri-Band Attacks**: 2.4GHz, 5GHz, 6GHz simultaneous operations - **Autonomou… |
| 424 | [ZeroDayArcade/capture-pmkid-wpa-wifi-hacking](https://github.com/ZeroDayArcade/capture-pmkid-wpa-wifi-hacking) | 22 | Python | A python script for capturing a PMKID from a WiFi router for cracking WPA/WPA2 passwords. |
| 425 | [byt3n33dl3/NetVenom](https://github.com/byt3n33dl3/NetVenom) | 21 | C | WiFi Pentesting on Mac filters bypass and SSID manipulation. |
| 426 | [CraftyZA/DetectWifiHack](https://github.com/CraftyZA/DetectWifiHack) | 21 | C | based on my previous deauth detection, but will expand to detect other hack types as well. |
| 427 | [ElmanTr/python-wifi-hack-with-subprocess](https://github.com/ElmanTr/python-wifi-hack-with-subprocess) | 21 | Python | A simple program with Python to hack WiFi ! getting WiFi information and passwords from CMD by su… |
| 428 | [i-am-unbekannt/unbekannt-framework](https://github.com/i-am-unbekannt/unbekannt-framework) | 21 | Python | A Hacking and Pentesting Tool for Windows |
| 429 | [imnortheastt/wireless_cracking_tools](https://github.com/imnortheastt/wireless_cracking_tools) | 21 | Python | Wifi cracking tools |
| 430 | [jimbon25/WIFI-TOOLKIT](https://github.com/jimbon25/WIFI-TOOLKIT) | 21 | CSS | A comprehensive, menu-driven utility for Wi-Fi penetration testing and security auditing. |
| 431 | [justcallmekoko/ROTA](https://github.com/justcallmekoko/ROTA) | 21 | — | A WiFi enabled Xbox One rapid-fire mod |
| 432 | [mehedishakeel/WiFi-Deauther-BW16](https://github.com/mehedishakeel/WiFi-Deauther-BW16) | 21 | C++ | Dual Band WiFi Deauther For Both 2.4GHz & 5GHz WiFI Networks with BW16 RTL8720DN Module |
| 433 | [richstokes/EvilPortal-M5Stack](https://github.com/richstokes/EvilPortal-M5Stack) | 21 | C | 😈 Evil Wi-Fi Portal implementation for the M5Stack Core S3 |
| 434 | [Whomrx666/Xdeauth-wifi](https://github.com/Whomrx666/Xdeauth-wifi) | 21 | Python | Xdeauth-wifi is a tool used to carry out DDOS attacks on a WiFi or is usually called a WiFi deauther |
| 435 | [DX4GREY/esp8266_wifitools](https://github.com/DX4GREY/esp8266_wifitools) | 20 | C | This is a WiFi Tool which includes EvilTwin and Deauther, this tool is based on esp8266_deauther,… |
| 436 | [GoldSkull-777/GoldJam](https://github.com/GoldSkull-777/GoldJam) | 20 | Python | WiFi jamming tool for Kali Linux using Aircrack-ng & Python. Built for educational and ethical te… |
| 437 | [jakuta-tech/Wifi-Cracker](https://github.com/jakuta-tech/Wifi-Cracker) | 20 | Python | Wifi-Cracker.py to Hack WPS/WPA/WPA2 Networks |
| 438 | [Rubbles-eh/Direwolf_3.5CYD](https://github.com/Rubbles-eh/Direwolf_3.5CYD) | 20 | Python | Multi Device Case for 3.5" CYD with modular options for use with common firmware's (Halehound, Br… |
| 439 | [trfahim/WIFI-HACK-LINUX](https://github.com/trfahim/WIFI-HACK-LINUX) | 20 | Python | Powerful WiFi Hacking penetration testing tools for Linux, designed for ethical hacking, security… |
| 440 | [waheeb71/WiFi-Hacking-Tool](https://github.com/waheeb71/WiFi-Hacking-Tool) | 20 | Python | WiFi Hacking Tool is a powerful Python-based tool designed for ethical hacking, network analysis,… |
| 441 | [dotberg/pwnagotchi-zero](https://github.com/dotberg/pwnagotchi-zero) | 19 | Java | Autonomous AI-driven WiFi security tool for rooted Android. Native Qualcomm monitor mode, Thompso… |
| 442 | [GoatsAndMonkeys/monster_mesh](https://github.com/GoatsAndMonkeys/monster_mesh) | 19 | C++ | MonsterMesh: a Game Boy emulator, Gen-1 monster-battling RPG, and WiFi/BLE 'Pentest Pikachu' secu… |
| 443 | [syphr0/wifi32](https://github.com/syphr0/wifi32) | 19 | C++ | A wifi tool using the esp32 |
| 444 | [xiv3r/uz801-usb-pentest](https://github.com/xiv3r/uz801-usb-pentest) | 19 | — | UZ801 4G USB Modem |
| 445 | [mattlawer/wifipineapple-PMKID](https://github.com/mattlawer/wifipineapple-PMKID) | 18 | HTML |  PMKID Attack Module for the WiFi Pineapple |
| 446 | [Mausam678/wifi-jammer-tool-for-esp32](https://github.com/Mausam678/wifi-jammer-tool-for-esp32) | 18 | — | This tool is a binary firmware designed for the ESP32 microcontroller, enabling it to perform WiF… |
| 447 | [mishra9759harshit/wifi-attack-tool](https://github.com/mishra9759harshit/wifi-attack-tool) | 18 | Python | WiFi Attack Tool is an advanced penetration testing and cybersecurity auditing tool that automate… |
| 448 | [OmarVillaWolf/RedTeam-Attack-Library](https://github.com/OmarVillaWolf/RedTeam-Attack-Library) | 18 | — | Red Team Techniques & TTPs: AD, C2, SCADA, PrivEsc, Web Hacking, Buffer Overflow, WiFi. |
| 449 | [p4wnsolo/p4wnsolo-joyterm](https://github.com/p4wnsolo/p4wnsolo-joyterm) | 18 | Python | 🕹️ Enter a command with OLED Joystick  ▶️ Run + Display output on OLED Screen (Works with P4wnP1!) |
| 450 | [samphoerna/EvilTwin-ESP8266](https://github.com/samphoerna/EvilTwin-ESP8266) | 18 | C | A network attack using Evil Twin Framework paired in NodeMCU ESP8266 device to exploit vulnerabil… |
| 451 | [sharathc213/wifi_deauth_detector](https://github.com/sharathc213/wifi_deauth_detector) | 18 | CSS | a web interface  to detect deauthentication attack |
| 452 | [socket8088/WiFi-Pentest](https://github.com/socket8088/WiFi-Pentest) | 18 | Shell | Wireless Pentest |
| 453 | [zer0dayf/Flipper_Jam](https://github.com/zer0dayf/Flipper_Jam) | 18 | C++ | WiFi security research tool for Flipper Zero + ESP32. Deauth, beacon spam, evil twin, targeted & … |
| 454 | [82goober82/fluxionwpacrack](https://github.com/82goober82/fluxionwpacrack) | 17 | Shell | Fluxion is the future of MITM WPA attacks  Fluxion is a security auditing and social-engineering … |
| 455 | [abzicht/heyyou](https://github.com/abzicht/heyyou) | 17 | Python | A simple script demonstrating the power that comes with SSID sniffing |
| 456 | [Coreymillia/Shark-Bait-add-on-Bruce-firmware-M5stackc-plus-](https://github.com/Coreymillia/Shark-Bait-add-on-Bruce-firmware-M5stackc-plus-) | 17 | — |   *Features:*  *Real-time WiFi threat detection* *4 targeted counter-attack methods* (Karma poiso… |
| 457 | [chargz/DeauthSniff](https://github.com/chargz/DeauthSniff) | 16 | C | DeauthSniff alerts users about potential WiFi deauthentication attacks. |
| 458 | [huaminghuangtw/ESP32WiFiSnifferApp](https://github.com/huaminghuangtw/ESP32WiFiSnifferApp) | 16 | C++ | 📌 An interdisciplinary team project of the course Software Lab at Technical University of Munich … |
| 459 | [jiansiting/HotAP-Jammer](https://github.com/jiansiting/HotAP-Jammer) | 16 | Python | Jammer 2.4G and 5G AP wifi |
| 460 | [LagrangianLad/tewcrack](https://github.com/LagrangianLad/tewcrack) | 16 | Shell | Run a dictionary attack on a Wifi network to get it's password |
| 461 | [Luigi-Pizzolito/Sonic-Deauther](https://github.com/Luigi-Pizzolito/Sonic-Deauther) | 16 | C | ESP8266 Pen-testing Deauther made into a sonic screwdriver controller. |
| 462 | [ra1nb0rn/CDeauth](https://github.com/ra1nb0rn/CDeauth) | 16 | C |  A WiFi deauthentication tool written in C |
| 463 | [RadDad87/C3RB3RU5](https://github.com/RadDad87/C3RB3RU5) | 16 | HTML | C3RB3RU5 web flasher for CiferTech ESP32-DIV (V2, S3) — flash 2.4GHz WiFi/BLE/SubGHz pentest firm… |
| 464 | [sobri3195/Pegabox](https://github.com/sobri3195/Pegabox) | 16 | Python | A collection of Windows, Website and Wifi pentesting scripts and exploits. |
| 465 | [Anamika21/WiHawk](https://github.com/Anamika21/WiHawk) | 15 | — | A wireless router when newly installed has a default admin password depending on its manufacturer… |
| 466 | [anonymous-beta/Wifidaemon](https://github.com/anonymous-beta/Wifidaemon) | 15 | Python | WiFiDAEMON is a next-generation, modular, and demon-themed Wi-Fi pentesting framework. Built from… |
| 467 | [ashrafuljoy62/WiFuX](https://github.com/ashrafuljoy62/WiFuX) | 15 | Python | A powerful tool for hacking WiFi using Termux/Linux. |
| 468 | [balwantyadav1/WIFI-Deauther](https://github.com/balwantyadav1/WIFI-Deauther) | 15 | C | WiFi-Deauther: Wi-Fi security tool with ESP8266 for deauth attacks and monitoring. |
| 469 | [FLOCK4H/Cappy](https://github.com/FLOCK4H/Cappy) | 15 | HTML | WiFi Evil Twin Attack - Credential Harvest Tool |
| 470 | [LowSkillDeveloper/AutoWPS-Script](https://github.com/LowSkillDeveloper/AutoWPS-Script) | 15 | Shell | Simple Auto WPS Pixie Dust Attack script for walking (using Wifite2) |
| 471 | [lynalan2/wifi_scripts](https://github.com/lynalan2/wifi_scripts) | 15 | Python | Menu-driven Wi-Fi auditing toolkit: handshake capture, hashcat cracking, and Evil Twin attacks. E… |
| 472 | [MBHudson/APEX-MassAP-Deauth](https://github.com/MBHudson/APEX-MassAP-Deauth) | 15 | Shell | Aggressive Mass AP Deauth/Jammer (PWN ALL WIFI IN RANGE) |
| 473 | [meepmaster360/wifiduck](https://github.com/meepmaster360/wifiduck) | 15 | — | Wireless keystroke injection attack platform # WifiDuck |
| 474 | [mrmonstertown226/wifi-password-stealing](https://github.com/mrmonstertown226/wifi-password-stealing) | 15 | — | A network security auditing tool. It allows for the recovery of saved Wi-Fi credentials and helps… |
| 475 | [aeracoop/dronehole](https://github.com/aeracoop/dronehole) | 14 | Shell | Example of Drone deauthentication attack to Parrot and DJI drones in wifi mode |
| 476 | [codewithharit/Deauther_With_Oled_Display](https://github.com/codewithharit/Deauther_With_Oled_Display) | 14 | — | Esp8266 Nodemcu Wifi Development Deauther With Oled Display |
| 477 | [danngalann/wifispammer](https://github.com/danngalann/wifispammer) | 14 | Python | A python script to spam a bunch of silly wifi networks |
| 478 | [DenoBY/HandshakeCrack](https://github.com/DenoBY/HandshakeCrack) | 14 | HTML | Module HandshakeCrack v1.1 for WiFi Pineapple |
| 479 | [G4MEOVER18/FlipperJammer](https://github.com/G4MEOVER18/FlipperJammer) | 14 | C | Flipper Zero Jammer Suite: SubGHz/NRF24/BLE/WiFi/IR/RFID/NFC/USB — Momentum API 87.1 |
| 480 | [haKC-ai/CapturedPortal](https://github.com/haKC-ai/CapturedPortal) | 14 | C++ | An ESP32-based captive portal scanner and credential enumerator. Automatically detects hotel styl… |
| 481 | [JNDreviews/est-Smartphones-under-Rs.15000-](https://github.com/JNDreviews/est-Smartphones-under-Rs.15000-) | 14 | — | WHICH ARE THE BEST SMARTPHONES UNDER 15000 . Best Smartphones under Rs.15000 models 2021  Step by… |
| 482 | [John-Athanasopoulos/Wifi-Deauther-ESP8266-Tutorial](https://github.com/John-Athanasopoulos/Wifi-Deauther-ESP8266-Tutorial) | 14 | — | A tutorial on how to make a Wifi Deauther (with beacon and probe attacks included) with an ESP826… |
| 483 | [lucianjames/ESP32WifiHacks](https://github.com/lucianjames/ESP32WifiHacks) | 14 | C++ | Easy to use WiFi tools for the ESP32. Graphical interface provided via IMGUI |
| 484 | [minimike86/aircrack-scripts](https://github.com/minimike86/aircrack-scripts) | 14 | Shell | Aircrack-ng Suite Scripts to Easily Demonstrate Wifi Attacks |
| 485 | [Samurai-X-13/wifi-deauther-gui](https://github.com/Samurai-X-13/wifi-deauther-gui) | 14 | Python | This is a gui interface for airmon-ng  |
| 486 | [sidward35/Deauth-RickRollAP](https://github.com/sidward35/Deauth-RickRollAP) | 14 | Arduino | Performs a deauth attack and sends beacon frames to flood the list of available WiFi networks wit… |
| 487 | [t04glovern/traffic-cop](https://github.com/t04glovern/traffic-cop) | 14 | C++ | WiFi Beacon & Client sniffing pipeline for analysing the movements of Human Traffickers. |
| 488 | [TeamBlackBerry/WIFI-JAMER](https://github.com/TeamBlackBerry/WIFI-JAMER) | 14 | Python | It,s A Wifi Jamer Tool For Jam Any Connect Wifi Network  |
| 489 | [usamahacker0/WIFI-Uchiha](https://github.com/usamahacker0/WIFI-Uchiha) | 14 | — | A WIFI Pentesting Tool ( WIFI Hacking ) with Powerfull tools. |
| 490 | [yaxter/DoSWifi](https://github.com/yaxter/DoSWifi) | 14 | Shell | DoS attack, Ataque DoS a redes Wifi, herramienta capaz de Expulsar a todos los usuarios de una re… |
| 491 | [ztzhang/GoProWifiCommand](https://github.com/ztzhang/GoProWifiCommand) | 14 | — | Gopro wifi command hack---a sniff result of Gopro App . The Json file can be used as a Gopro cont… |
| 492 | [7wp81x/NRSuite-firmware](https://github.com/7wp81x/NRSuite-firmware) | 13 | C++ | ESP32 firmware for the NRSuite security research toolkit. Wi-Fi/BLE attack and capture modules (d… |
| 493 | [AnandKatariya/WiFi-Jammer](https://github.com/AnandKatariya/WiFi-Jammer) | 13 | — | In this repositories we will learn , How to make WiFi Jammer and how to block the specific WiFi. … |
| 494 | [AuroraError/AuroraDeauth](https://github.com/AuroraError/AuroraDeauth) | 13 | Shell | Deauth and Beacon Spammer Script with Multiple functions. |
| 495 | [BlackTechX011/ESP8266_WIFI_PROBE_SNIFFER_Web_tool](https://github.com/BlackTechX011/ESP8266_WIFI_PROBE_SNIFFER_Web_tool) | 13 | HTML | a web based ESP8266 SNIFFER Flasher tool |
| 496 | [danya201272/ESP32-4M-WiFi-BLSerial-433Mhz](https://github.com/danya201272/ESP32-4M-WiFi-BLSerial-433Mhz) | 13 | C++ | ESP32 with app interface remoteXY and grab and sent code. Bruteforce Came and Nice. Have a Jammer… |
| 497 | [demining/Bluetooth-Attacks-CVE-2025-27840](https://github.com/demining/Bluetooth-Attacks-CVE-2025-27840) | 13 | Jupyter Notebook | Bitcoin Cryptanalysis: CVE-2025-27840 Vulnerability in ESP32 Microcontrollers Puts Billions of Io… |
| 498 | [Derek1ization/Hack-pack-ON-STRIOD-2020](https://github.com/Derek1ization/Hack-pack-ON-STRIOD-2020) | 13 | — | Tools that i have gatherd and study to see how thay work and learned why theses tools execute the… |
| 499 | [EMLGaming/handshakestealer](https://github.com/EMLGaming/handshakestealer) | 13 | Shell | This is just a basic script that steals handshakes and cleans them this can then be used to crack… |
| 500 | [fulvius31/WpsConnectionLibrary](https://github.com/fulvius31/WpsConnectionLibrary) | 13 | C | An Android library for WiFi WPS (WiFi Protected Setup) security testing. Provides a clean, asynch… |
| 501 | [ginanjaradit354/wifi-hacker](https://github.com/ginanjaradit354/wifi-hacker) | 13 | — | #!/bin/bash#############################################################################   CREDIT… |
| 502 | [indradhar/social-engineering-attack-wifi](https://github.com/indradhar/social-engineering-attack-wifi) | 13 | HTML | Social Engineering Attack Using Phishing in a Local Area Wi-Fi by Creating an Access Point and DN… |
| 503 | [jhannah01/WifiSniffer](https://github.com/jhannah01/WifiSniffer) | 13 | Java | An android-based tool to record and analyze wireless data |
| 504 | [Kalmat/DSTIKE-SPACEHUHN-Deauther-Weather](https://github.com/Kalmat/DSTIKE-SPACEHUHN-Deauther-Weather) | 13 | C | WiFi Deauther and OpenWeatherMap station for a DSTIKE&SPACEHUHN V3 wristwatch (Arduino ESP8266) |
| 505 | [koushikos/Kali-Linux-WiFi-Pentesting-Handbook](https://github.com/koushikos/Kali-Linux-WiFi-Pentesting-Handbook) | 13 | — | Wireless security penetration testing guide built for cybersecurity learning using Kali Linux. In… |
| 506 | [lukius/wifi-deauth](https://github.com/lukius/wifi-deauth) | 13 | Python | WiFi deauthentication attack using Scapy |
| 507 | [nerodtm/BetterBackdoor---A-Backdoor-With-A-Multitude-Of-Features](https://github.com/nerodtm/BetterBackdoor---A-Backdoor-With-A-Multitude-Of-Features) | 13 | — | A backdoor is a tool used to gain remote access to a machine.  Typically, backdoor utilities such… |
| 508 | [omeryos/ESP32-WIFI-JAMMER](https://github.com/omeryos/ESP32-WIFI-JAMMER) | 13 | C++ | 2.4Ghz Wifi networks spot jamming device, utilizing ESP32 and nRF24L01+  |
| 509 | [quackduck/wif](https://github.com/quackduck/wif) | 13 | C | wifi packet sniffer |
| 510 | [StepSisStuck/ESP32-Wifi-Hacking](https://github.com/StepSisStuck/ESP32-Wifi-Hacking) | 13 | — | A guide on using ESP32 with Flipper Zero to get your wifi password |
| 511 | [TechnicalUserX/proximoth](https://github.com/TechnicalUserX/proximoth) | 13 | C | Control Frame Attack Vulnerability Detection Tool (GitLab Mirror) |
| 512 | [TheLogeek/WiFi-Hacker](https://github.com/TheLogeek/WiFi-Hacker) | 13 | Python | WiFi-Hacker is a dictionary attack program that tests 2300+ commonly used passwords on a WiFi net… |
| 513 | [waheeb71/WiFiSlayer](https://github.com/waheeb71/WiFiSlayer) | 13 | Python | Advanced WiFi Penetration Testing Framework. WiFiSlayer automates wireless security auditing, WPA… |
| 514 | [Whomrx666/Xdeauth-owner](https://github.com/Whomrx666/Xdeauth-owner) | 13 | Python | Xdeauth-owner is a tool that can place us as the owner of the WiFi by being able to determine who… |
| 515 | [Ben-Sassi-Oussema/NODEMCU-DEAUTHER](https://github.com/Ben-Sassi-Oussema/NODEMCU-DEAUTHER) | 12 | — | This software allows you to easily perform a variety of actions to test 802.11 wireless networks … |
| 516 | [dfalt0/NodeMCU-ESP8266](https://github.com/dfalt0/NodeMCU-ESP8266) | 12 | C | This software allows you to perform a deauth attack with an ESP8266 against selected networks. Th… |
| 517 | [FL0WL0W/HumiditySnifferRTL8720](https://github.com/FL0WL0W/HumiditySnifferRTL8720) | 12 | C++ | A 2.4/5 Ghz WiFi Sniffer that also captures Temperature and Humidity from a HDC1080 using an RTL8720 |
| 518 | [godragun/Marauder-ESP32-S3](https://github.com/godragun/Marauder-ESP32-S3) | 12 | C++ | 📡 ESP32 Marauder v1.11.0 compiled for XIAO ESP32-S3 — WiFi security testing, BLE scanning, and et… |
| 519 | [graylagx2/Customized_spacehuhn_DeAuther](https://github.com/graylagx2/Customized_spacehuhn_DeAuther) | 12 | HTML | A customized version of spacehuhns Deauther for the esp8266 Wifi module. This folder contains the… |
| 520 | [imayavaramban11/2.4Ghz-Jammer](https://github.com/imayavaramban11/2.4Ghz-Jammer) | 12 | — | 2.4GHz RF Interference Generator — ESP32 + nRF24L01+ A dual-channel 2.4GHz RF noise generator usi… |
| 521 | [jaybosamiya/wifi-sniffer](https://github.com/jaybosamiya/wifi-sniffer) | 12 | C++ | Find MAC addresses of devices leaving any sort of trace in the air around you |
| 522 | [k1lgor/wifi-dos](https://github.com/k1lgor/wifi-dos) | 12 | Shell | A simple wifi dos attack |
| 523 | [MariyaSha/PacketSniffer](https://github.com/MariyaSha/PacketSniffer) | 12 | Python | Demonstrating with Flask and Scapy What Hackers See on Public WiFi |
| 524 | [N1P0STK4/Wificuak](https://github.com/N1P0STK4/Wificuak) | 12 | Shell | Tool for Wifi Network Attacks (WPA/WPA2 - PSK- Hijacking -  Beacon Flood - DoS Attack - Scanner -… |
| 525 | [purva-patel/WIFI-DOS-Scripts](https://github.com/purva-patel/WIFI-DOS-Scripts) | 12 | Python | This repository contains Python scripts for performing Denial of Service (DoS) attacks on WiFi ne… |
| 526 | [simeononsecurity/esp32-wifi-canary](https://github.com/simeononsecurity/esp32-wifi-canary) | 12 | C++ | Passive ESP32 WiFi canary with RGB LED alerts for deauth spikes, suspicious duplicate SSIDs, open… |
| 527 | [xiv3r/openwrt-deauther](https://github.com/xiv3r/openwrt-deauther) | 12 | Shell | openwrt wifi deauther jammer based on aireplay-ng \| capture 4 way handshake with openwrt router. |
| 528 | [1arlz/fiberRock](https://github.com/1arlz/fiberRock) | 11 | Python | Word lists and dictionaries for burte force attacks |
| 529 | [82goober82/fluxionwpa2](https://github.com/82goober82/fluxionwpa2) | 11 | — | Fluxion is the future of MITM WPA attacks  Fluxion is a security auditing and social-engineering … |
| 530 | [ALBINPRAVEEN/Wifi-jammer](https://github.com/ALBINPRAVEEN/Wifi-jammer) | 11 | Objective-C |  |
| 531 | [at0m-b0mb/Trident-FlipperZero](https://github.com/at0m-b0mb/Trident-FlipperZero) | 11 | C | Trident — one Flipper Zero app for a 3-in-1 ESP32 + NRF24 + CC1101 expansion board: Wi-Fi/BT via … |
| 532 | [CAPSTV/Deauther_0.96-inch-OLED_RGB-LED](https://github.com/CAPSTV/Deauther_0.96-inch-OLED_RGB-LED) | 11 | C | WiFi Deauther with 0.96 inch OLED and RGB LED Integration |
| 533 | [codewithharit/ESP8266-DEAUTHER-FILE](https://github.com/codewithharit/ESP8266-DEAUTHER-FILE) | 11 | — | WIFI JAMMER FILE ESP8266 |
| 534 | [cr4sh-me2/aura](https://github.com/cr4sh-me2/aura) | 11 | Shell | An easy user interface for pentesting tools |
| 535 | [egefeyzioglu/Long-Range-RFID-Sniffer](https://github.com/egefeyzioglu/Long-Range-RFID-Sniffer) | 11 | C++ | Reads RFID cards from a long/medium distance, and displays the card IDs on a web page on a WiFi n… |
| 536 | [ESPboy-edu/ESPboy_WiFiSniffer](https://github.com/ESPboy-edu/ESPboy_WiFiSniffer) | 11 | C++ | ESPboy WiFi sniffer. Sniff WiFi packets. |
| 537 | [Farizrmd/esp32-serangan](https://github.com/Farizrmd/esp32-serangan) | 11 | C++ | ESP32 BT/WiFi Attack Tool v2 MEGA - 16 attack modes (BLE Scanner, Deauth, A2DP Jam, Spam, WiFi De… |
| 538 | [GeneralDussDuss/davey-jones](https://github.com/GeneralDussDuss/davey-jones) | 11 | C | Multi-radio pentesting firmware for Arduino Nesso N1 (ESP32-C6 + SX1262). WiFi/BLE/Sub-GHz/IR/Zig… |
| 539 | [Hamed-Gharghi/wifi-deauther](https://github.com/Hamed-Gharghi/wifi-deauther) | 11 | Python | A powerful WiFi deauthentication tool for educational purposes. Features include interactive netw… |
| 540 | [jseric/raspberry-jammer](https://github.com/jseric/raspberry-jammer) | 11 | Python | WiFi Attacking Application With User Interface |
| 541 | [l4f2s4/pyqt5-linux-wifi-jamming-tools](https://github.com/l4f2s4/pyqt5-linux-wifi-jamming-tools) | 11 | Python | Wifi-Jamming is a simple GUI tool, yet highly effective method of causing a DoS on a wireless imp… |
| 542 | [Mehliug-git/Wifi-Mass-DeAuth](https://github.com/Mehliug-git/Wifi-Mass-DeAuth) | 11 | Python | A little script for DeAuth everyone on all wifi arround you  & capture the password hash ! |
| 543 | [Mr-C4T/EVIL-ESP-AP](https://github.com/Mr-C4T/EVIL-ESP-AP) | 11 | C++ | Rogue wifi AP with fake captive portal login page for pentesting with ESP32. |
| 544 | [Mrb4by/WiFi-Scanner-in-Python-using-Scapy](https://github.com/Mrb4by/WiFi-Scanner-in-Python-using-Scapy) | 11 | Python | In this project, we will do a simple Wi-Fi scanner using Scapy library that sniffs and decode bea… |
| 545 | [nhatprx/Deauther-RTL8720DN-ESP32S3](https://github.com/nhatprx/Deauther-RTL8720DN-ESP32S3) | 11 | C++ | WiFi deauthentication tool for ESP32S3 and RTL8720DN supporting both 2.4GHz and 5GHz bands. Educa… |
| 546 | [pitube08642/Fluxion-on-ESP8266](https://github.com/pitube08642/Fluxion-on-ESP8266) | 11 | — | A advance wifi hacking tool on esp8266 |
| 547 | [Sheikh-Nightshader/Wifire](https://github.com/Sheikh-Nightshader/Wifire) | 11 | Python | Wifire: Automated Wi-Fi Scanner and Attacker. Wifire is a Python-based tool that enables Wi-Fi ne… |
| 548 | [wshen0123/mitm-rogue-WiFi-AP](https://github.com/wshen0123/mitm-rogue-WiFi-AP) | 11 | — | MITM Attack Example Code with Rogue Wi-Fi AP |
| 549 | [0xtosh/t-dongle-s3-wifi-guard](https://github.com/0xtosh/t-dongle-s3-wifi-guard) | 10 | PowerShell | Portable passive deauthentication attack detector for 2.4Ghz WiFi networks for LilyGO T-Dongle-S3 |
| 550 | [Ahmadreza1600/FSociety-Tool](https://github.com/Ahmadreza1600/FSociety-Tool) | 10 | — | FSociety Tool: WiFi Deauth, Beacon Spam, RF/IR jammer, code capture, TV-B-Gone, Evil Portal & gam… |
| 551 | [aradhyacp/Wifi-dos](https://github.com/aradhyacp/Wifi-dos) | 10 | Python | WiFi-DoS is a Python-based Wi-Fi deauthentication tool for authorized security testing. It automa… |
| 552 | [canack/kismetdeauth](https://github.com/canack/kismetdeauth) | 10 | Python | Kismet plugin for deauth AP |
| 553 | [darkLabz001/ghosttap](https://github.com/darkLabz001/ghosttap) | 10 | C | GhostTap — Wi-Fi/BLE/Zigbee pentest field unit for the Waveshare ESP32-C5-LCD-1.47: scan, sniff, … |
| 554 | [DataSC3/WIFI-BRUTS](https://github.com/DataSC3/WIFI-BRUTS) | 10 | JavaScript | A powerful WiFi dictionary attack tool with an intuitive graphical interface, designed for penetr… |
| 555 | [deepalgorithm/RFJamming-FMRadio-SDR](https://github.com/deepalgorithm/RFJamming-FMRadio-SDR) | 10 | Python | Wifi Jamming and FM Radio with Software Defined Radio |
| 556 | [defeo/phishing-demo](https://github.com/defeo/phishing-demo) | 10 | HTML | Demonstration of wifi sniffing, dns poisoning, mitm and phishing attack |
| 557 | [ErickBuster/Wi-Fi-Attack](https://github.com/ErickBuster/Wi-Fi-Attack) | 10 | HTML | Una herramienta escrita en bash y python para la automatizacion de diversos ataques a redes Wifi … |
| 558 | [iCounterBOX/ESP32_WiFi_SNIFF_BLE_ANDROID-APP_PathFinderLE_V01](https://github.com/iCounterBOX/ESP32_WiFi_SNIFF_BLE_ANDROID-APP_PathFinderLE_V01) | 10 | C++ | esp32 as wifi Sniffer connected via BLE to Android-App |
| 559 | [jrdpteam/WiFi_Toolkit](https://github.com/jrdpteam/WiFi_Toolkit) | 10 | Python | WiFi_Toolkit my tiny wifi pentesting multitool. this code is really old and it should not be used… |
| 560 | [kaotickj/WiFi-Security-Testing-Guide---Practical-Red-Team-Pentest-Manual](https://github.com/kaotickj/WiFi-Security-Testing-Guide---Practical-Red-Team-Pentest-Manual) | 10 | Python | This guide provides a practical, command level methodology for red team operators and penetration… |
| 561 | [lutfizp/AirBully](https://github.com/lutfizp/AirBully) | 10 | Shell | Semi-automated toolkit designed to perform targeted WPA3 Transition Mode downgrade attacks |
| 562 | [mavinsi/wifi-deauther](https://github.com/mavinsi/wifi-deauther) | 10 | Shell | ☠️ Bash script to facilitate the use of the aireplay-ng deauth |
| 563 | [MohitPimoli/Net-Ninja](https://github.com/MohitPimoli/Net-Ninja) | 10 | Python | Wi-Fi Jammer Script: A Python tool that performs deauthentication attacks on Wi-Fi networks by di… |
| 564 | [MrEchoFi/EchoFi_8266Deauther](https://github.com/MrEchoFi/EchoFi_8266Deauther) | 10 | — | By this device you can apply Deauthentication attack in wifi and kick out from the network easily. |
| 565 | [PrettyBoyCosmo/DuckyLan](https://github.com/PrettyBoyCosmo/DuckyLan) | 10 | PowerShell | A USB RubberDucky payload that steals Wi-Fi credentials and sends them to the attacker via STMP |
| 566 | [RemaxBoxTeam/RemaxDos](https://github.com/RemaxBoxTeam/RemaxDos) | 10 | C | This is Script tools from all attack Denial of service by C programming |
| 567 | [tworjaga/ESP32Gotchi](https://github.com/tworjaga/ESP32Gotchi) | 10 | C++ | Autonomous WPA/WPA2 handshake sniffer and AP logger for ESP32. Captures 4-way EAPOL exchanges to … |
| 568 | [AtherNet29/BW-16-RTL8720DN-DEAUTHER-EVILTWIN-NRF24](https://github.com/AtherNet29/BW-16-RTL8720DN-DEAUTHER-EVILTWIN-NRF24) | 9 | — | Advanced WiFi (2.4GHz & 5GHz) & Bluetooth Security Audit Tool Single-module design integrating du… |
| 569 | [bad-antics/nullsec-payload-autopwn](https://github.com/bad-antics/nullsec-payload-autopwn) | 9 | Shell | NullSec WiFi Pineapple Pager payload |
| 570 | [benlarsendk/PS03](https://github.com/benlarsendk/PS03) | 9 | C# | Password Sniffer- gets saved WiFi- and Chrome/Firefox passwords, encrypts and transmit to a server. |
| 571 | [Cem-Bas/jammer-detector-flipper-zero](https://github.com/Cem-Bas/jammer-detector-flipper-zero) | 9 | Dart | Dual-band RF jammer detector for Flipper Zero + Flutter companion app — Sub-GHz (315-915 MHz) + W… |
| 572 | [davlaura/void-esp32-jammer](https://github.com/davlaura/void-esp32-jammer) | 9 | C++ | Project "void": Jammer based on ESP32 and nRF24L01 module that generates interference in the Blue… |
| 573 | [enty8080/denver-camera-backdoor](https://github.com/enty8080/denver-camera-backdoor) | 9 | Python | Backdoor has been discovered by me in Denver Smart Wifi Camera SHC-150. Backdoor allows attacker … |
| 574 | [Foxanthrope/PineAlert](https://github.com/Foxanthrope/PineAlert) | 9 | JavaScript | Firefox extension delivering real-time browser notifications for WiFi Pineapple Mark 7, powered b… |
| 575 | [Fz3r0/Fz3r0_-_Wi-Fi_CTS-Frame-Attack-802.11-Frame](https://github.com/Fz3r0/Fz3r0_-_Wi-Fi_CTS-Frame-Attack-802.11-Frame) | 9 | — | 802.11 WiFi CTS Frame Attack \| PoC \| Ejemplo \| Instrucciones |
| 576 | [girs1982/GanstaWifiCyberPunker](https://github.com/girs1982/GanstaWifiCyberPunker) | 9 | — | GanstaWifiCyberPunker it firmware on Cardputer M5Stack for crack wifi networks  |
| 577 | [hamzabellouch/nethunter](https://github.com/hamzabellouch/nethunter) | 9 | Shell | NetHunter is a Automated wireless security auditing framework supporting WPA/WPA2/WPA3, WPS, PMKI… |
| 578 | [l740416/ESP8266-WifiSniffer](https://github.com/l740416/ESP8266-WifiSniffer) | 9 | Arduino | Wifi Sniffer for ESP8266 |
| 579 | [LeucoByte/mcwfcrk](https://github.com/LeucoByte/mcwfcrk) | 9 | Shell | Automated Bash tool for WPA/WPA2/WPA3 handshake & PMKID capture and cracking (aircrack-ng, hcxdum… |
| 580 | [mrblinkybling/wifi2017](https://github.com/mrblinkybling/wifi2017) | 9 | C++ | Mr. Blinky Bling WiFi sniffing badge for 2017 |
| 581 | [ponmudimr/auto-internet-login](https://github.com/ponmudimr/auto-internet-login) | 9 | Shell | Automate login for BIT's WiFi captive portal — one command to deauth your old session and connect… |
| 582 | [rusyln/ESP32-S3-ePaper-1.54-SigBin](https://github.com/rusyln/ESP32-S3-ePaper-1.54-SigBin) | 9 | — | Passive WiFi & BLE recon on a 1.54" e-paper display. PCAP harvest, handshake/PMKID capture, deaut… |
| 583 | [scriptedp0ison/Kali-Linux-Wifi-Short-Cut-Scripts](https://github.com/scriptedp0ison/Kali-Linux-Wifi-Short-Cut-Scripts) | 9 | Python | These scripts consist of an easier, shorter way to do things via wireless attacks using Aircrack-… |
| 584 | [starminPIX/sh-kitty](https://github.com/starminPIX/sh-kitty) | 9 | — | sh-kitty is a black hat/grey hat tool it has many options that are great for many things you have… |
| 585 | [Throupy/wifi-jammer](https://github.com/Throupy/wifi-jammer) | 9 | C# | A Wi-Fi Jammer (De-Auther) built to run on a Raspberry Pi 3B+ with Avalonia UI framework, |
| 586 | [TimJ86AU/kali-linux-rpi-mdk3-airmon-ng-wifi-jamming](https://github.com/TimJ86AU/kali-linux-rpi-mdk3-airmon-ng-wifi-jamming) | 9 | — | Wireless - Wifi Jamming - Raspberry PI (RPI) |
| 587 | [tusharkeshav/wifi-jam](https://github.com/tusharkeshav/wifi-jam) | 9 | Python | WiFi Jam. Disconnect anyone from any wifi or Access point. Send crafted packet for disconnecting … |
| 588 | [ty1er4499/reaver-wps](https://github.com/ty1er4499/reaver-wps) | 9 | C | Brute force attack against Wifi Protected Setup |
| 589 | [0x0806/wifi-deauther-esp8266](https://github.com/0x0806/wifi-deauther-esp8266) | 8 | C++ | This comprehensive suite combines cutting-edge WiFi attack vectors, Bluetooth Low Energy (BLE) ca… |
| 590 | [0xbitx/DEDSEC_WIREMON](https://github.com/0xbitx/DEDSEC_WIREMON) | 8 | PHP | WIREMON is a Linux-based wifi attack framework tool. |
| 591 | [Aayush9029/esp8266_deauther](https://github.com/Aayush9029/esp8266_deauther) | 8 | — | Affordable WiFi hacking platform for testing and learning + Native iOS, watchOS support. |
| 592 | [archkhertdev/wifiattack](https://github.com/archkhertdev/wifiattack) | 8 | Shell | A powerful WiFi Distruption tool designed to kick devices that's connected to a network and displ… |
| 593 | [berkantay/wirect-firmware](https://github.com/berkantay/wirect-firmware) | 8 | C++ | WiFi Sniffer with ESP8266 |
| 594 | [Bilal-Belli/DictionaryWifiAttackTool](https://github.com/Bilal-Belli/DictionaryWifiAttackTool) | 8 | Python | This repository presents a simple Python program for testing a large number of passwords (diction… |
| 595 | [bishwabikash/wifi-autopwn](https://github.com/bishwabikash/wifi-autopwn) | 8 | Shell | WiFi Auto-PWN v1.0 - Advanced Multi-Generation WiFi Penetration Testing Framework \| Complete cov… |
| 596 | [BlackTechX011/DeautherX-lib](https://github.com/BlackTechX011/DeautherX-lib) | 8 | C | The Unified ESP8266 Wi-Fi Security & Testing Library |
| 597 | [blwhit/WifiReaper](https://github.com/blwhit/WifiReaper) | 8 | Shell | Automate large-scale Wi-Fi deauthentication attacks. Automatically discover vulnerable wireless n… |
| 598 | [Chibald/Esp-WifiSniffer-For-Openhab](https://github.com/Chibald/Esp-WifiSniffer-For-Openhab) | 8 | C++ |  |
| 599 | [Demontager/HoneyWIFI](https://github.com/Demontager/HoneyWIFI) | 8 | Shell | Wi-Fi access point for pentest purposes |
| 600 | [dev0root6/EvilTwin-ESP8266](https://github.com/dev0root6/EvilTwin-ESP8266) | 8 | C++ | 100% Working ESP8266 EVIL TWIN ATTACK. This code implements an ESP8266-based WiFi deauthenticatio… |
| 601 | [Dextelktro/Black-Crow-ESP32-C5-Firmware](https://github.com/Dextelktro/Black-Crow-ESP32-C5-Firmware) | 8 | C++ | BC Firmware ESP32 C5-Deauth dengan Nuker untuk 2.4Ghz dan 5Ghz yang dikendalikan oleh BLE dengan … |
| 602 | [errorfiathck/wifi-Brutefurce](https://github.com/errorfiathck/wifi-Brutefurce) | 8 | Python | in this python code we attack on wifi`s network useing brutefurceing  |
| 603 | [Evil0ctopus/wigglefish](https://github.com/Evil0ctopus/wigglefish) | 8 | Kotlin | Passive Wi-Fi/BLE field scanner: ESP32-C5 + Android USB controller — metadata-only, authorized ob… |
| 604 | [gdamdam/wifi-deauthdetector](https://github.com/gdamdam/wifi-deauthdetector) | 8 | C++ | WiFi Deauth Detector - a cute deauthentication detector for ESP8266 with OLED display |
| 605 | [gpimblott/ESP8266_Wifi_Analyst](https://github.com/gpimblott/ESP8266_Wifi_Analyst) | 8 | C++ | Command line Wifi utilities on an ESP 8266.  Includes scanning, fake beacons and deauth. |
| 606 | [HiddenSwagMan/ESP8266-BrutalDeauth](https://github.com/HiddenSwagMan/ESP8266-BrutalDeauth) | 8 | Arduino | This allow your ESP8266 to deauth every WiFi devices as long as it's turned on ! |
| 607 | [HUGOW04/FakeWifi](https://github.com/HUGOW04/FakeWifi) | 8 | C++ | Phishing is a type of social engineering where an attacker sends a fraudulent (e.g., spoofed, fak… |
| 608 | [hXR16F/Wi-Fi-Cracker](https://github.com/hXR16F/Wi-Fi-Cracker) | 8 | Batchfile | Slow but working Wi-Fi password recovery tool based on wordlist attack. |
| 609 | [IT-DIVIDMARK/ESP32-wifi-deauther](https://github.com/IT-DIVIDMARK/ESP32-wifi-deauther) | 8 | C++ | This project utilizes the ESP32 microcontroller to create a powerful Wi-Fi deauther tool. It allo… |
| 610 | [louisvarley/openwrt-probe-request-sniffer-luci](https://github.com/louisvarley/openwrt-probe-request-sniffer-luci) | 8 | Lua | A Wifi Probe Request Python Script with a Luci page to read the contents |
| 611 | [LuxStatera/flock-hunter-cyd-wifi](https://github.com/LuxStatera/flock-hunter-cyd-wifi) | 8 | C++ | WiFi-based Flock Safety camera detector for ESP32 CYD. Passively sniffs 32 OUI prefixes with PCAP… |
| 612 | [musagithub1/wifiHacking](https://github.com/musagithub1/wifiHacking) | 8 | Python | Ultimate Python-based WiFi hacking and security auditing framework. Automates PMKID, WPA offline … |
| 613 | [nistordarius26h-ship-it/esp32jamm](https://github.com/nistordarius26h-ship-it/esp32jamm) | 8 | C++ | ESP32 Multi-Protocol Wireless Sniffing Platform for passive Wi-Fi, Bluetooth, BLE, and RF signal … |
| 614 | [OhDamnn/wifi_hack_gui](https://github.com/OhDamnn/wifi_hack_gui) | 8 | Python | Advanced GUI for WiFi Penetration Testing Integrates: wifipumpkin3, airgeddon, KRACK attacks, Cap… |
| 615 | [rajtilak-2020/ESP32-wifi-sniffer-tool](https://github.com/rajtilak-2020/ESP32-wifi-sniffer-tool) | 8 | C++ | A real-time Wi-Fi packet sniffer built using ESP32. Captures MAC addresses, signal strength (RSSI… |
| 616 | [ripper121/odroidgowifisniffer](https://github.com/ripper121/odroidgowifisniffer) | 8 | HTML | Odroid Go Wifi Sniffer PCAP |
| 617 | [Ro9ueAdmin/wifi-cracking-dictionary-attack-](https://github.com/Ro9ueAdmin/wifi-cracking-dictionary-attack-) | 8 | — | 1.airmon-ng (to know status of N/W) 2.airmon-ng start wlan0 (to enable monitor mode) 3.airodump-n… |
| 618 | [rodolfomarianocy/Tricks-Wi-Fi-Pentest](https://github.com/rodolfomarianocy/Tricks-Wi-Fi-Pentest) | 8 | — | Wi-Fi Penetration Testing |
| 619 | [Slax38/WiFiDeauther](https://github.com/Slax38/WiFiDeauther) | 8 | Python | DDoS attack on wireless networks |
| 620 | [tanc7/Wifi-Attack-Auto-Loader-MANA-](https://github.com/tanc7/Wifi-Attack-Auto-Loader-MANA-) | 8 | Python | Easily walks you through the Mana Evil AP Attack (While eliminating common mistakes). All promise… |
| 621 | [Theus-Vieira/jammer_2.4ghz_wifi_bluetooth](https://github.com/Theus-Vieira/jammer_2.4ghz_wifi_bluetooth) | 8 | C++ | Projeto de Jammer 2.4 GHz wifi e bluetooth utilizando um ESP32S WROOM e dois módulos nRF24L01. Pr… |
| 622 | [TotallyNotAHaxxer/Red-Rabbit-1.0](https://github.com/TotallyNotAHaxxer/Red-Rabbit-1.0) | 8 | Ruby | Red Rabbit is a framework for Wifi attacks, Fake AP's, and web scanning <still adding some> |
| 623 | [TuHiN22/WiFiT](https://github.com/TuHiN22/WiFiT) | 8 | Python | Professional WPS Testing Toolkit for Rooted Android Devices with Termux - Advanced WiFi penetrati… |
| 624 | [xiv3r/dhcp-starvation](https://github.com/xiv3r/dhcp-starvation) | 8 | C++ | Powerful wifi dhcp starvation attack using termux \| no root |
| 625 | [XrangerCY19/Simple-DOS-Wifi-jammer-aircrack-ng-Kali-linux-NoobEdition](https://github.com/XrangerCY19/Simple-DOS-Wifi-jammer-aircrack-ng-Kali-linux-NoobEdition) | 8 | Shell | Easy to use on-the-go wifi jammer. |
| 626 | [yeahhub/wifidos](https://github.com/yeahhub/wifidos) | 8 | Shell | Wireless Dos Attack with wifidos Bash Script |
| 627 | [26zl/gadgets-tools](https://github.com/26zl/gadgets-tools) | 7 | Shell | Tools and firmware for various Flipper Zero / ESP32 / phone pentest gadgets — one folder per devi… |
| 628 | [accoleon/marauders-map](https://github.com/accoleon/marauders-map) | 7 | JavaScript | WiFi positioning through packet sniffing |
| 629 | [ANIMAALS/WatchDog-2.4](https://github.com/ANIMAALS/WatchDog-2.4) | 7 | C++ | Portable 2.4 GHz wireless security analyser — ESP32 + nRF24L01. Jammer detection, BLE tracker ID,… |
| 630 | [Anonymous40443/SCAN-X](https://github.com/Anonymous40443/SCAN-X) | 7 | Python | ⚔️ SCAN-X v3.0 🩸 The Ultimate Blood-Tiger Recon Engine. Automate 15+ Nmap scans, bypass firewalls… |
| 631 | [Ares-21/AeroSpy](https://github.com/Ares-21/AeroSpy) | 7 | Python | A simple WiFi scanning GUI for scanning the available wireless networks  |
| 632 | [bad-antics/nullsec-pineapple-ops](https://github.com/bad-antics/nullsec-pineapple-ops) | 7 | JavaScript | 🍍 Command & Control Dashboard for WiFi Pineapple Pager & Mark VII — Web-based ops center with rec… |
| 633 | [badcofn/WifiProbeSniffer](https://github.com/badcofn/WifiProbeSniffer) | 7 | Python | Wifi probe request sniffer for logging wifi probes near you into a db. |
| 634 | [bertrik/espwifisniff](https://github.com/bertrik/espwifisniff) | 7 | C++ | Experiment to create a wifi sniffer based on an ESP8266 |
| 635 | [codewithharit/WIFI-Jammer-FILE](https://github.com/codewithharit/WIFI-Jammer-FILE) | 7 | — | ESP8266 Node MCU Jammer File |
| 636 | [cx693/Rust_ESP32_Dome](https://github.com/cx693/Rust_ESP32_Dome) | 7 | Rust | A collection of Rust bare-metal examples for ESP32 using the `esp-hal` framework. Covers GPIO, UA… |
| 637 | [Eberth-sys/Deauth-Alert-WiFi-IoT-System](https://github.com/Eberth-sys/Deauth-Alert-WiFi-IoT-System) | 7 | TypeScript | Open-source defensive IoT system for real-time detection and alerting of Wi-Fi 802.11 deauthentic… |
| 638 | [emre-h/WIFI-Dictionary-Attack-Tool](https://github.com/emre-h/WIFI-Dictionary-Attack-Tool) | 7 | Java | WIFI Dictionary Attack Tool for Android Operating System. |
| 639 | [faisalfs10x/WiFi-Pentest-Cheat-Sheet](https://github.com/faisalfs10x/WiFi-Pentest-Cheat-Sheet) | 7 | — |  |
| 640 | [Ghael-V/LilyOS](https://github.com/Ghael-V/LilyOS) | 7 | C | Custom LVGL-based firmware for the LilyGo T-Embed CC1101 (ESP32-S3): WiFi auditing (deauth, hands… |
| 641 | [greatgaga/EspViking](https://github.com/greatgaga/EspViking) | 7 | C++ | Firmware made for ESP32 that is made for wifi pentesting. |
| 642 | [IMARv2/iphisher](https://github.com/IMARv2/iphisher) | 7 | Python | Advanced WiFi credential harvester for penetration testers — evil twin, OS-native portals, WPS Pi… |
| 643 | [iwheeliemycbr/5G_WiFi_Deauth_Attack_Flipper0](https://github.com/iwheeliemycbr/5G_WiFi_Deauth_Attack_Flipper0) | 7 | — | BW16 Flipper0 5g WiFi Deauth Attack files |
| 644 | [JEONTAEMIN2007/Esp32-WiFi-Hacking](https://github.com/JEONTAEMIN2007/Esp32-WiFi-Hacking) | 7 | C++ | Google account hijacking |
| 645 | [JizzyRivers/jam](https://github.com/JizzyRivers/jam) | 7 | Shell | Give your de-Amazonized Echo Dot 2 (Biscuit) some Jam — on-device WAN blocking, wake word switchi… |
| 646 | [KaSaNaa/ESP32-WiFi-Sniffer](https://github.com/KaSaNaa/ESP32-WiFi-Sniffer) | 7 | C |  this tool passively captures and logs probe request packets to demonstrate the potential securit… |
| 647 | [leonrinkel/esp32-mac-sniffer](https://github.com/leonrinkel/esp32-mac-sniffer) | 7 | C |  |
| 648 | [less-prog/wifi-pentest-handshake](https://github.com/less-prog/wifi-pentest-handshake) | 7 | Shell | Audit de sécurité Wi-Fi : scan WPS, attaque Pixie Dust, capture de handshake WPA2 avec Flipper Ze… |
| 649 | [lraton/ESP32-Wardriving-Deauther](https://github.com/lraton/ESP32-Wardriving-Deauther) | 7 | C | ESP32-Wardriving-Deauther is a WiFi security testing tool for the ESP32 platform, allowing for Wi… |
| 650 | [MuhamadJalalDev/MIM-attack-ESP32](https://github.com/MuhamadJalalDev/MIM-attack-ESP32) | 7 | C++ | ever thought about hacking wifi passwords with the esp32 ? well now you can  |
| 651 | [nathshobhan/wifijammer_nodemcu](https://github.com/nathshobhan/wifijammer_nodemcu) | 7 | C | code to jam the whole wifi network using cloning technique |
| 652 | [paolini99/Brute_Force-Dictionary_Attack_on_WiFi](https://github.com/paolini99/Brute_Force-Dictionary_Attack_on_WiFi) | 7 | — | 🔐 WPA2 WiFi Dictionary Attack Capture handshakes and crack passwords using a wordlist. For educat… |
| 653 | [pepeangell5/ESP8266-DEAUTHER](https://github.com/pepeangell5/ESP8266-DEAUTHER) | 7 | C | Deauther de laboratorio para ESP8266 enfocado en pruebas educativas de seguridad WiFi 2.4 GHz, an… |
| 654 | [phalloc/phalloc-sniffer](https://github.com/phalloc/phalloc-sniffer) | 7 | C++ | MAC Address sniffer. Captures packets on the WiFi network and outputs the MAC address and RSSI to… |
| 655 | [Qbaa134/Beacon-Spammer](https://github.com/Qbaa134/Beacon-Spammer) | 7 | HTML | The Beacon Spammer is a tool that sends fake Wi-Fi beacon frames, making it look like multiple wi… |
| 656 | [rff-glitch/wifi-jamming](https://github.com/rff-glitch/wifi-jamming) | 7 | Shell | 🚨 WiFi DEAUTH BLASTER 🔥                   Automated multi-target deauthentication attack system u… |
| 657 | [ricardojoserf/pywisam](https://github.com/ricardojoserf/pywisam) | 7 | Python | A Wifi pentesting framework written in Python |
| 658 | [s0m3-1/wifiBuddy](https://github.com/s0m3-1/wifiBuddy) | 7 | Python | A Buddy u ain't wanna be missing |
| 659 | [Sh7yk/Warwalking](https://github.com/Sh7yk/Warwalking) | 7 | Shell | Simple bash scripts on the Wifite base to automatically check all access points on the go |
| 660 | [Sota-0/VeilCast-Evil-Twin-Framework](https://github.com/Sota-0/VeilCast-Evil-Twin-Framework) | 7 | Python | VeilCast is a semi-automated Evil Twin attack Hacking framework written in Python. It simplifies … |
| 661 | [squidward404/wifi-crasher](https://github.com/squidward404/wifi-crasher) | 7 | Python | just a glorified version of aircrack-ng deauth script. |
| 662 | [tasos12/ESP32_WiFiSniffer_with_OLED](https://github.com/tasos12/ESP32_WiFiSniffer_with_OLED) | 7 | C | ESP32 wifi sniffer using oled to select the network to sniff built with arduino core for esp32 |
| 663 | [TECH7Fox/deauth-detector-hass-addons](https://github.com/TECH7Fox/deauth-detector-hass-addons) | 7 | Python | Detects wifi deauth attacks |
| 664 | [Tweeks-va/Kali_RPi_RIAB](https://github.com/Tweeks-va/Kali_RPi_RIAB) | 7 | Shell | This is a HOWTO and scripts for turning a RaspberryPi 2/3/4 into a Cyber Range In A Box (RIAB).. … |
| 665 | [vnsh02/Air-Kick](https://github.com/vnsh02/Air-Kick) | 7 | Python | Simple script for Wifi Deauth attack |
| 666 | [wirebits/DeauthEye](https://github.com/wirebits/DeauthEye) | 7 | C++ | A tool that detects deauthentication attacks on WiFi using BW16. |
| 667 | [yadhumanikandan/esp8266-wifi-hacking-device](https://github.com/yadhumanikandan/esp8266-wifi-hacking-device) | 7 | Rich Text Format | An all in one wifi hacking tool using esp8266 using micropython |
| 668 | [0xF35/Disrupt](https://github.com/0xF35/Disrupt) | 6 | Python | A Python-based WiFi deauther. |
| 669 | [0xIDA/ESP-SEC-TOOL](https://github.com/0xIDA/ESP-SEC-TOOL) | 6 | C | ESP32 WiFi/BLE Security Testing Toolkit - portable wireless auditing tool with mobile web dashboard |
| 670 | [5h4d0wn1k/airguard](https://github.com/5h4d0wn1k/airguard) | 6 | Python | Wireless defense & monitoring suite - WIDS sensor, deauth/evil-twin/rogue-AP detection, beacon an… |
| 671 | [5h4d0wn1k/h13-wifi-jammer](https://github.com/5h4d0wn1k/h13-wifi-jammer) | 6 | C++ | Wi-Fi jamming and resilience research - interference testing against own-lab networks. |
| 672 | [5h4d0wn1k/w1-deauth-eng](https://github.com/5h4d0wn1k/w1-deauth-eng) | 6 | Python | 802.11 deauthentication frame parser, spoofed-MAC heuristics, and PMF resilience analysis for aut… |
| 673 | [5h4d0wn1k/w2-evil-twin](https://github.com/5h4d0wn1k/w2-evil-twin) | 6 | Python | Evil-twin and rogue-AP detection lab — 802.11 beacon fingerprinting to identify cloned access poi… |
| 674 | [5h4d0wn1k/w3-probe-resp](https://github.com/5h4d0wn1k/w3-probe-resp) | 6 | Python | Wi-Fi probe-request responder for wireless security research — ESP32-C6 promiscuous sniffer with … |
| 675 | [5h4d0wn1k/w6-beacon-analysis](https://github.com/5h4d0wn1k/w6-beacon-analysis) | 6 | Python | 802.11 beacon analyzer - channel/rate/IE parsing and anomaly fingerprinting. |
| 676 | [5h4d0wn1k/w7-wids-sensor](https://github.com/5h4d0wn1k/w7-wids-sensor) | 6 | Python | WIDS sensor - rogue AP, deauth and beacon-flood detection with alerting. |
| 677 | [5h4d0wn1k/w9-ble-spoofer](https://github.com/5h4d0wn1k/w9-ble-spoofer) | 6 | Python | BLE spoofer for wireless security research — byte-exact ADV PDU forging, CRC-24 validation, lab-s… |
| 678 | [adialamsyahardi/Autologin-FreeBiznet](https://github.com/adialamsyahardi/Autologin-FreeBiznet) | 6 | PHP | AutoLogin @FreeBiznetHotspot, GAPERLU LAGI LOGIN MANUAL TIAP 2 JAM ! |
| 679 | [adithya9090/Termux-Deauther](https://github.com/adithya9090/Termux-Deauther) | 6 | — | Use Your Android Phone To Deauth WiFi Networks With Termux |
| 680 | [Anak0nd4/WifiExfiltrateDiscord](https://github.com/Anak0nd4/WifiExfiltrateDiscord) | 6 | PowerShell | A simple powershell script to exfiltrate wifi passwords using discord.  |
| 681 | [AtherNet29/Esp8266-Deauther-2.4-Ghz-Jammer-Bluetooth](https://github.com/AtherNet29/Esp8266-Deauther-2.4-Ghz-Jammer-Bluetooth) | 6 | — | 🎯 ESP8266 Deauther & BT Jammer. Features: Evil Twin, Auto-Password Verify, Beacon Spam, Rogue AP,… |
| 682 | [Axagt40/Vandeta](https://github.com/Axagt40/Vandeta) | 6 | C++ | Bruce (1.16.1) modded for the LilyGo T-Embed CC1101 Plus |
| 683 | [AyushGorlawar/ESP-Hidden-Features](https://github.com/AyushGorlawar/ESP-Hidden-Features) | 6 | C++ | Explore hidden features, stealth tricks, and ethical hacks using ESP8266/ESP32 — beyond basic IoT… |
| 684 | [bad-antics/nullsec-wifi](https://github.com/bad-antics/nullsec-wifi) | 6 | Kotlin | 📶 NullSec WiFi - Advanced Wireless Security Analyzer \| Channel analysis, deauth detection, secur… |
| 685 | [bad-antics/wifipineapplepager](https://github.com/bad-antics/wifipineapplepager) | 6 | — | 🍍 WiFi Pineapple MK7 automation, pager payloads & mass deployment toolkit \| 100+ payloads \| Nul… |
| 686 | [bman46/deauth-esp-rs](https://github.com/bman46/deauth-esp-rs) | 6 | Rust | A rust based WiFi deauther for ESP32. |
| 687 | [brighteyekid/ESP8266-WiFi-Pentesting-Tool](https://github.com/brighteyekid/ESP8266-WiFi-Pentesting-Tool) | 6 | C++ | ESP8266-WiFi-Pentesting-Tool  A comprehensive WiFi security testing toolkit for ESP8266 |
| 688 | [Calmclireveal/wifi-deauth-attack](https://github.com/Calmclireveal/wifi-deauth-attack) | 6 | Rust | A wireless deauthentication tool that disconnects every connected device from a target Wi-Fi netw… |
| 689 | [Coderxrohan/Wifi-Deauth-Evil-Twin](https://github.com/Coderxrohan/Wifi-Deauth-Evil-Twin) | 6 | C++ | ⚠️ WiFi Deauth & Evil Twin Attack Toolkit is a penetration testing project focused on simulating … |
| 690 | [d33tah/wifibacon](https://github.com/d33tah/wifibacon) | 6 | Python | Sniffs on the WiFi network and generates a graph showing the communication between the devices, i… |
| 691 | [darkLabz001/grimoire](https://github.com/darkLabz001/grimoire) | 6 | C++ | Self-contained ESP32-C5 Wi-Fi recon and attack console running inside a wizard pet: dual-band (2.… |
| 692 | [david-griffith/esp8266-sniffer](https://github.com/david-griffith/esp8266-sniffer) | 6 | C | A simple sniffer for Aeroscout wifi tags |
| 693 | [dcrisan/WiFi-802.11-Demo-Sniffer](https://github.com/dcrisan/WiFi-802.11-Demo-Sniffer) | 6 | Python | This 802.11 sniffer written in Python provides a useful tool to raise awareness at the amount of … |
| 694 | [Debajyoti0-0/Arduino-WiFi-Deauther-Detector](https://github.com/Debajyoti0-0/Arduino-WiFi-Deauther-Detector) | 6 | C++ | Detect deauthentication attack using NodeMCU without using any external leds. |
| 695 | [DX4GREY/WiFi_Deauther](https://github.com/DX4GREY/WiFi_Deauther) | 6 | Python | The script is a tool for scanning and attacking wireless networks. It discovers active access poi… |
| 696 | [ericohm/Wifi-sniffer](https://github.com/ericohm/Wifi-sniffer) | 6 | Python | How to store Mac:address, timestamp and gps and signal strength |
| 697 | [Ethical-Vikash/WiFi-Phiser](https://github.com/Ethical-Vikash/WiFi-Phiser) | 6 | C++ | WiFi Hacking with an ESP8266 - Deauther & Evil-Twin Attack |
| 698 | [Foxlith/strykeross-6.0.1-secure](https://github.com/Foxlith/strykeross-6.0.1-secure) | 6 | Smali | StrykerOSS 6.0.1 APK + fuentes — versión asegurada (F1: decode SSID seguro, filtro control-chars)… |
| 699 | [fuck-standardized-testing/rpi-wifi-jammer](https://github.com/fuck-standardized-testing/rpi-wifi-jammer) | 6 | — | Build your own wifi-jammer with raspberry pi! |
| 700 | [GuruprasadaShridharHegde/Wifi-Jammer-and-Detector](https://github.com/GuruprasadaShridharHegde/Wifi-Jammer-and-Detector) | 6 | — | A hacking mind can hack the hacker. |
| 701 | [hermit148/Hermit-ESP8266-Mint-Box-WIFI-Pentest](https://github.com/hermit148/Hermit-ESP8266-Mint-Box-WIFI-Pentest) | 6 | — | Hermit-ESP8266-Mint-Box-Attack And Reserch Tool |
| 702 | [Hmkz0x00/wireless-assessment-center](https://github.com/Hmkz0x00/wireless-assessment-center) | 6 | PHP | WiFi-Pineapple-style wireless security assessment platform — a native Frieren/OpenWrt module. Rec… |
| 703 | [ipv4shh/ESPTOOL2](https://github.com/ipv4shh/ESPTOOL2) | 6 | C++ | ESPTOOL2 — Multi-band wireless toolkit based on ESP32. Wi-Fi & BLE attacks, web interface, Master… |
| 704 | [Isonimus/wifi-sapper](https://github.com/Isonimus/wifi-sapper) | 6 | C++ | Autonomous handshake hunter for the ESP-32. |
| 705 | [jitujak55/WiFi-Pentesting-Tool](https://github.com/jitujak55/WiFi-Pentesting-Tool) | 6 | Python | comprehensive, modular WiFi security auditing framework designed for WEP and WPA2/WPA3 penetratio… |
| 706 | [krishrp0001/esp32-wifi-hacking](https://github.com/krishrp0001/esp32-wifi-hacking) | 6 | — | wifi deauther, wifi penetration tool, evil twin attack, air crack, honeypot wifi hacking, fake wifi |
| 707 | [leingangzj/yui](https://github.com/leingangzj/yui) | 6 | C++ | Pocket comms + pentest companion firmware for the M5Stack Cardputer ADV. Drives a Kenwood TH-D75 … |
| 708 | [lsw29475/WifiDestoryer](https://github.com/lsw29475/WifiDestoryer) | 6 | C | A small program running on the wifipineapple, simplifying from the aircrack-ng, by scanning aroun… |
| 709 | [MAAYTHM/deauth_wif_for_windows](https://github.com/MAAYTHM/deauth_wif_for_windows) | 6 | Python | A Python3 tool, which simply sends ∞ deauth packets to wifi becoz of which victim device cannot a… |
| 710 | [Matter0x00/AWESOME-Wifi-Pentest](https://github.com/Matter0x00/AWESOME-Wifi-Pentest) | 6 | — |  |
| 711 | [nd50095800/IISR-A-Secure-Router-for-IoT-Networks](https://github.com/nd50095800/IISR-A-Secure-Router-for-IoT-Networks) | 6 | — | With the increasing popularity of IoT devices, the vulnerabilities & security issues concerned wi… |
| 712 | [NextrixVFX/NRF24-Jammer](https://github.com/NextrixVFX/NRF24-Jammer) | 6 | C++ | NRF24L01-E01 Based Jammer that hits wifi and bluetooth consistantly |
| 713 | [no1se2/no1seWIFI---WiFi-Toolkit-for-Pentesters](https://github.com/no1se2/no1seWIFI---WiFi-Toolkit-for-Pentesters) | 6 | Python | Capture handshakes, conduct deauth attacks, and crack passwords with ease. |
| 714 | [oussamaelaji/DoS_WiFi_Jammer](https://github.com/oussamaelaji/DoS_WiFi_Jammer) | 6 | Python | WiFi DoS (Denial of Service) attack to send deauthentication frame to clients |
| 715 | [PanduTechLab/Bluetooth-Wifi-scanner-Jammer](https://github.com/PanduTechLab/Bluetooth-Wifi-scanner-Jammer) | 6 | C++ | A portable ESP32-based wireless research tool with BLE, Wi-Fi, and 2.4GHz nRF24 utilities on a 12… |
| 716 | [patrickhaahr/esp32-wifi-sniffer](https://github.com/patrickhaahr/esp32-wifi-sniffer) | 6 | Rust | ESP32 WiFi device tracking system with RSSI-based trilateration. Real-time web dashboard for indo… |
| 717 | [prabhatsoni14/ESP32-WiFi-PenTest-Tool](https://github.com/prabhatsoni14/ESP32-WiFi-PenTest-Tool) | 6 | C++ | Educational ESP32 tool demonstrating WiFi security vulnerabilities — Evil Twin, deauthentication,… |
| 718 | [rahuldudi0713/WiFi_hacking_Device](https://github.com/rahuldudi0713/WiFi_hacking_Device) | 6 | C++ | Hack any wifi with NodeMCU esp8266 Board |
| 719 | [s-b-repo/rasberry-lie](https://github.com/s-b-repo/rasberry-lie) | 6 | Python | a tool that will flood deauth packets to all wifi until control + c is pressed |
| 720 | [s-r-e-e-r-a-j/VALAK](https://github.com/s-r-e-e-r-a-j/VALAK) | 6 | C++ | VALAK is a powerful ESP32-based tool that performs real Evil Twin attacks by creating identical c… |
| 721 | [saifxionty/Evil-Twin-And-Deauther](https://github.com/saifxionty/Evil-Twin-And-Deauther) | 6 | — | Turns ESP8266 into a WiFi attack tool. Performs deauth attacks, creates Evil Twin hotspots, and c… |
| 722 | [sifirib/jammerDEAUTHway](https://github.com/sifirib/jammerDEAUTHway) | 6 | Python | I am not responsible for ill-usage |
| 723 | [slundell/wifi-presence](https://github.com/slundell/wifi-presence) | 6 | Python | Simple presence detection by passive wifi sniffing. esp8266 and Python |
| 724 | [ToaderMatei/ghostbox](https://github.com/ToaderMatei/ghostbox) | 6 | Python | Modular security research toolkit for Raspberry Pi Zero 2W — USB HID injection, WiFi scanner, Blu… |
| 725 | [Vitor-Oliveira84/WiFi-Pentesting-Guide](https://github.com/Vitor-Oliveira84/WiFi-Pentesting-Guide) | 6 | — | Comprehensive WiFi penetration testing guide - techniques, tools, and defenses |
| 726 | [WorkofAditya/Deauth-Simulator](https://github.com/WorkofAditya/Deauth-Simulator) | 6 | Shell | This script automates WiFi deauth attacks, enabling monitor mode, capturing handshakes, and safel… |
| 727 | [xFreed0m/Wifi_plug](https://github.com/xFreed0m/Wifi_plug) | 6 | Python | short python script to install wifi pentesting tools - made for kali |
| 728 | [xiaohe4966/esp32-wifi-sniffer](https://github.com/xiaohe4966/esp32-wifi-sniffer) | 6 | C++ | 基于 ESP32-S3 (支持 2.4GHz/5GHz 双频) 的 WiFi 抓包与字典攻击开源工具，用于无线安全研究。 |
| 729 | [z2labs/Sniff-Sight](https://github.com/z2labs/Sniff-Sight) | 6 | Python | Packet sniffer + RF spectrum side by side: pair 802.15.4/BLE/Wi-Fi packets with their RF bursts u… |
| 730 | [5h4d0wn1k/w1-wifi-scanner](https://github.com/5h4d0wn1k/w1-wifi-scanner) | 5 | Python | Wi-Fi scanner - SSID/channel/security-mode discovery and visualization. |
| 731 | [5h4d0wn1k/w10-wpa3-survey](https://github.com/5h4d0wn1k/w10-wpa3-survey) | 5 | Python | WPA3/WPA2 survey tool - security-mode census and transition-vulnerability checking. |
| 732 | [5h4d0wn1k/w2-deauth-detect](https://github.com/5h4d0wn1k/w2-deauth-detect) | 5 | Python | Deauth attack detector - monitor-mode heuristics that flag deauth floods and frame anomalies. |
| 733 | [5h4d0wn1k/w3-probe-audit](https://github.com/5h4d0wn1k/w3-probe-audit) | 5 | Python | Wi-Fi probe-request auditor - passive client-probe collection and SSID-leak analysis. |
| 734 | [5h4d0wn1k/w4-crack-pipeline](https://github.com/5h4d0wn1k/w4-crack-pipeline) | 5 | Python | WPA/WPA2/PMKID password audit pipeline — handshake/PMKID detection, hcxpcapngtool conversion, has… |
| 735 | [5h4d0wn1k/w5-nrf-observer](https://github.com/5h4d0wn1k/w5-nrf-observer) | 5 | Python | nRF observer - Nordic 2.4 GHz sniffing and packet-stream analysis for BLE lab work. |
| 736 | [5h4d0wn1k/w6-beacon-flood](https://github.com/5h4d0wn1k/w6-beacon-flood) | 5 | Python | Beacon flood generator - stress-tests client association and wireless IDS systems. |
| 737 | [5h4d0wn1k/w7-deauth-capture](https://github.com/5h4d0wn1k/w7-deauth-capture) | 5 | Python | Deauth capture utility - hunts handshakes, captures frames and logs offenders. |
| 738 | [5h4d0wn1k/w8-covert-beacon](https://github.com/5h4d0wn1k/w8-covert-beacon) | 5 | Python | 802.11 covert-channel toolkit - vendor-IE payload encoding in beacon/probe-response frames plus S… |
| 739 | [5h4d0wn1k/w8-evil-portal](https://github.com/5h4d0wn1k/w8-evil-portal) | 5 | Python | Evil portal / captive-portal builder - phishing landing pages for wireless security labs. |
| 740 | [5h4d0wn1k/w9-resilient-tele](https://github.com/5h4d0wn1k/w9-resilient-tele) | 5 | Python | Resilient telemetry system - wireless data-link redundancy and failover experiments. |
| 741 | [99stealth/wifi-evil-twin-detection-with-knn](https://github.com/99stealth/wifi-evil-twin-detection-with-knn) | 5 | Jupyter Notebook |  |
| 742 | [abhi-abhi86/spiffy](https://github.com/abhi-abhi86/spiffy) | 5 | Python | Advanced cybersecurity framework combining offensive (WiFi radar, auto-exploit, DNS enum, passwor… |
| 743 | [aidevsurya/ESP8266-Captive-Portal](https://github.com/aidevsurya/ESP8266-Captive-Portal) | 5 | C++ | This is simple program for NodeMCU, ESP8266, ESP32, ESP-12 F/E to perform Captive Portal Attack f… |
| 744 | [anudeepND/esp8266_2.0.0](https://github.com/anudeepND/esp8266_2.0.0) | 5 | — | esp8266 SDK 2.0.0 for ARM architecture.  |
| 745 | [AplAddict/Arduino-Pentesting-Tool](https://github.com/AplAddict/Arduino-Pentesting-Tool) | 5 | PHP | Arduino MKR 1000 Pentesting Tool |
| 746 | [aryanvish2006/MiniJammer](https://github.com/aryanvish2006/MiniJammer) | 5 | — | a small device which lets you jam anyones wifi |
| 747 | [axosecurity/wanjamer](https://github.com/axosecurity/wanjamer) | 5 | Python | its a wifi jammer.It is made of python script.its just sent dautantication pacakets to jamm the n… |
| 748 | [ayhamal/ESP32-Wifi-Sniffer](https://github.com/ayhamal/ESP32-Wifi-Sniffer) | 5 | C++ | Wifi sniffer builded with Arduino Framework on board ESP-WROOM-32D (esp32doit-devkit-v1) |
| 749 | [BabakStars/Wifi_scanner_jammer](https://github.com/BabakStars/Wifi_scanner_jammer) | 5 | — |  |
| 750 | [barratt/esp8266-wifi-tracking](https://github.com/barratt/esp8266-wifi-tracking) | 5 | C++ | Gives the ESP8266 the ability to sniff WiFi packets in the air and report back to a server for fu… |
| 751 | [dappoo/PEvilTwin](https://github.com/dappoo/PEvilTwin) | 5 | C++ | ESP8266-based Evil Twin attack tool for WiFi network testing and security research. |
| 752 | [dawoodkhatri1/Wifi-Jammer-using-arduino-uno](https://github.com/dawoodkhatri1/Wifi-Jammer-using-arduino-uno) | 5 | C | A C-based simulation of WiFi jamming for educational use. It mimics network scanning, displays fa… |
| 753 | [dherl0623/wifi-deauth](https://github.com/dherl0623/wifi-deauth) | 5 | Shell | Automated wifi deauthenticator of clients using MDK3. |
| 754 | [Dhirentek/network_hack](https://github.com/Dhirentek/network_hack) | 5 | Shell | This is my first basic bash script that I am uploading on github, as this was created 1 year ago … |
| 755 | [DX-PE/SurveillanceHound](https://github.com/DX-PE/SurveillanceHound) | 5 | C++ | ESP32 WiFi/BLE Sniffer Game, your pet hound sniffs out surveillance devices like Flock and many m… |
| 756 | [enesehs/esp32-jammer](https://github.com/enesehs/esp32-jammer) | 5 | — | ESP32 Bluetooth Wifi Jammer |
| 757 | [ESP32w/ESP32-Hack-device-](https://github.com/ESP32w/ESP32-Hack-device-) | 5 | C++ | HACK DEVICE ESP32 v2.0.1 |
| 758 | [feisuzhu/wifikiller](https://github.com/feisuzhu/wifikiller) | 5 | C | A tool for tearing down and password sniffing PPPoE connections on open WiFi connections. For Chi… |
| 759 | [GrantPierce94/FlipperZero-WiFi-Attacks](https://github.com/GrantPierce94/FlipperZero-WiFi-Attacks) | 5 | — | Exploring Evil Twin and WiFi Sniffing attacks using Flipper Zero |
| 760 | [InnerFireZ/F-Security-APP](https://github.com/InnerFireZ/F-Security-APP) | 5 | Python | F-Security Nethunter rooted APP for automate pentesting on phone devices. |
| 761 | [jcldf/deaulth-all-for-wifi-kit-8](https://github.com/jcldf/deaulth-all-for-wifi-kit-8) | 5 | C++ | this a mod from https://github.com/justcallmekoko/ESP8266_Deauth_All |
| 762 | [jcrvnx/PH-WIFI-WORDLISTS](https://github.com/jcrvnx/PH-WIFI-WORDLISTS) | 5 | — | This is a comprehensive wordlist containing millions of entries from PLDT, Globe, and Converge. C… |
| 763 | [JeonghunLee/wifisniffer](https://github.com/JeonghunLee/wifisniffer) | 5 | C | ESP32-S3 based on WIFI Sniffer and ReadTheDocs  |
| 764 | [KareemAksh/android-gki-wifi-injection](https://github.com/KareemAksh/android-gki-wifi-injection) | 5 | C | Monitor mode & 802.11 packet injection on a stock Android 13 GKI kernel — no reflash. Cross-built… |
| 765 | [kariemoorman/cyd-wifi-sniffer](https://github.com/kariemoorman/cyd-wifi-sniffer) | 5 | C | WiFi packet sniffer and network traffic classifier for the ESP32-3248S035 (CYD) board. |
| 766 | [learnwithaq/Hacking-WiFi-using-Aircrack-ng](https://github.com/learnwithaq/Hacking-WiFi-using-Aircrack-ng) | 5 | — | Aircrack-ng is a powerful suite used to audit wireless networks. It captures WPA/WPA2 handshakes … |
| 767 | [luciapintor/WiFi-Sniffer](https://github.com/luciapintor/WiFi-Sniffer) | 5 | Python |  |
| 768 | [malvidous/HELLISH](https://github.com/malvidous/HELLISH) | 5 | — | The code is for an ESP8266-based board, offering WiFi management, deauthentication attacks, fake … |
| 769 | [mohamadassaf96/WIFI_Jammer](https://github.com/mohamadassaf96/WIFI_Jammer) | 5 | Python | Python application that jams WIFIs by sending deauth packets |
| 770 | [Mohnki/dragotchi-flipper](https://github.com/Mohnki/dragotchi-flipper) | 5 | C | Dragotchi — a dragon virtual pet for the Flipper Zero that hunts the real airwaves (sub-GHz + opt… |
| 771 | [mr-tbot/Shadow-Apple-Installer](https://github.com/mr-tbot/Shadow-Apple-Installer) | 5 | Shell | Interactive installer that turns a GL.iNet AR300M into a self-reporting WiFi Pineapple Cloner app… |
| 772 | [MuAbdullah-sudo/FreeWifi-guard](https://github.com/MuAbdullah-sudo/FreeWifi-guard) | 5 | CSS | 🛡️ Free-Wi-Fi Guard: A Python-based security tool that monitors public airwaves for unencrypted n… |
| 773 | [Ohminecraft/ESP32-Attack-Tool](https://github.com/Ohminecraft/ESP32-Attack-Tool) | 5 | C | WiFi/BLE Testing/Offensive Tool/Defensive Tool |
| 774 | [oliverstraus246-beep/the-reaper](https://github.com/oliverstraus246-beep/the-reaper) | 5 | C++ | Multi-band ESP32-S3 wireless pentesting toolkit - WiFi, BLE, 2.4GHz, Sub-GHz, IR, RFID/NFC, GPS. … |
| 775 | [oshri-almog/esp32c5-wireshark-sniffer](https://github.com/oshri-almog/esp32c5-wireshark-sniffer) | 5 | Python | ESP32-C5 2.4Ghz + 5.8Ghz Wi-Fi, Zigbee or Thread sniffer interfaces for Wireshark  |
| 776 | [Pa1kumar1997/Wifijammer-Deauther](https://github.com/Pa1kumar1997/Wifijammer-Deauther) | 5 | — | Wifi Jammer code to Flash esp8266 Deauther |
| 777 | [pingbiqi/Mobile-Phone-Signal-Jammer-5G-LTE-Shielding-System-Pro](https://github.com/pingbiqi/Mobile-Phone-Signal-Jammer-5G-LTE-Shielding-System-Pro) | 5 | Python | 手机屏蔽器 (5G/4G/WiFi/GNSS) 技术方案。针对标准化考场、涉密会议室及监狱安全设计。支持 TDD-LTE/FDD-LTE/5G NR 智能屏蔽。 |
| 778 | [PitHerm/esphome-externalcomponents](https://github.com/PitHerm/esphome-externalcomponents) | 5 | C++ | Solis, Ginlong, S5-GR3P (15k) with wifi S3 Stick sniffer for Homeassistant using ESPHome |
| 779 | [profitpioneer/iphone-protocol-sniffer](https://github.com/profitpioneer/iphone-protocol-sniffer) | 5 | Shell | Reverse-engineer iPhone↔device protocols (BLE/WiFi) without a hardware sniffer. Captures decrypte… |
| 780 | [qsz13/WiFi-Hacker](https://github.com/qsz13/WiFi-Hacker) | 5 | Python | A WiFi Jammer |
| 781 | [redoyrowshon-dotcom/WiFi-RainbowBuffer](https://github.com/redoyrowshon-dotcom/WiFi-RainbowBuffer) | 5 | Python | An automated WiFi penetration testing tool for cracking WPA2 networks via handshake capture and b… |
| 782 | [rixgit/wifisniff](https://github.com/rixgit/wifisniff) | 5 | C++ | Simple C++ Wireless Sniffer.  Wrote it in approximately 3 hours including debugging and testing.   |
| 783 | [Sandesh-Basnet/Wifi-Jammer-with-ESP-8266](https://github.com/Sandesh-Basnet/Wifi-Jammer-with-ESP-8266) | 5 | C | Wi-Fi jamming with ESP8266 for educational purposes. Disrupts networks. Use responsibly. |
| 784 | [sftp-nik/ESP32-WiFi-Jammer](https://github.com/sftp-nik/ESP32-WiFi-Jammer) | 5 | CMake | This is the tool used in Wi-Fi penetration.   |
| 785 | [slashtechno/wifi-deauth](https://github.com/slashtechno/wifi-deauth) | 5 | Python | A semi-automated python script that can deauth clients from access points. |
| 786 | [SomnathGorai/ESP32-Marauder-WiFi-Tool](https://github.com/SomnathGorai/ESP32-Marauder-WiFi-Tool) | 5 | C++ | ESP32-based portable WiFi hacking tool using a 1.8" TFT SPI LCD display |
| 787 | [streanger/clients-scanner](https://github.com/streanger/clients-scanner) | 5 | Python | Local network clients scanner with deauth feature |
| 788 | [StrongWind1/WiFi_Cracking](https://github.com/StrongWind1/WiFi_Cracking) | 5 | Makefile | Complete technical reference for WPA/WPA2/WPA3 PSK security analysis |
| 789 | [suseong41/SuNiffing](https://github.com/suseong41/SuNiffing) | 5 | C++ | Galaxy S10 nexmon 기반 WiFi 스캐너 · 무선 보안 점검 도구 (Qt) |
| 790 | [tejasvane/Blu-WIFI_Jammer_Using_ESP8266](https://github.com/tejasvane/Blu-WIFI_Jammer_Using_ESP8266) | 5 | C++ | An ESP8266-based microproject to temporarily disrupt Wi-Fi (deauth) and Bluetooth signals, featur… |
| 791 | [Thenewmanator15/esp32c6-sniffer](https://github.com/Thenewmanator15/esp32c6-sniffer) | 5 | Python | Passive tri-radio wireless sniffer on an ESP32-C6 (802.15.4 / Wi-Fi / BLE), streaming into Wiresh… |
| 792 | [Unresponsive-hydrangeafamily234/DeautherX-lib](https://github.com/Unresponsive-hydrangeafamily234/DeautherX-lib) | 5 | C | Provide a unified ESP8266 library for Wi-Fi security assessment and testing with core tools from … |
| 793 | [UruxUs/ANKA-ESP32-MultiTool](https://github.com/UruxUs/ANKA-ESP32-MultiTool) | 5 | C++ | ANKA: ESP32 + SSD1306 OLED Security Tool. Includes WiFi Deauth/Beacon Spam, BLE Spam/Scan & IR. |
| 794 | [Volkov997/pen-card](https://github.com/Volkov997/pen-card) | 5 | — | RF Pentesting tool, but small enough for your wallet. Features: Wifi & Bluetooth, NFC, IR, (Sub G… |
| 795 | [voltsparx/Py-WiFi-Deauther](https://github.com/voltsparx/Py-WiFi-Deauther) | 5 | Python | Py-WiFi-Deauther is an ethical WiFi security testing tool for educational and authorized penetrat… |
| 796 | [w1ld3r/Raspi_Hackbox](https://github.com/w1ld3r/Raspi_Hackbox) | 5 | CSS | Debian Trixie Raspberry Pi 4 image builder for IoT, OT, automotive & RF/SDR pentesting — i3 + zsh… |
| 797 | [whoelse091/WIFI-BLE-JAMMER](https://github.com/whoelse091/WIFI-BLE-JAMMER) | 5 | C++ | WIFI/BLE JAMMER |
| 798 | [ykosaraju/Wifi-Pentesting-Cheatsheet](https://github.com/ykosaraju/Wifi-Pentesting-Cheatsheet) | 5 | — |  |
| 799 | [yofriendfromschool1/GEEKEYES-Flipper-Zero-5G-dualband-Wifi](https://github.com/yofriendfromschool1/GEEKEYES-Flipper-Zero-5G-dualband-Wifi) | 5 | — | GEEKEYES Flipper Zero 5G/dual band Wifi Deauth. |
| 800 | [yuno009/ESP32S3-USB-Keyboard-To-BLE](https://github.com/yuno009/ESP32S3-USB-Keyboard-To-BLE) | 5 | C++ | 🔄 Transform any USB keyboard into a Bluetooth device with ESP32-S3, allowing seamless connections… |
| 801 | [0x25/piSniff](https://github.com/0x25/piSniff) | 4 | — | sniff packet and access it with wifi (Raspberry) |
| 802 | [abir1999/Packet-Sniffer-ESP32](https://github.com/abir1999/Packet-Sniffer-ESP32) | 4 | C++ | Use an ESP32 to sniff WIFI packets |
| 803 | [Adityaraj6/Wi-Dos](https://github.com/Adityaraj6/Wi-Dos) | 4 | Python | WiFi Deauth Attack |
| 804 | [ahmhabib01/WIFI_PHISHER](https://github.com/ahmhabib01/WIFI_PHISHER) | 4 | C++ | HACK WIFI USING WIFI_PHISHER.  Evil-Twin AP to capture passwords with password verification again… |
| 805 | [aishee/Autopwn-Wifi](https://github.com/aishee/Autopwn-Wifi) | 4 | Shell | Searching and auditing Wifi |
| 806 | [aMiscreant/ESP32c3-Super-Mini-Scipts](https://github.com/aMiscreant/ESP32c3-Super-Mini-Scipts) | 4 | C | This repository contains a collection of Wi-Fi/Encryption/Bluetooth related scripts designed for … |
| 807 | [Amulong1/ESP8266_WiFi_Killer](https://github.com/Amulong1/ESP8266_WiFi_Killer) | 4 | — | A project that utilizes ESP8266 for network attacks and interference. |
| 808 | [anbdummy/WiFi-Deauth](https://github.com/anbdummy/WiFi-Deauth) | 4 | Shell | 802.11 Deauth BASH Script - Everyone Except You! |
| 809 | [areuhack/Wifi-Deauther](https://github.com/areuhack/Wifi-Deauther) | 4 | Python | A Python-based ethical hacking tool for performing WiFi network deauthentication attacks. This to… |
| 810 | [ArhumUsman9/AirStrike](https://github.com/ArhumUsman9/AirStrike) | 4 | Python | AirStrike-CLI is a powerful, terminal-based WiFi vulnerability assessment tool designed for both … |
| 811 | [ary27x/WIFI_JAMMER](https://github.com/ary27x/WIFI_JAMMER) | 4 | Python | Infinitely disconnects clients one by one from a 802.11 wifi network |
| 812 | [asgardOP/WiFi-Manager](https://github.com/asgardOP/WiFi-Manager) | 4 | Python | Advanced Windows WiFi Management Tool built with Python — includes network scanning, ARP spoofing… |
| 813 | [azph0byte/netmode](https://github.com/azph0byte/netmode) | 4 | Shell | Netmode is a lighweight bash script that use the power of 'iw' which allows users to easily switc… |
| 814 | [Bulletb8/esp32c5-wifi-pentool](https://github.com/Bulletb8/esp32c5-wifi-pentool) | 4 | C++ | ESP32-C5 dual-band 2.4/5GHz WiFi pentesting tool. Scan, deauth, capture, handshake harvest. Softw… |
| 815 | [CapibaraZero/WifiSniffer](https://github.com/CapibaraZero/WifiSniffer) | 4 | C++ | An ESP32 Wifi Sniffer |
| 816 | [cavoq/WiFi-Deauthenticator](https://github.com/cavoq/WiFi-Deauthenticator) | 4 | TypeScript | WiFi deauthentication tool. |
| 817 | [cheattheweb/ESP-WiFi-Deauther-and-Detector](https://github.com/cheattheweb/ESP-WiFi-Deauther-and-Detector) | 4 | C++ | This project is a proof of concept on WiFi deauth detection system. |
| 818 | [chetansaini53/ESP32-C6-Threat-Radar](https://github.com/chetansaini53/ESP32-C6-Threat-Radar) | 4 | C++ | Passive defensive wireless threat radar for ESP32-C6 (2.4GHz) - detects WiFi deauth, pwnagotchi &… |
| 819 | [Coreymillia/CYDSentinel](https://github.com/Coreymillia/CYDSentinel) | 4 | C++ | Touchscreen WiFi/BLE scanner, sniffer, and NOAA radar workspace for the ESP32-2432S028R Cheap Yel… |
| 820 | [corporation9/Lifeband-vxOS-WiFi-BLE-Sniffer](https://github.com/corporation9/Lifeband-vxOS-WiFi-BLE-Sniffer) | 4 | C | It detects wireless ESP32 chips as well as Bluetooth Low Energy devices and collects information … |
| 821 | [cyber6869/wifi-handshake-cracker](https://github.com/cyber6869/wifi-handshake-cracker) | 4 | Python | Professional WI-FI pentesting tool for analayzing and cracking WPA/WPA2 EAPOL (4-way Handshake) c… |
| 822 | [delvison/Netblock](https://github.com/delvison/Netblock) | 4 | Python | python script that has the ability to jam a single or multiple targets' wifi access. |
| 823 | [DIY-Learn/ESP32-DIV](https://github.com/DIY-Learn/ESP32-DIV) | 4 | C | ESP32-DIV: DIY multi‑tool with WiFi, Bluetooth, IR, 2.4GHz attacks and full menu system. |
| 824 | [dmanierre/PI-Sniffer](https://github.com/dmanierre/PI-Sniffer) | 4 | Python | This project will support using a raspberry pi and meshtastic to sniff out wifi enabled devices a… |
| 825 | [dnlrs/willy-board](https://github.com/dnlrs/willy-board) | 4 | C++ | ESP32 Probe Request Sniffer |
| 826 | [edward62740/DEFENDER](https://github.com/edward62740/DEFENDER) | 4 | C++ | This is a 2.4GHz Wi-Fi scanner for estimating channel usage and detect deauthentication attacks. … |
| 827 | [eokgnah/SmartED-to-MQTT-with-ESP32](https://github.com/eokgnah/SmartED-to-MQTT-with-ESP32) | 4 | C++ | SmartED CAN-BUS Data Sniffer and Sender to MQTT Server over ESP32 WIFI |
| 828 | [er2g/esp32-wifi-penetration-tool](https://github.com/er2g/esp32-wifi-penetration-tool) | 4 | C | ESP32-S3 WiFi penetration testing tool - auto handshake capture, single target attack, SPIFFS sto… |
| 829 | [Erennkrb/ESP32-and-ESP8266-DeAuthWifi](https://github.com/Erennkrb/ESP32-and-ESP8266-DeAuthWifi) | 4 | C++ | Educational proof-of-concept demonstrating Wi-Fi deauthentication attacks using ESP32 and ESP8266… |
| 830 | [Ethhacks-official/Wireless-Protect](https://github.com/Ethhacks-official/Wireless-Protect) | 4 | Python | An open source tool to detect deauth, Evil Twin, Clonned wifi, Arp Spoofing and Man in the Middle… |
| 831 | [frnAlt/FARHAN-Shot](https://github.com/frnAlt/FARHAN-Shot) | 4 | Python | **About Run WPS PIN attacks (Pixie Dust, online bruteforce, PIN prediction) without monitor mode … |
| 832 | [Glitchboi-sudo/RogueBridge](https://github.com/Glitchboi-sudo/RogueBridge) | 4 | Shell | Access Point WiFi para laboratorio/pentesting y configura NAT para dar salida a Internet a los cl… |
| 833 | [h2so0o4/CameraSniffer](https://github.com/h2so0o4/CameraSniffer) | 4 | Java | 基于WIFI的室内设备检测技术 |
| 834 | [Hexamora/ESP32-Wifi-Jammer](https://github.com/Hexamora/ESP32-Wifi-Jammer) | 4 | — | 📡 ESP32 + NRF24L01 PA LNA 2.4GHz RF tester \| No-solder breadboard build \| Webserver control int… |
| 835 | [heylizz/Wifi-Deauther-with-NodeMCU-ESP8266](https://github.com/heylizz/Wifi-Deauther-with-NodeMCU-ESP8266) | 4 | — | Scan for WiFi devices, block selected connections, create dozens of networks and confuse WiFi sca… |
| 836 | [iahunter/wifisniffer](https://github.com/iahunter/wifisniffer) | 4 | Shell | Wireshark Wifi Sniffing  - 802.11 plus radiotap header on Windows - Bridged Wireless NIC Adapter … |
| 837 | [iamEzmuth/DeAuthImposter](https://github.com/iamEzmuth/DeAuthImposter) | 4 | Python | Best tool to deauthenticate (disconnect) everyone in wifi network you are... |
| 838 | [ibtdev26/WifiRouge](https://github.com/ibtdev26/WifiRouge) | 4 | Python | A powerful Python-based RTL8720DN WiFi Deauther tool based on tesa-klebeband 5GHZ Deauther. Basic… |
| 839 | [Informatic/Sming_WiFi_Monitor](https://github.com/Informatic/Sming_WiFi_Monitor) | 4 | C++ | ESP8266 + Sming WiFi Sniffer example |
| 840 | [jakubkowalski167/wifi-pentesting-tutorial](https://github.com/jakubkowalski167/wifi-pentesting-tutorial) | 4 | Python |  |
| 841 | [Jarukit-PM/Wifi-Authentication-Attack](https://github.com/Jarukit-PM/Wifi-Authentication-Attack) | 4 | Shell | A mini project for studying Wi-Fi security vulnerabilities by simulating authentication bypass te… |
| 842 | [jaspreet-infosec/WiFi-Deauthenticator](https://github.com/jaspreet-infosec/WiFi-Deauthenticator) | 4 | Shell | The Wi-Fi Jammer Tool is a comprehensive bash script crafted to streamline the management and dep… |
| 843 | [jbenages/diswised](https://github.com/jbenages/diswised) | 4 | Shell | Audit WiFi clients with automated Evil Twin and Rogue AP attacks |
| 844 | [jimididit/wifi-pwn](https://github.com/jimididit/wifi-pwn) | 4 | Python | A script to perform a Wi-Fi deauthentication attack using a network interface controller (NIC) in… |
| 845 | [K3lgy/Flipper-Zero-Audit-Kit-](https://github.com/K3lgy/Flipper-Zero-Audit-Kit-) | 4 | Python | Kit d'audit de sécurité physique pour Flipper Zero. Parse automatiquement les exports de la carte… |
| 846 | [Kilouu/NowThisWifiIsMine](https://github.com/Kilouu/NowThisWifiIsMine) | 4 | Python | Outil d'attaque sur les réseaux Wifi avec 2 Mode : Attaque sur WPA, WEP, WPS ou en simulant un Ro… |
| 847 | [kostandinvllahu/ESP8266-BUG-FIXED](https://github.com/kostandinvllahu/ESP8266-BUG-FIXED) | 4 | — | ESP8266 wifi jammer had a bug so i fixed the bug |
| 848 | [kqzalf/Rootsignal-ESP32](https://github.com/kqzalf/Rootsignal-ESP32) | 4 | Python | RootSignal-ESP32 is a lightweight, MicroPython-based wireless anomaly detector that runs on moder… |
| 849 | [levouinse/deauther](https://github.com/levouinse/deauther) | 4 | Python | Sofinco Deauther v5.0 is a certified, cross-platform WiFi and Bluetooth penetration testing frame… |
| 850 | [lolue/ESP8266-ZeroTwo-Massive-Deauther](https://github.com/lolue/ESP8266-ZeroTwo-Massive-Deauther) | 4 | C++ | ESP8266 Wifi Deauther Massive With Oled Display (and have the anime waifu zero two😉) |
| 851 | [luketheluckyloner/nRF24_jammer](https://github.com/luketheluckyloner/nRF24_jammer) | 4 | — | The nRF24 jammer is a powerful tool that requires an ESP32 and configurable numbers of NRF24 modu… |
| 852 | [MallocPointer/BW16-Tools](https://github.com/MallocPointer/BW16-Tools) | 4 | — | 基于Ai-Thinker BW16-Kit RTL8720DN 的无线安全测试工具。包含WIFI功能：解除身份认证(Deauth)，信道干扰(Channel Interference)，Deau… |
| 853 | [MicrochipTech/atsamr34_lorawan_wifi_ap_scan](https://github.com/MicrochipTech/atsamr34_lorawan_wifi_ap_scan) | 4 | C | “IoT Made Easy!" - Adding Wi-Fi Sniffing to an existing LoRaWAN Application |
| 854 | [mkdirlove/DEADLY-DEAUTH](https://github.com/mkdirlove/DEADLY-DEAUTH) | 4 | Shell | A deadly WiFi deauthentication attack tool powered by MDK3. |
| 855 | [mmustaqim/RF_WiFi_jammer_detector](https://github.com/mmustaqim/RF_WiFi_jammer_detector) | 4 | Python |  |
| 856 | [my-project-droid/Hackbat-MultiToolhacking-OS1](https://github.com/my-project-droid/Hackbat-MultiToolhacking-OS1) | 4 | C++ | An open-source multi-tool firmware for the RP2040 Hackbat. Unifies sub-1GHz RF (CC1101), NFC (PN5… |
| 857 | [NodeLabs13/NETHER](https://github.com/NodeLabs13/NETHER) | 4 | — | A robust security testing firmware for ESP32 boards (Lolin32/ESP32). Designed for educational pur… |
| 858 | [omwardhanM/Bluetooth-Wifi-Jammer](https://github.com/omwardhanM/Bluetooth-Wifi-Jammer) | 4 | C++ | Bluetooth, BLE, Wifi - 2.4Ghz ISM Band Jammer / Interference Project with ESP32 and nRf24 |
| 859 | [pect0ral/kismet_parser](https://github.com/pect0ral/kismet_parser) | 4 | Python | Some Random Scripts to Parse Kismet output for useful info |
| 860 | [peterfillmore/ThreatbuttFreeWifi](https://github.com/peterfillmore/ThreatbuttFreeWifi) | 4 | C | ESP8266 based free wifi point - integrates advanced Threatbutt threaty threat zero day detection … |
| 861 | [ph4ntonn/wifi_attacker](https://github.com/ph4ntonn/wifi_attacker) | 4 | Python |  |
| 862 | [pirrofra/wifiSniffer](https://github.com/pirrofra/wifiSniffer) | 4 | Python |  |
| 863 | [PranitThorat/WiFire](https://github.com/PranitThorat/WiFire) | 4 | Python | :  🔥 WiFire – A blazing-fast automated Wi-Fi attack tool! Scan networks, send deauths, capture WP… |
| 864 | [Quantika14/logika14](https://github.com/Quantika14/logika14) | 4 | Python | Sniffer de clientes wifi y buscador de vendors. |
| 865 | [ripmeep/wifi-deauther](https://github.com/ripmeep/wifi-deauther) | 4 | C++ | A WiFi/Wireless Network Deauthentication attack  |
| 866 | [rouze-d/wificrack](https://github.com/rouze-d/wificrack) | 4 | Shell | Simple Tool For Crack WiFi Handshake file <.ivs/.cap> |
| 867 | [samdvl/Esp8266-Wifi-Sniffer](https://github.com/samdvl/Esp8266-Wifi-Sniffer) | 4 | C | This software make it possible to scan wifi devices with the esp8266. It contols the TTGO 0.91 ol… |
| 868 | [sayak-brm/DeauthAttack](https://github.com/sayak-brm/DeauthAttack) | 4 | C | Disconnects user from Wifi network using ESP microcontrollers. |
| 869 | [SequoiaSan/wifi_pentest_utils](https://github.com/SequoiaSan/wifi_pentest_utils) | 4 | Shell | WiFi pentest utilities |
| 870 | [ShaolinGardener/wsniff](https://github.com/ShaolinGardener/wsniff) | 4 | — | A WiFi sniffer for the Raspberry Pi - can be controlled remotely 🌱 |
| 871 | [ShlomiRex/WiFi-Deauthernticator](https://github.com/ShlomiRex/WiFi-Deauthernticator) | 4 | Python |  |
| 872 | [Sk-Traitor/ZOREX-WiFi-Cracker](https://github.com/Sk-Traitor/ZOREX-WiFi-Cracker) | 4 | — | ZOREX: All-in-one wireless security testing tool. Scan networks, capture handshakes, crack passwo… |
| 873 | [SriteXcode/alienwifidetector](https://github.com/SriteXcode/alienwifidetector) | 4 | Python | AlienWiFiDetector is your digital watchdog 👁️ — silently sniffing out WiFi clones and SSID spoofe… |
| 874 | [ssnrshnn/artemisz](https://github.com/ssnrshnn/artemisz) | 4 | C++ | ESP32 Based Wifi Hacking Tool |
| 875 | [Swimming-Monkey-Games/Shroomed](https://github.com/Swimming-Monkey-Games/Shroomed) | 4 | ShaderLab | Shroomed is a small game created for Wisniowa WIFI Game Jam. The entire project was completed in … |
| 876 | [Trojan1Hex/ESP32-2.4GHz-BLE-WiFi-Jammer-Educational-Project](https://github.com/Trojan1Hex/ESP32-2.4GHz-BLE-WiFi-Jammer-Educational-Project) | 4 | — | This project is developed strictly for educational purposes. Do not use it for unethical or illeg… |
| 877 | [udhaybhat00/airscope](https://github.com/udhaybhat00/airscope) | 4 | Python | Cross-platform USB Wi-Fi security auditor: WPA/WPA2 handshake + PMKID capture, WPS PixieDust, WPA… |
| 878 | [Van-Ziegelstein/airkick](https://github.com/Van-Ziegelstein/airkick) | 4 | C | C implementation of the classic WLAN deauthentication attack |
| 879 | [VinavilDev/DeautherDetector](https://github.com/VinavilDev/DeautherDetector) | 4 | C++ | A lightweight and customizable ESP32-based tool to detect deauthentication packets in WiFi networks. |
| 880 | [voltwu/WIFI-Deauthentication-Attack](https://github.com/voltwu/WIFI-Deauthentication-Attack) | 4 | Python | Forcing devices disconnect with wireless access point with wifi deauthentication attack |
| 881 | [WR117H/WiFiDucky](https://github.com/WR117H/WiFiDucky) | 4 | C++ | A tool used for HID attacks with an ESP32-S2 |
| 882 | [xiv3r/esp8266-deauth-detector](https://github.com/xiv3r/esp8266-deauth-detector) | 4 | C++ | esp8266 wifi jammer detector |
| 883 | [zuzu59/wifi-sniffer](https://github.com/zuzu59/wifi-sniffer) | 4 | Lua |  |
| 884 | [0xnhsec/Luminescence-Network-Sniffer](https://github.com/0xnhsec/Luminescence-Network-Sniffer) | 3 | C++ | ESP32-based Rogue AP with HTTP sniffing capability. Close in concept to Evil Twin crafted for WiF… |
| 885 | [8nt0n/Bl8ck0ut](https://github.com/8nt0n/Bl8ck0ut) | 3 | C++ | A 2.4Ghz Wifi Jammer pentesting tool |
| 886 | [ABHAYKUMARTRIPATHI/WiFi_Sniffer_Evil_Twin_Detector](https://github.com/ABHAYKUMARTRIPATHI/WiFi_Sniffer_Evil_Twin_Detector) | 3 | Python | A Python-based Wi-Fi Sniffer and Evil Twin Detector that passively monitors nearby wireless netwo… |
| 887 | [adipundir/deauther-dual-band-god-mode](https://github.com/adipundir/deauther-dual-band-god-mode) | 3 | C | Dual-band (2.4/5 GHz) WiFi deauther firmware for the ESP32-C5, with a phone-hosted web UI for liv… |
| 888 | [Ahmed-Ahmed16/variOne-2](https://github.com/Ahmed-Ahmed16/variOne-2) | 3 | C++ | Handheld ESP32-S3 wireless-security awareness device. Wi-Fi, BLE, Sub-GHz, NFC, IR & more. CIC Ne… |
| 889 | [AlbanoL/Sniffer_WiFi_ESP32_LoRa_TTN](https://github.com/AlbanoL/Sniffer_WiFi_ESP32_LoRa_TTN) | 3 | — | Contador de pessoas usando análise de pacotes WiFi. Projeto para o curso CPS 731/COPPE. |
| 890 | [AlldDev/Wifi-Hacking-Example](https://github.com/AlldDev/Wifi-Hacking-Example) | 3 | — | Este projeto demonstra como testar a vulnerabilidade de redes wireless e simular operações de Red… |
| 891 | [Aloka-Tek-Teach/ESP32-Wifi-Jammer-Sinhala](https://github.com/Aloka-Tek-Teach/ESP32-Wifi-Jammer-Sinhala) | 3 | C | ESP32 Wifi Jammer Sinhala. |
| 892 | [AnvilBrain/Anvil-f](https://github.com/AnvilBrain/Anvil-f) | 3 | — | Anvil-F is a high-performance, all-in-one Wi-Fi toolkit for the ESP32-C5. It provides fast scanni… |
| 893 | [asing012/Wifi_Jammer](https://github.com/asing012/Wifi_Jammer) | 3 | Python | This program uses aireplay to deauthenticate clients and jam the wifi. It makes it easier to run … |
| 894 | [ASP-29/WiFi-deauther-Mod-Bahasa-Indonesia](https://github.com/ASP-29/WiFi-deauther-Mod-Bahasa-Indonesia) | 3 | — |  |
| 895 | [astianmuchui/wifi-sniffer](https://github.com/astianmuchui/wifi-sniffer) | 3 | Python | Get all the Wifi networks ever connected to your device and their passwords at the time of connec… |
| 896 | [bad-antics/nullsec-mobile](https://github.com/bad-antics/nullsec-mobile) | 3 | Kotlin | 📱 NullSec Mobile - Security toolkit for Android & iOS \| Network scanner, WiFi analyzer, hash too… |
| 897 | [balwantyadav1/ESP8266-WiFiPhisher](https://github.com/balwantyadav1/ESP8266-WiFiPhisher) | 3 | C++ | ESP8266‑WiFiPhisher — ESP8266‑based rogue access‑point for Wi‑Fi phishing using captive portal an… |
| 898 | [berodcdev/alive-netscan](https://github.com/berodcdev/alive-netscan) | 3 | Python | Descoberta de hosts na rede local (macOS + Linux): enumera quem e o quê está conectado — IP, MAC,… |
| 899 | [bigjosh/drone-sniffer](https://github.com/bigjosh/drone-sniffer) | 3 | C | Standalone drone Remote ID sniffer for the Mesh-Detect board: XIAO ESP32-S3 sniffs BLE + WiFi ch6… |
| 900 | [BlackTesseract/Wifi-Jammer](https://github.com/BlackTesseract/Wifi-Jammer) | 3 | Python |  |
| 901 | [boubli/Wifi-Jammer-NodeMCU](https://github.com/boubli/Wifi-Jammer-NodeMCU) | 3 | C | ESP8266 WiFi Deauther & Jammer for NodeMCU - Scan networks, perform deauthentication attacks, and… |
| 902 | [chinese1123243/ESP32-C5-WIFI6-RF-Toolkit](https://github.com/chinese1123243/ESP32-C5-WIFI6-RF-Toolkit) | 3 | C | ESP32-C5 (RISC-V 240MHz, Wi-Fi 6 双频) 射频测试工具。37 条 CLI 覆盖嗅探 / 握手捕获 / 注入 / 钓鱼门户 / Evil Twin / KARMA … |
| 903 | [christianathinshelled7231/cs2-esp-radar-hack-2026](https://github.com/christianathinshelled7231/cs2-esp-radar-hack-2026) | 3 | — | External ESP and radar hack for CS2 — see enemies through walls with health, weapon info, and ful… |
| 904 | [codyaj/ReaperBoard](https://github.com/codyaj/ReaperBoard) | 3 | C++ | Wireless pentesting toolkit: ESP8266-based Lite and CM4-based Full version in development. |
| 905 | [cybermaksx/ESP32-Evil-Twin-Deauth-Captive-Portal](https://github.com/cybermaksx/ESP32-Evil-Twin-Deauth-Captive-Portal) | 3 | C++ |  Educational ESP32 WiFi security lab: deauthentication attack + Evil Twin clone + captive portal … |
| 906 | [danya201272/ESP32-WIFI-WebSerial-433Mhz](https://github.com/danya201272/ESP32-WIFI-WebSerial-433Mhz) | 3 | C++ | ESP32 with app interface remoteXY and grab and sent code. Bruteforce Came and Nice. Have a Jammer… |
| 907 | [darknecrocities/Python-Bruteforce-Attack-Script-for-Pentesting-Wifi](https://github.com/darknecrocities/Python-Bruteforce-Attack-Script-for-Pentesting-Wifi) | 3 | Python |  |
| 908 | [darrylburke/heltec_wifi_8_esp8266_LCD_deauth_detector](https://github.com/darrylburke/heltec_wifi_8_esp8266_LCD_deauth_detector) | 3 | C | ESP8266 Deauth Detector using the LCD on the Heltec Wifi 8 board |
| 909 | [dbarzin/FeatherDeauthDetector](https://github.com/dbarzin/FeatherDeauthDetector) | 3 | C++ | This is a tool for security operation teams to detect Wifi Deauth  actions made by attackers on n… |
| 910 | [DOMN-git/esp32s3-nat-router](https://github.com/DOMN-git/esp32s3-nat-router) | 3 | C | ESP32S3 WiFi NAT Router with client listing, serial deauth, and network monitoring |
| 911 | [drubaby/pi-probe-sniffer](https://github.com/drubaby/pi-probe-sniffer) | 3 | Python | Raspberry Pi-hosted wifi probe monitor with mqtt and supabase connections. |
| 912 | [DX4GREY/deauther-s](https://github.com/DX4GREY/deauther-s) | 3 | Python | This is a tool for wifi deauther, please use it as wisely as possible, don't use it for illegal a… |
| 913 | [EinsPommes/ArithOS](https://github.com/EinsPommes/ArithOS) | 3 | C | ArithOS: A stealth pentesting toolkit disguised as a calculator for PicoCalc hardware. Features W… |
| 914 | [eric-o-s/WIFIPOLICE](https://github.com/eric-o-s/WIFIPOLICE) | 3 | C++ | Deauth monitor for the Waveshare ESP32-S3 147 inch Display Dev Board. This guy passively logs to … |
| 915 | [Esther7171/ESP8266-Deauther](https://github.com/Esther7171/ESP8266-Deauther) | 3 | — | ESP8266 / NodeMCU WiFi deauther. Scan, deauth, beacon and probe flooding on 2.4GHz. Step by step … |
| 916 | [ethicalhackeragnidhra/Wifi-jammer-1](https://github.com/ethicalhackeragnidhra/Wifi-jammer-1) | 3 | Python |  |
| 917 | [F1DEL05/Wifi-Jammer_05](https://github.com/F1DEL05/Wifi-Jammer_05) | 3 | Python | Wifi handshake capturer (automation tool for airmon-ng) in Linux For pentesters |
| 918 | [F6Exp/ESP32-WiFi-Deauth-Indicator](https://github.com/F6Exp/ESP32-WiFi-Deauth-Indicator) | 3 | C++ | ESP32 WiFi-Deauth-Indicator |
| 919 | [Flyzone84/DeAuther](https://github.com/Flyzone84/DeAuther) | 3 | Shell | Deauther |
| 920 | [FuflyPaladium/NodeMCU-WifiJammer](https://github.com/FuflyPaladium/NodeMCU-WifiJammer) | 3 | Python | THIS TOOL IS FOR SETUP NODEMCU WIFI JAMMER  YOU CAN USE THIS TOOL ON WINDOWS  IF IS NOT WORK THEN… |
| 921 | [garrettmiller/WiFIDS](https://github.com/garrettmiller/WiFIDS) | 3 | Python | A Wireless-Physical IDS with Jam Detection - 18-731, Spring 2015, Carnegie Mellon University |
| 922 | [Gax-n2o/Wifi-Attack](https://github.com/Gax-n2o/Wifi-Attack) | 3 | Shell | WiFi MultiAttack - Herramienta de Auditoría WiFi  WiFi MultiAttack es un script integral en Bash … |
| 923 | [GEEKSUMAN/TL-WN722N](https://github.com/GEEKSUMAN/TL-WN722N) | 3 | — | TP-Link Nano USB WiFi Dongle 150Mbps High Gain Wireless Network Wi-Fi Adapter setting up for Kali… |
| 924 | [gibins/esp32_wifi_sniffer](https://github.com/gibins/esp32_wifi_sniffer) | 3 | C++ | IEEE802.11 packet capturing using ESP32 |
| 925 | [Gopalakrishnan20/WiJAMMER](https://github.com/Gopalakrishnan20/WiJAMMER) | 3 | Shell | WiJAMMER is a Hacking tool for deauthentication attack wifi with mdk4 or aireplay-ng. Easy and fa… |
| 926 | [goyalnish26/wifi_pentest_writeup](https://github.com/goyalnish26/wifi_pentest_writeup) | 3 | — | Documented authorized wireless security assessments on personally owned and permitted networks us… |
| 927 | [gregoirener/WIFIRE](https://github.com/gregoirener/WIFIRE) | 3 | — | WIFIRE is a Wi-Fi hacking tool for ethical penetration testing. It supports attacks like Evil Twi… |
| 928 | [hackerazmi201/wifi_killler](https://github.com/hackerazmi201/wifi_killler) | 3 | Shell | WiFiKiller is a Bash-based penetration testing tool for Kali Linux that automates Evil Twin attac… |
| 929 | [HelioASjunior/ESP32S3-pentest-tool](https://github.com/HelioASjunior/ESP32S3-pentest-tool) | 3 | C++ | Ferramenta educacional de teste de segurança WiFi para ESP32-S3, com interface web. Escaneia rede… |
| 930 | [honestcorrupt/PROJECT-wifi-jammerhc4](https://github.com/honestcorrupt/PROJECT-wifi-jammerhc4) | 3 | Python | Wi-Fi jamming 📡 is a disruptive technique that intentionally interferes with wireless communicati… |
| 931 | [HowDidThatHappen1/BT-Wifi-RC-Jammer](https://github.com/HowDidThatHappen1/BT-Wifi-RC-Jammer) | 3 | C++ |  |
| 932 | [hubb22/Wi-Fi-Bluetooth-and-RTL-SDR-Jamming-Alarm-System](https://github.com/hubb22/Wi-Fi-Bluetooth-and-RTL-SDR-Jamming-Alarm-System) | 3 | — | WiFi Jammer Alarm. Detects attacks on Wi-Fi, Bluetooth and 433 MHz frequency devices. Wi-Fi Jamme… |
| 933 | [impclaw/wifi-sniff](https://github.com/impclaw/wifi-sniff) | 3 | C | Custom wifi sniffer with only the data I want as output. Does not sniff ethernet at all.  |
| 934 | [jshearer/wifi-sniffer](https://github.com/jshearer/wifi-sniffer) | 3 | Python | A set of python scripts to sniff specific wifi packets for use in positioning. |
| 935 | [jshingler/Pi-Wifi-Sniff](https://github.com/jshingler/Pi-Wifi-Sniff) | 3 | Java | Raspberry Pi Wifi Sniffer |
| 936 | [Kidd3n/wifiphisher](https://github.com/Kidd3n/wifiphisher) | 3 | PHP | Evil Twin |
| 937 | [KlutzyBlade/NetRaze32](https://github.com/KlutzyBlade/NetRaze32) | 3 | C | NetRaze32 is a comprehensive penetration testing tool built for the ESP32-32E platform with a 2.8… |
| 938 | [koua29/wifi-auditor](https://github.com/koua29/wifi-auditor) | 3 | Python | Audit your OWN Wi-Fi: capture WPA/WPA2 handshakes on LilyGO T-Embed (Bruce firmware), crack on Ma… |
| 939 | [krrr/BW16-Stealth-Deauther](https://github.com/krrr/BW16-Stealth-Deauther) | 3 | C++ | BW16 WiFi Killer |
| 940 | [kylecmathias/FlipperInfinity](https://github.com/kylecmathias/FlipperInfinity) | 3 | C | Handheld multi-protocol signal analysis device — NFC, RFID, sub-GHz RF, IR, and WiFi on a custom … |
| 941 | [laoheimao/mac-address-harvester](https://github.com/laoheimao/mac-address-harvester) | 3 | Python | Python script to use your wifi adapter to sniff wifi packet traffic for mac addresses and then gr… |
| 942 | [linglingltd/wifi-remote](https://github.com/linglingltd/wifi-remote) | 3 | C++ | Hacked Ledvance SMART+ Wifi-Remote firmware for ESP8266 |
| 943 | [magikh0e/sprout](https://github.com/magikh0e/sprout) | 3 | C++ | Ambient hacker virtual pet for the 3.5" Cheap Yellow Display (ESP32-3248S035R) — real-time, weath… |
| 944 | [manishmarahatta/wifijammer-v1.0](https://github.com/manishmarahatta/wifijammer-v1.0) | 3 | Python | WIFI JAMMER |
| 945 | [MarcusProgram/Wifi-Jammer](https://github.com/MarcusProgram/Wifi-Jammer) | 3 | Python | python script to create random wifi  |
| 946 | [MarvinCS/DNS_Sniffer](https://github.com/MarvinCS/DNS_Sniffer) | 3 | Python | A dns sniffing tool. Only works in public wifis |
| 947 | [masssubash240/WIFI-Pentesting](https://github.com/masssubash240/WIFI-Pentesting) | 3 | HTML |  |
| 948 | [matb4r/wifi-sniffer](https://github.com/matb4r/wifi-sniffer) | 3 | C | IEEE 802.11/Wi-Fi sniffer |
| 949 | [MaxKei/Data-Parsing-from-serial-port](https://github.com/MaxKei/Data-Parsing-from-serial-port) | 3 | Python | If it's promiscuous mode working together with ESP32, it can sniff data packets from the wireless… |
| 950 | [mdtomo/wispy](https://github.com/mdtomo/wispy) | 3 | Python | Wifi probe request packet sniffer. |
| 951 | [meetsoni15/deadair](https://github.com/meetsoni15/deadair) | 3 | Go | Continuously jam all wifi clients/routers |
| 952 | [menashe12346/Evil_Twin](https://github.com/menashe12346/Evil_Twin) | 3 | Python | A tool for performing and detecting Evil Twin Wi-Fi attacks via fake AP creation and SSID duplica… |
| 953 | [Meshwa428/KIVA](https://github.com/Meshwa428/KIVA) | 3 | C++ | KIVA: A handheld AI hacking assistant born from a love of tinkering. A pen-testing tool built fro… |
| 954 | [mhaskar/wifi-jammer](https://github.com/mhaskar/wifi-jammer) | 3 | Python | Python automated wifi jammer |
| 955 | [MrDepph/Tamafi-CYD-ESP32](https://github.com/MrDepph/Tamafi-CYD-ESP32) | 3 | — | Tamagotchi-inspired WiFi/Bluetooth sniffer firmware for CYD 2.8" ESP32. Creature feeds on network… |
| 956 | [MrDestroyer0/Wifi_Jamme3r](https://github.com/MrDestroyer0/Wifi_Jamme3r) | 3 | Shell | Wifi Jammer \| Best For Wifi Jamming |
| 957 | [mrnet15/RavenRF](https://github.com/mrnet15/RavenRF) | 3 | C++ | Modular RF & pentest firmware for the M5Stack Cardputer Adv + Cap LoRa-1262 (WiFi, BLE, LoRa, GPS) |
| 958 | [nelsoncarlson/marauder-esp32c5-automation](https://github.com/nelsoncarlson/marauder-esp32c5-automation) | 3 | Python | Suite de automacao para ESP32-C5 Marauder com Attack Manager e WiFi Scanner. |
| 959 | [Nikita465-dev/wifinet-creds-inspector](https://github.com/Nikita465-dev/wifinet-creds-inspector) | 3 | HTML | Wi-Fi Password Auditor: Secure Credential Recovery & Network Vulnerability Scanner for 2026 |
| 960 | [nlogallo/esp32-mantisHack](https://github.com/nlogallo/esp32-mantisHack) | 3 | C++ | Project of a small hacking device with Wifi, Bluetooth, NFC, and IR capabilities. |
| 961 | [obstruse/PGNH](https://github.com/obstruse/PGNH) | 3 | C | PolarGraph Network Hack: PolarshieldSD v3.0e modified to use WiFi for communication between contr… |
| 962 | [Ola-Kaznowska/PyWiFi-Pentest](https://github.com/Ola-Kaznowska/PyWiFi-Pentest) | 3 | Python | PyWiFi Pentest - Wi-Fi Security Analysis Tool. |
| 963 | [pingbiqi/GPS-shield-jammer-cellphone-signal-blocker](https://github.com/pingbiqi/GPS-shield-jammer-cellphone-signal-blocker) | 3 | JavaScript | 专业GPS屏蔽器与手机信号屏蔽器方案。支持5G/4G/WiFi信号拦截，适用于会议室、考场及无人机防护 |
| 964 | [pressure679/mySimpleSniffer](https://github.com/pressure679/mySimpleSniffer) | 3 | Java | Jnetpcap 1.3 wifi monitor/sniffer |
| 965 | [project-1871/hailhound-laptop](https://github.com/project-1871/hailhound-laptop) | 3 | Python | GTK4 Linux security toolkit — WiFi, BLE, SubGHz, RFID, jamming detection |
| 966 | [pt-mastermind/WifiMaster](https://github.com/pt-mastermind/WifiMaster) | 3 | Shell | Bash Automation tool for evil twin attack. |
| 967 | [pwnk1t/esp32-bluetooth-WiFi-jammer](https://github.com/pwnk1t/esp32-bluetooth-WiFi-jammer) | 3 | — | how to build a simple bluetooth/WiFi-jammer (WiFi only works on 2,4Ghz Network-devices) |
| 968 | [RFIunknown/BocchiTwin](https://github.com/RFIunknown/BocchiTwin) | 3 | C | WiFi Security Audit Tool (v1.0 Alpha) menggunakan ESP8266. Mendukung scanning, deauth-injection, … |
| 969 | [RizzoEng/DevilApe-Tft-cyberdeck](https://github.com/RizzoEng/DevilApe-Tft-cyberdeck) | 3 | — | ESP32-powered cyberdeck interface. WiFi/BLE scanning, packet monitoring, deauth detection, beacon… |
| 970 | [romaneviil/Reviltwin](https://github.com/romaneviil/Reviltwin) | 3 | — | An opensource Python3 script for pentesters that facilitates evil twin attacks against wifi vulne… |
| 971 | [rootsid/Wifi-Jammer](https://github.com/rootsid/Wifi-Jammer) | 3 | Objective-C | Jam Wifi Networks  |
| 972 | [rzeldent/esp8266-deauther](https://github.com/rzeldent/esp8266-deauther) | 3 | C | Clone from SpaceHuhn wifi deauther |
| 973 | [saherm0hamed/wifi-networks-scanner](https://github.com/saherm0hamed/wifi-networks-scanner) | 3 | Python | Python script designed to scan and display nearby Wi-Fi networks using a specified network interf… |
| 974 | [saikat-rog/Hack-WiFi](https://github.com/saikat-rog/Hack-WiFi) | 3 | — | How to collect and crack any handshake file of a access point. |
| 975 | [sakearzoo/WiFi-Jammer](https://github.com/sakearzoo/WiFi-Jammer) | 3 | Python | WiFI Jammer |
| 976 | [samatt/Sniffer](https://github.com/samatt/Sniffer) | 3 | C++ | barebones wifi sniffer for pi and mac |
| 977 | [sarandia/WiFi_Jammer](https://github.com/sarandia/WiFi_Jammer) | 3 | Python |  |
| 978 | [sephallen/esp32-wifi-sniffer-sdcard-sqlite](https://github.com/sephallen/esp32-wifi-sniffer-sdcard-sqlite) | 3 | C++ |  |
| 979 | [shasradha/Orbit](https://github.com/shasradha/Orbit) | 3 | C | Wrist-worn WiFi security testing tool — ESP8266 + OLED in a modified SKMEI watch case. KiCad hard… |
| 980 | [shubbrotopaul-max/Spectre-DIV-OS](https://github.com/shubbrotopaul-max/Spectre-DIV-OS) | 3 | C | SPECTRE-DIV OS is a Matrix-themed WiFi Research Suite for ESP32 & ST7789 TFT. 🚀  Features: ✅ Pack… |
| 981 | [sobri3195/pegasus-sniffer](https://github.com/sobri3195/pegasus-sniffer) | 3 | Python | A comprehensive WiFi pentesting suite with multiple modules for network analysis and security tes… |
| 982 | [Somashekharh/Ethical-Hacking-GadgetHub](https://github.com/Somashekharh/Ethical-Hacking-GadgetHub) | 3 | — | A collection of hardware-based ethical hacking tools and guides for penetration testing, includin… |
| 983 | [stalss/passive-wifi-crowd-counter](https://github.com/stalss/passive-wifi-crowd-counter) | 3 | C | Passive WiFi crowd counter using ESP32 promiscuous mode — counts nearby devices by sniffing 802.1… |
| 984 | [stephanbluitt/-ESP32-Evil-Twin-Attack](https://github.com/stephanbluitt/-ESP32-Evil-Twin-Attack) | 3 | C++ | A proof-of-concept ESP32 Evil Twin attack demo featuring deauthentication and a customizable capt… |
| 985 | [terminat0r7031/ESP8266-WIFI-HACKING](https://github.com/terminat0r7031/ESP8266-WIFI-HACKING) | 3 | C++ |  |
| 986 | [The-Lxx-CLoUD/CLoUD-JAM](https://github.com/The-Lxx-CLoUD/CLoUD-JAM) | 3 | Python | wifi jammer❗(for pentest) |
| 987 | [thomaswilley/wifioutlets](https://github.com/thomaswilley/wifioutlets) | 3 | C++ | ESP8266/NodeMCU http-based server to control a hacked set of RF outlets from the internet. |
| 988 | [timschmolka/esp32-sniffer](https://github.com/timschmolka/esp32-sniffer) | 3 | C | A simple PoC of sniffing raw wifi packets from a pre-defined channel on an ESP32. |
| 989 | [Unknownx007/WI-JAM-X](https://github.com/Unknownx007/WI-JAM-X) | 3 | Python | WI-JAM-X is a wifi jamming tool used for jam the targated wifi device which will deauth all the c… |
| 990 | [usama7628674/Wifijammer](https://github.com/usama7628674/Wifijammer) | 3 | Python | Wifi Jammer in python utilizing scapy (2.4/5) Ghz with channel hop. |
| 991 | [VeerDev-hub/esp32-fake-virus-prank](https://github.com/VeerDev-hub/esp32-fake-virus-prank) | 3 | C++ | This project turns your ESP32 into a fake "Hacked" WiFi access point, complete with a full-screen… |
| 992 | [WhiskeyTangoHotel/Portable-ESP8266-WiFi-Sniffer-Arduino-IDE-](https://github.com/WhiskeyTangoHotel/Portable-ESP8266-WiFi-Sniffer-Arduino-IDE-) | 3 | — | Portable ESP8266 WiFi Sniffer (Arduino IDE) |
| 993 | [x3nc0n/flipper-fuzzer](https://github.com/x3nc0n/flipper-fuzzer) | 3 | C | FluckFlock - a Flipper Zero chaff broadcaster that floods passive Wi-Fi/BLE/RF tracking with plau… |
| 994 | [XanderStrike/wifido](https://github.com/XanderStrike/wifido) | 3 | Python | Mobile Wifi Sniffer |
| 995 | [xiaohe4966/BW16-WiFi-Scan-WebUI](https://github.com/xiaohe4966/BW16-WiFi-Scan-WebUI) | 3 | C++ | BW16 (RTL8720DN) WiFi 扫描与Deauther工具 — Web UI版。手机连接AP热点即可操作，支持WiFi扫描、目标选择、多种攻击模式，无需OLED屏幕。 |
| 996 | [younisrahman/WifiJammerUI](https://github.com/younisrahman/WifiJammerUI) | 3 | Java | A Wifi jammer UI for Onu |
| 997 | [0x00-0x00/netcracker](https://github.com/0x00-0x00/netcracker) | 2 | Python | WiFi auditing tool to monitor, capture and crack WPA handshakes. |
| 998 | [1337leets/WiFi-Wardriving-Logger](https://github.com/1337leets/WiFi-Wardriving-Logger) | 2 | Python | Termux Wi-Fi and GPS logger with a Leaflet map, security classes and evil-twin hints |
| 999 | [84KaliPleXon3/wifi-pentesting-guide](https://github.com/84KaliPleXon3/wifi-pentesting-guide) | 2 | Python |  |
| 1000 | [Aalok000/WIFI-Deauther](https://github.com/Aalok000/WIFI-Deauther) | 2 | Python |  |
| 1001 | [AaltoAsia/K1WifiGateway](https://github.com/AaltoAsia/K1WifiGateway) | 2 | C++ | Program for using ESP8266 to hack a certain 6LoWPAN to WiFi bridge system to use O-MI. |
| 1002 | [absolute-xero7/kestrel](https://github.com/absolute-xero7/kestrel) | 2 | C++ | Pocket RF & wireless recon multitool firmware for the ESP32 Cheap Yellow Display — WiFi/BLE + CC1… |
| 1003 | [actonetor/WifiTool](https://github.com/actonetor/WifiTool) | 2 | Python | Plusieurs Tool python pour du pentesting en wifi (wps cracking wpa cracking dos)  |
| 1004 | [ahmkrby/karabay_wifi_pentest_device](https://github.com/ahmkrby/karabay_wifi_pentest_device) | 2 | — | Proje dosyaları yakında yüklenecektir. |
| 1005 | [aingram702/ESP32-Net](https://github.com/aingram702/ESP32-Net) | 2 | C++ | A network of dropable ESP32 devices that all serve an individual purpose. One ESP32-S3 DevKitC-1 … |
| 1006 | [Ajay-Bommidi/WiFiSentry](https://github.com/Ajay-Bommidi/WiFiSentry) | 2 | Python | WiFiSentry is a lightweight Python-based wireless pentesting tool that helps ethical hackers dete… |
| 1007 | [akashdip2001/Wi-Fi-deauther-with-ESP8266-OLED-module](https://github.com/akashdip2001/Wi-Fi-deauther-with-ESP8266-OLED-module) | 2 | — | IOT with Cyber Security with WiFi deauther with esp8266 oled module |
| 1008 | [Alexxdal/esp_wifi_usb](https://github.com/Alexxdal/esp_wifi_usb) | 2 | C | RTL8188EU USB Wi-Fi driver for ESP32-S3's native USB host — promiscuous sniffing + raw 802.11 inj… |
| 1009 | [allegorix/esp-wifi-radar-lab](https://github.com/allegorix/esp-wifi-radar-lab) | 2 | Python | ESP8266 + ESP32 promiscuous sniffers, 3D Wi-Fi radar, active scan, and audit toolkit |
| 1010 | [alrayat/ESP32-S3-WiFi-Jammer](https://github.com/alrayat/ESP32-S3-WiFi-Jammer) | 2 | C++ |  |
| 1011 | [AmandracOP/wifi-deauther](https://github.com/AmandracOP/wifi-deauther) | 2 | — | This is a program for a network deauther which can deauth,beacon and probe a network through a wi… |
| 1012 | [amtzespinosa/esp8266-wifi-deauther](https://github.com/amtzespinosa/esp8266-wifi-deauther) | 2 | C | Today we're doing something different. We will leave the computer for a while and make something … |
| 1013 | [andrejliadov/Wifi-Sniffer](https://github.com/andrejliadov/Wifi-Sniffer) | 2 | Python | This programme uses socket in python to sniff for ethernet frames. The ethernet frames are then u… |
| 1014 | [aniceswan/PhantomRF](https://github.com/aniceswan/PhantomRF) | 2 | C++ | Open-source ESP32-S3 RF research & security testing platform. nRF24L01 + CC1101 jamming, full WiF… |
| 1015 | [Ankitkushwaha90/wifi_jammer_hijacking](https://github.com/Ankitkushwaha90/wifi_jammer_hijacking) | 2 | — | This note provides a concise, practical overview of wireless communications, SDR, and ethical Wi-… |
| 1016 | [annk15/Deauth](https://github.com/annk15/Deauth) | 2 | Java | A jammer written in java to perform deauthentication attacks on wifi networks. |
| 1017 | [AnthonyKNorman/ESP8266-Home-Assistant-RGB-Bulb](https://github.com/AnthonyKNorman/ESP8266-Home-Assistant-RGB-Bulb) | 2 | Python | This Micropython project is to Hack a TYWE3S board in a cheap WiFi RGB Bulb |
| 1018 | [AnthonyKNorman/ESP8266-Home-Assistant-Smart-Socket](https://github.com/AnthonyKNorman/ESP8266-Home-Assistant-Smart-Socket) | 2 | Python | This Micropython project is to Hack a Hyleton313 cheap WiFi smart socket |
| 1019 | [antonionard/Evil-Twin-Attack-on-Eduroam](https://github.com/antonionard/Evil-Twin-Attack-on-Eduroam) | 2 | Shell | Implementation of a MITM attack using Evil Twin, Captive Portal, and mitmproxy for HTTPS traffic … |
| 1020 | [aoluggo/word-list-pentest](https://github.com/aoluggo/word-list-pentest) | 2 | — | Spanish word list (plain text) for use in pen-test. WIFI Try with wifite // Lista de palabras en … |
| 1021 | [archrampart/zero-cmd](https://github.com/archrampart/zero-cmd) | 2 | JavaScript | Web-based command center for Flipper Zero — Screen mirror, file manager, Sub-GHz, NFC, IR, Bad US… |
| 1022 | [ArtemAvanesov/Arduino-WIFI-Jammer](https://github.com/ArtemAvanesov/Arduino-WIFI-Jammer) | 2 | C | Arduino-WIFI-Jammer based on Nodemcu Lua Wi-Fi (Esp8266) |
| 1023 | [Arxhsz/Project-Skull-Breaker-v1](https://github.com/Arxhsz/Project-Skull-Breaker-v1) | 2 | C++ | ESP32 handheld multi-radio security research device — WiFi, BLE, 2.4GHz & sub-GHz RF. v1 proof of… |
| 1024 | [austinbenincasa/PiFiHacker](https://github.com/austinbenincasa/PiFiHacker) | 2 | Python | CLI for deploying a Evil Twin Wifi network |
| 1025 | [AxGHaven/AxG_Haven-WiFi-Tool](https://github.com/AxGHaven/AxG_Haven-WiFi-Tool) | 2 | — | ESP8266-based portable WiFi audit tool with OLED UI, EvilTwin captive portal, deauth attack, NRF2… |
| 1026 | [AydanBedingham/deauth-wifi-jammer](https://github.com/AydanBedingham/deauth-wifi-jammer) | 2 | Shell | Script to automate the usage of the aircrack-ng to perform the Wi-Fi deauthentication denial-of-s… |
| 1027 | [Azhar14/Jam_Digital_Pintar](https://github.com/Azhar14/Jam_Digital_Pintar) | 2 | C++ |  Jam digital "pintar" menggunakan modul WiFi ESP8266 dan display Dot Matrix LED MAX7219. Perangka… |
| 1028 | [b-simjoo/esp8266-evil-wifi](https://github.com/b-simjoo/esp8266-evil-wifi) | 2 | — | Some hacking tools for esp8266 with arduino framework |
| 1029 | [bad-antics/nullsec-hak5-toolkit](https://github.com/bad-antics/nullsec-hak5-toolkit) | 2 | Python | Universal Hak5 device management toolkit - CLI suite for WiFi Pineapple, Bash Bunny, Rubber Ducky… |
| 1030 | [bagdigourav3/Air_wifi_craker](https://github.com/bagdigourav3/Air_wifi_craker) | 2 | Python | Air_wifi_craker is a Python 3 WiFi security testing tool. It scans nearby networks, lists them in… |
| 1031 | [blakejosephjames1-ctrl/WIFI_Cyberdeck](https://github.com/blakejosephjames1-ctrl/WIFI_Cyberdeck) | 2 | — | This project is a Cyberdeck based from an ESP32-S3 microcontroller designed to perform WIFI attac… |
| 1032 | [bsucyber/wifi-hacking](https://github.com/bsucyber/wifi-hacking) | 2 | — | Wifi hacking activity with ESP32-WROOM-ESP boards. |
| 1033 | [cashoefman/Resto-Score-for-Hack-2021-for-Positivity](https://github.com/cashoefman/Resto-Score-for-Hack-2021-for-Positivity) | 2 | Python | Resto Score connect a Heltec LoRaWAN 32, Heltec Wifi Kit 32 or Generic ESP32 Devkit to Google IoT… |
| 1034 | [ch3ber/esp32-projects](https://github.com/ch3ber/esp32-projects) | 2 | Python | Collection of small, self-contained projects for the ESP32 family of microcontrollers programmed … |
| 1035 | [Chap010/Alpha-Auto-Fix](https://github.com/Chap010/Alpha-Auto-Fix) | 2 | Python | Wifi Pentesting |
| 1036 | [chrislangfitt7/ESP_32_SNIFFER](https://github.com/chrislangfitt7/ESP_32_SNIFFER) | 2 | — | A small handheld device that has 2.4ghz capabilities along with Wifi and Bluetooth scanning. Usin… |
| 1037 | [cikolllooid/esp32_wifi](https://github.com/cikolllooid/esp32_wifi) | 2 | C | hack wifi |
| 1038 | [codesempai/WiFi-Hacking-Using-ESP8266](https://github.com/codesempai/WiFi-Hacking-Using-ESP8266) | 2 | C++ | WiFi Hacking Using ESP8266 Node MCU Wifi Development Board \| Captive portal \| Deauth |
| 1039 | [CoolJuvenile/esp32-s3-wifi-killer](https://github.com/CoolJuvenile/esp32-s3-wifi-killer) | 2 | C++ | ESP32-S3 掌上 Wi-Fi 测试仪 · Deauth / Beacon Flood / Probe Flood，摇杆 + OLED 脱机操作，已从 ESP8266 Deauther 移植… |
| 1040 | [CorePySystems/-WarCappin](https://github.com/CorePySystems/-WarCappin) | 2 | Perl | WiFi Hacking: Autonomously man in the middle deauthenticate WPA2 wireless networks and packet cap… |
| 1041 | [CristianT71/HackRell](https://github.com/CristianT71/HackRell) | 2 | Shell | HackRell es una suite de hacking ético profesional, funcional y modular, escrita en Bash, diseñad… |
| 1042 | [Cyb3rPh4nt0n/EvilTwin-PortalFramework](https://github.com/Cyb3rPh4nt0n/EvilTwin-PortalFramework) | 2 | Python | Script en Python para automatizar auditorías WiFi mediante la orquestación de hostapd, dnsmasq y … |
| 1043 | [cyberoscyber427-netizen/cyberoscyber427wifi-Abdul-Mateen-Suite](https://github.com/cyberoscyber427-netizen/cyberoscyber427wifi-Abdul-Mateen-Suite) | 2 | Python | Official repository for cyberoscyber427wifi. A professional tool for wifi-hacking, pentesting, an… |
| 1044 | [CyberRoninX1/AirStrike](https://github.com/CyberRoninX1/AirStrike) | 2 | — | wifi-security, penetration-testing, cybersecurity, wpa2-handshake, evil-twin, deauthentication-at… |
| 1045 | [Danucosukosuko/Flipper-devboard-WiFi-Spam](https://github.com/Danucosukosuko/Flipper-devboard-WiFi-Spam) | 2 | C++ | Programa escrito en Arduino para emitir redes Wi-Fi aleatorias en la Wi-Fi DevBoard del Flipper Zero |
| 1046 | [darkLabz001/pwni-esp32-c5](https://github.com/darkLabz001/pwni-esp32-c5) | 2 | C | PWNI: Pwnagotchi-style WiFi pet for Waveshare ESP32-C5-Touch-LCD-3.5 with web OTA, SD captures, d… |
| 1047 | [DeaDHackSTeam/HSHunter-1.0.0-Fixed](https://github.com/DeaDHackSTeam/HSHunter-1.0.0-Fixed) | 2 | Shell |  HSHunter Atomated Wireless Key Hacking Tool, handshakes are the wifi keys. When having a key in … |
| 1048 | [dela-99/WIFI-HACKING](https://github.com/dela-99/WIFI-HACKING) | 2 | Python | Ethical WiFi pentesting. OFFENSIVE (explicit written permission) to spot flaws like weak encrypti… |
| 1049 | [DesignGraveyard/V004_ESP32_Global_Control](https://github.com/DesignGraveyard/V004_ESP32_Global_Control) | 2 | C++ | Control your ESP32 globally without WiFi router hacks or port-forwarding. Please check the code a… |
| 1050 | [Dev-Lahrani/Evil-Twin_Wifi-Detection](https://github.com/Dev-Lahrani/Evil-Twin_Wifi-Detection) | 2 | Python | Deterministic Wi-Fi evil-twin detector for Raspberry Pi/Linux: explainable rule engine and RF fin… |
| 1051 | [Dhananjay-saxena/Wifi-deAuth-ESP-32](https://github.com/Dhananjay-saxena/Wifi-deAuth-ESP-32) | 2 | — | A lightweight and powerful tool built for the ESP32 that demonstrates Wi-Fi deauthentication atta… |
| 1052 | [DiamondsBattle/Sqkele](https://github.com/DiamondsBattle/Sqkele) | 2 | — | A python all-in-one toolkit packed with tons of different features, including iOS and Android app… |
| 1053 | [diegojoel301/PwnArduinoAutomatron](https://github.com/diegojoel301/PwnArduinoAutomatron) | 2 | Python | Esta herramienta se encarga de hacer que tu placa Arduino Leonardo funcione como un Rubber Ducky … |
| 1054 | [digenaldo/h4kfi](https://github.com/digenaldo/h4kfi) | 2 | Python | Wireless penetration testing framework with MCP integration built for OpenCode (Claude Code suppo… |
| 1055 | [dimitrisss/ESP32-WiFi-Jammer](https://github.com/dimitrisss/ESP32-WiFi-Jammer) | 2 | — |  |
| 1056 | [diyandexperiment/ShadowHawk-Pro](https://github.com/diyandexperiment/ShadowHawk-Pro) | 2 | — | ShadowHawk Pro is a powerful, all-in-one WiFi security testing tool built on the ESP8266 (NodeMCU… |
| 1057 | [DrEggdwarf/Argos](https://github.com/DrEggdwarf/Argos) | 2 | Kotlin | Android WiFi security auditing app — pentesting, GPS trilateration, Evil Twin, AI captive portals |
| 1058 | [Eivs/BeeperTX](https://github.com/Eivs/BeeperTX) | 2 | C | ESP32-S3 + Si4463 dual-protocol (POCSAG / FLEX) pager transmitter with a web UI, serial CLI, WiFi… |
| 1059 | [ElusiveFoxie/WiFi-Password-Phishing](https://github.com/ElusiveFoxie/WiFi-Password-Phishing) | 2 | PHP | Simple PHP code for stealing WiFi passwords using evil twin attacks |
| 1060 | [erkanrzgc/wlan-dumper](https://github.com/erkanrzgc/wlan-dumper) | 2 | Python | Terminal WiFi cracking toolkit: scan 802.11, deauth, capture WPA handshakes, crack. Textual TUI. … |
| 1061 | [error0327/ESP8266-Deauther](https://github.com/error0327/ESP8266-Deauther) | 2 | C | ESP8266-Deauther Wifi Hacker |
| 1062 | [eshwargit2/Kali_Deauther](https://github.com/eshwargit2/Kali_Deauther) | 2 | Python | Used to a  Esp8266 wifi deather flimeware based api access in to terminal line execution  |
| 1063 | [Ethhacks-official/Wireless-Protect_Service_Version](https://github.com/Ethhacks-official/Wireless-Protect_Service_Version) | 2 | Python | An open source tool to detect deauth, Evil Twin, Clonned wifi, Arp Spoofing and Man in the Middle… |
| 1064 | [favian-jpt/wiCrack](https://github.com/favian-jpt/wiCrack) | 2 | Shell | WiFi pentest is a penetration testing tool that can be used in the field of security testing |
| 1065 | [Figarow/eapol-hunter-flipper](https://github.com/Figarow/eapol-hunter-flipper) | 2 | C | EAPOL/PMKID Hunter für Flipper Zero - analysiert WiFi-Marauder-Captures direkt am Gerät, exportie… |
| 1066 | [G4MEOVER18/heltec-ukfe-rx](https://github.com/G4MEOVER18/heltec-ukfe-rx) | 2 | C++ | Heltec V3 (ESP32-S3+SX1262): 868-FSK+ESP-NOW Satellit/Hub des G4MEOVER-Oekosystems. Handler: WiFi… |
| 1067 | [G4MEOVER18/lilygo-ukfe-rx](https://github.com/G4MEOVER18/lilygo-ukfe-rx) | 2 | C++ | G4MEOVER LilyGo T-Dongle S3: ESP-NOW-Satellit. Handler: USB-HID (BadUSB), WiFi (Deauth/Beacon/Sca… |
| 1068 | [gentlemencoder/Wifi-Jammer](https://github.com/gentlemencoder/Wifi-Jammer) | 2 | Pascal | convert nodemcu esp8266 to wifi signal cutter |
| 1069 | [Ghost-Bx1/ghost-wifi](https://github.com/Ghost-Bx1/ghost-wifi) | 2 | Python | WiFi attack framework - monitor mode, deauth, WPA/WPA2 handshake, PMKID, WPS Pixie Dust, Evil Twi… |
| 1070 | [giridarane/Wifi-Jamer](https://github.com/giridarane/Wifi-Jamer) | 2 | Python | his tool is a **Wi-Fi deauthentication (deauth) jammer** that can send deauth packets to a target… |
| 1071 | [GlomarGadaffi/wifi-ble-marauder](https://github.com/GlomarGadaffi/wifi-ble-marauder) | 2 | C | Pure ESP-IDF 6.0.1 WiFi/BLE security tool: 5GHz deauth, Thread/Matter scanning, BLE 5.0 ext adv. … |
| 1072 | [gn0sys11root/bluetm-wifi-osint-toolkit](https://github.com/gn0sys11root/bluetm-wifi-osint-toolkit) | 2 | Shell | WiFi pentesting framework with OSINT capabilities, DNS spoofing, captive portal, and handshake ca… |
| 1073 | [Grostl/esp32-mac-collector](https://github.com/Grostl/esp32-mac-collector) | 2 | C++ | Dual-band (2.4/5 GHz) Wi-Fi & Bluetooth LE sniffer for ESP32-C5. Captures MAC addresses from Prob… |
| 1074 | [gurvinny/spectre](https://github.com/gurvinny/spectre) | 2 | Python | WiFi intrusion-detection sensor: ESP32-C5 sniffer to FastAPI detection to Next.js SOC console wit… |
| 1075 | [gyf304/occupancy-sniffer](https://github.com/gyf304/occupancy-sniffer) | 2 | C | A secure wifi sniffer |
| 1076 | [h435er/ESP32-WIFI-PENTESER](https://github.com/h435er/ESP32-WIFI-PENTESER) | 2 | C++ | An wifi penetration testing tool for the ESP32 with some cool functions like an Pwnagotchi or an … |
| 1077 | [hackingyseguridad/jammerwifi](https://github.com/hackingyseguridad/jammerwifi) | 2 | Shell | Denegacion de servicio a punto de acceso Wifi  |
| 1078 | [Hareesh-Rajput/WiFi-Pentest](https://github.com/Hareesh-Rajput/WiFi-Pentest) | 2 | — | A structured and actionable Excel-based checklist for WiFi penetration testing, covering every ph… |
| 1079 | [Harsh-Parasharj/Aerosniff-x3](https://github.com/Harsh-Parasharj/Aerosniff-x3) | 2 | C++ | AeroSniff X3: WiFi, BLE, drone, jamming & packet sniffing tool with OLED & web UI, controls via b… |
| 1080 | [Harsh-Tagra/wifi_jamer](https://github.com/Harsh-Tagra/wifi_jamer) | 2 | Shell | wifi jam dos attack |
| 1081 | [harsh13pro/ESP32-Evil-Twin-Deauther-WiFi-Pentest-Tool-](https://github.com/harsh13pro/ESP32-Evil-Twin-Deauther-WiFi-Pentest-Tool-) | 2 | — |  |
| 1082 | [hassanzprofile/wifi-jammer](https://github.com/hassanzprofile/wifi-jammer) | 2 | Shell | A Wi-Fi jammer script or tool is designed to disrupt and disable wireless communications between … |
| 1083 | [hdog27/airgeddon-evil-twin-captive-portal](https://github.com/hdog27/airgeddon-evil-twin-captive-portal) | 2 | — | Evil Twin captive portal WiFi attack using Airgeddon v11.61 on Kali Linux with Panda Wireless AC6… |
| 1084 | [hisham1665/Wifi_Pentester](https://github.com/hisham1665/Wifi_Pentester) | 2 | Python |  |
| 1085 | [hixmfu/WIFI-TOOLKIT](https://github.com/hixmfu/WIFI-TOOLKIT) | 2 | HTML | 🔍 Simplify WiFi pentesting with WIFI-TOOLKIT, a utility that integrates essential tools like Airc… |
| 1086 | [Hoanqnguyen292/Oled-Deauther](https://github.com/Hoanqnguyen292/Oled-Deauther) | 2 | C++ | Affordable WiFi hacking platform for testing and learning |
| 1087 | [IAbrahamI/Wifi_Scanner](https://github.com/IAbrahamI/Wifi_Scanner) | 2 | C++ | Multi-boot pocket RF gadget powered by ESP32-S3. Includes a touch-based boot launcher, active fla… |
| 1088 | [internettrashh/esp8266-wifi-deauter](https://github.com/internettrashh/esp8266-wifi-deauter) | 2 | C | my version of the wifi deauther compatible with chinese display modules |
| 1089 | [izaanhussain/Wifi-Death-V1](https://github.com/izaanhussain/Wifi-Death-V1) | 2 | C++ | A ESP32 based wifi hacking tool with esp32 c3 and 0.96 inch oled dsplay |
| 1090 | [J1rs/Jir32](https://github.com/J1rs/Jir32) | 2 | — | ESP32-based wireless security & signal research system: Integrated tools for WiFi, Bluetooth, and… |
| 1091 | [Jevonte07/WIFI-DEauther-Watch](https://github.com/Jevonte07/WIFI-DEauther-Watch) | 2 | C | The Deauther Watch is a compact, wearable device built using the ESP8266 microcontroller that per… |
| 1092 | [Joaquin7gg/esp32-pc-monitor](https://github.com/Joaquin7gg/esp32-pc-monitor) | 2 | C++ | Dashboard fisico ESP32-S3 (AMOLED) con metricas del PC en tiempo real y sensor WiFi defensivo (de… |
| 1093 | [joe-speedboat/embedded.esp8266.wifi_deauth](https://github.com/joe-speedboat/embedded.esp8266.wifi_deauth) | 2 | C++ | ESP8266 Wifi Deauth IoT  for Arduino IDE (Tested with ESP-01) |
| 1094 | [JoeSaf/Rouge_AP](https://github.com/JoeSaf/Rouge_AP) | 2 | Shell | A man in the middle tools which also creates evil twins and rouge WiFi’s (still in development) |
| 1095 | [Join-Exception/Wifi-BLE-Jammer](https://github.com/Join-Exception/Wifi-BLE-Jammer) | 2 | C++ |  |
| 1096 | [jrdnlrs/Pentacles](https://github.com/jrdnlrs/Pentacles) | 2 | Kotlin | Expected Thesis Output - an Android app that protects Filipino mobile users from fake WiFi networ… |
| 1097 | [jrsmile/ODROID-GO-WIFI-SNIFFER](https://github.com/jrsmile/ODROID-GO-WIFI-SNIFFER) | 2 | C | Custom Firmware for the ODROID-GO to save pcap files to sd-card |
| 1098 | [Juanx65/WifiSniffing](https://github.com/Juanx65/WifiSniffing) | 2 | Python | Testing A Case Study of WiFi Sniffing of Probe request |
| 1099 | [k4u5h4L/CrackEasy](https://github.com/k4u5h4L/CrackEasy) | 2 | Shell | A WiFi cracking script which eases the process of bruteforcing and capturing handshakes. |
| 1100 | [kaangoksal/wifi_device_stalker](https://github.com/kaangoksal/wifi_device_stalker) | 2 | Python | This piece of software is designed to sniff wifi packets and gather information about the sources… |
| 1101 | [kazawa392010/Deauth_Attack_WiFi_With_ESP32](https://github.com/kazawa392010/Deauth_Attack_WiFi_With_ESP32) | 2 | C++ | Dùng esp32 wroom |
| 1102 | [kes229229/JAM-PACK](https://github.com/kes229229/JAM-PACK) | 2 | C++ | 📡 Ultimate multi-tool firmware for ESP32 · WiFi · BLE · SubGHz · IR · GPIO · BETA |
| 1103 | [KevinDevSecOps/WifiKiller](https://github.com/KevinDevSecOps/WifiKiller) | 2 | Python | ### ⚡ **WiFiKiller (Educational)**   *"Aprende pentesting WiFi como un profesional"*   **Descripc… |
| 1104 | [Kim-San04/Wireless-Hacking-Concepts-Methods-Security](https://github.com/Kim-San04/Wireless-Hacking-Concepts-Methods-Security) | 2 | — | WPA2/WPA3, Aircrack-ng, Handshake attacks, Evil Twin — Wireless Security \| ESMT Dakar |
| 1105 | [Kry9toN/Wifi-Deauther-app](https://github.com/Kry9toN/Wifi-Deauther-app) | 2 | Java |  |
| 1106 | [lennarddaw/esp-wifi-tool](https://github.com/lennarddaw/esp-wifi-tool) | 2 | C | A lightweight ESP32-based Wi-Fi tool for scanning, analyzing, and interacting with nearby network… |
| 1107 | [LiamJ74/5g-wifi-deauther-app-for-flipper-for-backpack-board](https://github.com/LiamJ74/5g-wifi-deauther-app-for-flipper-for-backpack-board) | 2 | — | 5g wifi deauther app for flipper for backpack board |
| 1108 | [LieBtrau/esp32-wifi-sniffer](https://github.com/LieBtrau/esp32-wifi-sniffer) | 2 | C++ | wifi packet analyzer for ESP32 |
| 1109 | [Ludmilahttps/Jammer-WiFi-Bluetooth-ESP32](https://github.com/Ludmilahttps/Jammer-WiFi-Bluetooth-ESP32) | 2 | JavaScript | Protótipo de bloqueador de sinais sem fio (Wi-Fi/Bluetooth) na faixa de 2.4 GHz, desenvolvido com… |
| 1110 | [lukepereira/WiFiJammer](https://github.com/lukepereira/WiFiJammer) | 2 | Arduino |  |
| 1111 | [lumingmmlm/BW16-5GHZ-WiFi--Deauther](https://github.com/lumingmmlm/BW16-5GHZ-WiFi--Deauther) | 2 | C++ | 关于BW16的WiFi杀手 |
| 1112 | [m6c7l/tepsots](https://github.com/m6c7l/tepsots) | 2 | Python | Lightweight IEEE 802.11 Packet Sniffer |
| 1113 | [mackg1288-pixel/packet-squirrel](https://github.com/mackg1288-pixel/packet-squirrel) | 2 | Python | DIY network interception platform built with NanoPi NEO3 + ESP32. Inline Ethernet bridge with WiF… |
| 1114 | [Mahardika-Tech/mahardika-tech-esp32-wifi-ble-jammer](https://github.com/Mahardika-Tech/mahardika-tech-esp32-wifi-ble-jammer) | 2 | — | Jamming wifi & bluethooth with esp32 support oled or lcd. |
| 1115 | [ManojKumar-ind001/wifi-attaking-tool-easy-to-use](https://github.com/ManojKumar-ind001/wifi-attaking-tool-easy-to-use) | 2 | Python | MxAI WiFi Tool - A powerful cross-platform WiFi security assessment tool for penetration testing.… |
| 1116 | [marcelomd/wifi-lateration](https://github.com/marcelomd/wifi-lateration) | 2 | C | Packet sniffer and trilateration to locate devices using wifi |
| 1117 | [marpelskiy/pySniff---smart-wifi-sniffer](https://github.com/marpelskiy/pySniff---smart-wifi-sniffer) | 2 | Python | A smart Wi-Fi sniffer with the ability to send data to your Telegram bot and log it. |
| 1118 | [matiaslahore/wifi-sniffer](https://github.com/matiaslahore/wifi-sniffer) | 2 | C | track people through a mall through smart devices |
| 1119 | [maviaydin044-max/BlueDrogom](https://github.com/maviaydin044-max/BlueDrogom) | 2 | C++ | This software carries out kill attacks using the ESP32's Wi-Fi antennas.    PLEASE ONLY ATTACK YO… |
| 1120 | [michanisani/wifi_sniffer](https://github.com/michanisani/wifi_sniffer) | 2 | Python | wifi sniffer |
| 1121 | [MikeRicketts/wifi-wpa2-handshake-cracking](https://github.com/MikeRicketts/wifi-wpa2-handshake-cracking) | 2 | — | Hands-on WPA2 4-way handshake capture-and-crack (Wireshark to hcxtools to hashcat), and how WPA3-… |
| 1122 | [Mizu-Tech/mizu-tech-esp32-wifi-ble-jammer](https://github.com/Mizu-Tech/mizu-tech-esp32-wifi-ble-jammer) | 2 | — |  |
| 1123 | [MohitPatil2402/esp-drone-tracking](https://github.com/MohitPatil2402/esp-drone-tracking) | 2 | Python | Drone-based crowd monitoring using ESP32 WiFi sniffing and trilateration |
| 1124 | [Mr-Zer00/Driver-nodeMCU-ESP8266](https://github.com/Mr-Zer00/Driver-nodeMCU-ESP8266) | 2 | — | Wifi-deauther em micro-controlador |
| 1125 | [Nadoooor/SnakeHunter](https://github.com/Nadoooor/SnakeHunter) | 2 | — | An ESP32 wifi, bluetooth, IR, etc hacking device with touch screen. |
| 1126 | [neohiro/lora-sniffer](https://github.com/neohiro/lora-sniffer) | 2 | C++ | Passive LoRa sniffer firmware for the Heltec WiFi LoRa 32 V4, built to run as its own slot alongs… |
| 1127 | [NGDSA-Lab/WiFi-CTF](https://github.com/NGDSA-Lab/WiFi-CTF) | 2 | HTML | Self-hosted virtual WiFi pentesting environment using Docker and mac80211_hwsim kernel module. Id… |
| 1128 | [NNLisk/Wi-fi-sniffer](https://github.com/NNLisk/Wi-fi-sniffer) | 2 | C | A project to build a wifi sniffer on an Espressif ESP32 microcontroller |
| 1129 | [ocamposbio/ESP8266Sniff](https://github.com/ocamposbio/ESP8266Sniff) | 2 | C++ | Simple ESP8266 Wifi Sniffer project |
| 1130 | [OttPeterR/Trakr](https://github.com/OttPeterR/Trakr) | 2 | Python | WiFi MAC Address sniffer that tracks when devices enter and exit areas regardless of wifi connect… |
| 1131 | [paran0ids0ul/hubbIT-sniffer](https://github.com/paran0ids0ul/hubbIT-sniffer) | 2 | Python | Simple application that listens for WIFI-frames and records the mac-address of the sender and pos… |
| 1132 | [pedroasr/Sniffer_Wifi](https://github.com/pedroasr/Sniffer_Wifi) | 2 | JavaScript |  |
| 1133 | [possiblinkz/Wifite](https://github.com/possiblinkz/Wifite) | 2 | Python | an open-source, automated Python script designed to audit the security of Wi-Fi networks (WEP, WP… |
| 1134 | [PranavGajjar0305/WifiJammer](https://github.com/PranavGajjar0305/WifiJammer) | 2 | Python |  |
| 1135 | [prosaugat/wifi-jammer](https://github.com/prosaugat/wifi-jammer) | 2 | Python | Wifi jammer source code in python. |
| 1136 | [PythonJu80/sniffymapp](https://github.com/PythonJu80/sniffymapp) | 2 | — | In a Nutshell 🛰️  This is a **comprehensive GPS security analysis toolkit** that combines passive… |
| 1137 | [Q3hr/Blackout-2.4](https://github.com/Q3hr/Blackout-2.4) | 2 | C | Blackout 2.4 is a 5th Semester Network Security project that explores 2.4 GHz spectrum behavior a… |
| 1138 | [r00thex/wifi-jammer](https://github.com/r00thex/wifi-jammer) | 2 | Python |  |
| 1139 | [R09Aditya/ESP-Marauder](https://github.com/R09Aditya/ESP-Marauder) | 2 | — | ESP Marauder is a cybersecurity tool used to jam, analyze and do alot of things on wifi or blueto… |
| 1140 | [R0b1nary/radiosniffer](https://github.com/R0b1nary/radiosniffer) | 2 | Python | tool to sniff for wifi and bluetooth devices |
| 1141 | [r0ug3/WiFi_Jammer](https://github.com/r0ug3/WiFi_Jammer) | 2 | Python | Jam all wifi clients and access points within range. |
| 1142 | [raupulus/esp8266-wifi-spam](https://github.com/raupulus/esp8266-wifi-spam) | 2 | C++ | Demo practicando pentesting y esp8266 creando puntos de acceso (AP) - Mirror de https://gitlab.co… |
| 1143 | [ravshansaginbaev/ESP32-Wifi-Deauthenticator](https://github.com/ravshansaginbaev/ESP32-Wifi-Deauthenticator) | 2 | C |  |
| 1144 | [Rayan-Shareefi/WiFi-Intrusion-Detection-System-with-Encrypted-Cloud-Alerting](https://github.com/Rayan-Shareefi/WiFi-Intrusion-Detection-System-with-Encrypted-Cloud-Alerting) | 2 | Python | An ESP32 that detects Wi-Fi attacks (deauth, evil twin, unknown devices) and sends encrypted aler… |
| 1145 | [RaymondReddington479/Wi-PWN](https://github.com/RaymondReddington479/Wi-PWN) | 2 | C | Wi-Deauther, open source project, test on wifi, project based on the samdenty project. |
| 1146 | [revjmoney/simian-radar](https://github.com/revjmoney/simian-radar) | 2 | C++ | Listen-only pocket privacy scanner for the Heltec LoRa 32 V4: offline US ALPR camera alerts, trac… |
| 1147 | [Rockyrook96/Esp8266_Wifi_Jammer](https://github.com/Rockyrook96/Esp8266_Wifi_Jammer) | 2 | — | "An open-source ESP8266 Deauther project for testing Wi-Fi network security against deauthenticat… |
| 1148 | [rrrahat/Wifi-Jammer](https://github.com/rrrahat/Wifi-Jammer) | 2 | Python | A Wi-Fi testing tool for educational purposes |
| 1149 | [Rudii-25/BloodHound_VENOM](https://github.com/Rudii-25/BloodHound_VENOM) | 2 | HTML | BloodHound VENOM is an open-source hackable handheld IoT device for makers and developers. ESP826… |
| 1150 | [rukstovv-hash/Alfa-AWUS036ACH](https://github.com/rukstovv-hash/Alfa-AWUS036ACH) | 2 | Python | Offensive WiFi toolkit for the ALFA AWUS036ACH — deauth, PMKID capture, WPS PIN brute, evil twin,… |
| 1151 | [sagikandleker/WiFi-Evil-Twin](https://github.com/sagikandleker/WiFi-Evil-Twin) | 2 | Python | Fraudulent access point with phishing website |
| 1152 | [SaifKhan2002/Wifi_Jammer_System_8086](https://github.com/SaifKhan2002/Wifi_Jammer_System_8086) | 2 | C |  |
| 1153 | [salvul/Arduino_JammerWiFi](https://github.com/salvul/Arduino_JammerWiFi) | 2 | C | Create Wifi Jammer |
| 1154 | [SantiagoRR2004/APS-WiFiSniffer](https://github.com/SantiagoRR2004/APS-WiFiSniffer) | 2 | C | Contador de personas |
| 1155 | [saravanasai1435/esp32-marauder-wifi-bt-security-tool](https://github.com/saravanasai1435/esp32-marauder-wifi-bt-security-tool) | 2 | — | ESP32 Marauder WiFi/Bluetooth security toolkit: deauth, beacon spam, evil portal, GPS, SD logging… |
| 1156 | [secuRefeds/wifi-deauth](https://github.com/secuRefeds/wifi-deauth) | 2 | Python | wifi  deauther |
| 1157 | [shahabmohamadi/ESP32-Twin-WiFi-Hacking-Deauthentication-Captive-Portal](https://github.com/shahabmohamadi/ESP32-Twin-WiFi-Hacking-Deauthentication-Captive-Portal) | 2 | C++ | Disclaimer: This project is for educational purposes only. Use it responsibly and legally. Unauth… |
| 1158 | [shahafel/wifi-jammer](https://github.com/shahafel/wifi-jammer) | 2 | — | python script using hackrf to jam wifi signals |
| 1159 | [Shibasish-Dalui/Evil-Twin-Attack](https://github.com/Shibasish-Dalui/Evil-Twin-Attack) | 2 | C++ | Wifi network's security test using de-authentication and fake access point |
| 1160 | [sidak/WiFi-Sniffing-and-Distributed-Computing](https://github.com/sidak/WiFi-Sniffing-and-Distributed-Computing) | 2 | C | Packet Sniffing and Distributed Computing tools for WiFi |
| 1161 | [siul72/ksoft-wifi-serial-spy](https://github.com/siul72/ksoft-wifi-serial-spy) | 2 | C++ | Embedded device software for sniffing RS-485 bus communication lines and publish the serial data … |
| 1162 | [sUbc0ol/deauth](https://github.com/sUbc0ol/deauth) | 2 | Python | wifi jammer written in python |
| 1163 | [sumit814/ESP8266-WiFi-Jammer](https://github.com/sumit814/ESP8266-WiFi-Jammer) | 2 | C++ | A web-based Wi-Fi deauthentication tool made using ESP8266. |
| 1164 | [Swastika27/WiFi-password-crack](https://github.com/Swastika27/WiFi-password-crack) | 2 | Python | A custom tool for WiFi password cracking from captured WPA2 handshake frames and smart wordlist  |
| 1165 | [SwordsmanStronghold/deautherx-pro](https://github.com/SwordsmanStronghold/deautherx-pro) | 2 | Go | DeautherX Pro — продвинутая утилита для аудита безопасности Wi-Fi сетей (802.11). Инструмент позв… |
| 1166 | [t84RT/ESP8266-WiFi-Deauther-Beacon-Spammer-with-Web-UI](https://github.com/t84RT/ESP8266-WiFi-Deauther-Beacon-Spammer-with-Web-UI) | 2 | C++ | Wi-Fi 安全研究与网络管理工具 基于 ESP8266 的 802.11 管理帧注入测试平台，支持 AP/STA 扫描、Deauthentication 攻击模拟、Beacon 广告机及现代化… |
| 1167 | [Tanmay1894/ESP32-Flipper](https://github.com/Tanmay1894/ESP32-Flipper) | 2 | C++ | ESP32 Flipper is a touchscreen-driven toolkit for wireless security testing on ESP32. It features… |
| 1168 | [tanvir-ahamed04/wifi-packet-sniffer](https://github.com/tanvir-ahamed04/wifi-packet-sniffer) | 2 | Python |  |
| 1169 | [TaxCoding/ESP32-MultiTarget-Deauth-Engine](https://github.com/TaxCoding/ESP32-MultiTarget-Deauth-Engine) | 2 | CMake | Wifi deuther, deauthentication attack. An ESP32-based Wi-Fi research project exploring IEEE 802.1… |
| 1170 | [tchaiwanda/wifi-security-lab](https://github.com/tchaiwanda/wifi-security-lab) | 2 | — | Hands-on wireless security lab using ESP8266 Deauther and isolated guest network for ethical hack… |
| 1171 | [Th4ntis/Evil-Portals](https://github.com/Th4ntis/Evil-Portals) | 2 | CSS | Evil-Portals for WiFi Pineapples and other WiFi Pentesting |
| 1172 | [The-SPARK-Initiative-Labs/Symbiosis-WiFiArsenal](https://github.com/The-SPARK-Initiative-Labs/Symbiosis-WiFiArsenal) | 2 | Python | A WiFi penetration testing platform with attack automation, evil twin portals, wardrive integrati… |
| 1173 | [the-vnx/Wifi-Jammer-With-Node-MCU](https://github.com/the-vnx/Wifi-Jammer-With-Node-MCU) | 2 | — | A simple Wifi jammer with esp8266 or node mcu |
| 1174 | [The90Frank/PresenceChecker](https://github.com/The90Frank/PresenceChecker) | 2 | Python | WiFi 802.11 packet sniffer and device detector for Linux with signal analysis and XML logging |
| 1175 | [TheImposterz/RaspPunzel](https://github.com/TheImposterz/RaspPunzel) | 2 | Shell | RaspPunzel is a Raspberry Pi-based penetration testing platform that transforms a Pi into a porta… |
| 1176 | [TheKanjiTV/Beacon](https://github.com/TheKanjiTV/Beacon) | 2 | Swift | 📊 Track user behavior in Swift apps easily with Beacon, offering offline persistence, device cont… |
| 1177 | [thevixer/ESP32-Promiscuous-osc](https://github.com/thevixer/ESP32-Promiscuous-osc) | 2 | C++ | An esp32 promiscuous mac address sniffer with osc messaging |
| 1178 | [thex1le/py80211](https://github.com/thex1le/py80211) | 2 | Python | pure python wifi sniffer |
| 1179 | [Thilakkumar0308/IRUTESAM-Dark-Venom](https://github.com/Thilakkumar0308/IRUTESAM-Dark-Venom) | 2 | C++ | IRUTESAM is an ESP32-based IoT hacking toolkit with a custom hacker-style touchscreen UI. It supp… |
| 1180 | [ThinkEE/python-WiFiSniffer](https://github.com/ThinkEE/python-WiFiSniffer) | 2 | Python | Small python script to use a wifi chip in monitor mode to send packets received through UDP |
| 1181 | [Trsak/WifiSniffer](https://github.com/Trsak/WifiSniffer) | 2 | C++ | Tool for sniffing Wi-Fi data packets between client and access point. Uses libtins and libpcap li… |
| 1182 | [truemorganss/wraithnet](https://github.com/truemorganss/wraithnet) | 2 | Python | A multitool for pentesting WiFi networks |
| 1183 | [Try-harder-not-smarter/Proyect-EvilTwin-ESP32](https://github.com/Try-harder-not-smarter/Proyect-EvilTwin-ESP32) | 2 | C++ | Educational simulation of a WiFi Evil Twin attack with ESP32 — technical lab documentation |
| 1184 | [tworjaga/Esp32watchdog](https://github.com/tworjaga/Esp32watchdog) | 2 | C++ | Passive Wi-Fi threat monitor for ESP32. Detects deauth floods, evil twin APs and beacon floods in… |
| 1185 | [uffea/wifi_sniffer_setup](https://github.com/uffea/wifi_sniffer_setup) | 2 | Shell |  |
| 1186 | [uncleNas/wifiSnifferWithESP32](https://github.com/uncleNas/wifiSnifferWithESP32) | 2 | C++ | Cybersecurity hardware device:  implementing packet analyzer using ESP32, LCD, and I2C adapter |
| 1187 | [unnamedperson488/BlackHoleV1.0](https://github.com/unnamedperson488/BlackHoleV1.0) | 2 | C++ | A dual-band WiFi deauther built for power, stealth, and simplicity — powered by the RTL8720DN (BW… |
| 1188 | [Vagalam88/FreqSniff](https://github.com/Vagalam88/FreqSniff) | 2 | C++ | Combined WiFi + LoRa/Meshtastic passive sniffer for the Heltec WiFi LoRa32 V2 |
| 1189 | [vaibhavhere2003/wifi-autopwn](https://github.com/vaibhavhere2003/wifi-autopwn) | 2 | — | 🔍 Enhance WiFi security with this advanced penetration testing tool, covering generations from Wi… |
| 1190 | [Valbef/DeauthDetectorESP32](https://github.com/Valbef/DeauthDetectorESP32) | 2 | Python | detector de tramas deauth para Linux, usar con modulos wifi con modo monitor o con  ESP32-WROOM-32. |
| 1191 | [visionSensor/esp-deauther-detector](https://github.com/visionSensor/esp-deauther-detector) | 2 | C++ | detect wifi deauther with little effort. |
| 1192 | [Vola12do/IoT-WiFi-Attack-Tools-ESP8266-Deauther](https://github.com/Vola12do/IoT-WiFi-Attack-Tools-ESP8266-Deauther) | 2 | C++ | "A project leveraging ESP8266 for WiFi Deauth and Evil Twin attacks." |
| 1193 | [voltwizeshea/DarkMatter_Duck](https://github.com/voltwizeshea/DarkMatter_Duck) | 2 | C++ | Dual-stack HID weapon on ESP32-S3: USB + BLE keystroke injection, WiFi C2, payload chains. One of… |
| 1194 | [vslinuxdotnet/ESP32-Evil-Twin](https://github.com/vslinuxdotnet/ESP32-Evil-Twin) | 2 | C++ | ESP32 Evil Twin WiFi Hacking, Deauthentication  |
| 1195 | [Vybenclave/wifi-d_vice](https://github.com/Vybenclave/wifi-d_vice) | 2 | C | WIFI D_VICE - passive Wi-Fi / BLE / sub-GHz radio-monitoring tool for the 2.8-inch ESP32 CYD. No … |
| 1196 | [wk12100lol-prog/vexhack](https://github.com/wk12100lol-prog/vexhack) | 2 | C++ | VEXHACK - WiFi pentest tool for CYD ESP32-2432S028R. Features: WiFi scanner, deauth attack, clien… |
| 1197 | [WU-AetherCore/airgeddon-evil-twin-lab](https://github.com/WU-AetherCore/airgeddon-evil-twin-lab) | 2 | Python | Airgeddon Evil Twin Lab - WiFi安全攻防实战实验室：Evil Twin自动化钓鱼系统（Web控制台一键攻击+密码自动验证）+ 8篇详细中文教程 + 一键部署脚本。仅限… |
| 1198 | [xiixim101-pixel/sniffus](https://github.com/xiixim101-pixel/sniffus) | 2 | HTML | High-speed ESP8266 WiFi sniffer with real-time Web Serial API dashboard. Captures raw 802.11 fram… |
| 1199 | [xiv3r/esp32-deauth-detector](https://github.com/xiv3r/esp32-deauth-detector) | 2 | C++ | esp32 wifi deauth detector with led and buzzer notifications |
| 1200 | [xiv3r/esp32-jammer-detector](https://github.com/xiv3r/esp32-jammer-detector) | 2 | C++ | Detect deauthentication frames using esp32 (commonly known wifi jamming) |
| 1201 | [xuananbui/wifi-pentesting-cheatsheet](https://github.com/xuananbui/wifi-pentesting-cheatsheet) | 2 | — |  |
| 1202 | [yNeoo/wireless-hacking](https://github.com/yNeoo/wireless-hacking) | 2 | Shell | Auditoría WiFi en laboratorio: monitor mode, handshake/PMKID, WPA/WPA2/WPA3, WPS, Evil-Twin + det… |
| 1203 | [yt2600/WiFry](https://github.com/yt2600/WiFry) | 2 | — | WiFry is a simple PAsrberry Pi based wifi jammer. The idea of the project is to create a easy to … |
| 1204 | [YurilLAB/esp32-SnowOwl](https://github.com/YurilLAB/esp32-SnowOwl) | 2 | — | A multi-purpose wireless offensive & defensive security multitool — ESP32-S3 + ARM Linux, with NF… |
| 1205 | [Zer0D0wn/Jammer](https://github.com/Zer0D0wn/Jammer) | 2 | Perl | A perl wifi jammer who use an packet injection capable interface. Tested with Alfa AWUS1900. |
| 1206 | [0000000O0Oo/Wifi-Deauther](https://github.com/0000000O0Oo/Wifi-Deauther) | 1 | Python | Script made by me and ec404-cool => htts://github.com/ec404-cool |
| 1207 | [0EchoPixel/ESP32-Bluetooth-Jammer](https://github.com/0EchoPixel/ESP32-Bluetooth-Jammer) | 1 | C++ | ESP32 + NRF24L01 That jams WIFI and Bluetooth  |
| 1208 | [0xHadiRamdhani/wifi-deauther](https://github.com/0xHadiRamdhani/wifi-deauther) | 1 | Rust |  |
| 1209 | [0xStr1k3r/AeroStrike](https://github.com/0xStr1k3r/AeroStrike) | 1 | Python | Wifi Pentesting Tool |
| 1210 | [123tool/Wifi-Spy-Hacking](https://github.com/123tool/Wifi-Spy-Hacking) | 1 | Python | Alat audit keamanan jaringan nirkabel dan pengujian penetrasi jaringan yang komprehensif. Diranca… |
| 1211 | [1destroyer100yt/PiFi-network-pentest](https://github.com/1destroyer100yt/PiFi-network-pentest) | 1 | HTML | every thing you need for wifi pentesting on a pi 0 w |
| 1212 | [1mirabbas/esp8266_deauther](https://github.com/1mirabbas/esp8266_deauther) | 1 | C | Description: ESP8266 Deauther is a firmware for testing 802.11 networks on your own 2.4GHz Wi‑Fi.… |
| 1213 | [2272799702qq9/visualapproach1](https://github.com/2272799702qq9/visualapproach1) | 1 | — | Hack - ESP8266 as WiFi remote control for Bestway Lay-Z spa Helsinki |
| 1214 | [810810810/Tell-My-Wifi-Love-Her](https://github.com/810810810/Tell-My-Wifi-Love-Her) | 1 | Python | Written in python for automating wifi pentesting on a pentesting box. Do not use if you dont have… |
| 1215 | [aaemon/wifi-jammer-deauther](https://github.com/aaemon/wifi-jammer-deauther) | 1 | C | Wifi Jammer and Deauther using ESP8266 Wifi Module |
| 1216 | [Aazwd20/deauth-beacon_ESP32](https://github.com/Aazwd20/deauth-beacon_ESP32) | 1 | C++ | trying out different attacks on the wifi with esp32 |
| 1217 | [Abhay-Mahanta/Wifi-Deauther](https://github.com/Abhay-Mahanta/Wifi-Deauther) | 1 | Python | This tool can be used to deauth an access point or client from the network. |
| 1218 | [ABHAYKUMARTRIPATHI/WiFi-Deauther-Simulator](https://github.com/ABHAYKUMARTRIPATHI/WiFi-Deauther-Simulator) | 1 | Python | A powerful Wi-Fi Deauther Simulator that emulates deauthentication attacks in a safe, educational… |
| 1219 | [AbhiramKaduduri/ESP8266_Deauthor](https://github.com/AbhiramKaduduri/ESP8266_Deauthor) | 1 | — | Scan for WiFi devices, block selected connections, create dozens of networks and confuse WiFi sca… |
| 1220 | [Abhishek1033ubuntu/Dynamic-Speed-Limiter-ESP32](https://github.com/Abhishek1033ubuntu/Dynamic-Speed-Limiter-ESP32) | 1 | C++ | An infrastructure-to-vehicle (I2V) wireless speed-control system that dynamically restricts maxim… |
| 1221 | [AbinMM/WIFI_esp8266_deauther](https://github.com/AbinMM/WIFI_esp8266_deauther) | 1 | C | ESP8255 WIFI工具器 |
| 1222 | [adamLevAri/EvilTwin](https://github.com/adamLevAri/EvilTwin) | 1 | Python | Evil Twin hacking WiFi network exploit |
| 1223 | [Adarsha24/Esp8266_DEAUTHER](https://github.com/Adarsha24/Esp8266_DEAUTHER) | 1 | — | Attack:wifi-Dauther,Beacon,Probe.WARNING: LEARNING PURPOSE ONLY |
| 1224 | [adithyanp2005gt-dotcom/wifi-deauthenticator](https://github.com/adithyanp2005gt-dotcom/wifi-deauthenticator) | 1 | C++ | ESP8266-based WiFi Deauthenticator for educational security research |
| 1225 | [Aditya5441/Jammer_Adaptive](https://github.com/Aditya5441/Jammer_Adaptive) | 1 | C++ | an ESP32-based WiFi/BLE jamming device that uses chaos-derived entropy (from internal noise/analo… |
| 1226 | [Adnan0336/Wifi-Hacking-with-ESP8266](https://github.com/Adnan0336/Wifi-Hacking-with-ESP8266) | 1 | — | Exploring WiFi Security Using ESP8266: Deauthentication & Evil Twin Attacks I'm excited to share … |
| 1227 | [adumppp/Esp32-Deauther-](https://github.com/adumppp/Esp32-Deauther-) | 1 | C | this project for Penetration testing using esp32 on wifi |
| 1228 | [affiqadha/Wifi-Security-Scanner](https://github.com/affiqadha/Wifi-Security-Scanner) | 1 | Dart | Advanced Android WiFi security scanner for detecting MITM attacks and Evil Twin networks - FYP Un… |
| 1229 | [Afrochemist/WifiPentesting](https://github.com/Afrochemist/WifiPentesting) | 1 | — |  |
| 1230 | [AGESILAS3118/wpa2-tp-link-writeup](https://github.com/AGESILAS3118/wpa2-tp-link-writeup) | 1 | — | 🛡️ Write-up complet — Crack d'un réseau WPA2 par capture de handshake (TP-Link_0124). Pentest WiF… |
| 1231 | [ahsan-latif-tech/WifiMeNow](https://github.com/ahsan-latif-tech/WifiMeNow) | 1 | Python | Python tool that automates Wi-Fi hacking by capturing WPA/WPA2 handshakes and cracking them using… |
| 1232 | [Akshit0203/flipper-zero-wifi-security-assessment](https://github.com/Akshit0203/flipper-zero-wifi-security-assessment) | 1 | — | Hands-on WPA2-PSK wireless security assessment with a Flipper Zero + ESP32 Marauder — covering th… |
| 1233 | [aksrivastava/wifi-deauther-advance](https://github.com/aksrivastava/wifi-deauther-advance) | 1 | C++ |  |
| 1234 | [AlexisDuran/AutoCrackWifi](https://github.com/AlexisDuran/AutoCrackWifi) | 1 | — | Herramienta que automatiza el ataque a wifi de tipo handshake y PKMID |
| 1235 | [alihaider998/Wifi-Deauther](https://github.com/alihaider998/Wifi-Deauther) | 1 | Python |  |
| 1236 | [AlvGJ-UGR/ESP32-WiFi-Security-Research-Lab](https://github.com/AlvGJ-UGR/ESP32-WiFi-Security-Research-Lab) | 1 | Python | Educational adaptation of the ESP32 Wi-Fi Penetration Tool for studying wireless network security… |
| 1237 | [An0nMac/Wifi-Pentesting](https://github.com/An0nMac/Wifi-Pentesting) | 1 | Shell | The tools i use to pentest wifi |
| 1238 | [Ananyapulluri/wifi-security-analyzer](https://github.com/Ananyapulluri/wifi-security-analyzer) | 1 | Python | Evil Twin & Rogue AP Detector with K-Means ML clustering |
| 1239 | [AnasAbbasiCode/ESP-WiFi-Toolbox](https://github.com/AnasAbbasiCode/ESP-WiFi-Toolbox) | 1 | C++ | A web-based interface for interacting with an ESP32 over Wi-Fi. Allows users to connect, scan nea… |
| 1240 | [anaskhanxada/WifiandBluetoothJammer](https://github.com/anaskhanxada/WifiandBluetoothJammer) | 1 | C | A WiFi and Bluetooth jamming tool built on [ESP32/your hardware] for disrupting wireless signals … |
| 1241 | [AndrewChacon/wifi-evil-twin](https://github.com/AndrewChacon/wifi-evil-twin) | 1 | C++ | An ESP32-based wireless phishing simulator that replicates Evil Twin attacks for research and sec… |
| 1242 | [Anon505950/esp8266-evil-twin](https://github.com/Anon505950/esp8266-evil-twin) | 1 | C++ | Attempt to phish wifi passwords with a captive portal |
| 1243 | [Apoorva08-g/Firmware_Integrity_Monitor](https://github.com/Apoorva08-g/Firmware_Integrity_Monitor) | 1 | Python | Hardware-based firmware integrity monitor using Raspberry Pi Pico W + ESP32. Detects supply chain… |
| 1244 | [aproxtimedev/wifi.id-deauther](https://github.com/aproxtimedev/wifi.id-deauther) | 1 | Shell | Wifi.ID Deauther using Aireplay-ng  |
| 1245 | [armnsec/wireless-security-lab-wifi-pentesting](https://github.com/armnsec/wireless-security-lab-wifi-pentesting) | 1 | — | Wireless security lab demonstrating WPA2 attacks, handshake capture, password cracking, deauthent… |
| 1246 | [AshmitThakur23/wifi-security-analyzer](https://github.com/AshmitThakur23/wifi-security-analyzer) | 1 | Python | WiFi Security Analyzer — A Windows-based personal network security tool that scans your WiFi for … |
| 1247 | [AslamMahi/WiFi-Pentesting](https://github.com/AslamMahi/WiFi-Pentesting) | 1 | — | This guide offers a thorough, step-by-step approach to WiFi pentesting, designed for both beginne… |
| 1248 | [AtherNet29/ESP32-DEAUTHER-DAN-EVILTWIN-AETHERNET](https://github.com/AtherNet29/ESP32-DEAUTHER-DAN-EVILTWIN-AETHERNET) | 1 | — | 🎯 ESP32 Deauther & BT Jammer. Features: Evil Twin, Auto-Password Verify, Beacon Spam, Rogue AP, W… |
| 1249 | [BadRat-in/wifikit](https://github.com/BadRat-in/wifikit) | 1 | Python | Single-screen terminal UI + CLI for authorized WiFi security testing with an ESP32 running ESP32 … |
| 1250 | [baishakh22/Cracking-WiFi-WPA2-Handshake](https://github.com/baishakh22/Cracking-WiFi-WPA2-Handshake) | 1 | — |  |
| 1251 | [basht0p/WarPebble](https://github.com/basht0p/WarPebble) | 1 | Python | A system for wifi hacking / wardriving, designed for the ESP8266 HW-364A microcontroller, or othe… |
| 1252 | [bernie-oss/wifi-jammer-esp8266](https://github.com/bernie-oss/wifi-jammer-esp8266) | 1 | — | Professional Internship Project at UTC2 - 2023 |
| 1253 | [BG7YWL/Wifi-Deauther-Oled-V4-Fake](https://github.com/BG7YWL/Wifi-Deauther-Oled-V4-Fake) | 1 | — |  |
| 1254 | [bhargavvaghasiya12/wifi-deauth-detector-esp32](https://github.com/bhargavvaghasiya12/wifi-deauth-detector-esp32) | 1 | — | Real-Time Wi-Fi Deauthentication Attack Detection System using ESP32 |
| 1255 | [boogiegainz/AirStrike-WiFi](https://github.com/boogiegainz/AirStrike-WiFi) | 1 | — | ⚡ Next-gen WiFi auditing platform — crack captured handshakes on Windows, full attack suite on Li… |
| 1256 | [BrainRape23/Esp_WIFI](https://github.com/BrainRape23/Esp_WIFI) | 1 | — | Esp32_WIFI Analyzer and proofe of Concept Hacking  |
| 1257 | [brandonvader/Sentinel-Watch-OS](https://github.com/brandonvader/Sentinel-Watch-OS) | 1 | C | Passive WiFi + BLE threat monitor for the Waveshare ESP32-S3 AMOLED watch: gravity-driven data-ra… |
| 1258 | [brankkoo/wifi-tool](https://github.com/brankkoo/wifi-tool) | 1 | C | esp32 pentesting firmware |
| 1259 | [BVBGurke/wifi-handshaker](https://github.com/BVBGurke/wifi-handshaker) | 1 | Python | Passive WPA/WPA2 handshake capture on Linux + GPU cracking with hashcat on a Windows host over Ta… |
| 1260 | [byankush/Ble-wifi-jammer-byankush](https://github.com/byankush/Ble-wifi-jammer-byankush) | 1 | C++ | ESP32-based wireless security research project exploring Wi-Fi and Bluetooth protocols, RF commun… |
| 1261 | [byfat1h/ESP8266-WiFi-Jammer](https://github.com/byfat1h/ESP8266-WiFi-Jammer) | 1 | — |  |
| 1262 | [Chinmay2845/Wifi-Deauth-attack-detector-](https://github.com/Chinmay2845/Wifi-Deauth-attack-detector-) | 1 | C++ | Real-time Wi-Fi deauthentication attack detector using ESP8266 NodeMCU in promiscuous mode with S… |
| 1263 | [chinthajayanth/Wifi_Evil_Twin](https://github.com/chinthajayanth/Wifi_Evil_Twin) | 1 | Python | A graphical user interface (GUI) application built with Python and PyQt5. It's designed as a proo… |
| 1264 | [ciccirix/koko-v9](https://github.com/ciccirix/koko-v9) | 1 | C++ | ESP32 Marauder C5 — koko V9: WiFi/BT-only build, features reorganized into stock WiFi/Bluetooth m… |
| 1265 | [CircuitVortex/Esp32-S3-Jammer](https://github.com/CircuitVortex/Esp32-S3-Jammer) | 1 | C++ | It jams Wifi using just Esp32 s3 N16R8 it self. |
| 1266 | [COF10/MicroByte](https://github.com/COF10/MicroByte) | 1 | — | MicroByte is a compact handheld wireless tool built around the Waveshare ESP32-C6-LCD-1.47, featu… |
| 1267 | [comradezephyr/EvilTwinESP32](https://github.com/comradezephyr/EvilTwinESP32) | 1 | Python | ESP32 Evil Twin- WiFi Penetration Testing Tool \| Captive Portal \| Rogue AP |
| 1268 | [cotyloidcavitybutterheadlettuce306/wifi-heatmap](https://github.com/cotyloidcavitybutterheadlettuce306/wifi-heatmap) | 1 | Python | Map WiFi signal strength and coverage gaps locally by plotting measurements onto your floor plans… |
| 1269 | [crackerbyte/esp-cracker](https://github.com/crackerbyte/esp-cracker) | 1 | — | 🍪 Cracker - DIY pentest device on ESP32-S3 with Wi-Fi, BLE, IR, Sub-GHz, 2.4GHz, GPS, NFC, Bad-US… |
| 1270 | [cs-23-sw-7-06/esp32-wifi-sniffer](https://github.com/cs-23-sw-7-06/esp32-wifi-sniffer) | 1 | C++ | ESP32 Wifi sniffer |
| 1271 | [cyberkalki/wifi_deauthentication](https://github.com/cyberkalki/wifi_deauthentication) | 1 | — | A WiFi deauther employing an ESP8266 disrupts wireless connections, rendering devices temporarily… |
| 1272 | [cybersewer/WiFi-Deauther-With-ESP8266-NodeMCU-](https://github.com/cybersewer/WiFi-Deauther-With-ESP8266-NodeMCU-) | 1 | — | Guide to make a WiFi Deauther With ESP8266 (NodeMCU) |
| 1273 | [cyberwolf6938/evil-twin-attack](https://github.com/cyberwolf6938/evil-twin-attack) | 1 | C++ | ESP8266 Evil Twin WiFi Attack Awareness Project (Educational Only) |
| 1274 | [cybrly/wifiscan](https://github.com/cybrly/wifiscan) | 1 | Rust | Wireless network scanner TUI with monitor mode, handshake capture, deauth, and evil twin |
| 1275 | [D1se0/DetectorAPFisico-Gadget-Hacking](https://github.com/D1se0/DetectorAPFisico-Gadget-Hacking) | 1 | C++ | Detector WiFi con ESP32 y pantalla táctil ILI9341: escanea redes, muestra señal en tiempo real y … |
| 1276 | [DaayZMA/wifiCrack](https://github.com/DaayZMA/wifiCrack) | 1 | Shell | Bash script for WiFi network penetration testing, enabling handshake capture and PMKID attacks to… |
| 1277 | [davidsalden/wifi-deauth-monitor](https://github.com/davidsalden/wifi-deauth-monitor) | 1 | C++ | Moniteur de réseau Wi-Fi pour ESP32 : il écoute le canal de votre box en mode promiscuous, détect… |
| 1278 | [deadblackclover/DSTIKE-SPACEHUHN-HackerWatch](https://github.com/deadblackclover/DSTIKE-SPACEHUHN-HackerWatch) | 1 | C++ | Watch for real hackers |
| 1279 | [DevHrefTry/deauther](https://github.com/DevHrefTry/deauther) | 1 | Shell | Wifi deauter in bash |
| 1280 | [Dhiraj60/esp8266_wifi_jammer](https://github.com/Dhiraj60/esp8266_wifi_jammer) | 1 | C++ |  |
| 1281 | [diptimannxc/dEAUTHER](https://github.com/diptimannxc/dEAUTHER) | 1 | C | a wifi (2.4 Gz and WPA2-personal) scanner and deauther using ESP32 S3 DevkitM (no psram), two NRF… |
| 1282 | [dkprasad-surati/wifi-deauther](https://github.com/dkprasad-surati/wifi-deauther) | 1 | C | wifi jam and wifi attack |
| 1283 | [drngominhtu/ESP32_Deauther-WifiKiller-](https://github.com/drngominhtu/ESP32_Deauther-WifiKiller-) | 1 | C++ |  |
| 1284 | [ec404-cool/wifi_deauther](https://github.com/ec404-cool/wifi_deauther) | 1 | Python |  |
| 1285 | [elansarialmahdi/Evil-Twin-Attack-PFA](https://github.com/elansarialmahdi/Evil-Twin-Attack-PFA) | 1 | HTML | Academic simulation of Evil Twin WiFi attack using EVE-NG, pfSense, Kali Linux and Ubuntu Server … |
| 1286 | [ellipsys/WIFIRock](https://github.com/ellipsys/WIFIRock) | 1 | Dockerfile | Container centered in all the common tools for pentesting wifi networks. |
| 1287 | [ELRame/Auditorias-Wifi](https://github.com/ELRame/Auditorias-Wifi) | 1 | — | Auditorias, reportes e informes sobre auditorias y pentests de redes wifi realizadas por mi. |
| 1288 | [ELSHAB7UAHED/ghost15](https://github.com/ELSHAB7UAHED/ghost15) | 1 | Shell | ESP32 WiFi Security Testing Tool - Advanced WiFi scanner and penetration testing tool for educati… |
| 1289 | [EmeshTheRipper/AI-WIFI-threat-detection-centre](https://github.com/EmeshTheRipper/AI-WIFI-threat-detection-centre) | 1 | Python | An AI-powered real-time security system that detects and mitigates wireless network threats using… |
| 1290 | [Esteban4-CRo/Crock](https://github.com/Esteban4-CRo/Crock) | 1 | C++ | Wifi Pentesting Tool |
| 1291 | [Falconmx1/WifiCannon](https://github.com/Falconmx1/WifiCannon) | 1 | Python | ⚡ Cross-platform WiFi attack framework. Crack WPA/WPA2, capture handshakes, Evil Twin, WPS pwn. W… |
| 1292 | [FarhanKhanKakar07/wifideauth](https://github.com/FarhanKhanKakar07/wifideauth) | 1 | — | This is the wifi deauth attack bin files in which you can jam a wifi in your esp32 s3 n16 r8 Mode… |
| 1293 | [ferm10n/docking-bay](https://github.com/ferm10n/docking-bay) | 1 | C++ | Control a IoT relay over WiFi with an esp8266, complete with status LEDs, OTA updates, and WiFi m… |
| 1294 | [Fhanafii/ESP32-Mirage](https://github.com/Fhanafii/ESP32-Mirage) | 1 | C++ | My custom ESP32 VROOM Evil twin to harvest wifi credentials |
| 1295 | [finnmagnuskverndalen/airpulse](https://github.com/finnmagnuskverndalen/airpulse) | 1 | C++ | WiFi packet intelligence — M5StickC standalone scanner with OS fingerprinting, deauth detection, … |
| 1296 | [firmware404/wifideauth](https://github.com/firmware404/wifideauth) | 1 | Python | Simple Wi-Fi Deauthentication Attack (wifi deauth) |
| 1297 | [flandreiii/Neux-Firmware-for-Esp32](https://github.com/flandreiii/Neux-Firmware-for-Esp32) | 1 | C++ | Turn any ESP32 into a pocket-sized wireless security scanner. WiFi/BLE recon, rogue AP detection,… |
| 1298 | [foundafreename/wifi-ids-c6](https://github.com/foundafreename/wifi-ids-c6) | 1 | C | Passive 2.4 GHz Wi-Fi intrusion detector for ESP32-C6 (Waveshare LCD 1.47): deauth floods, evil t… |
| 1299 | [gerbsec/WIFI-Pentesting](https://github.com/gerbsec/WIFI-Pentesting) | 1 | — |  |
| 1300 | [GlomarGadaffi/deauth-detector](https://github.com/GlomarGadaffi/deauth-detector) | 1 | C | distributed 802.11 attack detector with a LoRa back-haul. sensors flag deauth/flood/evil-twin/EAP… |
| 1301 | [grimh3xx/aircracking-win-x64](https://github.com/grimh3xx/aircracking-win-x64) | 1 | Python | TUI orchestrator for authorized Wi-Fi audits: WPA/WPA2 handshake capture and offline cracking via… |
| 1302 | [guzzt/wifi-pentest-framework](https://github.com/guzzt/wifi-pentest-framework) | 1 | Shell | Um simples bash script que possui alguns ataques a redes wifi |
| 1303 | [h4zel-sec/wifi-deauther-with-esp32](https://github.com/h4zel-sec/wifi-deauther-with-esp32) | 1 | C++ | Wi-Fi deauther using ESP32  |
| 1304 | [hachimamma/ESP8266-Wifi-Attacks](https://github.com/hachimamma/ESP8266-Wifi-Attacks) | 1 | C++ | Types of evil twin and deauth attacks from my side |
| 1305 | [hackermanzz/Wifi_Deauth_ESP32](https://github.com/hackermanzz/Wifi_Deauth_ESP32) | 1 | C++ |  |
| 1306 | [harshalbadgujar1053/wifi_deauthentication_attack_detector](https://github.com/harshalbadgujar1053/wifi_deauthentication_attack_detector) | 1 | C++ | ESP8266-based WiFi Deauthentication Attack Detector that monitors 802.11 management frames in pro… |
| 1307 | [heisnabil/WiChain-The-Wifi-Threat-Detector](https://github.com/heisnabil/WiChain-The-Wifi-Threat-Detector) | 1 | JavaScript | Decentralized real-time Wi-Fi threat detection & Evil Twin prevention engine combining cross-plat… |
| 1308 | [Hemansh-Varshney/wifi-evil-twin-detector](https://github.com/Hemansh-Varshney/wifi-evil-twin-detector) | 1 | HTML |  |
| 1309 | [hemapriyaperugu-hub/wifi-evil-twin-detection](https://github.com/hemapriyaperugu-hub/wifi-evil-twin-detection) | 1 | — |  |
| 1310 | [henriford/wifi_hunter](https://github.com/henriford/wifi_hunter) | 1 | C++ | WiFi Hunter |
| 1311 | [hex0gen1/wifi-deauth-detector](https://github.com/hex0gen1/wifi-deauth-detector) | 1 | C | esp32 project, that listening and analyzing network traffic to expose wifi attacks like deauth an… |
| 1312 | [Hexacon-labs/Portable_WiFi_Deauther](https://github.com/Hexacon-labs/Portable_WiFi_Deauther) | 1 | — |  |
| 1313 | [hoangvu161/ESP32-Penetration-wifi-firmware](https://github.com/hoangvu161/ESP32-Penetration-wifi-firmware) | 1 | — | Headless ESP32 Wi-Fi penetration tool with standalone Web UI, optimized for ESP32-WROOM/D0WD boards. |
| 1314 | [Hs2aH/EAPOL-4way-Handshake-Pkt-Sniffer](https://github.com/Hs2aH/EAPOL-4way-Handshake-Pkt-Sniffer) | 1 | C++ | This project sniffes the network traffic that transmits the WIFI-Password in your regualar commer… |
| 1315 | [hwac121/SniperCrack](https://github.com/hwac121/SniperCrack) | 1 | Shell | Wifi capture/cracking tool for educational purposes and pentesting |
| 1316 | [iarpan1/wifi_deauther_esp32](https://github.com/iarpan1/wifi_deauther_esp32) | 1 | — |  |
| 1317 | [ibrahimalakeel/wifi-pentesting](https://github.com/ibrahimalakeel/wifi-pentesting) | 1 | — |  |
| 1318 | [ImLilDev/Evil-Twin-Collection](https://github.com/ImLilDev/Evil-Twin-Collection) | 1 | CSS | A collection of a few Evil Portals made for WiFi Pineapple based on well-known French ISPs and more! |
| 1319 | [InitOneTeam/pentest-DockerWifi](https://github.com/InitOneTeam/pentest-DockerWifi) | 1 | — | This is project which aims to create a 'docker' which contains a lot of pentest wifi tools |
| 1320 | [ishindersingh/nodemcu_eviltwin](https://github.com/ishindersingh/nodemcu_eviltwin) | 1 | C++ | This project implements an "Evil Twin" WiFi access point using a NodeMCU (ESP8266) to create a ro… |
| 1321 | [itsHareeshx01/Cybersecurity-project](https://github.com/itsHareeshx01/Cybersecurity-project) | 1 | — | Wi-Fi-Deauther wifi network Second project by nikhil (Nikto on a local lab vm) and third project … |
| 1322 | [jaidanmaity/free-honey-wifi](https://github.com/jaidanmaity/free-honey-wifi) | 1 | Python | automating something like evil twin attack but creating a fake honey pot like wifi access point |
| 1323 | [jailideaid/DeautherV2](https://github.com/jailideaid/DeautherV2) | 1 | Python | Deauth tool script adaptor wifi usb |
| 1324 | [janelhuang28/Evil-Twin-Attack-with-Airgeddon](https://github.com/janelhuang28/Evil-Twin-Attack-with-Airgeddon) | 1 | — | Evil twin is similar to a social engineering attack that steals the WiFi password |
| 1325 | [JavierSiliacay/2.4GHz-5GHz-WiFi-deauther](https://github.com/JavierSiliacay/2.4GHz-5GHz-WiFi-deauther) | 1 | — | A full-featured 2.4GHz & 5GHz WiFi deauther with web-based controls, real-time scanning, multi-ta… |
| 1326 | [JavierSiliacay/WiFi-Bluetooth-Jammer-Project](https://github.com/JavierSiliacay/WiFi-Bluetooth-Jammer-Project) | 1 | — | A powerful 2.4GHz signal disruptor built with ESP32, capable of jamming wireless communication by… |
| 1327 | [jayzonesec-ops/crack-wifi-password](https://github.com/jayzonesec-ops/crack-wifi-password) | 1 | Shell | Ferramenta automatizada para captura de handshake WPA/WPA2 e quebra de senha WiFi com wordlists, … |
| 1328 | [JK-Tmux/Flipper-Zero-Evil-Portal-Guide](https://github.com/JK-Tmux/Flipper-Zero-Evil-Portal-Guide) | 1 | — | Educational captive portal experiment using HTML templates |
| 1329 | [Jonathan-0101/skeletonKey](https://github.com/Jonathan-0101/skeletonKey) | 1 | C | BEng Dissertation; Penetration-testing device to highlight security system vulnerabilities |
| 1330 | [JPJ-89/Fluxion-Spanish-Orange-Livebox-Router-Portal-Translation-Evil-Twin-Attack---WiFi-](https://github.com/JPJ-89/Fluxion-Spanish-Orange-Livebox-Router-Portal-Translation-Evil-Twin-Attack---WiFi-) | 1 | — | This Fluxion template functions as a cloned visual bait whose sole purpose is to deceive the user… |
| 1331 | [jR4dh3y/Pico32](https://github.com/jR4dh3y/Pico32) | 1 | C++ | A lightweight, serial-only TUI port of ESP32 Marauder. WiFi/BT testing tool for generic ESP32 mod… |
| 1332 | [juanga333/Netattack](https://github.com/juanga333/Netattack) | 1 | Python | A wifi pentesting tool using scapy |
| 1333 | [JustFernandezz/Wireless-Hacking](https://github.com/JustFernandezz/Wireless-Hacking) | 1 | PowerShell | Wireless deauther and wifi cloner |
| 1334 | [kamelisas/wifi-forensics-toolkit](https://github.com/kamelisas/wifi-forensics-toolkit) | 1 | Python | Kismet .netxml WiFi capture triage tool with rogue-AP/evil-twin detection |
| 1335 | [Kaniga-sri/ai-powered-evil-twin-wifi-detection-system](https://github.com/Kaniga-sri/ai-powered-evil-twin-wifi-detection-system) | 1 | — | AI-powered system for detecting suspicious Evil Twin Wi-Fi access points using real-time Wi-Fi an… |
| 1336 | [kapo-hacker/evil-twin-hack-wifi-kapo](https://github.com/kapo-hacker/evil-twin-hack-wifi-kapo) | 1 | — | I'm kapo. I'm making hacking tools and adjusting other tools to make them powerful. It's a tool s… |
| 1337 | [karthik9810/wifi-network-pentesting-tool](https://github.com/karthik9810/wifi-network-pentesting-tool) | 1 | Python | 📡 Advanced WiFi Network Pentesting Tool \| Port Scanner \| Device Scanner \| DNS Leak Test \| Fir… |
| 1338 | [karthik9810/wifi-ultimate-pentesting-tool-v5](https://github.com/karthik9810/wifi-ultimate-pentesting-tool-v5) | 1 | Python | 📡 Ultimate WiFi Pentesting Tool v5.0 \| 20 Features \| AI Threat Analysis \| Deep Port Scanner \|… |
| 1339 | [Kashyap2way/Humming-Beta](https://github.com/Kashyap2way/Humming-Beta) | 1 | JavaScript | A wifi hacker app which works on .cap file of any network handshake then uses brute force and pas… |
| 1340 | [Kaushalsuvarna/bw16_deauther_v1.0.0_cli_only](https://github.com/Kaushalsuvarna/bw16_deauther_v1.0.0_cli_only) | 1 | C++ | Dual-band (2.4 + 5 GHz) WiFi deauther for the Realtek RTL8720DN (BW16), driven entirely via seria… |
| 1341 | [Kevin2901/wifi-defense-system-esp32](https://github.com/Kevin2901/wifi-defense-system-esp32) | 1 | HTML | Secure your WiFi from De-auth attacks, and monitor for anomalies and IP sniffing with ESP 32 hard… |
| 1342 | [khwaabchawla28/Esp-32-evil-twin](https://github.com/khwaabchawla28/Esp-32-evil-twin) | 1 | C | ESP32 WiFi security research tool -- evil twin + captive portal for IoT coursework |
| 1343 | [kiboiesther/WiFi-Scanner](https://github.com/kiboiesther/WiFi-Scanner) | 1 | HTML | WiFi scanner for evil twin attacks |
| 1344 | [kilam994/CryFi](https://github.com/kilam994/CryFi) | 1 | Python | A local web dashboard for the aircrack-ng suite - scan, capture handshakes, crack, and generate w… |
| 1345 | [KiltzX/Wifi-Deauth-Python](https://github.com/KiltzX/Wifi-Deauth-Python) | 1 | Python | Wifi deauther using aireplay and airodump |
| 1346 | [Kingisline/deauther-Wifi-jammer-esp8266-](https://github.com/Kingisline/deauther-Wifi-jammer-esp8266-) | 1 | — |  |
| 1347 | [KONERI-VISHNU/Wireless-Network-Security-Assessment](https://github.com/KONERI-VISHNU/Wireless-Network-Security-Assessment) | 1 | — | A practical wireless security lab project demonstrating WiFi penetration testing techniques such … |
| 1348 | [Landull/wifiscan](https://github.com/Landull/wifiscan) | 1 | Python | Lists nearby Wi-Fi networks and flags open, WEP, WPA/TKIP and possible evil-twin access points. P… |
| 1349 | [Luck-One9/rasputian-deauther](https://github.com/Luck-One9/rasputian-deauther) | 1 | C++ | Modular Wi-Fi security research firmware with clean architecture and event-driven design. |
| 1350 | [mad0xStrixhadorami/esp32-wifi-security-lab](https://github.com/mad0xStrixhadorami/esp32-wifi-security-lab) | 1 | C | ESP32 evil-twin captive-portal demo for teaching WiFi credential-harvesting risk (lab use only) |
| 1351 | [mandoof1/WiFi-Pentest-Assistant-Script](https://github.com/mandoof1/WiFi-Pentest-Assistant-Script) | 1 | Shell | Menu-driven Bash assistant for authorized WiFi security testing — monitor mode, airodump scanning… |
| 1352 | [marcucarapangea-cloud/ESP32-WiFi-BLE-Penetration-Tool](https://github.com/marcucarapangea-cloud/ESP32-WiFi-BLE-Penetration-Tool) | 1 | — | WiFi Deauth + BLE Spoofing tool for ESP32 DevKit with OLED 0.96 display (SSD1306 I2C) |
| 1353 | [MarkTH191/Esp32-WiFi-Jammer](https://github.com/MarkTH191/Esp32-WiFi-Jammer) | 1 | — | Esp-32 WiFi Jammer 2.4ghz |
| 1354 | [Martinxploit/NodeMCU-8266-WiFI-Evil-Jammer-Xploit](https://github.com/Martinxploit/NodeMCU-8266-WiFI-Evil-Jammer-Xploit) | 1 | — | Deauth attack to disconnect devices from WiFi Evil Twin AP to capture passwords No toggling - bot… |
| 1355 | [MateoQuinteroH/Open-Jammer-V1.0](https://github.com/MateoQuinteroH/Open-Jammer-V1.0) | 1 | — | This project is an ESP32 based WiFi/Bluetooth jammer device. |
| 1356 | [Mehflexx17/ESP5-WarBox-ESP32-](https://github.com/Mehflexx17/ESP5-WarBox-ESP32-) | 1 | — | ESP32-based RF security research tool with WiFi deauth, BLE flood, 2.4GHz spectrum analyzer, and … |
| 1357 | [mehraniqbalgp/esp8266_deauther](https://github.com/mehraniqbalgp/esp8266_deauther) | 1 | C | ESP8266 Wi-Fi Deauther v3.0 — WiFi security testing toolkit with deauth, beacon flood, probe atta… |
| 1358 | [mitthu786/wifijam](https://github.com/mitthu786/wifijam) | 1 | Shell | pentest toolkit whose goal is to perform jam on WiFi clients/routers and spam many fake AP for te… |
| 1359 | [Mizu-Tech/mizu-tech-esp32-ble-jammer-wifi-deauther](https://github.com/Mizu-Tech/mizu-tech-esp32-ble-jammer-wifi-deauther) | 1 | — |  |
| 1360 | [Mizu-Tech/mizu-tech-esp32-wifi-deauther](https://github.com/Mizu-Tech/mizu-tech-esp32-wifi-deauther) | 1 | — |  |
| 1361 | [mogtderi/ESP32-WiFi-Resilience-Research](https://github.com/mogtderi/ESP32-WiFi-Resilience-Research) | 1 | C++ | Experimental research framework evaluating wireless network resilience against 802.11 frame injec… |
| 1362 | [mohammadajani/Beacongotchi](https://github.com/mohammadajani/Beacongotchi) | 1 | Python | Wireless Security Awareness Platform - Custom ESP32-S3 / BW16 FirmwareBuilt a multi-board WiFi/BL… |
| 1363 | [mohdsaqibqamar/ESP8266-WiFi-Hacking-Bad-Cat-](https://github.com/mohdsaqibqamar/ESP8266-WiFi-Hacking-Bad-Cat-) | 1 | C++ | Blue Cat is a very powerful wifi hacking tool  |
| 1364 | [monescuteodor/Blocky-OS-v7.6](https://github.com/monescuteodor/Blocky-OS-v7.6) | 1 | C++ | WiFi security testing suite for ESP8266 and ST7735 display. Device based on ESP8266 for testing n… |
| 1365 | [MR-ABID07/BW16_5G-WIFI_DEAUTHER](https://github.com/MR-ABID07/BW16_5G-WIFI_DEAUTHER) | 1 | C++ |  |
| 1366 | [Mr-Beta-Version/WIFI-PENTEST](https://github.com/Mr-Beta-Version/WIFI-PENTEST) | 1 | C | Wifi Penetration Testing Tools |
| 1367 | [MRGcodex/WipanFi](https://github.com/MRGcodex/WipanFi) | 1 | Python | An advanced Linux WiFi auditing toolkit by MRGcodex. Features auto monitor mode, PMKID & Handshak… |
| 1368 | [ms604/wifi-pentest-tool](https://github.com/ms604/wifi-pentest-tool) | 1 | Python | Wi-Fi pentesting tool with deauth, handshake capture, and cracking features |
| 1369 | [Muneer461/WiFi-Deauthentication-Detection-using-ESP8266](https://github.com/Muneer461/WiFi-Deauthentication-Detection-using-ESP8266) | 1 | C++ |  |
| 1370 | [mw-darksword/Wifi-Pentest](https://github.com/mw-darksword/Wifi-Pentest) | 1 | Python | Automated Wi-Fi penetration testing tool using Aircrack-ng suite. Detects wireless adapters, capt… |
| 1371 | [N4P1x/YoRHa-Deauther](https://github.com/N4P1x/YoRHa-Deauther) | 1 | C++ | YoRHa Deauther is an ESP32-based Wi-Fi deauthentication tool that floods target access points wit… |
| 1372 | [NETERBIL/Cracking-WiFi-WPA2-Handshake](https://github.com/NETERBIL/Cracking-WiFi-WPA2-Handshake) | 1 | — |  |
| 1373 | [netvader/cyd-guard](https://github.com/netvader/cyd-guard) | 1 | C++ | Passive WiFi deauth + BLE jam detector for the CYD (ESP32-2432S024R) |
| 1374 | [night0x1/Learning-C-via-ESP32-](https://github.com/night0x1/Learning-C-via-ESP32-) | 1 | — | I will learn how to code in c and programming esp32 for any cyber security projects that will hel… |
| 1375 | [Nimpo714/WifiDeauther](https://github.com/Nimpo714/WifiDeauther) | 1 | Python | Скрипт для отключения всех устройств от Wifi (скрипт проверен на Arch Linux) |
| 1376 | [noushad27/Dog_Trail](https://github.com/noushad27/Dog_Trail) | 1 | Python | 🐾 Your WiFi's guard dog. Detects evil twin attacks & rogue access points — then explains it in pl… |
| 1377 | [OblivionDH/oblivion-wifi-auditor](https://github.com/OblivionDH/oblivion-wifi-auditor) | 1 | Python | Modular WiFi security auditing toolkit in Python: scan networks, test WPA/WPA2, capture handshake… |
| 1378 | [ohyoxo/wifi-adapter-tool](https://github.com/ohyoxo/wifi-adapter-tool) | 1 | Shell | AI-enhanced Wi-Fi adapter tool for ethical pentesting. |
| 1379 | [Omchireddy/wifi-evil-twin-detector](https://github.com/Omchireddy/wifi-evil-twin-detector) | 1 | Python | Evil Twin Wi-Fi Detector is a lightweight command-line tool designed to detect potential Evil Twi… |
| 1380 | [OsteenK/netcheck](https://github.com/OsteenK/netcheck) | 1 | Shell | Network diagnostic & security scanner for Linux. Single Bash script — WiFi analysis, evil twin de… |
| 1381 | [overlinderosier0-afk/DJA-SCAN](https://github.com/overlinderosier0-afk/DJA-SCAN) | 1 | C++ | Outil de reconnaissance WiFi/Bluetooth passif sur ESP32 (OLED + joystick) - scan, detection deaut… |
| 1382 | [owlsecx/OKarma](https://github.com/owlsecx/OKarma) | 1 | Go | OKarma: Evil-Twin/KARMA Analyzer |
| 1383 | [oycillessen/ETD-Bire](https://github.com/oycillessen/ETD-Bire) | 1 | Python | This program is used for evil twin attackes detection. |
| 1384 | [PARIKAKUGOD1/WIFI-Deauther](https://github.com/PARIKAKUGOD1/WIFI-Deauther) | 1 | Python | WIFI-Deauther – A Python-based tool for performing WiFi deauthentication attacks using aircrack-n… |
| 1385 | [parzival123-gan/esp32-wifi-ble-scanner](https://github.com/parzival123-gan/esp32-wifi-ble-scanner) | 1 | — | A lightweight RF scanner built with ESP32 that detects nearby Wi-Fi and Bluetooth Low Energy devi… |
| 1386 | [paumnoz/WifiHackingStuff](https://github.com/paumnoz/WifiHackingStuff) | 1 | Python | a set of tools and scripts used for pentesting wifi networks |
| 1387 | [pcabdou37-collab/DMT-CyberFang-Ultimate-Security-Tool-](https://github.com/pcabdou37-collab/DMT-CyberFang-Ultimate-Security-Tool-) | 1 | C++ | DMT-CyberFang جهاز أمن سيبراني محمول يجمع بين Dr Password لحفظ وتشفير 50 تطبيقاً وموقعاً، وDr Hac… |
| 1388 | [philiWeitz/wifiSniffer](https://github.com/philiWeitz/wifiSniffer) | 1 | C |  |
| 1389 | [PhoniexCoder/wifi-pentest-tool](https://github.com/PhoniexCoder/wifi-pentest-tool) | 1 | Python | A Python-based WiFi penetration testing tool that automates various security assessments like net… |
| 1390 | [Phunkafizer/RFM-gateway](https://github.com/Phunkafizer/RFM-gateway) | 1 | C++ | Hard- and software for the RFM-gateway, a universal platform for integrating sub-GHz radio into y… |
| 1391 | [Physostegiadragee5952/valorant-esp-items-2026](https://github.com/Physostegiadragee5952/valorant-esp-items-2026) | 1 | — | See dropped weapons, spike, abilities, and enemy economy through walls with real-time Valorant it… |
| 1392 | [PigManul/megaware](https://github.com/PigManul/megaware) | 1 | C++ | Firmware for LilyGo T-Embed CC1101 (ESP32-S3) with Wi-Fi, Sub-GHz, NFC, and Lua/JS scripting |
| 1393 | [piratos/Wifi-Jammer](https://github.com/piratos/Wifi-Jammer) | 1 | C | wifi jammer on esp8266 |
| 1394 | [pklosko/WiFiMulti](https://github.com/pklosko/WiFiMulti) | 1 | C++ | Arduino esp32 WiFiMulti fork - Hidden SSID hack |
| 1395 | [Prajwalpawar1/deauther](https://github.com/Prajwalpawar1/deauther) | 1 | Python | it is the deauther code  which use to program nodemcu  or esp8266 to perform  wifi  jaming attack   |
| 1396 | [Pranav-V-20/WiFi_Deauther_ESP8266](https://github.com/Pranav-V-20/WiFi_Deauther_ESP8266) | 1 | C | A compact and powerful tool built using an ESP8266 microcontroller to perform WiFi deauthenticati… |
| 1397 | [PratyushMishra-pro/ESP8266_deauther](https://github.com/PratyushMishra-pro/ESP8266_deauther) | 1 | — | ESP8266_deauther/FUNDING.yml |
| 1398 | [PrestoDL/Project_ESP32Controller](https://github.com/PrestoDL/Project_ESP32Controller) | 1 | C | Project about esp32 controller, using wifi and ble. hacking research also |
| 1399 | [ProgramingFactory/SignalStrength](https://github.com/ProgramingFactory/SignalStrength) | 1 | C# | WiFi-SignalStrength app for tracking signal strength; WiFi-Sniffer; |
| 1400 | [pUrGe12/Wi-Fi-Bunny](https://github.com/pUrGe12/Wi-Fi-Bunny) | 1 | CMake | A Wifi-deauth + evil twin framework for ESP32 and ESP8266 |
| 1401 | [R-S-Nithesh/Aircrack-Mcp](https://github.com/R-S-Nithesh/Aircrack-Mcp) | 1 | Python | MCP server that wraps aircrack-ng, enabling AI assistants to run and automate WiFi security asses… |
| 1402 | [R00TV3X/WiFi-Deauth-EvilTwin](https://github.com/R00TV3X/WiFi-Deauth-EvilTwin) | 1 | C++ | An educational project using NodeMCU (ESP8266) to simulate WiFi Deauthentication and Evil Twin at… |
| 1403 | [rafaelharzer/Guia_Pentest_WiFi_PT_BR](https://github.com/rafaelharzer/Guia_Pentest_WiFi_PT_BR) | 1 | — | Um guia pratico para auxiliar meus colegas profissionais da área a realizar um Pentest em redes W… |
| 1404 | [RafeKhen/NetSuck-esp8266](https://github.com/RafeKhen/NetSuck-esp8266) | 1 | — | Advanced WiFi attack and audit firmware with deauth, beacon spam, evil twin, and packet sniffing. |
| 1405 | [rahimmahamane/wifi-app](https://github.com/rahimmahamane/wifi-app) | 1 | Python | Pentest pour wifi a titre éducatif . |
| 1406 | [Rain26t/Bluetooth-Wifi-RC-RF-Jammer-using-ESP32-and-NRF24L01](https://github.com/Rain26t/Bluetooth-Wifi-RC-RF-Jammer-using-ESP32-and-NRF24L01) | 1 | C++ |  |
| 1407 | [RajeshSagar2912/wifi-testing](https://github.com/RajeshSagar2912/wifi-testing) | 1 | — | This repo will contains all my wifi pentesting useful commands |
| 1408 | [RANAJIIIII/Wifi-Broot](https://github.com/RANAJIIIII/Wifi-Broot) | 1 | Python | Crack WPA/WPA2 passwords using brute-force attacks. Supports handshake capture and crack, PMKID c… |
| 1409 | [Raunaksplanet/WiFi-Security-Pentesting-Learning-Notes](https://github.com/Raunaksplanet/WiFi-Security-Pentesting-Learning-Notes) | 1 | — | Personal documentation of my WiFi security research |
| 1410 | [ravdahuzaif88-hub/2.4GHz-Wireless-Security-Analysis-System](https://github.com/ravdahuzaif88-hub/2.4GHz-Wireless-Security-Analysis-System) | 1 | C++ | ESP32-based wireless security toolkit for 2.4GHz spectrum analysis, BLE spoofing and Wi-Fi deauth… |
| 1411 | [Rayenthestrongest/wifi-spectre-mcp](https://github.com/Rayenthestrongest/wifi-spectre-mcp) | 1 | HTML | Aircrack-MCP WiFi Pentesting Suite Automated 2026 |
| 1412 | [razannnnnn/ESP8266-Weather-Clock](https://github.com/razannnnnn/ESP8266-Weather-Clock) | 1 | C | Jam digital berbasis ESP8266 dengan display OLED 128x64, data cuaca real-time dari OpenWeatherMap… |
| 1413 | [Rexturnull/WiFi-PenTest](https://github.com/Rexturnull/WiFi-PenTest) | 1 | — | WiFi-PenetrationTest |
| 1414 | [rezaul1773/Wifi-penetesting-with-password-cracking](https://github.com/rezaul1773/Wifi-penetesting-with-password-cracking) | 1 | — | Here is demo wifi pentesting and password cracking. If want pentest your network don't hesitate t… |
| 1415 | [rfypych/ble-wifi-jammer-esp32](https://github.com/rfypych/ble-wifi-jammer-esp32) | 1 | C++ |  |
| 1416 | [Rhaine2008/WIfi---Bluetooth-Jammer](https://github.com/Rhaine2008/WIfi---Bluetooth-Jammer) | 1 | C++ | This project explores wireless communication, radio-frequency interference, and network security … |
| 1417 | [rickmatthewgerale3fb-cmd/Esp8266-signal-jammer-BLE-Bluetooth-and-Wifi](https://github.com/rickmatthewgerale3fb-cmd/Esp8266-signal-jammer-BLE-Bluetooth-and-Wifi) | 1 | C++ | A esp8266 optional screenless jammer with ONLY 2 supported nrf24's. Code mostly from gemini |
| 1418 | [ridhinva/pocket-s](https://github.com/ridhinva/pocket-s) | 1 | C | Toolkit: Pocket-S: Open-source ESP32-S3 multi-tool alternative to Flipper Zero — Sub-1GHz, NFC, R… |
| 1419 | [rizkyngrh23/wifi-cracking-with-aircrack](https://github.com/rizkyngrh23/wifi-cracking-with-aircrack) | 1 | — | This repository provides a comprehensive guide and scripts for cracking WPA/WPA2 WiFi passwords u… |
| 1420 | [Rohan131293/tinyWiFiHacker](https://github.com/Rohan131293/tinyWiFiHacker) | 1 | — | ESP8266 based WiFi Attacks |
| 1421 | [rohitcs1/ESP8266-WiFi-Security-Research](https://github.com/rohitcs1/ESP8266-WiFi-Security-Research) | 1 | C++ | This project uses the ESP8266 (NodeMCU) for WiFi security research and testing. It demonstrates c… |
| 1422 | [ronnymboumba1-maker/J4thniel_Evil_twin](https://github.com/ronnymboumba1-maker/J4thniel_Evil_twin) | 1 | Python | EVIL TWIN ULTIME est un outil de test de sécurité WiFi qui simule une attaque Evil Twin. Il perme… |
| 1423 | [roycuadra/WiFi-Jamming-Detector](https://github.com/roycuadra/WiFi-Jamming-Detector) | 1 | C++ | This project use a NodeMCU esp8266 It scans specific WiFi channels for deauth packets, When an at… |
| 1424 | [ryvoxo/nRF-jammer](https://github.com/ryvoxo/nRF-jammer) | 1 | C++ | A Bluetooth and a WIFIA jammer using the ESP32 and two NRF24L01s. |
| 1425 | [s3al4er/wifi-deauther](https://github.com/s3al4er/wifi-deauther) | 1 | Python |  |
| 1426 | [sachintha82288-cpu/WiFi-Evil-Twin](https://github.com/sachintha82288-cpu/WiFi-Evil-Twin) | 1 | Python | Can be used to perform Evil Twin attacks for WiFi testing. |
| 1427 | [saherkhizr123/wifi_evil_twin_detector](https://github.com/saherkhizr123/wifi_evil_twin_detector) | 1 | — | Detect fake wifi network that mimic real ones . Ethical hacking tool for awareness |
| 1428 | [Salvatore-droid/web-interface-wifi-deauther](https://github.com/Salvatore-droid/web-interface-wifi-deauther) | 1 | HTML |  |
| 1429 | [Sandeep3062/wifi-handshake-capture-and-crack-demo](https://github.com/Sandeep3062/wifi-handshake-capture-and-crack-demo) | 1 | — | "Educational project demonstrating Wi-Fi handshake capture and cracking using Aircrack-ng and Kal… |
| 1430 | [Sanjeewa-Karunarathna/Wifi_Pentest_Automation_Scripts](https://github.com/Sanjeewa-Karunarathna/Wifi_Pentest_Automation_Scripts) | 1 | Python |  |
| 1431 | [saranb565/EthicalHacking](https://github.com/saranb565/EthicalHacking) | 1 | — | Doc with commands and screenshots of Hacking Tasks involving WiFi - Password Cracking, Evil Twin … |
| 1432 | [sariftachamo-cybersec/wifidisrupt-esp32-deauth-lab](https://github.com/sariftachamo-cybersec/wifidisrupt-esp32-deauth-lab) | 1 | Python | A hardware based projects that can be used to disconnect the wifi by sending the deauth packets u… |
| 1433 | [saxflx/Esp32-EvilTwinWifiSifresi-EvilTwin-Instagram-WifiDoS-WifiSpam-Turkce](https://github.com/saxflx/Esp32-EvilTwinWifiSifresi-EvilTwin-Instagram-WifiDoS-WifiSpam-Turkce) | 1 | C++ |  |
| 1434 | [schemil053/ESP8266ProbeCounter](https://github.com/schemil053/ESP8266ProbeCounter) | 1 | C++ | A simple wifi-probe sniffer for ESP8266 to count devices in a room. |
| 1435 | [SecuredByKC/wifi-deauth-attack-red](https://github.com/SecuredByKC/wifi-deauth-attack-red) | 1 | — | My hands-on WPA2 handshake capture and cracking using deauthentication attacks on Kali Linux. Inc… |
| 1436 | [seva009/WiFi-jammer](https://github.com/seva009/WiFi-jammer) | 1 | C++ | А это уже не deauther :) |
| 1437 | [Shad0w-X/ESP8266_Deauther](https://github.com/Shad0w-X/ESP8266_Deauther) | 1 | — | Wifi Deauther for ESP8266 chips |
| 1438 | [SharadS28N/Netguard](https://github.com/SharadS28N/Netguard) | 1 | TypeScript | NetGuard Nepal detects and neutralizes evil twin WiFi networks in real-time. Enterprise-grade sec… |
| 1439 | [shark551151/Wifi-Deauthentication-Password-Capture-Evil-Twin-and-Other-Attacks-Ddos-Attack-Station-sniffing](https://github.com/shark551151/Wifi-Deauthentication-Password-Capture-Evil-Twin-and-Other-Attacks-Ddos-Attack-Station-sniffing) | 1 | Python | Buy Dual-Band (5 GHz and 2.4 GHz) RTL8720DN WiFi Deauther or Jammer device from - https://hacksho… |
| 1440 | [shasradha/epoch](https://github.com/shasradha/epoch) | 1 | — | Retro Gameboy-inspired handheld featuring 20+ games and a dual-firmware ESP8266 WiFi pentesting p… |
| 1441 | [shehanweersing/ESP8266-WiFi-Deauther](https://github.com/shehanweersing/ESP8266-WiFi-Deauther) | 1 | — |  |
| 1442 | [Sid214/ESP32_RFID_Wifi_Jammer](https://github.com/Sid214/ESP32_RFID_Wifi_Jammer) | 1 | C++ | A hardware-integrated Wi-Fi security auditor for ESP32 featuring an RFID physical access lock (MF… |
| 1443 | [Sid23-oss/grid_attacking](https://github.com/Sid23-oss/grid_attacking) | 1 | Python | grid_attacking is a cybersecurity mini SCADA system. An ESP32 substation (ZMPT and ACS712 sensors… |
| 1444 | [siddhu2004bhagat/Esp32-2.4GHz-Ble-WiFi-jammer](https://github.com/siddhu2004bhagat/Esp32-2.4GHz-Ble-WiFi-jammer) | 1 | — |  |
| 1445 | [sidharth-v-s/Wifi-Evil-Twin](https://github.com/sidharth-v-s/Wifi-Evil-Twin) | 1 | Python |  |
| 1446 | [sifatnotes/secbyte-wifi-security-wpa2-wpa3-rogue-ap-embedded-iot-ctf-labs](https://github.com/sifatnotes/secbyte-wifi-security-wpa2-wpa3-rogue-ap-embedded-iot-ctf-labs) | 1 | — | A practical collection of cybersecurity CTF labs covering wireless network security (Wi-Fi fundam… |
| 1447 | [silverbulletex0-debug/All-Wifi-Jacking-](https://github.com/silverbulletex0-debug/All-Wifi-Jacking-) | 1 | Shell | Advanced wireless security auditing framework featuring persistent scanning, automated deauth att… |
| 1448 | [SleepTheGod/LinuxNetworkPentesting](https://github.com/SleepTheGod/LinuxNetworkPentesting) | 1 | Python | A gui for linux wifi network penetration testing |
| 1449 | [SleepTheGod/Wifi-Pentesting](https://github.com/SleepTheGod/Wifi-Pentesting) | 1 | — | How to hack wifi and log it |
| 1450 | [sm2218157-creator/Netprobe](https://github.com/sm2218157-creator/Netprobe) | 1 | Shell | NetProbe - Android Security Toolkit: network scanner, WiFi pentesting, ESP32 control, OSINT tools… |
| 1451 | [sobri3195/pegasus-wifi-sobri](https://github.com/sobri3195/pegasus-wifi-sobri) | 1 | — | a tool designed for various WiFi network operations such as scanning networks, capturing handshak… |
| 1452 | [SODAVK/BW16-CTS-SLEEP](https://github.com/SODAVK/BW16-CTS-SLEEP) | 1 | C++ | CTS and Sleep frame attack use BW16 (RTL8720DN) board |
| 1453 | [SODAVK/BW16-SmartDeauther](https://github.com/SODAVK/BW16-SmartDeauther) | 1 | C++ | Deauth networks using BW16 (RTL8720DN). Deauth+Dissoc+CTS. Using Serial Terminal for communicate |
| 1454 | [stefaslsfij/Deauther.Wifi](https://github.com/stefaslsfij/Deauther.Wifi) | 1 | Python |  |
| 1455 | [steve3301/wifi-evil-twin-lab](https://github.com/steve3301/wifi-evil-twin-lab) | 1 | — | Educational Wi-Fi Evil Twin & deauthentication lab with offensive simulation and defensive detect… |
| 1456 | [sulthanbathusha852-commits/AI-Based-Wifi-Evil-Twin-Detection-System](https://github.com/sulthanbathusha852-commits/AI-Based-Wifi-Evil-Twin-Detection-System) | 1 | HTML |  |
| 1457 | [SupCom-Cyber-Security/Wifi-Pentest-Workshop-25-26](https://github.com/SupCom-Cyber-Security/Wifi-Pentest-Workshop-25-26) | 1 | HTML |  |
| 1458 | [suvo2007/Nrfboom_Btl](https://github.com/suvo2007/Nrfboom_Btl) | 1 | — | NRF BOOM — an ESP32-based multi-tool for nRF24, BLE, and WiFi security testing (scanner, jammer, … |
| 1459 | [taleofthelion/esp32-FakeGotchi](https://github.com/taleofthelion/esp32-FakeGotchi) | 1 | — | esp32-FakeGotchi - Oled Nice Kitty that start jamming WiFi Strongest Network around u |
| 1460 | [Tanzeel0Hussain/ESP8266-PhiSiFi-Pro](https://github.com/Tanzeel0Hussain/ESP8266-PhiSiFi-Pro) | 1 | C++ | A professional WiFi security testing tool for ESP8266 featuring an automated Evil Twin phishing p… |
| 1461 | [tech-nickk/ESP32Dragonfly](https://github.com/tech-nickk/ESP32Dragonfly) | 1 | C++ | WIFI and bluetooth pentesting tool |
| 1462 | [Technicalaccent/wifi-deauther-mini-esp8266-arduino-wifi](https://github.com/Technicalaccent/wifi-deauther-mini-esp8266-arduino-wifi) | 1 | — | Android app |
| 1463 | [the-hollowclan/Sneak-Into-Wifi](https://github.com/the-hollowclan/Sneak-Into-Wifi) | 1 | CSS | An AP setup utility, with captive portal to perform a controlled Evil-Twin. Use this responsibly |
| 1464 | [thund3rb0lt0x1/wifi-pentesting-notes](https://github.com/thund3rb0lt0x1/wifi-pentesting-notes) | 1 | — | A comprehensive reference guide for WiFi penetration testing and OSWP (PEN-210) exam preparation. |
| 1465 | [TM-Mehrab-Hasan/Iot-based-secure-wifi-deauthering-system](https://github.com/TM-Mehrab-Hasan/Iot-based-secure-wifi-deauthering-system) | 1 | C |  |
| 1466 | [tmvwin/WIFI--PENTESTING-ADDED-Cyber-security-with-AI-VI](https://github.com/tmvwin/WIFI--PENTESTING-ADDED-Cyber-security-with-AI-VI) | 1 | Python | 8TH module with voice assissents  + AI  |
| 1467 | [ToraGaming/wifi-pentest-lab](https://github.com/ToraGaming/wifi-pentest-lab) | 1 | Shell | 📡 Wi-Fi 6 pentesting lab: Alfa AWUS036AXML (MT7921U) on Kali for WPA3/SAE Dragonblood analysis |
| 1468 | [toutpuissantged/hacktools-cpp](https://github.com/toutpuissantged/hacktools-cpp) | 1 | C++ | wifi pentest tools can exploit free trial vulnerability  |
| 1469 | [tr4m0ryp/iot-evil-twin-lab](https://github.com/tr4m0ryp/iot-evil-twin-lab) | 1 | C++ | IoT evil-twin WiFi attack + defense lab (personal-network security education) |
| 1470 | [uchihaluckycs/IAITC](https://github.com/uchihaluckycs/IAITC) | 1 | C++ | Final Year Project - WiFi Disassociation and Deauthentication Attacks using NodeMCU ESP8266 |
| 1471 | [unlucky666god/ESP32-WiFi-deauther](https://github.com/unlucky666god/ESP32-WiFi-deauther) | 1 | C++ |  |
| 1472 | [unrealistic-reality/wifi-wordlists](https://github.com/unrealistic-reality/wifi-wordlists) | 1 | — | A Philippine based wordlist for cracking wifi passwords captured from handshakes. |
| 1473 | [uriel5523L/ESP32-Deauther-App](https://github.com/uriel5523L/ESP32-Deauther-App) | 1 | C++ | ESP32-Deauther app movil (WiFi/BLE) con login |
| 1474 | [Usernameaisnoavailable/Hecker](https://github.com/Usernameaisnoavailable/Hecker) | 1 | — | An ESP32-based multi-tool for WiFi and BLE pentesting, themed around the "Hecker" cat meme. heres… |
| 1475 | [usersdsa/wifi](https://github.com/usersdsa/wifi) | 1 | — | Wifi deauther layther |
| 1476 | [v-aryank/NRF_Box-WiFi_Bluetooth_Deauther](https://github.com/v-aryank/NRF_Box-WiFi_Bluetooth_Deauther) | 1 | — |  |
| 1477 | [vampel/ESP32-BlueJammer](https://github.com/vampel/ESP32-BlueJammer) | 1 | — | BT Jammer Wifi RC 2.4Ghz |
| 1478 | [victor22-te/wifi_pentest](https://github.com/victor22-te/wifi_pentest) | 1 | — | prueba de Hacking ético de wifi |
| 1479 | [vikrantbasak15-lgtm/esp32-wifi-projects](https://github.com/vikrantbasak15-lgtm/esp32-wifi-projects) | 1 | C++ | ESP32 & Arduino IoT projects by a 13 y/o maker. WiFi-controlled builds, sensors, automation hacks… |
| 1480 | [VishnuPrasanth-A/GC---GameChanger-Wifi-Tester](https://github.com/VishnuPrasanth-A/GC---GameChanger-Wifi-Tester) | 1 | C++ | The GC- Toolkit (Game Changer) is an advanced, self-contained Wi-Fi penetration testing and netwo… |
| 1481 | [vperron/snow](https://github.com/vperron/snow) | 1 | C | WiFi packets sniffer |
| 1482 | [vswanagan/flock-you-also](https://github.com/vswanagan/flock-you-also) | 1 | — | ESP32-S3 firmware that emulates Flock Safety surveillance devices (FS Ext Battery, WiFi AP, Raven… |
| 1483 | [vxnuprasad/EVIL-RAB-v2.0---ESP32-Evil-Twin-WiFi-Attack-Device](https://github.com/vxnuprasad/EVIL-RAB-v2.0---ESP32-Evil-Twin-WiFi-Attack-Device) | 1 | — | An ESP32-based evil twin WiFi attack device with 0.96 inch OLED display support (4-pin and 7-pin … |
| 1484 | [W0rKiska/wlab](https://github.com/W0rKiska/wlab) | 1 | Shell | WLAB — лабораторный набор для Wi-Fi / BLE / OSINT: скан, деаут, хендшейк, PMKID, evil twin, BLE-с… |
| 1485 | [WarGod5o5/Arduino-WiFi-Deauther-Detector](https://github.com/WarGod5o5/Arduino-WiFi-Deauther-Detector) | 1 | C++ |  |
| 1486 | [willlccasey/kali-wifi-pentest-kit](https://github.com/willlccasey/kali-wifi-pentest-kit) | 1 | Python | WiFi Pentest Kit GUI — scanner, deauth, evil twin, beacon spam, handshake capture |
| 1487 | [winzter143/esp2866_wifi](https://github.com/winzter143/esp2866_wifi) | 1 | C++ | This app is custom version of  https://github.com/spacehuhn/esp8266_deauther |
| 1488 | [xiv3r/handshake-bruteforce](https://github.com/xiv3r/handshake-bruteforce) | 1 | — | bruteforce the 4 way wifi handshake using air-crack via github action workflow |
| 1489 | [YanivHaliwa/WifiSec](https://github.com/YanivHaliwa/WifiSec) | 1 | Shell | WiFi auditing toolkit with multi-target capture, PMKID/deauth dual-path attacks, handshake triple… |
| 1490 | [ymvnby-alt/ESP32MotiondetectionWIP](https://github.com/ymvnby-alt/ESP32MotiondetectionWIP) | 1 | C++ | WiFi CSI + BLE motion detection using an ESP32 and a Qt6 desktop app. Sniffs channel state varian… |
| 1491 | [YoungRyx/ESP-32-wifi-deauther-](https://github.com/YoungRyx/ESP-32-wifi-deauther-) | 1 | — | This is ESP-32 wifi deuather, using for disconnect all the device that connecting to the wifi rou… |
| 1492 | [ysfhmtky/ESP32-Wifi-Deauther](https://github.com/ysfhmtky/ESP32-Wifi-Deauther) | 1 | C |  |
| 1493 | [zabszk/ESP8266-WiFi-Deauther](https://github.com/zabszk/ESP8266-WiFi-Deauther) | 1 | C++ | Project at AGH University of Science and Technology.  |
| 1494 | [zadkiel9067-hash/WifiSecurityScanner](https://github.com/zadkiel9067-hash/WifiSecurityScanner) | 1 | Kotlin | Advanced WiFi Security Scanner with Evil Twin Detection |
| 1495 | [Zebratic/ESP8266-DeAuther](https://github.com/Zebratic/ESP8266-DeAuther) | 1 | C | Wifi Jammer/DeAuther using a NodeMCU ESP8266 board.  |
| 1496 | [zeleron7/Wi-Fi-security-risks](https://github.com/zeleron7/Wi-Fi-security-risks) | 1 | — | Thesis project exploring security risks in open Wi-Fi networks, demonstrating Evil Twin attacks i… |
| 1497 | [zidhuxdev/WiSpam](https://github.com/zidhuxdev/WiSpam) | 1 | C++ | WiSpam —ESP32 WiFi Beacon Spammer. Broadcasts fake phone-model hotspot SSIDs. |
| 1498 | [ZorvWolf/EvilJam](https://github.com/ZorvWolf/EvilJam) | 1 | Python | So guys this is asicly a wifi tool which helps in deauth attack and Cracking wpa2 handshake files… |
| 1499 | [0xfL0ki/wifiee](https://github.com/0xfL0ki/wifiee) | 0 | Shell | WiFi EAP Evil-twin & PEAP Relay Toolkit |
| 1500 | [1F1XDRAGOB/Esp8266-deauther](https://github.com/1F1XDRAGOB/Esp8266-deauther) | 0 | — | ESP8266 Deauther is a WiFi deauthentication tool based on the ESP8266 microcontroller. It sends d… |
| 1501 | [1uci1er/Evil-Twin-Attack](https://github.com/1uci1er/Evil-Twin-Attack) | 0 | — | WIFI Evil Twin Attack Guide |
| 1502 | [41vi4p/WiFi_Monitor](https://github.com/41vi4p/WiFi_Monitor) | 0 | C | WiFi_Monitor — Advanced WiFi security monitoring and threat detection system for ESP32-C6. Real-t… |
| 1503 | [4min4yed/WIFI32-ESP32-Embedded-WIFI-Hacking](https://github.com/4min4yed/WIFI32-ESP32-Embedded-WIFI-Hacking) | 0 | C++ | Utilizing ESP32's 2.4 GHz Wifi card to conduct active and passive network sniffinf as welle as Do… |
| 1504 | [7yasin/esp-synapse](https://github.com/7yasin/esp-synapse) | 0 | — | A distributed cybersecurity platform using low-cost ESP32/ESP8266 devices as centrally managed ag… |
| 1505 | [aayush-xid-su/Esp32-Horcrux](https://github.com/aayush-xid-su/Esp32-Horcrux) | 0 | C++ | A comprehensive collection of ESP32 tools, scripts, and utilities for wireless security research,… |
| 1506 | [Abdelkarim-mourad/evolution-of-wifi-security-wpa2-wpa3](https://github.com/Abdelkarim-mourad/evolution-of-wifi-security-wpa2-wpa3) | 0 | — | Wireless security research project analyzing WPA2 weaknesses, WPA3 improvements, SAE handshake, D… |
| 1507 | [abdullahkhan4050/WIFI_HACKING](https://github.com/abdullahkhan4050/WIFI_HACKING) | 0 | — |  🔐 Exploring WiFi Security Using ESP8266: Deauthentication & Evil Twin Attacks I'm excited to sha… |
| 1508 | [abhi04anon/Network-Security-Toolkit](https://github.com/abhi04anon/Network-Security-Toolkit) | 0 | C++ | ESP8266 Network Security Toolkit - Educational WiFi security testing tool featuring deauth attack… |
| 1509 | [abhi96bold/esp32-wifi-and-bluetooth-deauther-with-scroling-function](https://github.com/abhi96bold/esp32-wifi-and-bluetooth-deauther-with-scroling-function) | 0 | — |  |
| 1510 | [abhinai2244/BLE-WIFI-JAMMER](https://github.com/abhinai2244/BLE-WIFI-JAMMER) | 0 | C++ | This project contains firmware for a Bluetooth jammer using an ESP32 and NRF24L01 radio modules |
| 1511 | [Adii3310/ESP32__jammer](https://github.com/Adii3310/ESP32__jammer) | 0 | C++ | this is the code for the ESP32 development board for programming it for the jammer this ESP32 jam… |
| 1512 | [Adityachawan97/Esp8266-Wifi-Deauther](https://github.com/Adityachawan97/Esp8266-Wifi-Deauther) | 0 | — | Contains files about the Esp8266 based Wifi Deauther and Beacon Spammer. |
| 1513 | [AhMahPort/ESP32-Wifi-Attack-Detector](https://github.com/AhMahPort/ESP32-Wifi-Attack-Detector) | 0 | C++ | A defensive Wireless Intrusion Detection System (WIDS) on the ESP32 |
| 1514 | [ahmeddurjoy14-spec/mt2-toolkit](https://github.com/ahmeddurjoy14-spec/mt2-toolkit) | 0 | Python | MT2 WiFi Pentest Toolkit - ESP8266 firmware with deauth fix |
| 1515 | [Aishah205/wifi-security-lab](https://github.com/Aishah205/wifi-security-lab) | 0 | — | WiFi Security Lab (simulated, no USB adapter) : conceptual walkthrough of WPA2 handshake capture … |
| 1516 | [AJ39210/Esp32-based-os-WiFi-jammer](https://github.com/AJ39210/Esp32-based-os-WiFi-jammer) | 0 | — | Nothing to see here maybe read "read me.md |
| 1517 | [akshay-j01/esp32-wifi-pentest-eviltwin](https://github.com/akshay-j01/esp32-wifi-pentest-eviltwin) | 0 | C++ | ESP32-based Wi-Fi security awareness project demonstrating rogue access point and captive portal … |
| 1518 | [AlanArantes/ESP32-BlueJammer](https://github.com/AlanArantes/ESP32-BlueJammer) | 0 | — | The ESP32-BlueJammer (Bluetooth jammer, BLE jammer, WiFi jammer, RC jammer) disrupts 2.4GHz commu… |
| 1519 | [AlexNaskida/WiFi-Evil-Twin](https://github.com/AlexNaskida/WiFi-Evil-Twin) | 0 | Shell |  |
| 1520 | [Aley3567/wifi-deauth-sentinel](https://github.com/Aley3567/wifi-deauth-sentinel) | 0 | Python | ESP32 + LLM powered WiFi Deauth attack detection system |
| 1521 | [alfredo-allan/EvilTwinAttack](https://github.com/alfredo-allan/EvilTwinAttack) | 0 | HTML | Ataque Via ESP32 Redes Wifi |
| 1522 | [ali-hadak/BHT-](https://github.com/ali-hadak/BHT-) | 0 | C++ | Türk yapımı ESP8266 tabanlı hacker terminali - 16x2 LCD ve WiFi özellikli |
| 1523 | [ali-hadak/BTH-v1.0](https://github.com/ali-hadak/BTH-v1.0) | 0 | — | Türk yapımı ESP8266 tabanlı hacker terminali - 16x2 LCD ve WiFi özellikli |
| 1524 | [alungal-sinan/WiFi-EvilTwin-Emulator](https://github.com/alungal-sinan/WiFi-EvilTwin-Emulator) | 0 | Python | A simulation tool written in Python that emulates an Evil Twin access point with fake DHCP and DN… |
| 1525 | [Amalhameed-stack/Wifi-Bluetooth-classic-and-BLE-jammer-using-one-nRF24L01-module-and-esp32](https://github.com/Amalhameed-stack/Wifi-Bluetooth-classic-and-BLE-jammer-using-one-nRF24L01-module-and-esp32) | 0 | — | This project is for educational purposes only |
| 1526 | [amirfazari01-commits/ESP32-WiFi-Jammer-Detection-Dashboard](https://github.com/amirfazari01-commits/ESP32-WiFi-Jammer-Detection-Dashboard) | 0 | HTML | Real-time WiFi monitoring and abnormal connectivity detection system using ESP32, Firebase, and a… |
| 1527 | [anishaSawant0409/EvilTwin-wifi-access-point-detector](https://github.com/anishaSawant0409/EvilTwin-wifi-access-point-detector) | 0 | HTML | An intelligent Wi-Fi security tool that detects Evil Twin access points by monitoring network par… |
| 1528 | [Ano-sys/ESP32WiFiPolluter](https://github.com/Ano-sys/ESP32WiFiPolluter) | 0 | C | This projects main purpose was to get into ESP-IDF and have some fun with polluting the WiFi spec… |
| 1529 | [apexmaniac/Wi-Fi-SCC](https://github.com/apexmaniac/Wi-Fi-SCC) | 0 | Python | scripts to scan wifi networks , capture handshakes & cracking passwords |
| 1530 | [ArdNU/OMEGA-Device](https://github.com/ArdNU/OMEGA-Device) | 0 | — | Ultimate ESP32-S3 Multi-tool DIY device: WiFi, Bluetooth, Sub-Ghz RF, IR, NFC, GPS. Open-source f… |
| 1531 | [arfuuu/Esp8266_2.5hz_wifi_deauther](https://github.com/arfuuu/Esp8266_2.5hz_wifi_deauther) | 0 | — |  |
| 1532 | [ArjunPavanje/ESP32_WiFi_Attacks](https://github.com/ArjunPavanje/ESP32_WiFi_Attacks) | 0 | C++ |  |
| 1533 | [arjuntanwar/espbox](https://github.com/arjuntanwar/espbox) | 0 | C++ | This is a comprehensive ESP32-based multi-tool firmware with 19+ modules including WiFi attacks, … |
| 1534 | [Aromalajith8/Bluject](https://github.com/Aromalajith8/Bluject) | 0 | C++ | An open-source, multi-OS BLE HID keystroke injection tool built for the ESP32. Features an air-ga… |
| 1535 | [ashikurrafi/esp32s3-wifi-pentest](https://github.com/ashikurrafi/esp32s3-wifi-pentest) | 0 | C |  |
| 1536 | [AtaCanYmc/Loki-Esp32](https://github.com/AtaCanYmc/Loki-Esp32) | 0 | C | Esp32 device for basic wifi examples |
| 1537 | [avinashyadav143210-lab/-Bt-wifi-jammerr](https://github.com/avinashyadav143210-lab/-Bt-wifi-jammerr) | 0 | — | Bluetooth and wifi  jammer by using ESP32 |
| 1538 | [aymannijamuddeen/WIFI-EvilL-twin-detection-](https://github.com/aymannijamuddeen/WIFI-EvilL-twin-detection-) | 0 | Python |  |
| 1539 | [B34tF34T/fluxion-original](https://github.com/B34tF34T/fluxion-original) | 0 | — | wifi evil twin pentesting |
| 1540 | [bangladeshcyberspectre/WIFI-SCANNER](https://github.com/bangladeshcyberspectre/WIFI-SCANNER) | 0 | Shell | wifi-scanner, cybersecurity, penetration-testing, ethical-hacking, aircrack-ng,  reaver, wps-atta… |
| 1541 | [Ben-Big/wifiCrackGUI](https://github.com/Ben-Big/wifiCrackGUI) | 0 | Python | BOG'S WiFi Attack Suite is a GUI-based WiFi security testing tool that enables network scanning, … |
| 1542 | [berkaybnc/EvilTwinWifi](https://github.com/berkaybnc/EvilTwinWifi) | 0 | HTML |  |
| 1543 | [bilal-robotics/-WiFi-BLE-Jammer](https://github.com/bilal-robotics/-WiFi-BLE-Jammer) | 0 | C++ | Yeh ek WiFi + BLE Jammer ka Arduino code hai jo ESP32 aur 2x NRF24L01 modules use karta hai. |
| 1544 | [BioNos1/WiFi-DeAuth-Detector](https://github.com/BioNos1/WiFi-DeAuth-Detector) | 0 | C++ | ESP8266 Wi-Fi Deauthentication Attack Detector |
| 1545 | [bl4k7en/NetSpec](https://github.com/bl4k7en/NetSpec) | 0 | C++ | ESP8266-based WiFi security testing tool with twin AP attack and credential capture via captive p… |
| 1546 | [blacksnakeCYS/BlackSnake_wifi](https://github.com/blacksnakeCYS/BlackSnake_wifi) | 0 | C++ | Wifi hack for esp32 |
| 1547 | [bmitay4/WiFiEvilTwin](https://github.com/bmitay4/WiFiEvilTwin) | 0 | — | ‫‪WiFi‬‬ ‫‪Attack‬‬ ‫&‬ ‫‪Defense‬‬ ‫‪Module‬‬ |
| 1548 | [boydjawun/WiFi-Deauthentication-Attack-ESP32-Aircrack-ng](https://github.com/boydjawun/WiFi-Deauthentication-Attack-ESP32-Aircrack-ng) | 0 | — | Deauthenticating devices from an ESP32 SoftAP using Aircrack-ng on Kali Linux with an AR9271 WiFi… |
| 1549 | [brycedc/esp32-blackout](https://github.com/brycedc/esp32-blackout) | 0 | C | ESP32 Pentest Wifi Tool |
| 1550 | [bytecod3/RedZone-HackerBadge](https://github.com/bytecod3/RedZone-HackerBadge) | 0 | — | A DIY ESP32 hacker badge with Wi-Fi/Bluetooth meshing, an OLED, and stealthy CTF challenges and p… |
| 1551 | [catx0rr/wifiphisher-mod](https://github.com/catx0rr/wifiphisher-mod) | 0 | C | Evil-Twin for wireless penetration tests |
| 1552 | [charan10k/wifi-deauther-esp8266](https://github.com/charan10k/wifi-deauther-esp8266) | 0 | — | WiFi deauthentication is a process where a device is disconnected from a WiFi network. This can b… |
| 1553 | [CHEN-233/esp8266](https://github.com/CHEN-233/esp8266) | 0 | — | wifi-attack。 |
| 1554 | [chonada/EmbedOS](https://github.com/chonada/EmbedOS) | 0 | C | A from-scratch ESP-IDF + FreeRTOS OS for the LilyGO T-Embed CC1101 (ESP32-S3): app launcher, sub-… |
| 1555 | [chrisq-dev/phantom-kit](https://github.com/chrisq-dev/phantom-kit) | 0 | C++ | Suite de auditoría de seguridad y ingeniería social para ESP8266 con dashboard web, evil portal, … |
| 1556 | [chukwupg/wireless-security-audit-lab](https://github.com/chukwupg/wireless-security-audit-lab) | 0 | — | Wireless Security Assessment Lab simulating WPA/WPA2 attacks, including handshake capture, deauth… |
| 1557 | [Cipher-Sheild/WiFiStrike-FW](https://github.com/Cipher-Sheild/WiFiStrike-FW) | 0 | Shell | Modular wireless penetration testing framework for WPA/WPA2 assessment, handshake capture, deauth… |
| 1558 | [ciscothehackergod/Wpa2_cracking](https://github.com/ciscothehackergod/Wpa2_cracking) | 0 | — | i simulated a wifi handshake capture attack on my home lab and cracked the captured hash  |
| 1559 | [claculator/deauther](https://github.com/claculator/deauther) | 0 | C++ | ESP32 Wifi deauther with extra features, uses SSD1306 display and 3 buttons |
| 1560 | [cnaqxc/evil-twin-wifi](https://github.com/cnaqxc/evil-twin-wifi) | 0 | Python |  |
| 1561 | [cod-xio/Growatt-Shine-X](https://github.com/cod-xio/Growatt-Shine-X) | 0 | C | ESP8266 replacement firmware for Growatt SHINE WiFi X dongle. Modbus RTU, MQTT, Home Assistant Au… |
| 1562 | [CoreProtectSource/Esp8266-Jammer](https://github.com/CoreProtectSource/Esp8266-Jammer) | 0 | — | Простая глушилка wifi на esp8266. |
| 1563 | [Cuberzing/wifi-pentest-lab](https://github.com/Cuberzing/wifi-pentest-lab) | 0 | — | Full WPA2 penetration test — TP-Link monitor mode setup, live handshake capture via deauth attack… |
| 1564 | [cuzoisrael/izywifi](https://github.com/cuzoisrael/izywifi) | 0 | Python | Python wrapper for WiFi auditing: Scan, capture handshakes, and prep for cracking (ethical lab to… |
| 1565 | [cwolfe1080/OpenCircuit](https://github.com/cwolfe1080/OpenCircuit) | 0 | C++ | An open-source arcade racing game for the PyBadge, featuring custom community-made tracks, online… |
| 1566 | [Cyber-Squad-CST/WiFi-Pentest-Kit-Flasher](https://github.com/Cyber-Squad-CST/WiFi-Pentest-Kit-Flasher) | 0 | — | ​An automated cross-platform tool to seamlessly flash custom firmware, Deauther scripts, and secu… |
| 1567 | [cyph-zz/RF-Pennywise](https://github.com/cyph-zz/RF-Pennywise) | 0 | C++ | ESP32 + nRF24L01x RF toolkit: jamming, WiFi/BLE scanning, spectrum analysis & security-awareness … |
| 1568 | [daboynb/wps-catcher](https://github.com/daboynb/wps-catcher) | 0 | C | ESP32 firmware for WPS attacks with captive web UI (SoftAP + WebSocket) |
| 1569 | [danaahmadifar/wifi-signal-tester-mit-esp32-support](https://github.com/danaahmadifar/wifi-signal-tester-mit-esp32-support) | 0 | Python | WLAN Signal-Tester und Netzwerk-Diagnosesystem mit ESP32 (Promiscuous Sniffer & Bluetooth SPP) un… |
| 1570 | [danialn000876/ESP32-wifi-deauth-detector](https://github.com/danialn000876/ESP32-wifi-deauth-detector) | 0 | C++ | ESP32-based passive Wi-Fi deauth attack detector and instrusion detection system (IDS) |
| 1571 | [daniel-mwendwa/WiFi-Security-and-PenTesting](https://github.com/daniel-mwendwa/WiFi-Security-and-PenTesting) | 0 | — | A comprehensive report on WiFi security and penetration testing techniques, covering WPA & WPA2 e… |
| 1572 | [darkrider88/wifi-auditor](https://github.com/darkrider88/wifi-auditor) | 0 | Python | A python tool to capture Wireless network handshake and crack it |
| 1573 | [daykiller-viann/esp32D4yk1ll3rsec](https://github.com/daykiller-viann/esp32D4yk1ll3rsec) | 0 | — | alat peretasan ,jammer bluetooth attack ,deauther,beacon spam ,auth spam |
| 1574 | [denethsec/evil-twin-wifi-lab](https://github.com/denethsec/evil-twin-wifi-lab) | 0 | Python |  |
| 1575 | [Denilxavier/esp32-Marauder](https://github.com/Denilxavier/esp32-Marauder) | 0 | — | ESP32-based wireless tool for both offensive testing and defensive detection deauth attacks, rogu… |
| 1576 | [dheerajramasahayam/Model_Training](https://github.com/dheerajramasahayam/Model_Training) | 0 | Python | Train model on wifi handshakes and try to crack passwords |
| 1577 | [Dhiraj60/esp8266-wifi-jammer](https://github.com/Dhiraj60/esp8266-wifi-jammer) | 0 | — |  |
| 1578 | [Dhiraj60/esp8266_wifi_jammer.](https://github.com/Dhiraj60/esp8266_wifi_jammer.) | 0 | — |  |
| 1579 | [dhruvnotcyber2005/WPA-WPA2-WiFi-Password-Cracking](https://github.com/dhruvnotcyber2005/WPA-WPA2-WiFi-Password-Cracking) | 0 | — | Educational WPA2 Wi-Fi security assessment project demonstrating handshake capture and password a… |
| 1580 | [Diksha-Deshmukh/wifi-threat-detector](https://github.com/Diksha-Deshmukh/wifi-threat-detector) | 0 | Python | Django-based Wi‑Fi security monitoring system for detecting rogue access points, evil twin attack… |
| 1581 | [divisionind/hackquad](https://github.com/divisionind/hackquad) | 0 | HTML | the hackable open-source esp32 wifi controlled quadcopter |
| 1582 | [dome-hub/WiFi-Security-Auditing-Project](https://github.com/dome-hub/WiFi-Security-Auditing-Project) | 0 | — | WPA2 Handshake Cracking |
| 1583 | [ducokaptein-cyber/esp-32-sub-ghz-scanner](https://github.com/ducokaptein-cyber/esp-32-sub-ghz-scanner) | 0 | — |  a esp32 u with a 0.96 oled screen and a cc1101 moudle to scan wifi for sub ghz devices. |
| 1584 | [Durzan12/Pocket-Hydra](https://github.com/Durzan12/Pocket-Hydra) | 0 | C++ | Esp8266 with a bunch of modules and a dream? here you go, IR, SubGHz, Deauther, a hydra of contro… |
| 1585 | [el-pablos/TamsDeauth](https://github.com/el-pablos/TamsDeauth) | 0 | C | TamsDeauth - WiFi Deauther untuk ESP8266 dengan SSD1306 OLED, 10+ attack modes, web interface 65 … |
| 1586 | [ElectrovillaYt/ESP8266-Wifi-Jammer](https://github.com/ElectrovillaYt/ESP8266-Wifi-Jammer) | 0 | — | For Educational Purpose only! |
| 1587 | [ELSHAB7UAHED/bin](https://github.com/ELSHAB7UAHED/bin) | 0 | C++ | BARA - ESP32 WiFi Security Testing Tool. Advanced WiFi scanner with hacker-style web interface fo… |
| 1588 | [embededbuild/Mona-Lisa](https://github.com/embededbuild/Mona-Lisa) | 0 | — | a esp32 device that can do WiFi/BLE base attacks and also have the ability to READ/WRITE to card/… |
| 1589 | [Eren-Oztk/esp32-wifi-bluetooth-scanner](https://github.com/Eren-Oztk/esp32-wifi-bluetooth-scanner) | 0 | C++ | ESP32-based scanner that detects nearby Wi-Fi and Bluetooth devices for local network analysis. |
| 1590 | [ethanrunn/Simulated-WiFi-Hacking-Report-WPA2-Handshake-Capture-and-Crack](https://github.com/ethanrunn/Simulated-WiFi-Hacking-Report-WPA2-Handshake-Capture-and-Crack) | 0 | — |  |
| 1591 | [etherift/esp32-wifi-jammer](https://github.com/etherift/esp32-wifi-jammer) | 0 | — |  |
| 1592 | [FancybearIN/Wifi_jammer](https://github.com/FancybearIN/Wifi_jammer) | 0 | Shell | The Wi-Fi Jammer Tool is a comprehensive bash script designed to automate the management and depl… |
| 1593 | [Fir3n0x/ESPion32](https://github.com/Fir3n0x/ESPion32) | 0 | Kotlin | ESPion32 is an ESP32 project which uses an Android application to set up wifi attacks on the prov… |
| 1594 | [Frendi-X/ESP8266-P10-Digital-Clock-WiFiManager-NTP](https://github.com/Frendi-X/ESP8266-P10-Digital-Clock-WiFiManager-NTP) | 0 | C++ | Sistem ini dirancang sebagai jam digital berbasis ESP8266 dan Panel LED P10 yang mampu menampilka… |
| 1595 | [G1thu8D4LL45/WIFIght](https://github.com/G1thu8D4LL45/WIFIght) | 0 | Shell | One single tool to catch handshakes and crack wifi passwords with a bunch of tools. |
| 1596 | [gabriel-re-pires/Deauther_BW16_5GHz_2.0](https://github.com/gabriel-re-pires/Deauther_BW16_5GHz_2.0) | 0 | C | Ataques em redes Wi-Fi de 5GHz e 2.4GHz, projetado para uso em ambientes controlados. |
| 1597 | [GamerFuryAction/Deauth-testing-device](https://github.com/GamerFuryAction/Deauth-testing-device) | 0 | — | Cybersecurity testing device based on the BW16 development board, designed for testing the securi… |
| 1598 | [GaniiGanesh/WIFI-Deauther-Pen-Tester](https://github.com/GaniiGanesh/WIFI-Deauther-Pen-Tester) | 0 | — | A simple WiFi Deauthentication tool using ESP8266 |
| 1599 | [geetanjalikuwar/Wifi-attack-automation-using-ESP8266](https://github.com/geetanjalikuwar/Wifi-attack-automation-using-ESP8266) | 0 | C++ |  |
| 1600 | [GHOST-WEB-spec/SPECTER](https://github.com/GHOST-WEB-spec/SPECTER) | 0 | C++ | ESP32-based handheld pentesting device running JINX OS. WiFi, BLE, IR, Sub-GHz, NFC and more. |
| 1601 | [giri068/evil-twin-wifi](https://github.com/giri068/evil-twin-wifi) | 0 | PHP | This project demonstrates how an Evil Twin Wi-Fi attack works by simulating a fake Access Point w… |
| 1602 | [h3ides/wifi-deauther](https://github.com/h3ides/wifi-deauther) | 0 | C | esp8266 wifi-deauther |
| 1603 | [hacking-in-kannada/esp32-wifi-jammer](https://github.com/hacking-in-kannada/esp32-wifi-jammer) | 0 | C++ |  |
| 1604 | [hamzaasghar2429/Esp8266_Deauther](https://github.com/hamzaasghar2429/Esp8266_Deauther) | 0 | — | Affordable WiFi hacking platform for testing and learning. I recreate my own version it is inspir… |
| 1605 | [haniefautophile-official/Arduino-ESP8266-WifiDeauther](https://github.com/haniefautophile-official/Arduino-ESP8266-WifiDeauther) | 0 | C++ |  |
| 1606 | [haodiy12-code/esp32-c3-mini-jammer-jammer-ir-jammer-wifi-2.4](https://github.com/haodiy12-code/esp32-c3-mini-jammer-jammer-ir-jammer-wifi-2.4) | 0 | C++ | DIY Tactical Multi-Tool using ESP32-C3 SuperMini, nRF24L01+, 0.96" OLED, TV-B-Gone (400+ IR codes… |
| 1607 | [harshapentu/esp32-wifi-pentest](https://github.com/harshapentu/esp32-wifi-pentest) | 0 | C | Educational Wi-Fi security testing project using ESP32. This repository focuses on understanding … |
| 1608 | [HarshitUmrao/Wifi-Attack-System](https://github.com/HarshitUmrao/Wifi-Attack-System) | 0 | — | Built a practical cybersecurity project simulating real Wi-Fi attacks to study wireless vulnerabi… |
| 1609 | [HarshRajSinghania/AirPhantom](https://github.com/HarshRajSinghania/AirPhantom) | 0 | Python | Wifi Deauther |
| 1610 | [HasanRsool/Simple-Signal-Jammer](https://github.com/HasanRsool/Simple-Signal-Jammer) | 0 | C++ | A simple WiFi & Bluetooth jammer using ESP32 & nRF24L01. |
| 1611 | [Hata214/MultitoolEvilWifi](https://github.com/Hata214/MultitoolEvilWifi) | 0 | COBOL | This is the Evil tool for wifi 2.4GHz ( The bad of hardware cannot support for 5Ghz wifi), I'm ma… |
| 1612 | [HelixCipher/wifi-penetration-testing](https://github.com/HelixCipher/wifi-penetration-testing) | 0 | Python | WiFi penetration testing guide with hardware-based and hardware-free setups. Includes handshake c… |
| 1613 | [HikmatAsifli/wifi_auth_tool](https://github.com/HikmatAsifli/wifi_auth_tool) | 0 | Shell | Modular bash toolkit for WiFi recon, WPA/WPA2 handshake capture & cracking — built for authorized… |
| 1614 | [Hotboy2414/Esp8266](https://github.com/Hotboy2414/Esp8266) | 0 | — | WiFi jam |
| 1615 | [htrooot/ESP8266-Evil-Twin-Deauthentication-Tool](https://github.com/htrooot/ESP8266-Evil-Twin-Deauthentication-Tool) | 0 | C++ | This is an educational cybersecurity tool designed to demonstrate common WiFi security vulnerabil… |
| 1616 | [hygef-v4/wifi-tool-esp8266](https://github.com/hygef-v4/wifi-tool-esp8266) | 0 | C++ | wifi deauth + evil twin esp8266 (educational purpose only) |
| 1617 | [IbrahimCR8/wifi-jammer-esp8266](https://github.com/IbrahimCR8/wifi-jammer-esp8266) | 0 | C |  |
| 1618 | [imanfatimz/wifi_evil_twin_detector](https://github.com/imanfatimz/wifi_evil_twin_detector) | 0 | Python |  |
| 1619 | [InoshMatheesha/ZeNeOn-ESP32-WiFi-Framework](https://github.com/InoshMatheesha/ZeNeOn-ESP32-WiFi-Framework) | 0 | C++ | ZeNeOn is an ESP32-based WiFi security assessment framework that provides deauthentication attack… |
| 1620 | [IshanShrestha77/Wifi-Jammer-Bw16](https://github.com/IshanShrestha77/Wifi-Jammer-Bw16) | 0 | — | Wi-Fi Security Research Device using BW16 This project builds a Wi-Fi security research device fr… |
| 1621 | [Isonimus/dupin](https://github.com/Isonimus/dupin) | 0 | C++ | A passive Wi-Fi security tool for the ESP-32 designed to observe, analyze, and detect anomalies i… |
| 1622 | [Isonimus/esp32-arduino-adv-libs](https://github.com/Isonimus/esp32-arduino-adv-libs) | 0 | JavaScript | Patched ESP-IDF 5.5 + Arduino-core precompiled-libraries build. Provenance-pinned drop-in for fra… |
| 1623 | [itz-mg/AirKick](https://github.com/itz-mg/AirKick) | 0 | — | Simple Wifi Deauther for Arduino Nano ESP32 |
| 1624 | [JackTheTripperr/WiFi-Hack](https://github.com/JackTheTripperr/WiFi-Hack) | 0 | — | Basic guide outlining the process to capture a handshake, convert it to a Hashcat compatible hash… |
| 1625 | [jagaor/Auditoria-WiFi-EvilTwin-Python](https://github.com/jagaor/Auditoria-WiFi-EvilTwin-Python) | 0 | — | Herramienta de ciberseguridad en Python para auditar redes WiFi, detectar ataques Evil Twin y val… |
| 1626 | [jagdishtripathy/WIFI-Password-Cracking](https://github.com/jagdishtripathy/WIFI-Password-Cracking) | 0 | — | This documentation demonstrates how to perform a WPA/WPA2 Wi-Fi handshake capture and password cr… |
| 1627 | [jaringankantor/ESP32-C3-OpenSourceProject](https://github.com/jaringankantor/ESP32-C3-OpenSourceProject) | 0 | C++ | Kumpulan contoh program open source untuk ESP32-C3 dengan OLED 72x40 I2C. Berisi project Blink LE… |
| 1628 | [JavierSiliacay/Wifi-Deauther-project](https://github.com/JavierSiliacay/Wifi-Deauther-project) | 0 | — | ESP8266-based educational tool for WiFi network exploration and security analysis. For educationa… |
| 1629 | [jenish78/fake-wifi-evil-twin-detection-tool](https://github.com/jenish78/fake-wifi-evil-twin-detection-tool) | 0 | Python | fake wifi |
| 1630 | [jessnolimit-lgtm/Wifi-Deauther-](https://github.com/jessnolimit-lgtm/Wifi-Deauther-) | 0 | — | A Wi-Fi deauthentication tool built on ESP8266 that scans nearby networks and sends 802.11 deauth… |
| 1631 | [Jexasa/wifighter](https://github.com/Jexasa/wifighter) | 0 | Python | A Python CLI tool to capture and crack WPA/WPA2 handshakes using Kali Linux and `aircrack-ng` or … |
| 1632 | [JKCOM1911/Jammer-wifi-Bluetooth-esp32](https://github.com/JKCOM1911/Jammer-wifi-Bluetooth-esp32) | 0 | C++ |  |
| 1633 | [jodhanfab/wifi-deauther-esp8266](https://github.com/jodhanfab/wifi-deauther-esp8266) | 0 | C | wifi deauther for esp8266 inspired from @SpacehuhnTech |
| 1634 | [jpswensen/esp8266-eap-lowmem](https://github.com/jpswensen/esp8266-eap-lowmem) | 0 | C++ | A working example of Enterprise wifi on the ESP8266 with hacks to move constant TLS data from DRA… |
| 1635 | [JSMAKERS015/ESP8266-WIFI-JAMMER](https://github.com/JSMAKERS015/ESP8266-WIFI-JAMMER) | 0 | Pascal |  |
| 1636 | [jvnwq6ctgw-max/https-github.com-n0tAv1ru5-RTL8720dn-5GHz-Wifi-Deauther](https://github.com/jvnwq6ctgw-max/https-github.com-n0tAv1ru5-RTL8720dn-5GHz-Wifi-Deauther) | 0 | — |  |
| 1637 | [jyotipanchal1922/esp8266-evil-twin](https://github.com/jyotipanchal1922/esp8266-evil-twin) | 0 | C++ | cybersecurity \| esp8266 \| arduino \| wifi-security \| network-security |
| 1638 | [kayShahbaaz/thm-wifi-hacking101](https://github.com/kayShahbaaz/thm-wifi-hacking101) | 0 | — | Notes from TryHackMe's WiFi Hacking 101 room. Capturing WPA/WPA2 4 way handshakes with the aircra… |
| 1639 | [kogmau/gatonet](https://github.com/kogmau/gatonet) | 0 | Python | GatoNet — avaliacao autorizada de redes WiFi: scan, assess, capture (PMKID/handshake/WPS), crack … |
| 1640 | [konaaakonaaa/bw16-deauth-detector](https://github.com/konaaakonaaa/bw16-deauth-detector) | 0 | C++ | Пассивный монитор WiFi (BW16/RTL8720DN), обнаруживающий deauth/disassoc-атаки |
| 1641 | [ksaswin/esp8266_wifi_deauth](https://github.com/ksaswin/esp8266_wifi_deauth) | 0 | C++ | Wifi Deauther using ESP8266 node mcu |
| 1642 | [LamarCS1337/wifitraining](https://github.com/LamarCS1337/wifitraining) | 0 | Shell | Evil Twin Training |
| 1643 | [lamerous/TinySniff](https://github.com/lamerous/TinySniff) | 0 | — | Tool for WiFi and NFC pentest attacks powered by ESP8266. |
| 1644 | [Lavictus/DeAuth](https://github.com/Lavictus/DeAuth) | 0 | C | ESP32-Wifi-Deauthentication |
| 1645 | [Leakyli/2.4GHz-BLE-WIFI-SNIFFER](https://github.com/Leakyli/2.4GHz-BLE-WIFI-SNIFFER) | 0 | C | A 3-in-1 project that includes the use of ESP32U's built in Bluetooth and Wifi shared radio and a… |
| 1646 | [leandrovitormoreira39012/GhostTek-PRE_ALPHA](https://github.com/leandrovitormoreira39012/GhostTek-PRE_ALPHA) | 0 | — | Firmware focado em wifi hacking, bluetooth jammig, nfc, lora e gps. Interface interativa. Inicial… |
| 1647 | [leduy100414/Code-Hack-Wifi-RTL8720DN-BW16-Vietsub](https://github.com/leduy100414/Code-Hack-Wifi-RTL8720DN-BW16-Vietsub) | 0 | C++ | Code hack nên mình sẽ không chịu các hành vi, vi phạm mọi người, mọi người làm sẽ có trách nhiệm … |
| 1648 | [lelouch456/esp8266_deauther](https://github.com/lelouch456/esp8266_deauther) | 0 | C | The main feature, the deauthentication attack, is used to disconnect devices from their WiFi netw… |
| 1649 | [liavgu/WifiMaster](https://github.com/liavgu/WifiMaster) | 0 | — | Automation tool for evil twin attack. |
| 1650 | [Linyings/esp32_wifi_attack](https://github.com/Linyings/esp32_wifi_attack) | 0 | C |  |
| 1651 | [LordEvron/ESP_wifi_fun](https://github.com/LordEvron/ESP_wifi_fun) | 0 | C | ESP8266 Deauther and SSID flooding.  |
| 1652 | [Lukasz-Wrobel/GhostBeacon](https://github.com/Lukasz-Wrobel/GhostBeacon) | 0 | C++ | A WiFi Probe Request Sniffer and Visualizer using an ESP32 and a WS2812 RGB LED Ring. Designed to… |
| 1653 | [lve-qw/espen](https://github.com/lve-qw/espen) | 0 | C++ | ESP32 based wifi/bluetooth pentest tool |
| 1654 | [M-YiXi/ESP32-BusPirate__Chinese-Localization__A-versatile-hacker-terminal](https://github.com/M-YiXi/ESP32-BusPirate__Chinese-Localization__A-versatile-hacker-terminal) | 0 | C | 它支持通过串口终端或基于网页的CLI与各种数字协议（I2C、UART、1-Wire、SPI等）进行嗅探、发送、脚本编写及交互。它还与蓝牙、Wi-Fi、sub-GHz和RFID等无线协议通信。 |
| 1655 | [M0D42/Botsec_Badge](https://github.com/M0D42/Botsec_Badge) | 0 | C++ | An esp8266 badge that you can make and help you hack the wifi |
| 1656 | [mahashakshuki/Network-Security-Project-WiFi-Evil-Twin-and-KRACK-Attack-](https://github.com/mahashakshuki/Network-Security-Project-WiFi-Evil-Twin-and-KRACK-Attack-) | 0 | — | WIFI Evil Twin and Krack Attack  |
| 1657 | [MAK554267/Blackout-2.4](https://github.com/MAK554267/Blackout-2.4) | 0 | C | Blackout 2.4 is a 5th Semester Network Security project that explores 2.4 GHz spectrum behavior a… |
| 1658 | [MallocPointer/esp8266_deauther](https://github.com/MallocPointer/esp8266_deauther) | 0 | — | Affordable WiFi hacking platform for testing and learning |
| 1659 | [manasashingade3/WiFi-jammer-detection](https://github.com/manasashingade3/WiFi-jammer-detection) | 0 | — | The Wi-Fi Jammer Detection System is an ESP32-based security device designed to detect Wi-Fi jamm… |
| 1660 | [manojan282006/ESP-Wireless-Security-Tools](https://github.com/manojan282006/ESP-Wireless-Security-Tools) | 0 | — | ESP32-based wireless security tools and educational projects featuring embedded interfaces, hardw… |
| 1661 | [mariusrazvan/impeditor-arduino](https://github.com/mariusrazvan/impeditor-arduino) | 0 | C++ | A firmware for the ESP8266 D1 mini that allows WiFi deauth attacks |
| 1662 | [mathish06/Sentinel-IDS](https://github.com/mathish06/Sentinel-IDS) | 0 | C++ | Portable passive WiFi Intrusion Detection System built on the ESP32. Detects Deauthentication flo… |
| 1663 | [maviaydin044-max/BlueDrogon](https://github.com/maviaydin044-max/BlueDrogon) | 0 | — | This software carries out kill attacks using the ESP32's Wi-Fi antennas.    PLEASE ONLY ATTACK YO… |
| 1664 | [mcbackup058-netizen/deauther-pro](https://github.com/mcbackup058-netizen/deauther-pro) | 0 | Python | Professional WiFi Security Testing Tool for ESP8266 - WPA2 Handshake Capture, Deauth Attack, Stea… |
| 1665 | [MevrickNeal/WraG](https://github.com/MevrickNeal/WraG) | 0 | C++ | Esp8266 based Telegram Comm device with wifi hacking capabilities  |
| 1666 | [Mfahadb/ESP8266-D1-Mini-Wifi-Deauther](https://github.com/Mfahadb/ESP8266-D1-Mini-Wifi-Deauther) | 0 | C++ |  |
| 1667 | [mhommet/esp32_wifi](https://github.com/mhommet/esp32_wifi) | 0 | C++ | Ethical hacking ESP32 dev module |
| 1668 | [milofrio066/Airlock](https://github.com/milofrio066/Airlock) | 0 | Python | IoT network monitoring system using ESP32, Python, and Flask. Detects Wi-Fi deauthentication atta… |
| 1669 | [MinArchie/evil-twin-wifi](https://github.com/MinArchie/evil-twin-wifi) | 0 | C |  |
| 1670 | [MO00X/WiFiPhisher](https://github.com/MO00X/WiFiPhisher) | 0 | — | ESP8266‑WiFiPhisher — ESP8266‑based rogue access‑point for Wi‑Fi phishing using captive portal an… |
| 1671 | [mriquelmec/ESP32-AI-SIEM-project](https://github.com/mriquelmec/ESP32-AI-SIEM-project) | 0 | Python | AI-powered SIEM that uses an ESP32 running Marauder firmware to collect Wi-Fi/BLE attack telemetr… |
| 1672 | [mrsathish2005/Esp32_ble-wifi_jammer](https://github.com/mrsathish2005/Esp32_ble-wifi_jammer) | 0 | C++ |  |
| 1673 | [mrsathish2005/Esp32_ble_wifi_jammer](https://github.com/mrsathish2005/Esp32_ble_wifi_jammer) | 0 | — |  |
| 1674 | [Mun-dus/Memory-Forensics-of-NMEA-2000-Wireless-De-Auth-Attack-Keyword-Search-Script](https://github.com/Mun-dus/Memory-Forensics-of-NMEA-2000-Wireless-De-Auth-Attack-Keyword-Search-Script) | 0 | Python | A keyword search tool built for the project Cracking the Maritime Handshake. It scans RAM dumps f… |
| 1675 | [mystry112000/wifi-analyzer](https://github.com/mystry112000/wifi-analyzer) | 0 | Python | WiFi Analyzer - Educational aircrack-ng wrapper with WiFi network scanner. Scan networks and crac… |
| 1676 | [nakano1337/ESP8266-Wifi-Deauther](https://github.com/nakano1337/ESP8266-Wifi-Deauther) | 0 | — |  |
| 1677 | [Nandahh14/Evil-Twin-Wifi-Detection](https://github.com/Nandahh14/Evil-Twin-Wifi-Detection) | 0 | SCSS | Behaviour-Aware Evil Twin Wi-Fi Detection System with adaptive risk analysis. |
| 1678 | [nandhakumard06-tech/Wolf-Jammer-IoT-](https://github.com/nandhakumard06-tech/Wolf-Jammer-IoT-) | 0 | — | Wolf Jammer IoT — ESP32-based WiFi security assessment tool for authorized pentesters. Supports d… |
| 1679 | [Nethravathi1706/WIFI-Deauther-Pen-Tester](https://github.com/Nethravathi1706/WIFI-Deauther-Pen-Tester) | 0 | — | A simple WiFi Deauthentication tool using ESP8266  |
| 1680 | [NikolaTesla17/testWifiDictAttack](https://github.com/NikolaTesla17/testWifiDictAttack) | 0 | C | test of esp8266's capacity as a tool for dictionary based wifi attacks |
| 1681 | [Nisar1000/wifi-jammer-with-node-mcu-esp8266-](https://github.com/Nisar1000/wifi-jammer-with-node-mcu-esp8266-) | 0 | — |  |
| 1682 | [nishk28/Wifi-password-hack](https://github.com/nishk28/Wifi-password-hack) | 0 | Python | A comprehensive Python-based automation tool for conducting authorized Wi-Fi security assessments… |
| 1683 | [nn1626/pwrlvl9000-pager](https://github.com/nn1626/pwrlvl9000-pager) | 0 | — | WiFi Pineapple Pager pentest console — 9-tab hacker web UI with WiFi, WPS, evil twin, probe sniff… |
| 1684 | [NS-Projects-Unina/ESP32_Attack](https://github.com/NS-Projects-Unina/ESP32_Attack) | 0 | Assembly | Attacchi a reti WiFi sfruttando una scheda ESP32 |
| 1685 | [nvinh5064-ctrl/esp8266_deauther.](https://github.com/nvinh5064-ctrl/esp8266_deauther.) | 0 | — | Affordable WiFi hacking platform for testing and learning |
| 1686 | [omairtemurian/Wifi-HS-Cracker](https://github.com/omairtemurian/Wifi-HS-Cracker) | 0 | Python | WPA/WPA2 handshake cracker — performs dictionary attacks against captured .cap files using pure P… |
| 1687 | [Onurcanblkn/wifi-pentest-project](https://github.com/Onurcanblkn/wifi-pentest-project) | 0 | — | WPA2 Handshake Cracking and Security Analysis |
| 1688 | [oscarSardaM/WiFI-Attacks-ESP32](https://github.com/oscarSardaM/WiFI-Attacks-ESP32) | 0 | C++ |  |
| 1689 | [oscarSardaM/WiFI-Attacks-ESP8266](https://github.com/oscarSardaM/WiFI-Attacks-ESP8266) | 0 | C++ |  |
| 1690 | [outgrow2029/macOS-WiFi-Pentest](https://github.com/outgrow2029/macOS-WiFi-Pentest) | 0 | Python | An automated script for cracking wifi handshakes, specific for MacOS via dictionary attack (for now) |
| 1691 | [ozarkplateautachinidae54/cyber-controller](https://github.com/ozarkplateautachinidae54/cyber-controller) | 0 | — | Manage security hardware and ESP32 devices from a single dashboard for cyberdecks and field opera… |
| 1692 | [P-ZINS/-ESP32-Marauder-M5Stick](https://github.com/P-ZINS/-ESP32-Marauder-M5Stick) | 0 | — | Déploiement d'un outil de pentest WiFi/Bluetooth portable sur microcontrôleur ESP32. |
| 1693 | [p4oT09/p4oT09](https://github.com/p4oT09/p4oT09) | 0 | — | 🔥 p4oT09 is an advanced WiFi exploitation toolkit ⚡ Made for pentesters, ethical hackers & resear… |
| 1694 | [ParthShethia25/wifi-jammer-using-esp8266-](https://github.com/ParthShethia25/wifi-jammer-using-esp8266-) | 0 | C |  |
| 1695 | [PawanKumarPandit/Esp8266_Wifi_Deauther](https://github.com/PawanKumarPandit/Esp8266_Wifi_Deauther) | 0 | C | Affordable WiFi hacking platform for testing and learning. |
| 1696 | [PedadaSwathiLakshmi/WIFI-Attack-Automation-using-ESP8266](https://github.com/PedadaSwathiLakshmi/WIFI-Attack-Automation-using-ESP8266) | 0 | C++ |  |
| 1697 | [Peterisdev/Skill-sync](https://github.com/Peterisdev/Skill-sync) | 0 | C++ | ESP8266-WiFi-Pentesting-Tool A comprehensive WiFi security testing toolkit for ESP8266 |
| 1698 | [phuongntmlc/NetworkII_WifiPwdCracking](https://github.com/phuongntmlc/NetworkII_WifiPwdCracking) | 0 | Python | Used brute-force method to create a tool can find WiFi password based on analyzing packets of the… |
| 1699 | [Phylakes01/wifi-deauther-esp8266-](https://github.com/Phylakes01/wifi-deauther-esp8266-) | 0 | C | ESP8266 OLED device with Wi-Fi AP, web interface, scan menu, show lists, attack simulation/status… |
| 1700 | [Pitchouneee/wifi-evil-twin](https://github.com/Pitchouneee/wifi-evil-twin) | 0 | PHP |  |
| 1701 | [PostboxRetinal/esp32_wifidemo](https://github.com/PostboxRetinal/esp32_wifidemo) | 0 | C++ | ESP32 WiFI pentest demo + OUI API lookup with cache implementation |
| 1702 | [Prajwalpawar1/evil-twin-wifi-](https://github.com/Prajwalpawar1/evil-twin-wifi-) | 0 | C++ | it is program which use to search all avilable wifi near to us and cheak password is valid or not… |
| 1703 | [Pranav-Darwai/wifi_deauther_esp8266](https://github.com/Pranav-Darwai/wifi_deauther_esp8266) | 0 | C++ | The WiFi Deauther ESP8266 is a simple tool designed to perform WiFi deauthentication attacks. It … |
| 1704 | [pranitdhanade-sys/ESP32-Wifi-attacker](https://github.com/pranitdhanade-sys/ESP32-Wifi-attacker) | 0 | Python |  |
| 1705 | [Prateek13421/wifi-deauther-esp8266](https://github.com/Prateek13421/wifi-deauther-esp8266) | 0 | C | deauth any wifi in your network |
| 1706 | [R00TV3X/WiFi-Security-Demonstrator](https://github.com/R00TV3X/WiFi-Security-Demonstrator) | 0 | — | A controlled lab simulation of Wi-Fi Deauthentication & Evil Twin attacks using NodeMCU (ESP8266)… |
| 1707 | [rabeehpullichola/ESP8266-WiFi-Deauther](https://github.com/rabeehpullichola/ESP8266-WiFi-Deauther) | 0 | C++ |  |
| 1708 | [RachappaB/wifi_hacking](https://github.com/RachappaB/wifi_hacking) | 0 | C++ | A hands-on Wi-Fi security research project exploring wireless attacks from beacon frames and pack… |
| 1709 | [radoslawsmolinski-byte/ESP32-NetHunter-Pentest](https://github.com/radoslawsmolinski-byte/ESP32-NetHunter-Pentest) | 0 | — | Integrated Android + ESP32 + Backend pentest framework with OTG serial communication and WiFi pen… |
| 1710 | [RaviNayyar/WifiAutoEvilTwin](https://github.com/RaviNayyar/WifiAutoEvilTwin) | 0 | Python | Automatically executes an wifi evil twin attack |
| 1711 | [retr0-dedsec2/Deauther-Simple-with-esp32](https://github.com/retr0-dedsec2/Deauther-Simple-with-esp32) | 0 | C++ | You want a good project ethical hacking with wifi deauth this repo is for you |
| 1712 | [Reuben123t/ESP-Hacker](https://github.com/Reuben123t/ESP-Hacker) | 0 | C++ | ESP32 hacking tool through Wifi and Bluetooth |
| 1713 | [rfypych/esp32-wifi-pentesting](https://github.com/rfypych/esp32-wifi-pentesting) | 0 | C |  |
| 1714 | [ridhinva/wifi-audit](https://github.com/ridhinva/wifi-audit) | 0 | Python | Tool: WiFi security auditor — WPA/WPA2/WPA3 handshake capture, PMKID, deauth, and cracking in Python |
| 1715 | [Rima333475/Esp32-wifi-scanner](https://github.com/Rima333475/Esp32-wifi-scanner) | 0 | C++ | ESP32 WiFi scanner with Evil Twin detection |
| 1716 | [riturajsingh0001/NodeMCU-WiFi-Security-Lab](https://github.com/riturajsingh0001/NodeMCU-WiFi-Security-Lab) | 0 | C++ | IoT Cybersecurity project demonstrating WiFi Evil Twin attack and deauthentication using NodeMCU … |
| 1717 | [roh7ops/ESP32-WiFi-Hacking-Lab](https://github.com/roh7ops/ESP32-WiFi-Hacking-Lab) | 0 | Python | ESP32 WiFi Hacking Lab |
| 1718 | [rooster197/wifi-deauther](https://github.com/rooster197/wifi-deauther) | 0 | — | wifi deauther |
| 1719 | [rperezll/WiFiDeauthLab](https://github.com/rperezll/WiFiDeauthLab) | 0 | — | 🧪 Laboratorio experimental diseñado para explorar y documentar ataques de Deauth en redes Wi-Fi d… |
| 1720 | [rrbaker00/BluetoothBaker](https://github.com/rrbaker00/BluetoothBaker) | 0 | C++ | A 2.4Ghz wifi and bluetooth jammer built on a ESP32 and 2 nrf24l01 antenna moduels that has multi… |
| 1721 | [Rwalhussain/WiFiTrap](https://github.com/Rwalhussain/WiFiTrap) | 0 | Python | WiFiTrap - Evil Twin Attack Simulator |
| 1722 | [ryhnmhrdka/Wraith](https://github.com/ryhnmhrdka/Wraith) | 0 | C | WiFi security auditing tool for the ESP8266 platform. It provides a set of tools for scanning, mo… |
| 1723 | [ryvoxo/RamJam-WIFI-Deauther](https://github.com/ryvoxo/RamJam-WIFI-Deauther) | 0 | — | A simple WIFI Deauther using the ESP8266, an OLED screen and 3 buttons. |
| 1724 | [sadiqgarba2553/wifi-master](https://github.com/sadiqgarba2553/wifi-master) | 0 | Python | **WiFi Master** automates aircrack-ng for wireless penetration testing. Handles monitor mode, net… |
| 1725 | [sahikkkk/PhiSiFi](https://github.com/sahikkkk/PhiSiFi) | 0 | — | WiFi Hacking with an ESP8266 - Deauth combined with Evil Twin attack  |
| 1726 | [SaidSec/Wifi-Password-Cracker](https://github.com/SaidSec/Wifi-Password-Cracker) | 0 | Shell | Greps the WPA handshake from one device after deauth attacking and cracks it with given wordlist |
| 1727 | [salahezzat120/auto_aircrack](https://github.com/salahezzat120/auto_aircrack) | 0 | Python | ⚡ Automated WiFi Handshake Capture & Cracking (for **legal lab testing only**) ⚡ |
| 1728 | [salehabbas99/ESP32-WiFi-Pentest](https://github.com/salehabbas99/ESP32-WiFi-Pentest) | 0 | C++ |  |
| 1729 | [Samoon19/ESP32-Wifi-Jammer](https://github.com/Samoon19/ESP32-Wifi-Jammer) | 0 | JavaScript |  |
| 1730 | [sangyapucharathkumar/WiFi-Phishing-Simulation-ESP8266-](https://github.com/sangyapucharathkumar/WiFi-Phishing-Simulation-ESP8266-) | 0 | C++ | WiFi Phishing Simulation is an educational project built using the ESP8266 WiFi module. The goal … |
| 1731 | [Sanj274/WiFi-Deauther-using-ESP8266](https://github.com/Sanj274/WiFi-Deauther-using-ESP8266) | 0 | C | Implemented features to scan nearby networks, select targets, and execute deauth and beacon frame… |
| 1732 | [santhoshreddy1600/esp32-deauther](https://github.com/santhoshreddy1600/esp32-deauther) | 0 | — | wifi deauther with esp32 |
| 1733 | [santipicon/WiFi-Penetration-Testing-Lab](https://github.com/santipicon/WiFi-Penetration-Testing-Lab) | 0 | — | WPA2 Handshake Capture & Cracking |
| 1734 | [Santosh-sudo-update/Wifi-deauther](https://github.com/Santosh-sudo-update/Wifi-deauther) | 0 | — | Custom ESP8266 Deauther firmware with a personalized web interface and default Wi-Fi settings.   … |
| 1735 | [sayooj2005/-WiFi-Deauther---802.11-Security-Testing-Tool](https://github.com/sayooj2005/-WiFi-Deauther---802.11-Security-Testing-Tool) | 0 | — | 802.11 deauthentication attack tool built on ESP8266 for wireless security testing. |
| 1736 | [scast3/deauth_detect](https://github.com/scast3/deauth_detect) | 0 | C++ | Detection and Localization of a Wifi deauth attack. Wireless communication between ESP32 devices … |
| 1737 | [schedutydev/ESP32-S3-WiFi-Interceptor](https://github.com/schedutydev/ESP32-S3-WiFi-Interceptor) | 0 | — | ESP32-S3 WiFi penetration testing tool - Captive Portal, Network Scanner, and Deauthentication at… |
| 1738 | [Seemab-Khan2336/Wireless-Interference-Analysis-ESP32](https://github.com/Seemab-Khan2336/Wireless-Interference-Analysis-ESP32) | 0 | Python | An experimental study on wireless interference and signal congestion in the 2.4 GHz ISM band. Usi… |
| 1739 | [shackablacka/wifi-cracking](https://github.com/shackablacka/wifi-cracking) | 0 | HTML | evil twin wifi cracking with capture portal |
| 1740 | [shahnowaz/wifi-handshake-cracker](https://github.com/shahnowaz/wifi-handshake-cracker) | 0 | — | "A complete guide and command workflow for capturing and cracking WPA/WPA2 Wi-Fi handshakes using… |
| 1741 | [Shashi552/esp32-wifi-and-web-pentest-lab](https://github.com/Shashi552/esp32-wifi-and-web-pentest-lab) | 0 | C++ |  |
| 1742 | [ShellCMD101/Blackout-2.4](https://github.com/ShellCMD101/Blackout-2.4) | 0 | C | A sophisticated embedded cybersecurity project demonstrating real-world abuse, analysis, and expl… |
| 1743 | [ShellCMD101/GHOST-WIRE-Multi-Protocol-IoT-Security-Diagnostic-Toolset](https://github.com/ShellCMD101/GHOST-WIRE-Multi-Protocol-IoT-Security-Diagnostic-Toolset) | 0 | HTML | A comprehensive, handheld IoT security diagnostic toolset built around the ESP32 platform. Ghost … |
| 1744 | [ShivamMathtech/ESP32-Dual-NRF24L01-RF-Test-Communication-Platform](https://github.com/ShivamMathtech/ESP32-Dual-NRF24L01-RF-Test-Communication-Platform) | 0 | C++ | > **Safety / legal note:** This project is documented as an RF communication and laboratory test … |
| 1745 | [Snyphix/Esp32-MultiTool](https://github.com/Snyphix/Esp32-MultiTool) | 0 | — | Educational purposes tool for wifi attacks build with esp32 with SSD1306 0.96 inch diaplay |
| 1746 | [sohamjuhin/Naughty_Man](https://github.com/sohamjuhin/Naughty_Man) | 0 | C | ESP8266 wifi deauther |
| 1747 | [sqralsnwy77-glitch/esp32-wifi-pentest-tool](https://github.com/sqralsnwy77-glitch/esp32-wifi-pentest-tool) | 0 | — |  |
| 1748 | [sridhar-sec/Advanced-Cybersecurity-Toolkit](https://github.com/sridhar-sec/Advanced-Cybersecurity-Toolkit) | 0 | Python | The Advanced Cybersecurity Toolkit is a powerful command-line tool designed for penetration teste… |
| 1749 | [Srihari-Narayan/WiFi-Security-Research](https://github.com/Srihari-Narayan/WiFi-Security-Research) | 0 | — | Performed research on WPA2 security, which involved capturing the Handshake packet and performing… |
| 1750 | [sriramnaidu2006/jammer-using-esp32](https://github.com/sriramnaidu2006/jammer-using-esp32) | 0 | — | A "jammer with ESP" generally refers to a DIY wireless interference or "deauther" project built o… |
| 1751 | [StevenSeagalStreams/Cypher32](https://github.com/StevenSeagalStreams/Cypher32) | 0 | C++ | ESP32 Lora Wifi hacking game |
| 1752 | [stricklandpreston/EvilTwin](https://github.com/stricklandpreston/EvilTwin) | 0 | — | Unfinished script to automate EvilTwin Wifi Attack using the aircrack suite. |
| 1753 | [study-room-lab/WiFi-Pentest-Kit](https://github.com/study-room-lab/WiFi-Pentest-Kit) | 0 | — | WiFi Pentest Kit is a toolkit designed for wireless network security testing and auditing. It pro… |
| 1754 | [SurhommeLee/scaryrf-plus](https://github.com/SurhommeLee/scaryrf-plus) | 0 | — | The firmware for ESP32 has WiFi, BLE and SubGHz functions. |
| 1755 | [susantks/Cam-Cypher-Dual-Recon](https://github.com/susantks/Cam-Cypher-Dual-Recon) | 0 | HTML | 2026 Ultimate WiFi & Bluetooth Pentesting Toolkit for Dual ESP32-CAM Security Audits |
| 1756 | [suvo2007/Nrfboom_Btl.](https://github.com/suvo2007/Nrfboom_Btl.) | 0 | — | NRF BOOM — an ESP32-based multi-tool for nRF24, BLE, and WiFi security testing (scanner, jammer, … |
| 1757 | [Sviatko124/wifi-wordlists](https://github.com/Sviatko124/wifi-wordlists) | 0 | — | Some wordlists I created for WiFi handshake cracking.  |
| 1758 | [swethas274/ESP8266-WiFi-DeAuther-](https://github.com/swethas274/ESP8266-WiFi-DeAuther-) | 0 | — | This project enhances ethical hacking, embedded systems, and network security skills. |
| 1759 | [SystemProgrammerWizzard/remote-monitoring-device](https://github.com/SystemProgrammerWizzard/remote-monitoring-device) | 0 | C++ | Sub-GHz LoRa GPS Beacon with Environmental Monitoring and Web Dashboard A low-power ESP32-S3 LoRa… |
| 1760 | [tehnomozg/esp32sniffing](https://github.com/tehnomozg/esp32sniffing) | 0 | — | This is a collection of ESP32 WiFi and Bluetooth sniffing tools. They're designed for use with th… |
| 1761 | [tellfride/evil-twin-wifi](https://github.com/tellfride/evil-twin-wifi) | 0 | Roff | falso wifi para coleta de dados em ESP-32 |
| 1762 | [texalpha973-rgb/Esp32-IR-RF-ble-wifi](https://github.com/texalpha973-rgb/Esp32-IR-RF-ble-wifi) | 0 | C++ |  ​1. CAPTURE IR ​2. SAVED CODES ​3. TV SWEEP ​4. AC KILLER ​5. TV ROULETTE ​6. SIGNAL FUZZER ​7. … |
| 1763 | [thefat-fox/fatfox-dual-attack-tool](https://github.com/thefat-fox/fatfox-dual-attack-tool) | 0 | Python | WiFi Deauth + Evil Twin Attack Tool |
| 1764 | [ThelzenGroup/wifistrike](https://github.com/ThelzenGroup/wifistrike) | 0 | Python | Offline Wi-Fi auditing toolkit — capture, extract, crack, and report on WPA/WPA2/WEP handshakes. … |
| 1765 | [usmanraees614-web/Evil-Twin](https://github.com/usmanraees614-web/Evil-Twin) | 0 | — | A fake wifi detector  |
| 1766 | [Vang-er/RF_series_killer](https://github.com/Vang-er/RF_series_killer) | 0 | — | it is a firmware that you lanuch on an esp32  and it starts to deauthincate all the nearby APs ra… |
| 1767 | [vigiled/vigiled](https://github.com/vigiled/vigiled) | 0 | C++ | VIGILED is an open-source RGB LED device that turns your dashcam into an active visual deterrent.… |
| 1768 | [webermohit/wifi_jammer](https://github.com/webermohit/wifi_jammer) | 0 | — | Wi-Fi Jammer using Node MCU ESP8266 |
| 1769 | [willlccasey/kali-wifite](https://github.com/willlccasey/kali-wifite) | 0 | Python | Wifite Wi-Fi auditor — GUI launcher with offline handshake cracking |
| 1770 | [worm00dat/wifireaper](https://github.com/worm00dat/wifireaper) | 0 | — | AIO Evil Twin Attack |
| 1771 | [Xhanos0/esp32-bleujammer-board-emensta-](https://github.com/Xhanos0/esp32-bleujammer-board-emensta-) | 0 | — | this is a circle vercion of the esp32 ble/low ble/wifi/rc jammer (its not my project but i tought… |
| 1772 | [yashwanth270405-creator/ESP32-WiFi-Bluetooth-Jammer](https://github.com/yashwanth270405-creator/ESP32-WiFi-Bluetooth-Jammer) | 0 | — | ESP32-based BLE and Bluetooth jammer project for studying wireless communication, signal interfer… |
| 1773 | [Yogi-076/ESP32-Evil-Twin-Wifi-Phishing](https://github.com/Yogi-076/ESP32-Evil-Twin-Wifi-Phishing) | 0 | HTML | Using ESP32 Wroom 32 module , Evil twin/wifi Phishing attack |
| 1774 | [yohannesfanuel936-cpu/esp32s3-beacon-spammer](https://github.com/yohannesfanuel936-cpu/esp32s3-beacon-spammer) | 0 | C++ | this project its main function is using an esp 32 s3 for an attack called bacon spamming what thi… |
| 1775 | [zero7608/wifi-dojo](https://github.com/zero7608/wifi-dojo) | 0 | C | Pocket-sized ESP32-C6 WiFi practice lab: a target AP and a companion attacker that generates 4-wa… |
| 1776 | [zneroravi/Wifi-jammer](https://github.com/zneroravi/Wifi-jammer) | 0 | — | wifi jammer with nodemcu esp8266 |

### 蓝牙攻击

> 共 **390** 个项目，按 Stars 降序排列。多标签项目会出现在多个分组。

| # | 项目 | Stars | 语言 | 简介 |
|---:|---|---:|---|---|
| 1 | [bettercap/bettercap](https://github.com/bettercap/bettercap) | 20,304 | Go | The Swiss Army knife for 802.11, BLE, HID, CAN-bus, IPv4 and IPv6 networks reconnaissance and MIT… |
| 2 | [SpacehuhnTech/esp8266_deauther](https://github.com/SpacehuhnTech/esp8266_deauther) | 15,109 | C | Affordable WiFi hacking platform for testing and learning |
| 3 | [EmenstaNougat/ESP32-BlueJammer](https://github.com/EmenstaNougat/ESP32-BlueJammer) | 8,931 | — | The ESP32-BlueJammer (Bluetooth jammer, BLE jammer, WiFi jammer, RC jammer) disrupts 2.4GHz commu… |
| 4 | [cifertech/ESP32-DIV](https://github.com/cifertech/ESP32-DIV) | 4,350 | C++ | ESP32DIV is a multi-purpose wireless offensive and defensive toolkit powered by an ESP32 |
| 5 | [cirosantilli/china-dictatorship](https://github.com/cirosantilli/china-dictatorship) | 3,350 | HTML | 反中共政治宣传库。Anti Chinese government propaganda. 住在中国真名用户的网友请别给星星，不然你要被警察请喝茶。常见问答集，新闻集和饭店和音乐建议。卐习万岁卐。… |
| 6 | [7h30th3r0n3/Evil-M5Project](https://github.com/7h30th3r0n3/Evil-M5Project) | 2,887 | C++ | Evil-M5Project is an innovative tool developed for ethical  hacking and exploration of WiFi netwo… |
| 7 | [cifertech/nRFBox](https://github.com/cifertech/nRFBox) | 2,140 | C++ | Open-source ESP32-powered tool to scan, jam, spoof, and master BLE, Wi-Fi, and 2.4GHz networks. |
| 8 | [gege-circle/.github](https://github.com/gege-circle/.github) | 2,106 | — | 这里是GitHub的草场，也是戈戈圈爱好者的交流地，主要讨论动漫、游戏、科技、人文、生活等所有话题，欢迎各位小伙伴们在此讨论趣事。This is GitHub grassland, and th… |
| 9 | [cifertech/RF-Clown](https://github.com/cifertech/RF-Clown) | 1,945 | C++ | BLE and Bluetooth Jammer with nRF24L01 and ESP32 |
| 10 | [xploitstech/Xteam](https://github.com/xploitstech/Xteam) | 1,365 | Python | Xteam All in one Instagram,Android,phishing osint and wifi hacking tool available  |
| 11 | [GhostESP-Revival/GhostESP](https://github.com/GhostESP-Revival/GhostESP) | 1,162 | C | The open-source wireless research platform for ESP32. |
| 12 | [W0rthlessS0ul/nRF24_jammer](https://github.com/W0rthlessS0ul/nRF24_jammer) | 1,022 | C | The nRF24 jammer is a powerful tool that requires an ESP32 and configurable numbers of NRF24 modu… |
| 13 | [Cyber-Dioxide/Wifi-Brute](https://github.com/Cyber-Dioxide/Wifi-Brute) | 780 | Python | A tool to crack a wifi password with a help of wordlist. This may take long to crack a wifi depen… |
| 14 | [landy22granatt/Kumpulan-Script-Termux](https://github.com/landy22granatt/Kumpulan-Script-Termux) | 776 | Python | Ok, Langsung Saja Ke Materi. Sesuai Judul, Disini Saya Akan Memberikan Kumpulan Script Termux Yan… |
| 15 | [Matheus-Garbelini/esp32_bluetooth_classic_sniffer](https://github.com/Matheus-Garbelini/esp32_bluetooth_classic_sniffer) | 617 | C | Active Bluetooth BR/EDR Sniffer/Injector as cheap as any ESP32 board can get. Works with Scapy ;-) |
| 16 | [Taoviqinvicible/Tools-termux](https://github.com/Taoviqinvicible/Tools-termux) | 606 | — | 1.[Script Termux] -Cmatrix *apt-get update *apt-get upgrade *apt-get install nmap *apt-get instal… |
| 17 | [Matheus-Garbelini/braktooth_esp32_bluetooth_classic_attacks](https://github.com/Matheus-Garbelini/braktooth_esp32_bluetooth_classic_attacks) | 599 | — | A Series of Baseband & LMP Exploits against Bluetooth Classic Controllers |
| 18 | [HighCodeh/TentacleOS](https://github.com/HighCodeh/TentacleOS) | 512 | C | Firmware High Boy |
| 19 | [priyankgada/The-Complete-Practical-Certified-Ethical-Hacking-Course-in-English](https://github.com/priyankgada/The-Complete-Practical-Certified-Ethical-Hacking-Course-in-English) | 490 | — | Welcome this comprehensive course on Ethical Hacking! This course assumes you have NO prior knowl… |
| 20 | [mcore1976/cc1101-tool](https://github.com/mcore1976/cc1101-tool) | 489 | C++ | RF tool based on CC1101 module and Arduino Pro Micro 8VMHz/3.3V. Allows using CLI with human read… |
| 21 | [uday-khan/Termux](https://github.com/uday-khan/Termux) | 463 | — | KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau hp lu gw… |
| 22 | [whatotter/pwnhyve](https://github.com/whatotter/pwnhyve) | 460 | Python | A low cost, jack-of-all-trades hacking tool, taking inspiration from FlipperZero and P4wnP1, usin… |
| 23 | [cirosantilli/china-dictatroship-7](https://github.com/cirosantilli/china-dictatroship-7) | 391 | HTML | 反中共政治宣传库。Anti Chinese government propaganda. https://github.com/cirosantilli/china-dictatorship 的… |
| 24 | [W0rthlessS0ul/FZ_nRF24_jammer](https://github.com/W0rthlessS0ul/FZ_nRF24_jammer) | 388 | C | The Flipper Zero nRF24 jammer is a powerful tool that requires an Flipper Zero and nRF24 module t… |
| 25 | [tnt-wolve/ch3r0](https://github.com/tnt-wolve/ch3r0) | 333 | — | Hackingtool Menu 🧰 AnonSurf Information Gathering Password Attack Wireless Attack SQL Injection T… |
| 26 | [EmenstaNougat/BlueJammer-V2](https://github.com/EmenstaNougat/BlueJammer-V2) | 322 | Batchfile | BlueJammer-V2 is a two-board RF research platform combining an ESP32 jamming engine with a BW16 5… |
| 27 | [psyb0t/piraterf](https://github.com/psyb0t/piraterf) | 291 | Go | PIrateRF transforms your Raspberry Pi Zero W into a portable RF signal generator that spawns its … |
| 28 | [DeaDHackS/WiFiSpy](https://github.com/DeaDHackS/WiFiSpy) | 247 | Python | The best WiFi spy avalaible for hire! Made for hackers, for hackers |
| 29 | [justcallmekoko/MarauderCentauri](https://github.com/justcallmekoko/MarauderCentauri) | 238 | C++ | A suite of WiFi/Bluetooth offensive and defensive tools for the ESP32 and ESP8266 |
| 30 | [mRFWq7LwNPZjaVv5v6eo/cihna-dictattorshrip-8](https://github.com/mRFWq7LwNPZjaVv5v6eo/cihna-dictattorshrip-8) | 217 | HTML | 反中共政治宣传库。Anti Chinese government propaganda. https://github.com/cirosantilli/china-dictatorship 的… |
| 31 | [panbinibn/OpenPacketFix_](https://github.com/panbinibn/OpenPacketFix_) | 215 | — | 大陆修宪香港恶法台湾武统朝鲜毁约美中冷战等都是王沪宁愚弄习思想极左命运共同体的大策划中共窃国这半个多世纪所犯下的滔天罪恶，前期是毛泽东策划的，中期6.4前后是邓小平策划的，黄牛数据分析后期是毛的… |
| 32 | [BlackTechX011/DeautherX](https://github.com/BlackTechX011/DeautherX) | 210 | C | An open-source ESP8266_Deauther with customizable Evil Twin attack, and WiFi signal strength chec… |
| 33 | [PentHertz/grimoire](https://github.com/PentHertz/grimoire) | 206 | Python | Offensive knowledge, offline. One search box for every playbook. |
| 34 | [Rizalcahdemak/akun-termux](https://github.com/Rizalcahdemak/akun-termux) | 198 | — | Skip to content arysandi/kumpulan kode di termux Created 3 years ago • Report abuse Code Revision… |
| 35 | [Electro-Gamma/ESP32-Quad-nRF24L01-Plus-Jammer-Multi-Band-2-4GHz-RF-Controller](https://github.com/Electro-Gamma/ESP32-Quad-nRF24L01-Plus-Jammer-Multi-Band-2-4GHz-RF-Controller) | 192 | C++ | ESP32-Quad-nRF24L01-Plus-Jammer is an open-source project for controlling four nRF24L01+ modules … |
| 36 | [pepeangell5/ESP32-TOOLS-PRO-480x320-V2.0](https://github.com/pepeangell5/ESP32-TOOLS-PRO-480x320-V2.0) | 191 | C++ | ESP32-TOOLS-PRO-480x320-V2.0 expande la V1.0 con soporte para módulos IR M5Stack y CC1101. Añade … |
| 37 | [ElectronicCats/BomberCat](https://github.com/ElectronicCats/BomberCat) | 186 | HTML | BomberCat is the latest security tool that combines the most common card technologies: NFC techno… |
| 38 | [ElectronicCats/Minino](https://github.com/ElectronicCats/Minino) | 183 | C++ | Minino is an original multiprotocol and multiband board made for sniffing, communicating, and att… |
| 39 | [dkyazzentwatwa/cypher-jammer-mini](https://github.com/dkyazzentwatwa/cypher-jammer-mini) | 182 | C++ | Tiny WiFi + Bluetooth Jammer w/ ESP32-C3 SuperMini |
| 40 | [Don-No7/Hack-SQL](https://github.com/Don-No7/Hack-SQL) | 153 | — | -- -- File generated with SQLiteStudio v3.2.1 on Sun Feb 7 14:58:28 2021 -- -- Text encoding used… |
| 41 | [Mxtiv/BlueJammer](https://github.com/Mxtiv/BlueJammer) | 136 | C++ | Simple BlueJammer using ESP32 and nRF24L01. For educational purposes only! |
| 42 | [zpc1314521/PCL2](https://github.com/zpc1314521/PCL2) | 135 | — | [stays mad] 反PCL宣传库。Anti PCL propaganda. 大陆修宪香港恶法台湾武统朝鲜毁约美中冷战等都是王沪宁愚弄习思想极左命运共同体的大策划中共窃国这半个多世纪所犯下的… |
| 43 | [EmenstaNougat/C3Mini-BlueJammer](https://github.com/EmenstaNougat/C3Mini-BlueJammer) | 125 | — | The C3Mini-BlueJammer (MINI FORMFACTOR) (Bluetooth jammer, BLE jammer, WiFi jammer, RC jammer) di… |
| 44 | [ezhil56x/Wifi-Deauthentication-Tool](https://github.com/ezhil56x/Wifi-Deauthentication-Tool) | 117 | Shell | Wi-Fi Deauthentication Tool is a command-line utility for educational purposes, enabling users to… |
| 45 | [bkerler/DroneID](https://github.com/bkerler/DroneID) | 113 | Python | OpenDrone ID sniffer/spoofer for Bluetooth + WIFI |
| 46 | [zall-4RT/kumpulan-code-termuxs-lenkap](https://github.com/zall-4RT/kumpulan-code-termuxs-lenkap) | 108 | — | termux KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau h… |
| 47 | [PNKP237/EHU32](https://github.com/PNKP237/EHU32) | 103 | C++ | ESP32-based bluetooth audio integration for Opel/Vauxhall vehicles. Control bluetooth audio sourc… |
| 48 | [iamhellaweiri/EXPLOIT-FRAMEWORK-v1.0](https://github.com/iamhellaweiri/EXPLOIT-FRAMEWORK-v1.0) | 100 | Python | EXPLOIT-FRAMEWORK is a very powerfull hacking tool and have dangerous hacks like  Payload Creator… |
| 49 | [OzInFl/WaveSentinelPublic---Squareline-Studio-UI-CC1101---ESP32](https://github.com/OzInFl/WaveSentinelPublic---Squareline-Studio-UI-CC1101---ESP32) | 100 | C | WT32-SC01-PLUS Module With SubGhz, Wifi and Bluetooth - Using CC1101, Able to play .sub files fro… |
| 50 | [trmxvibs/wifi-audit-tool](https://github.com/trmxvibs/wifi-audit-tool) | 87 | Python | A user-friendly command-line toolkit for WiFi network scanning, handshake capture, and vulnerabil… |
| 51 | [infobyte/doggie](https://github.com/infobyte/doggie) | 83 | Rust | Welcome to the Doggie and EvilDoggie repository by Faraday Security! Doggie is a modular DIY CAN … |
| 52 | [colonelpanichacks/Esp32-oui-sniffer](https://github.com/colonelpanichacks/Esp32-oui-sniffer) | 81 | C++ | BLE/WiFi detection over mesh |
| 53 | [pingequalab/5ghost-wifi-lab](https://github.com/pingequalab/5ghost-wifi-lab) | 77 | C | Dual-band 2.4/5 GHz Wi-Fi research tool for the Flipper Zero, built on the Realtek RTL8720DN (BW1… |
| 54 | [hackcrypto/fluxion](https://github.com/hackcrypto/fluxion) | 75 | Shell | Fluxion is a security auditing and social-engineering research tool. It is a remake of linset by … |
| 55 | [linkp2p/WPS-PIN](https://github.com/linkp2p/WPS-PIN) | 72 | Shell |  # This scripts is edited under the General Public License as defined by the Free software founda… |
| 56 | [michelangelomo/marauder-ui](https://github.com/michelangelomo/marauder-ui) | 69 | Vue | A modern web interface for the ESP32 Marauder firmware. |
| 57 | [wahid987654321/hecker](https://github.com/wahid987654321/hecker) | 64 | — | KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau hp lu gw… |
| 58 | [NSM-Barii/Yoda](https://github.com/NSM-Barii/Yoda) | 49 | Python | Passive RF monitor — real-time WiFi and BLE surveillance with deauth detection, device tracking, … |
| 59 | [Linuxndroid/Bluetooth-Ducky](https://github.com/Linuxndroid/Bluetooth-Ducky) | 47 | C++ | Bluetooth Ducky is a stealthy HID injection tool built on the ESP32 platform. It emulates a Bluet… |
| 60 | [shizakken/cheetah](https://github.com/shizakken/cheetah) | 44 | Rust | Portable WiFi/Bluetooth/RF-433MHz hacking tool |
| 61 | [soynx/Hacking-PenTesting-Utils](https://github.com/soynx/Hacking-PenTesting-Utils) | 44 | HTML | A collection of scripts, documentation and HTML-Sites that can be used for penetration-testing |
| 62 | [MuhamadJalalDev/ESP32-WiFi-Bluetooth-Jammer](https://github.com/MuhamadJalalDev/ESP32-WiFi-Bluetooth-Jammer) | 38 | — | Wi-Fi and Bluetooth jamming using an ESP32 microcontroller and NRF24L01 modules. This project inc… |
| 63 | [barryblueice/ESP32-Haptic-Precision-TouchPad](https://github.com/barryblueice/ESP32-Haptic-Precision-TouchPad) | 37 | C | Another touchpad hacking project, based on ESP32-S3 + Surface Laptop Studio 1964 Synaptics TouchPad. |
| 64 | [h9zdev/EthiFi](https://github.com/h9zdev/EthiFi) | 37 | C | EthiFi is a affordable WiFi pentesting platform for testing and learning  |
| 65 | [KaraZajac/OVERWATCH](https://github.com/KaraZajac/OVERWATCH) | 37 | Kotlin | Android app that flags nearby Flock ALPRs, Axon body cams, police and surveillance aircraft from … |
| 66 | [KEI4251/ESP32-Jammer-](https://github.com/KEI4251/ESP32-Jammer-) | 37 | — | KEI JAMMER – A personal project focused on experimenting with wireless security using ESP32 and N… |
| 67 | [rootsaid/ducky_over_wifi](https://github.com/rootsaid/ducky_over_wifi) | 37 | Arduino | HID or Human Interface Devices are Devices that takes input from human and pass it on to the devi… |
| 68 | [Woofydude/wifi_mitm](https://github.com/Woofydude/wifi_mitm) | 36 | C++ | for flipper zero, it is a man-in-the-middle app to be able to spoof a network name and get passwo… |
| 69 | [leo-aa88/wifi-jammer](https://github.com/leo-aa88/wifi-jammer) | 35 | Python | Continuously perform deauthentication attacks on all detectable stations |
| 70 | [Isonimus/adversary](https://github.com/Isonimus/adversary) | 34 | C++ | Red-team wireless pentesting firmware for the ESP32. Audit WiFi, BLE, IR, Sub-GHz, 2.4 GHz, RFID. |
| 71 | [valleytechsolutions/Skid-Detector](https://github.com/valleytechsolutions/Skid-Detector) | 34 | C++ | A wireless LED mood light and passive network security monitor built on the Seeed Studio XIAO ESP… |
| 72 | [chkndrp/ESPnRF24-Jammer](https://github.com/chkndrp/ESPnRF24-Jammer) | 33 | C++ | A low-power 2,4GHz wireless jammer based on ESP32 and nRF24LO1+PA+LNA (PlatformIO) |
| 73 | [M0M0Sec/MoMo](https://github.com/M0M0Sec/MoMo) | 33 | Python | 🎯 Pi 5 Wardriving & Wireless Pentest Platform \| WiFi/BLE/SDR Attacks \| WPA3 • Evil Twin • Karma… |
| 74 | [0day1day/Slave_I](https://github.com/0day1day/Slave_I) | 32 | C | Offensive-security firmware for the M5Stack Tab5 — browser-flashable Wi-Fi / BLE / 802.15.4 recon… |
| 75 | [sllumenikmati21/misteriusxx](https://github.com/sllumenikmati21/misteriusxx) | 32 | — | KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau hp lu gw… |
| 76 | [ASP-29/ZeroX32](https://github.com/ASP-29/ZeroX32) | 29 | HTML | The Multi-tool device has a lot of feature,including WIFi,Bluetooth,HID,Infrared,Sub-Ghz,NRF24L01… |
| 77 | [stetro/ngn-sniffer](https://github.com/stetro/ngn-sniffer) | 29 | CSS | Android APP for NGN to sniff location based rf signals like GSM, Bluetooth or Wifi  |
| 78 | [tajmancrackit/How-to-install-kali-nethunter-in-termux](https://github.com/tajmancrackit/How-to-install-kali-nethunter-in-termux) | 29 | — | What is Kali Nethunter?  Kali Nethunter is a Android ROM which is designed for Penetration Testin… |
| 79 | [ruvnet/wifi-veil](https://github.com/ruvnet/wifi-veil) | 27 | Rust | WiFi Veil — a privacy firewall against unauthorized WiFi sensing. Compliant waveform controls onl… |
| 80 | [taufiks22/new](https://github.com/taufiks22/new) | 27 | — | KUMPULAN CODE TERMUX LENGKAP   \| SPAM CHAT WHATSAPP \|\| nggk usah nyepam gw -_*   atau hp lu gw… |
| 81 | [dkyazzentwatwa/cypher-jammer-2nrf-oled](https://github.com/dkyazzentwatwa/cypher-jammer-2nrf-oled) | 26 | C++ | A wifi/bluetooth jammer with an oled screen and buttons. |
| 82 | [GeneralDussDuss/poseidon-tembed](https://github.com/GeneralDussDuss/poseidon-tembed) | 26 | Python | POSEIDON for the LilyGO T-Embed CC1101 Plus - 128 features, 5 onboard radios, browser flasher |
| 83 | [Hacker-World0/Wifi-Jammer](https://github.com/Hacker-World0/Wifi-Jammer) | 26 | Python | These are favored by companies who deal with sensitive information to prevent leaks. The 5GHz WiF… |
| 84 | [whitewhidow/bboink](https://github.com/whitewhidow/bboink) | 26 | C++ | WiFi handshake/PMKID capture firmware for ESP32 — LilyGo T-Embed CC1101, T-Display C5 & Waveshare… |
| 85 | [wickednull/KTOX_Pi](https://github.com/wickednull/KTOX_Pi) | 26 | Python | KTOx_Pi — Network penetration & purple team suite for Raspberry Pi Zero 2W. Joystick-controlled L… |
| 86 | [krakeninfosec/cyber-noise-blaster](https://github.com/krakeninfosec/cyber-noise-blaster) | 25 | HTML | Noise-based 2.4GHz jammer using ESP32 and NRF24L01 to disrupt Bluetooth, BLE, WiFi, and drone sig… |
| 87 | [Emersonmafra/f](https://github.com/Emersonmafra/f) | 22 | — | #!/bin/bash  ########## DEBUG Mode ########## if [ -z ${FLUX_DEBUG+x} ]; then FLUX_DEBUG=0     el… |
| 88 | [kxyznew/WiFi-Pineapple-Pager-Master-Control-Suite](https://github.com/kxyznew/WiFi-Pineapple-Pager-Master-Control-Suite) | 22 | Python | ## Key Features: - **Tri-Band Attacks**: 2.4GHz, 5GHz, 6GHz simultaneous operations - **Autonomou… |
| 89 | [ElmanTr/python-wifi-hack-with-subprocess](https://github.com/ElmanTr/python-wifi-hack-with-subprocess) | 21 | Python | A simple program with Python to hack WiFi ! getting WiFi information and passwords from CMD by su… |
| 90 | [GthiN89/NucleusGateKeeper](https://github.com/GthiN89/NucleusGateKeeper) | 20 | C++ | Nucleus Gate Keeper is a specialized, compact, and cost-effective device for capturing Sub-GHz RF… |
| 91 | [Rubbles-eh/Direwolf_3.5CYD](https://github.com/Rubbles-eh/Direwolf_3.5CYD) | 20 | Python | Multi Device Case for 3.5" CYD with modular options for use with common firmware's (Halehound, Br… |
| 92 | [dotberg/pwnagotchi-zero](https://github.com/dotberg/pwnagotchi-zero) | 19 | Java | Autonomous AI-driven WiFi security tool for rooted Android. Native Qualcomm monitor mode, Thompso… |
| 93 | [GoatsAndMonkeys/monster_mesh](https://github.com/GoatsAndMonkeys/monster_mesh) | 19 | C++ | MonsterMesh: a Game Boy emulator, Gen-1 monster-battling RPG, and WiFi/BLE 'Pentest Pikachu' secu… |
| 94 | [Th3-Priest/vigilance](https://github.com/Th3-Priest/vigilance) | 19 | C++ | Defensive surveillance HUD firmware for the LilyGo T-Embed CC1101 Plus (a Bruce fork). |
| 95 | [Mausam678/wifi-jammer-tool-for-esp32](https://github.com/Mausam678/wifi-jammer-tool-for-esp32) | 18 | — | This tool is a binary firmware designed for the ESP32 microcontroller, enabling it to perform WiF… |
| 96 | [82goober82/fluxionwpacrack](https://github.com/82goober82/fluxionwpacrack) | 17 | Shell | Fluxion is the future of MITM WPA attacks  Fluxion is a security auditing and social-engineering … |
| 97 | [CapibaraZero/BLESniffer](https://github.com/CapibaraZero/BLESniffer) | 17 | C++ | A bluetooth sniffer for ESP32 |
| 98 | [nturmose21/MKCOZMO-CONTROLLER](https://github.com/nturmose21/MKCOZMO-CONTROLLER) | 15 | C | A Cozmo-inspired mini robot built on ESP32 with continuous-rotation servos, Bluetooth Xbox contro… |
| 99 | [JNDreviews/est-Smartphones-under-Rs.15000-](https://github.com/JNDreviews/est-Smartphones-under-Rs.15000-) | 14 | — | WHICH ARE THE BEST SMARTPHONES UNDER 15000 . Best Smartphones under Rs.15000 models 2021  Step by… |
| 100 | [sidward35/Deauth-RickRollAP](https://github.com/sidward35/Deauth-RickRollAP) | 14 | Arduino | Performs a deauth attack and sends beacon frames to flood the list of available WiFi networks wit… |
| 101 | [7wp81x/NRSuite-firmware](https://github.com/7wp81x/NRSuite-firmware) | 13 | C++ | ESP32 firmware for the NRSuite security research toolkit. Wi-Fi/BLE attack and capture modules (d… |
| 102 | [danya201272/ESP32-4M-WiFi-BLSerial-433Mhz](https://github.com/danya201272/ESP32-4M-WiFi-BLSerial-433Mhz) | 13 | C++ | ESP32 with app interface remoteXY and grab and sent code. Bruteforce Came and Nice. Have a Jammer… |
| 103 | [demining/Bluetooth-Attacks-CVE-2025-27840](https://github.com/demining/Bluetooth-Attacks-CVE-2025-27840) | 13 | Jupyter Notebook | Bitcoin Cryptanalysis: CVE-2025-27840 Vulnerability in ESP32 Microcontrollers Puts Billions of Io… |
| 104 | [Derek1ization/Hack-pack-ON-STRIOD-2020](https://github.com/Derek1ization/Hack-pack-ON-STRIOD-2020) | 13 | — | Tools that i have gatherd and study to see how thay work and learned why theses tools execute the… |
| 105 | [EMLGaming/handshakestealer](https://github.com/EMLGaming/handshakestealer) | 13 | Shell | This is just a basic script that steals handshakes and cleans them this can then be used to crack… |
| 106 | [ginanjaradit354/wifi-hacker](https://github.com/ginanjaradit354/wifi-hacker) | 13 | — | #!/bin/bash#############################################################################   CREDIT… |
| 107 | [Whomrx666/Xdeauth-owner](https://github.com/Whomrx666/Xdeauth-owner) | 13 | Python | Xdeauth-owner is a tool that can place us as the owner of the WiFi by being able to determine who… |
| 108 | [dfalt0/NodeMCU-ESP8266](https://github.com/dfalt0/NodeMCU-ESP8266) | 12 | C | This software allows you to perform a deauth attack with an ESP8266 against selected networks. Th… |
| 109 | [godragun/Marauder-ESP32-S3](https://github.com/godragun/Marauder-ESP32-S3) | 12 | C++ | 📡 ESP32 Marauder v1.11.0 compiled for XIAO ESP32-S3 — WiFi security testing, BLE scanning, and et… |
| 110 | [imayavaramban11/2.4Ghz-Jammer](https://github.com/imayavaramban11/2.4Ghz-Jammer) | 12 | — | 2.4GHz RF Interference Generator — ESP32 + nRF24L01+ A dual-channel 2.4GHz RF noise generator usi… |
| 111 | [rgomez31UAQ/Poseidon-Cardputer-Adv_Firmware](https://github.com/rgomez31UAQ/Poseidon-Cardputer-Adv_Firmware) | 12 | C++ | Firmware de pruebas de penetración con más de 80 funciones para M5Stack Cardputer-Adv. WiFi, BLE,… |
| 112 | [82goober82/fluxionwpa2](https://github.com/82goober82/fluxionwpa2) | 11 | — | Fluxion is the future of MITM WPA attacks  Fluxion is a security auditing and social-engineering … |
| 113 | [cr4sh-me2/aura](https://github.com/cr4sh-me2/aura) | 11 | Shell | An easy user interface for pentesting tools |
| 114 | [egefeyzioglu/Long-Range-RFID-Sniffer](https://github.com/egefeyzioglu/Long-Range-RFID-Sniffer) | 11 | C++ | Reads RFID cards from a long/medium distance, and displays the card IDs on a web page on a WiFi n… |
| 115 | [Epickitrolaz/nRF24-Jammer](https://github.com/Epickitrolaz/nRF24-Jammer) | 11 | C++ | A very simple, optimized ESP32 Wroom + nRF24 bluetooth jammer |
| 116 | [Farizrmd/esp32-serangan](https://github.com/Farizrmd/esp32-serangan) | 11 | C++ | ESP32 BT/WiFi Attack Tool v2 MEGA - 16 attack modes (BLE Scanner, Deauth, A2DP Jam, Spam, WiFi De… |
| 117 | [0xtosh/t-dongle-s3-wifi-guard](https://github.com/0xtosh/t-dongle-s3-wifi-guard) | 10 | PowerShell | Portable passive deauthentication attack detector for 2.4Ghz WiFi networks for LilyGO T-Dongle-S3 |
| 118 | [darkLabz001/ghosttap](https://github.com/darkLabz001/ghosttap) | 10 | C | GhostTap — Wi-Fi/BLE/Zigbee pentest field unit for the Waveshare ESP32-C5-LCD-1.47: scan, sniff, … |
| 119 | [iCounterBOX/ESP32_WiFi_SNIFF_BLE_ANDROID-APP_PathFinderLE_V01](https://github.com/iCounterBOX/ESP32_WiFi_SNIFF_BLE_ANDROID-APP_PathFinderLE_V01) | 10 | C++ | esp32 as wifi Sniffer connected via BLE to Android-App |
| 120 | [rgomez31UAQ/Poseidon_Cardputer-ADV_Firmware](https://github.com/rgomez31UAQ/Poseidon_Cardputer-ADV_Firmware) | 10 | — | Firmware de pruebas de penetración con más de 80 funciones para M5Stack Cardputer-Adv. WiFi, BLE,… |
| 121 | [AtherNet29/BW-16-RTL8720DN-DEAUTHER-EVILTWIN-NRF24](https://github.com/AtherNet29/BW-16-RTL8720DN-DEAUTHER-EVILTWIN-NRF24) | 9 | — | Advanced WiFi (2.4GHz & 5GHz) & Bluetooth Security Audit Tool Single-module design integrating du… |
| 122 | [Cem-Bas/jammer-detector-flipper-zero](https://github.com/Cem-Bas/jammer-detector-flipper-zero) | 9 | Dart | Dual-band RF jammer detector for Flipper Zero + Flutter companion app — Sub-GHz (315-915 MHz) + W… |
| 123 | [davlaura/void-esp32-jammer](https://github.com/davlaura/void-esp32-jammer) | 9 | C++ | Project "void": Jammer based on ESP32 and nRF24L01 module that generates interference in the Blue… |
| 124 | [koua29/bruce-ble-finder](https://github.com/koua29/bruce-ble-finder) | 9 | JavaScript | Traqueur de proximité Bluetooth (radar RSSI, script JS) pour le firmware Bruce — LilyGO T-Embed C… |
| 125 | [mynameisnotjohnny/the-jester](https://github.com/mynameisnotjohnny/the-jester) | 9 | C++ | A fully open-source Bluetooth and BLE jammer based on the RF-Clown project by cifertech. This imp… |
| 126 | [rusyln/ESP32-S3-ePaper-1.54-SigBin](https://github.com/rusyln/ESP32-S3-ePaper-1.54-SigBin) | 9 | — | Passive WiFi & BLE recon on a 1.54" e-paper display. PCAP harvest, handshake/PMKID capture, deaut… |
| 127 | [starminPIX/sh-kitty](https://github.com/starminPIX/sh-kitty) | 9 | — | sh-kitty is a black hat/grey hat tool it has many options that are great for many things you have… |
| 128 | [0x0806/wifi-deauther-esp8266](https://github.com/0x0806/wifi-deauther-esp8266) | 8 | C++ | This comprehensive suite combines cutting-edge WiFi attack vectors, Bluetooth Low Energy (BLE) ca… |
| 129 | [Aayush9029/esp8266_deauther](https://github.com/Aayush9029/esp8266_deauther) | 8 | — | Affordable WiFi hacking platform for testing and learning + Native iOS, watchOS support. |
| 130 | [bishwabikash/wifi-autopwn](https://github.com/bishwabikash/wifi-autopwn) | 8 | Shell | WiFi Auto-PWN v1.0 - Advanced Multi-Generation WiFi Penetration Testing Framework \| Complete cov… |
| 131 | [blwhit/WifiReaper](https://github.com/blwhit/WifiReaper) | 8 | Shell | Automate large-scale Wi-Fi deauthentication attacks. Automatically discover vulnerable wireless n… |
| 132 | [Dextelktro/Black-Crow-ESP32-C5-Firmware](https://github.com/Dextelktro/Black-Crow-ESP32-C5-Firmware) | 8 | C++ | BC Firmware ESP32 C5-Deauth dengan Nuker untuk 2.4Ghz dan 5Ghz yang dikendalikan oleh BLE dengan … |
| 133 | [Evil0ctopus/wigglefish](https://github.com/Evil0ctopus/wigglefish) | 8 | Kotlin | Passive Wi-Fi/BLE field scanner: ESP32-C5 + Android USB controller — metadata-only, authorized ob… |
| 134 | [nistordarius26h-ship-it/esp32jamm](https://github.com/nistordarius26h-ship-it/esp32jamm) | 8 | C++ | ESP32 Multi-Protocol Wireless Sniffing Platform for passive Wi-Fi, Bluetooth, BLE, and RF signal … |
| 135 | [omairtemurian/Roadstar-TV---IR](https://github.com/omairtemurian/Roadstar-TV---IR) | 8 | — | 📡 Road Star RF Controller for Lilygo T-Embed This repository contains the firmware and web-based … |
| 136 | [Ro9ueAdmin/wifi-cracking-dictionary-attack-](https://github.com/Ro9ueAdmin/wifi-cracking-dictionary-attack-) | 8 | — | 1.airmon-ng (to know status of N/W) 2.airmon-ng start wlan0 (to enable monitor mode) 3.airodump-n… |
| 137 | [Theus-Vieira/jammer_2.4ghz_wifi_bluetooth](https://github.com/Theus-Vieira/jammer_2.4ghz_wifi_bluetooth) | 8 | C++ | Projeto de Jammer 2.4 GHz wifi e bluetooth utilizando um ESP32S WROOM e dois módulos nRF24L01. Pr… |
| 138 | [5h4d0wn1k/h2-ble-tracker](https://github.com/5h4d0wn1k/h2-ble-tracker) | 7 | C++ | BLE tracker and sniffer - Bluetooth Low Energy advertising scanning and device fingerprinting. |
| 139 | [ANIMAALS/WatchDog-2.4](https://github.com/ANIMAALS/WatchDog-2.4) | 7 | C++ | Portable 2.4 GHz wireless security analyser — ESP32 + nRF24L01. Jammer detection, BLE tracker ID,… |
| 140 | [Ares-21/AeroSpy](https://github.com/Ares-21/AeroSpy) | 7 | Python | A simple WiFi scanning GUI for scanning the available wireless networks  |
| 141 | [cx693/Rust_ESP32_Dome](https://github.com/cx693/Rust_ESP32_Dome) | 7 | Rust | A collection of Rust bare-metal examples for ESP32 using the `esp-hal` framework. Covers GPIO, UA… |
| 142 | [Eberth-sys/Deauth-Alert-WiFi-IoT-System](https://github.com/Eberth-sys/Deauth-Alert-WiFi-IoT-System) | 7 | TypeScript | Open-source defensive IoT system for real-time detection and alerting of Wi-Fi 802.11 deauthentic… |
| 143 | [MOG-Developing/MOG-BLEJAMMER](https://github.com/MOG-Developing/MOG-BLEJAMMER) | 7 | C++ | MOG-BLEJAMMER |
| 144 | [touhidshaikh/Wireless-Pentest-Cheatsheet](https://github.com/touhidshaikh/Wireless-Pentest-Cheatsheet) | 7 | — | The Wireless Pentest cheat sheet was created to provide concise collection of high value informat… |
| 145 | [0xIDA/ESP-SEC-TOOL](https://github.com/0xIDA/ESP-SEC-TOOL) | 6 | C | ESP32 WiFi/BLE Security Testing Toolkit - portable wireless auditing tool with mobile web dashboard |
| 146 | [5h4d0wn1k/h14-lora-attack](https://github.com/5h4d0wn1k/h14-lora-attack) | 6 | C++ | LoRa RF security toolkit - packet capture, replay and demodulation on 433/868 MHz. |
| 147 | [5h4d0wn1k/h3-zigbee-sniffer](https://github.com/5h4d0wn1k/h3-zigbee-sniffer) | 6 | C++ | Zigbee/Thread IEEE 802.15.4 packet sniffer for ESP32-C6 — frame capture, header decoding, device … |
| 148 | [5h4d0wn1k/h5-433-replay](https://github.com/5h4d0wn1k/h5-433-replay) | 6 | C++ | 433 MHz RF replay toolkit - capture and retransmit sub-GHz remote signals for hardware testing. |
| 149 | [5h4d0wn1k/w1-deauth-eng](https://github.com/5h4d0wn1k/w1-deauth-eng) | 6 | Python | 802.11 deauthentication frame parser, spoofed-MAC heuristics, and PMF resilience analysis for aut… |
| 150 | [5h4d0wn1k/w2-evil-twin](https://github.com/5h4d0wn1k/w2-evil-twin) | 6 | Python | Evil-twin and rogue-AP detection lab — 802.11 beacon fingerprinting to identify cloned access poi… |
| 151 | [5h4d0wn1k/w3-probe-resp](https://github.com/5h4d0wn1k/w3-probe-resp) | 6 | Python | Wi-Fi probe-request responder for wireless security research — ESP32-C6 promiscuous sniffer with … |
| 152 | [5h4d0wn1k/w6-beacon-analysis](https://github.com/5h4d0wn1k/w6-beacon-analysis) | 6 | Python | 802.11 beacon analyzer - channel/rate/IE parsing and anomaly fingerprinting. |
| 153 | [5h4d0wn1k/w7-wids-sensor](https://github.com/5h4d0wn1k/w7-wids-sensor) | 6 | Python | WIDS sensor - rogue AP, deauth and beacon-flood detection with alerting. |
| 154 | [5h4d0wn1k/w9-ble-spoofer](https://github.com/5h4d0wn1k/w9-ble-spoofer) | 6 | Python | BLE spoofer for wireless security research — byte-exact ADV PDU forging, CRC-24 validation, lab-s… |
| 155 | [AtherNet29/Esp8266-Deauther-2.4-Ghz-Jammer-Bluetooth](https://github.com/AtherNet29/Esp8266-Deauther-2.4-Ghz-Jammer-Bluetooth) | 6 | — | 🎯 ESP8266 Deauther & BT Jammer. Features: Evil Twin, Auto-Password Verify, Beacon Spam, Rogue AP,… |
| 156 | [BrotherOfJhonny/bleak](https://github.com/BrotherOfJhonny/bleak) | 6 | Python | BLEAK — Bluetooth Link Exploitation & Attack Knowledgebase, Plataforma de pentest Bluetooth BLE/C… |
| 157 | [ipv4shh/ESPTOOL2](https://github.com/ipv4shh/ESPTOOL2) | 6 | C++ | ESPTOOL2 — Multi-band wireless toolkit based on ESP32. Wi-Fi & BLE attacks, web interface, Master… |
| 158 | [leingangzj/yui](https://github.com/leingangzj/yui) | 6 | C++ | Pocket comms + pentest companion firmware for the M5Stack Cardputer ADV. Drives a Kenwood TH-D75 … |
| 159 | [MAAYTHM/deauth_wif_for_windows](https://github.com/MAAYTHM/deauth_wif_for_windows) | 6 | Python | A Python3 tool, which simply sends ∞ deauth packets to wifi becoz of which victim device cannot a… |
| 160 | [nd50095800/IISR-A-Secure-Router-for-IoT-Networks](https://github.com/nd50095800/IISR-A-Secure-Router-for-IoT-Networks) | 6 | — | With the increasing popularity of IoT devices, the vulnerabilities & security issues concerned wi… |
| 161 | [NextrixVFX/NRF24-Jammer](https://github.com/NextrixVFX/NRF24-Jammer) | 6 | C++ | NRF24L01-E01 Based Jammer that hits wifi and bluetooth consistantly |
| 162 | [PanduTechLab/Bluetooth-Wifi-scanner-Jammer](https://github.com/PanduTechLab/Bluetooth-Wifi-scanner-Jammer) | 6 | C++ | A portable ESP32-based wireless research tool with BLE, Wi-Fi, and 2.4GHz nRF24 utilities on a 12… |
| 163 | [sifirib/jammerDEAUTHway](https://github.com/sifirib/jammerDEAUTHway) | 6 | Python | I am not responsible for ill-usage |
| 164 | [ToaderMatei/ghostbox](https://github.com/ToaderMatei/ghostbox) | 6 | Python | Modular security research toolkit for Raspberry Pi Zero 2W — USB HID injection, WiFi scanner, Blu… |
| 165 | [xClem123/ESP32-BLE-FruitBuster](https://github.com/xClem123/ESP32-BLE-FruitBuster) | 6 | C++ | ESP32 BLE project sending malicious packets mimicking Apple devices (AirPods, AppleTV, etc.) or d… |
| 166 | [YM2992/Reverb](https://github.com/YM2992/Reverb) | 6 | TypeScript | A web interface to view and replay sub-GHz RF signals, connecting to your ESP32/CC1101 device ove… |
| 167 | [z2labs/Sniff-Sight](https://github.com/z2labs/Sniff-Sight) | 6 | Python | Packet sniffer + RF spectrum side by side: pair 802.15.4/BLE/Wi-Fi packets with their RF bursts u… |
| 168 | [5h4d0wn1k/h10-usb-hid](https://github.com/5h4d0wn1k/h10-usb-hid) | 5 | C++ | USB HID attack tool - programmable keystroke-injection payloads for hardware security testing. |
| 169 | [5h4d0wn1k/h4-mousejack](https://github.com/5h4d0wn1k/h4-mousejack) | 5 | C++ | nRF24 protocol-hacking research lab — ESP32 + nRF24L01+ firmware that scans all 41 channels, snif… |
| 170 | [5h4d0wn1k/w1-wifi-scanner](https://github.com/5h4d0wn1k/w1-wifi-scanner) | 5 | Python | Wi-Fi scanner - SSID/channel/security-mode discovery and visualization. |
| 171 | [5h4d0wn1k/w10-wpa3-survey](https://github.com/5h4d0wn1k/w10-wpa3-survey) | 5 | Python | WPA3/WPA2 survey tool - security-mode census and transition-vulnerability checking. |
| 172 | [5h4d0wn1k/w2-deauth-detect](https://github.com/5h4d0wn1k/w2-deauth-detect) | 5 | Python | Deauth attack detector - monitor-mode heuristics that flag deauth floods and frame anomalies. |
| 173 | [5h4d0wn1k/w3-probe-audit](https://github.com/5h4d0wn1k/w3-probe-audit) | 5 | Python | Wi-Fi probe-request auditor - passive client-probe collection and SSID-leak analysis. |
| 174 | [5h4d0wn1k/w4-crack-pipeline](https://github.com/5h4d0wn1k/w4-crack-pipeline) | 5 | Python | WPA/WPA2/PMKID password audit pipeline — handshake/PMKID detection, hcxpcapngtool conversion, has… |
| 175 | [5h4d0wn1k/w5-nrf-observer](https://github.com/5h4d0wn1k/w5-nrf-observer) | 5 | Python | nRF observer - Nordic 2.4 GHz sniffing and packet-stream analysis for BLE lab work. |
| 176 | [5h4d0wn1k/w6-beacon-flood](https://github.com/5h4d0wn1k/w6-beacon-flood) | 5 | Python | Beacon flood generator - stress-tests client association and wireless IDS systems. |
| 177 | [5h4d0wn1k/w7-deauth-capture](https://github.com/5h4d0wn1k/w7-deauth-capture) | 5 | Python | Deauth capture utility - hunts handshakes, captures frames and logs offenders. |
| 178 | [5h4d0wn1k/w8-covert-beacon](https://github.com/5h4d0wn1k/w8-covert-beacon) | 5 | Python | 802.11 covert-channel toolkit - vendor-IE payload encoding in beacon/probe-response frames plus S… |
| 179 | [5h4d0wn1k/w8-evil-portal](https://github.com/5h4d0wn1k/w8-evil-portal) | 5 | Python | Evil portal / captive-portal builder - phishing landing pages for wireless security labs. |
| 180 | [5h4d0wn1k/w9-resilient-tele](https://github.com/5h4d0wn1k/w9-resilient-tele) | 5 | Python | Resilient telemetry system - wireless data-link redundancy and failover experiments. |
| 181 | [DX-PE/SurveillanceHound](https://github.com/DX-PE/SurveillanceHound) | 5 | C++ | ESP32 WiFi/BLE Sniffer Game, your pet hound sniffs out surveillance devices like Flock and many m… |
| 182 | [enesehs/esp32-jammer](https://github.com/enesehs/esp32-jammer) | 5 | — | ESP32 Bluetooth Wifi Jammer |
| 183 | [KareemAksh/android-gki-wifi-injection](https://github.com/KareemAksh/android-gki-wifi-injection) | 5 | C | Monitor mode & 802.11 packet injection on a stock Android 13 GKI kernel — no reflash. Cross-built… |
| 184 | [Ohminecraft/ESP32-Attack-Tool](https://github.com/Ohminecraft/ESP32-Attack-Tool) | 5 | C | WiFi/BLE Testing/Offensive Tool/Defensive Tool |
| 185 | [oshri-almog/esp32c5-wireshark-sniffer](https://github.com/oshri-almog/esp32c5-wireshark-sniffer) | 5 | Python | ESP32-C5 2.4Ghz + 5.8Ghz Wi-Fi, Zigbee or Thread sniffer interfaces for Wireshark  |
| 186 | [profitpioneer/iphone-protocol-sniffer](https://github.com/profitpioneer/iphone-protocol-sniffer) | 5 | Shell | Reverse-engineer iPhone↔device protocols (BLE/WiFi) without a hardware sniffer. Captures decrypte… |
| 187 | [Scissors2099/ScissorsJammer-v6.5-Spectre-Trident-Edition](https://github.com/Scissors2099/ScissorsJammer-v6.5-Spectre-Trident-Edition) | 5 | C++ | Estación portátil de auditoría analítica y defensa de capa física en 2.4 GHz basada en ESP32 y nR… |
| 188 | [SomnathGorai/ESP32-Marauder-WiFi-Tool](https://github.com/SomnathGorai/ESP32-Marauder-WiFi-Tool) | 5 | C++ | ESP32-based portable WiFi hacking tool using a 1.8" TFT SPI LCD display |
| 189 | [tejasvane/Blu-WIFI_Jammer_Using_ESP8266](https://github.com/tejasvane/Blu-WIFI_Jammer_Using_ESP8266) | 5 | C++ | An ESP8266-based microproject to temporarily disrupt Wi-Fi (deauth) and Bluetooth signals, featur… |
| 190 | [Thenewmanator15/esp32c6-sniffer](https://github.com/Thenewmanator15/esp32c6-sniffer) | 5 | Python | Passive tri-radio wireless sniffer on an ESP32-C6 (802.15.4 / Wi-Fi / BLE), streaming into Wiresh… |
| 191 | [UruxUs/ANKA-ESP32-MultiTool](https://github.com/UruxUs/ANKA-ESP32-MultiTool) | 5 | C++ | ANKA: ESP32 + SSD1306 OLED Security Tool. Includes WiFi Deauth/Beacon Spam, BLE Spam/Scan & IR. |
| 192 | [whoelse091/WIFI-BLE-JAMMER](https://github.com/whoelse091/WIFI-BLE-JAMMER) | 5 | C++ | WIFI/BLE JAMMER |
| 193 | [yuno009/ESP32S3-USB-Keyboard-To-BLE](https://github.com/yuno009/ESP32S3-USB-Keyboard-To-BLE) | 5 | C++ | 🔄 Transform any USB keyboard into a Bluetooth device with ESP32-S3, allowing seamless connections… |
| 194 | [aMiscreant/ESP32c3-Super-Mini-Scipts](https://github.com/aMiscreant/ESP32c3-Super-Mini-Scipts) | 4 | C | This repository contains a collection of Wi-Fi/Encryption/Bluetooth related scripts designed for … |
| 195 | [chetansaini53/ESP32-C6-Threat-Radar](https://github.com/chetansaini53/ESP32-C6-Threat-Radar) | 4 | C++ | Passive defensive wireless threat radar for ESP32-C6 (2.4GHz) - detects WiFi deauth, pwnagotchi &… |
| 196 | [Coreymillia/CYDSentinel](https://github.com/Coreymillia/CYDSentinel) | 4 | C++ | Touchscreen WiFi/BLE scanner, sniffer, and NOAA radar workspace for the ESP32-2432S028R Cheap Yel… |
| 197 | [corporation9/Lifeband-vxOS-WiFi-BLE-Sniffer](https://github.com/corporation9/Lifeband-vxOS-WiFi-BLE-Sniffer) | 4 | C | It detects wireless ESP32 chips as well as Bluetooth Low Energy devices and collects information … |
| 198 | [DIY-Learn/ESP32-DIV](https://github.com/DIY-Learn/ESP32-DIV) | 4 | C | ESP32-DIV: DIY multi‑tool with WiFi, Bluetooth, IR, 2.4GHz attacks and full menu system. |
| 199 | [Exora-Lab/BW16-NRF24-jammer](https://github.com/Exora-Lab/BW16-NRF24-jammer) | 4 | C++ | BW16+ NRF24 constant carrier generator with automatic channel hopping for BW16/RTL8720DN. Creates… |
| 200 | [fatihyldz58/nRF24-BT-Jammer](https://github.com/fatihyldz58/nRF24-BT-Jammer) | 4 | C++ | A powerful 2.4GHz RF testing and Bluetooth interference research tool using ESP32 and dual nRF24L… |
| 201 | [krolyxon/orion-rf](https://github.com/krolyxon/orion-rf) | 4 | C++ | Portable RF and wireless toolkit built on ESP32-S3 |
| 202 | [levouinse/deauther](https://github.com/levouinse/deauther) | 4 | Python | Sofinco Deauther v5.0 is a certified, cross-platform WiFi and Bluetooth penetration testing frame… |
| 203 | [luketheluckyloner/nRF24_jammer](https://github.com/luketheluckyloner/nRF24_jammer) | 4 | — | The nRF24 jammer is a powerful tool that requires an ESP32 and configurable numbers of NRF24 modu… |
| 204 | [omwardhanM/Bluetooth-Wifi-Jammer](https://github.com/omwardhanM/Bluetooth-Wifi-Jammer) | 4 | C++ | Bluetooth, BLE, Wifi - 2.4Ghz ISM Band Jammer / Interference Project with ESP32 and nRf24 |
| 205 | [samdvl/Esp8266-Wifi-Sniffer](https://github.com/samdvl/Esp8266-Wifi-Sniffer) | 4 | C | This software make it possible to scan wifi devices with the esp8266. It contols the TTGO 0.91 ol… |
| 206 | [VinavilDev/DeautherDetector](https://github.com/VinavilDev/DeautherDetector) | 4 | C++ | A lightweight and customizable ESP32-based tool to detect deauthentication packets in WiFi networks. |
| 207 | [bigjosh/drone-sniffer](https://github.com/bigjosh/drone-sniffer) | 3 | C | Standalone drone Remote ID sniffer for the Mesh-Detect board: XIAO ESP32-S3 sniffs BLE + WiFi ch6… |
| 208 | [chinese1123243/ESP32-C5-WIFI6-RF-Toolkit](https://github.com/chinese1123243/ESP32-C5-WIFI6-RF-Toolkit) | 3 | C | ESP32-C5 (RISC-V 240MHz, Wi-Fi 6 双频) 射频测试工具。37 条 CLI 覆盖嗅探 / 握手捕获 / 注入 / 钓鱼门户 / Evil Twin / KARMA … |
| 209 | [eric-o-s/WIFIPOLICE](https://github.com/eric-o-s/WIFIPOLICE) | 3 | C++ | Deauth monitor for the Waveshare ESP32-S3 147 inch Display Dev Board. This guy passively logs to … |
| 210 | [FOXIK-Lab/esp-stun](https://github.com/FOXIK-Lab/esp-stun) | 3 | Python | ESP32 Firmware for Pentesting. |
| 211 | [HowDidThatHappen1/BT-Wifi-RC-Jammer](https://github.com/HowDidThatHappen1/BT-Wifi-RC-Jammer) | 3 | C++ |  |
| 212 | [KlutzyBlade/NetRaze32](https://github.com/KlutzyBlade/NetRaze32) | 3 | C | NetRaze32 is a comprehensive penetration testing tool built for the ESP32-32E platform with a 2.8… |
| 213 | [Meshwa428/KIVA](https://github.com/Meshwa428/KIVA) | 3 | C++ | KIVA: A handheld AI hacking assistant born from a love of tinkering. A pen-testing tool built fro… |
| 214 | [MrDepph/Tamafi-CYD-ESP32](https://github.com/MrDepph/Tamafi-CYD-ESP32) | 3 | — | Tamagotchi-inspired WiFi/Bluetooth sniffer firmware for CYD 2.8" ESP32. Creature feeds on network… |
| 215 | [mrnet15/RavenRF](https://github.com/mrnet15/RavenRF) | 3 | C++ | Modular RF & pentest firmware for the M5Stack Cardputer Adv + Cap LoRa-1262 (WiFi, BLE, LoRa, GPS) |
| 216 | [nlogallo/esp32-mantisHack](https://github.com/nlogallo/esp32-mantisHack) | 3 | C++ | Project of a small hacking device with Wifi, Bluetooth, NFC, and IR capabilities. |
| 217 | [pwnk1t/esp32-bluetooth-WiFi-jammer](https://github.com/pwnk1t/esp32-bluetooth-WiFi-jammer) | 3 | — | how to build a simple bluetooth/WiFi-jammer (WiFi only works on 2,4Ghz Network-devices) |
| 218 | [RizzoEng/DevilApe-Tft-cyberdeck](https://github.com/RizzoEng/DevilApe-Tft-cyberdeck) | 3 | — | ESP32-powered cyberdeck interface. WiFi/BLE scanning, packet monitoring, deauth detection, beacon… |
| 219 | [shasradha/Orbit](https://github.com/shasradha/Orbit) | 3 | C | Wrist-worn WiFi security testing tool — ESP8266 + OLED in a modified SKMEI watch case. KiCad hard… |
| 220 | [shubbrotopaul-max/Spectre-DIV-OS](https://github.com/shubbrotopaul-max/Spectre-DIV-OS) | 3 | C | SPECTRE-DIV OS is a Matrix-themed WiFi Research Suite for ESP32 & ST7789 TFT. 🚀  Features: ✅ Pack… |
| 221 | [stephanbluitt/-ESP32-Evil-Twin-Attack](https://github.com/stephanbluitt/-ESP32-Evil-Twin-Attack) | 3 | C++ | A proof-of-concept ESP32 Evil Twin attack demo featuring deauthentication and a customizable capt… |
| 222 | [WhiskeyTangoHotel/Portable-ESP8266-WiFi-Sniffer-Arduino-IDE-](https://github.com/WhiskeyTangoHotel/Portable-ESP8266-WiFi-Sniffer-Arduino-IDE-) | 3 | — | Portable ESP8266 WiFi Sniffer (Arduino IDE) |
| 223 | [x3nc0n/flipper-fuzzer](https://github.com/x3nc0n/flipper-fuzzer) | 3 | C | FluckFlock - a Flipper Zero chaff broadcaster that floods passive Wi-Fi/BLE/RF tracking with plau… |
| 224 | [xuemian168/esp32-ble-proximity-spoofing](https://github.com/xuemian168/esp32-ble-proximity-spoofing) | 3 | Python | Research artifact for ESP32 BLE proximity advertisement spoofing experiments |
| 225 | [aingram702/ESP32-Net](https://github.com/aingram702/ESP32-Net) | 2 | C++ | A network of dropable ESP32 devices that all serve an individual purpose. One ESP32-S3 DevKitC-1 … |
| 226 | [aniceswan/PhantomRF](https://github.com/aniceswan/PhantomRF) | 2 | C++ | Open-source ESP32-S3 RF research & security testing platform. nRF24L01 + CC1101 jamming, full WiF… |
| 227 | [Arxhsz/Project-Skull-Breaker-v1](https://github.com/Arxhsz/Project-Skull-Breaker-v1) | 2 | C++ | ESP32 handheld multi-radio security research device — WiFi, BLE, 2.4GHz & sub-GHz RF. v1 proof of… |
| 228 | [AxGHaven/AxG_Haven-WiFi-Tool](https://github.com/AxGHaven/AxG_Haven-WiFi-Tool) | 2 | — | ESP8266-based portable WiFi audit tool with OLED UI, EvilTwin captive portal, deauth attack, NRF2… |
| 229 | [chrislangfitt7/ESP_32_SNIFFER](https://github.com/chrislangfitt7/ESP_32_SNIFFER) | 2 | — | A small handheld device that has 2.4ghz capabilities along with Wifi and Bluetooth scanning. Usin… |
| 230 | [dela-99/WIFI-HACKING](https://github.com/dela-99/WIFI-HACKING) | 2 | Python | Ethical WiFi pentesting. OFFENSIVE (explicit written permission) to spot flaws like weak encrypti… |
| 231 | [Dev-Lahrani/Evil-Twin_Wifi-Detection](https://github.com/Dev-Lahrani/Evil-Twin_Wifi-Detection) | 2 | Python | Deterministic Wi-Fi evil-twin detector for Raspberry Pi/Linux: explainable rule engine and RF fin… |
| 232 | [devdanqtuan/esp32-bluetooth-classic-attacks](https://github.com/devdanqtuan/esp32-bluetooth-classic-attacks) | 2 | — |  |
| 233 | [DiamondsBattle/Sqkele](https://github.com/DiamondsBattle/Sqkele) | 2 | — | A python all-in-one toolkit packed with tons of different features, including iOS and Android app… |
| 234 | [G4MEOVER18/heltec-ukfe-rx](https://github.com/G4MEOVER18/heltec-ukfe-rx) | 2 | C++ | Heltec V3 (ESP32-S3+SX1262): 868-FSK+ESP-NOW Satellit/Hub des G4MEOVER-Oekosystems. Handler: WiFi… |
| 235 | [G4MEOVER18/lilygo-ukfe-rx](https://github.com/G4MEOVER18/lilygo-ukfe-rx) | 2 | C++ | G4MEOVER LilyGo T-Dongle S3: ESP-NOW-Satellit. Handler: USB-HID (BadUSB), WiFi (Deauth/Beacon/Sca… |
| 236 | [GlomarGadaffi/wifi-ble-marauder](https://github.com/GlomarGadaffi/wifi-ble-marauder) | 2 | C | Pure ESP-IDF 6.0.1 WiFi/BLE security tool: 5GHz deauth, Thread/Matter scanning, BLE 5.0 ext adv. … |
| 237 | [Grostl/esp32-mac-collector](https://github.com/Grostl/esp32-mac-collector) | 2 | C++ | Dual-band (2.4/5 GHz) Wi-Fi & Bluetooth LE sniffer for ESP32-C5. Captures MAC addresses from Prob… |
| 238 | [Hareesh-Rajput/WiFi-Pentest](https://github.com/Hareesh-Rajput/WiFi-Pentest) | 2 | — | A structured and actionable Excel-based checklist for WiFi penetration testing, covering every ph… |
| 239 | [Harsh-Parasharj/Aerosniff-x3](https://github.com/Harsh-Parasharj/Aerosniff-x3) | 2 | C++ | AeroSniff X3: WiFi, BLE, drone, jamming & packet sniffing tool with OLED & web UI, controls via b… |
| 240 | [hassanzprofile/wifi-jammer](https://github.com/hassanzprofile/wifi-jammer) | 2 | Shell | A Wi-Fi jammer script or tool is designed to disrupt and disable wireless communications between … |
| 241 | [Hoanqnguyen292/Oled-Deauther](https://github.com/Hoanqnguyen292/Oled-Deauther) | 2 | C++ | Affordable WiFi hacking platform for testing and learning |
| 242 | [IAbrahamI/Wifi_Scanner](https://github.com/IAbrahamI/Wifi_Scanner) | 2 | C++ | Multi-boot pocket RF gadget powered by ESP32-S3. Includes a touch-based boot launcher, active fla… |
| 243 | [internettrashh/esp8266-wifi-deauter](https://github.com/internettrashh/esp8266-wifi-deauter) | 2 | C | my version of the wifi deauther compatible with chinese display modules |
| 244 | [J1rs/Jir32](https://github.com/J1rs/Jir32) | 2 | — | ESP32-based wireless security & signal research system: Integrated tools for WiFi, Bluetooth, and… |
| 245 | [Jevonte07/WIFI-DEauther-Watch](https://github.com/Jevonte07/WIFI-DEauther-Watch) | 2 | C | The Deauther Watch is a compact, wearable device built using the ESP8266 microcontroller that per… |
| 246 | [johnnyk2000/BluetoothRover](https://github.com/johnnyk2000/BluetoothRover) | 2 | C++ | Redo of HAcK 22: Create a rover that is controlled through bluetooth using UART btw arduibno and … |
| 247 | [kes229229/JAM-PACK](https://github.com/kes229229/JAM-PACK) | 2 | C++ | 📡 Ultimate multi-tool firmware for ESP32 · WiFi · BLE · SubGHz · IR · GPIO · BETA |
| 248 | [killindodo/Dodo-RF](https://github.com/killindodo/Dodo-RF) | 2 | Kotlin | ESP32 based open-source, ultra-portable Sub-GHz radio analysis, capture, and replay |
| 249 | [Ludmilahttps/Jammer-WiFi-Bluetooth-ESP32](https://github.com/Ludmilahttps/Jammer-WiFi-Bluetooth-ESP32) | 2 | JavaScript | Protótipo de bloqueador de sinais sem fio (Wi-Fi/Bluetooth) na faixa de 2.4 GHz, desenvolvido com… |
| 250 | [mackg1288-pixel/packet-squirrel](https://github.com/mackg1288-pixel/packet-squirrel) | 2 | Python | DIY network interception platform built with NanoPi NEO3 + ESP32. Inline Ethernet bridge with WiF… |
| 251 | [maviaydin044-max/BlueDrogom](https://github.com/maviaydin044-max/BlueDrogom) | 2 | C++ | This software carries out kill attacks using the ESP32's Wi-Fi antennas.    PLEASE ONLY ATTACK YO… |
| 252 | [Nadoooor/SnakeHunter](https://github.com/Nadoooor/SnakeHunter) | 2 | — | An ESP32 wifi, bluetooth, IR, etc hacking device with touch screen. |
| 253 | [neilmanfredit/CyberDeck](https://github.com/neilmanfredit/CyberDeck) | 2 | C++ | Portable pentest cyberdeck — NUC-based clamshell with an embedded ESP32-S3 security module (sub-G… |
| 254 | [PythonJu80/sniffymapp](https://github.com/PythonJu80/sniffymapp) | 2 | — | In a Nutshell 🛰️  This is a **comprehensive GPS security analysis toolkit** that combines passive… |
| 255 | [Q3hr/Blackout-2.4](https://github.com/Q3hr/Blackout-2.4) | 2 | C | Blackout 2.4 is a 5th Semester Network Security project that explores 2.4 GHz spectrum behavior a… |
| 256 | [R09Aditya/ESP-Marauder](https://github.com/R09Aditya/ESP-Marauder) | 2 | — | ESP Marauder is a cybersecurity tool used to jam, analyze and do alot of things on wifi or blueto… |
| 257 | [R0b1nary/radiosniffer](https://github.com/R0b1nary/radiosniffer) | 2 | Python | tool to sniff for wifi and bluetooth devices |
| 258 | [raju-prajapat/ESP32-Brute-Force-Attack-To-ByPass-Phone-Lock](https://github.com/raju-prajapat/ESP32-Brute-Force-Attack-To-ByPass-Phone-Lock) | 2 | C++ | Proof-of-concept ESP32 BLE Keyboard script for automated 4-digit and 6-digit PIN testing. |
| 259 | [revjmoney/simian-radar](https://github.com/revjmoney/simian-radar) | 2 | C++ | Listen-only pocket privacy scanner for the Heltec LoRa 32 V4: offline US ALPR camera alerts, trac… |
| 260 | [Rudii-25/BloodHound_VENOM](https://github.com/Rudii-25/BloodHound_VENOM) | 2 | HTML | BloodHound VENOM is an open-source hackable handheld IoT device for makers and developers. ESP826… |
| 261 | [saravanasai1435/esp32-marauder-wifi-bt-security-tool](https://github.com/saravanasai1435/esp32-marauder-wifi-bt-security-tool) | 2 | — | ESP32 Marauder WiFi/Bluetooth security toolkit: deauth, beacon spam, evil portal, GPS, SD logging… |
| 262 | [Tanmay1894/ESP32-Flipper](https://github.com/Tanmay1894/ESP32-Flipper) | 2 | C++ | ESP32 Flipper is a touchscreen-driven toolkit for wireless security testing on ESP32. It features… |
| 263 | [TheImposterz/RaspPunzel](https://github.com/TheImposterz/RaspPunzel) | 2 | Shell | RaspPunzel is a Raspberry Pi-based penetration testing platform that transforms a Pi into a porta… |
| 264 | [TheKanjiTV/Beacon](https://github.com/TheKanjiTV/Beacon) | 2 | Swift | 📊 Track user behavior in Swift apps easily with Beacon, offering offline persistence, device cont… |
| 265 | [voltwizeshea/DarkMatter_Duck](https://github.com/voltwizeshea/DarkMatter_Duck) | 2 | C++ | Dual-stack HID weapon on ESP32-S3: USB + BLE keystroke injection, WiFi C2, payload chains. One of… |
| 266 | [Vybenclave/wifi-d_vice](https://github.com/Vybenclave/wifi-d_vice) | 2 | C | WIFI D_VICE - passive Wi-Fi / BLE / sub-GHz radio-monitoring tool for the 2.8-inch ESP32 CYD. No … |
| 267 | [xerdenx/Spooky-](https://github.com/xerdenx/Spooky-) | 2 | C++ | A customized fork of nRFBox firmware for ESP32.  Changes made: - TV-B-Gone added (IR remote power… |
| 268 | [Zer0D0wn/Jammer](https://github.com/Zer0D0wn/Jammer) | 2 | Perl | A perl wifi jammer who use an packet injection capable interface. Tested with Alfa AWUS1900. |
| 269 | [0EchoPixel/ESP32-Bluetooth-Jammer](https://github.com/0EchoPixel/ESP32-Bluetooth-Jammer) | 1 | C++ | ESP32 + NRF24L01 That jams WIFI and Bluetooth  |
| 270 | [Aditya5441/Jammer_Adaptive](https://github.com/Aditya5441/Jammer_Adaptive) | 1 | C++ | an ESP32-based WiFi/BLE jamming device that uses chaos-derived entropy (from internal noise/analo… |
| 271 | [anaskhanxada/WifiandBluetoothJammer](https://github.com/anaskhanxada/WifiandBluetoothJammer) | 1 | C | A WiFi and Bluetooth jamming tool built on [ESP32/your hardware] for disrupting wireless signals … |
| 272 | [basht0p/WarPebble](https://github.com/basht0p/WarPebble) | 1 | Python | A system for wifi hacking / wardriving, designed for the ESP8266 HW-364A microcontroller, or othe… |
| 273 | [brandonvader/Sentinel-Watch-OS](https://github.com/brandonvader/Sentinel-Watch-OS) | 1 | C | Passive WiFi + BLE threat monitor for the Waveshare ESP32-S3 AMOLED watch: gravity-driven data-ra… |
| 274 | [byankush/Ble-wifi-jammer-byankush](https://github.com/byankush/Ble-wifi-jammer-byankush) | 1 | C++ | ESP32-based wireless security research project exploring Wi-Fi and Bluetooth protocols, RF commun… |
| 275 | [ciccirix/koko-v9](https://github.com/ciccirix/koko-v9) | 1 | C++ | ESP32 Marauder C5 — koko V9: WiFi/BT-only build, features reorganized into stock WiFi/Bluetooth m… |
| 276 | [ClemensAtElektor/Bluetooth-LE-ESP32-client-server](https://github.com/ClemensAtElektor/Bluetooth-LE-ESP32-client-server) | 1 | C++ | Simple Bluetooth client-server setup on two ESP32 modules for trying out nRF52840 BLE sniffer. |
| 277 | [cyberkalki/wifi_deauthentication](https://github.com/cyberkalki/wifi_deauthentication) | 1 | — | A WiFi deauther employing an ESP8266 disrupts wireless connections, rendering devices temporarily… |
| 278 | [Deadbush225/Poltergeist](https://github.com/Deadbush225/Poltergeist) | 1 | Dart | Bluetooth payload attacks using ESP32-S3 |
| 279 | [DEBBUK/bruce-evil-knop-ble](https://github.com/DEBBUK/bruce-evil-knop-ble) | 1 | C++ | Custom Bruce firmware for LilyGO T-Display ESP32 with EVIL KNOP BLE — max-power iPhone BLE attack… |
| 280 | [flandreiii/Neux-Firmware-for-Esp32](https://github.com/flandreiii/Neux-Firmware-for-Esp32) | 1 | C++ | Turn any ESP32 into a pocket-sized wireless security scanner. WiFi/BLE recon, rogue AP detection,… |
| 281 | [GeneralDussDuss/hephaestus](https://github.com/GeneralDussDuss/hephaestus) | 1 | C++ | The forge: a Claude Code plugin for discovering, prototyping, and defending novel embedded/RF att… |
| 282 | [govardhanh21/ESP32-Based-Bluetooth-HID-Attack-and-BLE-Scanner-Detection-System](https://github.com/govardhanh21/ESP32-Based-Bluetooth-HID-Attack-and-BLE-Scanner-Detection-System) | 1 | C++ |  |
| 283 | [hackerazmi201/Ble-Jammer](https://github.com/hackerazmi201/Ble-Jammer) | 1 | — | Ble-jammer is a hardware-based BLE interference/testing toolkit that uses an ESP32 (for control a… |
| 284 | [hleserg/esp32-flipper-exp](https://github.com/hleserg/esp32-flipper-exp) | 1 | Python | Flipper Zero + ESP32 'chaos from one button': Sub-GHz + IR + BLE. Roadmap: XIAO ESP32-C6 Zigbee/T… |
| 285 | [JavierSiliacay/WiFi-Bluetooth-Jammer-Project](https://github.com/JavierSiliacay/WiFi-Bluetooth-Jammer-Project) | 1 | — | A powerful 2.4GHz signal disruptor built with ESP32, capable of jamming wireless communication by… |
| 286 | [jR4dh3y/Pico32](https://github.com/jR4dh3y/Pico32) | 1 | C++ | A lightweight, serial-only TUI port of ESP32 Marauder. WiFi/BT testing tool for generic ESP32 mod… |
| 287 | [Justus040/ESP32-DIV-EvilAppleJuice](https://github.com/Justus040/ESP32-DIV-EvilAppleJuice) | 1 | — | EvilAppleJuice BLE Spoofing integrated into ESP32-DIV with TFT display UI |
| 288 | [karthik-nidiginti/nRFBox_v2](https://github.com/karthik-nidiginti/nRFBox_v2) | 1 | C | ESP32 NRF toolbox project with BLE scanner, jammer, analyzer and spoofing ,modules |
| 289 | [Landull/wifiscan](https://github.com/Landull/wifiscan) | 1 | Python | Lists nearby Wi-Fi networks and flags open, WEP, WPA/TKIP and possible evil-twin access points. P… |
| 290 | [marcucarapangea-cloud/ESP32-WiFi-BLE-Penetration-Tool](https://github.com/marcucarapangea-cloud/ESP32-WiFi-BLE-Penetration-Tool) | 1 | — | WiFi Deauth + BLE Spoofing tool for ESP32 DevKit with OLED 0.96 display (SSD1306 I2C) |
| 291 | [MateoQuinteroH/Open-Jammer-V1.0](https://github.com/MateoQuinteroH/Open-Jammer-V1.0) | 1 | — | This project is an ESP32 based WiFi/Bluetooth jammer device. |
| 292 | [Mehflexx17/ESP5-WarBox-ESP32-](https://github.com/Mehflexx17/ESP5-WarBox-ESP32-) | 1 | — | ESP32-based RF security research tool with WiFi deauth, BLE flood, 2.4GHz spectrum analyzer, and … |
| 293 | [mike4x2/braktooth_esp32_bluetooth_classic_attacks-arm64-installer](https://github.com/mike4x2/braktooth_esp32_bluetooth_classic_attacks-arm64-installer) | 1 | — | Installer and compatibility fixes forBraktooth on ARM64 Debian 13 and Armbian |
| 294 | [MODARriba/Bluetooth-Jammer_IOT](https://github.com/MODARriba/Bluetooth-Jammer_IOT) | 1 | — | An ESP32-based RF interference research platform designed to analyze Bluetooth communication resi… |
| 295 | [mohammadajani/Beacongotchi](https://github.com/mohammadajani/Beacongotchi) | 1 | Python | Wireless Security Awareness Platform - Custom ESP32-S3 / BW16 FirmwareBuilt a multi-board WiFi/BL… |
| 296 | [MPunktBPunkt/esp32.bt-analyzer](https://github.com/MPunktBPunkt/esp32.bt-analyzer) | 1 | Python | ESP32-S3 Bluetooth USB/HCI analyzer lab (dongle HCI capture → Debian). Not an RF sniffer. |
| 297 | [MRGcodex/WipanFi](https://github.com/MRGcodex/WipanFi) | 1 | Python | An advanced Linux WiFi auditing toolkit by MRGcodex. Features auto monitor mode, PMKID & Handshak… |
| 298 | [ndpg33/CHICKADEE](https://github.com/ndpg33/CHICKADEE) | 1 | C++ | ESP32 and CC1101 portable sub-GHz RF analysis tool with OLED interface. |
| 299 | [netvader/cyd-guard](https://github.com/netvader/cyd-guard) | 1 | C++ | Passive WiFi deauth + BLE jam detector for the CYD (ESP32-2432S024R) |
| 300 | [nik-nim/ESP32-Multi-Protocol-Wireless-Analysis-System](https://github.com/nik-nim/ESP32-Multi-Protocol-Wireless-Analysis-System) | 1 | — | ESP32 Multi-Protocol Wireless Analysis System \| Personal R&D Project Arduino, C/C++, ESP32, RF E… |
| 301 | [noweheere/Lumos-BBR-Bluetooth-Sniffer](https://github.com/noweheere/Lumos-BBR-Bluetooth-Sniffer) | 1 | — | ESP32 Bluetooth sniffer for Lumos Matrix helmet communication analysis and trailer indicator rela… |
| 302 | [overlinderosier0-afk/DJA-SCAN](https://github.com/overlinderosier0-afk/DJA-SCAN) | 1 | C++ | Outil de reconnaissance WiFi/Bluetooth passif sur ESP32 (OLED + joystick) - scan, detection deaut… |
| 303 | [P1p2gamer26/Jammer_Hacking_etico](https://github.com/P1p2gamer26/Jammer_Hacking_etico) | 1 | HTML | Laboratorio educativo de seguridad RF 2.4 GHz: ESP32 + nRF24L01+ PA/LNA (consola serial, escaner … |
| 304 | [parzival123-gan/esp32-wifi-ble-scanner](https://github.com/parzival123-gan/esp32-wifi-ble-scanner) | 1 | — | A lightweight RF scanner built with ESP32 that detects nearby Wi-Fi and Bluetooth Low Energy devi… |
| 305 | [PrestoDL/Project_ESP32Controller](https://github.com/PrestoDL/Project_ESP32Controller) | 1 | C | Project about esp32 controller, using wifi and ble. hacking research also |
| 306 | [Rain26t/Bluetooth-Wifi-RC-RF-Jammer-using-ESP32-and-NRF24L01](https://github.com/Rain26t/Bluetooth-Wifi-RC-RF-Jammer-using-ESP32-and-NRF24L01) | 1 | C++ |  |
| 307 | [ravdahuzaif88-hub/2.4GHz-Wireless-Security-Analysis-System](https://github.com/ravdahuzaif88-hub/2.4GHz-Wireless-Security-Analysis-System) | 1 | C++ | ESP32-based wireless security toolkit for 2.4GHz spectrum analysis, BLE spoofing and Wi-Fi deauth… |
| 308 | [rewalo/RowBoy](https://github.com/rewalo/RowBoy) | 1 | C++ | A tiny, hackable handheld powered by the ESP32-S3 WROOM-1, designed for gaming, emulation, and mo… |
| 309 | [Rhaine2008/WIfi---Bluetooth-Jammer](https://github.com/Rhaine2008/WIfi---Bluetooth-Jammer) | 1 | C++ | This project explores wireless communication, radio-frequency interference, and network security … |
| 310 | [rickmatthewgerale3fb-cmd/Esp8266-signal-jammer-BLE-Bluetooth-and-Wifi](https://github.com/rickmatthewgerale3fb-cmd/Esp8266-signal-jammer-BLE-Bluetooth-and-Wifi) | 1 | C++ | A esp8266 optional screenless jammer with ONLY 2 supported nrf24's. Code mostly from gemini |
| 311 | [Romemu1810-tech/bluetooth_jammer_experimento](https://github.com/Romemu1810-tech/bluetooth_jammer_experimento) | 1 | HTML | Proyecto personal y experimental para el aprendizaje de electrónica, RF y comunicaciones Bluetoot… |
| 312 | [ryvoxo/nRF-jammer](https://github.com/ryvoxo/nRF-jammer) | 1 | C++ | A Bluetooth and a WIFIA jammer using the ESP32 and two NRF24L01s. |
| 313 | [somelucs/bluetooth-esp32-attack](https://github.com/somelucs/bluetooth-esp32-attack) | 1 | C++ | Windows code injection by HID with bluetooth and ESP32  |
| 314 | [sophatvathana/dt2m](https://github.com/sophatvathana/dt2m) | 1 | C++ | DT2M (Don't T to Me) - ESP32 Multi-Purpose RF Development Platform |
| 315 | [suvo2007/Nrfboom_Btl](https://github.com/suvo2007/Nrfboom_Btl) | 1 | — | NRF BOOM — an ESP32-based multi-tool for nRF24, BLE, and WiFi security testing (scanner, jammer, … |
| 316 | [tech-nickk/ESP32Dragonfly](https://github.com/tech-nickk/ESP32Dragonfly) | 1 | C++ | WIFI and bluetooth pentesting tool |
| 317 | [teodorandrei/esp32_blespoof_gui](https://github.com/teodorandrei/esp32_blespoof_gui) | 1 | C++ | Easy to use ESP32 BLE Spoofer with Tkinter GUI |
| 318 | [tharakamruthraj/signal-jammer](https://github.com/tharakamruthraj/signal-jammer) | 1 | — | Description: A portable ESP32-based wireless signal jammer and scanner (NRF Box) designed for edu… |
| 319 | [Usernameaisnoavailable/Hecker](https://github.com/Usernameaisnoavailable/Hecker) | 1 | — | An ESP32-based multi-tool for WiFi and BLE pentesting, themed around the "Hecker" cat meme. heres… |
| 320 | [v-aryank/NRF_Box-WiFi_Bluetooth_Deauther](https://github.com/v-aryank/NRF_Box-WiFi_Bluetooth_Deauther) | 1 | — |  |
| 321 | [Vardhan0257/BlackPebble](https://github.com/Vardhan0257/BlackPebble) | 1 | C++ | BlackPebble is a modular ESP32-S3–based multi-protocol security research platform integrating Wi-… |
| 322 | [vswanagan/flock-you-also](https://github.com/vswanagan/flock-you-also) | 1 | — | ESP32-S3 firmware that emulates Flock Safety surveillance devices (FS Ext Battery, WiFi AP, Raven… |
| 323 | [W0rKiska/wlab](https://github.com/W0rKiska/wlab) | 1 | Shell | WLAB — лабораторный набор для Wi-Fi / BLE / OSINT: скан, деаут, хендшейк, PMKID, evil twin, BLE-с… |
| 324 | [ymvnby-alt/ESP32MotiondetectionWIP](https://github.com/ymvnby-alt/ESP32MotiondetectionWIP) | 1 | C++ | WiFi CSI + BLE motion detection using an ESP32 and a Qt6 desktop app. Sniffs channel state varian… |
| 325 | [abhi96bold/esp32-wifi-and-bluetooth-deauther-with-scroling-function](https://github.com/abhi96bold/esp32-wifi-and-bluetooth-deauther-with-scroling-function) | 0 | — |  |
| 326 | [abhinai2244/BLE-WIFI-JAMMER](https://github.com/abhinai2244/BLE-WIFI-JAMMER) | 0 | C++ | This project contains firmware for a Bluetooth jammer using an ESP32 and NRF24L01 radio modules |
| 327 | [Adii3310/ESP32__jammer](https://github.com/Adii3310/ESP32__jammer) | 0 | C++ | this is the code for the ESP32 development board for programming it for the jammer this ESP32 jam… |
| 328 | [AlanArantes/ESP32-BlueJammer](https://github.com/AlanArantes/ESP32-BlueJammer) | 0 | — | The ESP32-BlueJammer (Bluetooth jammer, BLE jammer, WiFi jammer, RC jammer) disrupts 2.4GHz commu… |
| 329 | [Amalhameed-stack/Wifi-Bluetooth-classic-and-BLE-jammer-using-one-nRF24L01-module-and-esp32](https://github.com/Amalhameed-stack/Wifi-Bluetooth-classic-and-BLE-jammer-using-one-nRF24L01-module-and-esp32) | 0 | — | This project is for educational purposes only |
| 330 | [AndiMue/ESP32_NimBLE-Sniffer_v0_Radar](https://github.com/AndiMue/ESP32_NimBLE-Sniffer_v0_Radar) | 0 | C++ | Sniffs Bluetooth devices in your environment |
| 331 | [arjuntanwar/espbox](https://github.com/arjuntanwar/espbox) | 0 | C++ | This is a comprehensive ESP32-based multi-tool firmware with 19+ modules including WiFi attacks, … |
| 332 | [Aromalajith8/Bluject](https://github.com/Aromalajith8/Bluject) | 0 | C++ | An open-source, multi-OS BLE HID keystroke injection tool built for the ESP32. Features an air-ga… |
| 333 | [avinashyadav143210-lab/-Bt-wifi-jammerr](https://github.com/avinashyadav143210-lab/-Bt-wifi-jammerr) | 0 | — | Bluetooth and wifi  jammer by using ESP32 |
| 334 | [bilal-robotics/-WiFi-BLE-Jammer](https://github.com/bilal-robotics/-WiFi-BLE-Jammer) | 0 | C++ | Yeh ek WiFi + BLE Jammer ka Arduino code hai jo ESP32 aur 2x NRF24L01 modules use karta hai. |
| 335 | [billjuv/OMG-ESP32-BLE_govee_sniffer](https://github.com/billjuv/OMG-ESP32-BLE_govee_sniffer) | 0 | — | Monitoring Govee Thermo-Hygrometer sensors using OpenMQTTGateway |
| 336 | [bytecod3/RedZone-HackerBadge](https://github.com/bytecod3/RedZone-HackerBadge) | 0 | — | A DIY ESP32 hacker badge with Wi-Fi/Bluetooth meshing, an OLED, and stealthy CTF challenges and p… |
| 337 | [ComputerScienceHouse/imagine2022-embedded](https://github.com/ComputerScienceHouse/imagine2022-embedded) | 0 | C | The Sniffer ESP32 App. Forms a mesh net and looks for tags. |
| 338 | [cyph-zz/RF-Pennywise](https://github.com/cyph-zz/RF-Pennywise) | 0 | C++ | ESP32 + nRF24L01x RF toolkit: jamming, WiFi/BLE scanning, spectrum analysis & security-awareness … |
| 339 | [danaahmadifar/wifi-signal-tester-mit-esp32-support](https://github.com/danaahmadifar/wifi-signal-tester-mit-esp32-support) | 0 | Python | WLAN Signal-Tester und Netzwerk-Diagnosesystem mit ESP32 (Promiscuous Sniffer & Bluetooth SPP) un… |
| 340 | [daykiller-viann/esp32D4yk1ll3rsec](https://github.com/daykiller-viann/esp32D4yk1ll3rsec) | 0 | — | alat peretasan ,jammer bluetooth attack ,deauther,beacon spam ,auth spam |
| 341 | [Denilxavier/esp32-Marauder](https://github.com/Denilxavier/esp32-Marauder) | 0 | — | ESP32-based wireless tool for both offensive testing and defensive detection deauth attacks, rogu… |
| 342 | [divisionind/hackquad](https://github.com/divisionind/hackquad) | 0 | HTML | the hackable open-source esp32 wifi controlled quadcopter |
| 343 | [embededbuild/Mona-Lisa](https://github.com/embededbuild/Mona-Lisa) | 0 | — | a esp32 device that can do WiFi/BLE base attacks and also have the ability to READ/WRITE to card/… |
| 344 | [Eren-Oztk/esp32-wifi-bluetooth-scanner](https://github.com/Eren-Oztk/esp32-wifi-bluetooth-scanner) | 0 | C++ | ESP32-based scanner that detects nearby Wi-Fi and Bluetooth devices for local network analysis. |
| 345 | [GamerFuryAction/Deauth-testing-device](https://github.com/GamerFuryAction/Deauth-testing-device) | 0 | — | Cybersecurity testing device based on the BW16 development board, designed for testing the securi… |
| 346 | [hamzaasghar2429/Esp8266_Deauther](https://github.com/hamzaasghar2429/Esp8266_Deauther) | 0 | — | Affordable WiFi hacking platform for testing and learning. I recreate my own version it is inspir… |
| 347 | [HasanRsool/Simple-Signal-Jammer](https://github.com/HasanRsool/Simple-Signal-Jammer) | 0 | C++ | A simple WiFi & Bluetooth jammer using ESP32 & nRF24L01. |
| 348 | [inevitable-lettus/esp32-rf-security-toolkit](https://github.com/inevitable-lettus/esp32-rf-security-toolkit) | 0 | — | Wireless-protocol security research platform on ESP32 — IR / RFID-NFC / sub-GHz / WiFi / BLE capt… |
| 349 | [JackTheTripperr/WiFi-Hack](https://github.com/JackTheTripperr/WiFi-Hack) | 0 | — | Basic guide outlining the process to capture a handshake, convert it to a Hashcat compatible hash… |
| 350 | [JKCOM1911/Jammer-wifi-Bluetooth-esp32](https://github.com/JKCOM1911/Jammer-wifi-Bluetooth-esp32) | 0 | C++ |  |
| 351 | [jsuescun/espSAK](https://github.com/jsuescun/espSAK) | 0 | C | ESP32 Swiss Army Knife: wireless multi-tool, Flipper Zero capabilities at a fraction of the cost.… |
| 352 | [Leakyli/2.4GHz-BLE-WIFI-SNIFFER](https://github.com/Leakyli/2.4GHz-BLE-WIFI-SNIFFER) | 0 | C | A 3-in-1 project that includes the use of ESP32U's built in Bluetooth and Wifi shared radio and a… |
| 353 | [Luiz123819/Projeto-Jammer-Bluetooth](https://github.com/Luiz123819/Projeto-Jammer-Bluetooth) | 0 | C++ | Desenvolvi do zero um projeto pessoal de hardware e firmware focado em análise de sinais em RF. O… |
| 354 | [lve-qw/espen](https://github.com/lve-qw/espen) | 0 | C++ | ESP32 based wifi/bluetooth pentest tool |
| 355 | [MAK554267/Blackout-2.4](https://github.com/MAK554267/Blackout-2.4) | 0 | C | Blackout 2.4 is a 5th Semester Network Security project that explores 2.4 GHz spectrum behavior a… |
| 356 | [MallocPointer/esp8266_deauther](https://github.com/MallocPointer/esp8266_deauther) | 0 | — | Affordable WiFi hacking platform for testing and learning |
| 357 | [mathish06/Sentinel-IDS](https://github.com/mathish06/Sentinel-IDS) | 0 | C++ | Portable passive WiFi Intrusion Detection System built on the ESP32. Detects Deauthentication flo… |
| 358 | [maviaydin044-max/BlueDrogon](https://github.com/maviaydin044-max/BlueDrogon) | 0 | — | This software carries out kill attacks using the ESP32's Wi-Fi antennas.    PLEASE ONLY ATTACK YO… |
| 359 | [MAvinash24/esp32-iot-fuzzing-lab](https://github.com/MAvinash24/esp32-iot-fuzzing-lab) | 0 | C++ | A comprehensive IoT security project demonstrating protocol fuzzing on ESP32 using both:  Bluetoo… |
| 360 | [milofrio066/Airlock](https://github.com/milofrio066/Airlock) | 0 | Python | IoT network monitoring system using ESP32, Python, and Flask. Detects Wi-Fi deauthentication atta… |
| 361 | [mriquelmec/ESP32-AI-SIEM-project](https://github.com/mriquelmec/ESP32-AI-SIEM-project) | 0 | Python | AI-powered SIEM that uses an ESP32 running Marauder firmware to collect Wi-Fi/BLE attack telemetr… |
| 362 | [nandhakumard06-tech/Wolf-Jammer-IoT-](https://github.com/nandhakumard06-tech/Wolf-Jammer-IoT-) | 0 | — | Wolf Jammer IoT — ESP32-based WiFi security assessment tool for authorized pentesters. Supports d… |
| 363 | [nvinh5064-ctrl/esp8266_deauther.](https://github.com/nvinh5064-ctrl/esp8266_deauther.) | 0 | — | Affordable WiFi hacking platform for testing and learning |
| 364 | [open-is-all/berbel-remote](https://github.com/open-is-all/berbel-remote) | 0 | C++ | Berbel BFB 6bT Remote Bridge  ESP32-basiert Emulator für Berbel Dunstabzugshauben. Emuliert die B… |
| 365 | [ozarkplateautachinidae54/cyber-controller](https://github.com/ozarkplateautachinidae54/cyber-controller) | 0 | — | Manage security hardware and ESP32 devices from a single dashboard for cyberdecks and field opera… |
| 366 | [P-ZINS/-ESP32-Marauder-M5Stick](https://github.com/P-ZINS/-ESP32-Marauder-M5Stick) | 0 | — | Déploiement d'un outil de pentest WiFi/Bluetooth portable sur microcontrôleur ESP32. |
| 367 | [p4oT09/p4oT09](https://github.com/p4oT09/p4oT09) | 0 | — | 🔥 p4oT09 is an advanced WiFi exploitation toolkit ⚡ Made for pentesters, ethical hackers & resear… |
| 368 | [PawanKumarPandit/Esp8266_Wifi_Deauther](https://github.com/PawanKumarPandit/Esp8266_Wifi_Deauther) | 0 | C | Affordable WiFi hacking platform for testing and learning. |
| 369 | [Prajwalpawar1/evil-twin-wifi-](https://github.com/Prajwalpawar1/evil-twin-wifi-) | 0 | C++ | it is program which use to search all avilable wifi near to us and cheak password is valid or not… |
| 370 | [ralfs66/BLE-HID-HoneyPot](https://github.com/ralfs66/BLE-HID-HoneyPot) | 0 | C++ | This example turns the ESP32 into a Bluetooth LE Keyboard - Honeypot that runs RickRoll HID attac… |
| 371 | [recalde/garagewave](https://github.com/recalde/garagewave) | 0 | Python | Local-first ESPHome + CC1101 radio controller for compatible fixed-code garage doors, with Home A… |
| 372 | [Reuben123t/ESP-Hacker](https://github.com/Reuben123t/ESP-Hacker) | 0 | C++ | ESP32 hacking tool through Wifi and Bluetooth |
| 373 | [rrbaker00/BluetoothBaker](https://github.com/rrbaker00/BluetoothBaker) | 0 | C++ | A 2.4Ghz wifi and bluetooth jammer built on a ESP32 and 2 nrf24l01 antenna moduels that has multi… |
| 374 | [Seemab-Khan2336/Wireless-Interference-Analysis-ESP32](https://github.com/Seemab-Khan2336/Wireless-Interference-Analysis-ESP32) | 0 | Python | An experimental study on wireless interference and signal congestion in the 2.4 GHz ISM band. Usi… |
| 375 | [serplay/FishAI](https://github.com/serplay/FishAI) | 0 | Python | Giving a retro Billy Bass a new brain. ESP32 hardware hack featuring real-time lip-sync, Bluetoot… |
| 376 | [Shatwik7/ESP32-Quad-nRF24L01-Plus-Jammer-Multi-Band-2-4GHz-RF-Controller](https://github.com/Shatwik7/ESP32-Quad-nRF24L01-Plus-Jammer-Multi-Band-2-4GHz-RF-Controller) | 0 | — | ESP32-Quad-nRF24L01-Plus-Jammer is an open-source project for controlling four nRF24L01+ modules … |
| 377 | [ShellCMD101/Blackout-2.4](https://github.com/ShellCMD101/Blackout-2.4) | 0 | C | A sophisticated embedded cybersecurity project demonstrating real-world abuse, analysis, and expl… |
| 378 | [ShivamMathtech/ESP32-Dual-NRF24L01-RF-Test-Communication-Platform](https://github.com/ShivamMathtech/ESP32-Dual-NRF24L01-RF-Test-Communication-Platform) | 0 | C++ | > **Safety / legal note:** This project is documented as an RF communication and laboratory test … |
| 379 | [sriramnaidu2006/jammer-using-esp32](https://github.com/sriramnaidu2006/jammer-using-esp32) | 0 | — | A "jammer with ESP" generally refers to a DIY wireless interference or "deauther" project built o… |
| 380 | [SurhommeLee/scaryrf-plus](https://github.com/SurhommeLee/scaryrf-plus) | 0 | — | The firmware for ESP32 has WiFi, BLE and SubGHz functions. |
| 381 | [susantks/Cam-Cypher-Dual-Recon](https://github.com/susantks/Cam-Cypher-Dual-Recon) | 0 | HTML | 2026 Ultimate WiFi & Bluetooth Pentesting Toolkit for Dual ESP32-CAM Security Audits |
| 382 | [suvo2007/Nrfboom_Btl.](https://github.com/suvo2007/Nrfboom_Btl.) | 0 | — | NRF BOOM — an ESP32-based multi-tool for nRF24, BLE, and WiFi security testing (scanner, jammer, … |
| 383 | [tehnomozg/esp32sniffing](https://github.com/tehnomozg/esp32sniffing) | 0 | — | This is a collection of ESP32 WiFi and Bluetooth sniffing tools. They're designed for use with th… |
| 384 | [texalpha973-rgb/Esp32-IR-RF-ble-wifi](https://github.com/texalpha973-rgb/Esp32-IR-RF-ble-wifi) | 0 | C++ |  ​1. CAPTURE IR ​2. SAVED CODES ​3. TV SWEEP ​4. AC KILLER ​5. TV ROULETTE ​6. SIGNAL FUZZER ​7. … |
| 385 | [ThaVEL-FPE12/Flipper-C3](https://github.com/ThaVEL-FPE12/Flipper-C3) | 0 | — | Flipper Zero For ESP32 C3 |
| 386 | [vancipher/Mini-Bluetooth-Jammer](https://github.com/vancipher/Mini-Bluetooth-Jammer) | 0 | — | Educational ESP32+nRF demo showing how RF interference affects Bluetooth devices. |
| 387 | [WalderlanSena/prumoboard](https://github.com/WalderlanSena/prumoboard) | 0 | — | Prumo Board is an open hardware platform designed for education, research, and experimentation in… |
| 388 | [Xhanos0/esp32-bleujammer-board-emensta-](https://github.com/Xhanos0/esp32-bleujammer-board-emensta-) | 0 | — | this is a circle vercion of the esp32 ble/low ble/wifi/rc jammer (its not my project but i tought… |
| 389 | [yashwanth270405-creator/ESP32-WiFi-Bluetooth-Jammer](https://github.com/yashwanth270405-creator/ESP32-WiFi-Bluetooth-Jammer) | 0 | — | ESP32-based BLE and Bluetooth jammer project for studying wireless communication, signal interfer… |
| 390 | [yfe404/polar_h10_spoofer](https://github.com/yfe404/polar_h10_spoofer) | 0 | C++ | ESP32 BLE spoofer that emulates a Polar H10 heart rate monitor with ECG streaming |

### 射频/RF 攻击

> 共 **216** 个项目，按 Stars 降序排列。多标签项目会出现在多个分组。

| # | 项目 | Stars | 语言 | 简介 |
|---:|---|---:|---|---|
| 1 | [geo-tp/ESP32-Bit-Pirate](https://github.com/geo-tp/ESP32-Bit-Pirate) | 6,396 | C++ | A Hardware Hacking Tool with Web-Based CLI That Speaks Every Protocol  |
| 2 | [JesseCHale/HaleHound-CYD](https://github.com/JesseCHale/HaleHound-CYD) | 1,926 | — | ESP32-DIV HaleHound Edition for Cheap Yellow Display - Multi-protocol offensive security toolkit |
| 3 | [7h30th3r0n3/Raspyjack](https://github.com/7h30th3r0n3/Raspyjack) | 1,343 | Python | Small offensive network toolkit for Raspberry Pi (+ Waveshare 1.44″ LCD HAT) and Cardputer Zero i… |
| 4 | [GhostESP-Revival/GhostESP](https://github.com/GhostESP-Revival/GhostESP) | 1,162 | C | The open-source wireless research platform for ESP32. |
| 5 | [HKSSY/Drone-Hacking-Tool](https://github.com/HKSSY/Drone-Hacking-Tool) | 703 | Python | Drone Hacking Tool is a GUI tool that works with a USB Wifi adapter and HackRF One for hacking dr… |
| 6 | [HighCodeh/TentacleOS](https://github.com/HighCodeh/TentacleOS) | 512 | C | Firmware High Boy |
| 7 | [mcore1976/cc1101-tool](https://github.com/mcore1976/cc1101-tool) | 489 | C++ | RF tool based on CC1101 module and Arduino Pro Micro 8VMHz/3.3V. Allows using CLI with human read… |
| 8 | [zszszszsz/.config](https://github.com/zszszszsz/.config) | 372 | Shell | # # Automatically generated file; DO NOT EDIT. # OpenWrt Configuration # CONFIG_MODULES=y CONFIG_… |
| 9 | [rfquack/RFQuack](https://github.com/rfquack/RFQuack) | 350 | C++ | RFQuack: the versatile RF-analysis tool that quacks! |
| 10 | [Teapot174/ESP-HACK](https://github.com/Teapot174/ESP-HACK) | 313 | C++ | Open Source ESP32 Project for Pentesting. |
| 11 | [FernandoHansen666/ScaryRF-315-433mhz](https://github.com/FernandoHansen666/ScaryRF-315-433mhz) | 298 | C |  RF HACK • ESP32 + CC1101 • Sub-GHz RF Tool |
| 12 | [itsdarklikehell-interactive/pwnagotchi-plugins](https://github.com/itsdarklikehell-interactive/pwnagotchi-plugins) | 234 | Python | Collectie van Pwnagotchi-plugins voor Wi-Fi auditing en pentesting op Raspberry Pi. |
| 13 | [Hiktron/Hizmos](https://github.com/Hiktron/Hizmos) | 228 | C | ⚡ HIZMOS — An open-source, powerful alternative to Flipper Zero. Built on ESP32-S3, designed for … |
| 14 | [Electro-Gamma/ESP32-Quad-nRF24L01-Plus-Jammer-Multi-Band-2-4GHz-RF-Controller](https://github.com/Electro-Gamma/ESP32-Quad-nRF24L01-Plus-Jammer-Multi-Band-2-4GHz-RF-Controller) | 192 | C++ | ESP32-Quad-nRF24L01-Plus-Jammer is an open-source project for controlling four nRF24L01+ modules … |
| 15 | [pepeangell5/ESP32-TOOLS-PRO-480x320-V2.0](https://github.com/pepeangell5/ESP32-TOOLS-PRO-480x320-V2.0) | 191 | C++ | ESP32-TOOLS-PRO-480x320-V2.0 expande la V1.0 con soporte para módulos IR M5Stack y CC1101. Añade … |
| 16 | [0xless/433mhz_jam](https://github.com/0xless/433mhz_jam) | 163 | C++ | Simple WiFi controlled 433Mhz radio jammer based on ESP32/ESP8266 and FS1000A |
| 17 | [simondankelmann/Esp32-SubGhz](https://github.com/simondankelmann/Esp32-SubGhz) | 145 | Kotlin |  |
| 18 | [OzInFl/WaveSentinelPublic---Squareline-Studio-UI-CC1101---ESP32](https://github.com/OzInFl/WaveSentinelPublic---Squareline-Studio-UI-CC1101---ESP32) | 100 | C | WT32-SC01-PLUS Module With SubGhz, Wifi and Bluetooth - Using CC1101, Able to play .sub files fro… |
| 19 | [W0rthlessS0ul/CC1101_jammer](https://github.com/W0rthlessS0ul/CC1101_jammer) | 99 | C | CC1101 Jammer is a powerful tool that requires an ESP32 and a CC1101 module to assemble. It is de… |
| 20 | [LxveAce/cyber-controller](https://github.com/LxveAce/cyber-controller) | 97 | Python | The all-in-one security hardware controller for cyberdecks & field deployments — flash, control &… |
| 21 | [hugorezende/nRF24L01-WiFi-Jammer](https://github.com/hugorezende/nRF24L01-WiFi-Jammer) | 91 | C++ | Code to create some noise with nRF24L01 and interfere on the 2.4GHz spectrum |
| 22 | [dkyazzentwatwa/cypher-pulse](https://github.com/dkyazzentwatwa/cypher-pulse) | 65 | C++ | A versatile ESP32 sub-ghz jammer w/ 2 CC1101 radio modules. |
| 23 | [dkyazzentwatwa/cypher-jammer-3NRF24](https://github.com/dkyazzentwatwa/cypher-jammer-3NRF24) | 58 | C++ | An ESP32 BT + WiFi Jammer w/ 3 NRF24 modules. |
| 24 | [brianwalczak/BKFZ-SubGHz](https://github.com/brianwalczak/BKFZ-SubGHz) | 54 | C++ | A robust Arduino project for your ESP32 and CC1101 to capture, replay, and analyze nearby SubGHz … |
| 25 | [HoneyHoneyTeam/ESP32.Marauder.Double.Barrel.5G.by.ESP32.C5](https://github.com/HoneyHoneyTeam/ESP32.Marauder.Double.Barrel.5G.by.ESP32.C5) | 53 | — | The version of Double Barrel 5G is packed with 1 * ESP32 chipset & 1 * ESP32 C5 chipset, GPS, Sub… |
| 26 | [Seyitq/nrf24l01-wifi-jammer](https://github.com/Seyitq/nrf24l01-wifi-jammer) | 52 | C++ | The activity of the nRF24 RF radio board is transmitted to the Arduino board via the serial inter… |
| 27 | [666sempron999/HackRF_ONE-wifi-jammer](https://github.com/666sempron999/HackRF_ONE-wifi-jammer) | 49 | Python | Tis repository is proof of concept wifi denial of service (DOS) on phisical layer |
| 28 | [arpitxp/Bruce-Smoochie-esp32](https://github.com/arpitxp/Bruce-Smoochie-esp32) | 48 | — | Standalone ESP32-S3 wireless pentesting deck built on Bruce firmware alternate to Flipper Zero, s… |
| 29 | [hadis898/esp32-jammer](https://github.com/hadis898/esp32-jammer) | 48 | — | ESP32-BlueJammer（蓝牙干扰器、BLE干扰器、WiFi干扰器、遥控干扰器）是一种针对2.4GHz通信频段的定向干扰设备。该设备基于ESP32主控芯片与nRF24模块构建，通过发射噪… |
| 30 | [shizakken/cheetah](https://github.com/shizakken/cheetah) | 44 | Rust | Portable WiFi/Bluetooth/RF-433MHz hacking tool |
| 31 | [b1scuitdev/E07xESP32C5](https://github.com/b1scuitdev/E07xESP32C5) | 36 | — | E07xESP32C5 is a Sub-GHz & ESP32-C5 module for Flipper Zero. It includes an EBYTE E07-433M20S (PA… |
| 32 | [pingequalab/cardputer-adv-hydra-rf](https://github.com/pingequalab/cardputer-adv-hydra-rf) | 36 | — | CC1101 + nRF24 dual-band RF expansion module for M5Stack Cardputer ADV. Supports 433/868/915 MHz … |
| 33 | [HoneyHoneyTeam/ESP32-Marauder-Double-Barrel](https://github.com/HoneyHoneyTeam/ESP32-Marauder-Double-Barrel) | 35 | — | The ESP32 Marauder Double Barrel includes two ESP32 chipsets, GPS, Sub-GHz (433 MHz) and an onboa… |
| 34 | [HoneyHoneyTeam/ESP32-Marauder-Double-Barrel-5G](https://github.com/HoneyHoneyTeam/ESP32-Marauder-Double-Barrel-5G) | 35 | — | 1 * ESP32 chipset & 1 * BW16 chipset, GPS, Sub-GHz (433 MHz) and an onboard battery. It works wit… |
| 35 | [usamahacker0/RF-Mirage](https://github.com/usamahacker0/RF-Mirage) | 35 | HTML | Sub Ghz Radio Frequency Penetration testing Device. |
| 36 | [HoneyHoneyTeam/ESP32-Marauder-5G-Apex-5-Module---For-Flipper-Zero](https://github.com/HoneyHoneyTeam/ESP32-Marauder-5G-Apex-5-Module---For-Flipper-Zero) | 32 | — | Apex 5 Module include 5 major functions into one single board, ESP32-C5 (5G Wifi Capabliity), dua… |
| 37 | [sha1cybr/esp32-cc1101-rf-caprep](https://github.com/sha1cybr/esp32-cc1101-rf-caprep) | 30 | C++ | ESP32 + CC1101 RF signal capture and replay tool. Record, analyze, and retransmit radio frequency… |
| 38 | [ASP-29/ZeroX32](https://github.com/ASP-29/ZeroX32) | 29 | HTML | The Multi-tool device has a lot of feature,including WIFi,Bluetooth,HID,Infrared,Sub-Ghz,NRF24L01… |
| 39 | [HoneyHoneyTeam/3in1-WIFI-MultiBoard-with-Screen](https://github.com/HoneyHoneyTeam/3in1-WIFI-MultiBoard-with-Screen) | 29 | — | 3in1 WIFI board for Flipper Zero, ESP32 / Marauder + NRF24 + CC1101 by Honey Honey Lab |
| 40 | [jah64/Rothult-ESPeasy](https://github.com/jah64/Rothult-ESPeasy) | 29 | — | Hacking an IKEA Rothult NFC lock to be remotely controlled by a ESP8266 WiFi module |
| 41 | [MarauTech/ESP-GRABER](https://github.com/MarauTech/ESP-GRABER) | 27 | — | ESP-GRABBER is a powerful RF tool for ESP32 + CC1101. It can read, repeat, analyze, store, and ja… |
| 42 | [zeefaad/Jammer-433MHZ-ESP32](https://github.com/zeefaad/Jammer-433MHZ-ESP32) | 27 | C++ | The aim of this project is to design a 433MHz rf jammer using the CC1101 module and the ESP32 (ES… |
| 43 | [GeneralDussDuss/poseidon-tembed](https://github.com/GeneralDussDuss/poseidon-tembed) | 26 | Python | POSEIDON for the LilyGO T-Embed CC1101 Plus - 128 features, 5 onboard radios, browser flasher |
| 44 | [salman1123/Wifi-hacking-](https://github.com/salman1123/Wifi-hacking-) | 24 | — |                                              #!/usr/bin/env python import os import subprocess fr… |
| 45 | [GthiN89/NucleusGateKeeper](https://github.com/GthiN89/NucleusGateKeeper) | 20 | C++ | Nucleus Gate Keeper is a specialized, compact, and cost-effective device for capturing Sub-GHz RF… |
| 46 | [ccadic/HackZeGarage](https://github.com/ccadic/HackZeGarage) | 19 | C++ | ESP32-S2 and CC1101S 433Mhz usb stick to record and send car gates/garages data keys and open stuff |
| 47 | [Th3-Priest/vigilance](https://github.com/Th3-Priest/vigilance) | 19 | C++ | Defensive surveillance HUD firmware for the LilyGo T-Embed CC1101 Plus (a Bruce fork). |
| 48 | [Retr0Kr0dy/BeamStalker](https://github.com/Retr0Kr0dy/BeamStalker) | 17 | C | BeamStalker is open-source firmware for esp based board designed for RF experimentation, encourag… |
| 49 | [huaminghuangtw/ESP32WiFiSnifferApp](https://github.com/huaminghuangtw/ESP32WiFiSnifferApp) | 16 | C++ | 📌 An interdisciplinary team project of the course Software Lab at Technical University of Munich … |
| 50 | [RadDad87/C3RB3RU5](https://github.com/RadDad87/C3RB3RU5) | 16 | HTML | C3RB3RU5 web flasher for CiferTech ESP32-DIV (V2, S3) — flash 2.4GHz WiFi/BLE/SubGHz pentest firm… |
| 51 | [CyberDuckyiq/IshtarRF](https://github.com/CyberDuckyiq/IshtarRF) | 15 | Python | IshtarRF — Sub-GHz rx/tx for ESP32 + CC1101. |
| 52 | [G4MEOVER18/FlipperJammer](https://github.com/G4MEOVER18/FlipperJammer) | 14 | C | Flipper Zero Jammer Suite: SubGHz/NRF24/BLE/WiFi/IR/RFID/NFC/USB — Momentum API 87.1 |
| 53 | [nistordarius26h-ship-it/esp32s3-brucey](https://github.com/nistordarius26h-ship-it/esp32s3-brucey) | 14 | — | Custom ESP32-S3 Bruce handheld with CC1101, NRF24L01+, PN532, SSD1306 OLED, MicroSD, IR and LiPo … |
| 54 | [pingequalab/cardputer-adv-cc1101-nrf24-auto-switch](https://github.com/pingequalab/cardputer-adv-cc1101-nrf24-auto-switch) | 14 | — | Open-source design reference for software-defined dual-band CC1101 + NRF24 RF expansion on M5Stac… |
| 55 | [omeryos/ESP32-WIFI-JAMMER](https://github.com/omeryos/ESP32-WIFI-JAMMER) | 13 | C++ | 2.4Ghz Wifi networks spot jamming device, utilizing ESP32 and nRF24L01+  |
| 56 | [mildcrime/VARSYS](https://github.com/mildcrime/VARSYS) | 12 | C | Modular security-research firmware for LILYGO T-Embed CC1101 (ESP32-S3) — Flipper-class multitool… |
| 57 | [rgomez31UAQ/Poseidon-Cardputer-Adv_Firmware](https://github.com/rgomez31UAQ/Poseidon-Cardputer-Adv_Firmware) | 12 | C++ | Firmware de pruebas de penetración con más de 80 funciones para M5Stack Cardputer-Adv. WiFi, BLE,… |
| 58 | [at0m-b0mb/Trident-FlipperZero](https://github.com/at0m-b0mb/Trident-FlipperZero) | 11 | C | Trident — one Flipper Zero app for a 3-in-1 ESP32 + NRF24 + CC1101 expansion board: Wi-Fi/BT via … |
| 59 | [Epickitrolaz/nRF24-Jammer](https://github.com/Epickitrolaz/nRF24-Jammer) | 11 | C++ | A very simple, optimized ESP32 Wroom + nRF24 bluetooth jammer |
| 60 | [GeneralDussDuss/davey-jones](https://github.com/GeneralDussDuss/davey-jones) | 11 | C | Multi-radio pentesting firmware for Arduino Nesso N1 (ESP32-C6 + SX1262). WiFi/BLE/Sub-GHz/IR/Zig… |
| 61 | [romankalyna/RFsquek](https://github.com/romankalyna/RFsquek) | 11 | C++ | ESP32 + CC1101 RF spectrum scanner and Morse communicator |
| 62 | [deepalgorithm/RFJamming-FMRadio-SDR](https://github.com/deepalgorithm/RFJamming-FMRadio-SDR) | 10 | Python | Wifi Jamming and FM Radio with Software Defined Radio |
| 63 | [Lab217MX/Kraken-Kit](https://github.com/Lab217MX/Kraken-Kit) | 10 | Python | PCB personalizada que expande el proyecto [ESP32-Bus-Pirate](https://github.com/geo-tp/ESP32-Bus-… |
| 64 | [lierda-iot/esp32_lora_driver](https://github.com/lierda-iot/esp32_lora_driver) | 10 | C | ESP-IDF driver for Semtech LR2021 / LR20xx radios: FLRC at 2.6 Mbit/s air rate, about 2.2 Mbit/s … |
| 65 | [rgomez31UAQ/Poseidon_Cardputer-ADV_Firmware](https://github.com/rgomez31UAQ/Poseidon_Cardputer-ADV_Firmware) | 10 | — | Firmware de pruebas de penetración con más de 80 funciones para M5Stack Cardputer-Adv. WiFi, BLE,… |
| 66 | [koua29/bruce-ble-finder](https://github.com/koua29/bruce-ble-finder) | 9 | JavaScript | Traqueur de proximité Bluetooth (radar RSSI, script JS) pour le firmware Bruce — LilyGO T-Embed C… |
| 67 | [mynameisnotjohnny/the-jester](https://github.com/mynameisnotjohnny/the-jester) | 9 | C++ | A fully open-source Bluetooth and BLE jammer based on the RF-Clown project by cifertech. This imp… |
| 68 | [omairtemurian/Roadstar-TV---IR](https://github.com/omairtemurian/Roadstar-TV---IR) | 8 | — | 📡 Road Star RF Controller for Lilygo T-Embed This repository contains the firmware and web-based … |
| 69 | [parsapoorsh/waveduino](https://github.com/parsapoorsh/waveduino) | 8 | C++ | replay attack 433Mhz RF using ESP8266 (or arduino) |
| 70 | [ZeroNodeDIY/gate-control](https://github.com/ZeroNodeDIY/gate-control) | 8 | — | ESP32-C3 Super Mini and CC1101 Sub-GHz gate controller with OLED interface, RAW OOK/ASK signal ca… |
| 71 | [5h4d0wn1k/h2-ble-tracker](https://github.com/5h4d0wn1k/h2-ble-tracker) | 7 | C++ | BLE tracker and sniffer - Bluetooth Low Energy advertising scanning and device fingerprinting. |
| 72 | [aingram702/SubGHzuki](https://github.com/aingram702/SubGHzuki) | 7 | C++ | A firmware project for the LilyGO T-Embed CC1101 Plus ESP32-S3 |
| 73 | [bollgio/BruceIRF](https://github.com/bollgio/BruceIRF) | 7 | C++ | BruceIRF - ESP32 firmware fork (Bruce 1.16) with Universal IR + RF modules, RF+IR Dual Detector, … |
| 74 | [Ghael-V/LilyOS](https://github.com/Ghael-V/LilyOS) | 7 | C | Custom LVGL-based firmware for the LilyGo T-Embed CC1101 (ESP32-S3): WiFi auditing (deauth, hands… |
| 75 | [Snifi0/Sniffer](https://github.com/Snifi0/Sniffer) | 7 | — | Multitool! |
| 76 | [toprakahmetaydogmus/esp8266-nrf24-jammer](https://github.com/toprakahmetaydogmus/esp8266-nrf24-jammer) | 7 | C++ | ESP8266 + nRF24L01 2.4GHz RF Signal Testing, Spectrum Analysis & Simulation Tool with Web UI |
| 77 | [touhidshaikh/Wireless-Pentest-Cheatsheet](https://github.com/touhidshaikh/Wireless-Pentest-Cheatsheet) | 7 | — | The Wireless Pentest cheat sheet was created to provide concise collection of high value informat… |
| 78 | [5h4d0wn1k/h13-wifi-jammer](https://github.com/5h4d0wn1k/h13-wifi-jammer) | 6 | C++ | Wi-Fi jamming and resilience research - interference testing against own-lab networks. |
| 79 | [5h4d0wn1k/h14-lora-attack](https://github.com/5h4d0wn1k/h14-lora-attack) | 6 | C++ | LoRa RF security toolkit - packet capture, replay and demodulation on 433/868 MHz. |
| 80 | [5h4d0wn1k/h3-zigbee-sniffer](https://github.com/5h4d0wn1k/h3-zigbee-sniffer) | 6 | C++ | Zigbee/Thread IEEE 802.15.4 packet sniffer for ESP32-C6 — frame capture, header decoding, device … |
| 81 | [5h4d0wn1k/h5-433-replay](https://github.com/5h4d0wn1k/h5-433-replay) | 6 | C++ | 433 MHz RF replay toolkit - capture and retransmit sub-GHz remote signals for hardware testing. |
| 82 | [Axagt40/Vandeta](https://github.com/Axagt40/Vandeta) | 6 | C++ | Bruce (1.16.1) modded for the LilyGo T-Embed CC1101 Plus |
| 83 | [mineiwik/CoralWave](https://github.com/mineiwik/CoralWave) | 6 | — | Custom Sub-GHz Transceiver Gateway |
| 84 | [YM2992/Reverb](https://github.com/YM2992/Reverb) | 6 | TypeScript | A web interface to view and replay sub-GHz RF signals, connecting to your ESP32/CC1101 device ove… |
| 85 | [5h4d0wn1k/h10-usb-hid](https://github.com/5h4d0wn1k/h10-usb-hid) | 5 | C++ | USB HID attack tool - programmable keystroke-injection payloads for hardware security testing. |
| 86 | [5h4d0wn1k/h4-mousejack](https://github.com/5h4d0wn1k/h4-mousejack) | 5 | C++ | nRF24 protocol-hacking research lab — ESP32 + nRF24L01+ firmware that scans all 41 channels, snif… |
| 87 | [Albertokeroro/edge-ai-lora-anomaly-detection](https://github.com/Albertokeroro/edge-ai-lora-anomaly-detection) | 5 | C | Real-time Edge AI LoRa jamming and RF anomaly detector for the Heltec (V3/V4) ESP32-S3 |
| 88 | [Bulletb8/ESP32-DIV-CarPopper](https://github.com/Bulletb8/ESP32-DIV-CarPopper) | 5 | C++ | Fork of cifertech/ESP32-DIV with Car Popper RKE module added to SubGHz menu |
| 89 | [CyberDuckyiq/IshtarRF-Android](https://github.com/CyberDuckyiq/IshtarRF-Android) | 5 | Kotlin | Android app (Kotlin + Jetpack Compose) for an ESP32 + CC1101 Sub-GHz   RF tool over USB-OTG — rec… |
| 90 | [Mohnki/dragotchi-flipper](https://github.com/Mohnki/dragotchi-flipper) | 5 | C | Dragotchi — a dragon virtual pet for the Flipper Zero that hunts the real airwaves (sub-GHz + opt… |
| 91 | [oliverstraus246-beep/the-reaper](https://github.com/oliverstraus246-beep/the-reaper) | 5 | C++ | Multi-band ESP32-S3 wireless pentesting toolkit - WiFi, BLE, 2.4GHz, Sub-GHz, IR, RFID/NFC, GPS. … |
| 92 | [Scissors2099/ScissorsJammer-v6.5-Spectre-Trident-Edition](https://github.com/Scissors2099/ScissorsJammer-v6.5-Spectre-Trident-Edition) | 5 | C++ | Estación portátil de auditoría analítica y defensa de capa física en 2.4 GHz basada en ESP32 y nR… |
| 93 | [Volkov997/pen-card](https://github.com/Volkov997/pen-card) | 5 | — | RF Pentesting tool, but small enough for your wallet. Features: Wifi & Bluetooth, NFC, IR, (Sub G… |
| 94 | [w1ld3r/Raspi_Hackbox](https://github.com/w1ld3r/Raspi_Hackbox) | 5 | CSS | Debian Trixie Raspberry Pi 4 image builder for IoT, OT, automotive & RF/SDR pentesting — i3 + zsh… |
| 95 | [codebyant/esphome-rf-cloner](https://github.com/codebyant/esphome-rf-cloner) | 4 | Python | Learn and replay sub-GHz RF remote commands at runtime on ESP32 + CC1101, with a Home Assistant i… |
| 96 | [Exora-Lab/BW16-NRF24-jammer](https://github.com/Exora-Lab/BW16-NRF24-jammer) | 4 | C++ | BW16+ NRF24 constant carrier generator with automatic channel hopping for BW16/RTL8720DN. Creates… |
| 97 | [fatihyldz58/nRF24-BT-Jammer](https://github.com/fatihyldz58/nRF24-BT-Jammer) | 4 | C++ | A powerful 2.4GHz RF testing and Bluetooth interference research tool using ESP32 and dual nRF24L… |
| 98 | [Hexamora/ESP32-Wifi-Jammer](https://github.com/Hexamora/ESP32-Wifi-Jammer) | 4 | — | 📡 ESP32 + NRF24L01 PA LNA 2.4GHz RF tester \| No-solder breadboard build \| Webserver control int… |
| 99 | [K3lgy/Flipper-Zero-Audit-Kit-](https://github.com/K3lgy/Flipper-Zero-Audit-Kit-) | 4 | Python | Kit d'audit de sécurité physique pour Flipper Zero. Parse automatiquement les exports de la carte… |
| 100 | [kqzalf/Rootsignal-ESP32](https://github.com/kqzalf/Rootsignal-ESP32) | 4 | Python | RootSignal-ESP32 is a lightweight, MicroPython-based wireless anomaly detector that runs on moder… |
| 101 | [krolyxon/orion-rf](https://github.com/krolyxon/orion-rf) | 4 | C++ | Portable RF and wireless toolkit built on ESP32-S3 |
| 102 | [MicrochipTech/atsamr34_lorawan_wifi_ap_scan](https://github.com/MicrochipTech/atsamr34_lorawan_wifi_ap_scan) | 4 | C | “IoT Made Easy!" - Adding Wi-Fi Sniffing to an existing LoRaWAN Application |
| 103 | [my-project-droid/Hackbat-MultiToolhacking-OS1](https://github.com/my-project-droid/Hackbat-MultiToolhacking-OS1) | 4 | C++ | An open-source multi-tool firmware for the RP2040 Hackbat. Unifies sub-1GHz RF (CC1101), NFC (PN5… |
| 104 | [random-robbie/Flipper-SubGhz-RAW-to-ESP32-C-Array-Converter](https://github.com/random-robbie/Flipper-SubGhz-RAW-to-ESP32-C-Array-Converter) | 4 | Python | Flipper SubGhz RAW to ESP32 C Array Converter |
| 105 | [the0r4cle/JasperRF](https://github.com/the0r4cle/JasperRF) | 4 | C++ | ESP32 + CC1101 sub-GHz RF multi-tool with web UI. Sniff, record, replay, brute-force (De Bruijn),… |
| 106 | [Zebratic/esp32-433mhz-rf-controller](https://github.com/Zebratic/esp32-433mhz-rf-controller) | 4 | C | ESP32 RF Controller & Repeater - Trigger Sub GHz signals using a RESTful API |
| 107 | [Ahmed-Ahmed16/variOne-2](https://github.com/Ahmed-Ahmed16/variOne-2) | 3 | C++ | Handheld ESP32-S3 wireless-security awareness device. Wi-Fi, BLE, Sub-GHz, NFC, IR & more. CIC Ne… |
| 108 | [AlbanoL/Sniffer_WiFi_ESP32_LoRa_TTN](https://github.com/AlbanoL/Sniffer_WiFi_ESP32_LoRa_TTN) | 3 | — | Contador de pessoas usando análise de pacotes WiFi. Projeto para o curso CPS 731/COPPE. |
| 109 | [danya201272/ESP32-WIFI-WebSerial-433Mhz](https://github.com/danya201272/ESP32-WIFI-WebSerial-433Mhz) | 3 | C++ | ESP32 with app interface remoteXY and grab and sent code. Bruteforce Came and Nice. Have a Jammer… |
| 110 | [FOXIK-Lab/esp-stun](https://github.com/FOXIK-Lab/esp-stun) | 3 | Python | ESP32 Firmware for Pentesting. |
| 111 | [hubb22/Wi-Fi-Bluetooth-and-RTL-SDR-Jamming-Alarm-System](https://github.com/hubb22/Wi-Fi-Bluetooth-and-RTL-SDR-Jamming-Alarm-System) | 3 | — | WiFi Jammer Alarm. Detects attacks on Wi-Fi, Bluetooth and 433 MHz frequency devices. Wi-Fi Jamme… |
| 112 | [Isno-Open/OpenSuperRF](https://github.com/Isno-Open/OpenSuperRF) | 3 | — | Design ouvert de la carte radio ISNO Super v1.0 (ESP32-S3, CC1101 433/868) pour firmwares radio c… |
| 113 | [kylecmathias/FlipperInfinity](https://github.com/kylecmathias/FlipperInfinity) | 3 | C | Handheld multi-protocol signal analysis device — NFC, RFID, sub-GHz RF, IR, and WiFi on a custom … |
| 114 | [lank-one/ESPectro](https://github.com/lank-one/ESPectro) | 3 | — | DIY multi-function pentesting device (ESP32 + CC1101 + OLED) built on the ESP-HACK firmware. Hard… |
| 115 | [nicolaij/tpms](https://github.com/nicolaij/tpms) | 3 | C++ | TPMS Geely Coolray (SX11) hack |
| 116 | [oscarmh/CC1101-ESP32](https://github.com/oscarmh/CC1101-ESP32) | 3 | C | Sub Ghz scanner with 3 CC1101 and ESP32C6 |
| 117 | [popdoop/Esp32-s3-jammer-for-if-you-only-have-1-nRF24L0-PA-LNA-](https://github.com/popdoop/Esp32-s3-jammer-for-if-you-only-have-1-nRF24L0-PA-LNA-) | 3 | C++ | ***FOR EDUCATIONAL PURPOSES*** code is kinda wack// but it works.  |
| 118 | [project-1871/hailhound-laptop](https://github.com/project-1871/hailhound-laptop) | 3 | Python | GTK4 Linux security toolkit — WiFi, BLE, SubGHz, RFID, jamming detection |
| 119 | [Somashekharh/Ethical-Hacking-GadgetHub](https://github.com/Somashekharh/Ethical-Hacking-GadgetHub) | 3 | — | A collection of hardware-based ethical hacking tools and guides for penetration testing, includin… |
| 120 | [the78mole/moles-integ-dtu-hw](https://github.com/the78mole/moles-integ-dtu-hw) | 3 | — | This is a small module for use of ESP32 with a sub-GHZ transceiver, mainly intended to serve as a… |
| 121 | [toprakahmetaydogmus/uts-jam](https://github.com/toprakahmetaydogmus/uts-jam) | 3 | C++ | UTS-JAM Ultimate - ESP32-C3 SuperMini Dual nRF24 2.4GHz RF Spectrum Analyzer & Security Lab Device |
| 122 | [absolute-xero7/kestrel](https://github.com/absolute-xero7/kestrel) | 2 | C++ | Pocket RF & wireless recon multitool firmware for the ESP32 Cheap Yellow Display — WiFi/BLE + CC1… |
| 123 | [AedanJaeson/subghz-sdr-video-telemetry-lab](https://github.com/AedanJaeson/subghz-sdr-video-telemetry-lab) | 2 | Jupyter Notebook | Guided SDR/RF/DSP lab for low-rate ESP32-CAM to CC1101 to RTL-SDR image telemetry |
| 124 | [Ankitkushwaha90/wifi_jammer_hijacking](https://github.com/Ankitkushwaha90/wifi_jammer_hijacking) | 2 | — | This note provides a concise, practical overview of wireless communications, SDR, and ethical Wi-… |
| 125 | [archrampart/zero-cmd](https://github.com/archrampart/zero-cmd) | 2 | JavaScript | Web-based command center for Flipper Zero — Screen mirror, file manager, Sub-GHz, NFC, IR, Bad US… |
| 126 | [bartman081523/CMT2300A](https://github.com/bartman081523/CMT2300A) | 2 | C++ | ESP32 + CMT2300A sub-GHz transceiver: driver, WebUI, iM871A/wmbusmeters HCI shim, STM8 SWIM tooli… |
| 127 | [cashoefman/Resto-Score-for-Hack-2021-for-Positivity](https://github.com/cashoefman/Resto-Score-for-Hack-2021-for-Positivity) | 2 | Python | Resto Score connect a Heltec LoRaWAN 32, Heltec Wifi Kit 32 or Generic ESP32 Devkit to Google IoT… |
| 128 | [Eivs/BeeperTX](https://github.com/Eivs/BeeperTX) | 2 | C | ESP32-S3 + Si4463 dual-protocol (POCSAG / FLEX) pager transmitter with a web UI, serial CLI, WiFi… |
| 129 | [ghost00318/IshtarRF-Android](https://github.com/ghost00318/IshtarRF-Android) | 2 | Kotlin | Control Sub-GHz radio modules via USB-OTG. The native Android app captures, transmits, and visual… |
| 130 | [GlomarGadaffi/t-mixrf-idf](https://github.com/GlomarGadaffi/t-mixrf-idf) | 2 | C | Pure ESP-IDF driver suite for LILYGO T-MixRF: LR1121 dual-band LoRa, CC1101 sub-GHz, nRF24L01+, S… |
| 131 | [killindodo/Dodo-RF](https://github.com/killindodo/Dodo-RF) | 2 | Kotlin | ESP32 based open-source, ultra-portable Sub-GHz radio analysis, capture, and replay |
| 132 | [magikh0e/pueo](https://github.com/magikh0e/pueo) | 2 | C++ | A handheld multi-radio field tool. ESP32 firmware for the cheap yellow display, with CC1101 sub-G… |
| 133 | [Maytastico/PSec_RollingCode](https://github.com/Maytastico/PSec_RollingCode) | 2 | C++ | Rolling Code implementation for practical security workshop. The code is based on the CC1101 Sub … |
| 134 | [mytechnotalent/meshcore-sniffer](https://github.com/mytechnotalent/meshcore-sniffer) | 2 | C++ | A lightweight, dedicated firmware for the ESP32-S3 and SX1262 LoRa module designed to passively s… |
| 135 | [neilmanfredit/CyberDeck](https://github.com/neilmanfredit/CyberDeck) | 2 | C++ | Portable pentest cyberdeck — NUC-based clamshell with an embedded ESP32-S3 security module (sub-G… |
| 136 | [neohiro/lora-sniffer](https://github.com/neohiro/lora-sniffer) | 2 | C++ | Passive LoRa sniffer firmware for the Heltec WiFi LoRa 32 V4, built to run as its own slot alongs… |
| 137 | [nmicic/URTB](https://github.com/nmicic/URTB) | 2 | C | Encrypted PTY tunnel over ESP-NOW/LoRa radio links or untrusted jump hosts — XChaCha20-Poly1305 |
| 138 | [P5YB3RN4UT/ESP32-SubGHz-Jammer](https://github.com/P5YB3RN4UT/ESP32-SubGHz-Jammer) | 2 | C++ | Source code for a Sub-GHz Jammer controlled by ESP32 |
| 139 | [shahafel/wifi-jammer](https://github.com/shahafel/wifi-jammer) | 2 | — | python script using hackrf to jam wifi signals |
| 140 | [Thilakkumar0308/IRUTESAM-Dark-Venom](https://github.com/Thilakkumar0308/IRUTESAM-Dark-Venom) | 2 | C++ | IRUTESAM is an ESP32-based IoT hacking toolkit with a custom hacker-style touchscreen UI. It supp… |
| 141 | [Vagalam88/FreqSniff](https://github.com/Vagalam88/FreqSniff) | 2 | C++ | Combined WiFi + LoRa/Meshtastic passive sniffer for the Heltec WiFi LoRa32 V2 |
| 142 | [YurilLAB/esp32-SnowOwl](https://github.com/YurilLAB/esp32-SnowOwl) | 2 | — | A multi-purpose wireless offensive & defensive security multitool — ESP32-S3 + ARM Linux, with NF… |
| 143 | [zest988/ESP8266-nRF24-Jammer](https://github.com/zest988/ESP8266-nRF24-Jammer) | 2 | C++ | 2.4 GHz signal jammer using ESP8266 D1 and nRF24L01+ with web interface |
| 144 | [Abhishek1033ubuntu/Dynamic-Speed-Limiter-ESP32](https://github.com/Abhishek1033ubuntu/Dynamic-Speed-Limiter-ESP32) | 1 | C++ | An infrastructure-to-vehicle (I2V) wireless speed-control system that dynamically restricts maxim… |
| 145 | [abocconi/esp32_subghz_sniffer](https://github.com/abocconi/esp32_subghz_sniffer) | 1 | C | Sub-Ghz sniffer |
| 146 | [AtherNet29/ESP32-DEAUTHER-DAN-EVILTWIN-AETHERNET](https://github.com/AtherNet29/ESP32-DEAUTHER-DAN-EVILTWIN-AETHERNET) | 1 | — | 🎯 ESP32 Deauther & BT Jammer. Features: Evil Twin, Auto-Password Verify, Beacon Spam, Rogue AP, W… |
| 147 | [bdini13/esp32-cc1101-multiband](https://github.com/bdini13/esp32-cc1101-multiband) | 1 | Python | Work-in-progress ESP32-WROOM-32E + CC1101 multiband PCB: software-selected 315/433/868/915 MHz pa… |
| 148 | [bixente11/Waveshare-ESP32-S3-Touch-LCD-3.49-CC1101-LVGL-9.3](https://github.com/bixente11/Waveshare-ESP32-S3-Touch-LCD-3.49-CC1101-LVGL-9.3) | 1 | C++ | SubGhz with Waveshare ESP32-S3-Touch-LCD-3.49  |
| 149 | [COF10/MicroByte](https://github.com/COF10/MicroByte) | 1 | — | MicroByte is a compact handheld wireless tool built around the Waveshare ESP32-C6-LCD-1.47, featu… |
| 150 | [crackerbyte/esp-cracker](https://github.com/crackerbyte/esp-cracker) | 1 | — | 🍪 Cracker - DIY pentest device on ESP32-S3 with Wi-Fi, BLE, IR, Sub-GHz, 2.4GHz, GPS, NFC, Bad-US… |
| 151 | [electgpl/LoFi56kBridge](https://github.com/electgpl/LoFi56kBridge) | 1 | C++ | Sub-GHz 915 MHz GFSK bridge that turns two ESP32-S3 into a ~40 kbps slow internet link — like a 5… |
| 152 | [GeneralDussDuss/hephaestus](https://github.com/GeneralDussDuss/hephaestus) | 1 | C++ | The forge: a Claude Code plugin for discovering, prototyping, and defending novel embedded/RF att… |
| 153 | [ghost00318/ghost00318.github.io](https://github.com/ghost00318/ghost00318.github.io) | 1 | — | Control Sub-GHz signals with an Android device using an ESP32 and CC1101 module connected via USB… |
| 154 | [GlomarGadaffi/deauth-detector](https://github.com/GlomarGadaffi/deauth-detector) | 1 | C | distributed 802.11 attack detector with a LoRa back-haul. sensors flag deauth/flood/evil-twin/EAP… |
| 155 | [hleserg/esp32-flipper-exp](https://github.com/hleserg/esp32-flipper-exp) | 1 | Python | Flipper Zero + ESP32 'chaos from one button': Sub-GHz + IR + BLE. Roadmap: XIAO ESP32-C6 Zigbee/T… |
| 156 | [jdz99999/sanwa-garage-shutter-esp32-control](https://github.com/jdz99999/sanwa-garage-shutter-esp32-control) | 1 | C++ | Control a Sanwa Speedy garage shutter from Home Assistant with an ESP32 + CC1101. Learns your exi… |
| 157 | [Jonathan-0101/skeletonKey](https://github.com/Jonathan-0101/skeletonKey) | 1 | C | BEng Dissertation; Penetration-testing device to highlight security system vulnerabilities |
| 158 | [MikelEscobar123/esp32-rf-jammer](https://github.com/MikelEscobar123/esp32-rf-jammer) | 1 | C++ | ESP32-based dual-band RF jammer using two nRF24L01+ modules over HSPI and VSPI. Features toggle b… |
| 159 | [ndpg33/CHICKADEE](https://github.com/ndpg33/CHICKADEE) | 1 | C++ | ESP32 and CC1101 portable sub-GHz RF analysis tool with OLED interface. |
| 160 | [nik-nim/ESP32-Multi-Protocol-Wireless-Analysis-System](https://github.com/nik-nim/ESP32-Multi-Protocol-Wireless-Analysis-System) | 1 | — | ESP32 Multi-Protocol Wireless Analysis System \| Personal R&D Project Arduino, C/C++, ESP32, RF E… |
| 161 | [P1p2gamer26/Jammer_Hacking_etico](https://github.com/P1p2gamer26/Jammer_Hacking_etico) | 1 | HTML | Laboratorio educativo de seguridad RF 2.4 GHz: ESP32 + nRF24L01+ PA/LNA (consola serial, escaner … |
| 162 | [phfu/433RC_TX](https://github.com/phfu/433RC_TX) | 1 | C++ | ESP8266 transmits bits to 433MHz TX module   WEB interface & API for remote control |
| 163 | [Phunkafizer/RFM-gateway](https://github.com/Phunkafizer/RFM-gateway) | 1 | C++ | Hard- and software for the RFM-gateway, a universal platform for integrating sub-GHz radio into y… |
| 164 | [Physostegiadragee5952/valorant-esp-items-2026](https://github.com/Physostegiadragee5952/valorant-esp-items-2026) | 1 | — | See dropped weapons, spike, abilities, and enemy economy through walls with real-time Valorant it… |
| 165 | [PigManul/megaware](https://github.com/PigManul/megaware) | 1 | C++ | Firmware for LilyGo T-Embed CC1101 (ESP32-S3) with Wi-Fi, Sub-GHz, NFC, and Lua/JS scripting |
| 166 | [rgomez31UAQ/WaveSentinelSubGhz-CC1101-V2_ESP32](https://github.com/rgomez31UAQ/WaveSentinelSubGhz-CC1101-V2_ESP32) | 1 | — | Flash WT32-SC01-PLUS  Conecte su placa a través de USB-C y haga clic en Abrir instalador web arri… |
| 167 | [ridhinva/pocket-s](https://github.com/ridhinva/pocket-s) | 1 | C | Toolkit: Pocket-S: Open-source ESP32-S3 multi-tool alternative to Flipper Zero — Sub-1GHz, NFC, R… |
| 168 | [Romemu1810-tech/bluetooth_jammer_experimento](https://github.com/Romemu1810-tech/bluetooth_jammer_experimento) | 1 | HTML | Proyecto personal y experimental para el aprendizaje de electrónica, RF y comunicaciones Bluetoot… |
| 169 | [sebarreto/ESP32-rfid-smartwatch-Lora-TTN-chatbot](https://github.com/sebarreto/ESP32-rfid-smartwatch-Lora-TTN-chatbot) | 1 | JavaScript | Project to improve treatment on children with panic attack. ESP32 + Smartwatch + LoraWan + TTN + … |
| 170 | [ShubhamKanhere307/CloneGuard---RFID-Cloning-Defense-](https://github.com/ShubhamKanhere307/CloneGuard---RFID-Cloning-Defense-) | 1 | — | Attack-and-defend RFID security lab using ESP32 and RC522 to clone MIFARE cards and bypass UID-on… |
| 171 | [Sid214/ESP32_RFID_Wifi_Jammer](https://github.com/Sid214/ESP32_RFID_Wifi_Jammer) | 1 | C++ | A hardware-integrated Wi-Fi security auditor for ESP32 featuring an RFID physical access lock (MF… |
| 172 | [sophatvathana/dt2m](https://github.com/sophatvathana/dt2m) | 1 | C++ | DT2M (Don't T to Me) - ESP32 Multi-Purpose RF Development Platform |
| 173 | [Vardhan0257/BlackPebble](https://github.com/Vardhan0257/BlackPebble) | 1 | C++ | BlackPebble is a modular ESP32-S3–based multi-protocol security research platform integrating Wi-… |
| 174 | [Yad08/SmartLockV1](https://github.com/Yad08/SmartLockV1) | 1 | HTML | Hacking an Amazon Touchscreen Lock — office door  auto-locks and the touchpad is slow to wake. Bu… |
| 175 | [aayush-xid-su/Esp32-Horcrux](https://github.com/aayush-xid-su/Esp32-Horcrux) | 0 | C++ | A comprehensive collection of ESP32 tools, scripts, and utilities for wireless security research,… |
| 176 | [abdullahmehboob671-pixel/HydroSentinel-EdgeAI-Flood-Warning-Node](https://github.com/abdullahmehboob671-pixel/HydroSentinel-EdgeAI-Flood-Warning-Node) | 0 | C++ | Low-cost, off-grid Edge-AI flood early warning node powered by ESP32-S3, Edge Impulse TinyML, and… |
| 177 | [AkeFPU/RF-Signal-intrution-system-using-ESP32-and-Arduino-](https://github.com/AkeFPU/RF-Signal-intrution-system-using-ESP32-and-Arduino-) | 0 | C++ | An AI-powered RF spectrum monitor and intrusion detection system. Uses an Arduino and nRF24L01s f… |
| 178 | [Anonymousme00/ESP32-Single-nRF24-Remote-Controller](https://github.com/Anonymousme00/ESP32-Single-nRF24-Remote-Controller) | 0 | C++ | Arduino Uno remote controller with 2.4" TFT touch display for ESP32 RF jammer via nRF24L01+ |
| 179 | [ArdNU/OMEGA-Device](https://github.com/ArdNU/OMEGA-Device) | 0 | — | Ultimate ESP32-S3 Multi-tool DIY device: WiFi, Bluetooth, Sub-Ghz RF, IR, NFC, GPS. Open-source f… |
| 180 | [AyushDeep117/Lo-Ra-based-Crowd-Instability-Detector-using-Distributed-Sensor-n-w-](https://github.com/AyushDeep117/Lo-Ra-based-Crowd-Instability-Detector-using-Distributed-Sensor-n-w-) | 0 | C++ | An internet-independent edge-computing sensor network using ESP32, LoRa (SX1278), and multi-senso… |
| 181 | [chonada/EmbedOS](https://github.com/chonada/EmbedOS) | 0 | C | A from-scratch ESP-IDF + FreeRTOS OS for the LilyGO T-Embed CC1101 (ESP32-S3): app launcher, sub-… |
| 182 | [cvantienen/Esp32Subghz](https://github.com/cvantienen/Esp32Subghz) | 0 | C++ |  |
| 183 | [douglasrolim/bruce-gate-relay](https://github.com/douglasrolim/bruce-gate-relay) | 0 | TypeScript | Open your own RF gates from anywhere: a Cloudflare Worker relay + a Bruce firmware module for Sub… |
| 184 | [ducokaptein-cyber/esp-32-sub-ghz-scanner](https://github.com/ducokaptein-cyber/esp-32-sub-ghz-scanner) | 0 | — |  a esp32 u with a 0.96 oled screen and a cc1101 moudle to scan wifi for sub ghz devices. |
| 185 | [Durzan12/Pocket-Hydra](https://github.com/Durzan12/Pocket-Hydra) | 0 | C++ | Esp8266 with a bunch of modules and a dream? here you go, IR, SubGHz, Deauther, a hydra of contro… |
| 186 | [eirode/Smart-RFID-lock](https://github.com/eirode/Smart-RFID-lock) | 0 | C++ | simple PCB design for Hack Club Half Life that works as an esp32-c3 controlled RFID lock |
| 187 | [Encad/esp32-tram](https://github.com/Encad/esp32-tram) | 0 | — | Compact ESP32-S3 multitool featuring CC1101 (Sub-GHz) and NRF24L01 (2.4 GHz) hardware modules. |
| 188 | [GHOST-WEB-spec/SPECTER](https://github.com/GHOST-WEB-spec/SPECTER) | 0 | C++ | ESP32-based handheld pentesting device running JINX OS. WiFi, BLE, IR, Sub-GHz, NFC and more. |
| 189 | [haodiy12-code/esp32-c3-mini-jammer-jammer-ir-jammer-wifi-2.4](https://github.com/haodiy12-code/esp32-c3-mini-jammer-jammer-ir-jammer-wifi-2.4) | 0 | C++ | DIY Tactical Multi-Tool using ESP32-C3 SuperMini, nRF24L01+, 0.96" OLED, TV-B-Gone (400+ IR codes… |
| 190 | [inevitable-lettus/esp32-rf-security-toolkit](https://github.com/inevitable-lettus/esp32-rf-security-toolkit) | 0 | — | Wireless-protocol security research platform on ESP32 — IR / RFID-NFC / sub-GHz / WiFi / BLE capt… |
| 191 | [JavierSiliacay/Wifi-Deauther-project](https://github.com/JavierSiliacay/Wifi-Deauther-project) | 0 | — | ESP8266-based educational tool for WiFi network exploration and security analysis. For educationa… |
| 192 | [jsuescun/espSAK](https://github.com/jsuescun/espSAK) | 0 | C | ESP32 Swiss Army Knife: wireless multi-tool, Flipper Zero capabilities at a fraction of the cost.… |
| 193 | [lamerous/TinySniff](https://github.com/lamerous/TinySniff) | 0 | — | Tool for WiFi and NFC pentest attacks powered by ESP8266. |
| 194 | [leandrovitormoreira39012/GhostTek-PRE_ALPHA](https://github.com/leandrovitormoreira39012/GhostTek-PRE_ALPHA) | 0 | — | Firmware focado em wifi hacking, bluetooth jammig, nfc, lora e gps. Interface interativa. Inicial… |
| 195 | [LordSA/ESP32_STM32_RF](https://github.com/LordSA/ESP32_STM32_RF) | 0 | C++ | A low-power 2,4GHz wireless jammer based on ESP32 and nRF24LO1+PA+LNA (PlatformIO) |
| 196 | [Louistuis/concierge-phone](https://github.com/Louistuis/concierge-phone) | 0 | Python | A small candybar phone you click and talk to: script-built KiCad board, ESP32-P4, LTE, NFC, sub-G… |
| 197 | [lq-anarchy/open-hsdu](https://github.com/lq-anarchy/open-hsdu) | 0 | C++ | ESP32-S3 + CC1101 open replacement for a 418 MHz, 4800-baud serial-keyed base radio (the HSDU). I… |
| 198 | [Luiz123819/Projeto-Jammer-Bluetooth](https://github.com/Luiz123819/Projeto-Jammer-Bluetooth) | 0 | C++ | Desenvolvi do zero um projeto pessoal de hardware e firmware focado em análise de sinais em RF. O… |
| 199 | [M-YiXi/ESP32-BusPirate__Chinese-Localization__A-versatile-hacker-terminal](https://github.com/M-YiXi/ESP32-BusPirate__Chinese-Localization__A-versatile-hacker-terminal) | 0 | C | 它支持通过串口终端或基于网页的CLI与各种数字协议（I2C、UART、1-Wire、SPI等）进行嗅探、发送、脚本编写及交互。它还与蓝牙、Wi-Fi、sub-GHz和RFID等无线协议通信。 |
| 200 | [majeedkhori/mk-oniondao-badge](https://github.com/majeedkhori/mk-oniondao-badge) | 0 | C++ | OnionDAO badge firmware & mods, ESP32-S3 e-paper badge: Onion OS Lua platform, ESP-Duel game, Sol… |
| 201 | [minkione/433Serial-SignalHacker](https://github.com/minkione/433Serial-SignalHacker) | 0 | — | 433MHZ, full duplex, esp8266 based, RFM69HW radio based transceiver. SDR |
| 202 | [Officialsparxx/ESP32-Multitool](https://github.com/Officialsparxx/ESP32-Multitool) | 0 | — | ESP32-Multitool is an open-hardware, open-firmware handheld built around an ESP32-S3. Think “Flip… |
| 203 | [OjasUpadhyay/rf-flooding-detector](https://github.com/OjasUpadhyay/rf-flooding-detector) | 0 | C++ | Detection of 2.4 GHz RF Flooding and Jamming Using an ESP32 and nRF24L01+ |
| 204 | [OurLadyOfTheRevolution-droid/FOBworks_for_SGP-public](https://github.com/OurLadyOfTheRevolution-droid/FOBworks_for_SGP-public) | 0 | C++ | Standalone firmware for the SGP Card Mini: ESP32-S3 + CC1101 sub-GHz RKE capture, decode, replay … |
| 205 | [recalde/garagewave](https://github.com/recalde/garagewave) | 0 | Python | Local-first ESPHome + CC1101 radio controller for compatible fixed-code garage doors, with Home A… |
| 206 | [rh45-one/SubGHz-Remote-ESP8266](https://github.com/rh45-one/SubGHz-Remote-ESP8266) | 0 | Python | Authenticated ESP8266 CC1101 Sub-GHz transceiver with Docker GUI and offline simulation |
| 207 | [rperezll/WiFiDeauthLab](https://github.com/rperezll/WiFiDeauthLab) | 0 | — | 🧪 Laboratorio experimental diseñado para explorar y documentar ataques de Deauth en redes Wi-Fi d… |
| 208 | [samirmakwana/RF-Scanner-SubGHz](https://github.com/samirmakwana/RF-Scanner-SubGHz) | 0 | — | A sub-GHz RF Scanner using ESP32 and C1101 with SMA antenna. |
| 209 | [Shatwik7/ESP32-Quad-nRF24L01-Plus-Jammer-Multi-Band-2-4GHz-RF-Controller](https://github.com/Shatwik7/ESP32-Quad-nRF24L01-Plus-Jammer-Multi-Band-2-4GHz-RF-Controller) | 0 | — | ESP32-Quad-nRF24L01-Plus-Jammer is an open-source project for controlling four nRF24L01+ modules … |
| 210 | [ShellCMD101/GHOST-WIRE-Multi-Protocol-IoT-Security-Diagnostic-Toolset](https://github.com/ShellCMD101/GHOST-WIRE-Multi-Protocol-IoT-Security-Diagnostic-Toolset) | 0 | HTML | A comprehensive, handheld IoT security diagnostic toolset built around the ESP32 platform. Ghost … |
| 211 | [StevenSeagalStreams/Cypher32](https://github.com/StevenSeagalStreams/Cypher32) | 0 | C++ | ESP32 Lora Wifi hacking game |
| 212 | [SystemProgrammerWizzard/remote-monitoring-device](https://github.com/SystemProgrammerWizzard/remote-monitoring-device) | 0 | C++ | Sub-GHz LoRa GPS Beacon with Environmental Monitoring and Web Dashboard A low-power ESP32-S3 LoRa… |
| 213 | [ThaVEL-FPE12/Flipper-C3](https://github.com/ThaVEL-FPE12/Flipper-C3) | 0 | — | Flipper Zero For ESP32 C3 |
| 214 | [WalderlanSena/prumoboard](https://github.com/WalderlanSena/prumoboard) | 0 | — | Prumo Board is an open hardware platform designed for education, research, and experimentation in… |
| 215 | [Wasyliy/subghz_live_scope](https://github.com/Wasyliy/subghz_live_scope) | 0 | C | flipper zero esp32 port application |
| 216 | [WomanInStem-Projects/RFID_Secure_Safe_WIth_ESP32](https://github.com/WomanInStem-Projects/RFID_Secure_Safe_WIth_ESP32) | 0 | C | Project where I will code and wire an RFID access controll system, build and 3D print its enclsur… |

### 攻击/安全工具(其他)

> 共 **17** 个项目，按 Stars 降序排列。多标签项目会出现在多个分组。

| # | 项目 | Stars | 语言 | 简介 |
|---:|---|---:|---|---|
| 1 | [autrion/HeimdallRF](https://github.com/autrion/HeimdallRF) | 35 | C++ | HeimdallRF is an open-source, pocket-sized drone detector built on ESP32. It passively scans 868/… |
| 2 | [handiko/ESP12-MQTT-RF-Jammer](https://github.com/handiko/ESP12-MQTT-RF-Jammer) | 25 | C++ | A Simple ESP12 & AD9851 based RF Jammer which can be controlled using MQTT protocol |
| 3 | [Muhammednihalmp/RF-Jammer](https://github.com/Muhammednihalmp/RF-Jammer) | 8 | C++ | ESP32-based RF Jammer  |
| 4 | [torgeirn/tvlift-hack](https://github.com/torgeirn/tvlift-hack) | 4 | — | Trying to hack my not-smart tv-lift to be controlled by HomeAssistant |
| 5 | [kudoej/sentry-rf](https://github.com/kudoej/sentry-rf) | 3 | — | Passive drone RF detection + GNSS jamming/spoofing monitor for ESP32-S3 |
| 6 | [Sndcooper/2.4GHZ-jammer](https://github.com/Sndcooper/2.4GHZ-jammer) | 3 | C++ | Educational ESP32 PlatformIO project scaffold for 2.4 GHz RF experimentation and compliance learn… |
| 7 | [uchiha-madara-02/Esp32-jammer-rf](https://github.com/uchiha-madara-02/Esp32-jammer-rf) | 3 | — |  |
| 8 | [AtaCanYmc/esp32-rf-sword](https://github.com/AtaCanYmc/esp32-rf-sword) | 2 | C++ | ESP32 RF SWORD is an advanced, industrial grade multi-band radio frequency security research, spe… |
| 9 | [ahmedhussain006/SIM-Cellular-Jammer](https://github.com/ahmedhussain006/SIM-Cellular-Jammer) | 1 | — | Embedded RF security research project exploring radio frequency interference, wireless communicat… |
| 10 | [AmazingMoaaz/SpecterOS](https://github.com/AmazingMoaaz/SpecterOS) | 0 | C++ | ESP32 2.4 GHz RF jammer — a dual-radio, dual-core burst-hopping engine driven by 3 buttons and a … |
| 11 | [b-dorsal/arduino-esp32-rf-hacking](https://github.com/b-dorsal/arduino-esp32-rf-hacking) | 0 | C++ | A small project for capturing RF remote control signals and replaying them via ESPHome powered ES… |
| 12 | [clopso/esp32-rfm69-ook-cloner](https://github.com/clopso/esp32-rfm69-ook-cloner) | 0 | C | OOK Cloner with ESP32 and RFM69 |
| 13 | [Kyzerer/KYZER-jammer-0.1](https://github.com/Kyzerer/KYZER-jammer-0.1) | 0 | C++ | Educational ESP32-based RF experimentation toolkit for exploring wireless communication concepts,… |
| 14 | [mynameissami/Spectre](https://github.com/mynameissami/Spectre) | 0 | Python | S.P.E.C.T.R.E. is a hardware-integrated cybersecurity platform combining an ESP32 RF sniffer with… |
| 15 | [Nikhil-Shivhare/BLE_Attack_ESP32](https://github.com/Nikhil-Shivhare/BLE_Attack_ESP32) | 0 | C++ |  |
| 16 | [Nyos3s/Nyos3s](https://github.com/Nyos3s/Nyos3s) | 0 | — | 0x / Nyos3s Siber Güvenlik Araştırmacısı & Geliştirici RF Sinyal Analizi & ESP32 Donanım Protokol… |
| 17 | [seancarroll1999/Smart_Light_Control](https://github.com/seancarroll1999/Smart_Light_Control) | 0 | — | Project that builds a Flask API with ESP8266 to perform a man in the middle attack on RF remote c… |

## 📁 数据说明

- 采集方式：GitHub 仓库搜索 API，156 组查询设计（开发板型号 × 攻击主题组合），按 `full_name` 去重
- 生成时间：2026-11-17（采集） / 2026-11-26（本文档）
- 多标签说明：一个项目可同时属于多个板卡分组和领域分组，各分组数量之和大于总数
- 配套文件：`全部项目清单.csv`（Excel 直开）、`全部项目清单.json`（结构化数据）、`精选_Top300.md`（热度榜）

## 📄 许可与使用

- 本索引文档仅整理公开信息，遵循 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 发布
- 所收录各项目的权利归属其原作者，使用请遵循各项目自身的开源许可证（MIT / GPL / Apache 等）
- 如您的项目被收录且希望移除，请提交 Issue 说明，核实后即删除

<div align="center">

---

**⚠️ 再次提醒：本资料仅供学习研究，请在合法授权范围内使用**



</div>
