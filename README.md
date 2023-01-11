# ESP32 IoT Framework
This repository contains example programs of a custom ESP32-S2 and ESP32-S3 IoT framework.
It contains a custom upload script that converts the firmware binary file into UF2 format and uploads it to the connected board(s).
Support of multi-board programming (with explicit serial number compare).
Further, USB Settings (such as VID, PID, Serial Number) can be freely choosen.

* __ESP32S2_Basic__ <br />
  Fully working condiction <br />
  TODO: Update File System Libraries to newest version <br />
  TODO: Fix Warning ("CFG_TUD_VENDOR" redefined)

* __ESP32S3_Basic__ <br />
  Fully working condiction


* __ESP32S2_WiFiManager__ <br />
  Currently not working due to file system library conflicts.
  WiFiManager is not compatible with SdFat Library.
  Will not be fixed soon...
