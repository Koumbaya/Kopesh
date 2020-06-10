#Kopesh

The Kopesh is an "alice-ortho" 40% (well, almost 50%...) Keyboard with (optionals) OLED and undeglow.


![grass](https://github.com/Koumbaya/Kopesh/blob/master/pictures/grass.jpg?raw=true)
![without plate](https://github.com/Koumbaya/Kopesh/blob/master/pictures/20200418_130837~(1).jpg?raw=true)

#Cases

I've tried to give multiples options regarding mounting and plates so here you will find :
- a Sandwish-mount acrylic case, where the PCB is just "hanging" and the whole thing is a stack of acrylic and (optionnaly) metal for the switchplate

![acrylic case](https://github.com/Koumbaya/Kopesh/blob/master/pictures/real1.jpg?raw=true)

![acrylic case](https://github.com/Koumbaya/Kopesh/blob/master/pictures/real2.jpg?raw=true)

- cutouts for a more slim case (just a bottom plate, switchplate) which can be made either of FR4 materials (PCB) or acrylic.

![fr4 case](https://github.com/Koumbaya/Kopesh/blob/master/pictures/kopeshFR4.PNG?raw=true)

- basic fullsize 3D printed "drop in" case. I'm working on some other 3D case.

![3D case](https://github.com/Koumbaya/Kopesh/blob/master/pictures/caseoled.PNG?raw=true)

- fullsize plate-mounted 3 part 3D printed case (this one may have a better feeling due to it being plate-mounted)

![3D case2](https://github.com/Koumbaya/Kopesh/blob/master/pictures/real3d.jpg?raw=true)

![3D case2](https://github.com/Koumbaya/Kopesh/blob/master/pictures/3parts.PNG?raw=true)
You'll need 8 M2x16mm screws for this one.

#Content

(sorry the folders are a bit of a mess)
- root folder contain the KiCad project
-/case/cutouts contain everything to cut the sandwish case. 

	top1,top2 should be cut in 3mm

	bottom should be cut in 3mm but you can probably make it less thick I guess. Go for frosted acrylic if you want to enjoy the underglow.

	middle should be cut in 8mm, or multiplied if cut in 2 ou 3mm.

	switchplate should be 1,5mm so it snaps to the switches

-gerbers folder contain the gerbers .zip you need to order the PCB from a PCB maker
-FR4 Case folder contains both the .zip to order the plates for the slim case out of PCB, or the .dxf to cut them out of acrylic
(there are various solidworks parts in various folders if you need to modify something)

#Making it

I won't bother to explain everything, there are plenty guides onlines, so here is what you need (beside switches obviously) :
- 47 x 1N4148 diodes (or the SMD equivalent, the PCB support both TH and SMD)
- 1 x Pro Micro (or elite C)

Optionnaly :  
- 8 x SK6812 MINI-E LEDs (the '-E' part is important, non-E don't have the same pinout)
- 1 x SSD1206 OLED display
- a tiny reset button

Notes for the acrylic case : due to a f-up on my part, the pro-micro doesn't really fit on top of the PCB, so if you make an acrylic case (disregard that for all other type of case!) you'll have to solder the pro-micro under the PCB, in the same orientation (so USB port touching the PCB if you will : whatever the placement of the pro-micro, it should have the usb port pointing "up" towards the keycaps). One solution would be to make a cut on the metal plate and first top layer of acrylic, PM me if you want that or open an issue.

![withoutcaps](https://github.com/Koumbaya/Kopesh/blob/master/pictures/20200418_124801~(1).jpg?raw=true)

#QA

- Who's the little guy on the PCB : the god of keyboards Christian Clavier

#TODO :

- qmk : leds, better OLED library
- 3D printed case

#THANKS
- the MKBDFR community for the help with Kicad, shoutout to @Druz for the Christian stencil : https://github.com/mkbdfr/fancy-kicad-stuff
- Esca for running a GB for the US !

#LICENSE
All the STL/DXF/SLDPRT/ and Kicad PCB files here are licensed under the Creative Commons - Attribution - Non-Commercial - Share Alike license.

![CC](https://github.com/Koumbaya/Kopesh/blob/master/pictures/creativecommons.png?raw=true)

I need to make a proposer link to the correcte repositories for the Kicad Footprints.
