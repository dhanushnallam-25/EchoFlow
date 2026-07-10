# 🎙️ EchoFlow v0.1

### Static Hankel-SVD Audio Denoising

---

## Overview

Version 0.1 establishes the mathematical and implementation foundation of the EchoFlow project.

This version implements offline audio denoising using Singular Value Decomposition (SVD) applied to a Hankel matrix representation of the input audio signal.

The primary goal is to understand how low-rank approximation can separate useful signal components from noise.

---

## Objectives

- Learn Singular Value Decomposition
- Learn Hankel Matrix construction
- Implement Low-Rank Approximation
- Reconstruct denoised audio
- Understand frequency-domain visualization

---

## Features

✅ Audio preprocessing

✅ Hankel Matrix construction

✅ Economy-size SVD

✅ Fixed Rank Reconstruction

✅ Anti-diagonal Averaging

✅ FFT Visualization

✅ Waveform Visualization

✅ Audio Export

---

# Workflow

```
Input Audio
      │
      ▼
Preprocessing
      │
      ▼
Hankel Matrix
      │
      ▼
Singular Value Decomposition
      │
      ▼
Select Top-k Singular Values
      │
      ▼
Low-Rank Reconstruction
      │
      ▼
Anti-diagonal Averaging
      │
      ▼
Recovered Audio
```

---

# Concepts Learned

- Singular Value Decomposition
- Hankel Matrix
- Matrix Decomposition
- Low-Rank Approximation
- Audio Signal Processing
- FFT
- Signal Reconstruction

---

# Current Limitations

This version intentionally focuses on a static implementation.

Current limitations include:

- Offline processing
- Full SVD recomputation
- Manual rank selection
- No adaptive learning
- No streaming support
- No real-time processing

---

# Future Improvements

Version 0.2

- Automatic Rank Selection

Version 0.3

- Adaptive Truncated SVD

Version 0.4

- Sliding Window Hankel Matrix

Version 0.5

- Incremental SVD

Version 0.6

- Real-Time Audio Processing

---

# Repository Structure

```
v0.1-static-hankel-svd/

README.md

matlab/

figures/

sample_audio/

output/

paper/
```

---

# Results

Current implementation successfully

- reads WAV audio
- performs SVD decomposition
- reconstructs low-rank audio
- visualizes waveform
- visualizes singular values
- visualizes FFT
- exports denoised audio

---

# Version Information

Version: v0.1

Status: Stable

Type: Research Prototype

---

## Author

Dhanush Nallam

Amrita Vishwa Vidyapeetham