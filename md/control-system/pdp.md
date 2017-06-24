# power distribution panel

the power distribution panel is the heart of the control system. it distributes the power from the battery to the rest of the robot

![](https://cdn3.volusion.com/vyfsn.knvgw/v/vspfiles/photos/am-2856-2.jpg?1442240393)

## input

the pdp gets a positive connection from the main breaker and a ground straight from the battery connector

pdp input wires should be kept as short as possible in order to prevent bottlenecking the power of the robot. minimum wire gauge is 6awg

## output

the pdp has 16 open slots and 3 ports dedicated to the roborio, pcm, and vrm.

### 8 40A slots

these slots must use 40A breakers. only slots that are used need breakers.

### 8 30A/20A slots

these slots can use 30A or 20A breakers. only slots that are used need breakers.

### 3 bottom ports

the three bottom ports are protected by a 10A and 20A fuses. the roborio, vrm, and pcm occupy these ports. 

## interfaces

### can

the pdp talks to the rest of the control system over the can bus. the pdp also has a terminating resistor that is essential for the can bus. the pdp terminating resistor can be switched on or off with the jumper near the can weidmuller ports.

## links

### [pdp manual](http://www.ctr-electronics.com/PDP%20User's%20Guide.pdf)
### [pdp cad](http://www.ctr-electronics.com/downloads/cad/PDP_CAD.zip)
### [product page](http://www.ctr-electronics.com/pdp.html)