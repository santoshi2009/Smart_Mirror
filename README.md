<img width="1598" height="875" alt="screenshot (1)" src="https://github.com/user-attachments/assets/8b1a8429-6ff6-4cbb-9ddf-14cb88185090" />## Smart_Mirror
 ## What is this project?
Ever wondered if our Mirror could show us date and time along with news. so i am trying to work on this only.So project i am building is a Smart mirror based on raspberry pi. Smart mirror can show  the date , time , greeting message .etc along with acting as mirror.

# Why am i building it?
So This is my first official hardware project. i am so excited for this .i wanted to build something which can help me learn hardware and engineering with linux environment as well. So i was looking for the project that teaches me both .So i decided to work on this Smart mirror based on raspberry pi .This smart mirror will help me start day more organized,show weather, calender etc .i had earlier decided to do the project but becasue of the lack of the sufficient material i was unable to make ..Thanks to hackclub for this Amazing concept to help the geeks to learn by providing guidance and grant. i am excited to work on this project so It would be great learning and fun working on this project.

## What will it show?(Features)
It will show :-

Greeting Message

Time

Date

Temperature

upcoming calendar events

News

more features can be added by including the api in it.


## Note
This project focuses on designing a complete smart mirror system, including hardware planning, CAD modeling, and software integration, rather than just setting up existing tools.I have made this project  on top of MagicMirror and customized for my use case.


## why I am using Raspberry pi and Display ?

### Raspberry Pi:
So i am using Raspberry pi in this project because the project runs the customized MagicMirror which depends on node.js and a full operating system. And i will be integrating the camera module for feaures like user detection smart interaction and and internet based customized APIs for weather and News, all of which requires higher processing power of Raspberry pi  and cannot be handled by Microcontoller like Arduino.

### Display:
Like i am using dipslay because it shows the interface behind the two-way mirror and is connected to raspberry pi that will act as the UI for the magic mirror and show the all the api's information , time and dates, weaether , etc . i will be not directly using the monitor as it is , we have to fit the display by removing all the other above covering of a monitor to fit inside the wooden frame i am going to make myself from ply that hold everything.

## What This project teaches me?
Well  i have never worked earlier into anything like this. This project teaches me a lot of things :- hardware assemmbly , software and then integrating hardware and software to make a complete smart system. It helps me learn How the Magic Mirror and pi works , how display & sensors is connected and works . One of the thing that helps me a lot is configurin gthe modules which helps me improve my problem solving skills and uderstand the system Design. i am really excited for the project now.

# Current stage
Currently i am designing and prototyping stage where i am exploring how i can build it in efficient manner.
I have now applied for the grant and waiting for it to get approved as soon as possible as it is makaing me very excited to work on.

# What Next 

After approval of the Grant i will first purchase all the components as soon as possible and then i will start build the wooden frame of the for the ply and then finally complete the project as mentioned  .
Well , i am not done learning yet.I am planing to improve this project by adding more interactive features like motion detection and camera-based functionality. I also want to refine the hardware design and make the system more practical and efficient for real world use. Additionally, I will continue improving the interface and overall performance.



## 3D CAD SCREENSHOTS
 <img width="1598" height="875" alt="screenshot (1)" src="https://github.com/user-attachments/assets/5d2bbaa3-1c10-466d-a7c4-16d551232722" />

<img width="921" height="783" alt="screenshot (3)" src="https://github.com/user-attachments/assets/8d7570e0-f5c2-48de-8205-fe911048eeb2" />
<img width="1463" height="879" alt="screenshot (2)" src="https://github.com/user-attachments/assets/e2683f08-ec03-40f8-89e9-d0d0d8833dfa" />

# Wiring Diagram:
 ![wiringIMage](https://github.com/user-attachments/assets/db3e959f-b065-4a9c-bd30-52dd03ec7b04)


# BOM

|ITEM NAME                                             |PRICE($)|SOURCE                          |PURPOSE                                                              |
|------------------------------------------------------|--------|--------------------------------|---------------------------------------------------------------------|
|LED Strips                                            | 5.96   | https://rebrand.ly/ami0tt0     | Outline of the Smart Mirror                                         |
|Raspberry Pi 5                                        |138     |https://rebrand.ly/2stj695      |Main controller of the Mirror                                        |
|Raspberry Pi 5 Official 27W with USB-C PC Power Supply|19      |https://rebrand.ly/907dm6z      |Giving power to the Raspberry pi 5                                   |
|Double Sided Tape                                     |0       |Already own                     |Sticking the Display in the mirror                                   |
|Two way Glass Mirror                                  |50      |Locally Purchasing              |Front facing to act as mirror                                        |
|Wooden Frame                                          |40      |locally Making myself by Plywood|Enclosure of the mirror                                              |
|Monitor LCD Display                                   |122     |https://rebrand.ly/1jtghre      |Display of the Project which will be placed in the back of the Mirror|
|HDMI to mini HDMI Cable                               |2.8     |https://rebrand.ly/kqwm4sh      |Connecting the monitor to the raspberry pi                           |
|Carpentry Tools(Hammer , Saw,etc)                     |0       |already own                     |Making the frame for the monitor                                     |
|Microphone                                            |0       |already own                     |adding voice module                                                  |
|Memory Card                                           |5       |will buy from local market      |for Operating system of raspberry pi                                 |
|Speakers                                              |0       |already own                     |For the audio output from the smart mirror                           |
|Total                                                 |382.76  |                                |                                                                     |


# How to use this project
 1. First of all, the user needs to install the nodejs in the system from the official website. i used magic mirror because it makes the module integration easier.
 2. Then user should clone the repository of magic mirror . Here is the  link -> [https://tinyurl.com/5n887fes)]
 3. Then user should copy the project files into the MagicMirror modules folder.
 4. Now Open the config.js file and add the module configuration.
 5. after that, Run the MagicMirror using the command:
   [npm run start]
 6. The smart mirror interface will appear on the screen.
 7. For best experience, run it in full screen or on a Raspberry Pi connected to a display behind a two way Mirror.




