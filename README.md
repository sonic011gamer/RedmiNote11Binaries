# Firmware Binaries

This repository contains various UEFI firmwares extracted using https://github.com/theopolis/uefi-firmware-parser

## How to reproduce

```
uefi-firmware-parser -o ./Output -O -b -g XBL ./11
```

Where ```./11``` is an UEFI image.

Note: Open up the folders and see if there's an .obj about 2MB, if there is and it isn't extracted(check with 7zip), then use the program on that file