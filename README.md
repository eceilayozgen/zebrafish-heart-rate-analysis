# HR ImageJ Macro

This repository contains the HR macro for ImageJ, designed to quantify heart rate and rhythm from zebrafish cardiac videos. The macro detects diastolic frames via intensity changes, calculates beat intervals and average heart rate, computes HR variability metrics, and flags potential arrhythmias.

## Features

- Automatic diastole detection based on ventricular intensity changes
- Beat-to-beat interval and average heart rate calculation
- Heart rate variability metrics (SDNN, RMSSD, HR SD)
- Optional intensity plot for visual verification
- Adjustable parameters for different zebrafish lines and imaging conditions

## Requirements

- ImageJ
- Videos in `.avi` format

## Protocol

Full usage protocol and parameter guidelines are provided in the following document: [**FACDiam_Macro_Protocol.pdf**](https://github.com/eceilayozgen/zebrafish-heart-rate-analysis/blob/main/HR_Macro_Protocol.pdf)

## License

This project is licensed under the MIT License.

