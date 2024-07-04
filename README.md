# Object Detection from Live Video

This project performs real-time object detection from live video streams using Convolutional Neural Networks (CNN) and Region-based Convolutional Neural Networks (RCNN). The system can detect and classify objects in the video stream and draw bounding boxes around them.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Object detection is a crucial task in computer vision that involves identifying and localizing objects within an image or video. This project leverages the power of deep learning models, specifically CNN and RCNN, to achieve accurate and efficient object detection in live video feeds.

## Features

- Real-time object detection from live video streams.
- Uses CNN for feature extraction and RCNN for object detection.
- Visualizes detected objects with bounding boxes and labels.
- Easy-to-use and customizable.

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/object-detection-live-video.git
    cd object-detection-live-video
    ```

2. **Create and activate a virtual environment** (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:

    ```bash
    pip install -r requirements.txt
    ```
