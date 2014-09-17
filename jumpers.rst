.. _jumpers:

Jumpers
=======

**Jumper Description**

A jumper consists of pair conductive pins used to close in or bypass an
electronic circuit to set up or configure particular feature using a jumper cap.
The jumper cap is a small metal clip covered by plastic. It performs like a
connecting bridge to short (connect) the pair of pins. The usual colors of the
jumper cap are black/red/blue/white/yellow.

**Jumper Setting**
There are two settings of the jumper pin: *Short* and *Open*. The pins are
*Short* when a jumper cap is placed on the pair of pins. The pins are *Open* when
the jumper cap is removed.

In addition, there are jumpers that have three or more pins, and some pins are
arranged in series. In case of a jumper with three pins, place the jumper cap on
pin 1 and pin 2 or pin 2 and 3 to *Short* it.

Some jumper size is small or mounted on the crowded location of the board
that makes it difficult to access. Therefore, using a long-nose pliers in installing
and removing the jumper cap is very helpful.

.. _figure-jumpers:
.. figure:: images/jumpers.*
   :align: center
   :alt: Jumper settings example

   Jumper settings example

.. warning:: Make sure to install the jumper cap on the correct pins. Installing it in the wrong pin might cause
	     damage and malfunction.

Backlight Power Select Jumper
-----------------------------

The mainboard has a jumper that controls the input voltage delivered to the
LVDS inverter connector. The jumper is labeled as PBL_SET1. The jumper
settings are shown below.

.. _figure-backlight:
.. figure:: images/backlight.*
   :align: center
   :alt: Backlight power select jumper diagram

   Backlight power select jumper diagram

Backlight power select jumper settings:

=============== ======= ======= =======
Settings        Pin 1   Pin 2   Pin 3
=============== ======= ======= =======
12V (Default)   Short   Short   Open
5V              Open    Short   Short
=============== ======= ======= =======

Panel Power Select Jumper
-------------------------

The mainboard has a jumper that controls the voltage delivered to the LVDS
panel connector. The jumper is labeled as PVDD_SET1. The jumper settings
are shown below.

.. _figure-panel-power:
.. figure:: images/panel_power.*
   :align: center
   :alt: Panel power select jumper diagram

Panel power select jumper settings:

================ ====== ====== ======
Settings         Pin 1  Pin 2  Pin 3
================ ====== ====== ======
5V               Short  Short  Open
3.3V (Default)   Open   Short  Short
================ ====== ====== ======

Clear CMOS Jumper
-----------------

The onboard CMOS RAM stores system configuration data and has an onboard
battery power supply. To reset the CMOS settings, set the jumper on pins 2
and 3 while the system is off. Return the jumper to pins 1 and 2 afterwards.
Setting the jumper while the system is on will damage the mainboard. The
jumper is labeled as JM1. The default setting is on pins 1 and 2.

.. _figure-cmos:
.. figure:: images/cmos.*
   :align: center
   :alt: Clear CMOS jumper diagram

   Clear CMOS jumper diagram

Clear CMOS jumper settings:

================== ====== ====== ======
Settings           Pin 1  Pin 2  Pin 3
================== ====== ====== ======
Normal (default)   Short  Short  Open
Clear CMOS         Open   Short  Short
================== ====== ====== ======

.. note:: Except when clearing the CMOS RAM, never remove the cap from the JM1 (Clear CMOS) jumper
	  default position. Removing the cap will cause system boot failure. Avoid clearing the CMOS while the
	  system is on; it will damage the mainboard.

Mini PCIe Revision Select Jumper
--------------------------------

The mainboard has a mini PCIe select jumper that determines the supported
revision specification of mini PCIe slot. The jumper is labeled as MPCIE_SET.
The jumper settings are shown below.

.. _figure-pcie-revision:
.. figure:: images/pcie_revision.*
   :align: center
   :alt: Mini PCIe revision select jumper diagram

   Mini PCIe revision select jumper diagram

Mini PCIe revision select jumper settings:

=============================== ====== ====== =======
Settings                        Pin 1  Pin 2  Pin 3
=============================== ====== ====== =======
Support Revision 1.2 (Default)  Short  Short  Open
Support Revision 1.1            Open   Short  Short
=============================== ====== ====== =======

.. _misc-jumpers:

Miscellaneous Select Jumper
---------------------------

The mainboard has a miscellaneous select jumper that is used to
enable/disable the SD card write protect, detect the active/inactive audio head
phone, and auto power-on function. The jumper is labeled as JM3. The
jumper settings are shown below.

.. _figure-misc-jumper:
.. figure:: images/misc_jumper.*
   :align: center
   :alt: Miscellaneous select jumper

Miscellaneous select jumper settings:

=============================== ==========
SD Card Write Protect Settings  Pin 1-2
=============================== ==========
Disable (Default)               Short
Enable                          Open
=============================== ==========

========== =========
Reserved   Pin 3-4
========== =========
(Default)  Short
           Open
========== =========

================================= ==========
Audio Head Phone Detect Settings  Pin 5-6
================================= ==========
Active (Default)                  Short
Inactive                          Open
================================= ==========

================================= ==========
USB Bus Selection Settings        Pin 7-8
================================= ==========
USB to Mini PCIe (Default)        Short
USB to WLAN                       Open
================================= ==========

======================================== ==========
Auto Power On Function by H/W Settings   Pin 9-10
======================================== ==========
Enable                                   Short
Disable (Default)                        Open
======================================== ==========
