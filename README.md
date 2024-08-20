Automating Data Annotation with YOLOv8n 🚀
Overview
This project automates the data annotation process for a larger object detection model. It uses a mini CNN trained with YOLOv8n from Ultralytics.

Features
Utilizes YOLOv8n for high-accuracy object detection.
Automates the annotation process for training larger models.
Easily configurable dataset with data.yaml.
Includes a Jupyter Notebook for training and evaluation.
Installation
Clone the repository:

bash
Copy code


Install dependencies:

bash
Copy code
pip install -r requirements.txt
Install Ultralytics YOLOv8:

bash
Copy code
pip install ultralytics
Usage
Prepare your dataset by adjusting data.yaml to match your data paths.
Run the Jupyter Notebook (notebook.ipynb) to train and evaluate the model.
Perform inference to automatically annotate new images using the trained model.
