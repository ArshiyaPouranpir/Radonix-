![](RackMultipart20230318-1-aqtmlv_html_e13a469812367bdb.png)

![Shape4](RackMultipart20230318-1-aqtmlv_html_acee37b18bf97ef6.gif) ![Shape2](RackMultipart20230318-1-aqtmlv_html_a7615d7dad3c953f.gif) ![Shape1](RackMultipart20230318-1-aqtmlv_html_9754a0d3a3e219ad.gif) ![Shape3](RackMultipart20230318-1-aqtmlv_html_f80752e6d43adf67.gif)

**For router CNC machines**

**برای**  **cnc**  **های روتر**

**Radonix CNC Controller**

Prepared and written by: Sara Yarmohammadi, Shayan Turk


![](RackMultipart20230318-1-aqtmlv_html_f7dabb9f547c0a97.png)

**Headquarters**

**Iran**

**Radnik Automation Company**

Unit 2, Tatis Building, No. 4, Suhend Alley, Laleh Square, 7th East Boustan, Laleh Boulevard, Marzdaran Boulevard, Tehran

Telephone: +98-21-46112012-4 | Postal Code: 1461844843 | SMS gateway number: +98-9351983070

**TÜRKİYE**

**RADONİX OTOMASYON SİSTEMLERİ VE TİC. LTD. ŞTİ**

Halil Rıfat Paşa Mah.، Yüzer Havuz Sok.، Perpa Ticaret Merkezi، B Blok، No. 1668 Okmeydanı / İSTANBU

Telefon: +90-212-2229522| Fax: +90-212-22295

![Shape5](RackMultipart20230318-1-aqtmlv_html_1fd61728a5d60b5d.gif)
Introduction

| ![](RackMultipart20230318-1-aqtmlv_html_e2de3eb796f9372f.png)WARNING |
- Please read this book before using the product to ensure proper use of the controller and its related software.
 |
| --- | --- |

This book provides information on how to install and operate Radonics PC-Pro LAN and PC-Smart controllers for router machines. Having basic knowledge of industrial electricity is essential to make use of this information. Information about the drive motors used in the machine and their wiring is also required as supplementary information for the necessary electrical panel setup.

By installing the interface, default settings are installed that can be used as a wiring template by accessing the program's settings. Inputs, outputs, and axes are present in these settings. However, based on the conditions, different wiring templates can be applied, and by changing the program's settings, the hardware can be synchronized with the software.

Radonics offers several interfaces for router machine startup, with the XYZ-Router interface for simple 3-axis routers and the XYZA-Router interface for 4-axis rotary routers being the most commonly used examples. By installing them on the computer, pre-configured settings for inputs and outputs are installed.

|  | Who can benefit from using this book? |
| --- | --- |

This book is intended for the following users

- People responsible for installing or wiring Radonix controllers.
- People responsible for setting up Radonix controllers.
- People responsible for setting up Radonix controller software.
- People responsible for troubleshooting and maintaining CNC machines with Radonix controllers.
- People who intend to present a project based on CNC machines.

| ![](RackMultipart20230318-1-aqtmlv_html_a41bc5dbab983e34.png) |
- Indicates a hazardous situation that, if not avoided, will result in serious injury or death.
 |
| --- | --- |
| ![](RackMultipart20230318-1-aqtmlv_html_e2de3eb796f9372f.png)WARNING |
- Indicates a hazardous situation that, if not avoided, could result in minor or serious injury to the controller.
 |
| ![](RackMultipart20230318-1-aqtmlv_html_fabb4823930525de.png)STOP |
- Indicates an operation that is not recommended and may cause a disruption in the controller's performance.
 |

**Wiring**

| ![](RackMultipart20230318-1-aqtmlv_html_a41bc5dbab983e34.png)
 |
- Do not connect the controller power supply to the city power or 220V, incorrect connection can cause serious damage to the controller.
 |
| --- | --- |

| ![](RackMultipart20230318-1-aqtmlv_html_e2de3eb796f9372f.png)WARNING |
- To prevent noise, use shielded cable and foil for connecting to the encoders of the drives.
- Before connecting the controller to the power supply, check the wiring again and make sure the connections are correct.
 |
| --- | --- |

| ![](RackMultipart20230318-1-aqtmlv_html_fabb4823930525de.png)STOP |
- Make sure to correctly ground the electrical panel and computer case, otherwise the generated noise can cause incorrect operation of the computer and software.
- Pay attention to the wire size during wiring, otherwise the resistance created in the wire can cause incorrect data transmission.
 |
| --- | --- |

**Software**

| ![](RackMultipart20230318-1-aqtmlv_html_a41bc5dbab983e34.png)
 |
- Before using the controller and software, set the software parameters correctly, otherwise it may cause serious damage to the mechanical system.
 |
| --- | --- |

**Maintenance and Repair**

| ![](RackMultipart20230318-1-aqtmlv_html_fabb4823930525de.png)STOP |
- Please do not touch the controller while using it as it may cause an electric shock.
- Only people with electronics knowledge should be responsible for maintenance and repair.
 |
| --- | --- |

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png) | To facilitate easier understanding of the text, some commonly used terms that may need explanation are briefly described below: |
| --- | --- |
|



Interface: The main interface of the Radonix Cam-Pro program with the user, which is actually what the user sees on the computer and communicates with the controller through.

Variable: All numerical and string data available to the user to create changes in the user interface display, motion, and response are called variables.

Function: Programs that allow the controller and/or the user to execute specific commands and instructions, and enable communication between the controller and the user.

Parameter: Refers to internal variables of the controller and/or interface that allow the user to create changes in the program execution process and/or changes in the motion of the system.

Key: Can include both hardware and software keys, which can be defined based on the type of application. |

# فصل 1 چک کردن بسته بندی و توضیح انواع مدل­ها

## 1-1Check Pachage

Please check the following items after receiving the package:

Make sure that the product is the same as what you have ordered, and the serial number on the controller matches.

Make sure that the controller is not damaged and the controller board is not broken or any piece is damaged or detached.

If you notice any damage, please inform the sales representative or Radonix company before starting up the controller.

A complete and executable controller package should include the following:

**Radonix PC-Pro LAN 2A**

Controller

DB15 male connector (2 pieces)

DB15 connector cover (2 pieces)

Phoenix 3-pin terminal (1 piece)

Phoenix 6-pin terminal (1 piece)

Phoenix 8-pin terminal (3 pieces)

Phoenix 9-pin terminal (1 piece)

Radonix software CD

**Radonix PC-Pro LAN 4A**

Controller

DB15 male connector (4 pieces)

DB15 connector cover (4 pieces)

Phoenix 3-pin terminal (1 piece)

Phoenix 6-pin terminal (1 piece)

Phoenix 8-pin terminal (5 pieces)

Phoenix 9-pin terminal (1 piece)

Radonix software CD

 

**Radonix PC-Pro LAN 6A**

Controller

DB15 male connector (6 pieces)

DB15 connector cover (6 pieces)

Phoenix 3-pin terminal (1 piece)

Phoenix 6-pin terminal (1 piece)

Phoenix 8-pin terminal (8 pieces)

Phoenix 9-pin terminal (1 piece)

Radonix software CD

**Radonix PC-Pro LAN 3AS**

Controller

Phoenix 3-pin terminal (1 piece)

Phoenix 4-pin terminal (4 pieces)

Phoenix 6-pin terminal (1 piece)

Phoenix 8-pin terminal (1 piece)

Radonix software CD

**Radonix PC-Smart 4A**

Controller

DB15 male connector (4 pieces)

DB15 connector cover (4 pieces)

Phoenix 3-pin terminal (2 pieces)

Phoenix 4-pin terminal (2 pieces)

Phoenix 5-pin terminal (4 pieces)

Phoenix 6-pin terminal (1 piece)

Radonix software CD

**Radonix PC-Smart 3AS**

Controller

Phoenix 3-pin terminal (2 pieces)

Phoenix 4-pin terminal (4 pieces)

Phoenix 5-pin terminal (3 pieces)

Radonix software CD

## 1-2Controller Models Features

![](RackMultipart20230318-1-aqtmlv_html_a614e1c3cf607ad3.png)

### 1-2-1Radonix PC-Pro LAN 2A

**Flexible High Performance Position Control**

| 2 independent and synchronous axes | Axes |
| --- | --- |
| 16 Isolated NPN inputs | Digital Inputs |
| 8 (Negative protected outputs) | Digital Outputs |
| 2 (Protected outputs) | Analog Outputs |
| 2 PWM outputs with adjustable frequency | PWM Outputs |
| 500,000 pulses per second | Axis Pulse Rate |
| Directional pulse | Axis Pulse Type |
| From 50 mm/s² to 30,000 mm/s² | Acceleration Time |
| S-Curve | Speed Profile |
| 2,000 block FIFO | Hardware Buffer Size |
| 20 milliseconds | PC-Controller Data exchange time |
| Optocoupler | Isolation Type |
| LAN with 100 Mbps transfer rate (TCP/IP) | Communication Type |
| More than 20 meters with UTP/More than 50 meters with SFUTP | Communication Length |
| 24 time locks with internal clock | Hardware Lock |
| 16 to 32 volts - 300 milliamperes | Power Consumption |
| 19\*13 centimeters | Dimensions |
| Loop-open control | Controller Type |
| Windows 7, 8, 10, 11 | Operating System |
| Joystick, Remote control, Handwheel | Supported Equipment |
| 2
 | Active Axis Count |

### ![](RackMultipart20230318-1-aqtmlv_html_d5d4b14318e0d986.png)

###

###

### 1-2-2 **Radonix PC-Pro LAN 4A**

**Flexible High Performance Position Control**

| 4 independent and synchronous axes | Axes |
| --- | --- |
| 24 Isolated NPN inputs | Digital Inputs |
| 16 open collector outputs with short circuit protection circuit. | Digital Outputs |
| 2 | Analog Outputs |
| 2 PWM outputs with adjustable frequency | PWM Outputs |
| 500,000 pulses per second | Axis Pulse Rate |
| Directional pulse | Axis Pulse Type |
| From 50 mm/s² to 30,000 mm/s² | Acceleration Time |
| S-Curve | Speed Profile |
| 2,000 block FIFO | Hardware Buffer Size |
| 20 milliseconds | PC-Controller Data exchange time |
| Optocoupler | Isolation Type |
| LAN with 100 Mbps transfer rate (TCP/IP) | Communication Type |
| More than 20 meters with UTP/More than 50 meters with SFUTP | Communication Length |
| 24 time locks with internal clock | Hardware Lock |
| 16 to 32 volts - 300 milliamperes | Power Consumption |
| 25\*13 centimeters | Dimensions |
| Loop-open control | Controller Type |
| Windows 7, 8, 10, 11 | Operating System |
| Joystick, Remote control, Handwheel | Supported Equipment |
| 2، 3، 4 | Active Axis Count |

![](RackMultipart20230318-1-aqtmlv_html_eb81edc57b8e5347.png)

### 1-2-3 **Radonix PC-Pro LAN 6A**

**Flexible High Performance Position Control**

| 6 independent and synchronous axes | Axes |
| --- | --- |
| 32 PNP and NPN inputs | Digital Inputs |
| 32(Negative protected outputs) | Digital Outputs |
| 2 | Analog Outputs |
| 2 PWM outputs with adjustable frequency | PWM Outputs |
| 500,000 pulses per second | Axis Pulse Rate |
| Directional pulse | Axis Pulse Type |
| From 50 mm/s² to 30,000 mm/s² | Acceleration Time |
| S-Curve | Speed Profile |
| 2,000 block FIFO | Hardware Buffer Size |
| 20 milliseconds | PC-Controller Data exchange time |
| Optocoupler | Isolation Type |
| LAN with 100 Mbps transfer rate (TCP/IP) | Communication Type |
| More than 20 meters with UTP/More than 50 meters with SFUTP | Communication Length |
| 24 time locks with internal clock | Hardware Lock |
| 16 to 32 volts - 300 milliamperes | Power Consumption |
| 34\*13 centimeters | Dimensions |
| Loop-open control | Controller Type |
| Windows 7, 8, 10, 11 | Operating System |
| Joystick, Remote control, Handwheel | Supported Equipment |
| 6, 5, 4, 3, 2 | Active Axis Count |

### ![](RackMultipart20230318-1-aqtmlv_html_7afd4b6a9a2180e8.png)

###

### 1-2-4 **Radonix PC-Pro LAN 3AS**

**Smart Position Control - Suitable for steppers**

| 3 independent and synchronous axes | Axes |
| --- | --- |
| 8 Isolated NPN inputs | Digital Inputs |
| 4(Negative protected outputs) | Digital Outputs |
| 2 | Analog Outputs |
| 2 PWM outputs with adjustable frequency | PWM Outputs |
| 500,000 pulses per second | Axis Pulse Rate |
| Directional pulse | Axis Pulse Type |
| From 50 mm/s² to 30,000 mm/s² | Acceleration Time |
| S-Curve | Speed Profile |
| 2,000 block FIFO | Hardware Buffer Size |
| 20 milliseconds | PC-Controller Data exchange time |
| Optocoupler | Isolation Type |
| LAN with 100 Mbps transfer rate (TCP/IP) | Communication Type |
| More than 20 meters with UTP/More than 50 meters with SFUTP | Communication Length |
| 24 time locks with internal clock | Hardware Lock |
| 16 to 32 volts - 200 milliamperes | Power Consumption |
| 11\*13 centimeters | Dimensions |
| Loop-open control | Controller Type |
| Windows 7, 8, 10, 11 | Operating System |
| Joystick, Remote control, Handwheel | Supported Equipment |
| 3, 2 | Active Axis Count |

### 1-2-5 ![](RackMultipart20230318-1-aqtmlv_html_9964f15343a4da74.png) **Radonix PC-Smart 4A**

**Flexible High Performance Position Control**

| 4 independent and synchronous axes | Axes |
| --- | --- |
| 16 PNP and NPN inputs | Digital Inputs |
| 8 PNP and NPN output | Digital Outputs |
| 2 (10-0 Volts) | Analog Outputs |
| 2 (10-0 Volts) | Analog Inputs |
| 500,000 pulses per second | Axis Pulse Rate |
| Directional pulse | Axis Pulse Type |
| From 50 mm/s² to 30,000 mm/s² | Acceleration Time |
| S-Curve | Speed Profile |
| 2,000 block FIFO | Hardware Buffer Size |
| 20 milliseconds | PC-Controller Data exchange time |
| Optocoupler | Isolation Type |
| LAN with 100 Mbps transfer rate (TCP/IP) | Communication Type |
| More than 20 meters with UTP/More than 50 meters with SFUTP | Communication Length |
| 24 time locks with internal clock | Hardware Lock |
| 12 to 24 volts - 300 milliamperes | Power Consumption |
| 25\*13 centimeters | Dimensions |
| Loop-open control | Controller Type |
| Windows 7, 8, 10, 11 | Operating System |
| Joystick, Remote control, Handwheel | Supported Equipment |
| 4, 3, 2 | Active Axis Count |

### 1-2-6 ![Picture 5](RackMultipart20230318-1-aqtmlv_html_d5605058eaf6888.gif) **Radonix PC-Smart 3AS**

**Smart Position Control - Suitable for steppers**

| 3 independent and synchronous axes | Axes |
| --- | --- |
| 8 PNP and NPN inputs | Digital Inputs |
| 4 PNP and NPN output | Digital Outputs |
| 2 (10-0 Volts) | Analog Outputs |
| 100,000 pulses per second | Axis Pulse Rate |
| Directional pulse | Axis Pulse Type |
| From 50 mm/s² to 30,000 mm/s² | Acceleration Time |
| S-Curve | Speed Profile |
| 2,000 block FIFO | Hardware Buffer Size |
| 20 milliseconds | PC-Controller Data exchange time |
| Optocoupler | Isolation Type |
| LAN with 100 Mbps transfer rate (TCP/IP) | Communication Type |
| More than 20 meters with UTP/More than 50 meters with SFUTP | Communication Length |
| 24 time locks with internal clock | Hardware Lock |
| 12 to 24 volts - 200 milliamperes | Power Consumption |
| 15\*13 centimeters | Dimensions |
| Loop-open control | Controller Type |
| Windows 7, 8, 10, 11 | Operating System |
| Joystick, Remote control, Handwheel | Supported Equipment |
| 3, 2 | Active Axis Count |

## 1-3Identifying Different Parts of the Board

### 1-3-1 **Radonix PC-Pro LAN 2A**

**Flexible High Performance Position Control**

![Shape6](RackMultipart20230318-1-aqtmlv_html_e8bb2581bcdc2eef.gif) ![](RackMultipart20230318-1-aqtmlv_html_90dd0e2e247f2d39.png)

### 1-3-2 **Radonix PC-Pro LAN 4A**

**Flexible High Performance Position Control**

![](RackMultipart20230318-1-aqtmlv_html_59754c6342220f6.png)

### 1-3-3 **Radonix PC-Pro LAN 6A**

**Flexible High Performance Position Control**

![](RackMultipart20230318-1-aqtmlv_html_5caa39820711b22e.png)

### 1-3-4 **Radonix PC-Pro LAN 3AS**

**Flexible High Performance Position Control**

![](RackMultipart20230318-1-aqtmlv_html_9631977e52596df1.png)

### 1-3-5 **Radonix PC-Smart 4A**

**Flexible High Performance Position Control**

![](RackMultipart20230318-1-aqtmlv_html_d3afdade3ac13c95.png)

### 1-3-6 **Radonix PC-Smart 3AS**

**Flexible High Performance Position Control**

# فصل 2 ![](RackMultipart20230318-1-aqtmlv_html_3a51e814b2906a5a.png)نصب کنترلر در تابلو برق و سیم کشی

## 2-1Installation of the Radonix Controller in the Electrical Panel

The Radonix controllers have a strong plastic protective cover that is supported by a base. They have been designed to be installed on the rails of the electrical panel.

Location of the Controller

The location of the controller is crucial in relation to the other elements inside the electrical panel. Inverters, drivers, and high-voltage cables can generate noise in the electrical panel. Therefore, it is important to place the controller at a sufficient distance from these sources, particularly the path of the communication cable to the computer. The controller should be at least 5 cm away from the other components (such as ducts and cables inside the panel) on each side. (Refer to Figure 1)

Switchboard Design

It is recommended that the switchboard designer allocate a separate area for the low-voltage elements and the controller, and respect the distance between the high-voltage components of the panel. The high-voltage cables should have the shortest path in the panel and should not pass near low-voltage elements or be at a greater distance from these elements.

## 2-2Wiring and internal circuit of the controller

Table (1) summarizes the internal circuitry of the Radonix controller board.

| Description | Terminals | Terminal Identification |
| --- | --- | --- |
| To communicate with a computer under TCP/IP protocol, please refer to section 2.2.1 for more information. | Ethernet connection | Computer Connection |
| For the main power supply of the controller, please refer to section 2.2.2 for more information. | DC24V، DC0V | Power Supply |
| For communication with external controllers, please refer to section 2.2.3 for more information. | Input connector | Digital Inputs |
| For communication with external controlled devices, please refer to section 2.2.4 for more information. | Output connector | Digital Outputs |
| For communication with external controlled devices, these outputs create a continuous value between 0 and 10 volts. Please refer to section 2.2.5 for more information. | Output Analog & PWM | Analog and PWM Outputs |
| For communication between the controller's axes and servo and stepper motors, please refer to section 2.2.7 for more information. | Axis | Axis |
| It is designed for communication with a handwheel, please refer to section 2.2.7 for more information. | Handwheel | Handwheel |
| For communication with RS\_485, please refer to section 2.2.7 for more information. | RS485 communication connector | RS485 |

Table (1) - Wiring and Internal Circuit of the Controller 

### 2-2-1Communication with a Computer

The PC-Pro-Lan and PC-Smart series Radonix controllers communicate with a computer using the TCP/IP protocol and are connected through an Ethernet connection in a standard manner. (Refer to Figure 2) Standard CAT5 and CAT6 cables, up to 30 meters in length, can be used for communication. The wiring on both sides of the cables is depicted in Figure 3.

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png) | Keep in Mind that it is advisable for the path of the communication cable to not be in close proximity to high voltage cables and to not be exposed to pressure or impact along its route. |
| --- | --- |

![](RackMultipart20230318-1-aqtmlv_html_d0c1040bcd49e34b.png)

![](RackMultipart20230318-1-aqtmlv_html_f8892ee3e013378d.jpg)

![Shape7](RackMultipart20230318-1-aqtmlv_html_6999a36c21a3272d.gif)

Figure (2) - LAN cable

![](RackMultipart20230318-1-aqtmlv_html_705c5ae349bd6930.png)

Figure (3) - Wiring of LAN cable

### 2-2-2Power Supply

Power Supply The Radonix controllers are connected to the power supply via a 3-pin terminal. The positive terminal (24+) is connected to the positive pole of the power source, and the negative terminal (GND) is connected to the negative pole. (Refer to Figure 4 for the GND connection)

PC-Pro Models:

![](RackMultipart20230318-1-aqtmlv_html_786d9c68c4d4219b.jpg)

![](RackMultipart20230318-1-aqtmlv_html_8034f77fa55eb2e7.gif) ![Shape8](RackMultipart20230318-1-aqtmlv_html_2a7631f41eb98a45.gif)

![](RackMultipart20230318-1-aqtmlv_html_407eaf74350ec96d.png)PC-Smart Models:

![](RackMultipart20230318-1-aqtmlv_html_802a87f39837b0a2.png)

![Shape9](RackMultipart20230318-1-aqtmlv_html_2a7631f41eb98a45.gif)

Figure (4) - Power Supply Connector

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png) | Power Connector The positive pole of the controller is protected by a diode, which prevents damage to the controller if the poles are switched. The electronic circuit diagram of the controller is depicted in Figure 5. |
| --- | --- |

![](RackMultipart20230318-1-aqtmlv_html_8ee94c67f7cd5181.png)Schematic of Power Supply in PC-Pro Models:

Schematic of Power Supply in PC-Smart Models:

![](RackMultipart20230318-1-aqtmlv_html_ff693e7588871574.png)

Figure (5) - Schematic of the Electronic Power Supply Circuit

The power supply voltage for PC-Pro models should be between 18 and 28 volts, and for PC-Smart models it should be between 12 and 24 volts, requiring a current of fewer than 0.5 amps. Switching power supplies are the most suitable type for the Radonix controllers because they are not significantly affected by changes in network voltage. It is recommended to use 24V switching power supplies to power the Radonix controllers. Calculating Power Supply Current To determine the required power supply current in the electrical panel, the current consumption of each element connected to the power supply must be calculated. For example, if there are 4 relays, 3 pneumatic solenoid valves, and a controller in a switchboard, the current consumption can be determined using Ohm's law (V=I\*R).

The electric currents should be calculated and their sum considered as the current of the power supply, along with a confidence factor of a few percent. For example, if the current consumption of the relays is 0.1A and that of the solenoid valves is 0.25A, the total current can be calculated as follows:

Total current = controller current + relay current + solenoid valve current IT = 0.5 + 4 \* 0.1 + 3 \* 0.25 = 1.65A

Therefore, by choosing a 2A pow`er supply, a good reliability factor will be maintained.

Power Consumption of Significant Elements

It is important to calculate the current consumption of elements that impose a significant load on the power supply. Elements such as brakes, servo motors, and pneumatic valves are examples of such elements. The power consumption of these elements can be calculated using an ammeter or by using Ohm's law (V=I\*R). The ohmic resistance of each element can be measured using an ohmmeter and then, considering the source voltage, the equivalent current consumed by each element (I=24R) can be calculated.

### 2-2-3 Digital Inputs

The digital inputs of Radonix controllers are named as I.[n], where n is a number greater than zero and represents the input number. These inputs are isolated by optical couplers and have low noise tolerance due to their low impedance. (Figure 6)

PC-Pro Models:

![](RackMultipart20230318-1-aqtmlv_html_980ec45d94e56388.jpg)

![Shape10](RackMultipart20230318-1-aqtmlv_html_3423f2c6f862c79a.gif) ![](RackMultipart20230318-1-aqtmlv_html_343b9bd07aa87acf.jpg)

PC-Smart Models:

![](RackMultipart20230318-1-aqtmlv_html_407eaf74350ec96d.png)

![](RackMultipart20230318-1-aqtmlv_html_edacfe8efaff0556.png) ![Shape11](RackMultipart20230318-1-aqtmlv_html_3423f2c6f862c79a.gif)

Figure (6) - Digital Inputs

The digital inputs on Radonix controllers have the capability to switch between NPN and PNP modes depending on the output of the device or sensor. The mode changeover switch must be set to PNP position for devices with PNP output and NPN position for devices with NPN output. The internal circuit schematics for both NPN and PNP modes on PC-Pro and PC-Smart models can be seen in Figures 7 and 8.

Digital input schematic in NPN mode for PC-Pro models:

![](RackMultipart20230318-1-aqtmlv_html_db31ed0e072a1a1b.png)

Digital input schematic in PNP mode for PC-Pro models:

![](RackMultipart20230318-1-aqtmlv_html_695edacfd58e2043.png)

Figure (7) - Schematic of Digital Inputs in NPN and PNP Mode in PC-Pro Models

Digital Input Schematic in NPN and PNP modes in PC-Smart models:

![](RackMultipart20230318-1-aqtmlv_html_b0d44d773aafe9f5.png)

Figure (8) - Schematic of digital inputs in NPN and PNP modes in PC-Smart models.

In various branches of industrial automation, there are equivalent terms for PNP and NPN. Some examples of these terms include:

NPN = Sink = Low Active

PNP = Source = High Active

is done by connecting the positive terminal of the device to the input terminal and the negative terminal to the common terminal (GND). In PNP mode, the connection is done by connecting the negative terminal of the device to the input terminal and the positive terminal to the positive power supply (+Vcc). The wiring diagrams for these connections are shown in Figures 9 and 10.

Connection of digital inputs with switchboard elements in NPN mode in PC-Pro models:

![](RackMultipart20230318-1-aqtmlv_html_5663ec50495de1fa.png)

Connection of digital inputs with switchboard elements in PNP mode in PC-Pro models:

![](RackMultipart20230318-1-aqtmlv_html_f66123a46e21c134.png)

Figure (9) - Connection of digital inputs with electrical panel elements in NPN and PNP mode in PC-Pro models

Connection of digital inputs with electrical panel elements in NPN mode in PC-Smart models

![](RackMultipart20230318-1-aqtmlv_html_65d79b6154c565b3.png)

Connection of digital inputs with electrical panel elements in PNP mode in PC-Smart models

![](RackMultipart20230318-1-aqtmlv_html_84b85ab1bff1e606.png)

Figure (10) - Connection of digital inputs with electrical panel elements in NPN and PNP mode in PC-Smart models

### 2-2-4 Digital Outputs

The digital outputs of radial Radonix controllers are named O.[n], where n is a numerical identifier greater than zero and represents the output number (Figure 11). These outputs are protected in PC-Pro models against short-circuits and heat generated by high currents. If any of these events occur, an O-Error error is indicated on the board by the red LED, and all outputs are disabled by the controller. In PC-Smart models, the outputs are relays with a 1-amp contact and 24-volt bipolar zener diodes are taken into consideration for protection against overloading.

PC-Pro Models:

![](RackMultipart20230318-1-aqtmlv_html_84f3d41bc2939cab.jpg)

![](RackMultipart20230318-1-aqtmlv_html_ab49d37f9883a0b1.jpg) ![Shape12](RackMultipart20230318-1-aqtmlv_html_926e2ae8429fe66a.gif)

PC-Smart Models:

![](RackMultipart20230318-1-aqtmlv_html_a4b58ae8e3646b4.png)

![](RackMultipart20230318-1-aqtmlv_html_18a297acfa8f496c.png) ![Shape13](RackMultipart20230318-1-aqtmlv_html_926e2ae8429fe66a.gif)

Figure (11) – Digital Outputs

| ![](RackMultipart20230318-1-aqtmlv_html_e2de3eb796f9372f.png)WARNING |
- In PC-Pro models, under no circumstances should the outputs be connected to each other for high current flow or to create circuit paths, as the controller considers this as an error and will immediately turn off all outputs.
 |
| --- | --- |

The maximum current output for PC-Pro models is around mA300, and for PC-Smart models is approximately 1A. Therefore, if we plan to set up a device with a higher current, we must use a relay.

The digital outputs of the Radonix controllers in PC-Pro models are all NPN, which means they are Low Active or Sink, so when activated, the output is connected to zero voltage or GND.

The electrical schematic of the Radonix controller outputs is shown in Figure 12

The internal circuit of the digital outputs in PC-Pro models:

![](RackMultipart20230318-1-aqtmlv_html_fffbf69f0790823f.png)

The internal circuit of the digital outputs in PC-Smart models:

![](RackMultipart20230318-1-aqtmlv_html_5781ac518756d1e4.png)

Figure (12) - Internal circuit of digital outputs.

In the connection to relays, a diode is not needed to eliminate back current. The way of connecting the outputs to multiple devices is shown in Figure 13.

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png) | Please note that all peripheral devices such as PLCs and inverters must be connected to a common or mutually powered ground in the connection. In fact, even if multiple power supplies are used, the ground of the power supplies must be connected to each other. |
| --- | --- |

![](RackMultipart20230318-1-aqtmlv_html_b05117c33e7f875b.png)
Connection of digital outputs with electrical panel elements in PC-Pro models:

Connection of digital outputs with electrical panel elements in NPN mode in PC-Smart models:

![](RackMultipart20230318-1-aqtmlv_html_1c966be52684edbb.png)

Connection of digital outputs with electrical panel elements in PNP mode in PC-Smart models:

![](RackMultipart20230318-1-aqtmlv_html_e81329622ab1427.png)

Figure (13) - Connection of digital outputs with electrical panel elements

### 2-2-5Analog and Bandwidth Modulation Outputs

Radonix controllers in PC-Pro models have analog and PWM outputs which are shown as AO.[n] and PWM.[n] respectively, while PC-Smart models only have analog outputs shown as A[n], where n is a number greater than zero.

The analog outputs produce a continuous value between 0 and 10 volts. (Figure 14)

PC-Pro models:

![](RackMultipart20230318-1-aqtmlv_html_7097737de814003d.jpg) ![](RackMultipart20230318-1-aqtmlv_html_c12d3e58326b4f4b.jpg)

![Shape14](RackMultipart20230318-1-aqtmlv_html_926e2ae8429fe66a.gif)

Models PC-Smart :

![](RackMultipart20230318-1-aqtmlv_html_9d3ed2d8f04a8032.png) ![](RackMultipart20230318-1-aqtmlv_html_d2239be328fd820d.png)

![Shape15](RackMultipart20230318-1-aqtmlv_html_926e2ae8429fe66a.gif)

Figure (14) - Analog and PWM outputs

| ![](RackMultipart20230318-1-aqtmlv_html_e2de3eb796f9372f.png)WARNING |
- These outputs are protected against a short connection to the negative power supply terminal and grounded electricity, but a direct connection to a voltage higher than 10 volts will cause damage to them.
 |
| --- | --- |

The electrical circuit diagram of the analog outputs is shown in figure 15.

Electronic circuit schematic of analog outputs in PC-Pro models:

![](RackMultipart20230318-1-aqtmlv_html_1ee605f0050e6e6.png)

Electronic circuit schematic of analog outputs in PC-Smart models:

![](RackMultipart20230318-1-aqtmlv_html_af0116e972290d8.png)

Figure (15) - Electronic Circuit Diagram of Analog Outputs

How to connect the analog outputs is shown in Figure 16.

![](RackMultipart20230318-1-aqtmlv_html_d2cfec83d913216c.png)

Figure (16) – Analog Output Connection

| ![](RackMultipart20230318-1-aqtmlv_html_e2de3eb796f9372f.png)WARNING |
- Please note that the analog inputs and outputs are highly sensitive to noise due to their high impedance. Therefore, it is better to keep the analog communication cables away from strong voltage cables and noisy components. Use a twisted pair cable to establish communication and avoid using single-wire cables for analog communication, preferably use multi-wire or twisted pair cables.
 |
| --- | --- |

### 2-2-6

    1.
### Analog Inputs

Radonix controllers in the PC-Smart models have analog inputs named A[n], where n represents a number greater than zero. The voltage range of these analog inputs is 0 to 10 volts, as shown in Figure 17.

PC-Smart Models :

![](RackMultipart20230318-1-aqtmlv_html_2fa841278a434f92.png) ![](RackMultipart20230318-1-aqtmlv_html_354fcec2c76801e4.png)

![Shape16](RackMultipart20230318-1-aqtmlv_html_926e2ae8429fe66a.gif)

Figure (17) – Analog Inputs

The electronic circuit schematic of analog inputs in PC-Smart models

![](RackMultipart20230318-1-aqtmlv_html_993233b1bbd04b9c.png)

Figure (18) – Analog Inputs

### 2-2-2 Axes

Axes in Radonix controllers are numbered and named Axis[n]. Only active axes are allowed and inactive axes are not. The connection between the controller and the DB servo motors or stepper motors for the axes is established through connector 15, as shown in Table 2 and Figure 19.

![](RackMultipart20230318-1-aqtmlv_html_28a148bf024c65e2.gif) ![](RackMultipart20230318-1-aqtmlv_html_14d7324ce82f0232.jpg)

![Shape17](RackMultipart20230318-1-aqtmlv_html_926e2ae8429fe66a.gif)

![Shape18](RackMultipart20230318-1-aqtmlv_html_5eb25b036aeb1543.gif)

(Female) DB15

![Picture 14](RackMultipart20230318-1-aqtmlv_html_1a0a46f8ae29e38d.gif)

![Shape19](RackMultipart20230318-1-aqtmlv_html_ecf83f3a36d81fbf.gif)

(Male) DB15

Figure (19) – Connector

| Alarm Reset | 9 |
 | +VCC | 1 |
| --- | --- | --- | --- | --- |
| GND | 10 |
 | Direction - | 2 |
| GND | 11 |
 | Direction + | 3 |
| GND | 12 |
 | Pulse - | 4 |
| GND | 13 |
 | Pulse + | 5 |
| GND | 14 |
 | Servo On | 6 |
| GND | 15 |
 | Servo Ready | 7 |
| GND |
 |
 | Encoder Zero | 8 |

Table (2) – Pinouts

#### 2-2-2-1The function of axle pins in Radonix controllers:

**+VCC**

This pin is the source voltage output pin through the controller connector. It has a maximum current capacity of 100mA and is used to power the COM+.

**Direction+ & Direction-**

These two pins determine the direction of the motor. The connection type is line drive and they have a maximum current capacity of 25mA. They can control up to two motors simultaneously and in parallel.

**Pulse+ & Pulse-**

These two pins determine the amount of movement and the speed of the motor through a digital pulse with line drive output. They have a maximum current capacity of 25mA and can control up to two motors at the same time. The electronic circuit schematic for Pulse and Direction outputs is shown in Figure 20.

![](RackMultipart20230318-1-aqtmlv_html_53e2c6e726cbd9d7.png)

Figure (20) - Internal Circuit of Pulse and Direction Pins.

**Servo On**

Servo On Pin The Servo On pin is an output pin that is used to turn on the servo motor when the CNC controller is activated. If activated, the SON LED, which is located on the controller near each axis connector, will illuminate. The internal circuit of the Servo On pin is shown in Figure 21. It is important to note that the Servo On pin is not used in stepper motor systems.

![](RackMultipart20230318-1-aqtmlv_html_1f10966b1d113b1e.png)PC-Pro Models :

PC-Smart Models:

![](RackMultipart20230318-1-aqtmlv_html_f336188e98dd5a51.png)

Figure (21) - Internal Circuit of the Servo On Pin.

**Servo Ready**

Servo-Ready Pin The Servo Ready pin is an input pin isolated by a photo coupler that checks the readiness of the servo motor. In the case of an error or problem with the servo motor's power supply, connection, or encoder, the pin reports the status to the controller, preventing the axes from continuing to move, and an axis error can be displayed on the interface (Figure 22). The Servo Ready pin is not used in stepper motors.

P ![](RackMultipart20230318-1-aqtmlv_html_442b944e504c4146.png) C-Pro Models:

PC-Smart Models:

![](RackMultipart20230318-1-aqtmlv_html_a7189629ec714407.png)

Figure (22) - Internal Circuit of the Servo Ready Pin.

**Encoder Zero**

This pin is an input pin isolated by Photo Coupler, which is only available in PC-Smart models.

And the zero point of the encoder in the servo motor is announced to the controller as a pulse. The use of this pin to find the Home point.

It is accurate on some devices. (Figure 23)

Encoder Zero pin is not used in steppers.

![](RackMultipart20230318-1-aqtmlv_html_2bb3201ea6796576.png)

Figure (23) - Internal Circuit of the Encoder Zero Pin.

**Alarm Reset**

This pin is an output pin used to clear the drive error. If the drive reports an error and it is resolved, the error can be cleared without the need to disconnect the electrical circuit, by using this output pin, and the drive can be put back into normal operation. (Figure 24)

PC-Pro Models:

![](RackMultipart20230318-1-aqtmlv_html_510921fba2f0b965.png)

PC-Smart Models:

![](RackMultipart20230318-1-aqtmlv_html_86523158a1ee6c2.png)

Figure (24) - Internal alarm reset circuit.

**GND**

The Ground (GND) of the CNC controller is connected to six pins of the axis connector. These pins provide the ground connection required to connect to the drive, ensuring proper electrical signaling and stability of the system.

| ![](RackMultipart20230318-1-aqtmlv_html_e2de3eb796f9372f.png)WARNING |
- Please note that the Direction and Pulse output pins are digital and be careful when connecting them to other pins, especially pin 1.
 |
| --- | --- |

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png) |
- The Reset and Servo On output pins of the Radonix controller are open collector and NPN, meaning that when activated, Ground is switched to the pin. The driver connected to these pins must be NPN.
- The Ready and Encoder Zero input pins are also NPN, and the servo drive connected to these pins must connect Ground to these pins, making it NPN as well.
- Only the Direction+, Direction-, Pulse+, and Pulse- pins are used to connect the controller to the stepper motors. No other pins are needed. If the cable is disconnected, the axis error may appear as the controller sees this as an error. You can check pins 6 and 7 in the DB15 connector to detect any errors.
- For the user's convenience, wiring between Radonix controllers and servo motors is provided in Appendix 1."
 |
| --- | --- |

### 2-2-3Handwheel and serial communication

The 9-pin connector in the Radonix controllers (PC-Pro models, excluding the Pro LAN 3AS model) is used for communication with the handwheel and RS485 connection. In the PC-Smart models, there are two separate connectors (6 and 4 pins respectively) for handwheel and RS485 communication (Figure 25)

Handwheels with 5V encoder and differential outputs are compatible for communication with the Radonix controller. The schematic pin connection with the handwheel is shown in Figure 27. RS485 communication, a type of serial communication, is transmitted through pins A.485 and B.485.

PC-Pro Models :

![Picture 13](RackMultipart20230318-1-aqtmlv_html_3d984fe3b26d8a6e.gif)

![Shape20](RackMultipart20230318-1-aqtmlv_html_2edb2d47cb3a3934.gif)

![](RackMultipart20230318-1-aqtmlv_html_482ddece5b46f571.jpg)

PC-Smart Models:

![](RackMultipart20230318-1-aqtmlv_html_23b5ce3cfcc4081c.png)

![Shape21](RackMultipart20230318-1-aqtmlv_html_aa80c78c6f9898e8.gif) ![](RackMultipart20230318-1-aqtmlv_html_4ca943e393f1f3ae.png)

![](RackMultipart20230318-1-aqtmlv_html_b8b41a2298c7cc07.jpg)

![](RackMultipart20230318-1-aqtmlv_html_b1f090cf0dda9f13.png) ![Shape22](RackMultipart20230318-1-aqtmlv_html_aa80c78c6f9898e8.gif)

Figure (25) - Communication pins with the Encoder and RS485

The internal circuit of the RS485 communication pins in the PC-Smart and PC-Pro models:

![](RackMultipart20230318-1-aqtmlv_html_903ea76440682a53.png)

Figure (26) - Internal circuit of RS485 communication pins

The internal circuit of the handwheel communication pins in the PC-Pro models : ![](RackMultipart20230318-1-aqtmlv_html_fb8928a0fd41513e.png)

The internal circuit of the handwheel communication pins in the PC-Smart models:

![](RackMultipart20230318-1-aqtmlv_html_54e490dd5b247026.png)

Figure (27) - Internal circuit for communication pins with handheld.

![](RackMultipart20230318-1-aqtmlv_html_b413636e8e0fbaf.png)Figure (28) - The schematic equivalent of the internal circuit of the controller for communication with the handwheel.

Figure 29 shows the handwheel encoder communication pins on the controller in two differential and open collector modes. In the PC-Pro models, if the handwheel encoder is an open collector, the HW.A+ and HW.B+ pins should be connected to the +5V pin of the 9-pin connector. The other switches of the handwheel should be connected to the digital inputs of the controller, which is shown in Figure 29.

![](RackMultipart20230318-1-aqtmlv_html_1d003d2346e9f05d.png)

Figure (29) - Connection of handwheel with Radonix controller

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png) | Note that the analog input is only available in the PC-Smart model controllers. |
| --- | --- |

# فصل 3 نصب نرم افزار رادونیکس کم پرو

## 3-1software installation

### 3-1-1Requirements and comprehensive view for software installation.

In this section, we take a general look at the steps of installing Radonix software.

First, to install and use Radonix software, you need a computer with the following

minimum specifications.

| سیستم عامل | ویندوز 7، ویندوز 8، ویندوز 10، ویندوز 11 |
| --- | --- |
| سی پی یو (CPU) | 1GHz به بالا |
| رم (RAM) | 2GByte به بالا |
| هارد دیسک | بیشتر از 10Gbyte فضای خالی |
| کارت گرافیکی | کارت گرافیکی باید مدلی باشد که حین نصب XNA خطایی بروز نکند و توسط XNAشناسایی شود. |
| مادر برد | مادر برد کامپیوتر باید حداقل یک ارتباط LAN داشته باشد. |

جدول(1)

After making sure that the computer is compatible, you should install the following programs in order.

| 1 | دات نت فریم ورک 4 | dotNetFx40\_Client\_x86\_x64 |
| --- | --- | --- |
| 2 | XNA ورژن 4 | xnafx40\_redist |
| 3 | برنامه رادونیکس کم پرو | RadonixCAM-Pro X.X.X |
| 4 | اینترفیس | Interface |

جدول(2)

And after installing the above software, the controller is ready to start.

## 3-2 **Installation steps**

| ![](RackMultipart20230318-1-aqtmlv_html_e2de3eb796f9372f.png)WARNING |
- Make sure that the computer is compatible, as explained in the second chapter.
- Ensure that the computer does not have a virus, as a computer virus can cause disruptions in the computer's performance and installed software, including the Radonics software..
 |
| --- | --- |

After making sure that the computer operating system is healthy, install the software in order.

### 3-2-1Installation of Microsoft .NET Framework 4 Client Profile software

To download Microsoft .NET Framework 4 Client Profile, scan the barcode below. ![](RackMultipart20230318-1-aqtmlv_html_e9c8ae3a1565c101.jpg)

After downloading the .NET Framework 4 software, double-click on the downloaded file and follow these steps.

![Shape24](RackMultipart20230318-1-aqtmlv_html_54d3d72c62ca6d91.gif) ![Shape23](RackMultipart20230318-1-aqtmlv_html_d3d4cd79580281.gif) ![Shape25](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif)

1

 ![](RackMultipart20230318-1-aqtmlv_html_9b13f3ea87b1e68c.png)

Figure (1)

![](RackMultipart20230318-1-aqtmlv_html_730be27b1acf5dd5.png)

Figure (2)

![Shape31](RackMultipart20230318-1-aqtmlv_html_242d54163cf45f89.gif) ![Shape30](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape27](RackMultipart20230318-1-aqtmlv_html_625dd083199bdd1e.gif) ![Shape28](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape26](RackMultipart20230318-1-aqtmlv_html_52da7f2a82d9b802.gif) ![Shape29](RackMultipart20230318-1-aqtmlv_html_3d17ea43e17f319a.gif)

3

2

= ![](RackMultipart20230318-1-aqtmlv_html_a210029ef722b6d.png)

Figure (3)

![](RackMultipart20230318-1-aqtmlv_html_651265c963c4a8d7.png)

Figure (4)

![Shape33](RackMultipart20230318-1-aqtmlv_html_b891a3daa38938a9.gif) ![Shape34](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape32](RackMultipart20230318-1-aqtmlv_html_374a65c3c5a91e1.gif)

4

 ![](RackMultipart20230318-1-aqtmlv_html_683fcfc866f9eba6.png)

Figure (5)

The software was installed correctly.

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png) |
- If the user already has the software installed on their computer, then after Figure 1 is displayed, Figure 6 will appear. In this case, simply press the "Close" button.
 |
| --- | --- |

![Shape36](RackMultipart20230318-1-aqtmlv_html_ce6c0de4fd9e3759.gif) ![Shape37](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape35](RackMultipart20230318-1-aqtmlv_html_47b6376f35e82c71.gif)

2

 ![](RackMultipart20230318-1-aqtmlv_html_461e70790f51e6fc.png)

Figure (6)

### 3-2-2Installing the Microsoft XNA Framework Redistributable 4.0 software

If you do not have the Microsoft XNA Framework Redistributable 4.0 software, you can download it using the QR code provided.

![](RackMultipart20230318-1-aqtmlv_html_6c390dba4f3f3b18.jpg)

After downloading the Microsoft XNA Framework Redistributable 4.0 software, double-click on the downloaded file and follow the on-screen instructions to install it.

![Shape39](RackMultipart20230318-1-aqtmlv_html_715d974903b9f1f4.gif) ![Shape40](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape38](RackMultipart20230318-1-aqtmlv_html_951e6f42bf695129.gif)

1

 ![](RackMultipart20230318-1-aqtmlv_html_9d8cf297ca51278.png)

Figure (7)

![](RackMultipart20230318-1-aqtmlv_html_91cc1f89994736e4.png)

Figure (8)

 ![Shape41](RackMultipart20230318-1-aqtmlv_html_f3d2d8d6127e81eb.gif) ![Shape43](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape42](RackMultipart20230318-1-aqtmlv_html_7e64fda1cac6a368.gif)

2

![](RackMultipart20230318-1-aqtmlv_html_17233b028e9b4f98.png)

Figure (9)

 ![Shape49](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape47](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape46](RackMultipart20230318-1-aqtmlv_html_199f2d8a861f6de6.gif) ![Shape48](RackMultipart20230318-1-aqtmlv_html_715d974903b9f1f4.gif) ![Shape45](RackMultipart20230318-1-aqtmlv_html_e59a395100fbf37b.gif) ![Shape44](RackMultipart20230318-1-aqtmlv_html_7e64fda1cac6a368.gif)

4

3

![](RackMultipart20230318-1-aqtmlv_html_68b8d706302fa5ae.png)

Figure (10)

 ![Shape50](RackMultipart20230318-1-aqtmlv_html_f3d2d8d6127e81eb.gif) ![Shape52](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape51](RackMultipart20230318-1-aqtmlv_html_ed2ffad00480ae0b.gif)

5

![](RackMultipart20230318-1-aqtmlv_html_e1a42d5301d8f140.png)

Figure (11)

 ![Shape54](RackMultipart20230318-1-aqtmlv_html_8c2ef60cb88a8265.gif) ![Shape55](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape53](RackMultipart20230318-1-aqtmlv_html_8cb9c3f174051b1.gif)

6

![](RackMultipart20230318-1-aqtmlv_html_45baaffb57c24b46.png)

Figure (12)

 ![Shape57](RackMultipart20230318-1-aqtmlv_html_ce6c0de4fd9e3759.gif) ![Shape58](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape56](RackMultipart20230318-1-aqtmlv_html_52aac313931fb0ca.gif)

7

![](RackMultipart20230318-1-aqtmlv_html_f81d689e49b86ef1.png)

Figure (13)

The software was installed correctly.

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png) |
- If the user already has the Microsoft XNA Framework Redistributable 4.0 software installed on their computer, after Figure 2 is displayed, Figure 14 will be shown. The user should then continue with the steps starting from Figure 14.
 |
| --- | --- |

![Shape59](RackMultipart20230318-1-aqtmlv_html_70c44777308c620f.gif) ![Shape60](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape61](RackMultipart20230318-1-aqtmlv_html_d4f439debca15a49.gif)

3

 ![](RackMultipart20230318-1-aqtmlv_html_c446a4e0d81c2f2a.png)

Figure (14)

![Shape62](RackMultipart20230318-1-aqtmlv_html_a9a6cd3cf2401e9.gif) ![Shape63](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape64](RackMultipart20230318-1-aqtmlv_html_4a2f4dc37a95e6e8.gif)

4

 ![](RackMultipart20230318-1-aqtmlv_html_b95287d07f83b559.png)

Figure (15)

![Shape67](RackMultipart20230318-1-aqtmlv_html_7314f71f684d7540.gif) ![Shape65](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape66](RackMultipart20230318-1-aqtmlv_html_782ce7b895e47c1c.gif)

5

 ![](RackMultipart20230318-1-aqtmlv_html_bc04a49dadb5b229.png)

Figure (16)

### 3-2-3Installing Radonix CAM-Pro X.X.X software

If you do not have the latest version of the Radonix CAM-Pro X.X.X software (where X represents the latest version number), you can download it by using the link or QR code provided.

![](RackMultipart20230318-1-aqtmlv_html_8a264b68955d8482.jpg)

After downloading the Radonix CAM-Pro X.X.X software, double-click on the downloaded file and follow the on-screen instructions to install it.

![Shape68](RackMultipart20230318-1-aqtmlv_html_2d8837d0818024e7.gif) ![Shape69](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape70](RackMultipart20230318-1-aqtmlv_html_5a21c99baf1cf51.gif)

1

 ![](RackMultipart20230318-1-aqtmlv_html_632651722535459f.png)

Figure (17)

![Shape71](RackMultipart20230318-1-aqtmlv_html_833f04d9f99d8411.gif) ![Shape73](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape72](RackMultipart20230318-1-aqtmlv_html_c8e6fce0c231bf72.gif)

2

 ![](RackMultipart20230318-1-aqtmlv_html_e81ca01795479f05.png)

Figure (18)

To change the default installation and save the location for the Radonix CAM-Pro software, you need to follow the installation steps outlined in Figures 19 and 20. If you do not wish to change the default location, simply proceed with the installation steps starting from Figure 21 or Step 5 written next to the figure.

![Shape75](RackMultipart20230318-1-aqtmlv_html_d3d4cd79580281.gif) ![Shape76](RackMultipart20230318-1-aqtmlv_html_119eb6e33dfe48a2.gif) ![Shape74](RackMultipart20230318-1-aqtmlv_html_47b6376f35e82c71.gif)

3

. ![](RackMultipart20230318-1-aqtmlv_html_eb3b2334344fd35.png)

Figure (19)

In Figure 20, you need to select the desired location for the software installation and then click the "OK" button.

![Shape78](RackMultipart20230318-1-aqtmlv_html_2d8837d0818024e7.gif) ![Shape79](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape77](RackMultipart20230318-1-aqtmlv_html_3a0c055abfcbcbbe.gif)

4

 ![](RackMultipart20230318-1-aqtmlv_html_30f0cea0365f1d0e.png)

Figure (20)

![Shape81](RackMultipart20230318-1-aqtmlv_html_70c44777308c620f.gif) ![Shape80](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape82](RackMultipart20230318-1-aqtmlv_html_3d17ea43e17f319a.gif)

5

 ![](RackMultipart20230318-1-aqtmlv_html_d7e6f7b1a2d50219.png)

Figure (21)

![Shape83](RackMultipart20230318-1-aqtmlv_html_d18570ca85dffa93.gif) ![Shape85](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape84](RackMultipart20230318-1-aqtmlv_html_7e64fda1cac6a368.gif)

6

 ![](RackMultipart20230318-1-aqtmlv_html_c4f8084c078806c7.png)

Figure (22)

![](RackMultipart20230318-1-aqtmlv_html_237d912709b5b0ec.png)

Figure (23)

![Shape86](RackMultipart20230318-1-aqtmlv_html_70c44777308c620f.gif) ![Shape88](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape87](RackMultipart20230318-1-aqtmlv_html_cc513b9ee7f4739d.gif)

7

 ![](RackMultipart20230318-1-aqtmlv_html_c76f61631da6e765.png)

Figure (24)

The software was installed correctly.

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png) |
- If the user already has the software installed on their computer, they can continue by following the steps starting from Figure 25 in order to prevent the installation process from repeating.
 |
| --- | --- |

![Shape89](RackMultipart20230318-1-aqtmlv_html_625dd083199bdd1e.gif) ![Shape91](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape90](RackMultipart20230318-1-aqtmlv_html_8278465a3dce93d2.gif)

1

 ![](RackMultipart20230318-1-aqtmlv_html_f12f24f1035c2bf8.png)

Figure (25)

![Shape94](RackMultipart20230318-1-aqtmlv_html_715d974903b9f1f4.gif) ![Shape95](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape92](RackMultipart20230318-1-aqtmlv_html_4ed9ece03d609b42.gif) ![Shape93](RackMultipart20230318-1-aqtmlv_html_243760ff890ff522.gif)

2

 ![](RackMultipart20230318-1-aqtmlv_html_502879eae50e1d72.png)

Figure (26)

![Shape99](RackMultipart20230318-1-aqtmlv_html_464d0bdf7eba9b14.gif) ![Shape97](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape96](RackMultipart20230318-1-aqtmlv_html_625dd083199bdd1e.gif) ![Shape98](RackMultipart20230318-1-aqtmlv_html_63967ad2f07a21be.gif)

3

 ![](RackMultipart20230318-1-aqtmlv_html_7e7ff41239346fad.png)

Figure (27)

After successfully completing the installation of the Radonix CAM-Pro software, the user should select the appropriate interface for their device based on the Radonix controller being used. The different interfaces and their features are thoroughly explained in Chapter 4.

## 3-3 interface installation

As stated in the introduction, the CNC (Computer Numeric Control) controller is the main interface between the program and the user. Everything the user sees and interacts with on the computer is through the Radonix program. To ensure the proper interface, the user can access the folder of different router interfaces through the barcode and download the desired one.

![](RackMultipart20230318-1-aqtmlv_html_8780fe668c18bea7.jpg)

After downloading the interface, double-click on the downloaded file and follow the steps below.

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png) |
- Note that due to the variety of interfaces, they are represented as x-x-x in this text. The user should use the appropriate interface based on the type of their device. For example, one of the router interfaces is shown in Figure 28 (for more information, refer to Chapter 4).
 ![](RackMultipart20230318-1-aqtmlv_html_ae443cb9f241399e.png)



Figure(28) |
| --- | --- |

![Shape101](RackMultipart20230318-1-aqtmlv_html_adcc80c11f7b639.gif) ![Shape102](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape103](RackMultipart20230318-1-aqtmlv_html_c9926d183c045c92.gif) ![Shape100](RackMultipart20230318-1-aqtmlv_html_904f14ffe7d0d921.gif)

1

 ![](RackMultipart20230318-1-aqtmlv_html_ff1604dbbd3c948c.png)

Figure (29)

![Shape106](RackMultipart20230318-1-aqtmlv_html_242d54163cf45f89.gif) ![Shape107](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape104](RackMultipart20230318-1-aqtmlv_html_bf01ac1db5346c4d.gif) ![Shape108](RackMultipart20230318-1-aqtmlv_html_67a8a3e70f800aa1.gif) ![Shape105](RackMultipart20230318-1-aqtmlv_html_f11a4131bcf46109.gif)

It changes based on the specified interface.

2

 ![](RackMultipart20230318-1-aqtmlv_html_cce8a1bd6bac7f8b.png)

Figure (30)

![Shape111](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape110](RackMultipart20230318-1-aqtmlv_html_a9a6cd3cf2401e9.gif) ![Shape109](RackMultipart20230318-1-aqtmlv_html_3ed68b6b9ac4f863.gif)

3

 ![](RackMultipart20230318-1-aqtmlv_html_7b8c500415941d04.png)

Figure (31)

The interface has been installed correctly and the software is ready to launch.

To access the installed software, go to the Start menu in Windows and search for "Radonix" in the search field. You will see three Radonix icons

(refer to Table 3 and Figure 32) as follows:

| ![](RackMultipart20230318-1-aqtmlv_html_c8b8c5dd81cc2433.gif) | نرم­افزار اصلی رادونیکس می­باشد. | Radonix CAM-Pro |
| --- | --- | --- |
| ![](RackMultipart20230318-1-aqtmlv_html_cead760a88c83190.png)
 | جهت کالیبراسیون محورها استفاده می­شود. برای اطلاعات بیشتر لطفا به بخش پنجم مراجعه نمایید. | Radonix CAM-Pro Calibrator |
| ![](RackMultipart20230318-1-aqtmlv_html_52baa814063fee11.gif) | جهت تست کنترلر استفاده می­شود. برای اطلاعات بیشتر لطفا به بخش ششم مراجعه نمایید. | Radonix CAM-Pro Test |

Table (3)

 ![Shape115](RackMultipart20230318-1-aqtmlv_html_ff8680ec41b44084.gif) ![Shape114](RackMultipart20230318-1-aqtmlv_html_8b4bfb558af7076c.gif)

![Shape112](RackMultipart20230318-1-aqtmlv_html_8d921927097c9e94.gif) ![Shape113](RackMultipart20230318-1-aqtmlv_html_aee07028ce784218.gif)

Search bat

Start menu

 ![](RackMultipart20230318-1-aqtmlv_html_17413d896117256f.png)

Figure (32)

To launch the software, click on the Radonix CAM-Pro icon. This will open the software environment.

## 3-4 **Connecting the controller to the computer**

As explained in detail in Chapter 2 regarding the wiring and voltage supply of the controller, turn on the controller and make sure the Power LED lights up. Then, connect one side of the LAN cable to the LAN port of the controller and the other side to the computer. To establish the connection between the controller and the computer, perform the following basic settings in order. Note that these settings only need to be done once and are saved after the controller and computer are connected.

### 3-4-1IP definition

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png)
 |
- To set the IP, after connecting the controller to the computer, open the "Not Pro" program.
 |
| --- | --- |

To set the IP, follow these steps in order:

1. Go to the Start menu in Windows.

2. Enter the Control Panel environment.

3. Follow the steps shown in Figures 33 to 40 in order. (Refer to Figure 33)

 ![Shape116](RackMultipart20230318-1-aqtmlv_html_adcc80c11f7b639.gif) ![Shape118](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape117](RackMultipart20230318-1-aqtmlv_html_f46a2b17e1e2a3c0.gif)

1

![](RackMultipart20230318-1-aqtmlv_html_3545cd70481371a7.png)

Figure (33)

 ![Shape119](RackMultipart20230318-1-aqtmlv_html_9498d18786cf46cc.gif) ![Shape121](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape120](RackMultipart20230318-1-aqtmlv_html_4848acd46a8e4dca.gif)

2

![](RackMultipart20230318-1-aqtmlv_html_f0db027a80d6ca7f.png)

Figure (34)

 ![Shape122](RackMultipart20230318-1-aqtmlv_html_9bebe184701dcc1c.gif) ![Shape123](RackMultipart20230318-1-aqtmlv_html_2d8837d0818024e7.gif) ![Shape124](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif)

3

![](RackMultipart20230318-1-aqtmlv_html_f5fe737674afef3b.png)

Figure (35)

 ![Shape126](RackMultipart20230318-1-aqtmlv_html_129ef8ab39a9043.gif) ![Shape127](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape125](RackMultipart20230318-1-aqtmlv_html_82b25b53430ce446.gif)

4

![](RackMultipart20230318-1-aqtmlv_html_e862901bf948409a.png)

Figure (36)

 ![Shape128](RackMultipart20230318-1-aqtmlv_html_d65f961d3d6cae6d.gif) ![Shape130](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape129](RackMultipart20230318-1-aqtmlv_html_9408201375b40cac.gif)

5

![](RackMultipart20230318-1-aqtmlv_html_4c1dc952f239f9be.png)

Figure (37)

According to step 6, first click on Internet Protocol Version 4 (TCP/IPv4) to make it blue, then according to step 7, click on Properties. (Figure 38)

![Shape135](RackMultipart20230318-1-aqtmlv_html_70c44777308c620f.gif) ![Shape136](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape133](RackMultipart20230318-1-aqtmlv_html_d18570ca85dffa93.gif) ![Shape134](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape132](RackMultipart20230318-1-aqtmlv_html_dc51bd079fd828c.gif) ![Shape131](RackMultipart20230318-1-aqtmlv_html_d8593796cc19b892.gif)

7

6

 ![](RackMultipart20230318-1-aqtmlv_html_5a85521defb75311.png)

Figure (38)

According to step 8, select "Use the following IP address". Then, enter the IP address used in the controller, which is 192.168.11.100, and the Subnet mask, which is 255.255.255.0. Finally, click OK (refer to Figure 39). Close any remaining open windows.

![Shape138](RackMultipart20230318-1-aqtmlv_html_129ef8ab39a9043.gif) ![Shape137](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape139](RackMultipart20230318-1-aqtmlv_html_8b4bfb558af7076c.gif)

8

 ![](RackMultipart20230318-1-aqtmlv_html_7d053659e05e7196.png)

Figure (39)

After setting the IP, a warning may appear from the Windows Firewall after running each of the Cam Pro programs (Cam Pro, Cam Pro Test, and Cam Pro Calibrator), indicating that the connection is being blocked. In this window, you are asked to allow communication through the network port. To do so, follow the steps in 9 and 10, tick the two options, and finally click the "Allow Access" button. This will allow Windows to communicate with the Cam Pro programs through the network port. (Refer to Figure 40)

 ![Shape142](RackMultipart20230318-1-aqtmlv_html_47bdc0aa2e55fb8a.gif) ![Shape147](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape141](RackMultipart20230318-1-aqtmlv_html_fdd848ba3e11056d.gif) ![Shape148](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape140](RackMultipart20230318-1-aqtmlv_html_4265f0ff02970958.gif) ![Shape146](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape145](RackMultipart20230318-1-aqtmlv_html_2e66d82e5451ea1c.gif) ![Shape144](RackMultipart20230318-1-aqtmlv_html_e14eba412f8f0353.gif) ![Shape143](RackMultipart20230318-1-aqtmlv_html_3d17ea43e17f319a.gif)

11

10

9

![](RackMultipart20230318-1-aqtmlv_html_2c94052f579d750b.png)

Figure (40)

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png) |
- If you did not correctly perform steps 9, 10, and 11, and the IP is blocked by the firewall or if an antivirus is installed on the computer and is blocking the connection between the controller and the computer, then follow the steps shown in Figures 41 to 49 in order to resolve the issue.
 |
| --- | --- |

![Shape149](RackMultipart20230318-1-aqtmlv_html_72d929330e7bc767.gif) ![Shape151](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape150](RackMultipart20230318-1-aqtmlv_html_11e5f594876b0703.gif)

1

 ![](RackMultipart20230318-1-aqtmlv_html_3545cd70481371a7.png)

Figure (41)

![Shape153](RackMultipart20230318-1-aqtmlv_html_625dd083199bdd1e.gif) ![Shape154](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape152](RackMultipart20230318-1-aqtmlv_html_5546c477a42b3898.gif)

2

 ![](RackMultipart20230318-1-aqtmlv_html_f5fa9cf5565e66e8.png)

Figure (42)

![Shape156](RackMultipart20230318-1-aqtmlv_html_129ef8ab39a9043.gif) ![Shape157](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape155](RackMultipart20230318-1-aqtmlv_html_ce32b56e37bd7887.gif)

3

 ![](RackMultipart20230318-1-aqtmlv_html_aad82bf66a0888cd.png)

Figure (43)

![Shape158](RackMultipart20230318-1-aqtmlv_html_625dd083199bdd1e.gif) ![Shape160](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape159](RackMultipart20230318-1-aqtmlv_html_d90caae427a9dbf8.gif)

4

 ![](RackMultipart20230318-1-aqtmlv_html_a69cbb56a66b8d4c.png)

Figure (44)

If the software appears in gray color in the "Allow a program or feature through Windows Firewall" environment, you will not be able to make changes. To be able to make changes, click on "Change settings" as shown in Figure 45. If the software appears in black color, this means you have the ability to make changes, so you can skip this step and do not need to follow step 5. (Refer to Figure 45)

![Shape161](RackMultipart20230318-1-aqtmlv_html_d3d4cd79580281.gif) ![Shape163](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape162](RackMultipart20230318-1-aqtmlv_html_dff3794566c9f932.gif)

5

 ![](RackMultipart20230318-1-aqtmlv_html_b37169a890a07343.png)

Figure (45)

If the Radonix software (RadCAM-Pro, RadonixPC-Pro Test, RadPC-Pro Calibrator) is not listed in the "Allow a program or feature through Windows Firewall" environment (refer to Figure 46), you need to follow steps 6 to 8 as shown in figures 46 to 48. However, if the software is already listed, you can skip these steps and do not need to perform steps 6 to 8.

 ![Shape164](RackMultipart20230318-1-aqtmlv_html_d3d4cd79580281.gif) ![Shape166](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape165](RackMultipart20230318-1-aqtmlv_html_97ccd1a1b74cd55a.gif)

6

![](RackMultipart20230318-1-aqtmlv_html_9ef9da2ede440ba8.png)

Figure (46)

In step 7, you should find Radonix files from the Browser section and add them to the list. (Figure 47)

 ![Shape167](RackMultipart20230318-1-aqtmlv_html_ac73ccde814dff6b.gif) ![Shape169](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape168](RackMultipart20230318-1-aqtmlv_html_a30ae4607e459352.gif)

7

![](RackMultipart20230318-1-aqtmlv_html_64cd703aa2c521f9.png)

Figure (47)

 ![Shape172](RackMultipart20230318-1-aqtmlv_html_e9cecfb8c57ec376.gif) ![Shape171](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape170](RackMultipart20230318-1-aqtmlv_html_8e550bdf857d1ed7.gif)

8

![](RackMultipart20230318-1-aqtmlv_html_28ea3eff9deed978.png)

Figure (48)

According to step 9, all squares within the box should be checked (ticked) and if a checkmark is missing, it should be added by clicking within the check box. (Refer to Figure 49 for visual reference).

 ![Shape173](RackMultipart20230318-1-aqtmlv_html_715d974903b9f1f4.gif) ![Shape174](RackMultipart20230318-1-aqtmlv_html_2162a8e41c5bc292.gif) ![Shape175](RackMultipart20230318-1-aqtmlv_html_919225b9087ed4f1.gif)

9

![](RackMultipart20230318-1-aqtmlv_html_7a2f4570d313b6da.png)

Figure (49)

Now you are able to launch the Radonix software.

| ![](RackMultipart20230318-1-aqtmlv_html_27fbaa5de77c667e.png) |
- If the CNC controller and computer are properly connected and the necessary power supply voltage is being supplied to the controller, the LAN connector LEDs on the controller should be either blinking or on. If these LEDs are off, it can be concluded that the cable connection between the controller and the computer is disconnected or there is an issue with the connector.
 |
| --- | --- |
