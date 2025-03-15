# data-analytics-projects
A collection of data analysis projects using Python

# Data Analytics Final Project - Predicting Hospital Length of Stay

This repository contains our "IT Course Final Project", focusing on "predicting hospital length of stay" using regression models. We use the "MIMIC2 dataset" (Multiparameter Intelligent Monitoring in Intensive Care) and apply machine learning techniques to analyze patient data and build a predictive model.


# Important: Why is the dataset not included?
The dataset is not included in this repository due to:
Privacy and ethical considerations: The dataset contains de-identified patient health data, which should be handled with care.
Storage limitations on GitHub: The dataset is too large to be uploaded to this repository.

# How to Access the Data
Since our dataset is stored on Google Drive, please follow the method to use it:
You can download the dataset using gdown:
```python
import gdown
# Google Drive file ID
file_id = "106re38r_Ix5r8iPmkNlFfvZg_QsW05_s"

# Download the file
gdown.download(f"https://drive.google.com/uc?id={file_id}", "data.xlsm", quiet=False)
