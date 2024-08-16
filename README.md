# *EFI OC Gigabyte Z390M GAMING*

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Gilberto-Mascena/Z390M_GAMING)
[![license](https://img.shields.io/github/license/Gilberto-Mascena/Z390M_GAMING)](https://github.com/Gilberto-Mascena/Z390M_GAMING/blob/main/LICENSE.md)
[![GitHub stars](https://img.shields.io/github/stars/Gilberto-Mascena/Z390M_GAMING)](https://github.com/Gilberto-Mascena/Z390M_GAMING/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/Gilberto-Mascena/Z390M_GAMING)](https://github.com/Gilberto-Mascena/Z390M_GAMING/issues)
[![tag](https://img.shields.io/github/v/release/Gilberto-Mascena/Z390M_GAMING?include_prereleases)](https://github.com/Gilberto-Mascena/Z390M_GAMING/releases)
![release](https://img.shields.io/github/release-date/Gilberto-Mascena/Z390M_GAMING)
![size](https://img.shields.io/github/repo-size/Gilberto-Mascena/Z390M_GAMING)
##

## *Operational system*

<img align="right" src="./imgs/banner.png" alt="foto Z390 M GAMING" width="330">

_**macOS**_  _**Sonoma**_

##

_**My Setup**_

##

- _**Motherboard**_
  - <a href="https://www.gigabyte.com/br/Motherboard/Z390-M-GAMING-rev-10#kf" alt="photo Z390 M GAMING" target="_blank">*Gigabyte Z390M GAMING*</a>
- _**Case**_
  - *Pixxo Cg01 Rgb*
- _**Power supply**_
  - *GIGABYTE - GP-P550*
- _**CPU**_
  - *Core I7 9700F*
- _**Water Cooler**_
  - *DEEPCOOL GAMMAXX L120T*
- _**NVME M.2**_
  - *XPG GAMMIX S11L 256GB / macOS*
- _**NVME M.2**_
  - *XPG GAMMIX S41 512GB / Windows 11*
- _**GPU**_
  - *RX 570 4G PowerColor Red Dragon*
- _**Memory**_
  - *Crucial Ballistix 4x8GB 16GB*
- _**WI-FI**_
  - *BCM94360CD chip Apple*
- _**Network**_
  - *Intel I219-V*

---

<a name="ancora"></a>
## Navigation
- [*What works*](#ancora1)
- [*Geekbench results*](#ancora2)
- [*Screenshot*](#ancora3)
- [*Kexts used, (all Releases)*](#ancora4)
- [*Recommended tools*](#ancora5)
- [*Intel BIOS Settings*](#ancora6)
- [*Thanks*](#ancora7)
- [*License* ](#ancora8)

<a id="ancora1"></a>
## *What works*

- [x] *Sound*
- [x] *Network*
- [x] *WI-FI*
- [x] *Bluetooth*
- [x] *USB*
- [x] *Sleep*

[Top](#ancora)

---

<a id="ancora2"></a>
## *Geekbench results*

- [*Windows 11 Pro*](https://browser.geekbench.com/v5/cpu/19703206)
- [*macOS Ventura 13.1*](https://browser.geekbench.com/v5/cpu/19703520)
- [*macOS Sonoma 14.0 Beta 1*](https://browser.geekbench.com/v6/cpu/1566485)
- [*Ubuntu 22.04.2 LTS*](https://browser.geekbench.com/v6/cpu/1953890)

[Top](#ancora)

---

<a id="ancora3"></a>
## *Screenshot*

![about Sonoma](./imgs/about.png)
## *Sound*
![sound](./imgs/sound.png)
## *Ethernet*
![ethernet](./imgs/ethernet.png)
## *Peripherals*
![peripherals](./imgs/peripherals.png)
## *Sound Peripherals*
![sound-peripherals](./imgs/sound-peripherals.png)
## *Hackintool USB port mapping*
![mapping](./imgs/mapping.png)
## *Hackintool kexts*
![kexts](./imgs/kexts.png)

[Top](#ancora)

---

<a id="ancora4"></a>
## *Kexts used, (all Releases)*

- *[`WhateverGreen.kext`](https://github.com/acidanthera/WhateverGreen)*
- *[`Lilu.kext`](https://github.com/acidanthera/Lilu)*
- *[`VirtualSMC`](https://github.com/acidanthera/VirtualSMC), only: `VirtualSMC.kext`, `SMCProcessor.kext` and `SMCSuperIO.kext`*.
- *[`IntelMausi.kext`](https://github.com/acidanthera/IntelMausi)*
- *[`CpuTscSync.kext`](https://github.com/acidanthera/CpuTscSync)*
- *[`AppleALC.kext`](https://github.com/acidanthera/AppleALC)*
- *`USBMap.kext`*

[Top](#ancora)

---

<a id="ancora5"></a>
## *Recommended tools*

* _**Recommendation 1**_
  * *Use [`GenSMBIOS`](https://github.com/corpnewt/GenSMBIOS), to generate new serials for your SMBIOS in order to avoid conflicts with iServices.*
* _**Recommendation 2**_
  * *Use [`ProperTree`](https://github.com/corpnewt/ProperTree), to edit your config.plist.*    
* _**Recommendation 3**_
  * *Use [`USBMap`](https://github.com/corpnewt/USBMap), to map your USB ports, starting from OC 0.9.3, they can be mapped with XHCIPortLimit enabled in config.plist + [`USBInjectAll`](https://github.com/Sniki/OS-X-USB-Inject-All/releases).*
* _**Recommendation 4**_
  * *Extract your DSDT from windows.*
  * *Use [`SSDTTime`](https://github.com/corpnewt/SSDTTime), to generate your SSDT patches.*   
* _**Recommendation 5**_
  * *Use [`MaciASL`](https://github.com/acidanthera/MaciASL), to compile your SSDT patches on mac.*

[Top](#ancora)

---

<a id="ancora6"></a>
## *Intel BIOS Settings*

- [*OpenCore Install Guide*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#intel-bios-settings)

[Top](#ancora)

---

<a id="ancora7"></a>
## *Thanks*

- [*Acidanthera Team*](https://github.com/acidanthera)
- [*CorpNewt*](https://github.com/corpnewt)
- [*CrisHotpatch*](https://t.me/crishotpatch)
- [*Dortania*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#starting-point)
- [*Dicas do Mateus*](https://www.youtube.com/c/DicasdoMateus)
- [*Gabriel Luchina*](https://www.youtube.com/c/gabrielluchina)
- *And others*

[Top](#ancora)

---

<a id="ancora8"></a>
## *License* 

*The* [*MIT License*](LICENSE.md) (*MIT*)

*Copyright :copyright: 2020* 

[Top](#ancora)

---