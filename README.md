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
## Installation

# Clone the repository:

git clone https://github.com/Anjal10911/Deepfake-Detection-CID.git
cd Deepfake-Detection-CID


# Install dependencies:

pip install -r requirements.txt

# Usage
# Image Detection
python backend/scripts/detect_image.py --input path_to_image.jpg

# Video Detection
python backend/scripts/detect_video.py --input path_to_video.mp4


Outputs frame-level timestamps of suspicious segments.

Generates Grad-CAM visualizations for explanation.

# Audio Detection
python backend/scripts/detect_audio.py --input path_to_audio.wav

Detects manipulated audio segments.

Can perform comparisons between two audio files.
## Example Output

Video: Suspicious frames highlighted with Grad-CAM heatmaps and timestamps.

Audio: Segments flagged with manipulation scores, comparison results, and timestamps.

Images: Heatmaps highlighting manipulated regions.
## Contributing

Contributions are welcome! Please submit a pull request or open an issue for suggestions, bug fixes, or improvements.

## License

This project is for research and investigative purposes. Please cite accordingly when used in academic or forensic work.
