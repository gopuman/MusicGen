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
  * Place midi files of your choice into the midi_songs directory

  * Run the train.py file to train the NN
  
  ```
  python3 train.py
  ```
  
  * After successfully running train.py, update the path_to_weights_file variable in `gen.py` and run:
  
  ```
  python3 gen.py
  ```
  
  * Find the results in - `test_output.mid`
  
  ## Results
  * I had chosen music of similar genres i.e Superhero/Sci-Fi music
  * Check it out -> [BatAI_unmixed](https://soundcloud.com/gopal-nambiar/batai_unmixed?in=gopal-nambiar/sets/the-bat)
