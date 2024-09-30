# Fire Detection in Videos using YOLOv8

This repository contains a project that detects fire in videos using the YOLOv8 model. The model is trained to recognize fire in video frames, making it useful for real-time monitoring and early fire detection in security or surveillance systems.

## Table of Contents
- [Overview](#overview)
- [Model Architecture](#model-architecture)
- [Dataset](#dataset)
- [Training](#training)
- [Usage](#usage)
  - [Installation](#installation)
  - [Running the Model](#running-the-model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview
Fire detection plays a critical role in safety and surveillance systems. This project uses the YOLOv8 model, known for its accuracy and speed, to detect fire in video streams in real-time. The trained model can be integrated into existing systems for automatic fire detection.

## Model Architecture
YOLOv8 is a cutting-edge deep learning model designed for object detection. It is particularly well-suited for real-time applications, thanks to its speed and accuracy. In this project, the model was trained specifically to identify fire in video frames.

## Dataset
The model was trained on a dataset of video frames containing fire and non-fire scenes. The dataset includes a wide range of scenarios, such as:
- Wildfires
- Indoor fires
- Small and large fire instances

The dataset was split into training, validation, and test sets to ensure the model generalizes well to unseen data.

## Training
The YOLOv8 model was trained using the following key parameters:
- **Batch size**: 16
- **Image size**: 640x640
- **Epochs**: 100
- **Learning rate**: 0.001

### Model Performance
The model was evaluated on a test set of videos and achieved a high detection rate for fire, making it highly reliable for fire detection tasks.

## Usage

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Musawer1214/Fire-Detection.git
   cd Fire-Detection
