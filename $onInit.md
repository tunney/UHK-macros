# $onInit

Automatically invoked macro that runs on power on to initalise the keyboard

Enables extended commands and sets the LEDs for keys to turn off after 5 minutes

Sets the pinch to zoom to be mac mode and enables chording

Slows down the touchpad scrolling (default 8) 
Note: the documentation has the scroll speed divisor incorrectly capitalised.

```
set leds.fadeTimeout 5
set macroEngine.extendedCommands 1
set module.touchpad.pinchZoomMode zoomMac
set chordingDelay 50 
set module.touchpad.scrollSpeedDivisor 16
```
