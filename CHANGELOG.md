Changelog der KiCad HTL-Library
===============================

# Verbesserungen/Updates
* D-Sub Steckverbinder für RS232-Sniffer: ohne SMD-Paste
* Doppel LED (LED_LiteOn_LTST-C195KGJRKT.kicad_mod): Padabstand vergrößert, es gab gehäuft Lötbrücken
* Referenz für USB-C auf F.Silk

# Neue Footprints
* Leiterplattenfuß für Montageloch am Leiterplatteneck d4/R5: htl_mechanical.pretty/mountinghole_d4mm_R5mm.kicad_mod
* Passmarke für SMD-Schablone: htl_mechanical.pretty/paste-fiducial.kicad_mod  
  Dient dem Ausrichten der SMD-Schablone, wenn für alle SMD-Pads des Projektes eine Pastenreduktion angewandt wurde. 
* Sicherungshalter: htl_mechanical.pretty/fuse-clip_20x5mm.kicad_mod
* OLED-Modul, 128x32, I2C: htl_modules.pretty/OLED-128x32.kicad_mod
* Shunt, 7W: htl_smd.pretty/Shunt-15.2x7.6mm.kicad_mod
* SO-8 mit Massefläche für Schaltregler, JBC-Miniregler: htl_smd.pretty/SOIC-8-1EP_3.9x4.9mm_P1.27mm_EP2.514x3.2mm_ThermalVias.kicad_mod
* Virtueller Footprint für Items: htl_virtual.pretty/Virtual-Item.kicad_mod

# Neue Symbole
* D Half Bridge Driver, 2 Inputs, 300V, 3.3V/5V Inputs: htl_ics:PN7006A
* OLED-Module, I2C: htl_modules:OLED-128x32-Module
* htl_semiconductors: 
  * D_Schottky mit Pinnummer!
  * DiodeTVS mit Pinnummer!
  * DiodeTVS_Bidirek!
