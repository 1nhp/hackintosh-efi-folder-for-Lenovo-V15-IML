An Hackintosh OpenCore EFI folder created specifically for the Laptop now hackintoshing is possible on that laptop!

## Recommended OS Tested
![Screenshot 2024-12-06 at 23 34 03](https://github.com/user-attachments/assets/20bce156-44b5-4a41-ac1f-d12d0a04de09)
## Installation
Download the source code with Download button

![Step 1](https://github.com/user-attachments/assets/9b9f5468-5a35-4ea1-b794-2cb7b631ac77)

NOTE: This EFI Configuration will only work Fully with macOS Monterey - Sonoma the EFI may not work fully with older versions such as Catalina - Mojave USE AT YOUR RISK AM NOT RESPONSIBLE FOR ANY DAMAGES
YOU DONE TO YOUR LAPTOP!
## Laptop Specs


| Specs | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Laptop model      | Lenovo V15 IML     |
| CPU           | Intel(R) Core(TM) i3-10110U CPU @ 2.10GHz        |
| CPU Generation           | Comet Lake        |
| Display                  | 1920x1080 ISP     |
| RAM              | 8GB DDR4 2666MHz              |
| Hard Disk           | 256GB Toshiba SSD                |
| Integrated Graphics | Intel CoffeeLake-H GT2 UHD Graphics 630                     |
| Sound Card          | Realtek ALC257                             |
| Wireless Card       | Intel Wireless AC 9560                        |
| Touchpad            | idk                               |

## What is working Table
| Feature | Status | Reason
| ------------------- | ------|------------------------------------- |
| Hardware Acceleration|Works|Full|
| VAPPI| Works|Full|
| Sound| Works|Full|
| Microphone| Works|Full|
| Webcam| Works|Full|
| Wi-Fi| Works|Full|
| Bluetooth| Works|Kinda|
| Keyboard| Works|Full|
| Touchpad| Works|Full|
| USB| Works|Full|
| AirDrop| Doesn't Work|I aint buying an Iphone to test it|
| Battery Manager| Works|Full|
| Brightness| Works|Full|
| HID| Works|Full|
| Sleep| Doesn't Work|Couldn't manage to fix it perhaps theres no any kexts to fix it it seems to be an acpi issue?|
| NTFS Write| Doesn't Work|Didnt put a driver to the EFI itself|
| Dictation| Doesn't Work|Dunno why|
| Head Cursor| Doesn't Work|Who needs this?|
| Touch Bar| Doesn't Work|Does the laptop even have it?|

## Credits
- Thanks to oralia these guys made making the hackintosh EFI for the Laptop possible! [oralia.com](https://olarila.com/)
- Opencore https://github.com/acidanthera/OpenCorePkg
- https://github.com/acidanthera/OpenCorePkg for the readme template

## TODO List
- Fix Sleep (when there is a tutorial or a kext on it)
- Someone to test AirDrop (Any user is welcome to test it on their iphone and the same configuration Laptop!)
- NTFS put a driver for it
- Bluetooth find a way to fix the file transfer protocol on macOS with Bluetooth
- Dictation find a way to fix it
- Stress test the laptop
