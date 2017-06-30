# talon srx

the talon srx is a speed controlled designed by vex and ctre. it's the smartest frc speed controller.

despite the advanced functionality, the talon comes in a compact package

## can

the can bus enables the smart features of the srx. 

see the can bus page for recommended topology

## smart functionality

### onboard pid

the talon can run an onbord `pidf` (proportional, integral, derivative, & feedforward) control loop. this loop generally runs faster than what you would run on the roborio and relieves some load off the roborio

### motion profiling

motion profiling allows for more control over a mechanism than pid

ctre has made motion profiling easier with the motion magic control mode

see the [motion profile reference manual](https://www.ctr-electronics.com/downloads/pdf/Talon%20SRX%20Motion%20Profile%20Reference%20Manual.pdf) for more info

## pwm

most of the srx functionality is designed around its can bus functionality, but the basic srx features can be used through pwm

## links

### [user's guide](http://www.ctr-electronics.com/Talon%20SRX%20User's%20Guide.pdf)
### [product page](http://www.ctr-electronics.com/talon-srx.html)
### [motor controller output testing](http://www.ctr-electronics.com/downloads/pdf/Motor-Controller-Power-Testing.pdf)
### [software reference manual](http://www.ctr-electronics.com/downloads/pdf/Talon%20SRX%20Software%20Reference%20Manual.pdf)
### [cad model](http://www.ctr-electronics.com//downloads/cad/217-8080-STEP-20140814.zip)