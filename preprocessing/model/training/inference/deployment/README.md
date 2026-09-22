# Edge Deployment

This folder contains the files and documentation required to deploy the Cardio-Edge system on the Raspberry Pi 3.

## Deployment Architecture

```text
ECG Input
     ↓
AD8232 ECG Front-End
     ↓
MCP3008 ADC
     ↓
Raspberry Pi 3
     ↓
Signal Processing
     ↓
TFLite AI Model
     ↓
ECG Classification
     ↓
SIM800L GSM Module
     ↓
SMS Alert
