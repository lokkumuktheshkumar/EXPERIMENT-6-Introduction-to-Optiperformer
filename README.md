
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---

## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Instructions

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**

| S.No | Fiber Length (km) | Optical Power (Watts) | Optical Power (dBm) | Max Q Factor | Min BER | Eye Height | Decision Instant (Max Q / Min BER) |
|------|-------------------|------------------------|----------------------|--------------|---------|-------------|-------------------------------------|
| 1    |      89           |      8.039E-6          |      -20.948         |   50.4972    |    0    | 1.5678e-05  | 0.546875                            |  
| 2    |      98           |      5.226E-6          |      -22.818         |   39.2867    |    0    | 1.02106e-07 | 0.546875                            |
| 3    |      107          |      3.396E-6          |      -24.690         |   40.1904    |    0    | 6.72572e-07 | 0.546875                            |
| 4    |      121          |      1.871E-6          |      -27.279         |   28.2175    |1.11e-290| 3.4076e-06  | 0.484375                            |
| 5    |      140          |      780.089E-9        |      -31.079         |   21.3238    |6.241e-87| 1.37258e-07 | 0.609375                            |
<img width="1600" height="1200" alt="WhatsApp Image 2026-04-18 at 2 22 02 PM" src="https://github.com/user-attachments/assets/93eefba4-33fd-4f17-9f9a-cfff396da993" />

---

## Graphs

<img width="1915" height="1193" alt="Screenshot 2026-04-18 135523" src="https://github.com/user-attachments/assets/4b32ee1e-2832-4b88-97fd-f683fd10ab0f" />

---

## RESULT

*(Summarize key findings from simulation and analysis)*
