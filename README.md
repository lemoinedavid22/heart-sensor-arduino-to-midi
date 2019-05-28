# heart-sensor-arduino-to-midi

Goal : 
4 heartbeat sensors on an arduino mega send a note on a separate channel to Live. 

For now : 
- unable to write a proper code that would allow multiple sensors on one same board sending to different midi channels. 
- found a simple code that works for one sensor per board
- use multiple boards

Chain : 
Arduino & clone --> headless midiserial --> Live

Code :
piezo example of this tutorial : https://www.instructables.com/id/Arduino-Sensors-and-MIDI/

Boards : 
- Arduino mega 
- Uno 340 arduino compatible. Crashes issues when connecting to High Sierra solved by installing drivers following : https://firxworx.com/blog/maker/arduino/installing-ch340-ch34x-drivers-on-macos-for-cheap-arduino-clones/
