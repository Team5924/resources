# radio

the radio is used to communicate with the driver station. the current radio is the openmesh OM5P-AC

## power input

the radio takes a 12V power input from the 12V 2A port on the vrm

## ethernet ports

the radio has two ethernet ports. a switch can be used to get more ports, but the roborio must be directly connected to the radio

## using in an frc robot

the radio must be programmed and flashed with the radio programming utility before use

see instructions [here](https://wpilib.screenstepslive.com/s/4485/m/13503/l/144986-programming-your-radio-for-home-use) 

network names should be unique so that robots running simultaneously do not interfere with each other. for example, if we want to run our 2016 and 2017 robots at the same time for a demo, their network names should be something like `5924_2016` and `5924_2017`, not `5924` for both.

### at competions

radios must be programmed to work with the fms at each competition. after this is done, the radio does not broadcast a wireless network that you can connect to, so directly connect to the roborio or radio via usb or ethernet.

after competitions, the radio can be reprogrammed for home use using the same steps and tools as before

## links

### [OM5P-AC product page](http://www.open-mesh.com/products/access-points/grp-om5p-ac-cloud-access-point.html)