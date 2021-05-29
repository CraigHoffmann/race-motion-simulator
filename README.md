# Motion Simulator for Online Motor Racing

This is just a personal record of my motion simulator build and configuration for future reference.  This type of simulator is commonly referred to as a seatmover and is ideal for driving simulation.  The seat pivots and is driven by two motors to produce a roll and pitch action.  These two seat movements can be used to simulate vehicle roll, pitch, acceleration, sway, and verticle heave (road surface noise). I also have a seatbelt tensioner to assist in the braking simulation feel and another motor to provide traction loss motion which rotates the entire rig around a pivot point just in front of the foot pedals.

![SimSeat](https://github.com/CraigHoffmann/race-motion-simulator/blob/master/Images/sim2.jpg?raw=true)

## SMC3 Motor Driver
SMC3 is the arduino uno based motor driver software I developed for the motion sim.

![image](https://user-images.githubusercontent.com/27387872/120056720-42da9b80-c07d-11eb-8954-a2bf82b0f45e.png)

I released the code on xsimulator.net and it became one of the most popular drivers available due to it simplicity, flexibility and easy to source components.  Here is a link to the discussion thread... https://www.xsimulator.net/community/threads/smc3-arduino-3dof-motor-driver-and-windows-utilities.4957/

## SMC3 Windows Utilities
To aid in the easy configuration of the motor driver and sim setup, I also developed a windows graphical app.

![image](https://user-images.githubusercontent.com/27387872/120056817-c5fbf180-c07d-11eb-8c67-f6a8f7997dda.png)

Further details and discussion about the app can also be found on the xsimulator forum website link above.
