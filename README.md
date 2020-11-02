# Welcome to the respository that is associated with the manuscript titled: A Dual-Frequency Radar Retrieval of Snowfall Properties Using a Neural Network

(Under Review August 2020)

Authors: Randy J. Chase, Stephen W. Nesbitt and Greg M. McFarquhar
Corresponding author: Randy J. Chase (randyjc2@illinois.edu) 

Here we have the data used in the manuscript. Please email me if you have specific questions about units etc. 

1) DDA/GMM database of scattering properties: base_df_DDA.csv

  This is the combined dataset from the following papers: Leinonen & Moisseev, 2015; Leinonen & Szyrmer, 2015; Lu
et al., 2016; Kuo et al., 2016; Eriksson et al., 2018
  
2) Synthetic Data used to train and test the neural network: Unrimed_simulation_wholespecturm_train_V2.nc, Unrimed_simulation_wholespecturm_test_V2.nc

  This was the result of combineing the PSDs and DDA/GMM particles randomly to build the training and test dataset. 

3) Notebook for training the network using the synthetic database and Google Colab (tensorflow): Train_Neural_Network_Chase2020.ipynb

  This is the notebook used to train the neural network. 

4) Trained tensorflow neural network: NN_6by8.h5
  This is the hdf5 tensorflow model that resulted from the training. You will need this to run the retrieval. 
  
5) Scalers needed to apply the neural network: scaler_X_V2.pkl, scaler_y_V2.pkl
  These are the sklearn scalers used in training the neural network. You will need these to scale your data if you wish to run the retrieval. 
  
6) Example notebook of how to run the trained neural network on Ku- Ka- band observations. We showed this with the 3rd case in the paper: Run_Chase2021_NN.ipynb

7) APR data used to show how to run the neural network retrieval: Chase_2021_NN_APR03Dec2015.nc 

The data for the analysis on the observations are not provided here because of the size of the radar data. Please see the GHRC website (https://ghrc.nsstc.nasa.gov/home/) if you wish to download the radar and in-situ data or contact me. We can coordinate transfering the exact datafiles used. 

The GPM-DPR data are avail. here: http://dx.doi.org/10.5067/GPM/DPR/GPM/2A/05
