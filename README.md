# Cardio-Edge – AI-Based ECG Arrhythmia Detection

## SIH Problem Statement

Cardio-Edge is an edge-AI based ECG monitoring and arrhythmia detection system designed for reliable cardiac screening, especially in remote and resource-constrained areas.

The system processes ECG signals locally using a lightweight AI model and provides an interpretable result without depending entirely on cloud connectivity.

---

## Key Features

- Single-lead ECG signal acquisition
- ECG signal preprocessing
- Noise reduction and signal conditioning
- AI-based arrhythmia classification
- Lightweight edge deployment
- Local processing using Raspberry Pi
- Designed for remote and low-connectivity environments
- Source-grounded and reproducible AI pipeline

---

## System Workflow

```text
ECG Sensor
     ↓
Signal Acquisition
     ↓
Preprocessing
     ↓
Feature / Signal Representation
     ↓
AI Model
     ↓
Arrhythmia Classification
     ↓
Result / Alert
