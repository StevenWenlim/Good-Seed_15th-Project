# Good-Seed_15th-Project
The supermarket chain Good Seed would like to explore whether Data Science can help them adhere to alcohol laws by making sure they do not sell alcohol to people underage. I am asked to conduct that evaluation and here are some guidelines:
  - The shops are equipped with cameras in the checkout area which are triggered when a person is buying alcohol
  - Computer vision methods can be used to determine age of a person from a photo
  - The task then is to build and evaluate a model for verifying people's age

In this project, I trained a model to recognize the age of a person from photos. The model used was ResNet50, with 'relu' activation to transform negative values into 0, and an additional final layer with one neuron to produce a single output obtained through regression. The chosen loss function was 'mse' and the metric used was 'mae'. I did not use any type of augmentation when defining the training and testing sets. The lowest obtained MAE value was 1.6954.
