[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/_GqhAiVb)
# Using Convolutional Auto Encoders to Predict the Effect of Mutation on Protein Stability.
### Team:
1. Sarthak Aggarwal
2. Aum Khatlawala

## Progess (26th April, 2023):
1. Completed the coding part of the project by implementing the CAE architecture (gives latent space representation for a given input, input size: 50x30 and output size: 8x30) and the FCNN architecture (input size: 8x30 and output: change in stability).
2. Got the following results: \
PCC on the unseen test set: 0.52 \
RMSE on the unseen test set: 1.20 
3. Comparison with the baseline models: \
3.1. ProSGNN - \
PCC on the unseen test set: 0.56 \
RMSE on the unseen test: 1.20  \
3.2. ThermoNet - \
PCC on the unseen test set: 0.47 \
RMSE on the unseen test set: 1.40
