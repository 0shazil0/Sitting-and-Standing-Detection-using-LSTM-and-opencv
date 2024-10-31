# Sitting and Standing Detection using LSTM and OpenCV

Detecting human postures (sitting and standing) in video streams using a Long Short-Term Memory (LSTM) model combined with OpenCV for real-time video processing. This project aims to identify sitting and standing positions accurately to support applications like ergonomic analysis, security monitoring, or fitness tracking.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Project Overview

This project detects sitting and standing poses using a combination of computer vision and deep learning. OpenCV is used to process video frames and extract key features, and an LSTM model classifies the extracted features into "sitting" or "standing" classes. 

The model is trained to recognize the subtle differences in posture using sequential data, allowing it to maintain a robust understanding of the person’s position across time.

## Features

- **Real-Time Detection:** Analyzes live video feeds to detect sitting and standing postures in real-time.
- **Efficient Tracking:** Tracks the person throughout the video to ensure continuous and accurate posture detection.
- **Customizable:** Easily adaptable to detect additional postures by training on new labeled sequences.

## Technologies Used

- **OpenCV:** For real-time video processing and feature extraction.
- **LSTM (Long Short-Term Memory):** A neural network model from TensorFlow/Keras for time-series analysis, capturing temporal dependencies in posture sequences.
- **Python:** Primary language for processing and model development.

## Setup and Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/0shazil0/Sitting-Standing-Detection.git
   cd Sitting-Standing-Detection
   ```

2. **Install Requirements:**
   This project uses Python 3.7+. Install the dependencies by running:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download Pre-Trained Model (Optional):**  
   If available, download the pre-trained LSTM model from above and save it to the folder.
```

## Acknowledgments

Thanks to the open-source contributors of OpenCV and TensorFlow/Keras, and to everyone who helped in gathering datasets and testing the model.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This README will help others understand, set up, and use your project easily. Make sure to replace placeholder links with actual links to resources such as demo videos, pre-trained models, or any datasets if applicable.
