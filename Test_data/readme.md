MFCC coefficients extracted from 115 audio files (songs) and stored into CSV files. 
Songs are form these Categories:
  - National Anthem of India
  - Asha Bhosale
  - Kishore Kumar
  - Michael Jackson
  - Lavani 
  - Bhav geet
These files are named ‘nn-MFCC.csv’, where ‘nn’ is a song number. The song details were not given.

Python code segment used to create MFCC using the module librosa:
# Compute MFCC coefficients for the segment
mfccs = librosa.feature.mfcc(y=segment, sr=44100, n_mfcc=20)

The MFCC coefficients, 20 of them, have been created by using a sampling rate of 44100 Hz, with a default
hop size of 512 samples. 
