# Arduino core for ESP32 

## How to import arduino-esp32 library to Eclipse
Forked to include Eclipse + Sloeber installation. Needs Git in Eclipse. You should also check it out Baeyen's video ->  https://www.youtube.com/watch?v=ZN-rLSyhBN8

## Installation Instructions
1. Open Eclipse.
2. (If not already have) Install the Sloeber plugin -> http://eclipse.baeyens.it/installAdvice.shtml .
3. From File -> Import -> Git -> Projects from Git.
4. Choose Clone URI.
5. Insert URI section : https://github.com/thesoulkiller/arduino-esp32  or the espressif's repo.
6. Click Next, in Branch Selection select all then click Next again.
7. Choose a directory for the library. Say ("/home/user/arduino-esp32/").
8. Next, select "Import as general project". Then finish the project adding.


1. From Eclipse main screen select the Arduino tab and click Preferences.
2. In Arduino title, from "Private hardware path" click New.
3. Select the newly installed project directory and click OK.
4. Apply and Close.

### Install esp32 tools
Then from terminal cd to "/home/user/arduino-esp32/tools/" directory and run the "get.py" script
$ python get.py

### Create an arduino project
1. From Eclipse main screen select File -> New -> Arduino Sketch.
2. Enter the details then click Next.
3. Select "/home/user/arduino-esp32" from "Platform folder" dropdown. 
4. Select the dev board you're using from "Board" drop-down.
5. Sample config with ESP32 DOIT board ![Config](/config.png)

Then have fun !
