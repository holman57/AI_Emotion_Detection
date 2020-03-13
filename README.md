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

### Dataset

- **Cohn-Kanade (CK and CK+)** database. 
**CK+** https://drive.google.com/open?id=1OmNPGrtj5jjoMTGIc9W7jtUdohY1Sz2L 
**CK** https://drive.google.com/open?id=14ovbvSV0-Wh1URxVFiT04dwshqbNdizw 
Datasets for training affect recognition and for perception studies. RGB Video http://www.consortium.ri.cmu.edu/ckagree/

- **FER+**
https://drive.google.com/open?id=12Bd-5cYEKMCZQpfOb6-NEk01YmvQxGkL 
new label annotations for the Emotion FER dataset. (Paper) https://arxiv.org/abs/1608.01041 (Images) https://github.com/microsoft/FERPlus

- **FER2013** 
https://drive.google.com/open?id=1GR6K-A_2Q9MoLwc9qnjhb4D5TqiZ_xnu  https://www.kaggle.com/ahmedmoorsy/facial-expression

- **RAVDESS**
The Ryerson Audio-Visual Database of Emotional Speech and Song https://zenodo.org/record/1188976 https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0196391 
RAVDESS Facial Landmark Tracking
https://zenodo.org/record/3255102

- **iBug**
These data are in accordance with the paper Deep Affect Prediction in-the-wild: Aff-Wild Database and Challenge, Deep Architectures, and Beyond.
https://ibug.doc.ic.ac.uk/resources
Challenges in Representation Learning: Facial Expression Recognition Challenge (Kaggle) (Images) https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

- **The INTERSPEECH 2020** 
Interspeech Computational Paralinguistics Challenge (ComParE) is an open Challenge dealing with states and traits of speakers as manifested in their speech signal’s properties. http://www.compare.openaudio.eu/data/

- **The SEWA Database**
A database of annotated audio and 2D visual dynamic behaviour (recorded by standard webcams used by the volunteers) has been collected within the SEWA project. https://db.sewaproject.eu/

- **AFEW**
Acted Facial Expressions In The Wild is a dynamic temporal facial expressions data corpus consisting of close to real world environment extracted from movies. https://cs.anu.edu.au/few/AFEW.html

- **DISFA**
Denver Intensity of Spontaneous Facial Action Database is a non-posed facial expression database for those who are interested in developing computer algorithms for automatic action unit detection and their intensities described by FACS. https://web.archive.org/web/20151024114056/http://www.engr.du.edu/mmahoor/DISFA.htm

- **The MUG Facial Expression Database**
The MUG database was created by the Multimedia Understanding Group. It was created to overcome some limitations of the other similar databases that preexisted at that time, such as high resolution, uniform lighting, many subjects and many takes per subject. https://mug.ee.auth.gr/fed/ 

- **RaFD**
The Radboud Faces Database is a set of pictures of 67 models (including Caucasian males and females, Caucasian children, both boys and girls, and Moroccan Dutch males) displaying 8 emotional expressions. http://www.socsci.ru.nl:8180/RaFD2/RaFD

- **MMI** 
Facial Expression Database https://mmifacedb.eu/

- **AffectNet**
Existing annotated databases of facial expressions in the wild are small and mostly cover discrete emotions (aka the categorical model). There are very limited annotated facial databases for affective computing in the continuous dimensional model (e.g., valence and arousal). http://mohammadmahoor.com/affectnet/

- **DISFA+**
The Extended Denver Intensity of Spontaneous Facial Action Database 
http://mohammadmahoor.com/disfa/

- **EMOTIC** 
Dataset http://sunai.uoc.edu/emotic/

- **Facial Recognition Databases**
https://www.kairos.com/blog/60-facial-recognition-databases 

- **CVonline** 
Image Databases http://homepages.inf.ed.ac.uk/rbf/CVonline/Imagedbase.htm 
