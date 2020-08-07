# Welcome to the respository that is associated with the manuscript titled: A Dual-Frequency Radar Retrieval of Snowfall Properties Using a Neural Network

(Under Review August 2020)

Authors: Randy J. Chase, Stephen W. Nesbitt1 and Greg M. McFarquhar2
Corresponding author: Randy J. Chase (randyjc2@illinois.edu) 

Here we have the data used in the manuscript. Please email me if you have specific questions about units etc. 

1) DDA/GMM database of scattering properties: base_df_DDA.csv

  This is the combined dataset from the following papers: Leinonen & Moisseev, 2015; Leinonen & Szyrmer, 2015; Lu
et al., 2016; Kuo et al., 2016; Eriksson et al., 2018
  
2) Synthetic Data used to train and test the neural network: Unrimed_simulation_wholespecturm_train_V2.nc, Unrimed_simulation_wholespecturm_test_V2.nc

  This was the result of combineing the PSDs and DDA/GMM particles randomly to build the training and test dataset. 

3) Notebook for training the network using the synthetic database and Google Colab (tensorflow): Train_Neural_Network_Chase2020.ipynb

  This is the notebook used to train the neural network. 


The data for the analysis on the observations are not provided here because of the size of the radar data. Please see the GHRC website (https://ghrc.nsstc.nasa.gov/home/) if you wish to download the radar and in-situ data or contact me. We can coordinate transfering the exact datafiles used. 

The GPM-DPR data are avail. here: http://dx.doi.org/10.5067/GPM/DPR/GPM/2A/05
