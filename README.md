# SpeechRecognition-to-Text
This app covert from audio file and cobvert into text
 SPEECH to TEXT

## PROBLEM STAEMENT
In this project our goal is to acheive the problem of converting audio data into textual data.
DESCRIPTION OVERVIEW
Speech Recognition is an important feature in several applications used such as home automation, artificial intelligence, etc. This article aims to provide an introduction on how to make use of the SpeechRecognition library of Python. This is useful as it can be used on microcontrollers such as Raspberri Pis with the help of an external microphone.
Speech recognition technologies such as Alexa, Cortana, Google Assistant and Siri are changing the way people interact with their devices, homes, cars, and jobs. The technology allows us to talk to a computer or device that interprets what we’re saying in order to respond to our question or command.
Popular digital assistants, include:
⦁	Amazon’s Alexa
⦁	Apple’s Siri
⦁	Google’s Google Assistant
⦁	Microsoft’s Cortana

### TECHNOLOGY USE
Here we will be using  Anaconda Python 3.6 and SpeechRecognition package.

### INSTALLATION
Installation of this project is pretty easy. Please do follow the following steps to create a virtual environment and then install the necessary packages in the following environment.

### In Pycharm it’s easy 

1. Create a new project.
2. Navigate to the directory of the project
3. Select the option to create a new new virtual environment using conda with python3.6
4. Finally create the project using used resources.
5. After the project has been created, install the necessary packages from requirements.txt file using the command pip install -r requirements.txt


### In Conda also it’s easy

1. Create a new virtual environment using the command
    conda create -n your_env_name python=3.6
2. Navigate to the project directory.
3. Install the necessary packages from requirements.txt file using the command         
pip install -r requirements.txt

### IMPLEMENTATION
1. Project Directory
This is the folder stucture of this project.
2. requirements.txt
 This file contains the necessary package called SpeechRecognition
3. speechToText.py
This file contains the script to convert the speech to text using SpeechRecognition package.
4. clientApp.py


This this is the flask server file and entry point of your application.
TESTING IN LOCAL/API
To run this project in your local system just run the file clientApp.py and after that web server will start at http://0.0.0.0:5000/
 
Browse and Upload the .wav file and click on Predict button.
 Finally you will get the decoded text in the Results box.

## CONCLUSION

Hence we have successfully converted audio data or speech to digital text data.
COMPARISION
Here we can improve the results by testing with other APIs which are available from diffrent third party sources or by applying deep learning approaches.

**1) Home UI**

![1) Home UI](https://github.com/sohel-jagirdar/SpeechRecognition-to-Text/assets/52422511/23c5c7fa-ff6e-40c3-b4dd-7216d45f5135)

**2) send for prediction**

![2) send for prediction](https://github.com/sohel-jagirdar/SpeechRecognition-to-Text/assets/52422511/51b9c39f-4f2b-4ef8-b711-c7bf12794017)

**3) Prediction Output Result**

![3) Prediction Output Result](https://github.com/sohel-jagirdar/SpeechRecognition-to-Text/assets/52422511/780191ff-1524-4b18-a5b8-d5fc761955fb)

