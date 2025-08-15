# bitaxeGamma

Project version: 603
06/08/2025

### CHANGELOG

All notable changes to this project will be documented in this file.


<!--- ## [Unreleased]
### Added


### Changed


### Removed
--->

## [603a]
### Added
- Several fields in component properties
- iBOM
- DRC rules

### Changed
- Rework UART near U9
- Pour copper over the whole layers (GND)
- Make solid GND connection underneath DC/DC converter 
- Make solid GND connection underneath ASIC
- Increase minimum clearance to 0.15mm instead of 0.1mm
- Reduce minimum track width to 0.15mm for few tight spots
- Correct VDD plane below ASIC, GND below WiFi chip

### Removed
- Unused parts of 3V3 polygon in In2 layer
- SW signal in In2 due to EMI

## [603] - 08/25
### Added
- Initial version
