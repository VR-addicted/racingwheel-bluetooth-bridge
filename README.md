# racingwheel-bt-bridge (Logitech G29)
this is a cheap and easy to build bluetooth BLE adapter for Logitech G29 (in future more) racing wheels.   
its highly configurable via android app, uart.  
its build to use logitech`s racing wheels with android devices, like  
- META QUEST
- ANDROID Smartphones and Tablet
- IPHONE (untested)

What is needed? A Cheap 6$ ESP32 S3 with 2 USB Ports and a USB Type A Female to USB type C Adapter $4 (no soldering)

what you get:  
Firmware for the ESP32 S3:  xxxxxxxx.bin  
Android App for Quest/Smartphones/Tablets: xxxxxxx.apk  

The ESP32 is easy to flash over my website directly in your browser to the device.
The Android app is not needed, but it makes things easy as fork.


Features:
- Almost all G29 buttons are usable 
- Every G29 key is usable. 
- Multi profile editor in the Android app to map any G29 to any key on this Virtual Gamepad.
- 2 bluetooth client slots (I use meta q3 and my phone on the same esp device without repairing)
- config tool directly in your Meta Quest  
- diagnosis and configuration via uart possible as well
- both modes supported (PS3 / PS4 switch on the wheel)
- 270 degree PS3 mode (physical switch on the wheel)
  -  PS3 mode 8 bit resolution
   - all buttons working
   - virtual endstops at +-100 degrees.
   - gas and brake is working. the ps3 has had no cludge!
- 900 degree PS4 mode (physical switch on the wheel)
   - PS4 mode with 16 bit resolution
   - all buttons working
   - all pedals  working
   - rotation limiter from 900 to 540 and 270 degrees in software
   
- work in progress: motor spring effect regulator, its in the menus, but its not easy to set.
- work in progress: firmware updater over the BT app

