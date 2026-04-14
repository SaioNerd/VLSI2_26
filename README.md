**Overview**<br>
This repository implements a Hardware Integrity Layer designed for the Croc SoC. The module acts as a synchronous interposer between the OBI (Open Bus Interface) crossbar and the physical SRAM primitives. It ensures data persistence reliability by implementing a Linear Block Code (LBC) wrapper around standard memory macros.

**Project Context**<br>
This chip was designed as part of the [VLSI design](https://vlsi.ethz.ch/wiki/Main_Page) course at ETH Zurich which uses a (mostly) open source design flow for its exercises. Students are required to modify a [Croc](https://github.com/pulp-platform/croc) based SoC to improve its capabilities somehow to pass the course.

This work received generous support from the Leibniz Institute for High Performance Microelectronics through the BMBF project FMD-QNC (16ME0831).
