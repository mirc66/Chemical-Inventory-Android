# Chemical-Inventory-Android
Chemical Inventory app for android tablet 

This was an internal chemical inventory app made using MIT AppInventor.  All the chemicals in the Chemistry unit have a custom barcode with the initials of the scientist appended to begining of the numerical barcode.  So when you scan the custom barcode it would read something like JB1006 belones to scientist: John Bayer with bottle number:1006

For the purpose of our units use we barcoded the rooms, shelves, refrigerators, flammable cabinets with individual barcodes 

The  opening screen(ChemicalInvetoryFinal screen) has a selectable list of the 7 unit sientist and asks for the room, shelf/freezer/cabinet, and chemical barcode.  These three information complete describes the chemical, who it belongs to, location it can be found.  During the annual chemical inventory the technician only scans the room an location in the room barcodes and  these are automatically populated as he scans all the chemicals in one location when he needs a new location or room he just touches the input  box for that field and scans the new location.

If a new chemical needs to be entered in the inventory they use the Add new Chemical Bottle Button it opens a NewChemicalEntry form with auto populated Scientist and TemporaryID.  Here the information we require like CAS#, Hazards etc can be input.  The system assigns a TemporaryID  assuming no barcode has been assigned for the new chemical.  IF one was created you can click on the TempID field and scan the new barcode.  If it will be created later it can be entered in Excel.  The file outputs a csv file.  The new scanned outputfile can be easily correlated to the previous years inventory and the itms not found deleted or any other disposal documentation that is needed.


