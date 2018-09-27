# RD1552 Introduction:

The RD1552 Reference Design is a Pelion Ready design based on the u-blox ODIN W262 Wi-Fi module which includes an ST Microcontroller (STM32F439) .

The reference design is a tested and proven starting point targetted towards the creation of both Development Boards and End Products.


# Reference Design Contents:
**Reference Schematic** 
This is the core of reference design, and illustrates where and how the essential components are connected. 

**Example Implementation** 
Based on the Reference Design, this example implementation is included to demonstrate the Reference Design being used to create real-world hardware. The example implemenation is used within Arm to include the Reference Design into the internal test infrastructure, it is comprised of two parts:

**MCB (Module Carrier Board)** - this was created based on the Reference Design schematic
MTB (Module Test Bed) - this is part of the test infrastructure, and includes DAPLink circuit for programming the device, a range of I/O and loopback paths for automated testing.
 
**Reference Application**
Built on mbedOS, and includes Pelion Device Manager. This application has been configured to run on the Reference Design hardware, and will connect to the Pelion Cloud, and is capable of running the cloud based update service.
Please refer to the [\Documentation\RD1552_Readme.md](https://github.com/ARMmbed/reference-design-RD1552/blob/master/Documentation/RD1552_README.md) for instructions on how to build & use this example application.

# Version Information:
		
| Release | mbed OS | mbed Cloud Client | Release Date | Comment |
| --- | --- | --- | --- | --- | 
|v1.0 | 5.9.6	| 1.3.3	| 27/09/2018 | Initial Release
| |  |  |   | 
