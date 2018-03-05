# USB Serial Drivers for macOS

#### ch340g ch34g ch34x drivers.

Fixing issues with arduino and more boards that uses usb-serial.

### Download

- Version 1.4 (2017-01-11) of the [OEM driver](http://www.wch.cn/download/CH341SER_MAC_ZIP.html) for the CH34x chipset.

**SHA256:** b190f612b833727b2006f362a835f7e97177b580e45cef253e164202106c48eb

### Installation

Remove the old driver by issuing one of the following commands (depending on your installation):

```
sudo rm -rf /System/Library/Extensions/usb.kext
sudo rm -rf /Library/Extensions/usbserial.kext
```

- Restart your Mac.
- Double-click on the `CH34x_Install_V1.4.pkg` file.
- Restart your Mac.
- Plug in your device. It should now be listed under the `/dev` directory. 


