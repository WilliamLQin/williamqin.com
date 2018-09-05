---
layout: project
title: Disco Alarm
slug: discoalarm
description: Wake yourself up with special light effects!
image: /assets/img/squares/discoalarm.jpg
bgcolor: "9575CD"
timeline: Aug. 24-26, 2018
---

# Disco Alarm

![Disco Alarm](/assets/img/discoalarm1.jpg){: .image-right .image-6}
*Echo Dot and a Raspberry Pi connected to an LED strip!*{: .caption-right .caption-6}

Light up your room when you wake up in just the way you want it!  

Disco Alarm is a sunrise alarm that wakes you up with a light, instead of a sound, that gradually increases in brightness.  

In addition, there are many light modes that simulate movement to try to wake you up in a more natural way.  

Disco Alarm works with Amazon Alexa and is super customizable with different light modes, different pre-alarm lengths, and will have many more options in the future as well!  

<br>

To get started, users would set a disco alarm with Alexa by saying "Alexa, tell Disco Alarm to set an alarm for [time] on [day of the week]" and then follow the prompts!

<br>

The process through which Disco Alarm worked was as follows:  
First, the Alexa skill and the stdlib function worked together to ask you all the questions needed to setup an alarm.  
Then, once all the details had been determined, the stdlib function sent a payload with all the details to AWS IoT, which passed it on to the Raspberry Pi via MQTT.  
Finally, the Raspberry Pi received the message and set an alarm for the appropriate time. Extensive code was required for integrating different colour modes and ensuring that there was no time drift.  

<br>

Node.js was used for stdlib function programming. Python was used for Raspberry Pi programming.

Disco Alarm was built solo at Hack the 6ix 2018, a 36-hour hackathon at Top Hat HQ, with 400 participants!  
I finished as a finalist!

Check out the project page and learn about how it was created at [Devpost](https://devpost.com/software/disco-alarm){:target="_blank"}!  
Head to my [GitHub repository](https://github.com/WilliamLQin/DiscoAlarm){:target="_blank"}.
