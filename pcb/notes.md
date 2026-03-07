# PCB Design Notes

This folder contains the PCB design files for the **DC-DC Buck Converter Power Electronics Project**.

The schematic and PCB layout were designed using **Autodesk EAGLE**, and the final board was exported for manufacturing using **Gerber files**.

## Main Components

- IRLZ44Z Power MOSFET
- 1N4004 Freewheeling Diode
- 100 µH Inductor
- 100 µF Output Capacitor
- 10 Ω Load Resistor

## PCB Design Considerations

The following design considerations were applied during the PCB layout:

• Short switching current path between MOSFET, diode and inductor  
• Proper component placement for clean power flow  
• Ground plane implementation for stable return path  
• Adequate trace width for the power stage  
• Clear routing between switching node and output stage

## 3D PCB Visualization

The PCB layout was imported into **Autodesk Fusion** to generate a 3D model of the board.

This visualization allows inspection of:

- component placement
- board structure
- mechanical spacing

It also provides a realistic representation of the final hardware layout of the buck converter.

## Files Included

This folder includes:

- **buck_converter.sch** → EAGLE schematic  
- **buck_converter.brd** → PCB layout  
- **gerber.zip** → manufacturing files  
- **pcb_layout.png** → PCB layout preview  
- **pcb_3d_view.png** → 3D PCB visualization from Autodesk Fusion
