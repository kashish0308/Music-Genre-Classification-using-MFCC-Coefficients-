- MFCC coefficients extracted from 115 audio files (songs) and stored into CSV files. 

- The following groups of files contribute to the set of 115:
    * Files containing rendition of the Indian National Anthem
    * Files containing Marathi ‘Bhav Geet’ – sung by various artistes, male and female
    * Files containing Marathi Lavni songs – sung by various artistes, predominantly female
    * Hindi film songs sung by Asha Bhosale
    * Hindi film songs sung by Kishor Kumar
    * English songs by Michael Jackson
 
- These files are named ‘nn-MFCC.csv’, where ‘nn’ is a song number. The song details were not given.

- Python code segment used to create MFCC using the module librosa:
    * mfccs = librosa.feature.mfcc(y=segment, sr=44100, n_mfcc=20)

- The MFCC coefficients, 20 of them, have been created by using a sampling rate of 44100 Hz, with a default hop size of 512 samples. 
