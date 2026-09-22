# Cardio-Edge – AI-Based ECG Arrhythmia Detection

## SIH Problem Statement

Cardio-Edge is a low-cost, portable Edge-AI-based ECG monitoring and cardiac abnormality detection system designed for remote and resource-constrained environments.

The system processes ECG signals locally on a Raspberry Pi 3 using a lightweight AI model and provides real-time abnormality/arrhythmia screening, with critical alerts transmitted through a cellular network.

---

## Key Features

- Single-lead ECG signal acquisition
- ECG signal conditioning and preprocessing
- ECG signal digitization using MCP3008 ADC
- Signal filtering and noise reduction
- AI-based ECG abnormality/arrhythmia classification
- Lightweight Edge-AI inference using TensorFlow Lite
- Local processing using Raspberry Pi 3
- SMS alerts through cellular connectivity
- Designed for remote and low-connectivity environments

---

## System Workflow

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
Critical Alert via SMS
