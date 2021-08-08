# THIEF-DETECTING-NOTIFIER

 #### Hi, Shubh this side, I am here to give a bit of description about the project that i made.
 
 ## ABOUT THE PROJECT
 #### We have made this project so that if someone enters our room we could immediately get a notification on our mobile phone for the security purposes. We have used ESP8266 board and an Infrared Sensor. If any obstacle blocks the IR sensor or someone tries to open the door of the room , a notification is sent to the phone saying that someone has entered the room.
 
 ## REASON WHY WE MADE THIS PROJECT
####  As the thefts are increasing day by day, it is necessary to be precautious about it. And hence, we have made this project as a precautionary step.

 
 #### Q)What is ESP8266 used for?
##### -The ESP8266 module enables microcontrollers to connect to 2.4 GHz Wi-Fi, using IEEE 802.11 bgn. It can be used with ESP-AT firmware to provide Wi-Fi connectivity to external host MCUs, or it can be used as a self-sufficient MCU by running an RTOS-based SDK
 
 
#### Q) What is the purpose of an infrared sensor?
##### -IR sensor is an electronic device, that emits the light in order to sense some object of the surroundings.An IR sensor can measure the heat of an object as well as detects the motion.
 ## ESP8266 with IR sensor
 # 👇                                                                     
![ESP8266 With IR Sensor (1)](https://user-images.githubusercontent.com/79529647/122650533-2ea42e80-d151-11eb-965e-ec24178d6413.jpg)                 

#### Here is the picture of ESP8266 connected with the IR sensor. GND is connected to GND and VCC to Vin, IR sensor's out pin is connected to D1 pin of ESP8266. 
### Here's the schematic:                                     

![Connection Picture (1)](https://user-images.githubusercontent.com/79529647/122650781-62338880-d152-11eb-9044-0b952a438ab2.jpg)

# 👆                                                                                                                                                   

                     
                     
                     
                     
## POWER SUPPLY FOR THE PROJECT
#### Now let's about the power supply which is made for the project. IC 7805 and a switch to control the flow of voltage. As said before IC 7805 is used so that only +5V is supplied a head , and battery for the supply. To power the ESP board we have made this simple +5V power supply.


### IC 7805
 #### IC 7805 Voltage Regulator, a member of 78xx series of fixed linear voltage regulators used to maintain such fluctuations, is a popular voltage regulator integrated circuit (IC). The xx in 78xx indicates the output voltage it provides. 7805 IC provides +5 volts regulated power supply.
### COMPONENTS REQUIRED FOR POWER SUPPLY:
 # 👇                                                                                     

![image](https://user-images.githubusercontent.com/79529647/128630536-8c7e24dd-b95b-4ccd-bb24-351544ed80aa.png)
#### Ic 7805 ,9V battery with connector ,Switch ,Zero PCB, USB_B/Micro USB , Jumper wires. These are the few components required to make power supply. 
# 👆                                       

### CONNECTIVITY OF THE POWER SUPPLY:
 .                                                                                  
 
 # 👇                                                                                     
 ![Power Supply (3)](https://user-images.githubusercontent.com/79529647/122644262-ef1a1a00-d131-11eb-8c3c-31da8fc54f40.jpg)


### Here is the schematic of the supply.

![Schematic Of The Power Supply](https://user-images.githubusercontent.com/79529647/122650390-36170800-d150-11eb-9f0c-8ce8609476d2.png)

####  I gave connected 9V battery to first pin of the IC so that we could get +5V from the third pin. I have connected a switch in it so that the voltage is only forwarded when its required. The USB which gets connected to the ESP board is of B type/Micro USB. 
# 👆                                       
### OTHER WAYS TO POWER ESP8266 BOARD:
#### 1. Through Charger
#### 2. Through Power Bank

### Here is the complete Picture of the Project:
https://github.com/shubh0811/THIEF-DETECTING-NOTIFIER/blob/master/Project%20Picture.jpg








## VOICE MODULE FOR THE PROJECT
![image](https://user-images.githubusercontent.com/79529647/128633713-3336e8f7-0013-401b-89dc-32a710dacaf3.png)
#### The IC 1820 records the voice and plays it whenever asked. The module is placed behind the door so as the door opens the module starts working and play’s the sound which is already recorded in it. Due to this the thief will run away and the family members will be alert. 

### COMPONENTS REQUIRED FOR VOICE MODULE
 # 👇                                                                                     

![b](https://user-images.githubusercontent.com/79529647/128634622-6122ce91-fe80-4d23-85a1-e11058de04ad.jpg)    
#### Components Required are- ISD 1820 ,Speaker, 4V Battery, Mic, Switches, few Resistors, LED's, Ceramic Capacitors, Capacitors.
# 👆                                       

### Schematic OF VOICE MODULE
 # 👇                                                                                     

![image](https://user-images.githubusercontent.com/79529647/128634914-b4c760b0-1e7d-423e-a0f2-e0ccaef6d2d4.png)
# 👆                                       

### WHY VOICE MODULE IS NECESSARY
#### 1. If some how the ESP board doesn’t work.
#### 2. The thief will runaway after hearing such loud noise.




## Steps followed in BLYNK App
 ## 👇                                                                                     
![c (1)](https://user-images.githubusercontent.com/79529647/128635884-6583832b-df0a-42a5-b366-df44fa7d735e.jpg)
#### Just after signing in to Blynk this interface is faced. Name the project than choose the board which is getting used. 
## 👆     

 ## 👇           
![d (1)](https://user-images.githubusercontent.com/79529647/128636044-d734a37b-92d0-4cb4-8353-bbbde5a828b4.jpg)
#### Here we will get the auth which have to uploaded in the code. Email it or copy it. 
## 👆     
 ## 👇           
![e (1)](https://user-images.githubusercontent.com/79529647/128636116-fa98960e-e008-402d-b813-13f5f116160c.jpg)
#### We will choose the notification option just because we want to receive a notification from the ESP board.
## 👆     

 ## 👇           
![f](https://user-images.githubusercontent.com/79529647/128636189-7335f6c8-d7de-47ac-bc2f-10b3a5cb4c14.jpg)
#### Now the Blynk app is ready to work.
## 👆     




## CONNECTING TO WIFI
![g](https://user-images.githubusercontent.com/79529647/128636317-0069ba95-d21f-4adb-ad9f-1882a47cc40b.jpg)
#### When ever our ESP board is not connected to any Wifi than we will find this option Autoconnect in the setting(Wifi).
![h](https://user-images.githubusercontent.com/79529647/128637089-76f0b05d-fd15-49a6-9885-9d2da09a0db7.jpg)
#### So by just clicking to that(Autoconnect) we will get this interface. Write the credentials of Wifi and the ESP8266 will be connected to the wifi.






## Observation:
#### As any obstacle blocks the IR sensor or someone tries to open the door of the room , a notification directly comes on the phone that someone has entered the room. 
 
 ### Here is the video of the project connected through the Charger: https://github.com/shubh0811/THIEF-DETECTING-NOTIFIER/blob/master/Testing%20By%20Connecting%20Through%20The%20Charger.mp4 
 ### Here is the video of the project connected through the Power Supply: https://github.com/shubh0811/THIEF-DETECTING-NOTIFIER/blob/master/Testing%20The%20Project.mp4
 
 
 
## Explanation:
#### Power Supply is connected to the ESP8266 to power it than it is connected to the IR sensor. 
#### Here is the Code of the Project: https://github.com/shubh0811/THIEF-DETECTING-NOTIFIER/blob/master/Code.txt
#### ESP8266 connects to the WIFI(through phone) and the Blynk app(through the Auth provided by the Blynk app) due to which it sends the notification on the Blynk app which is in phone.
#### According to the code as the IR sensor senses the obstacle and it passes 1(voltage) through the output pin to the ESP8266 board. Now as the code says if their is 1 passed through the sensor than the ESP board will send the notification on the Blynk app which is in my phone.             
#### ESP8266 board could be directly connected to the charger or the power supply about which i have already discussed. 
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







 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 








