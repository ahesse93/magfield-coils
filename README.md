# magfield-coils
Calculates the behaviour of magnetic field coils based on their geometry and the desired magnetic field strength

Uses [Radia](http://www.esrf.eu/Accelerators/Groups/InsertionDevices/Software/Radia) 

Be aware, that the RL-bandwidth calculated is valid for voltage, not current - you can drive current much faster through the coil, and you're basically limited by your driver / the maximum voltage it can provide. Small L and R are beneficial, as it's easier to drive current quickly then.
