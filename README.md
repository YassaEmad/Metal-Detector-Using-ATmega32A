# Metal Detector Using ATmega32A

## Project Overview

This project presents a microcontroller-based metal detection system using the ATmega32A. The detector operates by generating a PWM signal that excites a transmitting coil. The resulting electromagnetic field interacts with nearby metallic objects, causing changes in the received signal.

The system measures the phase shift between the transmitted and received signals to determine the presence of metal objects.

## Working Principle

1. The ATmega32A generates a PWM signal.
2. The PWM signal drives the transmitter coil.
3. The coil produces an alternating electromagnetic field.
4. The received signal is amplified using operational amplifiers.
5. A phase detector compares the transmitted and received signals.
6. The phase difference is extracted and filtered using a smoothing circuit.
7. The filtered signal is sampled by the ATmega32A ADC.
8. The microcontroller processes the ADC readings to detect metallic objects.

## System Block Diagram

ATmega32A PWM → Transmitter Coil → Electromagnetic Field

Received Signal → Operational Amplifier → Phase Detector → Smoothing Filter → ADC → ATmega32A Processing

## Project Features

* PWM signal generation using ATmega32A
* Electromagnetic metal detection
* Signal amplification using operational amplifiers
* Phase shift measurement technique
* Analog signal conditioning and filtering
* ADC-based digital processing
* Real-time metal detection

## Repository Structure

### Documentation

Contains the project report, calculations, and experimental results.

### Simulation

Contains circuit simulation files and simulation videos.

### Videos

Contains hardware demonstrations and project testing videos.

## Hardware Components

* ATmega32A Microcontroller
* Transmitter Coil
* Receiver Coil
* Operational Amplifiers
* Phase Detector Circuit
* Low-Pass Filter
* Power Supply Circuit

## Software Tools

* Proteus
* Embedded C
* AVR Programming Tools

## Applications

* Metal Detection Systems
* Security Screening
* Industrial Inspection
* Educational Embedded Systems Projects


## Simulation

Simulation files are available in the Simulation folder.

### Simulation Video

Due to GitHub file size limitations, the simulation video is hosted on Google Drive:

[Watch Simulation Video](https://drive.google.com/file/d/1fpL_WPFA5AlaDryKr1ElvNHYuxU1z_RB/view?usp=drive_link)

## Team Members
Mina Naim
Yassa Emad
