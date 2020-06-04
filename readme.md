##### This folder containts robodk simulations

##### Simulation details:
	Boxes running on 2 conveyors, each box gets scanned by one of 2 scanners. 
	A robot grabs each box and places on a pallet 	
	There are 2 pallets that will look the same each containing ~100 boxes


Each box data is read from a file called: Pattern.txt
Row format: 
#### <box_type> <box_orientation> <pos_x> <pos_y> <pos_y> <dist> <level>
	
##### box_type 1 or 2 - the box type
##### box_orientation - 0 or 90 degrees
##### pos_x, pos_y, pos_z - position relative to the upper left corner of the pallet
##### dist - dist to the upper left corner of the pallet
##### level- the level of height the box will be placed at


## Steps to start the program:
	From the program run: MainSimulation
