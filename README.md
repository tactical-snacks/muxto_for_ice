# muxto_for_ice
update the arduino nano every's samd11d to v1.06(). uploaded using atmel-ice, no bossac. i used microchip studio 7.

## background
So i tried following the very nicely laid out steps here ... https://github.com/arduino/ArduinoCore-megaavr/issues/51#issuecomment-522905679
but i'm using windows and stuff didn't work and i honestly didn't try that hard.

## instructions
<ol>
<li>connect programming pads to atmel-ice squid plugged into sam connector (i.e. not avr connector)</li>
<li>provide power to nano every and connect to device ATSAMD11D14AM</li>
<li>program</li>
<li>remove atmel-ice and power cycle nano every</li>
<li>test uploading/serial on nano every
</ol>

