# ODIS - Orderly Demeanour Inspection System

## Introduction:
In recent times, there have been many situations where we are forced to leave behind loved ones, even when we want to be with them or when they require special care. While security cameras once served solely to protect properties, they have now evolved into tools that help us monitor the well-being of those we care about. However, despite technological advancements, we can never truly make a person feel our presence or offer emotional support just through cameras. 

What if we told you that we can indeed create a software solution that provides emotional support to users in need? The project we propose is **ODIS** (Orderly Demeanour Inspection System), an innovative emotional support system designed to create conversations and help users achieve emotional balance during difficult times.

## Modules and Functionalities:

### 1. Emotion Recognition
### 2. Speech Recognition

---

## 1. Emotion Recognition:
**Facial Recognition** technology plays a crucial role in various domains such as security, biometrics, entertainment, and personal safety. In the context of ODIS, facial recognition is used to detect and verify emotions based on facial expressions, enabling the system to respond with the appropriate emotional support.

### How it Works:
The facial recognition system verifies if two faces match, which can be used to determine emotional states. Using the Python library **OpenCV**, we first detect the face and then analyze facial features to assess emotional expressions.

### Steps Involved:
1. **Find face in an image**
2. **Analyze facial features** to detect emotional cues
3. **Compare features** from two input faces

The system will return `True` if a match is found (i.e., emotional expression recognized) or `False` if there’s no match.

### Dependencies for Emotion Recognition:
To implement emotion recognition, we need the following libraries:
```bash
pip install opencv-python
pip install tensorflow
pip install numpy
pip install pandas
pip install keras
pip install adam
pip install kwargs
pip install cinit
