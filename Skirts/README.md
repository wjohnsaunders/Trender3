# Trender3 Skirts

The skirts are a redesign that moves away from the Trident hexagons.
The additional difference is that the side skirts have the same look
as the front/rear skirts, which allows fingers to grip the sides for
carrying the printer.

I initially wanted to only do a left and rigth skirt from the back and
sides. However a prototype print showed that it was very hard to install
the second skirt, so I went with 3 skirts per side. The up-side was that
the front left/right skirts could also serve the sides, reducing the
number of designs that I needed to do.

## Front

### Print BOM

- 1x Trender3Skirts-MkII-FrontAndSidesStyleA
- 1x Trender3Skirts-MkII-FrontAndSidesStyleB

#### Headless Option
- 1x Trender3Skirts-MkII-CenterDoubleMountingBoltWidth117 (for headless)

#### Trident 12864 Option

- 1x mini12864_case_front
- 1x mini12864_case_rear
- 1x [a]_mini12864_case_front_insert
- 1x [a]_mini12864_case_hinge

Note: Files from Trident STL package

### Description

I have kept the center available for one of the Trident screen options.
Hopfully any screen that fits in the standard space on a Trident will fit.
There is also a no-screen skirt that keeps the Trender3 style for headless
builds.

Measurements: 268 (243 not including the feature)
Front Left/Right width: 75 (62.5 not including the feature)
No-screen skirt width: 117
Trident screen mount width: 117

## Sides

### Print BOM

- 2x Trender3Skirts-MkII-FrontAndSidesStyleA
- 2x Trender3Skirts-MkII-FrontAndSidesStyleB

#### Single Fan Option

- 1x Trender3Skirts-MkII-FanMount60mm
- 1x Trender3Skirts-MkII-FanCarrier60mm
- 1x Trender3Skirts-MkII-FanGrill60mm
- 1x Trender3Skirts-MkII-CenterDoubleMountingBoltWidth113

#### Dual Fans Option

- 2x Trender3Skirts-MkII-FanMount60mm
- 2x Trender3Skirts-MkII-FanCarrier60mm
- 2x Trender3Skirts-MkII-FanGrill60mm

### Description

The front left/right skirts are re-used, and the center skirt carries the
fan. There is a fan option for the standard 6020 Trident fan, but also for
dual 4010 axial fans as used on the Ender3 for the electronics bay cooling
and the hotend cooling.

Measurements: 264 (239)
Front Left/Right width: 75 (62.5 not including the feature)
Fan skirt width: 113

## Back

### Print BOM

- 1x Trender3Skirts-MkII-LeftSideRear-Ender3
- 1x Trender3Skirts-MkII-RightSideRear
- 1x Trender3Skirts-MkII-CenterSingleMountingBoltWidth41

### Description

The back of the Trender3 has a skirt with cutouts for the Ender3 inlet.
It has a narrow center skirt in addition to the right side skirt. It is
the only side that doesn't follow the narrow sides and wide center style,
but it is discated by needing an inlet, and a center inlet is blocked by
the rear stepper.

Measurements: 268 (243 not including the feature)
Back Left/Right width: 113 (100.5 not including the feature)
Back Center width: 41
