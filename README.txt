# Arduino-codes


Put the code from Time till christmas Esp32 file Into arduino ide and install following libraries:

NPTClient by Fabrice Weinberg
SevSeg by Dean Reading
TM1637 by Avishay Orpaz
and 
Time by Michael Margolis



Put pins to a TM1637Display like this:   vcc to 5v, gnd to gnd, clk to 2 and dio to 0 (Or other if you change the code)
Put in you wifi credentials in ssid and password 1 (and 2 if you have multiple wifi/workplaces)
Change timezone to your location:
For Europe:

Central European Time (CET): UTC+1
Eastern European Time (EET): UTC+2
For America:

Eastern Standard Time (EST): UTC-5
Central Standard Time (CST): UTC-6
Mountain Standard Time (MST): UTC-7
Pacific Standard Time (PST): UTC-8

example: 
const int timeZone = 1; // Central European Time
const int timeZone = -5; // Eastern Standard Time


also change the 2023 to the year you are in, may be automated in future
christmasDate.Year = 2023 - 1970;

After everything is set up upload the code and plug it in power, it should work.
