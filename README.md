## PPE Detection with YOLOv8

### Project Overview

This project focuses on detecting Personal Protective Equipment (PPE) using YOLOv8. The goal is to identify and classify PPE items such as gloves, helmets, footwear, and goggles in images of workers.

### Dataset and Annotation

- **Dataset**: Hundreds of images featuring workers equipped with various types of PPE.
- **Annotation Tool**: LabelImg was used for annotating the images.
- **Data Splitting**: The dataset was divided into training, testing, and validation sets to ensure robust model evaluation.

### Training and Validation

- **Model**: YOLOv8s.pt was utilized for training the model on the custom PPE dataset.
- **Hardware**: Training was performed using the T4 GPU on Google Colab for efficient computation.

### Evaluation Metrics and Visualization

- **Metrics**: The performance of the model was evaluated using several metrics, including the F1 score.
- **Graphs and Curves**: Generated visualizations include:
  - F1 score graph
  - Label distribution graph
  - Precision-Recall (PR) curve
  - Confusion matrix
- **Validation**: A validation image (validation.png) was produced to showcase the model’s performance.

### Tools and Libraries

- **LabelImg**: For annotating the dataset.
- **YOLOv8**: For object detection.
- **Google Colab**: For model training using T4 GPU.
- **IPython**: For visualizing results.

### Results

The project successfully demonstrates the capability of YOLOv8 in detecting PPE items from annotated images, providing a detailed evaluation of model performance through various metrics and visualizations.

### View the Notebook
You can view the detailed notebook on [Nbviewer](https://nbviewer.org/github/Deepparekh08/PPE-detection-with-YOLOv8/blob/main/Yolov8_object_detection.ipynb).

