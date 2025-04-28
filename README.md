EFI Hackintosh for Lenovo IdeaPad Flex 15IIL (Core i5-1035G1, UHD 620 (ICL RVP))

This EFI folder is designed for the Lenovo IdeaPad Flex 15IIL with an Intel Core i5-1035G1 processor and Intel UHD 620 graphics. The EFI works well with macOS Sonoma (or other recent macOS versions), providing full system functionality and hardware compatibility, except for the following known issues:

HDMI: HDMI output is currently not functional due to Ice Lake iGPU limitations in macOS.

Card Reader: The built-in card reader is not recognized and does not work.

Features:

Full iGPU acceleration (UHD 620 (ICL RVP)) with working graphics.

Touchscreen and touchpad fully functional.

Wi-Fi, audio, and USB ports working.

Battery management and sleep/wake functionality are working.

Important Notes:

Ensure that your system matches the configuration outlined above for optimal results.

You may need to tweak framebuffer settings to get the best graphics performance for your setup.

HDMI output is currently not supported; consider using USB-C DisplayPort adapters for external monitors.

Credits:

OpenCore team

Lilu.kext, WhateverGreen.kext, and VirtualSMC for their contributions.
