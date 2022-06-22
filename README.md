# Sentiment-Classification
## Data:
* In this project we used the CMU-MOSEI dataset which is multimodal sentiment analysis and emotion recognition to date. The dataset contains more than 23,500 sentence utterance videos from more than 1000 online YouTube speakers. http://multicomp.cs.cmu.edu/resources/cmu-mosei-dataset/.

* We divided the data into two classes ['Negative' , 'Positive'].

* We used three different kinds of features {vision, audio, text}.

* OpenFace and OpenSmile were used to extract features

## Models and Results:
* We used a DNN model to classify the vision data and another DNN model for the audio data, Bi-LSTM and LSTM neural network was used to classify the textual data then we concatenate the three models followed by some dense layers.

1- We achieved 72% accuracy on the vision data.

2- We achieved 72% accuracy on the audio data.

3- We achieved 78% accuracy on the textual data.

4- We achieved 81% accuracy with the final model.
