ODIS-Orderly Demeanour Inspection System

Introduction

In recent times as we could notice there are many situations where we have to
leave back loved ones even though when we want to be with them, or when they
need special care. This has gone to an extent where security cams that were once
used for guarding the house has evolved into cams we use today to make sure the
person is doing good. But the fact no matter what we do we can never make the
person left behind feel our presence or help them when they need emotional
support via watch cams. What if we said that we can indeed create a software to
help as an emotional support for users in need. The project we propose is one of
it’s kind emotional support system ODIS which creates a conversation to help the
user gain emotional balance.

Modules and Functionalities
1.Emotion Recognition
2.speech Recognition

1.Emotion Recognition:
Facial Recognition verifies if two faces are same. The use of facial recognition is huge in security, bio-metrics, entertainment, personal safety, etc. The same python library open cv used for face detection can also be used for face recognition. Our testing showed it had good performance. Given two faces match, they can be matched with each other giving the result as True or False. The steps involved in facial recognition are

1.Find face in an image
2.Analyze facial feature
3.Compare features for the 2 input faces

Returns True if matched or else False.
The code snippet that does this is below. We create face encoding vectors for both faces and then use a built in function to compare the distance between the vectors.

Some dependencies to install for emotion recognition like install keras,open cv,Tensorflow,numpy,keras important for that.

Then finally to install dependency file then ru first train.py file to training the module and execute the test.py module.


Dependencies to install for Emotion Recognition:

pip install opencv-python  
pip install tensorflow   
pip install numpy    
pip install pandas    
pip install keras   
pip install adam   
pip install kwargs    
pip install cinit  

Speech Analysis:

It will get some emotions from face recogniton file then it will speak with the person from voice mode like human to human chat base.

Dependency to install is:

pip install --upgrade pip
pip install tensorflow
pip install opencv-python
pip install tensorflow
pip install numpy
pip install pandas
pip install keras
pip install audio
pip install SpeechRecognition
pip install pickle5
pip install nltk
pip install lemminflect
pip install gTTS


NLTK for training module,lemminflect is wordlemmatizer to specific the word to present the response and tensorflow is machine learning module it interact file

Then finally to install dependency file then ru first train.py file to training the module and execute the test.py module.

Software Requirements are:
Pycharm or Visual Studio code
