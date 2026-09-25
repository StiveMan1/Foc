# A89503KLPTR-3-1

KiCad ID: Allegro_Drivers:A89503KLPTR-3-1.
Allegro LP eTSSOP-24, body 4.4 x 7.8 mm in footprint orientation; max height 1.2 mm.
Pads 1-24: 1.65 x 0.45 mm, pitch 0.65 mm, row centres X=±3.05 mm. Pin 1 upper left; 1-12 down left, 13-24 up right, top view.
EP: 3.00 x 4.32 mm, numbered 25 by this library. Datasheet calls it PAD without a numeric designation. Symbol must include pin 25 connected to GND (pin 1 is also GND).
Origin at body/EP centre. Courtyard 8.30 x 8.40 mm, at least 0.25 mm outside maximum body/copper envelope.
Six paste windows 1.25 x 1.20 mm, approximately 69.4% EP paste coverage: library design choice, not manufacturer stencil prescription. Peripheral pads use 1:1 paste. Thermal vias are not embedded; place them as appropriate to PCB stackup and assembly process. No 3D model included.

Source: Allegro A89503 datasheet Rev.8, Figure11 page44 (reference land pattern), terminal list page4:
https://www.allegromicro.com/-/media/files/datasheets/a89503-datasheet.pdf

Verified: KiCad loading, pad numbering, dimensions, coordinates and visual export. DRC test board connects EP to GND: 0 violations and 0 unconnected items. The GND trace in the preview is on the test board, not inside the footprint.

Add Allegro_Drivers.pretty via Manage Footprint Libraries to use in another project.
