### General info

EEZ BB3+ T&M chassis with two DCP405B+ power modules installed  
Main CPU/MCU: Raspberry Pi CM5 LITE  
Storage: SSD M.2 NMVe 128 GB  
AC Mains: 115/230Vac 

Consolidated [BOM](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/bom/Mainboard/BOM%20list.eezbom-list) in BOM checker format (BOM checker [installation](https://github.com/eez-open/bom_checker/releases) for Linux and Windows)

EAN code:** TBA**

### Mainboard PCB

Description | Link | Note
--|--|--
KiCad project |   [Link](https://github.com/eez-open/eez-bb3plus/blob/main/KiCad/BB3plus%20mainboard/BB3plus%20mainboard.kicad_pro) | KiCad 10.x
Gerbers | [Link](https://github.com/eez-open/eez-bb3plus/tree/main/fabrication/gerbers/Mainboard) | PCB: FR-4 1.6mm; **4-layer**; White silkscreen, Green solder mask, HASL (leadfree, RoHS compliant)
Position files | [Top](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/pos/Mainboard/BB3plus%20mainboard-top.pos), [Bottom](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/pos/Mainboard/BB3plus%20mainboard-bottom.pos) | Only Top is used
BOM | [ODS](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/bom/Mainboard/BB3plus%20mainboard%20BOM.ods), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/bom/Mainboard/BB3plus%20mainboard%20BOM.pdf) | [BOM checker](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/bom/Mainboard/BB3plus%20mainboard.eezbom) format

### TFT display module PCB

Description | Link | Note
--|--|--
KiCad project | [Link](https://github.com/eez-open/eez-bb3plus/blob/main/KiCad/TFT%20module/BB3plus%20DVID%20TFT%20display.kicad_pro) | KiCad 10.x
Gerbers | [Link](https://github.com/eez-open/eez-bb3plus/tree/main/fabrication/gerbers/TFT%20module) | PCB: FR-4 1.6mm; **2-layer**; White silkscreen, Green solder mask, HASL (leadfree, RoHS compliant)
Position files | [Top](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/pos/TFT%20module/BB3plus%20DVID%20TFT%20display-top.pos), [Bottom](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/pos/TFT%20module/BB3plus%20DVID%20TFT%20display-bottom.pos) | Only Bottom is used
BOM | [ODS](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/bom/TFT%20module/BB3plus%20DVID%20TFT%20display.ods), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/bom/TFT%20module/BB3plus%20DVID%20TFT%20display.pdf) | [BOM checker](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/bom/TFT%20module/BB3plus%20DVID%20TFT%20display.eezbom)  format

### EEZ DIB DCP405B+ PCB (x2)

Description | Link | Note
--|--|--
KiCad project | [Link](https://github.com/eez-open/dib-dcp405plus/blob/main/KiCad/EEZ%20DIB%20DCP405plus.kicad_pro) | KiCad 10.x, select variant **Basic**
Gerbers | [Link](https://github.com/eez-open/dib-dcp405plus/tree/main/fabrication/gerbers/DCP405plus) | PCB: FR-4 1.6mm; **4-layer**; White silkscreen, Green solder mask, ENIG (leadfree, RoHS compliant), Gold fingers with beveling 30°
Position files | [Top](https://github.com/eez-open/dib-dcp405plus/blob/main/fabrication/pos/EEZ%20DIB%20DCP405plus-top%20(Basic).pos), [Bottom](https://github.com/eez-open/dib-dcp405plus/blob/main/fabrication/pos/EEZ%20DIB%20DCP405plus-bottom%20(Basic).pos) | Only Top is used
BOM | [ODS](https://github.com/eez-open/dib-dcp405plus/blob/main/fabrication/bom/EEZ%20DIB%20DCP405plus%20BOM%20(Basic).ods), [PDF](https://github.com/eez-open/dib-dcp405plus/blob/main/fabrication/bom/EEZ%20DIB%20DCP405plus%20BOM%20(Basic).pdf) | [BOM checker](https://github.com/eez-open/dib-dcp405plus/blob/main/fabrication/bom/EEZ%20DIB%20DCP405plus%20(Basic).eezbom) format

### EEZ DIB DCP405B+ front mask PCB (x2)

Description | Link | Note
--|--|--
KiCad project |  [Link](https://github.com/eez-open/dib-dcp405plus/blob/main/KiCad/EEZ%20DIB%20DCP405plus%20front%20mask%20(Basic).kicad_pro) | KiCad 10.x
Gerbers | [Link](https://github.com/eez-open/dib-dcp405plus/tree/main/fabrication/gerbers/DCP405plus%20front%20mask%20(Basic)) | PCB: Aluminum 1.6mm; **1-layer silkscreen on aluminum**; Black silkscreen, White solder mask, (leadfree, RoHS compliant)

### Bare front masks PCB x2

Description | Link | Note
--|--|--
KiCad project |  [Link](https://github.com/eez-open/eez-bb3plus/blob/main/KiCad/Front%20masks/Bare%20front%20mask%20half%20width.kicad_pro) | KiCad 10.x
Gerbers | [Link](https://github.com/eez-open/eez-bb3plus/tree/main/fabrication/gerbers/Bare%20front%20mask%20(half%20width)) | PCB: Aluminum 1.6mm; **1-layer silkscreen on aluminum**; Black silkscreen, White solder mask, (leadfree, RoHS compliant)

### CM5 module

Description | Link | Note
--|--|--
BOM | [ODS](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/bom/Mainboard/CM5%20BOM.ods), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/bom/Mainboard/CM5%20BOM.pdf) | [BOM checker](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/bom/Mainboard/CM5.eezbom) format

### Enclosure

Description | Link | Note
--|--|--
Metal sheet
Bottom plate: [DXF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/dxf/Enclosure/BB3plus%20enclosure%20bottom%20plate%20(with%20dimensions).dxf), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/dxf/Enclosure/BB3plus%20enclosure%20bottom%20plate.pdf) | 1.5mm Aluminum, Powder coating RAL5025 semi-matt
| Top plate: [DXF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/dxf/Enclosure/BB3plus%20enclosure%20top%20plate.dxf), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/dxf/Enclosure/BB3plus%20enclosure%20top%20plate.pdf) | 1.5mm Aluminum, Powder coating RAL5025 semi-matt
| Front panel: [DXF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/dxf/Enclosure/BB3plus%20enclosure%20front%20panel%20(with%20dimensions).dxf), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/dxf/Enclosure/BB3plus%20enclosure%20front%20panel.pdf) | 1.5mm SGCC, Powder coating RAL5025 semi-matt
| Rear panel: [DXF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/dxf/Enclosure/BB3plus%20enclosure%20rear%20panel%20(with%20dimensions).dxf), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/dxf/Enclosure/BB3plus%20enclosure%20rear%20panel.pdf) | 1.5mm Aluminum, Powder coating RAL5025 semi-matt
Silkscreens
| Front panel: [SVG](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/silkscreens/Enclosure/BB3Plus%20Silkscreen%20(Front%20panel).svg), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/silkscreens/Enclosure/BB3Plus%20Silkscreen%20(Front%20panel).pdf)| Print color: White
| Rear panel: [SVG](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/silkscreens/Enclosure/BB3Plus%20Silkscreen%20(Rear%20panel).svg), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/silkscreens/Enclosure/BB3Plus%20Silkscreen%20(Rear%20panel).pdf)| Print color: White
Wire harness
| [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/wire%20harness/EEZ%20BB3plus%20wire%20harness.pdf)
| BOM Chassis: [ODS](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/wire%20harness/EEZ%20BB3plus%20wire%20harness%20BOM.ods), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/wire%20harness/EEZ%20BB3plus%20wire%20harness%20BOM.pdf) | [BOM checker](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/wire%20harness/EEZ%20BB3plus%20wire%20harness.eezbom) format
| BOM DCP405B+: [ODS](https://github.com/eez-open/dib-dcp405plus/blob/main/fabrication/wire%20harness/DCP405plus%20wire%20harness%20BOM.ods), [PDF](https://github.com/eez-open/dib-dcp405plus/blob/main/fabrication/wire%20harness/DCP405plus%20wire%20harness%20BOM.pdf) | [BOM checker](https://github.com/eez-open/dib-dcp405plus/blob/main/fabrication/wire%20harness/DCP405plus%20wire%20harness.eezbom) format, **Multiply by 2**
Assembly instructions | [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/mechanical/BB3plus%20mechanical.pdf)

### Cardboard box

Description | Link | Note
--|--|--
Cardboard box| [KiCad](https://github.com/eez-open/eez-bb3plus/blob/main/KiCad/Cardboard%20box/Cardboard%20box.kicad_pro) project |  KiCad 10.x
| Drawings: [DXF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/dxf/Cardboard%20box/Cardboard%20box%20(with%20dimensions%20and%20bending).dxf), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/dxf/Cardboard%20box/Cardboard%20box.pdf) |  Type: corrugated, double wall, thickness: 6 mm
| Silkscreen: [SVG](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/silkscreens/Cardboard%20box/BB3plus%20cardboard%20box.svg), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/silkscreens/Cardboard%20box/BB3plus%20cardboard%20box.pdf) | Print color: black
Cardboard box insert | [KiCad](https://github.com/eez-open/eez-bb3plus/blob/main/KiCad/Cardboard%20box/Cardboard%20box%20insert.kicad_pro) project| KiCad 10.x
| Drawings: [DXF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/dxf/Cardboard%20box/Cardboard%20box%20insert%20(with%20dimensions%20and%20bending).dxf), [PDF](https://github.com/eez-open/eez-bb3plus/blob/main/fabrication/dxf/Cardboard%20box/Cardboard%20box%20insert.pdf) | Type: corrugated, single wall, thickness: 2.5-3 mm







