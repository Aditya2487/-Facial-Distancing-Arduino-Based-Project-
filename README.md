# -Facial-Distancing-Arduino-Based-Project-
A wristband that uses RFID sensors to alert the user whenever he or she tries to touch their face subconsciously.

*************************************************************************************************
Project By Aditya Agrawal
*************************************************************************************************

So the idea behind this is simple, we are using a RFID sensor which will be placed on the wrist band and a passive RFID tag placed inside the mask.
When your hand approaches your face, the tag and the sensor come in close proximity and hence the system alerts you. Since RFID tags are available in various form factors and sizes, it is easy to customize this project. For an example a tiny RFID tag fitted in an ear ring would also work like a charm.

The RFID Sensor we are using is the RC522 based RFID sensor which follows the SPI communication protocol and hence the pin connections to the arduino pro mini are :-

Sensor Pin   Pro Mini Pin

RST              9 
SDA(SS)         10
MOSI            11
MISO            12
SCK             13

The MP1854 Step Down Converter is used to bring down the voltage to 5V.
You can simply upload the code and make the pin connections as given in the circuit diagram. Fritzing files have also been attached.
