.. _appendix_b:

Appendix B: VAB-1000-L Daughter Board (optional)
================================================

Specifications
--------------

* PCB: 68 mm x 47 mm (L x W), 4-Layer
* Onboard Connectors

  * 1 x Board-To-Board connector
  * 2 x LVDS connectors
  * 2 x Backlight connectors
  * 1 x DC-In connector

* Onboard Jumper

  * 1 x BL_SET

.. note:: Please ensure that all items in the packing list are present before using this product. If any of the items
	  are missing or damaged, contact your distributor or sales representative immediately.

VAB-1000-L Layout Diagram
-------------------------

.. _figure-lvds-layout-1:
.. figure:: images/lvds_layout_1.*
   :align: center
   :alt: VAB-1000-L layout labels, top view

   VAB-1000-L layout labels, top view

.. _figure-lvds-layout-2:
.. figure:: images/lvds_layout_2.*
   :align: center
   :alt: VAB-1000-L layout labels, bottom view

   VAB-1000-L layout labels, bottom view

Layout diagram description table of VAB-1000-L:

===== ===================================
Item  Description
===== ===================================
1     LVDS2: LVDS panel connector 2
2     BL_SET pin header
3     2CH_Backlight connector
4     LVDS1: LVDS panel connector 1
5     DC-In connector
6     1CH_Backlight connector
7     Board-To-Board connector
===== ===================================

VAB-1000-L Dimensions
---------------------

.. _figure-lvds-dimensions-1:
.. figure:: images/lvds_dimensions_1.*
   :align: center
   :alt: VAB-1000-L dimensions, top view

   VAB-1000-L dimensions, top view


.. _figure-lvds-dimensions-2:
.. figure:: images/lvds_dimensions_2.*
   :align: center
   :alt: VAB-1000-L dimensions, side view

   VAB-1000-L dimensions, side view

VAB-1000-L Onboard Connectors and Jumpers
-----------------------------------------

DC-In Connector
^^^^^^^^^^^^^^^

.. _figure-lvds-dc:
.. figure:: images/lvds_dc.*
   :align: center
   :alt: DC-In connector diagram

   DC-In connector diagram

===== ==========
Pin   Signal
===== ==========
1     GND 
2     DCIN
===== ==========

.. note:: Display panels using less than 12W do not need external power supply.

2CH Backlight Connector
^^^^^^^^^^^^^^^^^^^^^^^

.. _figure-lvds-backlight:
.. figure:: images/lvds_backlight.*
   :align: center
   :alt: 2CH Backlight connector diagram

   2CH Backlight connector diagram


2CH Backlight connector pinout:

==== ===========
Pin  Function 
==== ===========
1    VDD_BL_C
2    VDD_BL_C
3    ENABLT1
4    NC
5    NC
6    BL_CTL
7    GND
8    GND
==== ===========

2CH LVDS & BL Connector
^^^^^^^^^^^^^^^^^^^^^^^

.. _figure-lvds-2ch:
.. figure:: images/lvds_2ch.*
   :align: center
   :alt: 2CH LVDS & BL connector diagram

   2CH LVDS & BL connector diagram

2CH LVDS & BL connector pinout:

===== ============ ===== ================
Pin   Signal       Pin   Signal
===== ============ ===== ================
1     2CH_1LDC4-   2     PVDD1
3     2CH_1LDC4+   4     PVDD1
5     GND          6     GND
7     2CH_1LDC5-   8     GND
9     2CH_1LDC5+   10    2CH_1LDC0-
11    GND          12    2CH_1LDC0+
13    2CH_1LDC6-   14    GND
15    2CH_1LDC6+   16    2CH_1LDC1-
17    GND          18    2CH_1LDC1+
19    2CH_1LCLK2-  20    GND
21    2CH_1LCLK2+  22    2CH_1LDC2-
23    GND          24    2CH_1LDC2+
25    2CH_1LDC7-   26    GND
27    2CH_1LDC7+   28    2CH_1LCLK1-
29    NC           30    2CH_1LCLK1+
31    GND          32    GND
33    3.3V         34    2CH_1LDC3-
35    NC           36    2CH_1LDC3+
37    Reverse      38    LCD_CLK
39    SEL68        40    LCD_DAT
===== ============ ===== ================

1CH LVDS & BL Connector
^^^^^^^^^^^^^^^^^^^^^^^

.. _figure-lvds-1ch:
.. figure:: images/lvds_1ch.*
   :align: center
   :alt: 1CH LVDS & BL connector diagram

1CH LVDS & BL connector pinout:

===== ===============
Pin   Signal
===== ===============
1     NC
2     PVDD1
3     PVDD1
4     GND
5     GND
6     NC
7     1CH_1LDC0+
8     1CH_1LDC0-
9     GND
10    1CH_1LDC1+
11    1CH_1LDC1-
12    GND
13    1CH_1LDC2+
14    1CH_1LDC2-
15    GND
16    1CH_1LCLK1+
17    1CH_1LCLK1-
18    GND
19    1CH_1LDC3+
20    1CH_1LDC3-
21    GND
22    NC
23    NC 
24    GND
25    NC
26    PVDD1
27    NC
28    NC
29    NC
30    NC
===== ===============

BL_SET pin header
^^^^^^^^^^^^^^^^^

.. _figure-lvds-blset:
.. figure:: images/lvds_blset.*
   :align: center
   :alt: BL_SET pin header diagram

   BL_SET pin header diagram

BL_SET pin header pinout:

==== ================ ==== =========
Pin  Signal           Pin  Signal
==== ================ ==== =========
1    BAK_ADJ_M        2    BAK_ADJ
3    VDD33 (PU 4.7K)  4    BAK_ADJ
5    VDD50 (PU 10K)   6    BAK_ADJ
7    GND (PD 4.7K)    8    BAK_ADJ
9    VDD33 (PU 4.7K)  10   Reverse
11   VDD33 (PU 4.7K)  12   SEL68
==== ================ ==== =========


Board to board connector
^^^^^^^^^^^^^^^^^^^^^^^^

.. _figure-lvds-b2b:
.. figure:: images/lvds_b2b.*
   :align: center
   :alt: Board to board connector diagram

Board to board connector pinout:

===== =============
Pin   Singal
===== =============
1     GND
2     NC
3     NC
4     NC
5     NC
6     NC
7     NC
8     BAK_ADJ
9     ENABLT1
10    LCD_DATA
11    LCD_CLK
12    VDD33
13    CLK2P1
14    CLK2M1
15    GND
16    A7P1
17    A7M1
18    GND
19    A6P1
20    A6M1
21    GND
22    A5P1
23    A5M1
24    GND
25    A4P1
26    A4M1
27    GND
28    CLK1P1
29    CLK1M1
30    GND
31    A3P1
32    A3M1
33    GND
34    A2P1
35    A2M1
36    GND
37    A1P1
38    A1M1
39    GND
40    A0P1
41    A0M1
42    GND
43    VDD_BL
44    VDD_BL
45    VDD_BL
46    VDD50
47    VDD50
48    PVDD1
49    PVDD1
50    PVDD1
===== =============


1CH Backlight connector
^^^^^^^^^^^^^^^^^^^^^^^

.. _figure-lvds-1chbl:
.. figure:: images/lvds_1chbl.*
   :align: center
   :alt: 1CH Backlight connector diagram

   1CH Backlight connector diagram

1CH Backlight connector pinout:

==== =============
Pin  Signal
==== =============
1    NC
2    NC
3    BAK_ADJ
4    ENABLT1
5    NC
6    NC
7    NC
8    GND
9    GND
10   VDD_BL_C
11   VDD_BL_C
12   VDD_BL_C
==== =============

