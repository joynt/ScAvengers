# ScAvengers

This repository contains the code we developed for the Scavenge project.
The files are organized as follow:
- data_extraction.ipynb --> in this notebook, we loaded raw data and perform some
                            statistical evaluations on them. Then, we organizes the
                            user according to some metrics discussed in the paper. 
                            Finally, we saved the processed data for further elaborations.
                            
- classification.ipynb --> in this notebook, we perform users classification.

- train.ipynb --> in this notebook, we exploited methods from Network Science theory
                  to clusterize users according to their mobility pattern correlations.
                  Also, we developed an LSTM model and we trained it to predict the next
                  MCS given a sequence of 50 MCS of the previous timesteps.
                  
- Results.ipynb --> in this notebook, we calculated the NRMSE and the error vector to evaluate
                    our models.
