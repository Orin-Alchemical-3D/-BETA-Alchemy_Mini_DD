# BETA_Alchemy_Mini_Direct_Drive
Small footprint &amp; lightweight direct drive extrusion system.

!!!!  PLEASE READ THESE NOTES PRIOR TO CONTINUING WITH YOUR BUILD !!!!

A)  I will be releasing a model cooler assembly for this hotend shortly as well, so if you do not have something that works with it right away,
please keep an eye on this repository for the design.

B)  This assembly comes in relatively close conditions to a hotend and a working stepper motor.  I will not support issues due to using materials such as PLA to build the assembly.  PLA and similar materials are NOT suitable to build 3D printer parts out of, please do not ask if PLA is ok, it is not.  If you are going to use PETG for the build, please keep an eye on the motor mount area and consider reducing current to your motor.  Steppers produce heat and PETG (while better than PLA) still has a lower TG point, it could warp.

C)  THIS IS A BETA RELEASE AND NOT THE FINAL PRODUCT, YOU ARE RESPONSIBLE FOR YOUR SAFETY AND EQUIPMENT WHEN BUILDING AND USING THIS SYSTEM AND 
YOU ACCEPT ALL LIABILITY BY USING THESE FILES FROM THIS BETA TO RELEASE CANDIDATES AND POST!

-----------------------------------------------------------------------------------------------------------------------------------------------------------

# PREFACE

This is the first rendition of the Alchemy_Mini_DD.   This system's initial design is based on the Voron Jetpack motion components and principal.  

Creation of this system was inspired by the lack of existing direct drive solutions on the market and in maker space which compare with the likes 
of the E3D Hemera and BIQU H2, etc.  Units that we as individuals, can create and assemble, from available or owned materials.  Most solutions available 
to makers are gaudy, over sized, and overweight.  These negative traits have undesirable side effects when printing creating quality and speed concerns.

Much has changed in this system from its inspirational parent products at the Voron project.   However I would like to extend a special thanks to the Voron
group for their inspiration on this product and initial designs that made all of this possible so you and I can enjoy such things.  Please take a moment if
you are not familiar with the Voron project to educate yourself on the hard work they commit to the maker space.  https://vorondesign.com/

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

1. QTY - 9 - M3x5x4 Heatsets (Voron standard heatset)

https://kb-3d.com/store/inserts-fasteners-adhesives/278-brass-heat-set-threaded-insert-for-plastic-m3x5x4mm.html

2. QTY - 3 - MR115-2RS Bearing

https://www.amazon.com/Miniature-Bearings-MR115-2RS-Double-Shielded-5x11x4mm/dp/B08PFT72RQ/ref=sr_1_5?crid=U48P0O1YAV1E&keywords=MR115-2RS+Bearing&qid=1658323589&sprefix=mr115-2rs+bearing%2Caps%2C111&sr=8-5

3. QTY - 2 - GT2 16T 5mm Shaft Pully (Note: One of these gets the top ring pulled off, be sure your pully top is not molded and not the longer version)

https://kb-3d.com/store/motion/214-gates-powergrip-2gt-pulley-16-tooth-5mm-6mm-1634481998632.html

4. QTY - 2 - M3x8 SHCS


5. QTY - 1 - 5x45 Shaft w/flat.


https://kb-3d.com/store/hardware/141-60-5mm-bearing-steel-shafts-various-lengths-1642282491009.html#/32-5mmshafts-25mm

6. QTY - 4 - M3x6 Set Screw (Note: This is basically a longer grub screw, FHCS might clear the support)

https://kb-3d.com/store/inserts-fasteners-adhesives/624-alloy-set-screw-m3-x-05-x-6mm-cup-point-1656776837999.html

7. QTY - 1 - [GT2 150T](https://www.amazon.com/BEMONOC-Timing-Belt-Closed-Loop/dp/B014QJQMJ8/ref=sr_1_1_sspa?crid=1IC9U1M0CK6E3&keywords=150mm+belt+GT2&qid=1658323968&sprefix=150mm+belt+gt2%2Caps%2C76&sr=8-1-spons&psc=1&smid=A15GNHST7KG47K&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFFUzI2WEhNV0tETEsmZW5jcnlwdGVkSWQ9QTAyMDM3NjUyWEpYQzRBMUU1VUJTJmVuY3J5cHRlZEFkSWQ9QTAxOTEzMjZXRzdTN0hZQk5ENEYmd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl) Closed Loop Belt

https://www.amazon.com/BEMONOC-Timing-Belt-Closed-Loop/dp/B014QJQMJ8/ref=sr_1_1_sspa?crid=1IC9U1M0CK6E3&keywords=150mm+belt+GT2&qid=1658323968&sprefix=150mm+belt+gt2%2Caps%2C76&sr=8-1-spons&psc=1&smid=A15GNHST7KG47K&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFFUzI2WEhNV0tETEsmZW5jcnlwdGVkSWQ9QTAyMDM3NjUyWEpYQzRBMUU1VUJTJmVuY3J5cHRlZEFkSWQ9QTAxOTEzMjZXRzdTN0hZQk5ENEYmd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl

8. QTY - 7 - M3x20 SHCS

9. QTY - 2 - M3x25 SHCS

10. QTY - 1 - BondTech BMG Extruder Internals Kit

https://kb-3d.com/store/bondtech/484-bondtech-bmg-extruder-internals-kit-build-your-own-1645151327973.html

11. QTY - 1 - Nema17 42x42x20 16Ncm (You cannot use steppers with longer bodies without modifying the system, thus noted here.)

https://www.amazon.com/Stepper-Bipolar-15-6oz-42x42x20mm-4-wires/dp/B00W96BBF6/ref=sr_1_8?crid=2COZS9H4G2S5O&keywords=pancake+stepper&qid=1657939275&sprefix=pancake+steppe%2Caps%2C101&sr=8-8

12. QTY - 1 - E3D V6 (or clone) or E3D Revo-Six (or clone) or any other hotend using the V6 style clamp mounting system.

https://gulfcoast-robotics.com/collections/hotends/products/all-metal-v6-hotend-black-edition

Highly Recommended Items Below

13. QTY - 1 - Threadlocker (Loctite Blue or similar strength)

-----------------------------------------------------------------------------------------------------------------------------------------------------------


