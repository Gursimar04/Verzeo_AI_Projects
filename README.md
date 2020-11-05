# Verzeo_AI_Projects

### Table Of Contents
- [Project-Directory](#project-directory)
- [Outstanding-Projects](#outstanding-projects)
    * [CNN-for-MNIST-Dataset](#cnn-for-mnist-dataset)
    * [Motion-Detection-using-Pixel-Differencing](#motion-detection-using-pixel-differencing)
    * [Pedestrian-Detection-using-OPENCV](#motion-detection-using-pixel-differencing)
- [Major-Projects](#major-projects)
    * [Tensorflow-Speech-Recognition-Challenge](#tensorflow-speech-recognition-challenge)
    * [Speech-Translation-using-Google-APIs](#speech-translation-using-google-apis)
- [Minor-Projects](#minorproject)
    * [CNN-for-Mask-Detection](#cnn-for-mask-detection)
- [Author Info](#author-info)

---
## Project-Directory

``` bash 
+---Outstanding Projects
|   |       
|   +---MNIST dataset *(CNN)*
|   |   |   Outstanding-Project-1_MNIST_Gursimar.ipynb
|   |   |   submission.csv
|   |   |   test.csv
|   |   |   train.csv
|   |   |   
|   |           
|   +---Movement Detection  *(Pixel Differencing)*
|   |   |   input.mp4  *(Input Video)*
|   |   |   Outstanding-Project-2_Movement Detection.ipynb
|   |   |   vehicle_detection_v3.mp4  *(Output Video)*
|   |   |       
|   |   +---frames  *(Folder containing of frames extracted from the input video)*
|   |   |       
|   |   \---output  *(Frames after object detection)*
|   |           
|   \---Pedestrian Detection
|       |   Outstanding-Project-3_Pedestrian Detection Model.ipynb  *(OPENCV)*
|       |   
|       \---Pedestrian  *(Test Images)*
|               
+---Verzeo_Major_Projects
|   |   Please Read.txt
|   |       
|   +---AudioToTextFromScratch  *(Tensorflow Speech Recognition Challenge)*
|   |   |   AudioToTextFromScratch.ipynb 
|   |   |   
|   |   +---best_model  *(Saved Model)*
|   |   |   |   Please Read.txt
|   |   |   |   saved_model.pb
|   |   |   |   
|   |   |   +---assets
|   |   |   \---variables
|   |   |           variables.data-00000-of-00001
|   |   |           variables.index
|   |   |           
|   |   +---input  *(Test Voice Commands-Playable in IPYNB File)*
|   |   |   \---voice_commands
|   |   |       \---simar_voice
|   |   |               down.wav
|   |   |               go.wav
|   |   |               left.wav
|   |   |               no.wav
|   |   |               off.wav
|   |   |               on.wav
|   |   |               right.wav
|   |   |               stop.wav
|   |   |               up.wav
|   |   |               yes.wav
|   |   |               
|   |   \---train 
|   |       |   DatasetLink.txt
|   |       |   
|   |       \---train
|   |           \---train
|   |               |   LICENSE
|   |               |   README.md
|   |               |   testing_list.txt
|   |               |   validation_list.txt
|   |               |   
|   |               \---audio
|   |                       read.txt
|   |                       
|   \---TextToSpeech_and_SpeechToText_Togather *(using speech recognizer, googletrans, and gTTS)*
|       |   LanguageTranslation.ipynb
|       |   Please Read.txt
|       |       
|       +---input  *(contains test audio files)*
|       |       
|       \---output  *( translated audio files (50 languages))*
|           |   
|           \---example
|                   bengali.mp3
|                   
\---Verzeo_Minor_Project  *(Mask Detection- Needs a lot of work)*
    |   GettyImages-1216623969.jpg
    |   haarcascade_frontalface_alt.xml  *(For Face Detection)*
    |   mask_classifier.ipynb
    |   mask_cnn
    |   randomImage1.jpg
    |       
    +---Dataset COVID-19 Augmented 
    |   +---test
    |   |   +---mask
    |   |   |       
    |   |   \---nonmask
    |   |           
    |   +---train
    |   |   +---mask
    |   |   |       
    |   |   \---nonmask
    |   |           
    |   \---validate
    |       +---mask
    |       |       
    |       \---nonmask
    |               
    +---face_detector  *(Weights for Face Detection- better than haarcasade)*
    |       deploy.prototxt
    |       res10_300x300_ssd_iter_140000.caffemodel
    |       
    \---Success_Images 
            


```
## Outstanding-Projects
These 3 projects were completely optional and were to be done without any mentor guidance in exchange for an outstanding performer certificate.

   ### CNN-for-MNIST-Dataset
  MNIST ("Modified National Institute of Standards and Technology") is the “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. The goal for classification is to correctly identify digits from a dataset of tens of thousands of handwritten images. In the well-documented jupyter notebook, I have used Tensorflow's sequential API with Early stopping to train a CNN that can calssify the dataset with **99.39%** validation accuracy. At the end one can find the confusion matrix and the incorrectly predicted lables for review.
    
   ### Motion-Detection-using-Pixel-Differencing
  Taking the input as a video of vehicles moving on a highway, the jupyter notebook contains the process of detecting motion though pixel differencing. The basic idea is to divide videos into its frame and find the difference in pixels beween consecutive frames. The technique is straightforward but works only with a still camera.
    
   ### Pedestrian-Detection-using-OPENCV
  OpenCV ships with a pre-trained HOG + Linear SVM model that can be used to perform pedestrian detection in both images and video streams. HOG stands for Histogram of Oriented Gradients. We will be using that to our advantage in this project. Read the ipynb file for more information
  
---
  
## Major-Projects
The folder consists of Audio-specific neural network model and a speech translation model created using Google APIs.

   ### Tensorflow-Speech-Recognition-Challenge
   **Link to dataset:**  https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data
    In this link one can find all the details related to this project.
    
   ### Speech-Translation-using-Google-APIs
  In this project we have taken advantage of speech recognizer, googletrans, and gTTS to translate audio into 50 different languages. The project is created with using this technique in a form of an app in the future. Peek into the IPYNB file for further details.
  
---
 ## Minor-Project
   ### CNN-for-Mask-Detection
   This model represents my first try at creating a deep learning model. Considering that it was my first attempt at binary calssification, it needs a lot of work and demands improvement. Will be doing it soon though.

---

## Author Info
- Linkedin - [Gursimar Singh Bedi](https://www.linkedin.com/in/gursimar-singh-bedi-31439a170)

[Back to the top](#Verzeo_AI_Projects)
