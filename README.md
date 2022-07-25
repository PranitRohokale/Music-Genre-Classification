
# Music Genre Classification

- Aim is to create a machine learning model which classifies music samples into different genres.
- It aims to predict the genre by using an audio signal as its input.
- Automating the classification of music helps to make the selection of songs quick and less time-consuming.
- It can also be used to find valuable data such as finding out popular genres, trends, and artists very easily.

## 🌐 About Dataset?

- We shall be using the GTZAN music classification dataset, which consists of audio files of 30 seconds each with each audio track being in .wav format.
- The dataset contains 10 genres of music:
- Classical, Jazz, Country, Rock, Blues, Reggae, Metal, Disco, Hip-hop, Pop
- [GTZAN Dataset](http://marsyas.info/downloads/datasets.html)



### 🔗 Detail Project Documentation
* [Detail Documentation Here...](https://docs.google.com/document/d/1RNb-ffl4BGvS1t6MGBJwSh_7UfxYkpv4-DQsXd983G_k/edit?usp=sharing)

## ⚡Feature Extraction
- In order to help us extract the features from the audio files, we have used the LibROSA library
- Libros is a library designed for music and audio analysis and helps provides the building blocks necessary in order to create a music retrieval system.
- Libros helps to visualize the audio signals and perform feature extraction using different signal processing techniques.

-  **Signals :**
    - [x] A signal is a variation in a certain quantity over time.
    - [x] <img src="https://github.com/PranitRohokale/Music-Genre-Classification/blob/main/snapshots/signals.png"  width="600" height="300">

-  **The Fourier Transform  :**
    - [x] An audio signal is comprised of several single-frequency sound waves. When taking samples of the signal over time, we only capture the resulting amplitudes.
    - [x] It converts the signal from the time domain into the frequency domain. The result is called a spectrum.
    - [x] <img src="https://github.com/PranitRohokale/Music-Genre-Classification/blob/main/snapshots/fourier.png"  width="600" height="300">

-  **Zero-Crossing Rate :**
    - [x] The zero-crossing rate is the rate of sign-changes along with a signal, i.e., the rate at which the signal changes from positive to negative or back. 
    - [x] <img src="https://github.com/PranitRohokale/Music-Genre-Classification/blob/main/snapshots/zcr.png"  width="600" height="300">

-  **Spectral Centroid :**
    - [x] A signal is a variation in a certain quantity over time.
    - [x] <img src="https://github.com/PranitRohokale/Music-Genre-Classification/blob/main/snapshots/spectral_rolloff.png"  width="600" height="300">
-  **Signals :**
    - [x] A signal is a variation in a certain quantity over time.
    - [x]


## 📱 Screenshots
