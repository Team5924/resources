# pneumatic control module

the pneumatic control module (pcm) is the bridge between the control system and the pneumatic system

![](https://www.vexrobotics.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/2/1/217-4243.jpg)

## input

### input power

the pcm gets power from the pdp

### pressure switch

the pressure switch plugs into the pcm and tells the pcm when to cut power to the compressor

## outputs

### compressor

the pcm has a relay to control the air compressor. this allows the compressor to be cut from power using the roborio

the `comp` led on the pcm displays the status of the compressor

### solenoid

the cm has 8 solenoid outputs labeled from 0-7. these allow for control 

#### 12/24V jumper

use the 12/24V VSOL jumper to select the voltage that the solenoids use
 
## can

the pcm uses can to communicate with the control system. the roborio tells the pcm whether to power the pcm or not and which solenoids 

## links

### [pcm manual](http://www.ctr-electronics.com/PCM%20User's%20Guide.pdf)
### [pcm cad](http://www.ctr-electronics.com/downloads/cad/PCM_CAD.zip)
### [product page](http://www.ctr-electronics.com/control-system/pcm.html)