**Gesture Talk - Sign Language Conversion System (Android App)**


Gesture Talk is an AI-powered Android application designed to assist in converting sign language gestures into text and speech. This project aims to enhance communication between individuals who use sign language and those who do not, by providing a user-friendly platform for real-time gesture recognition and conversion.

Features
Sign Language to Text Conversion
The app detects hand gestures via the device's camera and converts them into corresponding text, making it easier for individuals using sign language to communicate with others.

Text to Speech Conversion
The recognized text can be transformed into speech using the built-in text-to-speech engine, allowing the message to be vocalized.

Real-Time Gesture Recognition
Using advanced machine learning models and the device’s camera, Gesture Talk processes hand gestures in real time, providing immediate feedback for fluent conversation.

Easy-to-Use Interface
The app features a simple, user-friendly interface, designed with accessibility in mind for both technical and non-technical users.

Pre-Trained Model and Dataset
Gesture Talk comes with a trained model and dataset, ensuring high accuracy for gesture recognition out-of-the-box.

Offline Support
Once the app is installed, Gesture Talk can run without the need for an internet connection, making it useful in various environments.

Files in the Repository
APK File: The compiled Android app that can be installed directly on your device.
Dataset: The dataset used to train the machine learning model for recognizing sign language gestures.
Model Code: Python code for training the AI model using the provided dataset.
Android Code: Source code for the Android app, including gesture recognition and user interface logic.
Technology Stack
Android Studio: Used for Android app development.
TensorFlow Lite: The mobile version of TensorFlow is integrated for on-device gesture recognition.
OpenCV: Used for image processing and gesture tracking through the camera.
Java/Kotlin: For Android app development and functionality.
Text-to-Speech (TTS): Android's native TTS engine for converting text to speech.
Python: For developing the machine learning model and training on the dataset.
How Gesture Talk Works
Gesture Detection
The Android app accesses the camera to capture the user's hand movements. OpenCV is used to track the hands, while TensorFlow Lite interprets the gestures based on the pre-trained model.

Gesture Recognition
The recognized gestures are mapped to corresponding words or phrases and displayed as text on the screen. The machine learning model was trained using a custom dataset uploaded in this repository.

Text-to-Speech Conversion
After translating gestures into text, the user can enable the text-to-speech feature to vocalize the converted text, facilitating communication.

Installation Instructions
Download APK
Download the APK file from the repository and install it on your Android device.

Enable Install from Unknown Sources
Ensure you have allowed installation of apps from unknown sources in your Android settings.

Run the Application
Open the app, grant camera permissions, and start using Gesture Talk by making sign language gestures in front of your camera.

Dataset and Model
The dataset used for training the gesture recognition model is available in the repository for users interested in enhancing or retraining the model.
The Python code for training the model can be found in the model-code folder, which includes scripts for preprocessing the dataset and training the model.
Future Enhancements
Customizable Gestures
Allow users to define and train their own gestures for a more personalized experience.

Additional Sign Languages
Currently, the app supports a specific set of sign languages. Future updates could include support for additional regional and international sign languages.

Gesture Accuracy Improvements
Continuous improvements to the machine learning model for more complex and accurate gesture recognition.

Cross-Platform Support
Expanding the project to include iOS support or a web-based version for broader accessibility.
