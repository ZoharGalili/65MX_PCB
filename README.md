# The65MX Keyboard PCB

a 65% keyboard pcb for use with my future keyboard projects.

## Features

### big components and BAV-70 diodes

I plan to assemble the pcb by hand to save costs as I have no problem putting the time to solder commponents by hand. for this reason i chose to not have any footprints smaller than an 0805 and also use BAV-70 dual diodes as i belive it will take less time to solder a single BAV-70 than two standard diodes.

### JST_SH daughterboard connector

I like the UBD-S daughterboard for case design but I have learned from a previous keyboard project that the molex EZmate connector is shit. I probably didnt solder it properly and it repeatedly snapped of the board. for this exact reason I desined the [UBD-S-JST](https://github.com/ZoharGalili/UDB-S-JST), a fork of the [UBD-S](https://github.com/Unified-Daughterboard/UDB-S) with a JST connecotr along with some ohter changes.

### QMK firmware and VIA support

the PCB uses an STM32f072 microcontroller. I have made a keyboard with this microcontroller before running QMK with VIA 

### bakeneko65 and ai03 vega board outline

I coppied the board outline of the bekeneko for supporting a gummy o-ring friction fit mount. I also took the 4 outer plate mounting standoff points from the ai03 vega so i took the board outline as well.

### soldered MX switches

I have encountered problems before with the standard keilh hot swap sockets so i decided to make a solder pcb this time. mill max sockets exits so if I ever want to have a hotswap board I can pop those in.

### multilatout support

the board supports 6.25u or 7u spacebar, stepped caps lock and split backspace. this isnt the most layouts in a board but i feel like those are the layouts that I may want to use and I dont want to go crazy with layout support.

![layout](/PCB_Files/renders/layout.jpg)

## board renders

![front](/PCB_Files/renders/front.png)

![back](/PCB_Files/renders/back.png)