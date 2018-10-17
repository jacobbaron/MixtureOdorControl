# MixtureOdorControl
Experiment control for odor mixture apparatus. For use with a microfluidic mixing device and Fluigent microfluidic flow meter + pressure controller. 
## Features
* Allows for up to 16 odors, and up to 10 odors may be present in a mixture. Dilution can be adjusted (requires recalibration).
* Integrates with [Andor Acquire](https://github.com/jacobbaron/AndorAcquire) to syncronize timing between camera and odor manifold.
![Setup Panel](https://github.com/jacobbaron/MixtureOdorControl/blob/master/Images/Odor_panel.PNG?raw=true)
* Easy choice of which odors to deliever at each stimulus step. Below is shown an experiment in which an odor is added to the stimulus at each step until there are 10 odors. 
![Odor Sequence Panel](https://github.com/jacobbaron/MixtureOdorControl/blob/master/Images/Odor_sequence.PNG?raw=true)
* Automatic calibration of pressures for the microfluidic system. Pressures depend on dilution and number of odors present in mixture.

![Flow Control Panel](https://github.com/jacobbaron/MixtureOdorControl/blob/master/Images/flow_control.PNG?raw=true)
