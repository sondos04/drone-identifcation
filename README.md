# Drone Radar Identification

Radar-based drone model identification using
STFT Micro-Doppler Spectrograms and Deep Residual Networks.

Dataset: St Andrews Radar Dataset

Models:
- ResNet-18
- ResNet-50
- Custom ResNet

Pipeline:
Raw FMCW Radar -> Range Processing -> Micro-Doppler STFT
-> Spectrogram -> Drone Model Classification
