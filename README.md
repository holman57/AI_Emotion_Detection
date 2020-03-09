# AI Emotion Recognition
## Spring 2020 AI project

https://docs.google.com/document/d/1PjkWR5__LrFzUJAlzkBKJEJTB5ch_Uyd/edit

- Ethan Kolkmeier ethankolkmeier@my.unt.edu 
- Jawad Ahmed jawadahmed@my.unt.edu 
- Filimon Gebrekidan filimongebrekidan@my.unt.edu 
- Luke Holman lukeholman@my.unt.edu 

## Abstract

Research has indicated that human emotion can be detected via facial expressions and speech, and identifying these emotions may be a quality innate to most humans.

Distinctly classifying these emotions can be difficult, and prime human emotions have been even more difficult to identify.
Machine learning models allow us to not only solve prediction problems, but see how different models solve these problems in a specific domain.

By identifying underlying patterns and using dimensionality reduction via machine learning, we may be able to better understand the distinctions and similarities between human emotions and how we perceive them in others.

We hypothesize that we may be able to identify a set of prime emotions that are recognizable by machine learning models.. This will be accomplished by gathering large datasets of facial expressions and speech clips displaying different levels of emotions.

A model that can accurately detect human emotions in individuals will help social services such as psychiatry, rehabilitation and counselling, by helping bridge any gaps in empathy between patient and caregiver.

## Introduction

Introduction
What is the problem you are addressing? 

- Humans may be able to identify emotions in others fairly easily. However, quantifying these emotions is more difficult, and methods and classifications of recognizable human emotions are debated.

What very specific claim do you hope to make when your work is complete?

- We will show that our method of recognizing emotions from images of faces will improve the F1-measure of the classifier by a relative 33% compared to choosing the most frequent class when applied to images of unseen people’s faces.

Who will care about your system? 

- Caregivers that are required to work with patients directly in situations where the patients current emotions are important to understand, such as counsellors, psychiatrists, therapists, etc.

Why do they care?

- It will aid them in understanding their patients emotional state.

### Basic Emotions, Paul Ekman 
https://drive.google.com/open?id=142GhLrr6pMwemVCF0R3WHJacOR2TIVAJ

Ekman and Friesen identified six basic emotions based on studying the isolated culture of people from the Fori tribe in Papua New Guinea in 1972. The tribe members were able to identify these six emotions on the pictures.
After that, they took pictures of facial expressions of people from the Fori tribe with the same emotions and they presented these pictures to people of other races and cultures all over the world. They also interpreted the emotions on the pictures correctly.

    Anger
    Disgust
    Fear
    Happiness
    Sadness
    Surprise

### Dataset

- **The INTERSPEECH 2020 Computational Paralinguistics ChallengE (ComParE)** is an open Challenge dealing with states and traits of speakers as manifested in their speech signal’s properties. http://www.compare.openaudio.eu/data/

- **The SEWA Database**. A database of annotated audio and 2D visual dynamic behaviour (recorded by standard webcams used by the volunteers) has been collected within the SEWA project. https://db.sewaproject.eu/

- **Cohn-Kanade (CK and CK+) database**. Datasets for training affect recognition and for perception studies. RGB Video http://www.consortium.ri.cmu.edu/ckagree/

- **AFEW** Acted Facial Expressions In The Wild is a dynamic temporal facial expressions data corpus consisting of close to real world environment extracted from movies. https://cs.anu.edu.au/few/AFEW.html

- **RAVDESS**. The Ryerson Audio-Visual Database of Emotional Speech and Song https://zenodo.org/record/1188976#.XlSgTChKhpg

- **DISFA**. Denver Intensity of Spontaneous Facial Action Database is a non-posed facial expression database for those who are interested in developing computer algorithms for automatic action unit detection and their intensities described by FACS. https://web.archive.org/web/20151024114056/http://www.engr.du.edu/mmahoor/DISFA.htm

- **The MUG Facial Expression Database**. The MUG database was created by the Multimedia Understanding Group. It was created to overcome some limitations of the other similar databases that preexisted at that time, such as high resolution, uniform lighting, many subjects and many takes per subject. https://mug.ee.auth.gr/fed/ 

- **RFD**. The Radboud Faces Database is a set of pictures of 67 models (including Caucasian males and females, Caucasian children, both boys and girls, and Moroccan Dutch males) displaying 8 emotional expressions. http://www.socsci.ru.nl:8180/RaFD2/RaFD 

- **MMI**. Facial Expression Database https://mmifacedb.eu/

- **AffectNet**. Existing annotated databases of facial expressions in the wild are small and mostly cover discrete emotions (aka the categorical model). There are very limited annotated facial databases for affective computing in the continuous dimensional model (e.g., valence and arousal). http://mohammadmahoor.com/affectnet/

- **FER+**. new label annotations for the Emotion FER dataset. (Paper) https://arxiv.org/abs/1608.01041 (Images) https://github.com/microsoft/FERPlus

- **iBug**. This dataset is in accordance with the paper Deep Affect Prediction in-the-wild: Aff-Wild Database and Challenge, Deep Architectures, and Beyond. https://ibug.doc.ic.ac.uk/resources/300-W/

**Challenges in Representation Learning**: Facial Expression Recognition Challenge (Kaggle) (Images) https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data 

**DISFA+** The Extended Denver Intensity of Spontaneous Facial Action Database http://mohammadmahoor.com/disfa/

**CK+ dataset for facial expression recognition** (Kaggle) (Images).  https://www.kaggle.com/shawon10/ckplus 

**Facial Expression** (Kaggle) (Images). https://www.kaggle.com/ahmedmoorsy/facial-expression 

**EMOTIC** Dataset http://sunai.uoc.edu/emotic/

**Facial Recognition Databases** https://www.kairos.com/blog/60-facial-recognition-databases 

**CVonline**: Image Databases http://homepages.inf.ed.ac.uk/rbf/CVonline/Imagedbase.htm 

### Papers
1. Facial Emotion Recognition Using Machine Learning https://drive.google.com/open?id=1AeaIHlm-1bhwxjvK_hCrsR2zp9JqKeIM 
SEWA DB: A Rich Database for Audio-Visual Emotion and Sentiment Research in the Wild https://drive.google.com/open?id=1tNdaeDHN9L-jA9PyZ6JIl52aHHwwlFEy 

1. Real Time Facial Expression Recognition using Deep Learning https://drive.google.com/open?id=1ANOWFRuqKOt0Rcifh7T9NedCmodLJHKN 

1. Facial Emotion Recognition using Convolutional Neural Networks https://drive.google.com/open?id=1W-z5GUTP0TNi-CxDRyFDyM67sC50OXG8 

1. Use of Facial Emotion Recognition in E-Learning Systems https://drive.google.com/open?id=1o_-mNq3KWZ3yvuDskX86KHVDUOMvRWqA 

1. Affect Measurement A Roadmap Through Approaches, Technologies, and Data Analysis https://drive.google.com/open?id=1lq9OdsSOe0pZT3Ah1Szlxw_MhJpYPDUL 

1. Detecting Micro-Expressions in Real Time Using HighSpeed Video Sequences https://drive.google.com/open?id=1gdog07BZXtCpYPPI7EZoDG5SroS8K7wH 

1. Recognition of Emotion Intensities Using Machine Learning Algorithms: A Comparative Study https://drive.google.com/open?id=1XHFsSOKA5y5H9CoPpRygZK_JRgV9WBCf 

1. An Expert System for Recognition of Facial Actions and Their Intensity https://drive.google.com/open?id=1o1A732Ujwk-_OZzK_OfoEUza2px5at5b 

1. Adaptive 3D facial action intensity estimation and emotion recognition https://drive.google.com/open?id=1aMXCggEQlPxLwdpws5IfINHWpiwNsoFw 

1. A Model of the Perception of Facial Expressions of Emotion by Humans Research Overview and Perspectives https://drive.google.com/open?id=1c__2WyBwgr75kzFi3qgOjFjRaoIUZToX 

1. Extended deep neural network for facial emotion recognition https://drive.google.com/open?id=13VxUoY0Fz2p5khmxjpQJnW2h2_T5_cZ3 

1. Context Based Emotion Recognition using EMOTIC Dataset https://drive.google.com/open?id=1VEfh_KNAg5Xge0QJdzL1Lr_RoXvYLsHM 

1. Real-time emotion recognition system with multiple physiological signals https://drive.google.com/open?id=1ogPSv1zXXZVhSy5kP-Unthyfwwbr4AlK 

1. FaceNet A Unified Embedding for Face Recognition and Clustering https://drive.google.com/open?id=1m0AeRAPStrP5ESTmg5mh9-8SmU1bq1kN 

1. Automatic Analysis of Facial Affect A Survey of Registration, Representation, and Recognition https://drive.google.com/open?id=1Md7SwyRhMUeeIcmG-x42VsDfEfVddp1t 

### Repositories

- Facial Emotion Recognition. The aim of this section is to explore facial emotion recognition techniques from a live webcam video stream. https://github.com/maelfabien/Facial-Emotion-Recognition/tree/master/Video

- Realtime person's face recognize and can classify emotion using webcam, video or images. https://github.com/vjgpt/Face-and-Emotion-Recognition 

- Real time emotion recognition https://github.com/omar178/Emotion-recognition#p4 

- Real-time Facial Emotion Detection using deep learning https://github.com/atulapra/Emotion-detection

- Facial Emotion Recognition on FER2013 Dataset Using a Convolutional Neural Network https://github.com/gitshanks/fer2013 

- The world's simplest facial recognition api for Python and the command line https://github.com/ageitgey/face_recognition 

- libfaceid is a research framework for prototyping of face recognition solutions. It seamlessly integrates multiple detection, recognition and liveness models w/ speech synthesis and speech recognition. https://github.com/richmondu/libfaceid 

### Articles

- EmoPy: a machine learning toolkit for emotional expression https://www.thoughtworks.com/insights/blog/emopy-machine-learning-toolkit-emotional-expression

- Demonstration of Facial Emotion Recognition on Real Time Video Using CNN : Python & Keras https://appliedmachinelearning.blog/2018/11/28/demonstration-of-facial-emotion-recognition-on-real-time-video-using-cnn-python-keras/

- Real-Time Face Recognition: An End-To-End Project https://towardsdatascience.com/real-time-face-recognition-an-end-to-end-project-b738bb0f7348 

- OpenCV Face Recognition https://www.pyimagesearch.com/2018/09/24/opencv-face-recognition/ 

- Face Detection, Recognition and Emotion Detection in 8 lines of code! https://towardsdatascience.com/face-detection-recognition-and-emotion-detection-in-8-lines-of-code-b2ce32d4d5de 

- AI ‘Emotion Recognition’ Can’t Be Trusted https://www.theverge.com/2019/7/25/8929793/emotion-recognition-analysis-ai-machine-learning-facial-expression-review

- Introduction to Facial Emotion Recognition https://algorithmia.com/blog/introduction-to-emotion-recognition 

- How I developed a C.N.N. that recognizes emotions and broke into the Kaggle top 10 https://www.freecodecamp.org/news/facial-emotion-recognition-develop-a-c-n-n-and-break-into-kaggle-top-10-f618c024faa7/


