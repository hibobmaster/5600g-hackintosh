# AMD 5600g hackintosh

OpenCore version: 1.0.2

macOS: 

| Hardware |                                        |
| -------- | -------------------------------------- |
| CPU      | AMD Ryzen 5 5600G with Radeon Graphics |
| GPU      | 5600g integrated apu                   |
| Motherboard | MSI B450M-A Pro Max                 |
| Audio    | Realtek ALC897                         |



## Install
1. [Create the USB](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/#creating-the-usb)
2. Download this EFI
3. [Use SSDTTime to generate the SSDTs](https://chefkissinc.github.io/guides/hackintosh/gathering-files/acpi/)
4. [Generate your SMBIOS data](https://github.com/corpnewt/GenSMBIOS)
5. [Create your own usb mapping](https://github.com/USBToolBox/tool)
6. [AMD BIOS Settings](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#amd-bios-settings)
7. Boot!

## Credits
1. [OpenCore Team](https://github.com/acidanthera/)
2. [AMD_Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
3. [Dortania Install Guide](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html)
4. The AMD Vega iGPU support patch kext - [NootedRed by ChefKissInc](https://github.com/ChefKissInc/NootedRed)
5. Other community driven projects
