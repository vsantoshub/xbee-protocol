<b> Xbee Generic Serial Protocol </b>
<br />
This project is under development. <br />
The objective of this project is to provide for the community a general-purpose serial protocol to use zigbee radios in transparent mode.<br />
Zigbee networks are well known to be reliable, and the module has relative low-cost to the benefits it offers.
<br />
<br />
Some technologies used are listed below. <br />
<br />
Hardware: <br />
+ Xbee S3B radio module <br />
+ Any microcontroller platform with a UART interface  <br />

User-Interface: <br />
+ C# interface developed with Windows Forms framework <br />
+ User-defined Serial Protocol <br />
<br /><br />

<b>User Interface </b>
<br />
Currently working features: <br />
+ Modules Search<br /><br />
The user can be tested with the "teste_ack.ptp" Docklight script. <br />
For example, to search for another xbee nodes in the network, the master sends a "KNOCK" command to the slaves and the slaves answer a "ACK" command to the master.