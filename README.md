# Main MIDI Controller firmware

⚠️ Under construction

The program starts with the setup, initializing the necessary variables and setting up the NeoPixel strip. 

Once the setup is complete, the program enters a loop where it checks the keys, processes MIDI events, and checks the volumes.

- In the "Check Keys" step, it sets the Mux channel and processes the key, which involves sending MIDI events.
- In the "Check MIDI" step, it receives MIDI events and updates the NeoPixel strip accordingly.
- In the "Check Volumes" step, it processes the volume, which involves sending control change MIDI events.

This loop continues indefinitely until the Arduino is reset or powered off.

<img src="https://showme.redstarplugin.com/s/aVHtosFr" title="" alt="Flowchart" data-align="center">

<img src="https://camo.githubusercontent.com/f766efce8df1e2ce779d57495b6adde32e0d9a697af800540595152ac2fac172/68747470733a2f2f73686f776d652e72656473746172706c7567696e2e636f6d2f732f615648746f734672">
