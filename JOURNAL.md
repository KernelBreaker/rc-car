# Metadata
Title: RC Car
Author: Axel Montlahuc
Description: An RWD RC Car controlled with a phone. 
Created On: 08/05/2025

# August 5
## Research
I spent quite a lot of time (as I'm a beginner) doing research on what parts I will need and which model of those parts would fit best. 
### Quick Recap
- XIAO ESP32
- Custom 3D printed frame (probably in a Corvette ZR1X shape)
- Custom 3D printed wheels
- [LiPo Battery](https://fr.aliexpress.com/item/4000389770504.html) - $8.99
- 2 [10,000 RPM RS555 brushed motors](https://fr.aliexpress.com/item/4000472195699.html) - $3.10
- [BTS7960 motor driver](https://fr.aliexpress.com/item/1005009130512928.html) - $1.79
- MG996R servomotor for steering
- [Buck Convertor](https://fr.aliexpress.com/item/1005006911398521.html) - $0.99
- Accelerometer (not mandatory)
- LEDs (optional)
- Smoke (optional)
  
### Explanations
- For the controller I settled for the XIAO ESP32 as it has WiFi, enabling me to control the car with my phone so that I don't have to build a remote. Its small size/weight and its computing power also makes it a better choice than the RPi Zero W.
- For the battery I discussed with ChatGPT and looked online and LiPo was my best option. I was hoping to get a 3S one but they were not cheap so I settled for a 2S one which should be fine.
- I was originally planning to use 4 motors to make an AWD car but after looking at my options on AliExpress I figured out 2 good motors would be great. I settled for RS555 brushed motors that can go up to 10,000 RPM (it will probably go at 8,000 RPM though because it needs 12V and i can only supply 8.4V with the LiPo).
- I chose a basic buck convertor to step down the LiPo voltage to 5V for the ESP and leds
- Regarding the 3D printing I'm planning on designing verything by myself and print it thanks to printing-legion.
- Even though it's not needed to run the car I planned on using an accelerometer to be able to measure the top speed of my car and other stats!
- I also planned on using a servomotor to steer the front wheels, leds to light up the bottom of the car and maybe some smoke for some cool drifting!

**Time spent: 1 hour**
