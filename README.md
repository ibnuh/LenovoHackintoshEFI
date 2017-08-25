# LenovoHackintoshEFI
Lenovo Ideapad 310-14IKB Hackintosh EFI

Clover Config file:
https://github.com/RehabMan/OS-X-Clover-Laptop-Config

Kexts:
https://www.tonymacx86.com/resources/intelgraphicsfixup.337/
https://www.tonymacx86.com/resources/lilu.336/
https://www.tonymacx86.com/resources/fakesmc.325/
https://github.com/RehabMan/OS-X-ACPI-Battery-Driver
https://www.tonymacx86.com/resources/voodootscsync-4-core.285/
https://github.com/RehabMan/HP-ProBook-4x30s-DSDT-Patch/tree/master/kexts/AppleBacklightInjector.kext

Installation:
- Prepare Installation Media uisng mentioned Kexts and Clover file.
- Use fake ig-platform-id for installation like 0x12345678

Post Installation:
- Use the same fake ig-platform-id for first boot like 0x12345678
- Install Clover to your macOS drive.
- Paste kexts to EFI drive and S/L/E
- Rebuild cache
- Reboot using default ig-platform-id i.e., 0x591b0000

- 
