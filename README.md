# Project Description
# Video
  In this youtube video I was using a 5v relay instead of a 3v one. I was not able to have the pump connected without an external power source. I instead connected it to my pi to show a proof of concept. When you are building your own remeber to get a 3v relay. 
https://www.youtube.com/watch?v=HtoZyUCmgwY
# What problem does my project solve?
  Solves the problem of remebering to water your plant.   
# How is it internet connected?
  Around 3 times a day the sensor will trigger and the level will be transfered to losant. If the level is below a certain threshhold
  it will automatically water the plant and send you a text that it has been watered. 
# Hardware
  NodeMCU, 3.3v Relay, moisture sensor with potentiometer, 3-6v pump, Power supply, jumper cables
  https://www.amazon.com/3V-Relay-Module-Optocoupler-Development/dp/B01M0E6SQM/ref=sr_1_3?ie=UTF8&qid=1525218487&sr=8-3&keywords=3v+relay
  https://www.amazon.com/Hygrometer-Humidity-Detection-Moisture-Arduino/dp/B01FDGUHBM/ref=sr_1_2?s=industrial&ie=UTF8&qid=1525218558&sr=1-2&keywords=moisture+sensor+arduino
  https://www.amazon.com/gp/product/B01LWQCXEL/ref=oh_aui_detailpage_o08_s00?ie=UTF8&psc=1
  https://www.amazon.com/gp/product/B01IB7UOFE/ref=oh_aui_detailpage_o03_s00?ie=UTF8&psc=1

# Cost?
$33.5
# Where did you buy it?
Amazon
# Network
Wifi and Cellular(GSM or CDMA)
# Why did they choose these?
Simple and easy to set up
# Architecture
![final](https://user-images.githubusercontent.com/14096879/39499697-9f3b03a4-4d7d-11e8-8958-a1dd1df3b870.png)
