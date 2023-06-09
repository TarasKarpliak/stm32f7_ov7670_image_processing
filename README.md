## STM32F767 and OV7670 Image Processing Project

This Git repository contains the source code, documentation, and hardware design files for a project that utilizes a microcontroller STM32F767 and camera module OV7670. 

The firmware is developed in Eclipse IDE and implements the communication with the OV7670 camera module through the camera interface (DCMI) and the I2C interface. The firmware also handles the image processing tasks, such as color space conversion, image filtering, and compression. 

The hardware design includes a custom board that integrates the STM32F767 microcontroller and the OV7670 camera module, along with other peripherals such as USB, Ethernet, and SD card interfaces. 

The software provides a graphical user interface for configuring the camera settings, capturing and displaying images, and performing image analysis. 

The project is version-controlled using Git, and the commit history reflects the evolution of the project from the initial design to the final implementation.

## Repository Organization

The repository is organized into the following folders:

- **docs:** contains the project documentation, including the diploma report, user manuals, and datasheets for the hardware and software components.

- **firmware:** contains the source code for the firmware running on the STM32F767 microcontroller. The firmware is developed using Eclipse IDE and implements the communication with the OV7670 camera module through the camera interface (DCMI) and the I2C interface. The firmware also handles the image processing tasks, such as color space conversion, image filtering, and compression.

- **hardware:** contains the schematics and PCB layout files for the custom hardware board that integrates the STM32F767 microcontroller and the OV7670 camera module. The board also includes other peripherals, such as USB, Ethernet, and SD card interfaces.

- **software:** contains the source code for the PC software that interacts with the microcontroller board through a USB connection. The software provides a graphical user interface for configuring the camera settings, capturing and displaying images, and performing image analysis.
