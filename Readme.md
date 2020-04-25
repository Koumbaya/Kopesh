#Kopesh

The Kopesh is an "alice-ortho" 40% (well, almost 50%...) Keyboard with (optionals) OLED and undeglow.

![without plate](https://github.com/Koumbaya/Kopesh/blob/master/pictures/20200418_130837~(1).jpg?raw=true)

#Cases

I've tried to give multiples options regarding mounting and plates so here you will find :
- a Sandwish-mount acrylic case, where the PCB is just "hanging" and the whole thing is a stack of acrylic and (optionnaly) metal for the switchplate

![acrylic case](https://github.com/Koumbaya/Kopesh/blob/master/pictures/kopesh.png?raw=true)

![acrylic case](https://github.com/Koumbaya/Kopesh/blob/master/pictures/kopeshcaps.PNG?raw=true)

- cutouts for a more slim case (just a bottom plate, switchplate) which can be made either of FR4 materials (PCB) or acrylic.

![fr4 case](https://github.com/Koumbaya/Kopesh/blob/master/pictures/kopeshFR4.PNG?raw=true)

-TODO : a 3D printed case. It will probably be made of multiple section since the keyboard is too big for a 20cm*20cm printer.

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


![withoutcaps](https://github.com/Koumbaya/Kopesh/blob/master/pictures/20200418_124801~(1).jpg?raw=true)

#QA

- Who's the little guy on the PCB : the god of keyboards Christian Clavier

#TODO :

- qmk : oled and leds
- 3D printed case
