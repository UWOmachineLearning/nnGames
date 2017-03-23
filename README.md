# nnGames
Neural networks playing video games. For this, we will use the openAI gym, which provides a nice and easy to use python API to play video games. Currently, we are implementing the model described in [this paper](http://www.nature.com/nature/journal/v518/n7540/full/nature14236.html) from Deepmind, but we intend to try various trianing paradigm and model architectures. Deepmind algorithm finds the optimal solution in about 600 training steps, so that's a nice objective to aim for. Once good results are achieved, we will attempt training the model on more complex games.

This readme act as a progress report and contains dependencies of packages to install in order to successfully play with the model.

## Progress Summary
So far, we have :
  + Choose the game breakout from the Atari environment
  + Built the breakout game environment in python and understood how to interact with it
  + Built the model architecture
  
## Near Future Objectives
  + Convert 3d image into 2d efficiently (removing color dimension)
  + Implement a basic training paradigm
  + Implement the Q-learning paradigm
  
## Dependencies
To run the model successfully, you will need to install ;
  + [Tensorflow](https://www.tensorflow.org/install/) 
  + [cmake](https://cmake.org/install/)
  + swig (for Mac and Linux users) : 
      `brew install swig` OR `sudo apt-get install swig` 
  + [Open AI gym](https://gym.openai.com/docs) 
  

