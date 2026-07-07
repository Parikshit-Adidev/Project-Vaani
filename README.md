# Vaani

**Vaani** is a low-cost **Edge AI-powered neurological screening system** that analyzes speech to detect early vocal biomarkers associated with disorders such as **Amyotrophic Lateral Sclerosis (ALS)** and **Parkinson's disease**. By combining embedded machine learning, digital signal processing, and robotics, Vaani performs real-time voice analysis entirely on-device, making neurological screening more accessible, affordable, and privacy-preserving.

---

## Overview

Neurological disorders often produce subtle changes in speech long before severe physical symptoms appear. Traditional diagnostic methods require specialist consultations, expensive equipment, and multiple clinical assessments, making early detection difficult in many regions.

Vaani addresses this challenge by providing an offline, portable screening solution that uses artificial intelligence to analyze voice recordings and identify potential neurological abnormalities in seconds.

The entire inference pipeline runs locally on embedded hardware without requiring cloud processing, ensuring low latency, reduced power consumption, and complete user privacy.

---

## Features

- Real-time speech analysis
- Offline Edge AI inference
- TinyML deployment on ESP32
- MFCC-based feature extraction
- Privacy-first local processing
- Low-cost and portable hardware
- Fast neurological risk prediction
- Designed for early screening applications
- No internet connection required

---

## How It Works

1. The user records a short speech sample.
2. Audio is captured through the onboard digital microphone.
3. MFCC features are extracted from the recording.
4. The optimized TinyML model analyzes the extracted features.
5. The device predicts whether the voice resembles healthy or neurological speech patterns.
6. Results are displayed in real time.

---

## Hardware

- ESP32
- INMP441 Digital MEMS Microphone
- OLED Display (optional)
- Rechargeable battery
- Embedded Edge AI firmware

---

## Artificial Intelligence Pipeline

The machine learning model was trained using more than **1,100 publicly available clinical voice recordings** collected from:

- Synapse VOC-ALS Dataset
- KaggleHub Parkinson's Voice Dataset

The training pipeline includes:

- Audio preprocessing
- Noise reduction
- MFCC feature extraction
- Dataset balancing
- Model optimization for TinyML deployment
- Edge Impulse model training
- Embedded inference optimization

The final model is optimized for low-memory embedded devices while maintaining real-time performance.

---

## Technology Stack

### Embedded Systems

- ESP32
- Arduino IDE
- C++

### Artificial Intelligence

- Python
- Edge Impulse
- TensorFlow Lite for Microcontrollers
- TinyML

### Audio Processing

- MFCC Feature Extraction
- Digital Signal Processing (DSP)

---

## Applications

- Early neurological screening
- Rural healthcare
- Community health programs
- Medical awareness campaigns
- Educational research
- AI-assisted diagnostics
- Remote health monitoring

---

## Project Goals

- Make neurological screening affordable
- Enable AI diagnostics without cloud infrastructure
- Increase accessibility in underserved communities
- Protect user privacy through local inference
- Demonstrate the potential of TinyML in healthcare

---

## Future Development

- Support additional neurological disorders
- Improve model accuracy with larger datasets
- Multi-language speech analysis
- Mobile application integration
- Cloud dashboard for clinicians (optional)
- Explainable AI predictions
- Clinical validation studies

---

## Repository Structure

```
Vaani/
│
├── datasets/
├── model/
├── firmware/
├── hardware/
├── docs/
├── images/
├── app/
├── README.md
└── LICENSE
```

---

## License

This project is released under the MIT License.

---

## Author

**Parikshitsinh Jadeja**
