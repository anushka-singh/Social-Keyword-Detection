# Social Keyword Detection Documentation

### This repository contains the data and scripts which comprise the Social Keyword Detection models. Three approaches were implemented and tested and this repository contains the code and the actual dataset used to train and test the approaches. The dataset is composed of over 102 labeled real-world data files plus a novel scoring mechanism designed for real-time applications.

### Included are the tools which allow you to run the models. 

### Three approaches

##### 1.Spectrogram Based Classification 
a. A spectrogram is regarded as a very detailed and accurate representation of audio information. 
b. Classification of audio with variable length using a CNN architecture on the Mechanically Generated Dataset. 


##### 2.Google Speech Recognition
a. Speech Recognition using the Google API 

Installation

<sudo pip install SpeechRecognition>

<sudo apt-get install python-pyaudio python3-pyaudio>


##### 3.Wavenet Based Approach - Final model
a. Uses soundex and edit distance for similarity between pronounced words and transcribed words. 

Usage 
<python wavenet/recognize.py> 



##### Data folder used to perform all tests. <Mechanical Turk Data> 
