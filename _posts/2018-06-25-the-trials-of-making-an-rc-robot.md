---
layout: post
title: The Trials of Making an RC Robot
date: 2018-06-25
description: "There was so much hope for features, but some just couldn't make it."
image: "/assets/blog/rcrobot0.jpg"
bgcolor: "9575CD"
---

# Raspberry Pi Robot

#### What We Created

As a part of my computer engineering class, my partner and I built a robot that could be controlled to move via Bluetooth and infrared. The focus of the project we designed was on using communications technology and creating a working drivetrain for the robot.

So, we built this:

![Robot](/assets/blog/rcrobot1.jpg){: .image-left .image-6}
*Look at all the RGB lighting!*{: .caption-left .caption-6}

Our main controller for the robot was a Raspberry Pi!
Our drivetrain consisted of 5 VEX motors and wheels: 2 for the left side, 2 for the right side, and 1 for strafing.
We used WS2812b individually addressable RGB strips for the lighting on the bottom of the robot.
The Raspberry Pi was powered by a power bank, while the drivetrain was powered by two 9V batteries.
An infrared receiver on the breadboard was used to decode infrared remote signals for the Raspberry Pi.

<br>

<br>

<br>

Here are some diagrams for how the robot's circuit was constructed:

![Robot](/assets/blog/rcrobot2.png){: .image-center .image-8}
*This is the pictorial drawing for the circuit of the robot*{: .caption-center .caption-8}

![Robot](/assets/blog/rcrobot3.png){: .image-center .image-8}
*This is the schematic drawing for the circuit of the robot*{: .caption-center .caption-8}

<br>

As for the robot's programming (my specialty!), feel free to check it out at my [GitHub repo](https://github.com/WilliamLQin/Raspberry-Pi-Robot)!

#### Looking Back

Reflecting on this project, overall, it turned out very well. We were able to get Bluetooth running seamlessly with fast response times from the robot, infrared decoding and processing, and RGB LED controls all at the same time with threading. By ensuring that the batteries were in top shape and by using speed control, we could get the robot to move fairly straight and pretty quickly. The LEDs looked beautiful and suited the robot’s movements perfectly. The construction of the circuit worked as intended. The robot was built without any major issues and was the perfectly sized to fit all components. It also worked on its own without needing a Wi-Fi connection for using SSH to start up the program.

However, there were many things that did not go as planned. Originally, we had intended to use a third communication protocol: voice control. After trying several times to install Jasper, which didn’t work, and then Google Assistant, we did finally manage to get it to turn on a motor. Unfortunately, the new functionality provided by voice control was extremely limited. Firstly, the voice assistant had to be manually turned on, requiring another form of communication, whether that be through Wi-Fi, Bluetooth, or infrared. Secondly, the voice assistant did not work well in noisy environments; it could barely even hear our commands. Lastly, even when it did hear us, it took a very long time to process the command and run it. Eventually, we had to scrap that idea, especially after I realized that audio output to the speaker from the voice assistant cannot be used at the same time as the WS2812b RGB LED strip controller. Another problem we encountered was that the 9V batteries we used died very quickly. The motors consumed a lot of power can quickly drained them. However, one thing that I did notice that caused the batteries to die even faster was to leave them connected to the circuit overnight. After that, we always disconnected the batteries when the robot was off. One final problem that we encountered after completing the robot was that the strafe wheel often resulted in the other wheels not fully contacting the ground. This made them significantly weaker and impacted the movement of the robot when not strafing.

If I were to do this project again, I would avoid creating a strafing robot, as while it was cool, it did not add a lot to the robot’s movement capabilities. Instead, armed with new knowledge of building circuits and programming a Raspberry Pi, I would try to create a robot arm that could do actions. For example, I could create an adjustable platform to allow it to carry sheets of paper around. I would have also explored other options for creating the robot, instead of using VEX parts. We used those parts because they were readily available and usable, but they weren’t of the best quality. Next time, I would see if I could try other motors and motor controllers to create a better and more reliable drivetrain.

In the end, I’m very proud of what we’ve created. Despite some complications in the making of the robot, it turned out very well and worked as intended. I now have a better understanding of microcontrollers and motors, and if I were to do the project again, I would explore extending the robot to do more.
