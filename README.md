| Component      | Description                                                  |
| -------------- | ------------------------------------------------------------ |
| Processor      | Core i5-8300H                                                |
| iGPU           | Intel UHD 630 Graphics                                       |
| dGPU           | GTX 1050 TI (disabled)                                       |
| Audio          | Realtek ALC3204-CG (ALC236)                                  |
| Wifi/Bluetooth | AC9560                                                       |
| Ethernet       | Realtek PCIe GbE Family Controller                           |

| Dependencies      | Version                                                   |
| --------------    | --------------------------------------------------------  |
| OpenCore Version  | 0.9.2                                                     |
| OS Version        | macOS Ventura 13.4.2                                      |

### Current Known Issues
- Bluetooth null address
- Built-in microphone not working
- Hibernate not working  // useful guide: https://dortania.github.io/OpenCore-Post-Install/universal/sleep.html#fixing-gpus

#### note: 
- work in progress
- remap usb ports if there's a problem with usb devices

#### guide followed: https://dortania.github.io/OpenCore-Install-Guide/ and others

## Core i7-9750H, RTX 2060 variant here
https://github.com/leocg/Hackintosh-Dell-G5-5590