﻿# Fire Detection Project

![Demo](https://github.com/username/repository/raw/main/assets/m1.jpeg)
## Overview

This project implements a fire detection system using the YOLO (You Only Look Once) model, specifically tailored for real-time object detection. The YOLO model has been trained to accurately identify fire in images, enabling effective and precise fire detection. This repository provides all the necessary code and instructions for setting up and running the fire detection system.

## Features

- **Real-Time Detection:** Leverages the YOLO model for real-time fire detection in images.
- **Pre-Trained Model:** Utilizes a pre-trained model for efficient and accurate predictions.
- **Easy Integration:** Simple setup process for integrating fire detection into your applications.

## Installation

To get started with this project, follow these steps to set up your environment and install the required dependencies.

### 1. Mount Google Drive

Mount your Google Drive in Google Colab to access the pre-trained model and input images.

```python
from google.colab import drive
drive.mount('/content/drive')
