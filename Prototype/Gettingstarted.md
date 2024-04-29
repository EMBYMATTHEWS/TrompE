For my project I didnt need to import much I actually aimed to use as much native stuff to the teensy 4.0 as possible to get a handle on the software. 


#include <Wire.h>
#include <Adafruit_MPL115A2.h>
#include <usb_midi.h>

Wire was needed to use I2C communication for the pressure sensor. 

The usb.midi was the mvp of this build as it is the coolest feature. Maping values from the sensor to midi over the same usb that powers it