# Marlin-Artillery
Marlin adapted for Artillery Genius (3D printer)

Release notes:

8/4/2020:
Primera release publica, este firmware esta adaptado para la impresora 3D Artillery genius con todo su hardware original.
Recomiendo hacer PID para la cama y el hotend, los valores del firmware son los que funcionan para mi.

Detalles:
-Marlin 2.0.5.3
-DEFAULT_MAX_ACCELERATION      { 800, 800, 100, 5000 }
-S-Curve Acceleration 
-Enabled Z_SAFE_HOMING
-Enabled EEPROM_SETTINGS
-Enable LIN_ADVANCE, K0.17
-Disabled STEALTHCHOP_E (Es un modo de funcionamiento silencioso del extrusor, desactivado el extrusor tiene mas potencia)
