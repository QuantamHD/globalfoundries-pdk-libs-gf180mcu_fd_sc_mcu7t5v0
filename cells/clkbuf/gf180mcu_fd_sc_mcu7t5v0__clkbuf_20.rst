=======================================
gf180mcu_fd_sc_mcu7t5v0__clkbuf_x20
=======================================

**gf180mcu_fd_sc_mcu7t5v0__clkbuf_x20 symbol**

.. image:: gf180mcu_fd_sc_mcu7t5v0__clkbuf_20.symbol.png
    :alt: gf180mcu_fd_sc_mcu7t5v0__clkbuf_x20 symbol

**gf180mcu_fd_sc_mcu7t5v0__clkbuf_x20 schematic**

.. image:: gf180mcu_fd_sc_mcu7t5v0__clkbuf.schematic.svg
    :alt: gf180mcu_fd_sc_mcu7t5v0__clkbuf_x20 schematic

**gf180mcu_fd_sc_mcu7t5v0__clkbuf_x20 layout**

.. image:: gf180mcu_fd_sc_mcu7t5v0__clkbuf_20.layout.png
    :alt: gf180mcu_fd_sc_mcu7t5v0__clkbuf_x20 layout



CLKBUF_X20 is a clock buffer, 20X drive strength

|
| Attributes

============= =======================
**Attribute** **Value**
area          136.102400 µm\ :sup:`2`
============= =======================

|
| OUTPUT FUNCTIONS

============== ============
**Output Pin** **Function**
Z              I
============== ============

|
| TRUTH TABLE FOR Z

===== =====
**I** **Z**
1     1
0     0
===== =====

|
| FUNCTIONAL SCHEMATIC

.. image:: gf180mcu_fd_sc_mcu7t5v0__clkbuf_20.png

| PIN CAPACITANCE (pf)

======= ======== ====================
**Pin** **Type** **Capacitance (pf)**
I       input    0.0280
======= ======== ====================

|
| DELAY AND OUTPUT TRANSITION TIME corresponding to min slew and load

+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| **Input Pin** | **Output** | **When Condition** | **Tin (ns)** | **Out Load (pf)** | **Delay (ns)** | **Tout (ns)** |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(LH)         | Z(LH)      | default            | 0.0100       | 0.0010            | 0.1898         | 0.0352        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(HL)         | Z(HL)      | default            | 0.0100       | 0.0010            | 0.1834         | 0.0339        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+

|
| DYNAMIC ENERGY

+---------------+--------------------+--------------+------------+-------------------+---------------------+
| **Input Pin** | **When Condition** | **Tin (ns)** | **Output** | **Out Load (pf)** | **Energy (uW/MHz)** |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(LH)      | 0.0010            | 1.8965              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(HL)      | 0.0010            | 2.3819              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+

|
| LEAKAGE POWER

================== ==============
**When Condition** **Power (nW)**
!I                 0.7944
I                  0.8268
================== ==============

