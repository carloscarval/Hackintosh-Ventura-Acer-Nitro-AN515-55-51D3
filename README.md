# [SUCCESS] Hackintosh-Ventura---Acer-Nitro-AN515-55-51D3

If it worked for you, please give it a ⭐

# macOS Ventura : version 13.1

The project was based on .

`Opencore Version : 0.8.6`

## Contents

- [Configuration](#configuration)
- [Current Status](#current-status)
- [Credits](#credits)

## Configuration

| Specifications | Detail                                    |
| ------------------- |-------------------------------------------|
| Computer model      | Acer Nitro 5 2018 - AN515-55 (GTX 1650)   |
| Processor           | Intel Core i5-10300h ~2.5ghz turbo 4.5ghz |
| Memory              | XXXX 16GB 2400MHz DDR4                    |
| Hard Disk           |                                           |
| Integrated Graphics | Intel UHD Graphics 630                    |
| Monitor             | FHD 1920x1080 (15.6 inch)                 |
| Sound Card          | Realtek ALC255                            |
| Wireless Card       |                                           |
| Touchpad            | Synaptics I2C HID based                   |

## Current Status
- **Discrete graphic card** never going to work!
- **Touchpad Gestures** works after adding patched DSDT/SSDT (XOSI) in OC
- **Sound** Works perfectly.
- **HDMI** Won't work, since the port is hardwired to the dGpu (disabled). And this device doesn't support AltMode, so, in order to use it with HDMI, it's necessary to use an adapter with DisplayLink.
- **Everything else works**

## Credits

- Thanks to [X](https://github.com/X) for providing the EFI folder for the model XXXX (https://github.com/XXXXX).