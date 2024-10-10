## assignment 1
Assignment 1 description

# Introduction

CLASSIC CAMERA WITH LIGHT

![sketch](1st_Assignment_Sketch.jpg)

# Firmware
```
 # When user took the picture, light will blink time like camera flash.

   elif program_state == 'DONE':
    
    for i in range(100):
      rgb_color = get_rgb_color(i, 100-i, 0)
      rgb.fill_color(rgb_color)
      output_pin.on()
      time.sleep_ms(2)
      
    time.sleep(1)
    
    for i in range(100):
      rgb_color = get_rgb_color(100-i, 0, 0)
      rgb.fill_color(rgb_color)
      time.sleep_ms(1)
      
      
    rgb.fill_color(0)
    output_pin.off()
```
# State Diagram

blakskkskksksksskskkss:
![state diagram](Diagram_1st_Assignment.jpg)

# Physical Components

Using LEGO kits, I built the classic camera and used coppers, light, resistor to make function.

# Project Outcome

It was pretty fun start from beginning project. I made a project inspired by classic camera flashing. When people use the classic camera, the flash will blink one time when they took the picture. By that, using lego camera, I bring similar functions to my first project:

![project photo](1st_Assignment_HW1.jpg)


Video
https://drive.google.com/drive/folders/1HGnTw7oHCrzTg4h89gobelJjIQi-6_kc?usp=sharing
