# Traffic_Law_Enhancer
This is a Vehicle in built module to find speed violations in designated areas.<br />
AS PER KERALA POLICE RECORDS: 40,181 accidents were reported in 2018.<br />
State of Kerala witnessed an increase of 3.86 per cent in accidents in 2018.<br />
Accident death rates are 10:1 for only speed violation causes.<br />

![image](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/81b13b21-3cab-44f5-94c4-dd43bd14bcea)
<br />
The graph above shows the statistics of road accidents in Kerala for around 18 years till 2018 and it was shocking.<br />
The table below shows the classifications of accidents in the year 2018.Hence there was a very much requirement of traffic rule monitoring.<br />
Now with the development of AI cameras that can detect weather a driver is wearing a passenger is wearing a seatbelt or not,There is a requirement of monitoring the speed of vehicles so as to decrease accidents.<br />

![image](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/19e95666-7779-4a1d-afd3-6662b53b8cdd)
<br />
Hence the idea of **Traffic Law Enhancer** a Vehicle in built module to find speed violations(in designated areas) came into thought.<br />

## Current System
<br />

The speed violation regulation systems currently used are surveillance cameras, traffic enforcement speed cameras, and radar speed gun, interceptor units.These systems are those which have been used for some time and must be updated for decreasing the accident rates. The surveillance cameras are cameras that can only be used to monitor the roads and review and see in case if any accidents occur in front of the camera. Traffic monitoring cameras typically sit on top of traffic lights and monitor traffic flowing through an intersection or on the highway. They do not take pictures of vehicles that over speed.<br />

## METHODOLOGY Adopted
<br />

The proposed system mainly comprises of a Global Positioning System (GPS) Receiver equipped with Global System for Mobile Communication (GSM), and microcontroller. The proposed work is going to be an effort to control and regulate the speed of the vehicles augmented with computer software to enable the third party or owner/supervisor to know the location, speed and activity of the driver. The system will transmit information in real time. The use of GSM/GPRS technologies will allows the system to track the objects and provide the up to-date information. The proposed equipment/device will compare the present position and speed of the vehicle with applicable traffic rules and on occurrence of any violation, will caution the driver and will also send the violation information to the supervising authorities.<br />
<br />
This device consists of mainly two parts, a transmitter side that mainly consists of GPS, GSM and Arduino mega and a receiver side with GSM, Arduino uno and a display system. In the transmitter side the Arduino continuously checks the location and speed limit of the location with respect to the data it receives from the GPS and the speedometer. If the vehicle violates speed limit of a particular location a message is send to the transmitter side through the GSM module with information such as location,time, date and speed at which the vehicle was moving. On the receiver it receives the information through the GSM module in the receiver side and process the data using Arduino uno and display the information.<br />
<br />
![image](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/c0bc8be1-597f-46f8-b257-4c803a144025)
Fig(Prototype:Initial stage)

## Block Diagrams

![Screenshot from 2023-10-02 21-43-33](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/f2c55b19-e8ab-4719-b2af-e1d8d6bb6ce4)
            <br />Fig:(Transmission side circuit)<br />
<br />

![Screenshot from 2023-10-02 21-43-44](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/2f8aa77d-4d56-4c02-bf11-4d24d5907717)
               <br />Fig:(Receiver side circuit)<br />


## Components Used

### ARDUINO MEGA 2560
<br />
The Arduino Mega 2560 is a microcontroller board based on the ATmega2560. It has
54 digital input/output pins (of which 14 can be used as PWM outputs), 16 analog
inputs, 4 UARTs (hardware serial ports), a 16 MHz crystal oscillator, a USB
connection, a power jack, an ICSP header, and a reset button. It contains everything
needed to support the microcontroller; simply connect it to a computer with a USB
cable or power it with an AC-to-DC adapter or battery to get started. The Mega 2560 is
an update to the Arduino Mega.
<br />

![Screenshot from 2023-10-03 18-06-47](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/383d038f-2e25-43a6-a9a2-9e27d64896d7)


### ARDUINO UNO
<br />
The Arduino UNO is an open-source microcontroller board based on the Microchip
ATmega328P microcontroller and developed by Arduino.cc. The board is equipped
with sets of digital and analog input/output (I/O) pins that may be interfaced to various
expansion boards (shields) and other circuits. The board has 14 Digital pins, 6 Analog
pins, and programmable with the Arduino IDE (Integrated Development Environment)
via a type B USB cable. It can be powered by a USB cable or by an external 9 volt
battery, though it accepts voltages between 7 and 20 volts. It is also similar to the
Arduino Nano and Leonardo. The Uno board is the first in a series of USB Arduino
boards, and the reference model for the Arduino platform. The ATmega328 on the
Arduino Uno comes pre-programmed with a bootloader that allows uploading new code
to it without the use of an external hardware programmer. It communicates using the
original STK500 protocol.<br />

![Screenshot from 2023-10-03 18-08-03](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/eb5ab879-3615-4b81-aa90-70a673eb727f)


### SIM 900A GSM Module
<br />
This is an ultra-compact and reliable wireless module. The SIM900A is a complete
Dual-band GSM/GPRS solution in a SMT module which can be embedded in the
customer applications allowing you to benefit from small dimensions and cost-effective
solutions. Featuring an industry-standard interface, the SIM900A delivers GSM/GPRS
900/1800MHz performance for voice, SMS, Data, and Fax in a small form factor and
with low power consumption. With a tiny configuration of 24mm x 24mm x 3 mm,
SIM900A can fit almost all the space requirements in your applications, especially for
slim and compact demand of design.<br />

![Screenshot from 2023-10-03 18-09-24](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/fe06a8ba-93d4-4c23-a00d-9ea4d9e6a453)

![Screenshot from 2023-10-03 18-09-53](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/a57b2cc5-7a1d-488e-838f-7780cc006c3b)


### NEO 6M GPS Module
<br />
The NEO-6 module series is a family of stand-alone GPS receivers featuring the high
performance u-blox 6 positioning engine. These flexible and cost effective receivers
offer numerous connectivity options in a miniature 16 x 12.2 x 2.4 mm package. Their
compact architecture and power and memory options make NEO-6 modules ideal for
battery operated mobile devices with very strict cost and space constraints.<br />

![Screenshot from 2023-10-03 18-10-44](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/dccdbc14-c784-4135-8286-7d1963656a3d)


## Logic Working

### FlowChart

**Transmission side:**

<br />

![Screenshot from 2023-10-03 18-12-23](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/f2783cdd-b220-45ea-9ea1-613c3cc407a8)
<br />
![Screenshot from 2023-10-03 18-12-34](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/eb82f12b-175e-45a6-b1d4-43212faed84b)
<br />
<br />
**Receiver side:**
<br />

![Screenshot from 2023-10-03 18-13-56](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/9a608f98-dc12-4862-85cb-0ca9f18829aa)

<br />

### Logic:
<br />
At transmitter part the process begins with the initialization of the input output
ports, GSM module, GPS module. The real time speed of the moving vehicle is tracked
continuously. A predefined minimum speed value and maximum speed value is
determined. If the speed of the vehicle is less than that of the predefined minimum
value, then no need of checking violation. If the speed of vehicle is greater than the
predefined maximum value it results to violation and send message to the receiver
server irrespective of the location. If the speed of the vehicle is in between the data is
always compared with the database data by fetching it. If the over speeding occurs the
violation message is send to the receiver server. The process continues occur as a loop
function.<br />
The receiver consists only a core processor and a GSM module, so here the
process is much simpler. The process begins with initialization of input output ports
and GSM module. The message received from the transmitter is received if a violation
occurs.<br />

## Acknowledgement

1. Arun P.S,College of Engineering,Chengannur
2. Deepak D,College of Engineering,Chengannur
3. Muhammad Shibili M.H,College of Engineering,Chengannur


