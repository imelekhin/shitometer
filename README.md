# Water tank level meter
This is quick and dirty device to measure waste level in undergraund tank (actually level of shit). It is build with Heltec esp32 LoRa board and hc-sr04 sonar.
To connect hc-sr04 to esp32 were used 5v-3v level shifter. To smooth measurements were used QuickStats lib and median. Measurements and heartbeats
transmits by LoRa to LoRa-mqtt bridge https://github.com/imelekhin/LoRatoMQTT

