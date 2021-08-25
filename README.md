# GCN_Cancer
This is a code evolution from this [forked repo](https://github.com/RicardoRamirez2020/GCN_Cancer) owned by Ricardo Ramirez. The code is supplied with [Classification of Cancer Types Using Graph Convolutional Neural Networks](https://www.frontiersin.org/articles/10.3389/fphy.2020.00203/full) paper, where Dr. Ramirez is the main author.
The instructions to run all the codes are available in MD_thesis.pdf under the "work done/final code" subsections.

### Features added
* Ability to create the GCNN in any of the four different gene intertactions.
* Confusion matrix is generated using all the input data after the GCNN creation, also CSV files are created to work with the data.
* A coarse post-modelling analysis code is created to extract the final results. It gives the results in Matplotlib plots and in CSV. 
* OnlyGCNN.py creates only the GCNN and generates it's confusion matrix. This file is ready to being modified to use the original code, other section is ready to work as the original code, but with the train and the validation/test data selected at random, and to divide the data in 3 blocks to use the common technique that divides the data in: 75% to train, 15% to validation and 15% to test. With this last one, the GCNN is really tested under unseen data.
