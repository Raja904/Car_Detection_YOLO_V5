# Car Detection with YOLO V5 Model (Transfer Learning)

## Overview

This project focuses on car and jeep detection using the YOLO (You Only Look Once) version 5 model with the application of transfer learning. The dataset, comprising images from highway traffic cameras, was annotated using the "roboflow" software. This annotated dataset, consisting of 100 images, was divided into training, testing, and validation sets, with the objects classified into two categories: "Car" and "Jeep."

The YOLO V5 model was then fine-tuned through transfer learning to enhance its ability to detect and classify cars and jeeps in a variety of scenarios.

## Dataset

The dataset utilized in this project is sourced from open data repositories and features images captured by highway traffic cameras. Annotation of the dataset was carried out using the "roboflow" software, ensuring precise labeling of cars and jeeps. The dataset includes 100 images, with a balanced distribution across training, testing, and validation sets.

### Classes
1. Car
2. Jeep

## Transfer Learning with YOLO V5 Model

Transfer learning involves leveraging the knowledge gained by a pre-trained model on a large dataset and applying it to a specific task with a smaller dataset. In this project, transfer learning was employed to fine-tune the YOLO V5 model on the annotated dataset, enabling it to excel in the task of car and jeep detection in highway traffic camera images.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Car_DETECTION_YOLO_V5.git
   cd Car_DETECTION_YOLO_V5

## Results and Training Metrics

### Classification Results

Here are some sample results showcasing the classification of cars and jeeps:
![val_batch0_labels](https://github.com/Raja904/Car_Detection_YOLO_V5/assets/108182700/ed0e1ded-72aa-4aed-9e30-ef12d42e87a5)



### Training Metrics Curve

The following curve illustrates the variation of key metrics over training epochs:


![results](https://github.com/Raja904/Car_Detection_YOLO_V5/assets/108182700/ff239491-e11b-4190-88c2-cfcb6641052a)



- **X-axis:** Training epochs
- **Y-axis:** Loss and metric values

#### Metrics Included:
- Box Loss
- Object Loss
- Classification Loss
- Precision
- Recall


Feel free to explore the detailed results and metrics for a deeper understanding of the model's performance during training.

---



## Acknowledgments

Special thanks to the contributors of the [YOLO V5 GitHub repository](https://github.com/ultralytics/yolov5) and the creators of the "roboflow" software for their valuable tools and resources.

Feel free to contribute, report issues, or provide feedback to enhance the functionality of this car detection project.


