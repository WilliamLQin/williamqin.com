---
layout: project
title: MAGNET
slug: magnet
description: The multi-purpose catching device!
image: /assets/img/squares/magnet.jpg
bgcolor: "9575CD"
timeline: Sep. 14-16, 2018
---

# MAGNET

![MAGNET](/assets/img/magnet1.jpg){: .image-right .image-6}
*The internals of the autonomous robot assembled from VEX parts + an Arduino, a Raspberry Pi, and a camera module!*{: .caption-right .caption-6}

Never get up to pick up your stuff after you toss and miss again!  

MAGNET is a modular robotic catching device that allows you to throw stuff at it with a margin of error and still have it go in!   

You can attach a recycling bin to catch paper, a hook to catch shirts, or a laundry hamper for your old laundry!  

Here's how it catches your stuff:  
First, the robot detects the object that you want to throw in your hand with computer vision. This happens with the Raspberry Pi and the camera module.  
Then, the Raspberry Pi figures out where the robot needs to move to keep the object in the centre of its field of view. It sends a digital signal to the Arduino to tell it how to move.  
Finally, the Arduino takes the instructions from the Raspberry Pi to power the motors as instructed.

<br>

OpenCV was used for computer vision. Python was used for Raspberry Pi programming. Arduino was used for VEX motor control.

MAGNET was built at [Hack the North 2018](https://hackthenorth.com){:target="_blank"}, a 36-hour hackathon with 1000 participants!  
It's North America's largest hackathon, receiving over 5000 applicants every year.

Check out the project page and learn about how it was created at [Devpost](https://devpost.com/software/magnet){:target="_blank"}!  
Head to our [GitHub repository](https://github.com/janakitti/MAGNET){:target="_blank"}.

<br>

Video Demo:
<div class="text-center video-container">
    <video controls>
        <source src="/assets/video/MagnetDemo.mp4" type="video/mp4">
    </video>
</div>