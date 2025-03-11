# Presettable-Digital-Clock

## Overview  
This project implements a digital clock using a combination of synchronous and asynchronous Flip-Flop counters. The clock can be preset by applying the binary representation of numbers to each digit stage.  

## Features  
- *Preset Function:* Allows users to set the clock by applying binary values to each digit.  
- *Stop Mechanism:*  
  - Press the *SET* switch to enter preset mode.  
  - Press the *RESET* switch to start the clock from the preset value.  
- *Pause Function:* Press the *PAUSE* switch to temporarily stop the clock.  

## Components Used  
- Flip-Flop Counters (Synchronous & Asynchronous)  
- Binary Input Preset Logic  
- Control Switches:  
  - *SET* – Enter preset mode  
  - *RESET* – Start/reset the clock  
  - *PAUSE* – Pause the clock  

## How It Works  
1. *Setting the Time:*  
   - Apply the binary representation of the desired time to each digit stage.  
   - Press *SET* to load the preset value into the counters.  

2. *Starting the Clock:*  
   - Press *RESET* to start counting from the preset value.  

3. *Pausing the Clock:*  
   - Press *PAUSE* to halt counting.  
   - Press *RESET* to resume from the last value.  

## Usage Instructions  
1. Set the desired time using the binary input.  
2. Press *SET* to load the value.  
3. Press *RESET* to start the clock.  
4. Press *PAUSE* to stop temporarily.  
5. Press *RESET* again to resume.  

## Future Improvements  
- Add a display module for real-time visualization.  
- Implement an alarm system.  
- Introduce a more user-friendly interface for setting the time.  

## License  
This project is open-source and free to use for educational and personal purposes.  

---

### Author: [Mostafa Mohamed]
