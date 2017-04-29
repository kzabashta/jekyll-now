---
layout: post
title: Messing With The Pi
published: true
---
Started putting together sensors on the Raspberry Pi, writing code in Python to integrate it with a Slack bot.

Here's the Pi with the temperature / humdity sensor:

![_config.yml]({{ site.baseurl }}/images/IMG_4710.JPG)

Here's the Slack bot that I can ask about the current temperature and humidity in the house:

![_config.yml]({{ site.baseurl }}/images/2017-04-28.png)

The code for the Slack bot is in the [pi-slack-bot repository](https://github.com/kzabashta/pi-slack-bot).

I will write a more detailed post on hardware and the bot in follow up posts. I am also planning to build a script that uses [Plotly Python API](https://plot.ly/python/streaming-tutorial/) to show real-time sensor data in the context of last 24 hour rolling window.
