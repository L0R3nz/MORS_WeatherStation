# Hardware
## 1. EnvironmentSensors
### Jumper list
|Jumper	|Function																	|
|-------|---------------------------------------------------------------------------|
|JP1	|Set BME680 Address <br>0x76 - Open <br>0x77 - Closed						|
|JP2	|Set LPS22HB Address <br>0x5C - Open <br>0x5D - Closed						|
|JP3	|Bridge EXT_3V3 signal from connector J1 <br>to 3V3 signal of J2 connector	|

### Useful Files
- [iBom File](/../master/Hardware/1.EnvironmentSensors/Kicad/doc/ibom/) - interactive file which help you while soldering 
- [Schematic File](/../master/Hardware/1.EnvironmentSensors/Kicad/doc/schematic/EnvironmentSensors.pdf)
- [Stencil Holder](/../master/Hardware/Tools/StencilHolder/)

Front side of PCB
![PCB_KiCad_EnvironmentSensors_Front]

Back side of PCB
![PCB_KiCad_EnvironmentSensors_Back]

Stencil Holder 
![PCB_KiCad_EnvironmentSensors_StencilHolder]


## 12. LightSensors
### Jumper list
|Jumper	    |Function                                           |
|-----------|---------------------------------------------------|
|ADDR1	    |Set OPT3004 Address according to layout description|
|A0 and A1  |Set AS7331 Address according to layout description |

### Useful Files
- [iBom File](/../master/Hardware/2.LightSensors/Kicad/doc/ibom/) - interactive file which help you while soldering 
- [Schematic File](/../master/Hardware/2.LightSensors/Kicad/doc/schematic/LightSensors.pdf)

Front side of PCB
![PCB_KiCad_LightSensors_Front]

Back side of PCB
![PCB_KiCad_LightSensors_Back]



<!-- Images and diagrams -->
[PCB_KiCad_EnvironmentSensors_Front]: 	        img/Hardware/PCB-Kicad-EnvironmentSensors-Front.png
[PCB_KiCad_EnvironmentSensors_Back]: 	        img/Hardware/PCB-Kicad-EnvironmentSensors-Back.png
[PCB_KiCad_EnvironmentSensors_StencilHolder]: 	img/Tools/PCB-Kicad-EnvironmentSensors-StencilHolder.png
[PCB_KiCad_LightSensors_Front]: 	            img/Hardware/PCB-Kicad-LightSensors-Front.png
[PCB_KiCad_LightSensors_Back]: 	                img/Hardware/PCB-Kicad-LightSensors-Back.png