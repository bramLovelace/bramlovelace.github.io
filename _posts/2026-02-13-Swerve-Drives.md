---
layout: post
title: Swerve Drives
---

In high school I was the CAD lead for FRC Team 900: The Zebracorns. During the offseason prior to the 2018 season, I took on a project to develop a swerve drive that would be fully custom. This was largely driven by the $1100 BOM cost of the 4 COTS (commercial off the shelf) swerve modules we had used the previous year. 

The general idea is that by being able to control the direction and speed of each wheel independently, the robot can have full freedom to translate and rotate freely including any combination of the two. This opens up the design of the rest of the robot rather than being limited to two faces as the front and back. It also allows more advanced defense / evasion and path planning. 

We had previously run COTS swerve modules in 2015 and 2017 so were confident in the ability to design around it and to have the software necessary. 

After 10 major iterations in CAD, the first time we built it was for the robot and it worked! We even won an award that called it out specifically. 

![image]({{ site.baseurl }}/images/Swerve2018a)
![image]({{ site.baseurl }}/images/Swerve2018b)

This version had a cut into the main drive gear to hold the module bearing as well as offsetting the wheel to allow it to be directly driven through a bevel gear train so as to shorten the height of the module. 


After the success of our first custom swerve module, we identified many places we could improve the design to save weight and volume. 
Through the next offseason we developed a way to stack the position and drive encoders on the module axis by sending the position through a 1/8" carbon fiber rod in the center of the drive axle and 3d printing gears for the encoder. That meant the rotation gear did not have to be 1:1 with the main module gear. 

With this and other changes I was able to shave off ~3lbs from each module for a total weight savings of ~12lbs (10% of the weight limit for the robot)

![image]({{ site.baseurl }}/images/Swerve2019a)
![image]({{ site.baseurl }}/images/Swerve2019b)

