# DTR1
Dauphin DTR-1 garbage goes here.

To all DTR-1 travelers that may end up finding this here repo: best of luck. Some directions provided below.

1) Warnings etc:
Open your unit and recap it, for chrissakes. IT'S REALLY IMPORTANT. There's a 220uF/16V capacitor close to the parallel port that needs replacement.
Also the CMOS battery, at this point, has probably eaten a hole on the motherboard. It's attached by 4 pins which are close to the storage attachment port. Desolder that,
the aforementioned cap, and start neutralizing the alkaline goo spread by both. The internet should cover that sort of repair pretty well, but in short: white vinegar and
isopropyl alcohol. Soak in vinegar until tarnished areas appear bright copper, rinse with IPA, tin with fresh solder and good flux (important), wash flux with more iso.
Ultrasonic cleaner recommended. Furthermore, there are SMT caps on the display module. You'll have to remove the digitizer backplate. Don't try pulling the display from
the case - it can be serviced in place. I think it's 7 or 8 2.2uF x 50V caps, and one 10uF x 16V, same kind as you'd find in a Sega Game Gear. Skip the vinegar, here
you just use flux, isopropyl and qtips.

2) How to open: remove the two screws on the port cover, slide that off. Remove the 4 screws on the battery side. Slightly open the ports side, tug the backlight cable
from the inverter. Now remove the top cover. Undo the screw close to the battery contacts, and then the one midway into the board. That releases the digitizer
daughterboard, and makes you less likely to wreck the cable. Flip the board up, undo the catches on the display and LED cables, and the board should come out.
You can now carry out the remediations described above.

3) Bodges: The DTR-1 is a piece of crap. Not that it's poorly designed or anything, it was just conceived in an era where product development was clunky and costly, and
it simply didn't sell enough to iterate until it was a perfect design. As such, you'll find several layout fixes inside, depending on your board revision. (I know of 3,
more may exist)
THOSE ARE NOT DOCUMENTED, SCHEMATICS DON'T EXIST, NOT EVEN PINOUTS FOR THE CORE LOGIC EXIST. DON'T MESS WITH ANY OF IT. I BROKE A BODGE AND I'M LUCKY MY UNIT STILL WORKS.

4) Peripherals and expansion: any DTR-1 can be expanded to 6MB. If you're lucky yours is decked out. If you're less lucky you have a 2MB expansion which can have extra
chips soldered to attain 6. If you're SOL someone took out the expansion from you machine and you only have 2MB now, lol.
I'm eventually gonna replicate the memory daughterboard, and perhaps see if I can add memory beyond 6MB. Theoretically the CPU can address 16MB in total. 2 are already
on the mainboard, we'll see if at least 10MB total is feasible.

A CF card adapter can be modified to take the place of the Kittyhawk drive. My machine has a Sundisk (SanDisk nowadays) 10MB SSD and that sucks. More on that to come.
Floppies: these are usually missing the floppy drive. I've created an adaptor to allow for connecting a PC standard floppy, or Gotek. Gerbers and schems in this repo.
NOT FOR COMMERCIAL USE - I'LL SUE YOU. You're free to make as many as you'd like and distribute them to friends with DTR-1s (LOL, as if), but they are not to be sold,
not now, not EVER.

As a bonus, the adaptor allows for the connection of external IDE/ATA devices. Probably a first. After all, it's the first time since the machine was released that
someone has bothered to document the pinout. Since my own DTR-1 is a bit cruddy and corroded, I couldn't verify that it will work, but it should. Sorry about the
50-way connector alone costing 20 bucks - Dauphin picked it, not me.

Since there are no docs, chance of me copying the LAN expansion, or developing anything else, range from slim to none. Drop me a line if you have DTR-1 bits you'd be
willing to let go of. I would greatly appreciate being able to create more for this machine.
