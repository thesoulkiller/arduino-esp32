# Arduino core for ESP32 

## How to import arduino-esp32 library to Eclipse
Forked to include Eclipse + Sloeber installation. Needs Git in Eclipse. You should also check it out Baeyen's video ->  https://www.youtube.com/watch?v=ZN-rLSyhBN8

## Installation Instructions
Open Eclipse.
(If not already have) Install the Sloeber plugin -> http://eclipse.baeyens.it/installAdvice.shtml 
From File -> Import -> Git -> Projects from Git.
Choose Clone URI
Insert URI section : https://github.com/thesoulkiller/arduino-esp32  or the espressif's repo.
Click Next, in Branch Selection select all then click Next again.
Choose a directory for the library. Say ("/home/user/arduino-esp32/")
Next, select "Import as general project". Then finish the project adding.

From Eclipse main screen select the Arduino tab and click Preferences.
In Arduino title, from "Private hardware path" click New.
Select the newly installed project directory and click OK.
Apply and Close.

### Install esp32 tools
Then from terminal cd to "/home/user/arduino-esp32/tools/" directory and run the "get.py" script
$ python get.py

### Create an arduino project
From Eclipse main screen select File -> New -> Arduino Sketch.
Enter the details then click Next.
Select "/home/user/arduino-esp32" from "Platform folder" dropdown. 
Select the dev board you're using from "Board" drop-down.

Then have fun !


