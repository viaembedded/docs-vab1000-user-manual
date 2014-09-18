.. _appendix_a:

Appendix A: VAB-1000-T Companion Card
=====================================

Specifications
--------------

* Onboard Connectors and Jumper

  * One Front panel, USB and COM board-to-board connector
  * One Audio board-to-board connector
  * One COM pin header (for RS-232/Console)
  * One USB/COM select jumper

* Front Panel I/O

  * Three Audio jacks (Line-In, Line-Out and Mic-In)
  * One Power On status LED indicator
  * One SSD and USB/COM activity LED indicator
  * Two USB 2.0 ports
  * One Power On/Off button

* Supports three modes:

  * System Suspend/Resume (press the button once)
  * Popup power control menu (press the button for 4 seconds)
  * System Off (press the button for 8 seconds)

* Form Factor: 4-layers, 100 mm x 21 mm

VAB-1000-T Layout Diagram
-------------------------

.. _figure-companion-layout:
.. figure:: images/companion_layout.*
   :align: center
   :alt: VAB-1000-T layout labels

   VAB-1000-T layout labels

Layout diagram description table of VAB-1000-T:

====== ===================================================================================
Item   Description
====== ===================================================================================
1      PW_SW: Power On/Off button with Power LED
2      HD_LED: SSD activity LED indicator
3      USB/COM_LED: USB/COM indicator LED
4      USB2: USB 2.0 port
5      USB1: USB 2.0 port
6      LINE-IN: Line-In audio jack
7      LINE-OUT: Line-Out audio jack
8      MIC-IN: Mic-In audio jack
9      COM1: COM pin header
10     B2B_AUDIO: Audio board-to-board connector
11     B2B_FRONT_USB_COM: Front panel, USB 2.0 and COM board-to-board connector
12     USB_COM_SEL: USB/COM select jumper
====== ===================================================================================

VAB-1000-T Dimensions
---------------------

.. _figure-companion-dimensions:
.. figure:: images/companion_dimensions.*
   :align: center
   :alt: VAB-1000-T Dimensions

   VAB-1000-T Dimensions


VAB-1000-T Onboard Connectors and Jumpers
-----------------------------------------

Audio Board-to-Board Connector
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. _figure-companion-audio:
.. figure:: images/companion_audio.*
   :align: center
   :alt: Audio board-to-board connector diagram

   Audio board-to-board connector diagram

Audio board-to-board connector pinout:

==== =========== ==== ===========
Pin  Signal      Pin  Signal
==== =========== ==== ===========
1    LINEIN_R    2    GND_AUDIO
3    LINEIN_L    4    MICIN1
5    LINEOUT_R   6    MINI2
7    LINEOUT_L   8    HP_DET-
==== =========== ==== ===========

Front panel_USB_COM Board-to-Board Connector
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. _figure-companion-panel:
.. figure:: images/companion_panel.*
   :align: center
   :alt: Front panel/USB/COM board-to-board connector diagram

   Front panel/USB/COM board-to-board connector diagram

Front panel/USB/COM board-to-board connector pinout:

==== ============= ==== ==============
Pin  Signal        Pin  Signal
==== ============= ==== ==============
1    PWR_LED       2    VDD33_SUS
3    PWR_BUTTON-   4    GND
5    RESET_GND     6    GND
7    -HD_LED1      8    VDD50
9    VCC_USB2      10   VCC_USB3
11   USBH2_C_DM    12   USBH3_C_DM
13   USBH2_C_DP    14   USBH3_C_DP
15   GND           16   GND
17   DTE1_TXD_C    18   DTE1_RXD_C
19   HWTP_1        20   USBH123_SW
==== ============= ==== ==============

COM Pin Header
^^^^^^^^^^^^^^

.. _figure-companion-com:
.. figure:: images/companion_com.*
   :align: center
   :alt: COM pin header diagram

   COM pin header diagram

COM pin header pinout:

==== =============
Pin  Signal
==== =============
1    DTE1_TXD
2    DTE1_RXD_C
3    GND
==== =============

.. note:: Please use the COM connector cable provided for connection.

USB/COM Select Jumper
^^^^^^^^^^^^^^^^^^^^^

.. _figure-companion-comselect:
.. figure:: images/companion_comselect.*
   :align: center
   :alt: USB/COM select jumper diagram

   USB/COM select jumper diagram

USB/COM select jumper settings:

=============== ====== ====== ======
Setting         Pin 1  Pin 2  Pin 3
=============== ====== ====== ======
USB (Default)   Short  Short  Open
COM             Open   Short  Short
=============== ====== ====== ======
