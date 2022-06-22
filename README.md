## Sentiment-Classification
# Data:
In this project we used CMU-MOSEI dataset which are multimodal sentiment analysis and emotion recognition to date. The dataset contains more than 23,500 sentence utterance videos from more than 1000 online YouTube speakers. http://multicomp.cs.cmu.edu/resources/cmu-mosei-dataset/.
We divided the data into two calsses ['Negative' , 'Positive'].
We used three diffrent kinds of featurs {Vision, audio, text}.
# Models and Results:
We used DNN model to classify the vision data and another DNN model for the audio data, Bi-LSTM and LSTM neoural network was used to classify the text data then we concatanate the three models followed by some layers.

