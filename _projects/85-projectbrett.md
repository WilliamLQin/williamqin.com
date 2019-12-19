---
layout: project
title: Project BRETT
slug: projectbrett
description: Survey an area for heat sources and create a heat map with a drone!
image: /assets/img/squares/projectbrett.jpg
bgcolor: "9575CD"
timeline: Oct. 2019 - Dec. 2019
---

<section name="demo" id="demo" class="content-section-b">
    <br>
    <div class="video-container">
        <iframe
        src="https://www.youtube.com/embed/El_kEeH8zig"
        allowfullscreen="true"
        mozallowfullscreen="true"
        msallowfullscreen="true"
        oallowfullscreen="true"
        webkitallowfullscreen="true">
        </iframe>
    </div>  
    <br>
</section>

# Project BRETT

![Project BRETT](/assets/img/projectbrett1-min.jpg){: .image-right .image-4}
*Fully assembled drone!*{: .caption-right .caption-4}

Project *BRETT* is an autonomous heat source mapping drone!  
To use it, all you need to do is tell the drone where to go.  
<br>
The drone can fly in a survey pattern and it collects data by polling its GPS, infrared sensor, and a PiCamera mounted to a RaspberryPi.  
<br>
<br>
We made Project *BRETT* with an assortment of technologies and programming languages.
* The drone was built from the [NXP Hovergames kit](https://www.hovergames.com/Technology)
* The flight management unit and temperature data collection was programmed in C/C++
* The RaspberryPi and photo capture was programmed in Python
* Image processing was done with OpenCV and programmed in Python
* Infrared data processing and heat map generation was done with Seaborn and Matplotlib and programmed in Python

<br>
![Image Capture Device](/assets/img/projectbrett2-min.jpg){: .image-left .image-6}
*Using a RaspberryPi + PiCamera to capture images*{: .caption-left .caption-6}

Project *BRETT* was created as a final project for a university course.  
Credits to my awesome team: Jason Guo, Jonathan Xu, Joshua Cheng, and Ricky Mao! <br>


Check out our [project report](/assets/docs/Project-Brett-Final-Report.pdf) to learn about how it was created and our design process.  
See the code at our [Git repository](https://git.uwaterloo.ca/j885chen/BRETT-SE101){:target="_blank"}!
