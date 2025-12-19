# PD Signal Denoising Using Discrete Wavelet Transform (DWT)

## Overview
This repository presents a complete workflow for denoising a measured
partial discharge (PD) detection signal using the Discrete Wavelet Transform (DWT).

The objective is to suppress background noise while preserving impulsive PD characteristics.

## Data
- Measured time-domain PD signal (CSV format)
- Signal visualization provided for reference

## Methodology
1. Load measured PD signal
2. Apply multi-level DWT decomposition (db4 wavelet)
3. Perform soft-thresholding on detail coefficients
4. Reconstruct denoised signal
5. Compare raw and denoised signals

## Results
The DWT-based method effectively reduces noise while maintaining PD pulse integrity.

![Raw vs Denoised](results/raw_vs_denoised.png)

## Requirements
Install required packages using:

