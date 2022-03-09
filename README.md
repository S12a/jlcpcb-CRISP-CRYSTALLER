# jlcpcb-CRISP-CRYSTALLER






  Project Report on CRISP CRYSTALLER


                                                                                         


 
				  	Contents

Chapter – 1 Introduction                                                                  
1.1 Problem statement
1.2 Introduction to the project
Chapter – 2 Architecture                                                                                                                              
2.1 Components
	2.1.1 Hardware
	2.1.2 Software
Chapter – 3 Working of the robot                                                                                            
3.1   Block Diagram
3.2   Basic idea
3.3   Heart of the Robot
3.4   Movement
3.5   Process of Cleaning
3.6   Dispensing of foam
3.7   Power source used
Chapter – 4 Experimental results                                                                                                      
4.1   Result
4.2   Future Enhancement
4.3   Conclusion

COMPONENTS USED

Fig.no	                          Figure name
1	Arduino Integrated Development Environment (IDE)
2	Proteus 
3	Fusion 360
4	Jump Wires
5	Plastic
6	Rubber pads
7	Wiper 
8	Foam 
9	Foam dispenser
10	Microfiber cloth (scrubber)
11	Roller 
12	Li-ion battery
13	Servo motor (MG995)
14	SG90s Servo motor
15	Stepper motor (NEMA-17, 17HS4401)
16	DC Motor
17	L298N Motor Driver
18	A4988 Stepper Motor Driver
19	Ultrasonic sensor
20	DHT-11 sensor
21	DS18B20 temperature sensor
22	Arduino Uno
23	Arduino Mega2560
24	Bread Board



THE PROBLEM:
When it comes to high rise buildings with glass facades, there comes a problem in maintenance and cleaning of glass facades using human labour. Using humans for cleaning the glass facades at high altitudes is a difficult, requires professionals and is a dangerous task.

THE TEAMS APPROACH TO THIS PROBLEM: Since using humans is risky for cleaning high rise buildings glass facades, robots make a great replacement for this task. Using self-navigating and cleaning robot for glass facades makes the maintenance easy and allows no human loss or injuries. 
![image](https://user-images.githubusercontent.com/92536200/157374084-1e269166-5d54-450b-817f-13adb97cbfa5.png)


https://jlcpcb.com/rel




Software List:
S.no	              Components 
1	Arduino Integrated Development Environment (IDE)
2	Proteus 
3	Fusion 360

Description:
2.1.2 Software:
1.	Arduino Integrated Development Environment (IDE): Arduino IDE is an open-source cross platform application. This is written in C, C++, and java languages. This is used to write and upload programs to Arduino compatible boards.


![image](https://user-images.githubusercontent.com/92536200/157373161-93ba4753-24ec-4080-b5b6-12a8c5a4d100.png)


                                
              Fig 1.  Arduino IDE

2.	Proteus: Proteus Design Suite software is primarily used for electronic design automation. This software is mainly used to create schematic and electronic prints.

                        ![image](https://user-images.githubusercontent.com/92536200/157373180-d8b32e39-6c58-4e8d-96df-23ad11bd1db5.png)

                    Fig 2. Proteus

3.	Fusion 360: Fusion 360 is a cloud-based 3D CAD, CAM, and CAE design tool from Autodesk. It is the tool for collaborative product development that combines industrial design, mechanical engineering, and machine tool programming into one software solution    
4.	     ![image](https://user-images.githubusercontent.com/92536200/157373221-43d9b76c-cdc6-4ae0-82d9-13f64db65c68.png)
         
                        Fig 3 fusion 360
Hardware:

1.	Jump Wires: Jump Wires are used to connect components on a bread board or other circuit boards without the use of soldering method. This jump wires are also called as jumper wires. These wires have a connector or pin at its end, which is used for interconnection of components.
2.	![image](https://user-images.githubusercontent.com/92536200/157373257-4dc29388-fbf1-4863-9210-4cc665e27fd4.png)

                                     
         Fig 4. Jump Wires  

2.	Plastic: We use plastic for our “CRISP CYRSTALLER”, because using plastic makes the bot to feel less weight as compared to metal bodies. These plastic bodies give the perfect support to the other components in the bot. The ‘links’ and ‘joints’ used in the bot are also of plastic materials.
 ![image](https://user-images.githubusercontent.com/92536200/157373271-da0c2470-d141-44db-a169-db8c45cf2514.png)

                    Fig 5. Plastic

3.	Rubber pads (Geckos shoes): These shoes are used to climb the glass surface easily with less power consumption. These rubber pads have a tiny hair like structure at the bottom of their feet known as setae. These setae create vacuum in between them to get perfect attraction between glass and pads.
![image](https://user-images.githubusercontent.com/92536200/157373294-08bac326-cde3-47c9-b078-63dadb10595a.png)

 
              Fig 6.  Rubber pads
4.	Wiper: Wiper is generally used to remove the water marks and the patches created on the glasses while cleaning process. Wiper is used in our bot to remove the foot prints made by the rubber pads on the glass while cleaning the glass surface.
 ![image](https://user-images.githubusercontent.com/92536200/157373317-c0444d68-bcaf-47e1-9547-36a340428c84.png)

           Fig 7. Wiper
5.	Foam dispenser: Foam dispenser is used to convert soap liquid directly into the foam with the spring action involved in it. This spring is also called as spring pump which makes the soap liquid to mix with air and form foam.
                                  
![image](https://user-images.githubusercontent.com/92536200/157373330-ac9b935c-b3dd-40da-8de8-773b2575c4d4.png)



 
       Fig 9.  Foam dispenser
6.	Roller: Roller is used to spread the released foam onto the glass surface thoroughly. It makes the glass surface wet which helps in cleaning glass surface.
 ![image](https://user-images.githubusercontent.com/92536200/157373352-8689bdbf-c286-4054-aaaf-292e61fe25de.png)

           Fig 11.  Roller
7.	Li-ion Battery: We use Lithium ion battery in our project. It is a rechargeable battery and it has a capacity to full charge in 90 minutes. It requires low maintenance. It has a long life with full capacity for up-to 1000 charge cycles. It has higher discharging current of 4200mA. It weights nearly 41 grams.
                   ![image](https://user-images.githubusercontent.com/92536200/157373376-12bd37e3-1a86-4cbe-8184-acda01db343a.png)
                      
   Fig 12. Lithium-ion Battery 

8.	Servo Motor: Servo Motor is also called as Servos. It rotates at an angle of 0 to 180 degrees. It can also rotate in clock and anti-clockwise direction. Servo library supports 12 motors on UNO and 48 motors on Mega. It consists of gears, circuits and potentiometer. 
 ![image](https://user-images.githubusercontent.com/92536200/157373398-a2392061-572a-4122-98e6-4d164f6f42f7.png)

  Fig 13.Servo Motor (MG995)

9.	SG90s Servo Motor: We use SG90s in our bot. It is a light weight servo motor with high output power. Its operating speed is 0.1s/60degrees. It can rotate up-to 180 degrees.
 ![image](https://user-images.githubusercontent.com/92536200/157373416-6fe32f5b-8dcb-4c4d-86e9-87b999c8ac18.png)

    Fig 14. SG90s Servo Motor

10.	DC motor: The DC motor is a device which converts direct electrical energy into mechanical energy. 
 ![image](https://user-images.githubusercontent.com/92536200/157373442-3eaa73e8-f129-4c79-a7fb-af788cfbc35a.png)

          Fig 16.  DC motor

11.	L298N Motor Driver: The L298N Motor Driver Module is a high power motor driver module for driving DC and Stepper Motor. This module consists of an L298 motor driver IC and a 78M05 5V regulator.
![image](https://user-images.githubusercontent.com/92536200/157373460-b54b6dde-02cc-4019-9fe1-cd40953c5ee5.png)

 
   Fig 17.  L298N Motor Driver 

12.	Ultrasonic Sensor: An Ultrasonic Sensor is an electronic device that measures the distance of an object by emitting ultrasonic sound waves, and converts the reflected sound into electrical signal.
 ![image](https://user-images.githubusercontent.com/92536200/157373477-08bd4e3e-221c-4ee7-9f9c-f21ccc38ce58.png)

 Fig 19. Ultrasonic Sensor (HC-SR04)

13.	DHT-11: The DHT-11 is a Temperature and Humidity sensor. This sensor gives the digital signal and takes analog signals from the environment. The pins of the sensor should be connected to digital i/o of Arduino.
 ![image](https://user-images.githubusercontent.com/92536200/157373498-3db1131a-e37c-4cc0-b428-fa3a29fe0c78.png)

              Fig 20. DHT-11 sensor

14.	DS18B20(Temperature): The DS18B20 is a 1-wire programmable temperature sensor. It is used to measure temperature in hard environments. The maximum and minimum temperature measurements are -55 to 125C.
 ![image](https://user-images.githubusercontent.com/92536200/157373512-811759b5-1386-4a0b-96b2-7bf6723f2f62.png)

 Fig21.DS18B20 Temperature sensor
                                       
15.	Arduino Uno: Arduino Uno is an open source microcontroller board based on Microchip ATmega328P microcontroller. The board contains 14 digital pins and 6 analog pins and is programmable with Arduino IDE.
 ![image](https://user-images.githubusercontent.com/92536200/157373547-78bb1835-2054-44ef-95ee-ad436aa2a333.png)

             Fig 22. Arduino Uno

16.	Arduino Mega2560: The Arduino Mega2560 is a microcontroller board based on ATmega2560. The board has 54 digital pins and 16 analog pins.  
![image](https://user-images.githubusercontent.com/92536200/157373564-f09a7cd1-1a25-4601-afd9-56bf288ca302.png)

 
               Fig23.ArduinoMega2560


17.	Bread Board: Bread Board is a plastic board with a bunch of tiny holes in it. These holes are used to connect the components in it. This breadboard is also called as solder less board because they do not require soldering to make connections. 

 ![image](https://user-images.githubusercontent.com/92536200/157373599-df7781d3-a8e9-4a82-b7a0-71d08f9a016f.png)

           Fig 24. Bread Board

         
         
WORKING OF THE ROBOT

BLOCK DIAGRAM:


![image](https://user-images.githubusercontent.com/92536200/157373623-2d45b976-6f55-4b7d-947c-1b968616a75c.png)

 
 BASIC IDEA: 
Initially the bot is fixated onto a glass window with the help of adhesive pads acting as feet to the bot. The bot then divide’s the glass into 9 equal partition in the form of a grid according to the glass’s dimensions. This grid consists of 3 rows and 3 columns. The bot cleans each column starting from left to right by spraying foam, cleaning with roller and finally wiping with wiper. The bot moves to the next glass  and repeats the above procedure.
3.3 Heart of the robot:
•	The heart consists of the roller, foam container with dispenser, wiper(extended), IR sensor and development boards with power source.
•	When the bot starts to function, the foam dispenser spray’s out foam onto the glass.
•	The roller then spreads and cleans the window with the rolling action.
•	Finally when the bot moves down on a column of the window, the dampness and the foot prints are wiped away with wiper which is attached to the heart of the bot.
•	Wiper is adjustable and detachable manually so that the operator can adjust it according to the dimensions of the window. The length of the wiper is slightly greater than the heart of the bot. 
•	Here when the bot reaches the final glass of the building it has to detect with the help of IR sensor and make a 1800 turn and proceed to the next window.
3.4 Movement:
•	When the bot is placed on the mirror, it gets attached with e adhesive pads.
•	These adhesive pads are attached to the extendable arms which are controlled with the help of stepper motor.
•	So the path of the bot is decided by the user with the help of SLAM technology.
•	And when the bot reaches the lowest point on a building it has to take a 1800 turn so that the sequence of cleaning doesn’t change.
3.5 Process of cleaning:
1.	Bot is placed on the glass and is adjusted according to the dimensions of the glass window.
2.	Each and every column is cleaned by first spraying the foam from the foam dispenser and applied onto the glass surface with constant rolling action of roller and finally the wiper touches the surface firmly and start’s to wipe the whole column as the bot goes down and lifts up for a few centi-meters. This process is repeated for each column.
3.	It cleans the first column that is on the left side by fixing the legs on other two columns firmly and placing the body on the left.
4.	And middle column is cleaned by keeping the body in the middle and placing the legs on other two columns.
5.	It cleans the last column that is on the right side by fixing the legs on other two columns firmly and placing the body on the right. 
6.	It moves to the next glass which is below with the help of legs. While moving to the next glass the wiper placed behind the whole body lifts up for a few centi-meters for easy movement. 
3.6 Dispensing of foam:
•	The foam container is fixed on the heart of the bot which is replaceable for refilling purpose.
•	Here we use gas propelled dispenser cylinders so that whenever the foam is completed the cylinder can be replaced easily.
•	And the spray control of the foam is done by twisting the nozzle so that different area and quantity of foam is sprayed onto the glass depending upon the users choice (Ex: colin glass cleaners have adjustable nozzle so that the area and quantity of spray is controlled by twisting it easily).
•	And servo motors are used for pressing action of the nozzle.
3.7 Power source used:
•	Battery used is a lithium-ion battery of 3.7V and 2200mah discharge current.
•	These are rechargeable where maximum charging voltage is 4.2V and charging current is 4200mah.
•	We are using this particular battery because it has higher discharge current and charge cycles upto 100 times.
•	The time taken for single complete charge is 90mins.




EXPERIMENTAL RESULTS
1 RESULT:
This robot will clean the glass facades
Neatly using foam , scrubber and a wiper
This robot does not leave any kind of impressions on the glass. It automatically 
Adjust to the size of glass and work accordingly


2  FUTURE ENHANCEMENT:
	In future we can add a power backup  through solar panels so as to charge the battery while it is working .
	Mapping technology can also be used  so that we clean our glass in our required path according to shape our glass
	We can add weather sensor, to estimate 
weather and indicate to users. if there is any chances of rain then robot may looseany chances of rain then robot may loose its grip ,so to avoid it this sensor is used.

SOURCE CODE

#include<Servo.h>
#include<SoftwareSerial.h>
SoftwareSerial softserial( 8, 9);
int trigger=0 ;
int echo= 1;
Servo sv1;
Servo sv2;
Servo sv3;
Servo sv4;
Servo sv5;//for 1,2
Servo sv6;// for 3,4
void left_cleaning(){
  for(int i=0;i<180;i++){
    sv2.write(i);
    sv4.write(i);
    sv5.write(i);
    sv6.write(i);
    if(i<100){
      sv1.write(i);
      sv3.write(i);
    }
  }
}
void right_cleaning(){
  for(int i=0;i<180;i++){
    sv1.write(i);
    sv3.write(i);
    sv5.write(i);
    sv6.write(i);
    if(i<100){
      sv2.write(i);
      sv4.write(i);
    }
  }
}
void middle_cleaning(){
  for(int i=180;i>0;i--){
    sv1.write(i);
    sv2.write(i);
    sv3.write(i);
    sv4.write(i);
    sv5.write(i);
    sv6.write(i);
  }
}

void setup() {
  sv1.attach(3);
  sv2.attach(5);
  sv3.attach(2);
  sv4.attach(10);
  sv5.attach(11);
  sv6.attach(6);
 pinMode(trigger,OUTPUT);
 pinMode(echo,INPUT);
softSerial.begin(9600);
}

void loop() {
  digitalWrite(trigger, LOW);
delay(20);
digitalWrite(trigger, HIGH);
delay(10);
digitalWrite(trigger, LOW);
if(digitalRead(echo)==0){
  left_cleaning();
  if(Serial.available()){
    softSerial.write(1);
  if(softSerial.read()==2){
  middle_cleaning();
   softSerial.write(1);
 }
  if(softSerial.read()==2){
  right_cleaning();
  softSerial.write(1);
}
}
}

#include<Servo.h>
#include<Stepper.h>
#include<SoftwareSerial.h>
SoftwareSerial softSerial( 8, 9);
int steps=2048,mspeed=10;
int c=0;
Stepper mystepper(steps,44,45,46,47);
Servo sv7;
Servo sv8;
Servo sv9;
Servo sv10;
void wiper(){
for(int i=0;i<180;i++){
  sv7.write(i);
  sv8.write(i);
}
  delay(5000);
}
void foam(){
  for(int i=0;i<90;i++)
sv9.write(90);
  
}
void roller()
{
  for(int i=0;i<90;i++)
  sv10.write(i);
  delay(5000);
}
void stepper_right(){
  for(int i=0;i<steps;i++)
  mystepper.step(steps);
}
void stepper_left(){
for(int i=0;i<steps;i++)
  mystepper.step(-steps);
}
void setup() {
  
sv7.attach(12);
  sv8.attach(13);
  sv9.attach(11);
  sv10.attach(10);
softSerial.begin(9600);

}

void loop() {
  if(Serial.available()){
    if(softSerial.read()==1){
      foam();
      roller();
      wiper();
      stepper_right();
      softSerial.write(2);
    }

                                               

RECORD OF EXPENSES


SI.
NO.	Components	Cost
1.	Servo motor(MG996R)	503
2.	Stepper motor(NEMA-17,17HS4401)	951
3.	DC Motor	60
4.	Shoes	
5.	Joints and links	
6.	Arduino UNO	1200
7.	Arduino MEGA 2560	699
8.	DC Motor driver-L298N	385
9.	Stepper Motor driver -A4998	229
10.	Scrubber	35
11.	Wiper	360
12.	Foam dispenser	500
13.	DHT-11	75
14.	DS18B20 (Temperature)	210
15.	Ultrasonic (HCSR04)	227
TOTAL	






 





                            












 

