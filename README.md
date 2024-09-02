# Car License Plate Detection Model using YOLOv8
This repository contains a car license plate detection model built using YOLOv8. The model is trained on a dataset sourced from Kaggle and is capable of detecting car license plates from images and videos with high accuracy. The frontend for the model is designed using Streamlit, providing an easy-to-use interface for users.

## Dataset
The dataset used for training the model is obtained from Kaggle and consists of 433 images with their corresponding annotations in XML format.

Kaggle Dataset: [Car License Plate Detection Notebook](https://www.kaggle.com/code/ravee360/car-license-plate-detection)

Model
The model is built using YOLOv8, a state-of-the-art object detection algorithm. After training, the model is saved as best.pt.

## Project Structure
- notebooks/:[ Kaggle notebooks](https://www.kaggle.com/code/ravee360/car-license-plate-detection) used for data exploration, preprocessing, and model training.
- best.pt: Directory containing the trained YOLOv8 model (best.pt).
- yolo_application.py: Contains the Streamlit app code for the frontend.
- data/: Includes sample images for testing the model.
- requirements.txt: Lists all the dependencies required to run the project.
## Usage
Upload an image containing a car license plate through the Streamlit interface.
The app will display the image with the detected license plate highlighted.
## Results
The model was trained for 100 epochs and achieved a mAP50_0.9 and mAP50-95_0.5 on validation set.

## Acknowledgments
- Kaggle community for the Car License Plate Detection Dataset.
- YOLOv8 developers for providing a robust and flexible object detection framework.
- Streamlit for creating an easy-to-use framework for building web apps.


## Contact
For any questions, please feel free to reach out at my linkedin mentioned in my profile.
