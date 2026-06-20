
# Change Log

All notable changes to this project will be documented in this file.
 
## [Unreleased v3] - as of 20 June 2026
  
Version 3 fixes a bug that prevents the D1 mini from booting during periods of programming and reboot.
The workaround has been to disconnect the USB cable connecting the D1 mini to the computer after 
flashing the program onto the D1 mini.
 
### Added
- A 10KΩ resistor between pin D8 and ground.

### Changed
  
- Migrated project from Eagle 7.7.0 to KiCAD.
 
### Fixed
 
- [GPIO15 Bootstrapping Trap](https://github.com/Tiogaplanet/MiP_D1-mini-Pack/issues/1)
  The D1 mini occassionally hangs on reboot during program-and-test cycles due to 
  GPIO15 being pulled high.  Problem solved with 10KΩ resistor.
 
## [v2] - 2018
   
### Changed
- Corrected the serial port wiriring and added silkscreening to explain pin layout.

### Fixed
 
- The unreleased v1 board had the serial port wired incorrectly.