<h1 align="center">🎙️ Beamforming-Based Far-Field Speech Recognition for Regional Language</h1>

<p align="center">
AI-powered far-field speech recognition system using beamforming techniques and Whisper ASR for Kannada language speech enhancement and transcription.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Speech%20Processing-blue?style=for-the-badge">
  <br> </br>
  <img src="https://img.shields.io/badge/Technique-Beamforming-green?style=for-the-badge">
  <br> </br>
  <img src="https://img.shields.io/badge/Language-Regional-orange?style=for-the-badge">
  <br> </br>
  <img src="https://img.shields.io/badge/ASR-OpenAI%20Whisper-red?style=for-the-badge">
  <br> </br>
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
</p>

---

# 📌 Project Overview

This project focuses on improving far-field speech recognition performance for regional-language speech using beamforming-based speech enhancement techniques.

The system combines:
- Multi-microphone signal processing
- Delay-and-Sum beamforming
- Signal preprocessing and filtering
- Whisper-based Automatic Speech Recognition (ASR)

to improve speech intelligibility and transcription quality in noisy and reverberant far-field environments.

The project primarily targets Kannada language speech recognition under practical distant-speech conditions.

---

# 🎯 Project Objectives

- Study challenges in far-field speech recognition systems
- Understand microphone array processing and beamforming techniques
- Implement beamforming for speech enhancement
- Reduce background noise and reverberation effects
- Improve Kannada speech recognition performance
- Compare ASR performance before and after enhancement
- Develop a scalable regional-language far-field ASR framework

---

# ✨ Phase-1 Implementations

- Far-field speech simulation
- Multi-microphone array simulation
- Delay-and-Sum beamforming
- Bandpass filtering
- Signal normalization
- Noise addition using AWGN
- Whisper ASR integration
- Kannada speech transcription
- Comparative speech enhancement analysis

---

# 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Speech Processing | Librosa, SciPy |
| Numerical Computing | NumPy |
| Visualization | Matplotlib |
| ASR Model | OpenAI Whisper |
| Development Environment | Google Colab / Jupyter Notebook |
| Signal Processing | Beamforming, Filtering |

---

# ⚙️ Methodology

The implemented prototype currently follows the below processing pipeline:

```text
Speech Input
    ↓
Far-Field Noise Simulation
    ↓
Multi-Microphone Array Simulation
    ↓
Delay-and-Sum Beamforming
    ↓
Bandpass Filtering
    ↓
Signal Normalization
    ↓
Whisper ASR Processing
    ↓
Kannada Text Output
    ↓
Performance Evaluation
```

---

# 🧠 System Workflow

## Step 1 — Speech Acquisition
Kannada speech samples are collected using prerecorded audio recordings.

## Step 2 — Far-Field Simulation
Background noise is artificially added to simulate practical far-field environments.

## Step 3 — Microphone Array Simulation
Multiple microphone channels are generated for spatial signal processing.

## Step 4 — Beamforming
Delay-and-Sum beamforming is applied to enhance desired speech signals.

## Step 5 — Signal Enhancement
Bandpass filtering and normalization improve speech quality.

## Step 6 — Speech Recognition
The processed audio is transcribed using the OpenAI Whisper ASR model.

## Step 7 — Comparative Evaluation
Recognition performance before and after enhancement is analyzed.

---

# 📂 Repository Structure

```bash
far-field-speech-recognition-beamforming/
│
├── README.md
├── docs/
│   ├── phase-1-report.pdf
│   └── phase-1-presentation.pptx
│
├── notebook/
│   └── beamforming.ipynb
│
├── images/
│   ├── system-architecture/
│   ├── waveforms/
│   └── results/
│
├── results/
│   ├── noisy-audio/
│   ├── enhanced-audio/
│   └── transcripts/
│
└── references/
```

---

# 📊 Phase-1 Experimental Highlights

The implemented prototype demonstrated:

- Improved speech clarity
- Reduced environmental noise
- Better recognition stability
- Improved Kannada transcription quality
- Enhanced speech intelligibility in noisy environments

Comparative analysis showed that beamforming-based preprocessing improved the overall quality of far-field speech signals before ASR processing.

---

# 📈 Phase-1 Results & Analysis

| Parameter | Before Enhancement | After Enhancement |
|-----------|-------------------|------------------|
| Speech Quality | Noisy & Distorted | Improved & Clear |
| Background Noise | High | Reduced |
| Recognition Stability | Unstable | More Stable |
| Kannada Text Quality | Partially Distorted | More Coherent |
| Speech Intelligibility | Moderate | Improved |

---

# 📚 Documentation

| File | Description |
|------|-------------|
| Phase-1 Report | Detailed synopsis and implementation documentation |
| Phase-1 Presentation | CIE presentation slides |
| Beamforming Notebook | Prototype implementation and experiments |

---

# 🔬 Research Focus

This project primarily explores:
- Far-field speech enhancement
- Beamforming techniques
- Regional-language ASR
- Microphone array signal processing
- Speech preprocessing pipelines
- Noise reduction for speech recognition

---

# 🚀 Planned Future Work

- MVDR beamforming implementation
- Real microphone array integration
- Real-time speech processing
- Advanced neural beamforming
- Multi-language ASR support
- Embedded deployment optimization

---

# 👨‍💻 Team Members

- Nandan Kuchabal
- Sagar A S
- Relangi Mahesh Satya Venkat Gowd

---

# 🎓 Academic Information

- Department of Electronics and Communication Engineering
- Nitte Meenakshi Institute of Technology
- Visvesvaraya Technological University (VTU)
- Major Project
- Academic Year: 2026–2027

---

# 📖 References

Key references and research papers are included in the project report and references section.

---

# 📌 Current Development Status

| Phase | Status |
|------|--------|
| Phase-1 | ✅ Completed |
| Phase-2 | 🔄 Planned |
| Phase-3 | ⏳ Upcoming |

Current Repository Stage:

```text
Phase-1 Documentation & Prototype Implementation
```

---

# 📝 Note

This repository currently contains the implementation and documentation developed during Major Project Phase-1. Future enhancements, advanced beamforming methods, and real-time speech processing modules will be progressively integrated in subsequent phases of the project.
