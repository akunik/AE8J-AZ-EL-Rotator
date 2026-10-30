# AE8J-AZ-EL-Rotator
Azimuth and Elevation antenna rotator for satellite tracking. Rotator is completely 3D printed. I'm using PETG but any suitable filament can be used. Stepper motors are 23HE22-2804S with a holding torque of .9 ft-lb. 3D printed 50:1 split ring planetary gear reducers are used in each axis. An additional 2:1 spur gear reduction increases the theoretical holding torque to 90 ft-lbs.

Rotator controller uses an Arduino mega 2560 and is driven by the excellent K3NG AZ EL Rotator code. A 20x4 I2C LCD displays the current AZ EL positions as well as Commanded positions. Controller includes a NEO GPS module to display local time and your maidenhead grid square. Pushbuttons are incorporated for manual rotation. RJ45 connectors are used for both stepper motors and potentiometers. This allows the use of off-the-shelf CAT 6 cables of any desired length. Connection to the computer is by a standard USB cable. Stepper motors supply voltage can range from 12 to 36 volte DC.

All 3D printed components were designed in FreeCAD. Files will be released in .FCStd format to allow customization, improvements and addition of new features by all users.
