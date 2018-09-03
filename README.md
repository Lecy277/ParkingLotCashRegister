# C-Plus-Plus-ParkingLotCashRegister

This program creates a cash register for a series of parking lots based on multi-dimensional arrays. The pricing for the parking lots are based on the proximity to the main gate.  The spots closest to the main gate are most expensive with more spots available and the spots farthest from the gate are least expensive with less spots available.  The program begins with some spots already randomly taken by cars that may have been left in the parking lots overnight or if they are an emergency vehicle. The cash register starts with a certain amount of money and funds are deducted whenever a customer purchases a spot based on the type of bills used and the change given. Both the cashregister.cpp and the GateMenuSelector.cpp have their own .h files which include class objects that are both public and private. The main .cpp file is the parkingControlMain.cpp which is just a file that combines the .h files and runs the .cpp files with the one line in main of myGate.gateMenuSelection().
