# hackintosh
Opencore Hacintosh EFI

| Hardware | Version |
|-------------------|----------------------|
| Motherboard        |  Asrock H410M-HDV R2.0 |
| CPU | Intel i3 10105 |
| GPU0 | Intel UHD 630 |
| GPU1 | Powercolor RX580 AXRX580-DHDV2.OC|
| SSD0 | Midasforce SATA SSD 120GB |
| SSD1 | VGEN Platinum SATA SSD 512GB |
| HDD0 | Seagate HDD 500GB |
| RAM | 12GB (4+8) 2666 |

Tested with Macintosh Sonoma 14.4

### NOTE:
> RX580 are undervolted using opencore. simply remove this line of code if you want to use this EFI.
> it's at `DeviceProperties` -> `PciRoot(0x0)/Pci(0x1,0x0)/Pci(0x0,0x0)` -> `PP_PhmSoftPowerPlayTable`

> remove the `PP_PhmSoftPowerPlayTable`. remove this line using ProperTree if You want to use this EFI. and change device serial number etc.

> if you're using USB3 in your PC case (front panel), you may need to remap the USB. probably only Front USB2 are working by default since my PC case only have USB2 Connector in front panel.
