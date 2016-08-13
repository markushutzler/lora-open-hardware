LoRa Open Hardware
##################

Current project status: `Pre-alpha`


Dependencies
============

To compile, design and export schematic or PCB files a list of dependencies
need to be installed.

 - geda-gaf
 - pcb
 - gerbv
 - python2
 - autosym

Schematic Files
===============

Schematic files are found in `hardware/` and can be edited by gschem
(geda-gaf project). Some symbols need to be compiled first.

::

        cd hardware
        make

If autosym is not installed follow the guide on
https://github.com/markushutzler/autosym.
