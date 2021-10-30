# Macintosh-Classic-Reloaded
A 1:1 Recreation of the Macintosh Classic logic board

As with the Macintosh SE, many Classic's have died because of Apple's short sighted decision to add a battery to the board - and unfortunately a particularly explosive one at that! This will inevitably pop and causes a horrific amount of damage.

Thankfully, because i've done this before, with the Macintosh SE, I decided to make a near 1:1 reproduction of the board, using Sprint Layout v6.0 again.

The Maxell batteries fitted to most classics, when they explode, will eat away at the component legs, tracks and via's if the battery electrolyte is left too long. Luckily almost all the other parts can be replaced with modern equivalents.

In the Macintosh Classic, the battery is placed in the bottom left hand corner of the board, underneath the RTC chip and to the left of the CPU. Mostly the damage is confined to this area, but if the system has been left a long time, you may discover the damage reaching beyond the SND chip (which is vital for generating the /RESET) functionality for the CPU and the board is essentially wrecked at this point.

Unlike the Macintosh SE, the PLCC versions of the SND and the RTC chip are not readily available and in the event of a total loss, will have to be salvaged from machines of a similar vintage.

The Macintosh II, IIx, IIfx, IIcx, IIci and IIsi all use the same SND and RTC chips - so if you have a destroyed/non-working board, you can salvage them from there.

As with the Macintosh SE board - there are other components than the custom chips that should be salvaged when possible, the 6-pin inductors/ferrite beads, the reset & programmers switch, RAMexpansion connector and headphone jack and try, if you can, to save the R/C network filters if possible, as these can be expensive to replace (sometimes £4 to £6 each!) Last but not least the DB-19 external Floppy connector, assuming the shell and pins haven't been eaten away by rust/battery electrolyte.

While it is possible to source some of the Apple custom IC's from resellers and chinese inventory warehouses, the supply cannot be guaranteed, so it is imperative that as many of the custom IC's are salvaged.

These boards aren't quite enough to build a new Macintosh SE from scratch (maybe one day, though!) - so you'll need to harvest a few parts from your donor board.

* **RAM Expansion Socket - 2 row, 44-pin connector - may be possible to substitute an IDC header.

* **DB19 Connector - Almost NLA, only really available as NoS or Reclaimed. These are a bastard to get out cause the lugs are soldered. I found that pre-heating the joint first, filled with flux, then pressing hard into the pad with the desoldering gun, waiting til you see the solder go molten, you can often schlorp out the majority of the solder and then tidy up with wick afterwards.

NoS ones available from https://www.exxoshost.co.uk/atari/store2/ - search for DB19F ASCI PCB RA POST

* **Main 14-pin Molex - Molex P/N 39-28-1143 - Still available new - costs less than £2. Get a new one.

* **Inductors & Ferrite beads

* **Passives - REPLACE ALL - use high tolerance metal film resistors & Nichicon or Panasonic electrolytics.

* **AM26LS30's - NLA, only available as NoS or Reclaimed

* **AM26LS32's - Available new, but still worth reclaiming

* **MC3488A - NLA - replace with Texas Instruments SN75150

* **Rockwell 338-6523 - This is the 65C22N VIA, still available new as the W65C22S6TPLG-14

* **RTC Chip - Custom Chip - maybe possible to clone using a flex-PCB/ATTiny Chip

* **ADB Chip - Apple branded PIC16CR54 in a PLCC package - maybe possible to re-produce/clone

* **BBU Chip - Custom Chip - identical in pinout to the Macintosh SE

* **NCR5830/AM58C30 SCSI Chip - Reclaim, but if not possible, these can be purchased from Mouser, as ZiLOG still makes them under the part number Z53C8003VSG

* **SWIM Floppy Chip - Custom Chip - available NoS from UTSource

* **ROM Chip - Toshiba TC534200 MASK ROM - Reclaim & reuse, but these are the same pinout as 27C040

![Finished Logic Board](/macclassicboard-final-rev12-release.jpg)
![Finished Logic Board - Bottom](/macclassicboard-final-rev12-release-rear.jpg)
