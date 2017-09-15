# NBH-Ferien
As part of a workshop for young beginners (children above 12 y/old), we programmed an Arduino UNO using ArduBlock (version 20140414) to develop an RGB-Thermometer, using and RGB-LED and the temperatur sensor LM35.
The RGB-LED changes its colour depending on certain defined threshold values. 
For example if the sensed temperature was below 27°C then the RGB-LED will only light up blue. Between 27°C and 29°C the RGB-LED will light only green. Above 29°C the RGB-LED will light up red.
The children learned how to read a temperature sensor and how to control the RGB-LED using the IF instruction.
The PDF document is in German. The abp files for ArduBlock are also for the german version.
I divided the project in three parts: 
1. controlling the RGB-LED (file RGB LED.abp)
2. reading the temperature on the serial monitor (file LM35-seriellmonitor.abp)
3. putting together the colour-thermometer mentioned above (file Temp_messen_RGB.abp)

