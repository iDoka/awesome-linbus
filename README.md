<p align="center">
<img src="https://github.com/iDoka/awesome-linbus/raw/master/lin_logo.png" alt="LIN logo" width="300" heigth="150"/>
<!-- ![LIN logo](lin_logo.png) -->
</p>


# :tractor: A curated list of awesome tools, hardware and resources for LIN bus

This list helps a reverse engineering LIN bus devices with lightly specializing in automotive embedded controller software and communication understanding.

URL: https://github.com/iDoka/awesome-linbus


## Contents

This is a [LIN](http://en.wikipedia.org/wiki/Local_Interconnect_Network) protocol ToC:

* [Intro](#intro)
* [SW Tools](#sw-tools)
  * [Linux related](#linux-related)
* [Parsers](#parsers)
* [Hardware](#hardware)
* [SLLIN protocol](#sllin-protocol)


## Intro

* [LIN Bus Explained](https://www.csselectronics.com/pages/lin-bus-protocol-intro-basics) - A Simple Intro.

## SW Tools

* [TSMaster](https://github.com/TOSUN-Shanghai/TSMaster) - Powerful open environment for automotive CAN and LIN bus monitoring, simulation, testing, diagnostics, calibration and so on _(Closed source)_.

### Linux related

* [linux-lin](https://github.com/lin-bus/linux-lin) - Linux kernel LIN bus support implemented as TTY line discipline for generic UART conrollers: [Documentation](https://github.com/lin-bus/linux-lin/wiki); [Paper](https://github.com/lin-bus/linux-lin/wiki/sllin-rtlws14-paper.pdf).

## Parsers

* [LDF Parser](https://github.com/c4deszes/ldfparser) - tool is able parse LIN Description Files, retrieve signal names and frames from them, as well as encoding messages using frame definitions and decoding them
* [LDF-Parser](https://github.com/TrippW/LDF-Parser) - parser for retrieving data from automotive Lin description files (LDF)
* [NCF-Parser](https://github.com/TrippW/NCF-Parser) - parser for retrieving data from automotive Node Configuration Files (NCF)

## Hardware

* [LinUSBConverter](https://github.com/uCAN-LIN/LinUSBConverter) - LIN to USB converter with LIN master support compatible with SLCAN
* [linbus](https://github.com/zapta/linbus) - Arduino based LINBUS stack and signal interceptor/injector
* [linbus-phat](https://github.com/cepr/linbus-phat) - LIN Bus interface for Raspberry PI Zero
* [budgetcan](https://github.com/ryedwards/budgetcan_fw#how-to-use-the-lin-driver) - Firmware to support gs_usb on most STM32 devices with LIN bus support.

## SLLIN protocol (like slcan)

SLLIN protocol - that is like slcan protocol for linux based OS.

* [sllin](https://github.com/sstiller/sllin) - Linux driver for LIN interfaces (serial line qdisc)
* [sllin linux](https://github.com/trainman419/linux-lin)
* [start_lin_demo.sh](https://gerrit.automotivelinux.org/gerrit/c/AGL/meta-agl-demo/+/22877/1/recipes-kernel/sllin/files/start_lin_demo.sh)

## unsorted

* [Uart to LinBus on Android](http://fatalfeel.blogspot.com/2013/09/uart-to-linbus.html)

* [Volvo LIN bus reader](https://github.com/laurynas/volvo_linbus)

* [LIN Nodes](https://github.com/John-Titor/LIN_Nodes) Firmware and PCB designs for various LIN network nodes intended for retrofitting older vehicles
* [LIN](https://github.com/gandrewstone/LIN) The LIN protocol implemented over Arduino APIs (Serial and Digital IO)

* [macchina LIN](https://github.com/macchina/LIN) Arduino library to add dual LIN support on SAM3X based boards
* [LIN compiler](https://github.com/PersonalTransport/LIN) LIN is a compiler (written in java) that will parse LIN Node capability and LIN description files and generate C source code that implements the LIN 2.2 spec for slave or master nodes.


* [ESP32-LIN-Interface-Library](https://github.com/mestrode/Lin-Interface-Library) - LIN-Master functions (write and request LIN-Frames via hardware UART of an ESP32
* [open-LIN](https://github.com/open-LIN/open-LIN-c) - Implementation of Local interconnect network in C
* [ESP32-openLIN](https://github.com/CW-B-W/ESP32-openLIN) - The [open-LIN](https://github.com/open-LIN/open-LIN-c) implementation on ESP32 based on [ESP32-SoftwareLIN](https://github.com/CW-B-W/ESP32-SoftwareLIN)

* []() -
* []() -
* []() -

<!--
https://github.com/marmotton/esp32-connected-car-lora
https://github.com/festlv/carpc RaspberryPi based CarPC build, to replace stock Volvo navigation system
https://github.com/festlv/carpc/blob/master/doc/volvo_can_buttons.txt
https://github.com/festlv/carpc/tree/master/linux_software/driver
https://github.com/festlv/carpc/blob/master/linux_software/driver/driver.py
-->


---

## Contributing

* Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.


## Footnotes

1. Please follow [this](https://github.com/iDoka/awesome-linbus) root-repo for lastest updates.
2. Also might be useful [this curated list](https://github.com/iDoka/awesome-canbus) of awesome tools and resources for CAN bus reverse engineering with lightly specializing in automotive embedded controller software and communication understanding.
3. The another awesome list [CAN ID collections](https://github.com/iDoka/awesome-automotive-can-id) also might be useful.


<!--
## Tags

#awesome
#awesome-list
#lin
#lin-bus
#local-interconnect-network
#logger
#sniffer
#slcan
#socketcan
#car-hacking
#bus-monitoring
#lawicel
#elm327
#linutils
#automotive
#embedded
#arduino
#rpi
#raspberry-pi
#sae
#obd-ii
#slcan-protocol
#usbtin
#usb2can
#iso9141
#iso17987
#ldf
#electric-vehicles
#vehicular-networks
#python
#automotive-security
-->
