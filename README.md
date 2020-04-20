# Macintosh Classic II FPU / ROM board

Designed by Joshua Ryan (<360alaska@gmail.com>) and Paralel.  Pre-built boards can be purchased from Joshua at https://www.ebay.com/usr/alaska360?_trksid=p2047675.l2559

## Operation

The FPU can be any 68-pin PLCC M68882.  If you are using a 40MHz chip, you must move the "Clock Select" jumper to "C".
 
ROM image operation is documented at http://www.synack.net/~bbraun/classic2.html

Although the original thread has been purged from 68kmla, it has been archived at https://web.archive.org/web/20170707023942/https://68kmla.org/forums/index.php?/topic/23149-classic-ii-fpurom-card/

## Parts list

All capacitors are 0.1µF non-polarized ... except for a single 4.7µF polarized as marked on the board.

The FPU socket is a 68-pin PLCC, Mouser #517-8468-11B1-RK-TP or similar.

The board connector is an AMP 532955-8, Mouser #571-5-532955-8 or similar.  .

The oscillator is a 40MHz standard oscillator, Mouser #520-2200B-400 or similar.

The ROM can be either a MC27160 (2MiB) or M27C322 (4MiB) 

## Circuit board fabrication details

v4.9 is a four-layer board.

The .pcb file is a DesignSpark board file.

The .zip file contains the Gerbers for PCB fabrication.  These work as-is with PCBway.
