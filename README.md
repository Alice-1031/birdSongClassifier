Uses K-NN classifier and Random Forest classifier models to classify bird song audio files. Trained on a robust dataset of 4000+ audio files from Cornell lab 
with the limitation of only 10-20 samples per species. Thus I did some wrangling to only use the species with the most samples ending up with 25 species total. Both models have
72% total accuracy currently with much better accuracy for some species than others. More samples or a bigger model size will definitely improve results even with the current methods used.

To use please import your own audio files and run the chunks - 

import glob
from collections import Counter

audio_dir = '/Users/shreyajaiswal/Desktop/BirdSong/'

reaplce with your directory, the dataset I have cannot be shared without special permissions from Cornell.
