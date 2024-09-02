Car License Plate Detection Model using YOLOv8
This repository contains a car license plate detection model built using YOLOv8. The model is trained on a dataset sourced from Kaggle and is capable of detecting car license plates from images and videos with high accuracy. The frontend for the model is designed using Streamlit, providing an easy-to-use interface for users.

Dataset
The dataset used for training the model is obtained from Kaggle and consists of 433 images with their corresponding annotations in XML format.

Kaggle Dataset: Car License Plate Detection Dataset
Model
The model is built using YOLOv8, a state-of-the-art object detection algorithm. After training, the model is saved as best.pt.

Project Structure
notebooks/: Jupyter notebooks used for data exploration, preprocessing, and model training.
models/: Directory containing the trained YOLOv8 model (best.pt).
app/: Contains the Streamlit app code for the frontend.
data/: Includes sample images for testing the model.
requirements.txt: Lists all the dependencies required to run the project.
