# Dactyl ManuForm Keyboard

This is a fork of the [Dactyl-ManuForm](https://github.com/tshort/dactyl-keyboard). The Dactyl-Manuform is a fork of the [Dactyl](https://github.com/adereth/dactyl-keyboard) with the thumb cluster from [ManuForm](https://github.com/jeffgran/ManuForm). Some features from the Dactyl Manuform Mini are kept along with new features added. 

## Features

- The use of sidenubs can be disabled. Sidenub should be disabled if you use Kailh, and Outemu. If you use Cherry MX, Gateron or Zealios switches, you can enable the sidenubs.

![sidenubs](https://i.imgur.com/bCpeHjh.png)
- Toggle for outer column between using 1.5u sized keys and 1u sized keys. If enabled, the rows which use 1.5u sized keys can be specified.

![1.5u outer column](https://i.imgur.com/3hZadLK.png)
- Toggle for an extra row of keys for the outer column(s).

![extra bottom row](https://i.imgur.com/Gw3qk6Q.png)
- Toggle for an extra inner column before the thumbcluster with (nrows-2) rows.

![inner column](https://i.imgur.com/GnxvHOQ.png)
- Toggle between using the manuform thumb cluster, the mini thumb cluster designed by [l4u](https://github.com/l4u/dactyl-manuform-mini-keyboard), and the cf thumb cluster.
- The cf thumb cluster uses the same keycaps as the manuform, but is more compact. The thumb only has to move one position left or right from its neutral position to reach all the keys. 

![thumb clusters](https://i.imgur.com/3dvW10o.png)
- Removable MCU / TRRS jack holder as a separate part. This holder slides into a cutout on the back wall of the case. Designed for common TRRS breakout boards.

![MCU holder](https://i.imgur.com/wwKsOYR.png) 
- Models for both pro-micro and elite-c holders in the [things/](things/) directory. 

## Generate OpenSCAD and STL models

* Run `lein generate` or `lein auto generate`
* This will regenerate the `things/*.scad` files
* Use OpenSCAD to open a `.scad` file.
* Make changes to design, repeat `load-file`, OpenSCAD will watch for changes and rerender.
* When done, use OpenSCAD to export STL files



## License

Copyright © 2015-2018 Matthew Adereth, Tom Short and Leo Lou

The source code for generating the models is distributed under the [GNU AFFERO GENERAL PUBLIC LICENSE Version 3](LICENSE).

The generated models are distributed under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE-models).
