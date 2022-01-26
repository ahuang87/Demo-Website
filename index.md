## DropLock Project Summary  

The implementation of an effective drop detection safety in power tools is potentially a safety redundancy that may save many a trip to the emergency room.
However, the difficulty of such a device is that an effective impulse detection algorithm in a noisy environment is often non-linear, requiring a convolutional process at every signal received. However, by putting a weighting the most recent data points over the older ones, an algorithm may be able to efficiently determine whether a device had a small jump from kick back during the use of the tool or if the user has lost control of the tool while still being able to shut off for large enough kick backs. 

By using a microcontroller with an accelerometer placed somewhere on the device, the device aims to efficiently detect danger while maintaining minimal power draw from the tool for a price of $9.16.


### Project Description

We will be designing a prototype of a module for a power tool that’ll be able to detect free fall. 
Eventually, when free fall is detected, the power tool will shut off minimizing unwanted damage.
Our prototype will be able to detect free fall within 0.5 seconds of the initial drop, causing an LED on its enclosure to turn on.
It’ll also be able to withstand repeated drops of 3 to 6 feet and filter out noisy signals to minimize false positives all while consuming less than 3.3mW of power. 


### Simulation Data/Results 

Insert Simmulation Results Here:

### Test Video

Click Here to watch a [demo](https://support.github.com/contact) 
