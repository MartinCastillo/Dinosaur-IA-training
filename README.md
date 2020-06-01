<<<<<<< HEAD
# DinoRuning-ml-game-training
A simple game similar to Google's dinosaur, programmed in Python, the plan for this project is to train a machine learning model that has to learn to play, with a genetic model<br>
=======
# Dinosaur-IA-training
A simple game similar to Google's dinosaur, programmed in Python, the plan for this project is to train a machine learning model that has to learn to play, with a genetic model
>>>>>>> 8ede232f240e9e64ac1df6bcfef61362bb8950fe

# Src
* | ```/main.py ```: Is the main file, it makes the learning process, using functions from ```/genetic_model.py ```.<br>
* | ```/model.h5 ```: Saved best keras model.<br>
* | ```/Game ```: Game class contains the game structure, ```Game.play(models)``` takes a lists of models to predict jumps in game and returns pairs of each    model and the score that it got .<br>
  * | -> ```/Agent/Agent.py ```: This Agent class represents dinosaurs, contains their coordinates, movments, bounding boxes, etc<br>
  * | -> ```/Obstacle/Obstacle.py```: class to save obstacles´s bounding boxes <br>
  * | -> ```/assets ```: Game sprites and backgrounds.<br>
* | ```/genetic_model.py ```: Contains functions to manage the population of the genetic model in ```/main.py ```, ```genetic_model.over_population()``` iterates over the nn models to corssover and mutate them.<br>

![img](https://github.com/MartinCastillo/Dinosaur_runing_ml_gym/blob/to_pygame/Captures/1.PNG)
