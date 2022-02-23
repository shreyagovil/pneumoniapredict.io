# Pneumonia Detector

## About

This webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:


- Pneumonia

## Models with their Accuracy of Prediction

| Disease        | Type of Model            | Accuracy |
| -------------- | ------------------------ | -------- |
| Pneumonia      | Deep Learning Model(CNN) | 95%      |

## NOTE

==> You can access the website live at: https://pneumoniadetector.azurewebsites.net/ <br>
==> Python version 3.6.15 was used for the whole project.<br>

## Steps to run this application in your system

1. Clone or download the repo.
2. Open command prompt in the downloaded folder.
3. Create a virtual environment

```
mkvirtualenv environment_name
```

4. Install all the dependencies:

```
pip install -r requirements.txt
```

5. Run the application

```
python app.py
```

## Dataset Links

All the datasets were used from kaggle.


- [Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
