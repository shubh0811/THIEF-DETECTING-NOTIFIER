# THIEF-DETECTING-NOTIFIER

 #### Hi, Shubh this side, I am here to give a bit of description about the project that i made.
 
 #### Q)What is ESP8266 used for?
##### -The ESP8266 module enables microcontrollers to connect to 2.4 GHz Wi-Fi, using IEEE 802.11 bgn. It can be used with ESP-AT firmware to provide Wi-Fi connectivity to external host MCUs, or it can be used as a self-sufficient MCU by running an RTOS-based SDK
 
 
#### Q) What is the purpose of an infrared sensor?
##### -IR sensor is an electronic device, that emits the light in order to sense some object of the surroundings.An IR sensor can measure the heat of an object as well as detects the motion.
 
 #### -7805 Voltage Regulator, a member of 78xx series of fixed linear voltage regulators used to maintain such fluctuations, is a popular voltage regulator integrated circuit (IC). The xx in 78xx indicates the output voltage it provides. 7805 IC provides +5 volts regulated power supply.
 
 .                                                                                  
 
 👇                                                                                     
 ![Power Supply (3)](https://user-images.githubusercontent.com/79529647/122644262-ef1a1a00-d131-11eb-8c3c-31da8fc54f40.jpg)

#### Now let's about the power supply which is made for the project. With the use of a 9V Battery, IC7805 and a switch to control the flow of voltage. As said before 7805 is used so that only +5V is supplied a head , and battery for the supply.
### Here is the schematic of the supply.

![Schematic Of The Power Supply](https://user-images.githubusercontent.com/79529647/122650390-36170800-d150-11eb-9f0c-8ce8609476d2.png)

#### USB is B type who's positive is connected to the 3rd pin of the IC and negative is connected to 2nd pin of Switch.

👆                                       
👇                                                                     
![ESP8266 With IR Sensor (1)](https://user-images.githubusercontent.com/79529647/122650533-2ea42e80-d151-11eb-965e-ec24178d6413.jpg)                 

#### Here is the pic of ESP8266 connected with the IR sensor. GND is connected to GND and VCC to Vin, IR sensor's out pin is connected to D1 of ESP8266. 
### Here is the schematic:                                     

![Connection Picture (1)](https://user-images.githubusercontent.com/79529647/122650781-62338880-d152-11eb-9044-0b952a438ab2.jpg)

👆

### Here is the complete Picture of the Project:
https://github.com/shubh0811/THIEF-DETECTING-NOTIFIER/blob/master/Project%20Picture.jpg

## Observation:
#### As any obstacle blocks the IR sensor or someone tries to open the door of the room , a notification directly comes on the phone that someone has entered the room. 
 
 ### Here is the video of the project connected through the Charger: https://github.com/shubh0811/THIEF-DETECTING-NOTIFIER/blob/master/Testing%20By%20Connecting%20Through%20The%20Charger.mp4 
 ### Here is the video of the project connected through the Power Supply: https://github.com/shubh0811/THIEF-DETECTING-NOTIFIER/blob/master/Testing%20The%20Project.mp4
 
 
 
## Explanation:
#### Power Supply is connected to the ESP8266 to power it than it is connected to the IR sensor. 
#### Here is the Code of the Project: https://github.com/shubh0811/THIEF-DETECTING-NOTIFIER/blob/master/Code.txt
#### ESP8266 connects to the WIFI(just by writing the name and the pass of the WIFI in the code) and the Blynk app(through the Auth provided by the Blynk app) due to which it sends the notification on the Blynk app which is in phone.
#### According to the code as the IR sensor senses the obstacle it passes 1 through the output pin to the ESP8266 board. Now as the code says if their is 1 passed through the sensor than send the notification on the Blynk app.             
#### ESP8266 board could be dirrectly connected to the charger or the power supply about which i have already disscused. 
### The image of the Project when attached on the wall: https://github.com/shubh0811/THIEF-DETECTING-NOTIFIER/tree/master/Project%20On%20The%20Wall
### The image of the Project when put in the box: https://github.com/shubh0811/THIEF-DETECTING-NOTIFIER/tree/master/Project%20In%20The%20Box




### Here is the video of the project connected through the Charger: https://github.com/shubh0811/THIEF-DETECTING-NOTIFIER/blob/master/Testing%20By%20Connecting%20Through%20The%20Charger.mp4 
 ### Here is the video of the project connected through the Power Supply: https://github.com/shubh0811/THIEF-DETECTING-NOTIFIER/blob/master/Testing%20The%20Project.mp4
 
 
 
## Board used:
#### ESP8266
#### IR sensor

## COMPONENTS USED for the Power Supply:
#### 9V Battery 
#### Zero PCB 
#### IC 7805 
#### Switch
#### USB_B 
#### Jumper Wires



Took help from youtube videos!                               







 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 








