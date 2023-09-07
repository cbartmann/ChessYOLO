 # ChessYOLO
 # Deep Learning for Visual Computing: Exercise 3 Submission

This repository contains the submission for Exercise 3 of the Deep Learning for Visual Computing course. It includes details on the workflow and results, which can be found in the report.

## Repository Structure

- `dataset_generation.ipynb`: This Jupyter Notebook manages the dataset generation. To generate any number of test instances, replace the cookies with the ones for the personal user. Prior to starting the dataset generation, delete the instances in the `Data` and `custom_data` folders. Although it is not necessary unless you want to train a new model.\

- `Data` folder: Stores the raw, cropped images and labels. In this submission, we've only included the labels due to data size limitations. We don't see a benefit in including the raw images in the submission.\

- `custom_data` folder: Contains the data split into train, validation, and test sets. It's formatted to aid the training of YOLOv5 by the ultralytics repository. The actual data can be downloaded from https://drive.google.com/drive/folders/1GVLntmFLohUCDhRm9Te9VNfnDW6tFsuz?usp=sharing. We couldn't include it in the submission due to the size of the data.\

- `YOLOv5.ipynb`: This notebook is used for the training and inference of the YOLOv5 model and is meant to be used with Google Colab. Training was done using the custom yaml file included in the `Training colab` folder. The optimal training parameters are also included in this folder, along with the best weights used for inference.\

- `Evaluation.ipynb`: This notebook establishes a pipeline for the evaluation of the predictions, which are stored for the training, test, and validation sets in the `Predictions` folder.\

For more information, please refer to the report included in the repository.

# ChessYOLO
