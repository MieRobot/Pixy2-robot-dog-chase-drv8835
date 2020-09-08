# Pixy2-robot-dog-chase-drv8835

![Chase robot Image 2 ](https://github.com/MieRobot/Pixy2-robot-dog-chase-drv8835/blob/master/Pixy2%20Chase%20robot.jpeg)
This is a simple implementation of the chase mode with pixy2 along with DRV8835. The code I used is the same given CMS for Pixy called as ccc_zumo_chase. You can see it under examples -> Pixy2 -> ccc_zumo_chase
![Chase robot Image ](https://github.com/MieRobot/Pixy2-robot-dog-chase-drv8835/blob/master/package%20code%20source.jpg)
I have also put a copy incase you wish to see the code in browser. The motor driver I used is the DVR8835 (Link https://www.pololu.com/product/2135). 
Please note you would need to download Pixymon2 to train the Pixy2 first.
Download link for PixyMon2 https://pixycam.com/downloads-pixy2/

Step 1# Download Pixymon and train the Pixy2 with the object
Step 2# Assemble the robot
Step 3# Deploy the code
Step 4# Arduino and driver connection is given at https://www.pololu.com/product/2135 and use mode 1 IN/IN, You do not need to make the MODE HIGH in DVR8835 Driver
Step 5# Test. Make sure you use the same lighting conditions as you used to train. Bright white lights seemed better than neon or yellow shades.

Note# This code will not work with L293/L298 Driver so donot waste time on it. DVR8835 uses only 2 connection per motor unlike L298 with needs 3 connections with PWM.

#### H4 Testing video in below link


[![IMAGE ALT TEXT](http://img.youtube.com/vi/OETt1gaWnrE/0.jpg)](http://www.youtube.com/watch?v=OETt1gaWnrE "Pixy2 and DVR8835 Color ball chase robot with code")
