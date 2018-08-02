---
layout: post
title:  Think Tank
date:   2017-11-07
description: "Train your concentration and lose yourself in this immersive telepathic co-op tank game!"
image: "/assets/blog/ThinkTank1.png"
bgcolor: "E57373"
---

## Think Tank
Last weekend, I attended Electric City Hacks at Trent University, Peterborough! Electric City Hacks is one of many hackathons that are happening around the world throughout the year. Simply put, a hackathon is a mash up of the words "hack" (in this case is to build or put something together) and "marathon". All sorts of people, including computer programmers, designers, graphic artists, and mechanics, come together to collaborate at these events and innovate or invent something new!

![Muse Headbands](/assets/blog/ThinkTank4.JPG){: .image-8 .image-center}
*Two Muse Headbands! They have electrodes everywhere on the front to analyze your brain waves.*{: .caption-center}

So, teamed up with a friend of mine, we came to this 37-hour hackathon with a goal of learning more about electroencephalograph (EEG) technology and the applications of such technology. EEG tech works by measuring electrical activity from certain parts of your brain with electrode sensors, that is to say it detects your brain waves! Within the last 4 years, there has been a rise in consumer EEG technology, and now we have access to dry electrodes which do not need to be continuously maintained with a paste or other conductive substance.

![Muse Lab](/assets/blog/ThinkTank5.png){: .image-right .image-6}
*The Muse Lab has three processed and usable channels: blinks, concentration, and jaw clench.*{: .caption-right .caption-6}

At ECHacks, we managed to obtain two Muse headbands from the hardware lab. I tested the Muse headbands with the proprietary Muse app on Android, and the meditation experience was enjoyable. Surprisingly, I achieved 91% calm in my first meditation exercise! After initial testing, we moved on to the  software development kit (SDK) provided by Muse, which was quite simple to get started. Unfortunately, documentation was very lacking, with the getting started tutorial being the only available resource.  As we took a look at the different channels provided by the Muse headband, we quickly realized that without extensive knowledge in data analysis and psychology, all the data we had was practically useless. Fortunately, the Muse Lab did provide some processed data with the raw data, which consisted of concentration levels, and blink and jaw clench detection.

![Volunteers](/assets/blog/ThinkTank3.JPG){: .image-left .image-6}
*Volunteer organizers demoing our game with a lot of excitement!*{: .caption-left .caption-6}

With the very limited set of processed data channels, we went with making a video game in Unity where you could use your mind to control something! A quick hack of some random code using my extensive knowledge of game development created a small tank game where you and a partner would work together to move a tank around and shoot enemies. It felt a little discouraging to only be able to make such a simple game, and at this point we felt too tired to move on. However, a group of organizers at the event came to visit us and made us show them what we had made. Despite how we felt about the project, they were extremely excited to see our project and brought many more people to come see the game. It was this push of excitement from other people at the event that motivated us to work harder and polish our project to make it into Think Tank, a name that another volunteer coined for us. We refined the control system to make it much easier to control, added level obstacles, and created a website for our project at [tanksforplaying.net](http://tanksforplaying.net){:target="_blank"}, which won us a Raspberry Pi Zero W for being the best domain name at the event!

Overall, Electric City Hacks was an incredibly fun and great learning experience. I now know much more about EEG tech and look forward to integrating it with my virtual reality system to make some crazy games! The Muse headband was a little lacking in its capabilities, so I am investigating other brain-computer interface and EEG devices that I could use. I also am looking forward to seeing what I can do with my new Raspberry Pi and Wolfram One cloud computing subscription!

If you would like to learn more about the project, head on to [tanksforplaying.net](http://tanksforplaying.net){:target="_blank"}

If you happen to have two Muse headbands and would like to try out the game, or just simply want to see the source code, check out my [GitHub repository](https://github.com/WilliamLQin/Think-Tank){:target="_blank"}! Just follow the README tutorial on the repository to get started!