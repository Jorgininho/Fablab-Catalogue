# Manufacturing File

### This file shall store all the information realted to the manufacturing of the product. The manufacturing might be related to a freezed version of the conception of the product.

## Raw material used for the mnufaturing
Reference | Type (tag) | Description
----------|------------|------------
*A* | *Wood plate*| *raw wood plate dimension : l :300mm L:200mm : e: 12mm*


## Steps for manufacturing of the product ?
> Describes the different steps needed to go from a parent conception file to the actual manufacturing of the product

Steps # | Type of operation (Tag) |  Description 
--------|-------------------------|-------------
1 | *Gcode configuration* | *configure fusion to allows generation of Gcode *
2 | *Gcode convertion* | *convert 3D model to Gcode via the software Fusion *
3 | *CNC setup* | *Install the material **A** on the CNC*
4 | *CNC Machining* | *Launch the machining for part1*



## What are the technics used to manufacture the product ? 
> Describes breifly how a user can manufacture the product, 


 Manufacturing files	| Description	| System	| Software	| Conception parent file	| Material
 ---------------------|-------------|---------|-----------|-------------------------|---------
*Ex : Part1.gcode*	|*Gcode of the part 1 to be manufactured*	|*CNC Openfab	*|*Linux CNC	*|*part1.fusion*|	*Wood*

