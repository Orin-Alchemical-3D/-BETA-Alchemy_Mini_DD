# BETA_Alchemy_Mini_Direct_Drive
Small footprint &amp; lightweight direct drive extrusion system.

# Join the community discussion, get assistance, or even show off your mods!  
# DISCORD: https://discord.gg/aE49DW2xXe

-----------------------------------------------------------------------------------------------------------------------------------------------------------

!!!!  PLEASE READ THESE NOTES PRIOR TO CONTINUING WITH YOUR BUILD !!!!

A)  I will be releasing a model cooler assembly for this hotend shortly as well, so if you do not have something that works with it right away,
please keep an eye on this repository for the design.

B)  This assembly comes in relatively close conditions to a hotend and a working stepper motor.  I will not support issues due to using materials such as PLA to build the assembly.  PLA and similar materials are NOT suitable to build 3D printer parts out of, please do not ask if PLA is ok, it is not.  If you are going to use PETG for the build, please keep an eye on the motor mount area and consider reducing current to your motor.  Steppers produce heat and PETG (while better than PLA) still has a lower TG point, it could warp.

C)  THIS IS A BETA RELEASE AND NOT THE FINAL PRODUCT, YOU ARE RESPONSIBLE FOR YOUR SAFETY AND EQUIPMENT WHEN BUILDING AND USING THIS SYSTEM AND 
YOU ACCEPT ALL LIABILITY BY USING THESE FILES FROM THIS BETA TO RELEASE CANDIDATES AND POST!

-----------------------------------------------------------------------------------------------------------------------------------------------------------

# PREFACE

This is the first rendition of the Alchemy_Mini_DD.   This system's initial design is based on the Voron Jetpack motion components.  

Creation of this system was inspired by the lack of existing direct drive solutions on the market and in maker space which compare with the likes 
of the E3D Hemera and BIQU H2, etc.  Units that we as individuals, can create and assemble, from available or owned materials.  Most solutions available 
to makers are gaudy, over sized, and overweight.  These negative traits have undesirable side effects when printing creating quality and speed concerns.

Much has changed in this system from its inspirational original product at the Voron project, simply put... everything changed and it really is not the same unit.   However I would like to extend a special thanks to the Voron group for their inspiration on this product and initial designs that made all of this possible so you and I can enjoy such things.  Please take a moment if you are not familiar with the Voron project to educate yourself on the hard work they commit to the makerspace.  https://vorondesign.com/

This product's initial design is centered around using with one of the most popular printers available today, the Creality Ender.   Its designed to work with the stock bolting pattern of the system.  In the very near future, additional models of this will be released to facilitate mounting on other popular systems available today, as well as variations of the system to provide more hotend compatibility.   Upcoming target printers include Prusa, Artillery, Tevo, etc.   As the product evolves so will each variation.

Upcoming models of this will include a Bowden version and a Micro version each serving their purpose with a unique twist.  The bowden is going to have some tricks up its sleeve you will not have ever seen to further improve print quality, while the micro version is going to take lightweight toolhead to the extreme.  Keep an eye out for these models as soon as this initial product leaves beta.

Once this product leaves beta, along with the additional variations, scheduled is an entire 3D print based on the principles these units bring.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

# PRINT SETTINGS

Materials - ABS/ASA

Layer Height - 0.20

Extrusion Width - Forced 0.4m

Infil Percentage - 40%+

Infil Type - Grid, Honeycomb, Triangle, or Cubic

Top/Bottom Wall Count - 4

Perimeter Count - 4

-----------------------------------------------------------------------------------------------------------------------------------------------------------

# B.O.M.  
Note: I am working with suppliers to distribute individual qty purchases, this early in project though some of these are multipacks.

Note: This is the bare minimum, it is wise to have spare screws/heatsets etc.)

1. QTY - 9 - [M3x5x4 Heatsets](https://kb-3d.com/store/inserts-fasteners-adhesives/278-brass-heat-set-threaded-insert-for-plastic-m3x5x4mm.html) (Voron standard heatset)
2. QTY - 3 - [MR115-2RS Bearing](https://www.amazon.com/Miniature-Bearings-MR115-2RS-Double-Shielded-5x11x4mm/dp/B08PFT72RQ/ref=sr_1_5?crid=U48P0O1YAV1E&keywords=MR115-2RS+Bearing&qid=1658323589&sprefix=mr115-2rs+bearing%2Caps%2C111&sr=8-5) 
3. QTY - 2 - [GT2 16T 5mm Shaft Pully](https://kb-3d.com/store/motion/214-gates-powergrip-2gt-pulley-16-tooth-5mm-6mm-1634481998632.html) (Note: One of these gets the top ring pulled off, be sure your pully top is not molded and not the longer version)
4. QTY - 1 - [5x45 Shaft w/flat](https://kb-3d.com/store/hardware/141-60-5mm-bearing-steel-shafts-various-lengths-1642282491009.html#/32-5mmshafts-25mm) (You can either find one with flats already, or add them yourself using a dremmel or other tool.)
5. QTY - 4 - [M3x6 Set Screw](https://kb-3d.com/store/inserts-fasteners-adhesives/624-alloy-set-screw-m3-x-05-x-6mm-cup-point-1656776837999.html) (Note: This is basically a longer grub screw, FHCS might clear the support)
6. QTY - 2 - M3x8 SHCS (Socket Head Cap Screw)
7. QTY - 7 - M3x20 SHCS (Socket Head Cap Screw)
8. QTY - 2 - M3x25 SHCS (Socket Head Cap Screw)
9. QTY - 1 - [BondTech BMG Extruder Internals Kit](https://kb-3d.com/store/bondtech/484-bondtech-bmg-extruder-internals-kit-build-your-own-1645151327973.html) (Some clones have the correct components for this build internally)
10. QTY - 1 - [GT2 150T](https://www.amazon.com/BEMONOC-Timing-Belt-Closed-Loop/dp/B014QJQMJ8/ref=sr_1_1_sspa?crid=1IC9U1M0CK6E3&keywords=150mm+belt+GT2&qid=1658323968&sprefix=150mm+belt+gt2%2Caps%2C76&sr=8-1-spons&psc=1&smid=A15GNHST7KG47K&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFFUzI2WEhNV0tETEsmZW5jcnlwdGVkSWQ9QTAyMDM3NjUyWEpYQzRBMUU1VUJTJmVuY3J5cHRlZEFkSWQ9QTAxOTEzMjZXRzdTN0hZQk5ENEYmd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl) Closed Loop Belt
11. QTY - 1 - [Nema17 42x42x20 16Ncm](https://www.printedsolid.com/collections/electronics/products/ldo-nema-17-motor-super-slim-ldo-42sth20-1004as1) (You cannot use steppers with longer bodies without modifying the system, thus noted here.)
12. QTY - 1 - [E3D V6 (or clone)](https://gulfcoast-robotics.com/collections/hotends/products/all-metal-v6-hotend-black-edition) or [E3D Revo-Six](https://kb-3d.com/store/extruders-hotends/425-e3d-rapid-change-revo-hotend-six-24v-1640229946834.html) or any other hotend using the V6 style clamp mounting system.

Highly Recommended Items Below

13. QTY - 1 - Threadlocker (Loctite Blue or similar strength, its important to note that threadlockers WILL damage ASA/ABS if they come in contact, take care when applying thread lockers that it only gets on the metal assembly.)

-----------------------------------------------------------------------------------------------------------------------------------------------------------


