# \# AI Image Emotion Detector

# 

# Real-time facial emotion recognition system using OpenCV face detection + deep learning emotion classification (Baseline CNN / ResNet18 Transfer Learning).

# 

# \## Team

# \- Won Kim

# \- Tripp Ix

# \- Brian Lee

# \- Shun Funeno

# 

# ---

# 

# \## Overview

# This project builds an AI image-based emotion detector that:

# 1\) detects a face from an image/webcam frame  

# 2\) preprocesses the face region  

# 3\) predicts one of 7 emotion classes in real time

# 

# The pipeline combines traditional face detection (OpenCV Haar Cascade) with modern CNN-based classifiers (a baseline CNN trained from scratch and ResNet18 transfer learning). :contentReference\[oaicite:1]{index=1}

# 

# ---

# 

# \## Features

# \- Real-time webcam emotion prediction (OpenCV)

# \- Face detection: Haar Cascade

# \- Emotion classifiers:

# &nbsp; - Baseline CNN (trained from scratch)

# &nbsp; - ResNet18 transfer learning (fine-tuned / last layer replaced for 7 emotions)

# \- Preprocessing: crop face → resize to \*\*48×48\*\* → grayscale → normalize :contentReference\[oaicite:2]{index=2}

# 

# ---

# 

# \## Emotion Classes

# \- angry

# \- disgust

# \- fear

# \- happy

# \- neutral

# \- sad

# \- surprise

# 

# (Exact label names depend on the dataset label mapping used in training.)

# 

# ---

# 

# \## Tech Stack

# \- Python 3.x

# \- PyTorch

# \- OpenCV

# \- NumPy

# 

# ---

