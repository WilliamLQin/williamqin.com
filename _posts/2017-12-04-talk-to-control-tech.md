---
layout: post
title:  Talk to Control Tech
date:   2017-12-04
description: "Voice activated keyboard input web application!"
image: "/assets/blog/talk2control1.JPG"
bgcolor: "FFAB91"
---

## Talk to Control Tech
Yesterday, I attended another hackathon called Local Hack Day at Shopify Toronto! This time, I met up with 3 other people that I had never worked with before to create a website in just 9 hours! Coincidentally, one was a student at the high school I had transferred from, and another had volunteered with me at another hackathon.

We made a voice activated keyboard input web application, called Talk to Control Tech! Essentially, Talk to Control Tech listens to your voice for a keyword that you enter, and whenever it hears the keyword, it presses space on your keyboard! This is incredibly useful for presenters who want to use a slide deck, but will be standing away from their computer while speaking. You can sync up the lines of your presentation with the slides and there is no need for a clicker! Sadly, the web app currently only runs on localhost, but you can view a front-end demo at [talk2control.tech](http://talk2control.tech){:target="_blank"}. If you want to actually try using it, head to the [GitHub repository](https://github.com/WilliamLQin/talk2control){:target="_blank"} to download the source code, follow the README, and run it on localhost!

Originally, we had planned to learn how to use Wolfram One through the application of some kind of software, but later found that Wolfram One was unable to do real time voice recognition, which was essential to our idea. Instead, we used a JavaScript library called [p5.speech](http://ability.nyu.edu/p5.js-speech/){:target="_blank"}, which worked really well!  

Talk to Control Tech was built with a plethora of web stack tools. For our back-end, we used DigitalOcean for hosting and cloud computing and ran the website on Flask, which uses Python. As for our front-end, we tried to implement React and Node.js, but ended up falling back on using just HTML, CSS, and JavaScript after some complications with implementing React and Flask together. It was a tough call to revert back our work on React with only 2 hours left, but ultimately it was a good choice.

![Winners](/assets/blog/talk2control2.jpg){: .image-right .image-6}
*My team and I won first place at Local Hack Day!*{: .caption-right .caption-6}

As we prepared for the demo, we came up with idea of using Talk to Control Tech to control our own slideshow presentation. Then, instead of the word “next”, I opted to make the keyword “magic”. The next hour of practicing before our presentation was full of me saying “magic!”. I made up transition sentences like “Talk to Control Tech, it’s like magic”, “control your slides with magic”, and “this is .tech magic”. In the end, our presentation went somewhat okay, as voice controller only picked up on one instance of the keyword magic. It seemed like the problem was not with poor voice recognition, rather the website just stopped listening to me. However, that did not impede our wonderful idea from leaving an impression and we ended up winning 1st place at the hackathon!

![Table Tennis](/assets/blog/talk2control3.jpg){: .image-left .image-6}
*We got to play table tennis during our time at Shopify Toronto!*{: .caption-left .caption-6}

The Toronto Youth Network did an incredible job in hosting the event. The venue that they provided us was absolutely phenomenal. We got to work in the actual Shopify employee workspace, and they had some really cool stuff! There were numerous board rooms filled with technology, a kitchen area for food, a big common room with a projector, a table tennis table, a Wii U, and noise isolating couches! The whole place was furnished with wood and decorated, unlike the usual concrete flooring in most venues. I loved the atmosphere that they created by bringing awesome speakers and friendly organizers. Everything was easy to access within a small area and did not require a lot of travelling just to get to something simple, like the washroom.

Overall, this year's Local Hack Day was an awesome experience! I look forward to the next hackathon I'll be attending in two weeks: [Snowday](http://snowday.projectcipher.io){:target="_blank"}!

![Shopify](/assets/blog/talk2control4.jpg){: .image-center .image-8}
*Many thanks to Toronto Youth Network and Shopify Toronto for the great time!*{: .caption-center .caption-8}