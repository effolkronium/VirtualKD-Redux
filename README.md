# VirtualKD-Redux

VirtualKD-Redux is a fork of Sysprogs' VirtualKD.

## Features

* Support for the latest VMware Workstation (Currently 15.5.0)
* Toolchain modernization. Builds with Visual Studio 2017
* Greatly simplified build system

## Build Instructions
### Prerequisites
* Visual Studio 2017
* Windows Driver Kit 7.1.0
### Steps
1. Set WDK7_PATH to the WDK 7.1.0 install path
2. Edit make.bat to modify VS150COMNTOOLS path if needed
3. Run make.bat
4. Use binaries produced in Bundle directory
## Documentation
* Consult the documentation for VirtualKD (http://sysprogs.com/legacy/virtualkd/).
