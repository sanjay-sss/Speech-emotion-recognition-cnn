# Speech-emotion-recognition--cnn
Basic Idea :
Our machine learning model tries to detect and predict various emotion in speech signal or human audio by detecting different features and component of speech affected by human emotion. Emotion detection from the speech is a relatively new field of research. Here, we are trying a new approach or ways to contribute towards emotion recognition research.

Our dataset:
We referred two dataset RAVDESS and SAVEE Dataset. Only took the audio data from 
this datasets. 
The RAVDESS database is gender balanced consisting of 24 professional actors. Speech 
part of dataset includes calm, happy, sad, angry, fearful, surprise, and disgust expressions 
and song part of dataset contains calm, happy, sad, angry, and fearful emotions. Each 
expression is produced at two levels of emotional intensity, with an additional neutral 
expression.
The SAVEE dataset consists of recordings from 4 male actors in 7 different emotions, 
480 British English utterances in total.There are 15 sentences for each of the 7 emotion 
categories, and one file for each sentence. It includes 'anger', 'disgust', 'fear', 'happiness', 
'neutral', 'sadness' and 'surprise'.

We made customized dataset by using this two dataset. We have less samples of ‘calm’ 
emotion. Hence we eliminate ‘clam’ samples to balance the dataset. Our dataset contain 7
folders, each represents the different emotion. Contain Separate emotion's voice/speech in
each separate folder.

anger : 436 samples

disgust : 252 samples

fear : 436 samples

happy : 436 samples

neutral : 308 samples

sad : 436 samples

surprise : 252 samples

Total : 2556 Samples

Our project presents a new way to give the ability to machine to determine the
emotion with the help of the human voice. It will give the machine the ability to have a
better approach towards having a better conversation and seamless conversation like
human does
