# Marlin-Artillery
<b>Marlin adapted for Artillery Genius</b> (3D printer)
<p>Guia de flasheo: https://3dprintbeginner.com/artillery-genius-firmware-with-marlin-2-0-1/</p>

<p>Release notes:</p>
<br><b>8/4/2020:</b>
<p><br>Primera release publica, este firmware esta adaptado para la impresora 3D Artillery genius con todo su hardware original.
<br>Recomiendo hacer PID para la cama y el hotend, los valores del firmware son los que funcionan para mi.</p>

<p>Detalles:
<br>-Marlin 2.0.5.3
<br>-DEFAULT_MAX_ACCELERATION      { 800, 800, 100, 5000 }
<br>-S-Curve Acceleration 
<br>-Enabled Z_SAFE_HOMING
<br>-Enabled EEPROM_SETTINGS
<br>-Enable LIN_ADVANCE, K0.17
<br>-Disabled STEALTHCHOP_E (Es un modo de funcionamiento silencioso del extrusor, desactivado el extrusor tiene mas potencia)</p>
