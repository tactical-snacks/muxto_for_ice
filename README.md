# muxto_for_ice
update the arduino nano every's samd11d to v1.07 which was downloaded from a nano every. uploaded using atmel-ice, no bossac. i used microchip studio 7.

## background
So i tried following the very nicely laid out steps here ... https://github.com/arduino/ArduinoCore-megaavr/issues/51#issuecomment-522905679
but i'm using windows and stuff didn't work and i honestly didn't try that hard.

## instructions
<ol>
<li>connect programming pads to atmel-ice squid plugged into either avr or sam connector using the SWD pins</li>
<li>provide power to nano every and connect to device ATSAMD11D14AM</li>
<li>program</li>
<li>remove atmel-ice and power cycle nano every</li>
<li>test uploading/serial on nano every with verbose output on upload. should see latest rev like this in the output ... `M_MCU firmware version: 1.07`
</ol>

