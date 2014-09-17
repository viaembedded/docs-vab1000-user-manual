.. _overview:

Product Overview
================

Based on the ultra compact Pico-ITX form factor, measuring 10 cm x 7.2 cm,
the VIA VAB-1000 is powered by a 1.0GHz dual core VIA Elite E1000 Cortex-
A9 SoC. The board features a high-performance graphics and video engine
with a Unified Shader Architecture featuring 64 stream processors that
provides support for dual independent displays along with the smoothest
3D/2D graphics acceleration and full HD playback support for the most
demanding video formats in resolutions up to 1080p.

The ultra compact VAB-1000 board is optimized for both performance and
power to meet the high end demands of advanced industrial, in-vehicle and
multimedia applications, boasting a ruggedized design with an extended
operating temperature range from 0°C to 60°C, while offering extremely low
power consumption.

The VAB-1000 board has integrated dual-channel LVDS connector, mini PCIe
slot and SATA connector, WLAN connector for WLAN USB module (WiFi),
and an SPI connector. In addition, VAB-1000 provides an impressive selection
of rear I/O in a compact form factor including HDMI® In and Out ports, Mini
USB 2.0 port, Micro SD card slot and RJ-45 GigaLAN port.

The VIA VAB-1000 board supports an optional I/O companion card VAB-1000-T.
The optional I/O companion card is connected through onboard pin
headers connectors carrying the I/O such as audio jacks, LED indicators, button
switch, additional USB 2.0 ports, COM connector, DIO connector, etc.

Key Features
------------

* Powered by VIA E1000 1.0GHz ARM Cortex-A9 Dual-Core processor
* Supports integrated graphics processing (GPU) with Unified Shading
* Architecture
* Small form factor and low power design
* Fanless and ultra low power consumption
* Compatible with Android operating system
* 4GB onboard eMMC Flash memory
* Supports dual-channel 18/24-bit LVDS connector
* Supports Mini PCIe expansion slot for 3.75G/3G module
* Supports Micro SD Card slot for expandable storage up to 32GB size
* Supports SATA connector for SATA SSD device
* Supports WLAN (WiFi) connectivity connector for optional WLAN USB module.

Product Specifications
----------------------

* Processor: VIA Elite E1000 ARM Cortex-A9 Dual Core @ 1.0 GHz processor with 512KB cache
* System Memory: 2GB DDR3
* Flash: eMMC Flash default 4GB
* Graphics controller:

  * Unified Shader Architecture with 64 stream processors
  * Open GL ES 3.0, OpenVG 1.1, OpenCL 1.1
  * Fix function 2D with HW rotation and overlay
  * Video Decoding and Video Encoding

* HDMI Interface

  * One HDMI Out port (HDMI Type C connector)
  * One HDMI In port (HDMI Type C connector) (available by project only)

* Ethernet: Realtek RTL8111G PCIe Gigabit Ethernet controller
* Audio: WOLFSON WM8960 Audio Codec
* Power Management: WOLFSON WM8326GEFL/RV processor power management subsystem
* EEPROM: Flash ROM M25P32-VMW6G 32Mbit/4MB SO8W 8-pin for boot load
* LVDS Transmitter

  * Onboard Chrontel CH7305A Single/Dual LVDS transmitter (DVP to LVDS)
  * Support pixel rate up to 165M pixel/sec
  * Support up to UXGA resolution (1600 x 1200)
  * 18/24-bit LVDS output

  .. note:: The LVDS transmitter has to be used along with VAB-1000-L board and cables.

* Watchdog Timer: When system hang, the watchdog will reboot the system after timeout
* Rear Panel I/O

  * One HDMI In port (HDMI Type-C connector) (available by project only)
  * One HDMI Out port (HDMI Type-C connector)
  * One Mini USB 2.0 port (USB Type AB connector)
  * One RJ-45 LAN port (Gigabit Ethernet)
  * One Micro SD card slot (support SD card 3.0 (SDXC) up to 32GB)
  * One DC-In jack connector for system power (ø3.7)

* Onboard Connectors:

  * One SATA connector
  * One SATA power connector (supports +12V/+5V)
  * One RTC Battery connector
  * One WLAN connector (for Wireless LAN USB module)
  * One SPI connector (for Boot Leader EEPROM update)
  * One Mini PCIe expansion slot (for 3.75G/3G module)
  * One LVDS connector
  * One JTAG connector

* Onboard Pin headers:

  * One VGA pin header (reserved for factory production)
  * One Front panel, USB 2.0 and COM pin header (for On/Off button, power LED
    indicator, two USB 2.0 ports, and one RS-232/Console that only supports Tx/Rx)
  * One SPI and DIO header (supports 4-bit GPIO (two GPI and two GPO)
  * One I2C and COM pin header (for two I2C pair and two COM connector that’s only
    supports Tx/Rx)
  * One Front Audio pin header (for Line-In, Line-Out and Mic-In)

* Onboard Pin Jumpers:

  * One Backlight power select jumper
  * One Panel power select jumper
  * One Miscellaneous select jumper (for SD write protect, line-out and auto power-on select)
  * One Clear CMOS select jumper
  * One Mini PCIe version select jumper

* Supported Operating System: Android 4.3
* Operating Conditions

  * Operating Temperature: 0°C to 60°C
  * Operating Humidity: 0% ~ 95% (relative humidity; non-condensing)

* Power Supply: DC 12V
* Form Factor: Pico-ITX, 10 cm x 7.2 cm (10-layer PCB)

.. note:: As the operating temperature provided in the specifications is a result of the test performed in VIA’s
	  chamber, a number of variables can influence this result. Please note that the working temperature may
	  vary depending on the actual situation and environment. It is highly suggested to execute a solid
	  testing and take all the variables into consideration when building the system. Please ensure that the
	  system runs well under the operating temperature in terms of application.

Layout Diagram
--------------

.. _figure-layout-top:
.. figure:: images/layout_top.*
   :align: center
   :alt: Layout diagram of the VAB-1000 mainboard, top view

   Layout diagram of the VAB-1000 mainboard, top view

.. _figure-layout-bottom:
.. figure:: images/layout_bottom.*
   :align: center
   :alt: Layout diagram of the VAB-1000 mainboard, bottom view

   Layout diagram of the VAB-1000 mainboard, top view


Layout diagram description:

===== =====================================================================
Item  Description
===== =====================================================================
1     DDR3 memory
2     JM3: Miscellaneous select jumper
3     PWR1: SATA power connector
4     CN9: SPI and GPIO combination pin header
5     WLAN1: WLAN connector
6     CN8: COM and I2C combination pin header
7     JSF1: SPI flash connector
8     CN7: Front panel, USB 2.0 and COM combination pin header
9     SATA1: SATA connector
10    CN6: Front audio pin header
11    eMMC/NAND Flash ROM
12    MPCIE_SET1: Mini PCIe revision select jumper
13    JM1: Clear CMOS jumper
14    VGA1: VGA pin header
15    BAT1: RTC battery connector
16    VIA Elite E1000 ARM Cortex-A9 Dual Core 1 GHz processor
17    PBL_SET1: Backlight power select jumper
18    PVDD_SET1: Panel power select jumper
19    MPCIE1: Mini PCIe slot
20    JTAG1: JTAG connector
21    DDR3 memory
22    LVDS1: LVDS connector
===== =====================================================================

Product Dimensions
------------------

.. _figure-dimensions-top:
.. figure:: images/dimensions_top.*
   :align: center
   :alt: Dimensions of VAB-1000, top view

   Dimensions of VAB-1000, top view

.. _figure-dimensions-side:
.. figure:: images/dimensions_side.*
   :align: center
   :alt: Dimensions of VAB-1000, side view

   Dimensions of VAB-1000, side view

Height Distribution
-------------------

.. _figure-height-top:
.. figure:: images/height_top.*
   :align: center
   :alt: Height distribution of VAB-1000, top view

   Height distribution of VAB-1000, top view

.. _figure-height-bottom:
.. figure:: images/height_bottom.*
   :align: center
   :alt: Height distribution of VAB-1000, bottom view

   Height distribution of VAB-1000, bottom view
