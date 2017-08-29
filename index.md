Making gcodes for cnc machine

STEP 1: Go to fabmodules.org

STEP 2: Click on image (.png) and select your schematic file

STEP 3: Click on Output format and select ShopBot (.sbp)

STEP 4: Click on Process and select Foam rough cut

STEP 5: Select mm in File Units and input the required data values

STEP 6: Click on Calculate and save the file

Break

Milling using ShopBot

STEP 1: Select the ‘Program Run’ tab in Mach3

STEP 2: Plug your USB Drive into the Mach3 PC and use ‘File->Load GCode’ within Mach3 to load your file.

STEP 3: Use the arrow keys to jog the spindle to what will be the lower right corner of your etching. Leave some extra room to avoid disasters.

STEP 4: Click ‘Zero X’, ‘Zero Y’ and ‘Zero Z’ on the Mach3 Screen

STEP 5: Click ‘Cycle Start’ on the Mach3 Screen

STEP 6: When prompted, jog the spindle down to within 5mm of the board and click ‘Cycle Start’ again.

STEP 7: The CNC will begin probing the work piece. If at any point Guido seems to be plunging the bit into the copper, hit the red E-Stop button and check your connections.

STEP 8: If you need to fix a connection and restart the process, be sure to use the ‘Rewind’ button in Mach3 before clicking ‘Cycle Start’ again.
