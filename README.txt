********************************************************************************
FlightGear :: Scenery Add-on Chagual:: Sierra de la Libertad
********************************************************************************
Contains:	Aeródromo de Chagual	- SPGL
			Aeródromo de Urpay		- SPAI
			Aeródromo de Gochapita	- SPGC 
			Aeródromo de Pias		- SPIS

Note:	to use the start-up positions in-sim, select your starting position 
		via the [Location -> Select Airport] menu. Type in the name of the 
		parking position, press enter (important!). Then select [Go To Airport].

********************************************************************************
This is a Scenery for testing in FlightGear. Adding this scenery
to the Flightgear/x-plane was done or is planned for the medium term.
********************************************************************************

Author:		josh >fgjosh<
Version: 	FGscenery_Chagual_20151229
Feedback:	contact me on the FG forum -user:josh -forum.flightgear.org
Notes: 		Please make a backup of your important files! Use all files at 
			your own risk. The author of this package is not liable for any 
			problems caused by these files.


Table of contents
-----------------
1. Introduction
2. Features
3. First tips
4. High altitude operation
5. Compatibility
6. Installation instruction
7. Data sources & Programs
8. License
9. Change Log


1.   Introduction
=============================
These airfields are located in Peru, province of Pataz in the department 
of La Libertad.

The Chagual airfield is an private Peruvian airfield owned by Compania Minera 
Poderosa and is located near the town Chagual in the district of Pataz. Chagual 
is the only airfield in the district offering passenger traffic, air cargo and 
operations. The Chagual airfield, 3.980 feet high in the middle of the Andes, 
is a small airstrip  with a length of 1.200 meter encased in a winding valley 
which only allows a very difficult and complicated visual approach. The approach
to the runway 14 is made with a substantial bank angle on final, since due to 
the topography is impossible to make an approach centered on the axis of runway.

The airfield of Pias is situated about 10nm from Chagual. The final approach 
is a little complicated and risky because of the high mountainous terrain of 
the Coordillera and a descend rate of approx 2.000 feet per minute.

Urpay Airfield is situated about 37nm from Chagual Airport. 
The approach is a little tricky because often there are clouds covering the 
airfield in dense mist.

Gochapita Airfield is situated about 37nm from Chagual Airport. The approach 
is a little tricky because often there are clouds covering the airfield 
in dense mist.


2.   Features
=============================
* All airfields of the Province of Pataz included
* Sloped runways at all airfields
* Detailed, phototextured and handcolored 3D models of buildings
* fully Rembrandt compatible
* Challenging take-offs, approaches and cloud flying


3.   First tips
=============================
- often there are clouds at 8.000ft until 13.000ft, for the beginning set the 
  weather conditions to vairy weather or set the cloud layer above 16.000 ft 
- you should notice the winds at different altitudes


4.   High altitude operation
=============================
- choose an aircraft wich allows a service ceiling more than 10.000 ft 
  like the PC-6, B200 or AeroStar700
- reduce the fuel to a minimum
- reduce your load, every 10% under the gross weight, performance increases 20%
- choose flaps for take-off depending on the maximum deflection of the aileron. 
  Not much more.
- pre-lean your engine and give a bit of throttle to get the engine started
- check your indicated airspeed again and again


5.   Compatibility
=============================
This Custom Scenery is fully compatible with dates from Terrasync, if you
make sure the folder 'FGscenery_Chagual' has a higher priority than Terrasync
and/or Root/scenery (see also Installation instruction).
http://wiki.flightgear.org/index.php/TerraSync


6.   Installation instruction
=============================

* Scenery
  uncompress the FGscenery_Chagual.zip and copy the folder 'FGscenery_Chagual' 
  to a location of your choice.

* Airport Data (apt.dat)
  backup your original flightgear/Airports/apt.dat.gz or 
  rename it (e.E apt.dat-original).
  	- uncompress your flightgear/Airports/apt.dat.gz
	- copy and paste the lines from the airports-apt.txt 
      (have a look at the FGscenery_Chagual folder) to the apt.dat
	- compress your new apt.dat to apt.dat.gz
  Data is inserted only; no existing data is overwritten.

* First Run with FGRun
	* Paths: 
		add the folder Terrasync/FGscenery_Chagual to your FG-Scenery 
		directory and make sure the folder 'FGscenery_Chagual' has the 
		highest priority. Priorities among folders are managed with the up 
		and down arrows; the top most folder having the highest priority. 
		If there is no scenery for a location in the top folder, FlightGear 
		will look in the next folder etc. 
	* Airport Selection: 
		click on the [Refresh] button to rescan the airport list, 
		please choose your airport and start-up position             
	* Options and Run
		make sure Terrasync is enabled

* Ready to fly!


7.   Data sources & Programs
=============================
The following data sources have been used and processed to generate this scenery
	*landcover information from Custon Scenery data (mapserver.flightgear.org),
    *Road and rail information from OpenStreetMap,
	*digital elevation data from usgs.gov.
3D-Modeling programs are Sketchup and Blender.
Airport editing with WED.
Image processing program is Gimp.


8.   License
=============================
This work is licensed under the Creative Commons Attribution-NonCommercial-
ShareAlike 4.0 International License. To view a copy of this license, visit 
http://creativecommons.org/licenses/by-nc-sa/4.0/.


9.   Change Log
=============================
FGscenery_Chagual_20151229
- added license
- described the steps of airport adding (README#Installation instruction)
- reformulated the airports-apt.txt
- OBJECT_SHARED Models/Airport/Vehicle/hoskosh-ti-1500.ac instead .xml

FGscenery_Chagual_20151222
- first stage


********************************************************************************

