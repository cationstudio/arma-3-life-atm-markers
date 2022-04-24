# arma-3-life-atm-markers

This is a script that marks all atm on the map for ArmA 3 RPG Life.

![ATMs on Altis](https://i.imgur.com/Ypcl64Q.jpeg)

## Installation

A working installation of ArmA Life RPG Framework is required for a successful installation. Modifying the ArmA Life RPG Framework could cause errors – feel free to connect to our discord if you have a problem.

### Step 1

Download the newest release and extract the archive. Copy the attached folder “atm” in your “cation” folder that can be found in the  root folder (subsequently called \<mission\>) of your mission.

### Step 2

Open \<mission\>/cation/cation_functions.cpp and insert

`#include "atm\functions.cpp"`

and save the file.

### Step 3

Open \<mission\>/cation/cation_master.cpp and insert

`#include "atm\config.cpp"`

and save the file.

### Step 4

Open \<mission\>/cation/cation_remoteExec.cpp and insert

`#include "atm\remoteExec.cpp"`

and save the file.

**That's it!**

You have installed the cationstudio crafting system successfully!

## Configuration

If you wish to mark also your self placed ATMs on the map, enable it in
\<mission\>/cation/config.cpp