
<p align="center">
  <a href="" rel="noopener">
 
<img src="PartRenders\Simplicity.png"></a>
</p>

<h1 align="center">Parts List</h1>

## BOM

Big Parts:
 - Control Board - I recommend SKR Pico with raspberry pi and klipper, but you can use whatever printer board you have access to.
 - 3x NEMA 17 stepper motors less than 40mm in length (For XYZ axis).
 - Extruder and Stepper - Any you have available. The stock Creality will fit but i recommend a dual gear like the bondtech BMG clones available from ali-express or amazon.
 - Hot End - Again, creality ender/CR10 hot end is fine but i recommend a high flow nozzle. im using a cheep volcano block and nozzle from amazon.
 - Bed - 120x120mm beds compatible with Voron V0 or Rook should fit. Otherwise Im using a diy bed made from a 150x150mm scrap of aluminum with V0 compatible mounting. If not using a printed bed i have seen some Rook's with printed beds. 
 - Power supply - whatever you can find 24V PSU is ideal but im just using a 20V 6.5A Dell laptop supply, its a little less powerfull but much easier to mount externally.
 - 3010 fan for hot end.
 - Optional 120mm radial blower for part cooling.

Bearings & Drive:
 - 3x 150mm MGN9 rails with MGN9C carriages
 - 4x 8mm smooth rods 200mm length.
 - 2x LM8UU Long 45mm bearings (dual short bearings might work instead but not tested)
 - 1x 8mm lead screw and nut, ~150mm length
 - 20x F695 Bearings (5x13x4 flanged). Usually available in sets of 10.
 - 8x F623 Bearings (3x10x4 flanged). Usually available in sets of 10.
 - 2x 20T GT2 pulleys.
 - 2m of Gates GT2 Belt
 - 2x 5mm to 5mm motor couplers
 - 1x 5mm to 8mm motor coupler 
 - 2x 160mm 5mm rod (steel, aluminum, carbon, shouldn't matter what)

Hardware: 
 - 24 M2.5 x 8mm self tapping screws (i used Torx T10, will try find a good link ASAP)
 - 6 M2.5 x 16mm self tapping screws (i used Torx T10, will try find a good link ASAP)
 - 6x M5x30 CSK
 - 2x M5x25 CSK (+4 if using my electronics tray)
 - 2x M5x25 Cap Head (tension adjusters so cap or dome works too)
 - 8x M5 Heatset Inserts (+4 if using my electronics tray)
 - 20x M5 Washer (should be 1mm thick)
 - 8x M3 Washer (should be 0.5mm thick)
 - 8x M3x25 Cap Head (or dome head if your a sadist)
 - 4x M3x6 Cap Head (see above)
 - 12x M3x8 CSK (for stepper motors)

---

## Printed Partrs

I have been printing all parts in ABS+ as i plan to print PETG in the future, but if you only plan to print PLA i would expect a PLA frame to be fine.

I sliced with 0.2mm layers, 15% infill, 3 perimiters and 4/5 bottom/top layers.

Total filament used was around 430g and total print time was around 24 hours on my ender 5 plus with conservative speed settings.

### Frame Base
The base is the largest part. it should print top side down.
<p><img src="PartRenders\SimplicityBase.png" width="400" height="300"></a></p>

### Frame Mid and Frame Top
These 2 parts bolt together to form the main top assembly.
<p><img src="PartRenders\SimplicityTop.png" width="400" height="300"></a>
<img src="PartRenders\SimplicityMid.png" width="400" height="300"></a></p>

### Tensioner (x2)
You need 2 of these. They hold the adjustable belt pulleys to tension the belt. They should sit flat on the bed with the widest part of the slope at the bottom. 
<p><img src="PartRenders\SimplicityTension.png" width="400" height="300"></a></p>

### X Gantry
Printed on its back with the rail surface on the top.
<p><img src="PartRenders\SimplicityX.png" width="400" height="300"></a></p>

### Print Head
Printed on its back.
<p><img src="PartRenders\SimplicityPrintHead.png" width="400" height="300"></a></p>

### Bed
Printed with the large flat side down, a small amount of support is usually needed for the overhand near the nut for the threaded rod
<p><img src="PartRenders\SimplicityBed.png" width="400" height="300"></a></p>

### Extruder mount
Optional part that will alow for easy mounting of most extruders that use a standard stepper motor. I have used both the original Creality extruder as well as the bondtech Clone shown in my photos.
<p><img src="PartRenders\SimplicityExtruderMount.png" width="400" height="300"></a></p>

### Electronics mount
Optional part that will alow for easy mounting of raspberry Pi and SKR Pico driver board. if your using something else this part can be modified to support different control boards.
<p><img src="PartRenders\SimplicityElectronics.png" width="400" height="300"></a></p>

### Cooling
This is a quick bodge to add an RCS style part cooling fan. its not optimized but it will get you going. it takes a 120mm blower fan. It fits mine, I dont know if they are all the same or not.
<p><img src="PartRenders\SimplicityRCS.png" width="400" height="300"></a>
<img src="PartRenders\SimplicityRCS2.png" width="400" height="300"></a></p>

### Draft Shield (Guard)
CURRENTLY UNTESTED - This is a simple print that can be printed in vase mode and is designed to provide a semi inclosed bed, offering a little protection from drafts. Its not compatible with the cooling fan above
<p><img src="PartRenders\SimplicityGuard.png" width="400" height="300"></a></p>