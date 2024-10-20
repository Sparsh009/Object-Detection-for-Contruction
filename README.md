# Object Detection for Construction

## Project Overview

This project focuses on building an object detection system for construction sites using a custom-trained YOLOv9 model. The objective is to accurately identify and classify various types of construction equipment and safety gear (e.g., dump trucks, excavators, helmets) within construction site images or videos.

## Key Components

- **YOLOv9 Model**: Utilized for its real-time object detection capabilities.
- **Custom Dataset**: A dataset containing images of construction equipment labeled with corresponding object classes.
- **Training**: The notebook includes code for pre-processing the data, training the model, and evaluating its performance.

## File Structure

- **Train_YOLOv9_Custom_Dataset.ipynb**: The main notebook used for training the YOLOv9 model on the custom dataset. It contains code for:
  - Loading and pre-processing the dataset.
  - Setting up the YOLOv9 model.
  - Training and evaluating the model.
  - Visualizing detection results.

## Requirements

- **Python 3.x**
- **Libraries**:
  - PyTorch
  - OpenCV
  - NumPy
  - Matplotlib
  - YOLOv9-specific dependencies (Install using the requirements file if applicable)

## How to Run

1. Clone the repository and navigate to the project directory:

    ```bash
    git clone <repository_link>
    cd object_detection_for_construction
    ```

2. Install required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Open the notebook and run all the cells to train the YOLOv9 model on the custom dataset:

    ```bash
    jupyter notebook Train_YOLOv9_Custom_Dataset.ipynb
    ```

## Dataset

Ensure you have the dataset prepared in the correct format before running the notebook. The dataset should include:

- **Images**: Construction site images with various objects.
- **Labels**: Corresponding object labels in YOLO format (bounding boxes and class labels).

## Results

The trained model can be used to detect and classify construction objects in real-time using the YOLOv9 detection framework.
