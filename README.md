# zx spectrum 16k / 48k lower ram module
 a Sram module to replace the 8 lower Dram chips  
 
 
 
this project was based on the work of a similar project by [derekfountain](https://github.com/derekfountain/zx-spectrum-lower-ram.git)  
### THIS LOWER RAM MODULE IS CURRENTLY AT THE TESTING STAGE 
![Alt text](<rev 1/mounted on sockets.jpg>)
revision 1 using through hole capacitors / resistor


![Alt text](<rev 3/mounted on sockets.jpg>)
revision 3 using surface mount capacitor / resistor
and also on a smaller footprint 

the module is intended to be solderd direct to the board

the operation of the board is much the same as from dereks project but i made it 2 layers by shifting the address lines and data lines in order to make for the shortest path this can be seen in the schematic 

![Alt text](<rev 3/schematic.png>)

## bill of materials
revision 1 & 2  
[32k Sram](https://www.mouser.co.uk/ProductDetail/870-62C256AL-25ULIT)  
[flip flop latch](https://www.mouser.co.uk/ProductDetail/595-SN74HCT574NSR)  
[inverter](https://www.mouser.co.uk/ProductDetail/863-MC74HCT04ADG)  

revision 1 only  
1 x 68R axial resistor  
3 x 100 nf disc capacitor  
1 x 100 pf disc capacitor

revision 3 only  
[1 x 68R resistor](https://www.mouser.co.uk/ProductDetail/603-RT1206FRE0768RL)  
[3 x 100nf capacitor](https://www.mouser.co.uk/ProductDetail/581-12065C104KAT4A)  
[1 x 100pf capacitor](https://www.mouser.co.uk/ProductDetail/581-12065A101J)

### rev 1 board layout  
at the top of board is 100pf capacitor with the 68R resistor to the right of it
the other 3 capacitors are 100nf





![Alt text](<rev 1/PCB - top.png>)

![Alt text](<rev 1/PCB - bottom.png>)

### revision 3 board layout 
top left is the 68R resistor, to the right of the resistor is the 100pf capacitor.
the other 3 capacitors are 100nf


![Alt text](<rev 3/PCB - top.png>)
![Alt text](<rev 3/PCB - bottom.png>)

revision 2 was the same as revision 1 but using auto route instead of manualy routing.
i made the boards using easy eda / JLPCB and made the boards 1mm thick

## to do . 
1. check to see if it will fit into the case while on sockets
2. conduct propper testing in various issue motherboards
3. update the board so that the components are labeled 
4. improve the description
   