---
layout: post
title: Analog Arrays 
subtitle: blink blink
tags: [coding]
mathjax: true
comments: true
author: Cici
---
An idol of mine once said that what makes a super villain is something quite simple: presentation. Following his advice, my minions and I have dedicated ourselves to the art of light-making. And with this new script, our variable efficiency might skyrocket.
## Behold... More Lights
![blue, green, red and yellow lights on at different brightnesses](../assets/img/array.jpg)
Every second, a PWM light turns on (or off) to a random brightness. For this project, we used arrays to make variable declarations more efficient. It essentially takes a base name and adds a number to it. I used an array for my light pins and to assign each "is it on?" bool the value "false," so the program knows that the lights are all off at the beginning. I think this kind of tool would have been  helpful for my *Jammin'* project to name all the frequencies efficiently. I would also like to note that pin 10 wasn't performing its WPM function despite being labeled as a PWM pin. Even when I ran the fade demo, pin 10 was only ever completely on or completely off.

A tip to my future self is to make use of the Arduino demos to test my code. Since not even the fade demo worked for pin 10, and every other pin works as normal, I'm fairly confident that my code isn't incorrect. Because of this, I won't waste too much time trying to figure out what's wrong. 
