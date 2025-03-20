# C64MechanicalKeyboard
All you need to create a true modern mechanical keyboard for the C64

Instructions for building a mechanical keyboard for the C64 (all versions)
Based on a PCB designed by MtnBuffalo (https://www.breadbox64.com/blog/the-mechboard64/)

and all the other (3D printing) stuff designed by Wolfgang Kierdorf (https://www.youtube.com/@RetroWK)


Step 1: Get the material
- The Mechboard64 PCB by MtnBuffalo (order it here: https://www.pcbway.com/project/shareproject/The_MechBoard64_1.html)
- The free STL-files from this GitHub-Repo
- C64 keycaps (the ones with the cross inside) old or new ones (https://www.cbmstuff.com/index.php?route=product/category&path=83&limit=100)
- 66 mechanical key switches (https://de.aliexpress.com/item/1005007865371679.html)
- Some lubricant (like silicone grease) (https://de.aliexpress.com/item/1005007204626264.html)
- Space bar stabilising wire (or some 1.2mm thick wire (https://www.amazon.de/gp/product/B0D6G6N9BK?th=1) and pliers to make one)
- Space bar stabilising plastic things (the white ones inside the key) or print some with the free STL-files
- 19 Dupont cables or an old 40 pin IDE cable
- 3D printer filament for the keyboard shell (https://de.aliexpress.com/item/1005005937405325.html)
- 3D printer filament for the key adapters and the space bar support inserts (https://de.aliexpress.com/item/1005005992077485.html)
- 20 pin header (90 degree angled)
- 2 x 3 pin header (straight)
- (Optional) Parts for the shift key circuit (if you want the shift lock key to work)

Step 2: Print the parts
- Print the key adapters with border only (no other supports) in SUNLU filament. You need 57 single key adapters, 8 double size key adapters and 1 triple size key adapter. 
- Print the keyboard shell with supports on the sides in Geeetech filament. The part where the keys go in faces the bottom. You can print either two halves (which fit a 20x20 print bed) oder the whole keyboard shell at once.
- Print the space bar support inserts (for the keyboard shell) with border and minimal support (in either SUNLU or Geeetech filament).
- Print the space bar support inserts (for inside the keys) with border and minimal support (in either SUNLU or Geeetech filament).

Step 3: Clear the prints
- Remove the support material from the keyboard shell.
- Remove the border from the key adapters using a flush cutter.
- Remove the border and the support from the space bar support inserts. Watch out, the space bar supports that go inside the space bar are SUPERBRITLE!

Step 4: Soldering
- Put the 20 pin header on the backside of the PCB (the side which says MechBoard64 in the lower left corner), then solder it in from THE OTHER side (solder goes on the side that does NOT say MechBoard64!). If you want to use the keyboard with a longboard 64 (breadbin, use J1, otherwise use J2. The solder in the two 3 pin headers at J3.
- If you want the shift lock to work, you can now solder the Shift Lock Circuits surface mount parts. The keyboard works fine without them, all you loose is the shift lock … I never used that anyway!
- These are the parts that you need:
- R1/R4 = 10K resistor
- R2 = 100K resistor
- R3 = 56K resistor
- C1 = 1UF cap
- C2 = 10NF cap

Step 5: Assembly
- Cut of the two small plastic pins on the back of EVERY key switch (NOT the metal pins and NOT the big pin in the middle!)
- Grab the two plastic halves of the keyboard shell and put in the key switches. Make sure to leave the bottom left and right holes empty (That’s where the space bar stabilising parts go). Leave out the keys in the keyholes that are split up (in the middle of the keyboard shell when assembled) for now. When inserting the switches, make sure to press on down on the center of the key (with your thumb), while supporting the back of the shell with your index and middle finger. Make sure that the two metal pins of the key switch are in the upper left corner (when putting it into the keyboard shell).
- Put in the two space bar supports in the lower left and right holes on the keyboard shell. Attention: There is one for left and right (and they are different). There is an L or an R on top of the part. The L goes on the left, the R on the right side (when the F-keys are at your right side).
- Make sure that all the contacts (the metal pins on the keys) are straight.
- Take the left half of the keyboard shell (NOT the one with the F-keys), turn it around and gently place the PCB in it. All the middle pins and contacts should align with the holes in the PCB. Then press the keys parts together, making sure, that no key pops out.
- If you are sure, that all the keys are in the PCB properly, go and solder some of the keys on the sides, push down on every key while soldering or press down the whole keyboard on the desk. The keys must sit flush to the keyboard shell.
- Take the right half of the keyboard shell (the one with the F-keys), turn it around and gently place the PCB in it. All the middle pins and contacts should align with the holes in the PCB. Then press the keys parts together, making sure, that no key pops out.
- If you are sure, that all the keys are in the PCB properly, go and solder some of the keys on the sides, push down on every key while soldering or press down the whole keyboard on the desk. The keys must sit flush to the keyboard shell.
- Check your work. If all the keys are still in it and flush, go and solder them all in, making sure, that EVERY key sits flush BEFORE soldering!
- Put the key adapters into the key caps: Take a keycap, put in the adapter (the cross goes into the cap) making sure it is straight. Turn the key around and push the key hard on the table. The adapter should go in and click. If the adapter breaks, you used the wrong filament. Repeat for all single keys. For the RETURN key use the largest of the adapters. Push it in with you fingers, don’t push it on the desk. Same for the 8 special keys: CTRL, SHIFT, SHIFT, RESTORE, F1, F3, F5, F7. All the special keys have the adapter (the part that goes into the keyswitch) on the right side. The RESTORE key has it on the left (just turn the adapter around ;-))
- Put the keys (except for the space bar) into the keyboard.
- Put the white plastic supports (the ones you stole from the C64 or printed) into the space bar.
- Put the metal thing into the plastic supports (the wire faces you).
- Put the space bar onto the keyboard.
- Put the wire into the support taps (using pliers or your super flat fingers).
- Use some grease to grease the parts where the wire meets plastic (on the space bar supports and the white plastic things inside the key).
- Connect the 19 Dupont wires (or IDE cable) to the pin header on the backside of the keyboard. Pin 1 on the C64 is the one that is alone - make sure to connect the cable so that pin 1 connects to pin 1 etc.
- Put the keyboard into a C64.
- Type away! Have fun!
