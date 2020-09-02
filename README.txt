Open up:
Sprites\gui_global.spr

At the bottom of the file, make a new line, and add:

@include gui_addon-klingon.spr

remember the techtree entries!

// ***[ KLINGON STATIONS ]**************

kli_field_yardZ.odf		1	kyard.odf							// Klingon Field Yard
kli_field_yardP1Z.odf	2	kli_field_yardZ.odf kresear.odf		// Field Yard Central Facility
kli_field_yardP2Z.odf	1	kli_field_yardZ.odf					// Field Yard Bird of Prey Extension
kli_field_yardP3Z.odf	2	kli_field_yardZ.odf kresear2.odf	// Field Yard Special Forces Extension
kli_field_yardP4.odf	0										// Repair section of Field Yard
