# README

This repository contains an example of structuring your 1Bitsy project using
the libopencm3 hardware library.

The 1Bitsy is an open hardware stm32F415 based small microcontroller development
board.

For more information visit http://1bitsy.org

The libopencm3 project aims to create an open-source firmware library for
various ARM Cortex-M3 microcontrollers.

For more information visit http://libopencm3.org

## Usage

You will have to fetch the libopencm3 submodule by running:

    git submodule init
    git submodule update

You compile the needed part of the library and the project firmware by invoking
"make" in the toplevel directory.

Executing "make flash" will try to use arm-none-eabi-gdb to connect ta a Black
Magic Probe and upload the firmware to your target.

## Contributions

Pull requests simplifying and making this example easier to adapt are welcome!
Please strive to keep things fairly simple and magical as possible. :)
