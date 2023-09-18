# Signal_Processing_and_Feature_Engineering_of_Respiratory_Disease

## Introduction
This project focuses on the classification of respiratory diseases using signal processing and feature engineering techniques. It leverages data augmentation, SMOTE (Synthetic Minority Over-sampling Technique), a Convolutional Neural Network (CNN) algorithm, and Mel-frequency cepstral coefficients (MFCC) features for improved disease detection. The goal is to perform binary classification for each respiratory disease and multi-classification.

### Project Overview
Respiratory diseases are a significant public health concern, and early detection is crucial for effective treatment. This project aims to classify respiratory diseases from audio signals using advanced machine learning techniques.

### Data Augmentation
Data augmentation is applied to increase the diversity of the training dataset. Augmentation techniques include:

- Random noise addition
- Time-stretching
- Pitch-shifting

### SMOTE for Class Imbalance
To address class imbalance in the dataset, SMOTE is used to oversample minority classes and balance the class distribution.

### Convolutional Neural Network (CNN)
A CNN architecture is employed for its ability to capture spatial features from MFCC representations of audio signals. 

### Mel-frequency Cepstral Coefficients (MFCC)
MFCC features are extracted from audio signals as they provide a compact representation that is highly effective for audio classification tasks.

## Dataset Used
ICBHI 2017 hosted a sci. challenge, and here is where the Respiratory Sound database was first created. The current version of this database, which includes private and public dataset of ICBHI, is made openly for study. It includes 920 audio samples of 126 patients, recording of 5.5 hours with 6898 breathing, of which 886 have wheezes, 1864 have crackles, and 506 have both.
Experts of respiratory biology annotated the cycles as having wheezes and crackles, or no accidental noises. These were made with various tools, and they ranged in length from 10 to 90 seconds. It also includes the location in the chest where these were made.
Each file name is composed of five components.:
1. Recording index
2. Patient number (101,102,...,226)
3. Chest location
a. Lateral right (Lr)
b. Lateral left (Ll)
c. Posterior right (Pr)
d. Trachea (Tc)
13
e. Anterior left (Al)
f. Anterior right(Ar)
g. Posterior left (Pl)
4. Recording equipment
a. WelchAllyn Meditron Master Elite Electronic Stethoscope (Meditron)
b. 3M Littmann 3200 Electronic Stethoscope (Litt3200)
c. 3M Littmann Classic II SE Stethoscope (LittC2SE)
d. AKG C417L Microphone (AKG C417L)
5. Acquisition
a. Simultaneous/multichannel (mc)
b. Sequential/single channel (sc)
These having 4 columns :
1. Presence/absence of wheezes (presence=1, absence=0)
2. Presence/absence of crackles (presence=1, absence=0)
3. Beginning of respiratory cycle(s)
4. End of respiratory cycle(s)
The abbreviations are used :
1. LRTI
2. COPD
3. URTI

## Results
The results of binary classification and multi-classification for each disease are reported, including accuracy, precision, recall, sensitivity, specificity and F1-score. Visualizations may include confusion matrices.
