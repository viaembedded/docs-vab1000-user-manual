.. _installation:

Hardware Installation
=====================

Installing the VAB-1000-T
-------------------------
The VAB-1000 board comes with a VAB-1000-T companion card. The VAB-1000-T
companion card is connected through CN6, CN7, CN8 and CN9 pin
headers.

**Step 1**

Align the Audio and Front panel_USB_COM board-to-board connectors on
the VAB-1000-T with the CN6 and CN7 combinations pin header block on the
VAB-1000 board.

.. _figure-companion-card:
.. figure:: images/companion_card.*
   :align: center
   :alt: Installing the VAB-1000-T companion card

   Installing the VAB-1000-T companion card

**Step 2**

Then gently press down and apply even pressure until the pins on the VAB-
1000 board have been fully inserted into the Audio and Front
panel_USB_COM board-to-board connectors of the VAB-1000-T companion
card.

**Step 3**

Secure the VAB-1000-T to the chassis with two screws.

.. _figure-companion-card-2:
.. figure:: images/companion_card_2.*
   :align: center
   :alt: Securing the VAB-1000-T companion card

   Securing the VAB-1000-T companion card

Installing the VAB-1000-L (optional)
------------------------------------

**Step 1**

Insert one end of the board to board flex cable to the Board to Board connector on
VAB-1000-L daughter board and the other end to LVDS connector on VAB-1000
mainboard.

**Step 2**

Connect the 1-Channel backlight connector to the LVDS panel display.

.. _figure-lvds-card-1:
.. figure:: images/lvds_card_1.*
   :align: center
   :alt: Connect the 1-CH backlight connector to the LVDS panel

   Connect the 1-CH backlight connector to the LVDS panel

**Step 3**

Install the VAB-1000-L daughter board to a suitable surface and secure it with
two screws.

.. _figure-lvds-card-2:
.. figure:: images/lvds_card_2.*
   :align: center
   :alt: Install the VAB-1000-L to a suitable surface

   Install the VAB-1000-L to a suitable surface


**Step 4**

Connect the 2-Channel LVDS connector & 2-Channel Backlight connector to
the 10.4" LVDS panel display.

.. _figure-lvds-card-3:
.. figure:: images/lvds_card_3.*
   :align: center
   :alt: Connect the 2-CH LVDS & 2-CH Backlight connector to 10.4" LVDS panel

   Connect the 2-CH LVDS & 2-CH Backlight connector to 10.4" LVDS panel

**Step 5**
Connect the DC-In power cable to the DC-In connector.

.. _figure-lvds-card-4:
.. figure:: images/lvds_card_4.*
   :align: center
   :alt: Connect the DC-In power cable

   Connect the DC-In power cable

.. note:: Connect the 1-Channel LVDS connector to the LVDS panel display, if necessary.

Installing the Mini PCIe module
-------------------------------

**Step 1**

Align the notch on the Mini PCIe module with the counterpart on the Mini
PCIe slot then insert the module at 30° angle.

.. _figure-pcie-card-1:
.. figure:: images/pcie_card_1.*
   :align: center
   :alt: Inserting the mini PCIe module

   Inserting the mini PCIe module

**Step 2**

Once the module has been fully inserted, push down the module until the
screw holes align with the mounting holes on the hex spacer screws. Secure
the module with two screws (6 mm) to the standoffs.

.. _figure-pcie-card-2:
.. figure:: images/pcie_card_2.*
   :align: center
   :alt: Securing the mini PCIe module

   Securing the mini PCIe module

Installing into a Chassis
-------------------------

The VAB-1000 can be fitted into any chassis that has the mounting holes for
compatible with the standard Pico-ITX mounting hole locations. Additionally,
the chassis must meet the minimum height requirements for specified areas of
the board. If the companion card VAB-1000-T is being used, the chassis will
need to accommodate the additional space requirements.

Suggested minimum chassis dimensions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The figure below shows the suggested minimum space requirements that a
chassis should have in order to work well with the VAB-1000.

.. _figure-minimum-chassis_1:
.. figure:: images/minimum_chassis_1.*
   :align: center
   :alt: Suggested minimum chassis dimensions

   Suggested minimum chassis dimensions

Each side of the board should have a buffer zone from the internal wall of the
chassis. The side of the board that accommodates the I/O coastline should
have a buffer of 1.5 mm. The side on the opposite end of the I/O coastline that
has SATA connector and board-to-board pin headers should have a buffer of
at least 12 mm, or 27 mm if the VAB-1000-T companion card will be used.
The two sides adjacent to the I/O coastline should have at least a 2 mm buffer.

Suggested minimum chassis height
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The figure below shows the suggested minimum height requirements for the
internal space of the chassis. It is not necessary for the internal ceiling to be
evenly flat. What is required is that the internal ceiling height must be strictly
observed for each section that is highlighted.

.. _figure-minimum-chassis_2:
.. figure:: images/minimum_chassis_2.*
   :align: center
   :alt: Suggested minimum internal chassis ceiling height

   Suggested minimum internal chassis ceiling height

.. note:: In getting the minimum height requirements for internal space of the chassis, it is required to consider
	  the heights of the connectors (such as JTAG connector and Mini PCIe slot) on the bottom side of the
	  VAB-1000 board.

Suggested keep out areas
^^^^^^^^^^^^^^^^^^^^^^^^

The figure below shows the areas of the mainboard that is highly suggested to
leave unobstructed.

.. _figure-keep-out-areas:
.. figure:: images/keep_out_areas.*
   :align: center
   :alt: Suggested keep out areas

   Suggested keep out areas
