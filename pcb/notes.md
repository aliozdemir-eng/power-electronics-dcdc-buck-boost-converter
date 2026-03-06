# PCB Design Notes

This folder contains the PCB design files for the DC-DC Buck Converter implemented after completing the simulation stage.

The PCB was designed using Autodesk EAGLE and includes both the schematic and the board layout.

## Main Components

- IRLZ44Z Power MOSFET  
- 1N4004 Freewheeling Diode  
- 100 µH Inductor  
- 100 µF Output Capacitor  
- 10 Ω Load Resistor  

## PCB Design Considerations

The following design considerations were applied during the PCB layout process:

- Short switching current path between MOSFET, diode and inductor
- Proper component placement to minimize noise
- Ground return path optimization using a ground plane
- Adequate trace width for the power path
- Clear separation between switching node and ground connections

## Files Included

This folder contains:

- **buck_converter.sch** → EAGLE schematic file  
- **buck_converter.brd** → EAGLE PCB layout file  
- **gerber.zip** → manufacturing files for PCB fabrication  
- **pcb_layout.png** → PCB layout preview image
