---
title: Root 3 Bill of Materials
description: Root 3 Bill of Materials
published: true
date: 2022-06-28T21:37:30.411Z
tags: root 3, r3, BOM
editor: markdown
dateCreated: 2022-05-24T19:30:47.756Z
---


<img align="right" width=175 src="https://raw.githubusercontent.com/RootCNC/Root-3-CNC/master/Media/Root%203%20CNC.png" />

# Root 3 CNC Bill of materials
The Root 3 CNC is configurable in many ways, here are a few configurations you'll need to consider before building one.

Please note an Excel document can be downloaded for more information - [Link](https://github.com/RootCNC/Root-3-CNC/blob/master/BOM/R3%20BOM.xlsx)
#### Belt Options:
 - 2mm GT2 Belts
 - 3mm HTD Belts (Advised option)
#### Box section Options
 - 25x25mm Box section (Metric) 
 - 1"x1" Box section (Imperial)
#### Motor Section
Root 3 CNC can accommodate either NEMA 17 or NEMA 23 Motors. If budget allows, I would recommend the NEMA 23 motor defined in the list below
### Spindle Options
Root 3 supports a number of Spindle sizes:
 - 52mm
 - 65mm
 - 80mm
#### Coach bolts
Coach bolts are optional for the 3D printed carriage if you want a low profile mounting. if you choose to use coach bolts to mount the two carriages together, then you'll need half coach and half standard (this information in the Excel Bill of Materials)
# 3D Printed Parts required
Please note the Root 3 CNC machine can be configured for **different belt sizes** and **different box section sizes**. 
| 3D Printed Parts                 | Required | QTY    | Alternative |
|----------------------------------|----------|--------|-------------|
| Box Section Linear (\*1) | YES       | 8       ||
| Y Axis Bar Mount (\*2) (\*3) Mirror | YES       | 2      ||
| Y Axis Bar Mount (\*2) (\*3) STD | YES       | 2      ||
| X Axis Belt Clamp (\*3) Belt Plate | YES       | 2      ||
| X Axis Belt Clamp (\*3) | YES       | 2      ||
| Motor Mount (\*4)| YES      | 2      ||
| 50mm Spacer (\*4)| YES      | 2      ||
| X Carriage Belt Idler | YES      | 1      ||
| Y Axis Dust Cover Spacer | NO      | 4      ||
| Y Gantry Bearing Cap | YES      | 1      |
| Y Gantry Bearing Cap (Cable mount) | YES      | 1      ||
| Y Gantry Bearing Space | YES      | 2      ||
| Y Gantry Box Mount Foot | YES      | 4   |
| Y Gantry Box Section Belt Clamp | YES      | 4     ||
| Y Gantry Motion Link | YES      | 2      ||
| Z Axis Bearing Cup Bottom | YES      | 1    ||
| Z Axis Bearing Cup Top | YES      | 1   |Z Axis Bearing Cup Top - Limit Tab Removed<br />Allows clearance for router (Makita in my case) by removing the upper Z limit switch tab |
| MGN 12 Spindle mount (\*5) (Text) | YES      | 1      ||
| MGN 12 Spindle mount (\*5)  | YES      | 1      ||
| X Axis Drag Chain mount X carriage | YES      | 1      ||
| X Axis Drag Chain Mount Y Side panel | YES      | 1      ||
| Y Axis Drag Chain mount to  X carriage | YES      | 1      ||
| Drag Chain Y Carriage Mount | YES      | 1      ||

(\*1) Optional Configuration: for standard M8 Bolts print x8 Guild STD and for Coach bolt print x8 Guild STD and 4x COACH BOLT
(\*2) Select box section size
(\*3) Select Belt type 
(\*4) Select Motr size 
(\*5) Select Spindle size 

# Panels
| Item               | QTY    | Link|
|----------------------------------|--------|-----|
| Side_Panel|2|[Root CNC Store](https://rootcnc.com/product/root-3-side-panel/)|
| Z_Axis_WoodPanel_Front|1|[Root CNC Store](https://rootcnc.com/product/root-3-front-rear-x-carriage-z-plate/)|
| Z_Axis_WoodPanel_Rear|1|[Root CNC Store](https://rootcnc.com/product/root-3-front-rear-x-carriage-z-plate/)|

Wooden Panel kits can be found [HERE](https://rootcnc.com/product/root-3-cnc-starter-pack/) 

# Electronics/ Electro Mechanical
| Item               | Required | QTY    | Link|
|----------------------------------|----------|--------|-----|
| 23HS41-1804S NEMA 23 1.8deg 2.4Nm (340oz.in) 1.8A               | YES       | 4      | [LINK](https://www.omc-stepperonline.com/nema-23-bipolar-1-8deg-2-4nm-340oz-in-1-8a-4-95v-57x57x104mm-4-wires.html/?tracking=5efc6f6300e83)|
| NEMA 17 Bipolar 1.8deg 65Ncm (92oz.in) 2.1A |NO |4| [LINK](https://www.omc-stepperonline.com/nema-17-bipolar-1-8deg-65ncm-92oz-in-2-1a-3-36v-42x42x60mm-4-wires-it.html/?tracking=5efc6f6300e83)|
| 1.5KW Spindle with VFD|YES|1|[LINK_1](https://s.click.aliexpress.com/e/_dX0JKm3) [LINK_2](https://s.click.aliexpress.com/e/_dT4xs63) [LINK_3](https://s.click.aliexpress.com/e/_dSjt6gr) [LINK_4](https://s.click.aliexpress.com/e/_dSUhh43)
| 400W Quiet Spindle (not recommended)|NO |||
| Micro Switch SPDT micro switch V4 KW11i|YES|6|[LINK UK](https://amzn.to/31Kf1wC) [LINK](https://s.click.aliexpress.com/e/_ATnQCz)| 
| 12V or 24V PSU (For Controller power + any lights) |YES|1|[12V_LINK_UK](https://amzn.to/2HxYvIS) [12V_lINK](https://s.click.aliexpress.com/e/_AACYyd)| 
| Aviation plug (GX12) |NO|x|[LINK_UK](https://amzn.to/31LBPfl) [LINK](https://s.click.aliexpress.com/e/_AtqbWz)|
| Stepper Motor Drivers (E.G DRV8825)| YES | 4||
| Cooling Fan - 60mm DC Fan | YES | 1 ||
| 4 Core AWG24/26 Cable | YES |||
| Arduino Mega With RAMP kit ||||
| Root CNC GRBL controller comming soon ||||

# Motion
| Item               | Required | QTY    | Link|
|----------------------------------|----------|--------|-----|
|608 Bearings               | Yes       | 56      |[LINK_UK](https://amzn.to/3dWB9c6) [LINK](https://s.click.aliexpress.com/e/_ATuujF)|
|MGN12 200mm + (MGN12C x2)              | Yes       | 2      |[LINK]()|
|R38 18mm x 37mm Black Drag Chain 1M              | Yes       | CNC Size dependant      |[LINK_UK](https://amzn.to/37J6PAH)  [LINK](https://s.click.aliexpress.com/e/_9hJS33)|
|3M HTD Belt             | Yes       | CNC Size dependant (2x Y Axis Length + 1x X Axis Length = min belt length)      |[LINK_UK]()  [LINK]()|
|HTD 3M Round Tooth Timing Belt Pulley 8mm Bore 24T*| Yes       | 5/7      |[LINK]()|
|HTD 3M Round Tooth Timing Belt Pulley 8mm Bor 20T*| Yes       | 2      |[LINK]() |
|HTD 3M Round Tooth Timing Belt 9mm Wide 345-3M-9| Yes       | 1      |[LINK_UK]() [LINK]()

(\*) Dependant on stepper motor selection - This configuration will work for the above stepper motor from OMC Stepper Motor Online

# Hardware
Below is guide on the QTY required/ the pack sizes I brought to assemble the Root 3 CNC
| Item               | Required | QTY    | Link|
|----------------------------------|----------|--------|-----|
|Box section 25x25xX/Yx3mm (W,D,L,T)(\*)|YES|4||
|M3 Penny Washers (Large)|YES|100|YES||
|M3 Machine Screws (16,20,25,30,40 mm)|YES|100|YES||
|M3 Nuts|YES|100|YES||
|M3 Rivit Nuts|YES|16|YES||
|M4 Penny Washers (Large)|YES|30|YES||
|M4 x40mm Bolt|YES|20|YES||
|M4 x 35mm Countersunk Screw|YES|32|YES||
|M4 Nuts|YES|50|YES||
|M5 x70mm Bolt with Washer head|YES|8|YES||
|M5 Washers|YES|8|YES||
|M5 Nuts|YES|8|YES||
|M8 Axis Connecting Bar|YES|1|YES||
|M8 Lead screw / Threaded Rod|YES|1|YES||
|M8 x25mm Herx Head Bolt|YES|32|YES||
|M8 x75mm Bolt|YES|20|YES||
|M8 x75mm Coach Bolt|NO|20|NO||
|M8 Washers|YES|100|YES||
|M8 Nuts|YES|100|YES||
|M8 Collar|YES|4|YES||
|M8 Tee Nuts|NO||NO||

(\*) Length of the box section is dependant on size of the machine you are building - use this link for more information [LINK](https://rootcnc.com/machines/root-3/root-3-dimensions/)

# MISC Items
| Item               | Required | QTY    | Link|
|----------------------------------|----------|--------|-----|
|Mist Coolant Lubrication Spray System Unit (Used for Airline to Spindle - Aluminium machining)| No |1 | |



