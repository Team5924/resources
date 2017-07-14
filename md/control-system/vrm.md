# voltage regulator module

the voltage regulator module (vrm) regulates the power from the pdp to provide constant 12V and 5V outputs

![](https://cdn3.volusion.com/vyfsn.knvgw/v/vspfiles/photos/am-2857-2.jpg?1442240393)

## input

### power input

the vrm is powered through the `12Vin` port by the pdp. input can be 24-16awg

## output

### 12V

the vrm has 12V 2A and 12V 500mA outputs. the 12V 2A must be used for powering the radio

**note:** the 12V 2A port is 2A peak and 1.5A sustained

### 5V

the vrm contains 5V 2A and 5V 500mA outputs. these outputs are not required to be populated (like the 12V 2A output), but can be used for additional components, like a targeting flashlight

**note:** the 5V 2A port is 2A peak and 1.5A sustained

## connecting to the vrm

the vrm uses weidmuller connectors for its input and outputs. see the [weidmuller page](../electrical/weidmuller.md) for more info

## links

### [vrm manual](http://www.ctr-electronics.com/VRM%20User's%20Guide.pdf)
### [vrm cad](http://www.ctr-electronics.com/downloads/cad/VRM_CAD.zip)
### [product page](http://www.ctr-electronics.com/vrm.html)