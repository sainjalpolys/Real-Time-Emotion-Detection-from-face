# Real-Time-Emotion-Detection-from-face
Developed a vision system that performs face detection and emotion classification in a single integrated module
Real-time face detection and emotion/gender classification using fer2013/IMDB datasets with a keras CNN model and openCV.

* fer2013 emotion classification test accuracy: 66%.





### To train previous/new models for emotion classification:


* Download the fer2013.tar.gz file from [here](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)

* Move the downloaded file to the datasets directory inside this repository.

* Untar the file:
> tar -xzf fer2013.tar

* Run the train_emotion_classification.py file
> python3 train.py

