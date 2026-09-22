# ECG Inference

The inference module performs local ECG analysis on the Raspberry Pi 3 using a lightweight TensorFlow Lite (TFLite) AI model.

## Inference Workflow

```text
ECG Electrodes
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
Normal / Abnormal
      ↓
SIM800L
      ↓
SMS Alert to Caregiver
