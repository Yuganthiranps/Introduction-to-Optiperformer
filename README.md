# Introduction-to-Optiperformer


## Aim
Download and install OptiPerformer software on your computer and run a sample file.

## Software required
Optiwave introduces OptiPerformer, a free photonic design automation tool which harnesses the full power of OptiSystem and creates specific dynamic design scenarios which can be used by students.

The system is *instrumented* with:
- An optical power meter at the input to the receiver (or the output of the fiber)  
- A bit error rate (BER) analyzer


## Procedure

1. Download and install OptiPerformer from the [optiwave.com](https://optiwave.com) website.
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.
3. Start OptiPerformer.
4. Use either the **File menu** or the **Open File** button to open the Fiber Optic System File.
5. Study the layout, which includes text and boxes identifying the three components of the fiber optic system:
   - **Transmitter section**: binary source (PRBS generator), electrical pulse generator, laser diode, external modulator  
   - **Receiver section**: photodiode, low-pass filter, decision circuit (with BER analyzer)  
   *(These components will be covered in more detail later in the course.)*
6. Run the simulation by pressing the **Start** button.  
   - Progress will be displayed.  
   - The message *“Calculation Finished!”* will appear when complete.
7. Double-click on the optical power meter and BER analyzer.  
   - Move the windows as necessary for clarity.  
   - In the BER window, check the box **Show Eye Diagram**.  
   - The optical power meter shows power at the photodiode input in both watts and dBm.  
   - The BER window displays the eye diagram and quantities including **Max Q Factor** and **Min BER**.
8. The simulation runs **5 iterations**, with fiber length varying from 50 km to 150 km in 5 steps.  
   - The index is displayed in the upper right corner of the layout.  
   - Use the forward/reverse buttons in the lower left to step through iterations.  
   - Note changes in received power and BER display (eye diagram, Q factor, BER) with fiber length.

## Tabulation:
![IMG_8862](https://github.com/user-attachments/assets/c4b76639-5fe8-4b61-87e3-334389b54e56)

## Graph:

<img width="1131" height="624" alt="image" src="https://github.com/user-attachments/assets/a84ffc64-3f9c-4e7f-968d-99a706582d36" />


## Description:

the eye diagram and corresponding Q-factor variation for an optical communication link operating at 2.5 Gb/s with a 193.1 THz laser.
The eye diagram (left) illustrates signal integrity over multiple iterations, where the eye opening indicates timing margin and noise tolerance.
Clear eye opening at the sampling instant suggests relatively low intersymbol interference and acceptable system performance.
The Q-factor plot (right) shows how signal quality varies across the bit period, peaking near the optimal decision point.
Higher Q values at mid-bit confirm improved signal-to-noise ratio and reliable data detection.

## Result:

The above experiment is executed and output is verified.





