# Speech_Emotion_Recognition
# Deep Learning
![speech recogn](https://github.com/ShwetaDhore/Speech_Emotion_Recognition/assets/130909060/889d1079-40aa-424f-a085-b702b807d19a)

Follow this README text file to get the clear idea about the repository.

# TRAINING DATASET
#TESS - Toronto Emotional Speech Set.

# DATASET DESCRIPTIONS:
#TESS:
There are a set of 200 target words were spoken in the carrier phrase "Say the word _' by two actresses (aged 26 and 64 years) and recordings were made of the set portraying each of seven emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral). There are 2800 data points (audio files) in total.
The dataset is organised such that each of the two female actor and their emotions are contain within its own folder. And within that, all 200 target words audio file can be found. The format of the audio file is a WAV format.

# Feature Selection:
Feature selection aims to obtain a subset of a relevant features that are selected from the feature space and to facilitate subsequent analysis . The traditional feature selection methods are involved extracting features in time or frequency domain. E.g, Pitch, Energy, Power, Amplitude, FFT, Mel-Scale measurements like Mel-spectrum, Mel-frequency Cepstral Coefficients (MFCC), Spectogram, Linear prediction coefficients (LPC), n-gram, Constant Q Cepstral Coefficients (CQCC), etc.
The most used features of speech involve both time and frequency combined. These features will help in keeping track of both time and frequency variations rather than a limitation to only one domain. The Simulated and Induced data-set is used in the above approaches rather than the Natural data-set. Natural data involve several pre-processing steps like data cleaning(Noise reduction, sampling issue).etc.
# PROBLEM DEFINITION:
There are several traditional statistical algorithms for speech emotion recognition which are limited to an assumption of using the training and testing data from the same database (Cross-corpus problem). Also for feature selection process CNN makes all low to high-level feature extractions simpler and more efficient but can't deal well in numerous emotional classes and require a lot of data collection to train a model.
# MFCC:
They are derived from a type of cepstral representation of the audio clip (a nonlinear "spectrum-of-a-spectrum"). The difference between the cepstrum and the mel-frequency cepstrum, the frequency bands are equally spaced on the mel scale, which approximates the human auditory system's response more closely than the linearly-spaced frequency bands used in the normal cepstrum.
The steps to calculate the MFCC are as follows :
Take the Fourier transform of (a windowed) a signal.
Map the powers of the spectrum obtained above onto the mel scale, using triangular overlapping windows.
Take the logs of the powers at each of the mel frequencies.
Take the discrete cosine transform of the list of mel log powers.
The MFCCs are the amplitudes of the resulting spectrum.

<img width="367" alt="Screenshot 2024-06-25 191102" src="https://github.com/ShwetaDhore/Speech_Emotion_Recognition/assets/130909060/ec10967a-7a32-4f9d-ae05-34d8095d145d">

# Train Models

<img width="466" alt="Screenshot 2024-06-25 191241" src="https://github.com/ShwetaDhore/Speech_Emotion_Recognition/assets/130909060/b6a56e61-e97c-4e0e-b04b-3942ae6c3e70">

<img width="421" alt="Screenshot 2024-06-25 191137" src="https://github.com/ShwetaDhore/Speech_Emotion_Recognition/assets/130909060/9ea1e1a2-d30c-4a47-af54-ad5280164bae">


# Conclusion
Building the model was a challenging task as it involved lot of trail and error methods, tuning etc. The model is very well trained to distinguish between male and female voices and it distinguishes with 100% accuracy. The model was tuned to detect emotions with more than 70% accuracy. Accuracy can be increased by including more audio files for training.
