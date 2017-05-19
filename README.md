# The "Mister Screamer" 3D Printer Filament Alarm
A device that passively monitors the presence of 3D printer filament as a 3D printer prints.  It notifies a nearby operator with a piercing alarm (hence the name, "Mister Screamer") when filament runs out.  The idea is to give the nearby operator a chance to feed a new spool right behind the previous one so that printing can continue uninterrupted.

(This device was made as part of a short series of articles on Prototyping which I wrote for Hackaday.com. For more information, visit http://wp.me/pk3lN-14TA )

The design consists of a piece of hardware that is sensitive to orientation. When hanging vertical, it is unpowered and silent. When it is laying flat, the alarm goes off.

To do the job of filament monitoring, it dangles (rather like a keychain) from the filament line being fed into a 3D printer's extruder. When the spool runs out, the device falls to the tabletop and begins a piercing audio alarm.

This design may not be suitable for every 3D printer out there, since they come in so many shapes and sizes and filament orientations, etc. Your printer may not be able to use this device without the device getting in the way of something. It works great for me, but your results may vary.

# Inside and Parts
Inside the device is a CR2032 coin cell, a 3V buzzer, a (normally open) reed switch, and a small disc magnet. The wiring is simple: when the magnet triggers the reed switch, the circuit is closed and the buzzer is powered.

The enclosure is held shut with a nylon M3 bolt and nut, and the pressure holds the battery contacts firmly to the coin cell. The device hangs by a ball link chain (like those found on keychains.)
