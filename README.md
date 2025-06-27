# Baja SAE Accelerometer System

![Baja SAE Vehicle](Images/baja%20sae%20car.png)

## Overview

This project implements a custom accelerometer data acquisition system for a Baja SAE vehicle. The goal is to accurately measure and analyze the vehicle's acceleration along the x, y, and z axes, supporting improved understanding and optimization of vehicle dynamics.

## What Does It Do?

- **Custom PCB Design:** Developed using Altium, the PCB integrates an STM32 microcontroller, an accelerometer sensor, SD card slot, and an LCD display.
- **Real-Time Sensing:** Continuously measures the Baja SAE vehicle's acceleration to aid in evaluating and improving vehicle performance.
- **Data Logging & Display:** Acceleration data is displayed on an LCD and exported as CSV files for detailed analysis.

![PCB, STM32, Accelerometer, and LCD Display Breadboard Setup](Images/Acceleration%20Sensor.jpg)

## How Does It Work?

- **Firmware:** The STM32 microcontroller is programmed in C to read accelerometer data, process it, and handle data storage and display.
- **Collaboration:** Developed in close partnership with the Baja SAE team to ensure robust operation and accurate, reliable measurements in real-world racing environments.
- **Output:** Data is exported as CSV files for easy analysis in tools like Excel or MATLAB.

## Results

- **Precision:** Achieved ±5% accuracy in x, y, and z axis acceleration readings.
- **Impact:** Enabled real-time evaluation of vehicle dynamics, contributing to improved performance and safety for the Baja SAE team.
- **Sample Data Output:**
  
  ![Sample Accelerometer Data (CSV)](Images/accel%20output.png)

  ```
  x, y, z
  -0.6532, 0.0215, 8.8478
  -0.6292, 0.0766, 8.8454
  -0.6484, 0.0909, 8.8813
  ...
  ```

## Features

- **STM32-based data acquisition**
- **Custom Altium-designed PCB**
- **LCD for live acceleration readout**
- **SD card data logging in CSV format**
- **±5% measurement precision**

## Baja SAE Context

This system played a key role in the Baja SAE vehicle's development and testing, providing actionable insights into suspension behavior, vehicle control, and overall performance.

---

*For more details, see the code and hardware files in this repository.*