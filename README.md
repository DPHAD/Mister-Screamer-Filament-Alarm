![Mister Screamer Filament Alarm](https://github.com/DPHAD/Mister-Screamer-Filament-Alarm/blob/master/Mister%20Screamer%20V2.jpg)

# The "Mister Screamer" 3D Printer Filament Alarm
A device that passively monitors the presence of 3D printer filament as a 3D printer prints.  It notifies a nearby operator with a piercing alarm (hence the name, "Mister Screamer") when filament runs out.  The idea is to give the nearby operator a chance to feed a new spool right behind the previous one so that printing can continue uninterrupted.

(This device was made as part of a short series of articles on Prototyping which I wrote for Hackaday.com. For more information, visit part one at http://hackaday.com/2017/01/27/lets-prototype-this-filament-end-needs-80-decibels/ and part two http://hackaday.com/2017/06/07/improving-mister-screamer-an-80-decibel-filament-alarm/ )

The design consists of a piece of hardware that is sensitive to orientation. When hanging vertical, it is unpowered and silent. When it is laying flat, the alarm goes off. This is done by means of a disc magnet in a channel that holds the magnet away from a reed switch while vertical, and ramps it down towards the reed switch when horizontal.

To do the job of filament monitoring, it dangles (rather like a keychain) from the filament line being fed into a 3D printer's extruder. When the spool runs out, the device falls to the tabletop and begins a piercing audio alarm.

This design may not be suitable for every 3D printer out there, since they come in so many shapes and sizes and filament orientations, etc. Your printer may not be able to use this device without the device getting in the way of something. It works great for me, but your results may vary.

# Inside and Parts
Inside the device is a CR2032 coin cell, a 3V buzzer, a (normally open) reed switch, and a small disc magnet. The wiring is simple: when the magnet triggers the reed switch, the circuit is closed and the buzzer is powered.

The battery area has a small amout of space for small wire or strips of metal to be used as battery contacts. I used a small spring-loaded battery contact for the negative side, and a strip of solder braid for the positive side.

The enclosure is held shut with a nylon M3 bolt and nut, and the pressure holds the battery contacts firmly to the coin cell. The device hangs by a ball link chain (like those found on keychains.)

Electrically the negative side of the coin cell goes to the negative lead of the buzzer. The positive lead of the buzzer goes through the reed switch, to the positive side of the coin cell.  When the magnet closes the reed switch, the circuit is completed.

# List of Parts
These are the parts I used, if you use different parts be ready to modify the 3D model to fit.

CR2032 3V Coin Cell

Ball chain (from a keychain)

Reed Switch, NO - Digi-key part #HE667-ND 

Disc Magnet : I used 6mm dia x 1.5mm thick, but as low as 1mm thick and as wide as 8mm should work as well.

Negative battery contact - Digi-key part #36-112CT-ND : soldered to a thin wide and glued to the flat bottom of the battery cavity.

Positive battery contact - I used a piece of solder braid, a piece of bare wire should work as well.

Buzzer, 2-5V - Digi-key part #458-1063-ND : in a pinch even 4-6V buzzers seem to work OK with a 3V coin battery.
