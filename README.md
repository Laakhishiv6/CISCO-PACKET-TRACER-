# EASY CISCO-PACKET-TRACER PROJECT-

This project is a network simulation of a smart city created using Cisco Packet Tracer. It includes key areas like homes, a cyber café, a hotel, and a college campus, each with its own network setup.The project helps understand how networks are built and managed in real-world scenarios.

Features:
Home Network: Basic setup with Wi-Fi and connected devices.
Cyber Café: Public network for secure internet access.
Hotel Network: Separate networks for guests and staff, including smart devices.
College Campus: Organized network with VLANs for staff, students, and administration.

Connections and Configurations for College Campus:
Connections and Components:
Routers , Switches, servers , computers , serial cable wires ,and printers 

STEP1: ASSIGN THE COMPNENETS IN THE WAY SHOWN IN THE FIGURE 
2911 ROUTERS , 3950-24 SWITCHES , SERVERS , 2960-24TT switches , 

FOR MAIN ROUTER USE 3950-24 SWITCH AND THE OTHER SWITCHES WILL BE 2960-24TT 
THE REST OF THE COMPUTERS AND PRINTERS ARE PRETTY OBVIOUS 
STEP2:
BEFORE CONNECTING MAIN ROUTER WITH CLOUD SERVER CHANGE THE DEVICE SETTINGS BY SWITCHING THEM OFF AND EXCHANGING FOR SERIAL CABLES , NOW CONNECT THE SERIAL CABLES 
REPEAT THE SAME STEP FOR HOSTEL ROUTER AS WELL
NOW AS YOU CAN SEE THE CONFIGURATIONS ARE STILKL INCOMPLETE 
STEP3:(for the configrations i had to take help from chatgpt)
WE ONLY HAVE TO DO CONFIGURATIONS IN 3 ROUTERS:MAIN ROUTER,CLOUD ROUTER,HOSTEL ROUTER BY CLICKING ON CLI COMMAND BAR 
REPEAT THE FOLLOWING COMMANDS FOR EACH OF THE 3 ROUTERS
->enable
->config t
->int gig0/0
->no sh
->int se0/1/0
->no sh
->do wr


THATS ALL YOU ARE READY TO GO 

Connections and Configuration for Cyber Cafe:
The connections include:
a router 
a switch
a single server 
and computer and printers as to your wish 
Building this was the easiest of all since all you have to do is :
STEP1:connect the router to switch 
STEP2: connect router to server
STEP3: connect the rest of the computers and printers to the switch without any configuartions


CONNECTIONS AND CONFIGRATION FOR SMART HOME:
Over here I used a bit a iot technology to incorporate a smart home feature 
COMPONENTS:
Homegateway
Motion Detector
Siren
Webcam
Tablet

STEP1:
FIRSTLY PLACE ALL THE COMPONENTS FROM THE  TOOL BOX IN THE BOTTOM OF CISCO PACKET TRACER . THE DEVICES WILL GET CONNECTED AUTOMATICALLY
STEP2:
IN HOME GATEWAY CLICK ON config>wireless 
check if authentication is disabled now go to global >settings
CHANGE THE NAME FROM DEFAULT TO HomeGateway of the device

STEP3:NOW CLICK ON  THE MOTION DETECTOR AND CLICK config>wireless0 .now overher make the SSID name to HomeGateway and then click global>settings
IN SETTING CHANGE THE IOT SERVER TO TO HomeGateway and close it

REPEAT THE SAME STEPS FOR WEBCAM AND SIREN AS WELL.









