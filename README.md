This repository summarizes all 

### corresponding repositories:

1. Library incl. documentaion:

   The ThingSpeak library https://github.com/ATM-HSW/libThingSpeak is a port and extension of https://github.com/mathworks/thingspeak-arduino for Mbed OS 5 https://github.com/ARMmbed/mbed-os


2. http Dependency:

   The ThingSpeak library was changed to use the mbed-http library https://os.mbed.com/teams/sandbox/code/mbed-http/ The examples include https://github.com/ATM-HSW/libHttp which is a fork of the mercurial repository https://os.mbed.com/teams/sandbox/code/mbed-http/

3. MQTT Dependency:

   The ThingSpeak library was extended by MQTT using the https://os.mbed.com/teams/mqtt/ The examples include https://github.com/ATM-HSW/libMQTT and dependencies which are forks of the mercurial repositories https://ohagendorf@os.mbed.com/teams/mqtt/code/MQTT/ and dependencies

### and examples:

1. exampleThingSpeakReadField

   Reading a value from a ThingSpeak single field (own channel has to be configured).

   https://github.com/ATM-HSW/exampleThingSpeakReadField

2. exampleThingSpeakReadWeatherStation

   Reading weather station data from Mathwork's headquarter weather ThingSpeak channel (public channel)

   https://github.com/ATM-HSW/exampleThingSpeakReadWeatherStation

3. exampleThingSpeakWriteField 

   Writing a value to a single field on ThingSpeak (own channel has to be configured).

   https://github.com/ATM-HSW/exampleThingSpeakWriteField

4. exampleThingSpeakWriteChannel 

   Writing values to multiple fields of a channel on ThingSpeak (own channel has to be configured).

   https://github.com/ATM-HSW/exampleThingSpeakWriteChannel
