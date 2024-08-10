# Piano Music Generation using GRU
Generating music using a neural network has always been a fascinating task.
This repository showcases one such neural network which  is able to produce somewhat nice results.

## Model Architecture
The model leverages the GRU architecture.
For indepth analysis do checkout the [training notebook](./MusicGen.ipynb)

![architecture](./results/version_0.png)

## Training
The model was trained on the midi music of [Frédéric Chopin
](https://en.wikipedia.org/wiki/Fr%C3%A9d%C3%A9ric_Chopin) from the [Classical Music MIDI](https://www.kaggle.com/datasets/soumikrakshit/classical-music-midi?select=albeniz)
available on Kaggle. It contains 48 music pieces.

The model was trained for 46 epochs.

## Results
These are the training and validation loss curves respectively.

Training_loss
![train loss](results/train_loss.svg)

Validation_loss
![validation loss](results/val_loss.svg)


## Predictions

To generate your own pieces I would suggest you to open the [prediction.ipynb](prediction.ipynb) in Google Colab and run it there.

*You can git clone the repository there.*

Here are some of the generated music pieces.

* Prediction 1
![Sheet Music](./results/melody-0.png)
<audio controls>
  <source src="./results/test-0.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

* Prediction 2
![Sheet Music](./results/melody-1.png)
<audio controls>
  <source src="./results/test-1.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

* Prediction 3
![Sheet Music](./results/melody-2.png)
<audio controls>
  <source src="./results/test-2.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

* Prediction 4
![Sheet Music](./results/melody-3.png)
<audio controls>
  <source src="./results/test-3.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

* Prediction 5
![Sheet Music](./results/melody-4.png)
<audio controls>
  <source src="./results/test-4.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>