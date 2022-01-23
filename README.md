# Smart-Farm
This Project shows how to make a Smart Farm

Parts Needed And Their Connections
NodeMCU(any development board with wifi module)-connect to breadboard
Breadboard-connect NodeMCU board on it
Buzzer-connect to D8 pin in NodeMCU
LED-connect to D3 pin in NodeMCU
PIR Sensor-connect to D7 pin in NodeMCU
Rain Sensor-connect to D0 pin in NodeMCU
DHT11 sensor-connect to D4 pin in NodeMCU
Soil Moisture Detecting Sensor-connect to A0 pin in NodeMCU
Jumper Cables-use to connect sensors 

Frist create your own thingspeak account.
Next create your own channel (You Can Get Help From Screenshots in Folder).
Download Libraries(copy DHT11 folder and paste it on your libraries folder in arduino folder do same thing to ThingSpeak folder and ESP8266wifi-master folder)
(I think Arduino folder Was located in Documents in all windows PCs).
Open Arduino code(open SMART FARM folder and double click on smartfarm.ino file).
Change My Channel Number and My Write API Key (You Can Get Help From Screenshots in Folder).
Change ssid and password.
Choose your iot board(here I am using NodeMCU 12E Module You can choose your board.If you have a wemos you have to select wemos).
Select the port and upload the code.
Open Serial Monitor and Thingspeak channel.
