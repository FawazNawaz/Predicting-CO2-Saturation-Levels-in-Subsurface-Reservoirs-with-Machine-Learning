# Predicting-CO2-Saturation-Levels-in-Subsurface-Reservoirs-with-Machine-Learning
Predicting CO2 Saturation Levels in Subsurface Reservoirs with Machine Learning
Predicting CO2 Saturation Levels in Subsurface Reservoirs with Machine Learning
This script tackles the challenge of predicting CO2 saturation levels within underground reservoirs using supervised learning regression models.

Key Points:

Data: The dataset encompasses information on 2360 potential subsurface reservoirs, each described by a combination of 59 bedform architectures and 40 matrix-laminae pairings.
Training and Testing: The script utilizes data from 51 bedforms for training the models, while reserving data from 8 bedforms for testing their performance.
Feature Mix: The models can handle both numerical (3 features) and descriptive (5 features) data, offering flexibility in model design.
Interactive Exploration: The script provides user-friendly widgets that allow for customization of model parameters and visualization of results.
Evaluation Metrics: The script evaluates model performance using R-squared score, mean cross-validation score, and a visual comparison of predicted vs. actual CO2 saturation values for the test bedforms.
Target Variable: The model aims to predict the 'Saturation' value, which represents the CO2 storage capacity of a specific reservoir configuration.
Note: Due to confidentiality, the training data itself is not shared. However, a sample output file, "machineLearningOuput.pdf", is included in the repository to illustrate the script's functionalities.
