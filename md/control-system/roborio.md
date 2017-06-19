# roborio

the roborio is the brain of the control system. it's made by National Instruments. it's IO includes: PWM, CAN, RS232, USB, analog input, DIO, ethernet, I2C, SPI, and MXP.

## power input

the roborio takes a 12v input from its designated port on the pdp

## interfaces

### pwm

the roborio has 10 pwm outputs

### dio

the dio (digital input and output)

### rsl

the rsl port powers the robot signal light

### analog in


### ethernet port

the ethernet port connects directly to the radio. it can also be used for directly connecting to a computer when a radio isn't needed

### usb type a ports

the two usb ports can be used for connecting additional parts to the robot such as webcams

### usb type b port

this port can be used for connecting to a computer. it's useful for situations where a radio isn't useable 

### mxp 

the mxp port can be used to connect extension boards such as the [spartan board](http://www.wcproducts.net/WCP-0045) for additional functionality

### can

the roborio can communicate with the pdp, can speed controllers (such as the talon srx), pcm, and other control system components over the can bus

## links

### [roborio manual](tp://www.ni.com/pdf/manuals/374474a.pd)
### [NI support](http://www.ni.com/en-us/support/model.roborio.html)