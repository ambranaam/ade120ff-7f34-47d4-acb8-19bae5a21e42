# ade120ff-7f34-47d4-acb8-19bae5a21e42

Repo to install MattairTech-Arduino SAMD Core

# Installation

Enter the following URL in **Additional Boards Manager URLs**:
```
 https://raw.githubusercontent.com/ambranaam/ade120ff-7f34-47d4-acb8-19bae5a21e42/main/packages/package_MattairTech_index.json
```

It is a replacement for the no longer existing Boards Manager URL:
```
 https://www.mattairtech.com/software/arduino/package_MattairTech_index.json
```

# Source of "CMSIS-Atmel-1.0.0-mattairtech-2"

Our archive "packages\CMSIS-Atmel-1.0.0-mattairtech-2.tar.gz" is using the files from https://github.com/mattairtech/CMSIS-Atmel/releases/tag/CMSIS-Atmel-1.0.0-mattairtech-2.
For some unknow reason we can't use "https://github.com/mattairtech/CMSIS-Atmel/archive/refs/tags/CMSIS-Atmel-1.0.0-mattairtech-2.tar.gz" directly because if we do this it is installed into "packages\MattairTech_Arduino\tools\CMSIS-Atmel\1.0.0-mattairtech-2\CMSIS\CMSIS\Device\ATMEL" instead of "packages\MattairTech_Arduino\tools\CMSIS-Atmel\1.0.0-mattairtech-2\CMSIS\Device\ATMEL" which is wrong.
