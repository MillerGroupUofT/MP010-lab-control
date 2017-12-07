# Operature procedure for MP010 laser system

## Turn on procedure for MP010 laser rod amplifier
1. Turn on the water chiller.  Usually, it will be set to 22.5° C.
2. Turn on the oscillator.
  1. Turn on the oscillator power supply/temperature controller.
  2. Press the left side “adjust on” button to turn on the temperature control.
  3.	Press the right side “adjust on” button to enable current to the oscillator diode.
  4.	Switch “display to ILD to display the present current.
  5.	Open Picoscope 6 on the computer to monitor the laser output (to confirm modelocking).
  6.	Turn up the current at a medium pace using the dial under “adjust on” on the right side up to 600 mA. Ensure that modelocking has started – a pulse train should be visible in Picoscope 6.
3.	Turn on the AOM for the preamps.
  1.	Turn on the “AOM” function generator.
  2.	Turn on the Circuit Test power supply with positive leads unplugged.
  3.	Switch the mode on the Circuit Test power supply to independent using the black button in the center.
  4.	Plug in the positive leads of both outputs.
4.	Turn on the fibre preamps.
  a.	Turn both preamp (“Preamp A” and “Preamp B”) power supplies on following the same steps as 2a-2d (the order in which the power supplies are turned on is not important).
  b.	Turn preamp A current to ~600 mA at a medium pace.
  c.	Turn preamp B current to ~300 mA at a medium pace.
5.	Open the shutter of the preamp box, ensure that the laser is present with a detector card or IR viewer.
6.	Turn on the Laser Electronics controller for the fibre amplifier by turning the key.
7.	Change the trigger mode on the AOM function generator to “external” (press “trig” and then use the arrow keys to switch to “external”).  Make sure the “rate” indicator light is lit up in red, if not, return the trigger mode to “internal” and diagnose the problem.
8.	On the Laser Electronics controller, navigate in the menu so the cursor is pointing to “power” then press the “laser on” button.
9.	Turn on the Xantrex power supply for the rod.
  a.	Make sure the current is turned all the way down.
  b.	Open the rod emergency shutdown (turn the button so that is in the up position).
  c.	Press standby on the Xantrex power supply.
10.	Turn up the fibre amplifier power until the optical interlock for the rod is met.  
  a.	If the interlock has been met, the light above the current knob on the Xantrex power supply should turn on, and the light above “standby” should turn off.  This will usually happen at ~13W.  
  b.	Continue increasing the power to ~17W. Note: Several watts of laser power will be coming out of the rod at this point.
11.	Turn up the power for the rod diode.
  a.	Start the monitoring program (FibreRod Monitor) on the computer.
  b.	Scan for devices.
  c.	Start monitor.
  d.	Turn up the current on the Xantrex power supply SLOWLY, while monitoring the power and temperature on the FibreRod Monitor program – If sudden jumps in temperature are detected, stop and diagnose for a problem. A threshold is expected around 2A.
  e.	When 10W is reached, ensure that there is an increase in the rod output power using the power meter in the beam path.
  f.	Continue increasing the power SLOWLY to the desired level (tested up to 40W as of 06/12/2017).

## Turn off procedure:
The laser can be safely turned off following the steps above in reverse.
Important points:

1.	Never leave the rod pumped if it is not seeded.
2.	After turning off the rod diode power, put the Xantrex power supply on standby and close the rod’s ememrgency stop (the button should be in the down position).
3.	Leave the Laser Electronics power supply on for 5-10 minutes after turning off the laser to allow the temperature to stabilize.
4.	Turn the AOM controller to internal before turning off the oscillator (the modelocked signal is used for the external trigger).
5.	Leave the temperature controller on the preamps on for a few minutes after turning off the current to allow the temperature to stabilize.
