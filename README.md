# F10-IEEE-IF - a CBM6400 / StarWriter F10 IEEE-488 interface clone
A 100% compatible replica of the F10-IEEE-IF IEEE-488 internal interface board used in the CBM 6400 daisy-wheel printer to convert the parallel interface of its StarWriter F10-based internals to the IEEE-488 bus used in the CBM PET series computers. 

![F10-IEEE-IF render](https://github.com/InsaneDruid/F10-IEEE-IF/blob/main/images/F10-IEEE-IO_render.png)

[Schematic](https://github.com/InsaneDruid/F10-IEEE-IF/blob/main/F10-IEEE-IF.pdf "Schematic")  

[Bill of Materials](https://htmlpreview.github.io/?https://github.com/InsaneDruid/F10-IEEE-IF/blob/main/bom/F10-IEEE-IF_bom.html "Bill of Materials")

## The IEEE-488 device number
There are 4 jumpers on the interface card that define the device number under which the printer can be accessed.
Set them according to the table:

| device number | J1 | J2 | J3 | J4 |
|---------------|----|----|----|----|
| 1             | 1  | 0  | 0  | 0  |
| 2             | 0  | 1  | 0  | 0  |
| 3             | 1  | 1  | 0  | 0  |
| 4 (default)   | 0  | 0  | 1  | 0  |
| 5             | 1  | 0  | 1  | 0  |
| 6             | 0  | 1  | 1  | 0  |
| 7             | 1  | 1  | 1  | 0  |
| 8             | 0  | 0  | 0  | 1  |
| 9             | 1  | 0  | 0  | 1  |
| 10            | 0  | 1  | 0  | 1  |
| 11            | 1  | 1  | 0  | 1  |
| 12            | 0  | 0  | 1  | 1  |
| 13            | 1  | 0  | 1  | 1  |
| 14            | 0  | 1  | 1  | 1  |
| 15            | 1  | 1  | 1  | 1  |

## The License
This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.   
See https://creativecommons.org/licenses/by-sa/4.0/.
