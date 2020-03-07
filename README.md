# proximity_lights
turn on the lights in my room when i get close


so i initially stole this code from some guy on youtube who graciously linked his github in the description. I was in incognito so i lost the link to his code and can't credit him properly unless i look for it again which i might do idk

anyway his code uses rpi gpio pins and i dont wanna deal with that shit right now i just want it to turn on my smart outlets

and i think his rotating buffer mechanism is wrong so i changed it. his code doesnt work in python3, only python2 so i might rewrite it later.

right now my smart outlets are connected to google home, which i talk to through my google home mini. I have a speaker attached to my raspberry pi, and for now my genius galaxy brain solution is to simply make the raspberry pi play a recording saying "okay google, lights on" instead of trying to figure out IFTTT or trying to reverse engineer IoT or whatever.

anyway yea lol im happy with this solution for now. i'll write a service file later to start this stuff on boot and then as long as i keep my phone's bluetooth enabled this will work.
