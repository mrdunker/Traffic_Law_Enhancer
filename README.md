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

![Screenshot from 2023-10-02 21-43-33](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/1b7338a9-fee2-46db-98c2-405c6ebeb2e1)
            <br />Fig:(Transmission side circuit)<br />
<br />
![Screenshot from 2023-10-02 21-43-44](https://github.com/mrdunker/Traffic_Law_Enhancer/assets/38190245/ce5dc5a0-c66d-41d8-8e36-6f4e9cd032a8)
            <br />Fig:(Receiver side circuit)<br />



