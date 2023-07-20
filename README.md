# *EFI OC Z390M GAMING macOS Ventura (Sonoma BETA 1)*



![tag](https://img.shields.io/github/v/release/Gilberto-Mascena/Z390M_GAMING?include_prereleases)
![release](https://img.shields.io/github/release-date/Gilberto-Mascena/Z390M_GAMING)
![size](https://img.shields.io/github/repo-size/Gilberto-Mascena/Z390M_GAMING)
![license](https://img.shields.io/github/license/Gilberto-Mascena/Z390M_GAMING)
##

## *Sistema Operacional*

<img align="right" src="./Imagens/z390m.png" alt="Z390 M GAMING" width="330">

*macOS* | *Ventura (Sonoma BETA 1)*
:---:|:---
##

## *Meu Setup*

*Config | Desktop*
:---:|:---
*Placa Mãe* | <a href="https://www.gigabyte.com/br/Motherboard/Z390-M-GAMING-rev-10#kf" target="_blank">*Gigabyte Z390M GAMING*</a>
*Gabinete* | *Fortress-tg Gamemax*
*Fonte* | *GIGABYTE - GP-P550*
*CPU* | *Core I7 9700F*
*Water Cooler* | *DEEPCOOL GAMMAXX L120T*
*NVME M.2* | *XPG GAMMIX S11L 256GB / macOS*
*NVME M.2* | *XPG GAMMIX S41 512GB / Windows 11*
*GPU* | *RX 570 4G PowerColor*
*Memória ram* | *CORSAIR VENGEANCE LPX 2x16GB total 32GB*
*WI-FI* | *BCM94360CD chip Apple*
##

## *O que funciona*

- [x] *Áudio.*
- [x] *LAN.*
- [x] *WI-FI. (não funciona no Sonoma BETA 1)*
- [x] *Bluetooth.*
- [x] *USB.*
- [x] *Sleep.*
##

## *Resultados Geekbench*

- [*Windows 11 Pro*](https://browser.geekbench.com/v5/cpu/19703206)
- [*macOS Ventura 13.1*](https://browser.geekbench.com/v5/cpu/19703520)
- [*macOS Sonoma 14.0 Beta 1*](https://browser.geekbench.com/v6/cpu/1566485)
- [*Ubuntu 22.04.2 LTS*](https://browser.geekbench.com/v6/cpu/1953890)
##

## *Captura de telas*

![Sobre_Este_Mac](https://user-images.githubusercontent.com/103699861/211068915-4c3cad37-ddf3-478b-bbff-18db80fee956.png)
![Sobre Ventura](https://user-images.githubusercontent.com/103699861/211068963-7337e637-db69-41bb-a7e4-3e11ff33e374.png)
![Sobre Sonoma](https://github.com/Gilberto-Mascena/Z390M_GAMING/assets/103699861/3993b082-9b46-4051-bac2-4566ec8aa439.png)
![Hackintool_Peripherals](https://user-images.githubusercontent.com/103699861/211069054-801c45ef-5ae4-4f47-bcf2-be6b2d775632.png)
![Hackintool_PCIe](https://user-images.githubusercontent.com/103699861/211069091-0312b533-8e6d-4bf9-9d1d-615907c8f256.png)
![USB_Ports](https://user-images.githubusercontent.com/103699861/211069110-4ebffbf0-49d4-42aa-90a3-91ef3203a4e2.png)
![Hackintool_kexts](https://user-images.githubusercontent.com/103699861/211069119-367064ca-8298-4ec9-be3e-1875911c432b.png)
##

## *Kexts usadas, (todas versões Releases).*

- *[`WhateverGreen.kext`](https://github.com/acidanthera/WhateverGreen)*
- *[`Lilu.kext`](https://github.com/acidanthera/Lilu)*
- *[`VirtualSMC`](https://github.com/acidanthera/VirtualSMC), somente: `VirtualSMC.kext`, `SMCProcessor.kext` e `SMCSuperIO.kext`*.
- *[`IntelMausi.kext`](https://github.com/acidanthera/IntelMausi)*
- *[`CpuTscSync.kext`](https://github.com/acidanthera/CpuTscSync)*
- *[`AppleALC.kext`](https://github.com/acidanthera/AppleALC)*
- *`USBMap.kext`*
##

## *Utilização*

* _**Recomendação 1**_
  * *Use [`GenSMBIOS`](https://github.com/corpnewt/GenSMBIOS), para gerar novos seriais para sua SMBIOS afim de evitar conflitos com iServices.*
* _**Recomendação 2**_
  * *Use [`ProperTree`](https://github.com/corpnewt/ProperTree), para editar sua config.plist.*     
* _**Recomendação 3**_
  * *Use [`USBMap`](https://github.com/corpnewt/USBMap), para mapear suas portas USB, (apartir do OC 0.9.3, pode ser mapeadas com XHCIPortLimit + USBInjectAll).*
* _**Recomendação 4**_
  * *Extrair sua DSDT a partir do windows.*
  * *Use [`SSDTTime`](https://github.com/corpnewt/SSDTTime), para gera seus patches de SSDT.*    
* _**Recomendação 5**_
  * *Use [`MaciASL`](https://github.com/acidanthera/MaciASL), para compilar seus patches de SSDT.*
##

## *Configurações de BIOS Intel*

* _**Desativar**_

  * *Fast Boot*
  * *Secure Boot*
  * *Serial/COM Port*
  * *Parallel Port*
  * *VT-d (pode ser ativado se você definir DisableIoMapper como true)*
  * *Módulo de suporte de compatibilidade (CSM) (deve estar desativado na maioria dos casos, erros/paradas de GPU como gIO são comuns quando esta opção está ativada)*
  * *Thunderbolt (para instalação inicial, pois o Thunderbolt pode causar problemas se não for configurado corretamente)*
  * *Intel SGX*
  * *Intel Platform Trust*
  * *CFG Lock (proteção contra gravação MSR 0xE2) (deve estar desativado, se você não conseguir encontrar a opção, ative AppleXcpmCfgLock em Kernel -> Quirks. Seu hack não inicializará com o CFG-Lock ativado)*

* _**Habilitar**_

  * *VT-x*
  * *Above 4G Decoding*
  * *Hyper-Threading*
  * *Execute Disable Bit*
  * *EHCI/XHCI Hand-off*
  * *Tipo de SO: Modo UEFI do Windows 8.1/10 (algumas placas-mãe podem exigir "Outro sistema operacional")*
  * *DVMT pré-alocado (memória iGPU): 64 MB ou superior*
  * *Modo SATA: AHCI*
##

## *Agradecimentos*

- [*Acidanthera*](https://github.com/acidanthera)
- [*CorpNewt*](https://github.com/corpnewt)
- [*CrisHotpatch*](https://t.me/crishotpatch)
- [*Dortania*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#starting-point)
- [*Dicas do Mateus*](https://www.youtube.com/c/DicasdoMateus)
- [*Gabriel Luchina*](https://www.youtube.com/c/gabrielluchina)
##

## *Licença* 

*The* [*MIT License*](https://github.com/Gilberto-Mascena/Z390M_GAMING/blob/main/LICENSE.md) (*MIT*)

*Copyright :copyright: 2020* 
##