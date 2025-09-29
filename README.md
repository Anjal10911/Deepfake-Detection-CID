### Deepfake Detection CID

## Overview

This project is a multi-modal Deepfake Detection system designed for investigative and research purposes. It can detect manipulations in images, videos, and audio using advanced detection models, Grad-CAM visualizations, and detailed analysis outputs.

The system was developed as part of a Crime Investigation Department (CID) project and focuses on robust forensic detection.

## Features

Image Deepfake Detection: Detect manipulated faces or objects in images.

Video Deepfake Detection: Detect video-level manipulations and provide frame-level timestamps of suspected frames.

Audio Deepfake Detection: Detect manipulated audio snippets and perform comparisons between audio files.

Grad-CAM Visualizations: Highlight areas of the image or video frame that influenced the model's prediction.

Detailed Reports: Outputs timestamps for suspicious video and audio segments, enabling precise forensic analysis.

Multi-modal Support: Combines image, video, and audio analysis for comprehensive detection.

## Folder Structure
deepfake-detection-ccitr-main/
├── backend/
│   ├── checkpoints/      # Pretrained models (ignored in Git)
│   ├── scripts/          # Detection scripts for image, video, audio
│   └── utils/            # Helper functions for Grad-CAM, comparisons
├── frontend/             # Optional UI or visualization code
├── README.md
└── requirements.txt      # Python dependencies

⚠ Note: Checkpoints are large and are excluded from the repository (.gitignore).
