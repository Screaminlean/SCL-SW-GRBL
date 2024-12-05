- [SCL-SW-GRBL](#scl-sw-grbl)
  - [Versions](#versions)
    - [SCL-SW-GRBL-1\_1](#scl-sw-grbl-1_1)
  - [Usage](#usage)
- [Confirmed Tested Machines](#confirmed-tested-machines)
- [Modification](#modification)
- [Issues](#issues)
- [Disclaimer](#disclaimer)

Test 
# SCL-SW-GRBL
Solidworks CamWorks Post Processor for Generic 3 axis CNC using a GRBL controller.
## Versions
I decided upfront to version the files according to the GRBL release.
### SCL-SW-GRBL-1_1
- SCL-SW-GRBL-1_1.ctl
- SCL-SW-GRBL-1_1.lng
## Usage
Copy `SCL-SW-GRBL-version.ctl` and `SCL-SW-GRBL-version.lng` to the CamWorksData directory **C:\CAMWorksData\UPG-2\ctl**

# Confirmed Tested Machines
Please send me through makes and models of machines this has worked on, I will then update the list below.

# Modification
- Open `SCL-SW-GRBL-version.SRC` in UPG-2 and/or EC Edit-2 and make the changes required.
- Open `SCL-SW-GRBL-version.SRC` in UPG-2 and compile.

The new compiled files `SCL-SW-GRBL-version.ctl` and `SCL-SW-GRBL-version.lng` will be output to the CamWorksData directory **C:\CAMWorksData\UPG-2\ctl**

# Issues
If you have issues using these post's please open an issue and describe what is or is not working along with 
- Machine manufacturer
- Machine model
- Controller make
- Controller model
- Controller firmware version

# Disclaimer
No warranty or guarantee is given! it is your responsibility to check and test the code produced.