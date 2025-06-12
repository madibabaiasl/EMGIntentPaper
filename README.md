# EMG-TransNN-MHA: A Transformer-Based Model for Enhanced Motor Intent Recognition in Assistive Robotics

This repository contains the code and data for the paper on EMG-based intent detection, using transformer-based models to classify upper limb gestures. The project utilizes the EMG dataset from the IEEE DataPort, focusing specifically on EMG data to identify user intent in assistive robotics applications.

    Dataset Link: https://ieee-dataport.org/documents/emg-eeg-dataset-upper-limb-gesture-classification
    Models: Includes several transformer-based models for classification tasks.
    Goal: To develop a robust model that can classify different upper limb gestures for applications in assistive robotics.

## Repository Structure

    All-Model-1.zip: Contains the trained models used for intent detection.
    EDA And Data Cleaning.zip: Includes exploratory data analysis (EDA) and data cleaning scripts.
    README.md: Documentation for understanding and using the repository.

## Dataset Description

The dataset used in this project is publicly available on IEEE DataPort and contains EMG data. This repository specifically uses EMG data acquired through the Myo armband with 8 channels at a 200 Hz sampling frequency. The dataset has been preprocessed for gesture classification tasks.
Usage

    Data Preprocessing:
        Unzip the EDA And Data Cleaning.zip file.
        Run the data cleaning and preprocessing scripts provided to prepare the data for training.

    Model Training and Evaluation:
        Unzip All Model.zip to access pre-trained models.
        Follow the instructions in the scripts to either retrain or evaluate the models on the dataset.

## Citation
```bash
@inproceedings{joby2024emg,
  title={EMG-TransNN-MHA: A Transformer-Based Model for Enhanced Motor Intent Recognition in Assistive Robotics},
  author={Joby, Joel Aikkarakudiyil and Sikorski, Pascal and Sultan, Tipu and Akbarpour, Hadi and Esposito, Flavio and Babaiasl, Madi},
  booktitle={2024 IEEE International Conference on Big Data (BigData)},
  pages={8691--8693},
  year={2024},
  organization={IEEE}
}
