# Emotion_detection

This repository implements an emotion recognition system that can predict the emotion of a given text or transcribed speech. The model is trained on the Emotion dataset, and it uses machine learning techniques such as Natural Language Processing (NLP) and a Naive Bayes classifier to predict the emotion of the text. The system can also transcribe audio files using the Whisper model and predict the emotion from the transcribed text.

**Features**
Text-Based Emotion Recognition: The system predicts the emotion of a given text.
Audio-Based Emotion Recognition: The system transcribes audio to text using the Whisper model and then predicts the emotion from the transcribed text.
Preprocessing: The text is preprocessed by removing special characters and stopwords before feeding it into the model.
Model Saving: The trained model and vectorizer are saved using joblib for future use.
Predicted Emotions: The system can predict six different emotions: anger, fear, joy, sadness, surprise, and love.

**Requirements**
Python 3.x
numpy
pandas
seaborn
neattext
joblib
whisper
sklearn
datasets

**Emotion Labels**
The model predicts the following emotions:

0: Anger
1: Fear
2: Joy
3: Sadness
4: Surprise
5: Love
