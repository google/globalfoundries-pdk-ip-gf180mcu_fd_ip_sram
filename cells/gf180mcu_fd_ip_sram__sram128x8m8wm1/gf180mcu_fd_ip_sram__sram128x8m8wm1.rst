***********************************
gf180mcu_fd_ip_sram__sram128x8m8wm1
***********************************

.. centered::
   **gf180mcu_fd_ip_sram__sram128x8m8wm1**
.. centered::
   **180nm 5V Green synchronous single port SRAM**
.. centered::
   **Memory Macro IP**
.. centered::
   **Datasheet**

====

**Features**

- Uses 180nm 5V Green CMOS 13.5um2 6 transistors bitcell

- 128 words X 8 bits, mux 8 Instance

- Periphery circuitry uses 5V transistors

- Operating voltage is 1.62V to 5.50V

- Operating temperature is -40 degC to 125 degC

- Minimum 3 layers of metals required: Metal1, Metal2, Metal3

- Bit write mask

- Self timed operation to reduce power

- Separate data in and data out ports

- Macro cell name: gf180mcu_fd_ip_sram__sram128x8m8wm1


====================
1.0 Pins Description
====================

.. csv-table::
   :file: specs/1_pins_desc.csv

===============
2.0 Truth Table
===============

.. csv-table::
   :file: specs/2_truth_table.csv

.. note::

    X: don't care

=========================================
3.0 Capacitance loading ( fF ) @ TT, 25°c
=========================================

.. csv-table::
   :file: specs/3_Capacitance_loading.csv

============================
4.0 Power Consumption ( uW )
============================

Condition of AC Write power is all data input pins switch and AC Read power is all address input and data output pins switch at 1MHz

==============
4.1 5.0V Power
==============

.. csv-table::
   :file: specs/4_Power_Consumption1.csv

==============
4.2 3.3V Power
==============

.. csv-table::
   :file: specs/4_Power_Consumption2.csv

==============
4.3 1.8V Power
==============

.. csv-table::
   :file: specs/4_Power_Consumption3.csv

======================
5.0 AC Characteristics
======================

The timing and power values measured from the input slew of 20ps on clock pin, 20ps on signal and output load .01pF.

===========================
5.1 5.0V AC Characteristics
===========================

.. csv-table::
   :file: specs/5_AC_Characteristics1.csv

===========================
5.2 3.3V AC Characteristics
===========================

 .. csv-table::
    :file: specs/5_AC_Characteristics2.csv

===========================
5.3 1.8V AC Characteristics
===========================

.. csv-table::
   :file: specs/5_AC_Characteristics3.csv

.. centered::
    **AC Timing Waveform Chart**

.. image:: specs/ac_timing.png
   :width: 600
   :align: center
   :alt: AC Timing Waveform Chart

=======================
6.0 Physical Dimensions
=======================

.. csv-table::
   :file: specs/6_Physical_Dimensions.csv

