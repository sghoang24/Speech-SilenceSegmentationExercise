# Speech-SilenceSegmentationExercise
## Exercise about segment signal into speech and silence region

In this exercise, I use logistic regression to identification speech and silence in an audio signal (.wav file).

I used 2 folder of signal which is 'TinHieuHuanLuyen' for training model and 'TinHieuKiemThu' for testing model.
In each folder, it include .wav file and .lab file:
- .wav file is audio file
- .lab file is the label of speech and silence region in signal

To segment speech and silence of signal, I used STE (Short-Time Energy) feature to work in this exercise.

I choosed Softmax Regression to classify speech and silence into 2 classes based on STE feature
