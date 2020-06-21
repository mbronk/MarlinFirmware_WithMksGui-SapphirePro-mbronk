# Mks-Robin-Nano-Marlin2.0-Firmware
## Features
Additional documentation can be found at the [Marlin Home Page](http://marlinfw.org/).
The firmware of Mks Robin Nano, based on [Marlin2.0.x](https://github.com/MarlinFirmware/Marlin)(The based version is based on Marlin2.0.5), added the [LittlevGL](https://github.com/littlevgl/lvgl), supporting colourful GUI and touch screen. It is developed on PlatformIO, we hope more and more developers will participate the development of this repository.

![](https://github.com/makerbase-mks/Mks-Robin-Nano-Marlin2.0-Firmware/blob/master/Images/MKS_Robin_Nano_printing.png)

## Build
To build Marlin 2.0 you'll need [Arduino IDE 1.8.8 or newer](https://www.arduino.cc/en/main/software) or [PlatformIO](http://docs.platformio.org/en/latest/ide.html#platformio-ide). We've posted detailed instructions on [Building Marlin with Arduino](http://marlinfw.org/docs/basics/install_arduino.html) and [Building Marlin with PlatformIO for ReArm](http://marlinfw.org/docs/basics/install_rearm.html) (which applies well to other 32-bit boards).

## About the gcode file preview
The images should be added to gcode file when slicing, and MKS has developed the [plugin for Cura](https://github.com/makerbase-mks/mks-wifi-plugin) to make it.

## About the image conversion
- Open [lvgl image convert](https://github.com/makerbase-mks/Software/tree/master/Lvgl_image_convert_tool) software. 
- Open bmp images.
- Enter the saved file name.
- Choose file output format:Bin_565.
- Start convertion.
- Save bin file.
- Copy the converted bin file to the mks_pic folder.
- Copy the mks_pic folder to the SD card.
- SD card is connected to the motherboard, and you can see the update interface after powering on.

  [Geeetech3D GTM32](https://github.com/Geeetech3D/Diagram/blob/master/Rostock301/Hardware_GTM32_PRO_VB.pdf)|[STM32F1](https://www.st.com/en/microcontrollers-microprocessors/stm32f103.html) ARM-Cortex M3|72MHz|256-512k|48-64k|3.3V|no

  #### STM32F4

  boards|processor|speed|flash|sram|logic|fpu
  ----|---------|-----|-----|----|-----|---
## More information about the Robin Nano
- Follow the [Coding Standards](http://marlinfw.org/docs/development/coding_standards.html) to gain points with the maintainers.
Please refer to [MKS Robin Nano github](https://github.com/makerbase-mks/MKS-Robin-Nano).

