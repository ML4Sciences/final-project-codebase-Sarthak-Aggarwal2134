# Using Convulational AutoEncoders to Predict the Effect of Mutation on Protein Stability.
### Team:
1. Sarthak Aggarwal
2. Aum Khatlawala

## Progress(12th April, 2023):
1. We extracted the data from the Pdb database.
2. One hot encoded the data so that it can be fed to the model.
   1. The one hot encoding considers 12 elements, 7 possible degrees, 5 possible hydrogen, 7 possible implicit valence.
      1. By degree, we mean the number of bonds that a particular atom has.
      2. By implicit valence, we mean the number of bonds that a particular atom can have.
3. Formed a adjacency matrix for each protein.
4. Finally, the datapoint contains:
   1. Number of atoms(both wild and mutated)
   2. Positions of atoms(both wild and mutated)
   3. Adjacency matrix(both wild and mutated)
   4. One hot encoded data(both wild and mutated)
   5. Change in stability

