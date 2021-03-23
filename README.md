# Spectrograms


Here is a set of programs for making spectrograms out of audio files and making audio files out of spectrograms. 

This is still very much a work in progress. Important points will be the challenge of image resizing and phase reconstruction including the Griffin-Lim algorithm.



- write spectrogram: .wav to .jpg 
  + STFT parameters:
    * window function
    * overlap
    * block size
    * fft size
  + image parameters
    * width and height
    * orientation
    * color, white, black
- read spectrogram: .jpg to .wav
