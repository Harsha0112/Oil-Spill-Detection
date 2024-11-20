The primary objective of this project is to detect oil spills in the ocean using Sentinel-1 SAR (Synthetic Aperture Radar) satellite imagery. This project employs deep learning models, such as U-Net and DeepLabV3, for oil spill detection and incorporates vessel anomaly detection to identify regions of interest.

Workflow Overview
Model Training and Saving:
Each deep learning model uploaded in this repository (U-Net and DeepLabV3) should be trained individually using the provided dataset.

Save the trained models in a designated folder for reuse.
These models will later be integrated and utilized in the Project2 file for final predictions.
Dataset Details:

Oil Spill Detection Dataset:
Download both the train and test directories from this 
https://www.kaggle.com/datasets/nabilsherif/oil-spill
Kaggle dataset. This dataset contains Sentinel-1 SAR imagery annotated for oil spills.
AIS Vessel Data: https://marinecadastre.gov/accessais/
Access Marine Cadastre to download Automatic Identification System (AIS) vessel data. This data is critical for detecting ship anomalies and generating regions of interest for oil spill detection.
Prerequisites
Deep Learning Knowledge: Familiarity with models like U-Net and DeepLabV3 is required to train and fine-tune the models effectively.
Python Programming: Proficiency in Python is essential for running and modifying the scripts.
Required Libraries: Ensure all necessary dependencies are installed, including TensorFlow, Keras, and OpenCV. Use the requirements.txt file in the repository to set up the environment.
Instructions
Download the datasets mentioned above.
Train each model using the respective script provided.
Save the trained models in the models directory (or any specified path).
Use the Project2 file to combine oil spill detection and AIS-based anomaly detection for end-to-end processing.
