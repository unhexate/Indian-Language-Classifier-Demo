# Indian Language Classifier Demo

## Description

A demo using tensorflow to identify spoken language. We use tensorflow's MelSpectrogram layer to convert the speech .wav files to spectrogram images, which are used as training data for a CNN model. The model achieves an accuracy of 95%.

## Dataset

The dataset used in this project, [IndicTTS by IIT Madras](https://www.iitm.ac.in/donlab/indictts/database), is a corpus of 13 Indian languages with 10,000+ spoken sentences recorded by both male and female speakers.
We only use 6 languages for this demo, namely Gujarati, Hindi, Kannada, Malayalam, Tamil, and Telegu. The actual dataset used for this project was over 34GB, so a sample of 100 random speech segments from each language has been provided.
