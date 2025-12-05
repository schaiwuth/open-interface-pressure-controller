# Open-interface Programmable Pressure Controller

<img src="images/open-interface_programmable_pressure_controller.jpg" width="800"/>

An open-source programmable pressure controller designed for pneumatic actuation in robotics and automation. This device enables computer-controlled air pressure output in real time, through a serial communication protocol. With a built-in manual controller, it also supports stand-alone operation. The controller can be operated from any platform capable of serial communication, making it compatible with a wide range of robotics and automation frameworks. This open-interface design allows the system to be easily adapted and integrated into unique or custom robotic applications.

# Key Specifications

| Parameter            | Specifications                           |
|----------------------|:----------------------------------------:|
| Fluid Type           | Air                                      |
| Set Pressure         | 0–900 kPa                                |
| Power Supply         | 24 VDC, 0.4 A                            |
| Max Frequency        | 10 Hz                                    |
| Programming Protocol | Serial Communication (Baud Rate: 115200) |
| Dimension (WxLxH)    | 185x236.2x150 mm                         |

# Instruction Manual

The instruction manual for the pressure controller is available [here](instruction_manual.pdf).

# List of Main Components

* [Pi Interface](https://github.com/Ninth2234/Pi_Interface) x1
* ET-MINI I2C D/A x1
* SMC ITV2050-31 x1
* SMC VT307-5G x1
* Cytron UC00C x1
* Single-channel Relay 3.3 V x1
* [Chassis](cad_models/chassis.stl) x1
* [Cover](cad_models/cover.stl) x1
* [Interface Panel](cad_models/interface_panel.stl) x1
* Adafruit 4056 x1
* Rocker Switch x1
* DC Jack Female 5.5x2.1 mm x1
* Audio Jack Female 3.5 mm x1
* SMC KQ2E06 x2

# Wiring Diagram

<img src="images/wiring_diagram.jpg" width="800"/>

# Firmware

The firmware for this device is developed in MicroPython, and its repository can be found [here](https://github.com/Ninth2234/Pi_Interface).

# Video Demonstration

* [Manual Pulse-mode Operation on a Soft Pneumatic Actuator](https://www.youtube.com/watch?v=VrCpQ_EVPBg)
