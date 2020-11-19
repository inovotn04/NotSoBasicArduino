# NotSoBasicArduino
 The follwing files are my second foray into Arduino
 
 
## Table of Contents
* [Table of Contents](#TableOfContents)
* [LED_Fade](#LED_Fade)
* [Hello_LCD](#Hello_LCD)
* [FillMeInLAter](#FillMeInLAter)
---

## LED_Fade

### Description & Code
Making the arduino fade using analogWrite and variables to change the brightness.

```C++
// set the brightness of pin 9:
  analogWrite(led, brightness);

  // change the brightness for next time through the loop:
  brightness = brightness + fadeAmount;

  // reverse the direction of the fading at the ends of the fade:
  if (brightness <= 0 || brightness >= 255) {
    fadeAmount = -fadeAmount;
  }
```
analogWrite sets the led brightness to the "brightness" variable and then the 
brightness is either increased or decreased by the "fadeAmount" variable.
### Evidence
https://create.arduino.cc/editor/inovotn04/c8784bd7-16b9-4bf7-9797-a1a1dd349e99/preview

### Images
<img src="Images/FadeWire.png" alt="Fade Wiring" width="300" height="300">
### Reflection

## Hello_LCD

### Description & Code
Description goes here

Here's how you make code look like code:

```C++
Code goes here
```
Talk about how the code works, here....

### Evidence
link goes here

### Images
draw it yourself, take a picture, make a fritzing, whatever you want to EFFECTIVELY communicate how its put together.

### Reflection

