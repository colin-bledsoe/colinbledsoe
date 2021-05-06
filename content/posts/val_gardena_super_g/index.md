---
title: "Val Gardena Super G Analysis"
date: 2020-12-28T01:26:55-07:00
draft: true
---
**Background**
While working out the details of the multi-component phase equilibria problem from my Bread and Brown Sugar blog post, I decided to turn on some light-entertainment. I wanted to find some background noise and settled for the 2020 FIS Men's Super G World Cup race at Val Gardena, Italy. It didn't take long for me to realize I was wrong to assume that a televised ski race wouldn't be distracting. I should've known that pretty much anything would distract me from sifting through college thermodynamics lecture notes. Honestly though, watching skiers fly down a slope that they haven't practiced on* at speeds greater than 70 mph is very distracting. 

*A distinguishing attribute of the Super G Alpine Skiing event is that competitors don't get a trial run. The entire competition boils down to each athlete's first and only time down the slope. This makes the athleticism even more mind-blowing. 

I recently watched my first televised FIS Alpine Skiing event. I saw the 2020 Men's Super G World Cup Event at Val Gardena. It is rare for me to watch sports, I actually turned to that channel because I figured watching skiing wouldn't be very distracting, I was looking for some background noise while I worked through a blog post question that left me tangeld in a messy thermodynamics problem. In between google searches and scouring old PDFs I found myself sparing 15-30 seconds here and there to watch portions of each skier's run. Before long I found that televised skiing is more entertaining that researching multicomponent VLE parameters.

**Where data science comes in**
Super G is an interesting event, its a spin-off of downhill alpine skiing. Unlike downhill skiing, Super G competitors don't get to train on the course before the event, they have a single run on competition day to record their best time and that is it. Besides that interesting fact, I was blown away by the on-screen split timer results. Although clear differences existed between skiers (height, weight, ski, line selection to name a few) the skiers were completing the course with insanely similar lap times. Out of clear necessity, split intervals are reported with hundredth of a second accuracy. As an engineer who ferociously battles variation in a manufacturing process each day I was stunned by the lack of influence that the variables I perceived as important/relevant were having on the performance (time) of each racer.

As with most data, there are many different ways to present the same information. This particular sporting event was a race and as such, lap times are the primary data source. A single lap can be broken down into segments or intervals. Each interval's time can be recorded to share a more granular view of the race. I had more questions about the on-screen interval split timer.

Who does 1st place get compared to? 
Consistency is speed. Assuming it is possible to connect each interval perfectly, the fastest time down this course could be predicted to be the composite sum of each individual interval leader's time (1st in interval 1, interval 2, etc)
Speed doesn't get 1st place
Speed causes DNF?
How is racer psychology (cautious mindset) influenced by crashes on the course? Val D'isere women's downhill 2020, multiple crashes in series. Did the racer's before these crashes perform better lap times than the racer's afterwards?

