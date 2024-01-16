# Helmet_NoPlate_Recognition
Dataset link: https://universe.roboflow.com/gw-khadatkar-and-sv-wasule/helmet-and-no-helmet-rider-detection
# YOLOV8 Helmet License Plate Detection System - Setup Instructions

## Overview

This project addresses traffic accidents by enforcing helmet regulations through a YOLO-based detection system. The dataset is diverse and annotated with three classes: With Helmet, Without Helmet, and License Plate.

## Instructions for Use

```bash
# 1. Download Project Files
# Download and extract the project files from the GitHub repository.

# 2. Set Up Virtual Environment
# Navigate to the extracted project folder and create a virtual environment.
python -m venv env

# 3. Activate Virtual Environment
# Activate the virtual environment.
# For Windows:
.\env\Scripts\activate
# For Unix or MacOS:
source env/bin/activate

# 4. Install Dependencies
# Install required dependencies.
pip install -r requirements.txt
# Install Ultralytics and YOLO.
pip install ultralytics
pip install yolo

# 5. Configure Paths
# Navigate to the "run_py_files" folder and open the Python files.
# Update paths for custom models and datasets.

# 6. Run the Model
# Execute the main Python script (e.g., main.py).
python main.py
