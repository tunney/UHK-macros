# $onInit

Automatically invoked macro that runs on power on to initalise the keyboard

Enables extended commands and sets the LEDs for keys to turn off after 5 minutes

Sets the pinch to zoom to be mac mode and enables chording

```
set leds.fadeTimeout 5
set macroEngine.extendedCommands 1
set module.touchpad.pinchZoomMode zoomMac
set chordingDelay 5
```
