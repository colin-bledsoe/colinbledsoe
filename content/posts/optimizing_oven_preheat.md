---
title: "Optimizing_oven_preheat"
date: 2020-11-26T08:10:10-07:00
draft: true
---

Today (well over the last several months) I measued oven preheating times. If my oven functions the way I expect it uses a duty cycle to turn on and off a circuit through my heating element. If this system is linear then I can optimize energy usage and avoid wasting time heating to any temperature 70-500 by calculating it with a simple linear equation.

Control data
- Push bake, set desired temperature, push bake, start timer, stop timer when oven beeps
11-26-20 ramp ambient (70 deg F) to 400F in 10 minutes 52 seconds
11-26-20 ramp 110 deg F to 375 deg F in 8 minutes 39 seconds (oven was still warm from use earlier in day)
11-29-20 70-400 deg F in 10 minutes 40 seconds
11-29-20 70-350 deg F in 8 minutes 43 seconds
12-4-20 ramp 70 deg F to 425 deg F in 13 minutes 32 seconds
12-5-20 ramp 70 to 400 in 10 minutes 47 seconds
12-7-20 ramp 70 to 500 deg F in 18 min 59 seconds, on the way to 500 I hit 350 at 10 min 42 seconds
12-8-20 ramp 70 to 350 deg F in 9 minutes 1 second
12-11-20 ramp 70-425 deg F in 12 minutes flat
12-15-20 ramp 70 to 400 deg F in 10 min 57 seconds (350 deg F achieved at 8 minutes 47 seconds)
12-24-20 ramp 70-400 deg F in 10 min 48 seconds 
1-2-2021 ramp 68-400 degF in 10 minutes 56 seconds


Optimizing boiling a cup of water, a quart of water, a gallon water
- better to wait until the tap is hot and then fill the pot versus fill the pot with cold water and put it on the burner rapidly.
- Time this, measure it and time it.