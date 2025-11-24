
## Exp 6 Simulation of Optical Communication System
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
## Theory
Optiwave introduces OptiPerformer, a free photonic design automation tool which harnesses the full power of OptiSystem and creates specific dynamic design scenarios which can be used by students.
In this exercise, you will download and install OptiPerformer on your PC/laptop. Your license of OptiPerformer will be capable of loading and running OptiSystem simulations prepared for this course.
Once you have installed OptiPerformer, you can copy the first file (named: ‘Introduction_OptiPerformer.osp’) to your PC and run the simulation. The first file is a basic fiber optic system consisting of a transmitter, a fiber and a receiver. The system is “instrumented” with an optical power meter at the input to receiver (or the output of the fiber) and a bit error rate (BER) analyzer.


## Instructions

1.	Download and install OptiPerformer from the optiwave.com web site.
2.	Copy the ‘Introduction_OptiPerformer.osp’ file to your PC
3.	Start OptiPerformer
4.	Use either the File menu or the Open File button to open the Fiber Optic System File.
5.	Study the layout, which includes some text and boxes to identify the three components of the fiber optic system. The “transmitter” section includes a binary source (PRBS or pseudo-random bit sequence generator), an electrical pulse generator, a laser diode and an external modulator. The receiver section includes a photodiode, a low-pass filter and a decision circuit, which includes a BER analyzer. We will cover these components in more detail later in the course.
6.	Run the simulation by pushing the start button. The progress of the simulation will be displayed
and the message “Calculation Finished!” will appear when the simulation runs to completion.
7.	Double click on the optical power meter and the BER analyzer and move the windows as necessary for clarity. Check the box next to “Show Eye Diagram” in the BER window. The optical power meter shows the power at the input to the photodiode in both watts and dBm. The BER window displays the “eye diagram” and several quantities including the “Max Q
Factor” and the “Min BER”.
8.	The simulation is set to run 5 “iterations”, with the fiber length varying from 50 to 150 km in 5 steps. The index is displayed in the upper right corner of the layout. To step through the iterations, use the forward and reverse buttons in the lower left of the window. Note the change in received power and BER display (eye diagram, Q factor and BER) with fiber length.


---

## Report

<img width="1280" height="680" alt="image" src="https://github.com/user-attachments/assets/1cc60fcd-38ee-4195-ad09-46390f75c673" />

## Tabulation

**Transmission Analysis Across Fiber Lengths**

<img width="1280" height="949" alt="image" src="https://github.com/user-attachments/assets/501a457a-f648-4eb0-bf39-fb0e9554d525" />



---

## RESULT
Thus the simulation of optical communication system is successfully verified with BER analyzer.

