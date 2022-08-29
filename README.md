# Ender3-4.2.7-BLTouch-Firmware
Config files and binary for Creality Ender3 with BLTouch (Silent Motherboard v4.2.7)

# Install
  1. [Download](https://github.com/sebastianrich18/Ender3-4.2.7-BLTouch-Firmware/releases/tag/v1.0) the binary
  2. Put binary on microSD card
  3. Insert SD card into powered off Ender3
  4. Power on Ender3, after a few seconds the firmware will be installed!

# Modified Settings
  * `#define USE_PROBE_FOR_Z_HOMING`
  * `#define BLTOUCH`
  * `#define NOZZLE_TO_PROBE_OFFSET { -55, -6, 0 }`
  * `#define Z_PROBE_FEEDRATE_FAST (20*60)`
  * `#define Z_CLEARANCE_DEPLOY_PROBE 6`
  * `#define Z_CLEARANCE_BETWEEN_PROBES 3`
  * `#define AUTO_BED_LEVELING_BILINEAR`
  * `#define RESTORE_LEVELING_AFTER_G28`
  * `#define Z_SAFE_HOMING`
  * `#define GRID_MAX_POINTS_X 5`
  * `#define BLTOUCH_DELAY 300`
  * `#define BLTOUCH_HS_MODE true`
  
# Other configurations
Other configurations can be found on Marlin's github [here](https://github.com/MarlinFirmware/Configurations)
