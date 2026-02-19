# Sampling of Data using MATLAB and Arduino

## Project Overview

This project was developed as part of the Messtechnik curriculum. The goal was to capture real-world physical data (light intensity) and analyze its frequency components using digital signal processing. The system utilizes a Light Dependent Resistor (LDR) in a voltage divider circuit to translate light levels into measurable analog voltages.

### Core Concepts Utilized

<ul><li>Sampling: Converting continuous analog light data into discrete digital values using the Arduino ADC via the MATLAB Command Server.</li>
    <li>DC Removal (Mean Subtraction): Eliminating the average voltage offset to center the signal at zero, which is essential for a clean frequency analysis.</li>
    <li>Fast Fourier Transform(FFT): Transitioning the signal from the Time Domain to the Frequency Domain to identify periodic patterns or noise.</li>
</ul>

### Hardware & Tools Used

<ul><li>Software: MATLAB with the MATLAB Support Package for Arduino Hardware</li>
    <li>Microcontroller: Arduino Uno</li>
    <li>Sensor: Light Dependent Resistor (LDR)</li>
    <li>Circuitry: Voltage divider (LDR + Fixed Resistor) and breadboard connections</li>
    <li>Visual Feedback: Onboard LED (Pin D5) used as a status indicator during measurement</li>
</ul>
