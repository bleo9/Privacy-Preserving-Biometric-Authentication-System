# Privacy-Preserving-Biometric-Authentication-System (PPBAS)
# Prototype made in collaboration with Srishail Maskey. (BioSys Engineering) 


2-factor authentication system utilising both extracted facial and vocal data for the verification of users. 

This security system provides extra safety measures by ensuring that the raw data of users are not accessible, using both the **Siamese Neural Network** and **Gaussian Mixture Model** to process and authenticate raw facial and vocal data. TensorFlow and OpenCV incorporated for real-time face detection and recognition. 

Incorporates basic UI that includes the features to register, delete and check the list of users. 
Updated UI that requires authorisation to access features. (Implemented for dev-only capabilities)

Haar classifier (Haar cascade) used for face detection. 
Facial data are extracted and serialised into a vector of 128 dimensions using FaceNet model. 
Utilises Siamese Neural Network to compare registered and input facial data. 

MFCC features are extracted from concatenated voice recordings, stored and compared using GMM model. 

Weight file can be downloaded via https://drive.google.com/drive/folders/1VCm5TXmzKQ4xo0RD8bBzJaGDQz2ImgBz?usp=sharing.
