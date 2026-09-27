<div align="center">

  <h1>pan-tilt</h1>

  <p>An alt-azimouth mount for patch antennas up to 500mm x 500mm in size.</p>

<p align="center">
  <img width="3024" height="1324" alt="pan-tilt render" src="https://github.com/user-attachments/assets/213b92fb-164c-414d-bb03-66f999f09bb5" />
</p>

</div>

# Overview

A custom, adjustable alt-azimouth mount that can manipulate a patch antenna of up to 500mm x 500mm in size. The base is built using 4 hollow aluminium rods with an inner diameter or 27mm, and a thickness of 3mm, connected using a PLA connector and M3 bolts to fasten. Powered by either 2 or 3 NEMA 17 steppers (3 if tilt is driven by two steppers), stepped down using GT2 pulleys and timing belts in a 1:4 ratio for more torque. It was intended to track a CanSat during its descent (it can track ascent too given distance between launch site and antenna is great enough). The mount has been constructed, but hasn't been tested under load since we didn't make national finals...


# Assembly 
I do not know why you would assemble this, but in case you do... 

Print out the following files in their specified quantity. I used PLA, but PETG would probably be more ideal.

>[!NOTE]
> The antenna mount was for the antenna we used. You'll have to make your own of course. It will have to mount to a GT2 pulley. I used a clamp joint for the same.

| file                | qty |
| ------------------- | --- |
| pan connector.step  | 1   |
| antenna mount.step  | 2   |
| base mount.step     | 1   |
| tilt connector.step | 2   |

Insert your 4 aluminium rods of OD 30mm and length 300mm into the pan connector. Fasten with 4 M3x6ish bolts into the sides. Attach the two tilt connectors, one on either side, and attach to the rods using 4 M3x6ish bolts for each connector. This is the adjustable part, and can be moved down the length of the rods to accommodate different sized antennas, and balance the mount. 

Now thread a long M3 bolt down the centre of the pan connector, and thread it through the GT2 100 teeth pulley, and then tighten with bolts. Attach the timing belt, and then the smaller GT2 20 tooth pulley. After that, mount one NEMA 17 motor using M3xsomething bolts, and attach the GT2 20 teeth pulley to the shaft and tighten the grub screw. 

Now for the tilt, first press fit 608-2Z deep groove bearings into both connectors. Mount a NEMA 17 motor onto the tilt connector. Attach a GT2 20 tooth pulley to the shaft of the same. Attach the timing belt. Using another long M3 shaft, thread it through the GT2 100 tooth pulley, with your custom antenna mount before it. Use some spacers to go through the bearing, and then tighten on the other side with a bolt. Repeat on the other side if needed (if you don't you'll have to counterbalance it). 

And with that you should be done!


