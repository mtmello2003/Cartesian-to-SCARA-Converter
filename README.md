# Cartesian-to-SCARA-Converter
This script will convert gcode from cartesian space to SCARA space


There are better ways to go about doing this, but this way allowed me to stay hardware agnostic until I decided what hardware I would choose.

----------

Update: I forked this project from the original author to change it a little bit, in order to run it in a scara drawbot (3d printed project from thingiverse - a robot arm), using an arduino uno + cnc shield + GRBL firmware (that isn´t able to work native with scara kinematics)

The prior idea is compile the original GRBL (maybe 0.9 version) into the arduino UNO and use this script to change the cartesian to scara moves before send the gcode to the arm.
