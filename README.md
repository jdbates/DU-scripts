# This repository contains a list of useful scripts and configuration files for Dual Universe

# Stochasty's Baseline Autoconfiguration

This autoconfiguration includes Rezoix DU-hud script as well as a simple attitude control script.

To install, copy the file stoch_baseline.conf to the \Dual Universe\Game\data\lua\autoconf\custom directory, then right click your construct and select Advanced->Update Custom Conf List and Advanced->Run Custom AutoConfiguration->Stochasty Baseling Autoconfiguration

The attitude control script does the following:
- On system.start(), and whenever you extend or retract gear, it will automatically level your construct.
- Pressing the 'Option 2' command will also auto-level your construct while in flight.
- 'Option 1' toggles the attitude controller on and off. (Note that, as of yet, there is no visual indicator in the HUD for whether attitude control is on or off.  This is coming soon.)
- When attitude control is running, it will attempt to maintain constant pitch and roll unless the pilot is giving manual control input.  This means that you do not have to continually pitch down when travelling long distances in atmosphere, and will also help you maintain a constant angle of ascent when climbing to orbit. (Note that, due to curvature of the planet, constant angle of ascent is not the same as a constant heading.  If you want to maintain a constant heading, toggle the controller off.)
