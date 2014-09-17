.. _iointerface:

I/O Interface
=============

The VIA VAB-1000 has a wide selection of interfaces integrated into the board.
It includes a selection of frequently used ports as part of the rear I/O coastline.

Rear I/O Ports
--------------

.. _figure-rear-io:
.. figure:: images/rear_io.*
   :align: center
   :alt: Rear I/O ports

   Rear I/O ports

Layout diagram description table of Rear I/O ports:

===== ===========================
Item  Description
===== ===========================
1     CN1: DC-In jack
2     SD1: Micro SD card slot
3     USB1: Mini USB 2.0 port
4     HDMIO1: HDMI Out port
5     HDMIIN1: HDMI In port
6     LAN1: RJ-45 LAN port
===== ===========================

DC-In Jack
^^^^^^^^^^

The mainboard comes with a DC power input jack on the rear I/O panel
adjacent to the Micro SD slot. The power connector carriers +12V DC external
power input. The specifications and pinout of power connector are shown
below.

.. _figure-dc-in:
.. figure:: images/dc_in.*
   :align: center
   :alt: DC-In jack diagram

   DC-In jack diagram

DC-In jack specifications:

================ =========
Spec             Value
================ =========
Outer Diameter   3.7 mm
Inner Diameter   1.3 mm
Barrel Depth     8.25 mm
Input Voltage    12V
================ =========

Micro SD Card Slot
^^^^^^^^^^^^^^^^^^

The mainboard comes with a Micro SD card slot located on the rear I/O panel.
Micro SD card slot offers expandable storage

.. _figure-sd-card:
.. figure:: images/sd_card.*
   :align: center
   :alt: Micro SD Card slot diagram

   Micro SD Card slot diagram

Micro SD Card slot pinout:

==== ===========
Pin  Signal
==== ===========
1    SD0DATA2
2    SD0DATA3
3    SD0CMD
4    VDD (3.3V)
5    SD0CLK
6    GND
7    SD0DATA0
8    SD0DATA1
9    SD0_CD
==== ===========

Mini USB 2.0 Port
^^^^^^^^^^^^^^^^^

There are two integrated Mini USB 2.0 ports located on the rear I/O panel. The
Mini USB 2.0 interface port gives complete Plug and Play and hot swap
capability for external devices and it complies with USB UHCI, rev. 2.0. Each
Mini USB port uses the USB Type AB receptacle port connector. The pinout of
the typical Mini USB port is shown below.

.. _figure-usb-port:
.. figure:: images/usb_port.*
   :align: center
   :alt: Mini USB port diagram

   Mini USB port diagram

Mini USB 2.0 port pinout:

==== ===========
Pin  Signal
==== ===========
1    VCC (+5V)
2    USBH1-
3    USBH1+
4    ID (GND)
5    GND
==== ===========

HDMI Out Port
^^^^^^^^^^^^^

The HDMI® Out port is used to connect high definition video and digital audio
using a single cable. It allows connecting the digital video devices which
utilize a high definition video signal. The HDMI Out port uses an HDMI

Type C receptacle connector as defined in the HDMI specification. The
pinout of the HDMI® Out port is shown below.

.. _figure-hdmi-out:
.. figure:: images/hdmi.*
   :align: center
   :alt: HDMI® Out port diagram

   HDMI® Out port diagram

HDMI® Out port pinout:

===== ======================
Pin   Signal
===== ======================
1     TMDS Data2 Shield
2     TMDS Data2+
3     TMDS Data2-
4     TMDS Data1 Shield
5     TMDS Data1+
6     TMDS Data1-
7     TMDS Data0 Shield
8     TMDS Data0+
9     TMDS Data0-
10    TMDS Clock Shield
11    TMDS Clock+
12    TMDS Clock-
13    DDC/CEC Ground
14    CEC
15    SCL
16    SDA
17    Reserved
18    +5V Power
19    Hot Plug Detect
===== ======================

2.1.5. HDMI ® In Port
The HDMI ® In port is used for connecting an external digital/video sources
such as HD-DVD player, Blu-ray players, satellite boxes and etc. The HDMI
In port uses an HDMI Type C receptacle connector as defined in the HDMI
specification. The pinout of the HDMI ® In port is shown below.


.. _figure-hdmi-in:
.. figure:: images/hdmi.*
   :align: center
   :alt: HDMI® In port diagram

   HDMI® In port diagram

HDMI® In port pinout:

===== ======================
Pin   Signal
===== ======================
1     TMDS Data2 Shield
2     TMDS Data2+
3     TMDS Data2-
4     TMDS Data1 Shield
5     TMDS Data1+
6     TMDS Data1-
7     TMDS Data0 Shield
8     TMDS Data0+
9     TMDS Data0-
10    TMDS Clock Shield
11    TMDS Clock+
12    TMDS Clock-
13    DDC/CEC Ground
14    CEC
15    SCL
16    SDA
17    Reserved
18    +5V Power
19    Hot Plug Detect
===== ======================

RJ-45 LAN port (Gigabit Ethernet)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The VAB-1000 is equipped with a Gigabit Ethernet LAN port. The Gigabit
Ethernet LAN port is using 8 Position 8 Contact (8P8C) receptacle connector
or commonly referred to as RJ-45. It is fully compliant with IEEE 802.3
(10BASE-T), 802.3u (100BASE-TX), and 802.3ab (1000BASE-T) standards. The
pinout of the LAN port is shown below.

.. _figure-lan:
.. figure:: images/lan.*
   :align: center
   :alt: RJ-45 LAN port diagram

   RJ-45 LAN port diagram

RJ-45 LAN port pinout:

==== =============
Pin  Signal
==== =============
1    LAN1_TD0+
2    LAN1_TD0-
3    LAN1_TD1+
4    LAN1_TD1-
5    LAN1_TD2+
6    LAN1_TD2-
7    LAN1_TD3+
8    LAN1_TD3-
==== =============

The LAN port has two individual LED indicators located on the front side to
show its Active/Link status and Speed status. RJ-45 LAN port color LED definition:

=============== ======================================= =======================================
Mode            Left LED                                Right LED
=============== ======================================= =======================================
Link Off        Off                                     Off
Speed_10Mbit    The LED is On in Green color (flash)    Off
Speed_100Mbit   The LED is On in Red color (flash)      Off
Speed_1000Mbit  Off                                     The LED is On in Orange color(flash)
=============== ======================================= =======================================

Onboard Connectors
------------------

RTC Battery Connector
^^^^^^^^^^^^^^^^^^^^^

The mainboard is equipped with onboard RTC battery connector used for
connecting the external cable battery that provides power to the 32.768KHz
crystal oscillator for Real Time Clock (RTC). The RTC battery connector is
labeled as BAT1. The connector pinout is shown below.

.. _figure-rtc:
.. figure:: images/rtc.*
   :align: center
   :alt: RTC Battery connector diagram

   RTC Battery connector diagram

RTC Battery connector pinout:

==== =======
Pin  Signal
==== =======
1    VBAT
2    GND
==== =======

SATA Connector
^^^^^^^^^^^^^^

The SATA connector on board can support up to 3 Gb/s transfer speeds. The
SATA connector is labeled as SATA1 and it can support 2.5" SATA SSD. The
pinout of the SATA connector is shown below.

.. _figure-satar:
.. figure:: images/sata.*
   :align: center
   :alt: SATA connector diagram

   SATA connector diagram

SATA connector pinout:

===== ============
Pin   Signal
===== ============
1     GND
2     STXP_1
3     STXN_1
4     GND
5     SRXN_1
6     SRXP_1
7     GND
===== ============

SATA Power Connector
^^^^^^^^^^^^^^^^^^^^

The VAB-1000 is equipped with 3-pin SATA power connector used for
connecting SATA SSD power cable to power 2.5" SATA SSD. When
connecting the SATA SSD power cable, make sure the power plug is inserted
in the proper orientation and pins are properly aligned. The SATA power
connector is labeled as PWR1. The pinout of the SATA power connector is
shown below.

.. _figure-sata-power:
.. figure:: images/sata_power.*
   :align: center
   :alt: SATA SSD power connector diagram

   SATA SSD power connector diagram

SATA SSD power connector pinout:

==== =========
Pin  Signal
==== =========
1    VDD5V
2    VDD12V
3    GND
==== =========

SPI Flash Connector
^^^^^^^^^^^^^^^^^^^

The mainboard has one 8-pin SPI flash connector. The SPI (Serial Peripheral
Interface) flash connector is used to update the Boot Leader EEPROM. The
connector is labeled as JSF1. The pinout of the connector is shown below.

.. _figure-spi:
.. figure:: images/spi.*
   :align: center
   :alt: SPI Flash connector diagram

   SPI Flash connector diagram

SPI Flash connector pinout:

==== ========================= ===== ===========
Pin  Signal                    Pin   Signal
==== ========================= ===== ===========
1    VDD33_SF (VDD33_SPI VDD)  2     GND
3    SF_CS0-                   4     SF_CLK
5    SF_MISO                   6     SF_MOSI
7    No Connect                8     No Connect
==== ========================= ===== ===========

WLAN Connector
^^^^^^^^^^^^^^

The mainboard has a WLAN connector labeled as WLAN1. The WLAN
connector is used to attach WLAN USB module to provide WiFi connectivity.
The pinout of the connector is shown below.

.. _figure-wlan:
.. figure:: images/wlan.*
   :align: center
   :alt: WLAN connector diagram

   WLAN connector diagram

WLAN connector pinout:

===== ==============
Pin   Signal
===== ==============
1     NC
2     WLAN_LED
3     GND
4     USBH1_C_2DP_1
5     USBH1_C_20M_1
6     VCC_USB1
===== ==============

.. note:: WLAN connector shares the same USB signal port with Mini PCIe. Whenever the WLAN is connected,
	  Mini PCIe is automatically disabled, and vice versa. Please refer to :ref:`misc-jumpers`.

VGA Pin Header
^^^^^^^^^^^^^^

The mainboard has one 2 x 6-pin VGA pin header for CRT display. The pin
header is labeled as VGA1. The pinout of the connector is shown below.

.. _figure-vga:
.. figure:: images/vga.*
   :align: center
   :alt: VGA pin header diagram

   VGA pin header diagram

VGA pin header pinout:

==== ========== ==== ===========
Pin  Signal     Pin  Signal
==== ========== ==== ===========
1    VGA_R      2    5VCRT
3    VGA_G      4    GND
5    VGA_B      6    VGA_SDA
7    GND        8    VGA_SCL
9    NC         10   VGA_VSYNC
11   VGA_HSYNC  12   GND
==== ========== ==== ===========

.. note:: This function is reserved for factory production only.

Front Audio Pin Header
^^^^^^^^^^^^^^^^^^^^^^

The mainboard has a front audio pin header for connecting the Line-Out, Line-
In and Mic-In jacks. The pin header is labeled as CN6. The pinout of the pin
header is shown below.

.. _figure-audio:
.. figure:: images/audio.*
   :align: center
   :alt: Front audio pin header diagram

   Front audio pin header diagram

Front audio pin header pinout

==== =========== ==== ========
Pin  Signal      Pin  Signal
==== =========== ==== ========
1    LINEIN_R    2    AUD_GND
3    LINEIN_L    4    MICIN1
5    LINEOUT_R   6    MICIN2
7    LINEOUT_L   8    HP_DET-
==== =========== ==== ========

Front Panel, USB 2.0 and COM Combination Pin Header
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The mainboard includes one Front Panel, USB2.0 and COM combination pin
header block labeled as CN7. The front panel, USB2.0 and COM
combination pin header is used to connect the power switch, reset switch,
power LED, suspend LED, SSD LED, case speaker, additional USB 2.0 port and
RS232/Console port. The pinout of the pin header is shown below.

.. _figure-combination-pin:
.. figure:: images/combination_pin.*
   :align: center
   :alt: Front Panel, USB 2.0 and COM combination pin header diagram

   Front Panel, USB 2.0 and COM combination pin header diagram

Front Panel, USB 2.0 and COM combination pin header pinout:

==== ===================================== ==== =================
Pin  Signal                                Pin  Signal
==== ===================================== ==== =================
1    PWR_LED (Series 470 ohm resistance)   2    VDD33_SUS/0.5A
3    PWR_BUTTON#                           4    GND
5    RESET_GD                              6    GND
7    -HD_LED1 (Series 470 ohm resistance)  8    VDD50/0.5A
9    VCC_USB2/0.5A                         10   VCC_USB3/0.5A
11   USBH2_C_DM                            12   USBH3_C_DM
13   USBH2_C_DP                            14   USBH3_C_DP
15   GND                                   16   GND
17   DTE1_TXD_C                            18   DTE1_RXD_C
19   HWTP_1                                20   USBH123_SW
==== ===================================== ==== =================

COM and I2C Combination Pin Header
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The COM and I2C combination pin header block labeled as CN8 is used for
connecting I2C device and additional COM connector that supports Tx/Rx. The
pinout of the pin header is shown below.

.. _figure-com:
.. figure:: images/com.*
   :align: center
   :alt: COM and I2C combination pin header diagram

   COM and I2C combination pin header diagram

COM and I2C combination pin header pinout:

==== =============== ==== =========================
Pin  Signal          Pin  Signal
==== =============== ==== =========================
1    VDD33_SUS/0.5A  2    VDD33/0.5A
3    DTE0_TXD_C      4    NC
5    DTE0_RXD_C      6    NC
7    GND             8    I2C0_SCL(IPU to VDD33)
9    DTE2_TXD_C      10   I2C0_SDA(IPU to VDD33)
11   DTE2_RXD_C      12   I2C1_SCL(IPU to VDD33)
13   GND             14   I2C1_SDA(IPU to VDD33)
15   PMIC_CONF_SCL   16   PMIC_CONF_SDA
==== =============== ==== =========================

SPI and GPIO Combination Pin Header
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The SPI and GPIO combination pin header block labeled as CN9 is used for
connecting SPI device, and General Purpose Input and Output. The pinout of
the pin header is shown below.

.. _figure-spi-pin:
.. figure:: images/spi_pin.*
   :align: center
   :alt: SPI and GPIO pin header diagram

   SPI and GPIO pin header diagram

SPI and GPIO pin header pinout:

==== ======================================= ==== =====================================================================
Pin  Signal                                  Pin  Signal
==== ======================================= ==== =====================================================================
1    VDD3318_DVP (for GFX GPIO Power)/100mA  2    VDD50_SUS/0.5A
3    GND                                     4    VDD33 For GPIO Power)/0.5A
5    GFX_GPIO11 (Graphics GPIO11)            6    SPI1_CLK : SPI1 Host Interface Clock, GPIO5
7    GFX_GPIO12 (Graphics GPIO12)            8    SPI1_MISO : SPI1 Host Interface Master Input, Slave Output, GPIO6
9    GFX_GPIO13 (Graphics GPIO13)            10   SPI1_MOSI :SPI1 Host Interface Master Output, Slave Input, GPIO7
11   GFX_GPIO14 (Graphics GPIO14)            12   SPI1 Host Interface Slave Select Active-low, GPIO8
13   GND                                     14   GND
==== ======================================= ==== =====================================================================

JTAG Connector
^^^^^^^^^^^^^^

The JTAG connector provides a set of JTAG signals that allow JTAG
debugging equipment to be used. The connector is labeled as JTAG1. The
pinout of the connector is shown below.

.. _figure-jtag:
.. figure:: images/jtag.*
   :align: center
   :alt: JTAG connector diagram

   JTAG connector diagram

JTAG connector pinout:

==== =========== ==== ==========
Pin  Signal      Pin  Signal
==== =========== ==== ==========
1    GND         2    NC
3    JTAG_TRST#  4    JTAG_TD0
5    JTAG_TDI    6    JTAG_TMS
7    JTAG_TCK    8    VDD33
==== =========== ==== ==========

LVDS Connector
^^^^^^^^^^^^^^

The mainboard has one LVDS connector on the bottom side of the board. The
LVDS connector can connect the panel’s LVDS cable to support the dual-
channel 18-bit/24-bit display. The LVDS connector is labeled as LVDS1. The
pinout of the connector is shown below.

.. _figure-lvds:
.. figure:: images/lvds.*
   :align: center
   :alt: LVDS connector diagram

LVDS connector pinout:

==== ==================================== ==== ===================================
Pin  Signal                               Pin  Signal
==== ==================================== ==== ===================================
1    PVDD1 (for Panel VDD +5V or +3.3V)   2    PVDD1 (for Panel VDD +5V or +3.3V)
3    PVDD1 (for Panel VDD +5V or +3.3V)   4    VDD50
5    VDD50                                6    VDD_BL (for Panel BL +12V or +5V)
7    VDD_BL (for Panel BL +12V or +5V)    8    VDD_BL (for Panel BL +12V or +5V)
9    GND                                  10   A0M1
11   A0P1                                 12   GND
13   A1M1                                 14   A1P1
15   GND                                  16   A2M1
17   A2P1                                 18   GND
19   A3M1                                 20   A3P1
21   GND                                  22   CLK1M1
23   CLK1P1                               24   GND
25   A4M1                                 26   A4P1
27   GND                                  28   A5M1
29   A5P1                                 30   GND
31   A6M1                                 32   A6P1
33   GND                                  34   A7M1
35   A7P1                                 36   GND
37   CLK2M1                               38   CLK2P1
39   VDD33 for EDID Power                 40   LCD_CLK (I2C CLK)
41   LCD_DATA (I2C DATA)                  42   ENABLT1 (Enable BL)
43   BAK_ADJ                              44   NC
45   NC                                   46   NC
47   NC                                   48   NC
49   NC                                   50   NC
==== ==================================== ==== ===================================
