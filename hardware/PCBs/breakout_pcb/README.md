# Breakout PCB

The **Breakout PCB** facilitates the use of GAPses without the BioGAP acquisition platform. It provides access to all the signals on the electrode interface PCB, allowing other commercial or research biopotential acquisition platforms to be used in conjunction with GAPses.

## Features
- Enables the use of GAPses with non-BioGAP acquisition platforms
- Provides direct access to all electrode interface signals
- Supports EEG/EOG signal measurements
- Includes a DC offset of 2.048 V for proper operation of embedded electronics

## How to Connect the Breakout PCB

Follow these steps to connect the breakout PCB to your measurement system:

### 1. Powering the Breakout PCB
To power the breakout PCB, follow these steps:
   - Connect **GND** and **AVDD** to a lab power supply.
   - Set the power supply voltage to **3.0V (AVDD)**.

### 2. Measuring EEG/EOG Signals
Once powered, you can measure EEG and EOG signals by following these guidelines:
   - The signals are measured with respect to the **REF** pin (e.g., TL1 - REF, TL2 - REF, EOG L - REF, etc.).
   - The signals will have a **DC offset of 2.048 V**, which can be measured on the **BIAS** pin. This offset is necessary for the proper operation of the embedded electronics in the glasses frame and is generated by the breakout PCB.

### 3. Connecting to Measurement Device
   - Connect the channels you wish to measure to your measurement device. Ensure that the signals are correctly referenced with respect to the **REF** pin.