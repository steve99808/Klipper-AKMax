Continuation of my Marlin project

Built in an <a href="https://biqu.equipment/de/products/manta-m4p-m8p?variant=40215553900642" target="_blank"> BTT M5P Motherboard </a>, the rest is the same as in my previous Marlin build. 
Had to switch back to the Inductive Probe since it made me some struggle with the BL Touch. 
Compared to the E3V3 Board the M5P has two EXP ports, which made it Plug&Play with the display. Same for everything else.

For installing Klipper on the CB1 and Board please refer to the instructions of the <a href="github.com/bigtreetech/CB1" target="_blank"> BIQU Github</a>, same for the wiring diagram . 
I personally used PuTTY as an SSH client for installing. 

Printed a little case with a 120mm Fan for the board, found on printables https://www.printables.com/model/592451-case-bigtreetech-manta-m5p 

My Klipper config has Mesh Bedleveling and Octoeverywhere installed within and a seperate Startcode. Please take that into account so you could change up your start G-Code in your Slicer. 

Pictures of the build will follow soon

Next updates:
-Linear Rails for the X-Axis first, later for Y and Z
-Revo Hotend
-CanBus Connection with ADXL for Input Shaping
-Voron Tap for Leveling
