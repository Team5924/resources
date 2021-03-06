# control system overview
 
## standard components
see each component's page for further info

* [battery](battery.md)
* [breaker](main-breaker.md)
* [power distribution panel (pdp)](pdp.md)
* [roborio](roborio.md)
* [voltage regulator module (vrm)](vrm.md)
* [pneumatic control module (pcm)](pcm.md)
* [radio](radio.md)
* [speed controllers](speed-controllers)
* [robot signal light (rsl)](rsl.md)

## overview

![](http://team358.org/files/programming/ControlSystem2015-2019/images/2016_CS_Layout.jpg)

Power distribution starts with the battery. We use 12V batteries. From the battery, power flows to the PDP where the positive termination from the battery to the PDP is broken by the main breaker. This is the on/off switch for the robot as well as a safety mechanism. The PDP then distributes power to the rest of the control system. The PDP has special designated ports on the bottom for the roborio, vrm, and pcm. The other ports are general purpose, with 8 being 40A slots and another 8 being 30A or 20A slots. Usually speed controllers occupy these ports. The drivetrain will generally be on 40A slots because it will generally pull the most current. The radio gets its power from the 12V 2A VRM port. The VRM regulates power from the PDP to provide steady 12V and 5V outputs. The PCM gets power from the PDP and communicates with the control system over the CAN bus. The roborio’s power also comes from the pdp, and it can communicate with the control system over can, serial, i2c, pwm, and other methods. Speed controllers communicate with the roborio over can or pwm. The RSL (robot safety light) is powered and controlled by the roborio rsl port. The roborio and radio communicate via an ethernet cable. The radio can optionally connect to other components such as an IP webcam. The radio then allows for communication with the driver station via a laptop.

## getting started

see [this screensteps live](http://wpilib.screenstepslive.com/s/4485/m/24166/l/144971-wiring-the-2017-frc-control-system) page to get started on setting up the control system

## external resources

### [screenstepslive](https://wpilib.screenstepslive.com/s/4485/m/24166)