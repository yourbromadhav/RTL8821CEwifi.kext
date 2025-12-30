# RTL8821CEwifi.kext
**Wi-Fi driver for macOS (RTL8821CE)**

Project under development, for testing.
Based on macOS 15.5 Sequoia and later, although it may work on versions like Sonoma.

- Based on the Linux driver for rtw88 in its RTL8821CE variant, but may be compatible with similar variants.
- Initially designed for PCIe, additional lines of code and the usb.h and usb.c files could be added to support USB variants.
- It inherits Linux compatibility and the macOS framework from Itlwm, but focuses on Realtek and the Linux rtw88 driver.

You can contribute ideas, code, and improvements for driver stability and performance, as well as communication with macOS. After releasing the first stable versions for RTL8821CE PCIe, more support could be added. Some parts of the code may be reviewed by AI to inspect for any details or human error.

**Project STILL UNDER DEVELOPMENT, test and build at your own risk.**

Special thanks to:

- [OpenIntelWireless](https://github.com/OpenIntelWireless) for [Itlwm](https://github.com/OpenIntelWireless/itlwm/tree/53c51c2cdd6e4b69beb91f310d74c53422b0f8bd)
- [Linux](https://www.kernel.org) for rtw88 driver

