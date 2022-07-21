# MusicGen
Credits - [How to Generate Music using a LSTM Neural Network in Keras](https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5) --> [Classical Piano Composer](https://github.com/Skuldur/Classical-Piano-Composer)

This project allows you to train a neural network to generate midi music files that make use of a single instrument

## Requirements
* Python 3.x
* Installing the following packages using pip:
	* Music21
	* Keras
	* Tensorflow
	* h5py
  
  ## Usage
  * Place midi files of your choice into the midi_songs directory, which is read from Google Drive
    * Note: I had chosen music of similar genres i.e Superhero/Sci-Fi music
  * Run the train.py file to train the NN
  
  ```
  python3 train.py
  ```
