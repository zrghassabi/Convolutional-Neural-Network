# Convolutional-Neural-Network

 
 
 Example 1: Class Dataset and how to use Data Loder
 
 

   1-1) Generalization of Training step ( A function that get Loss, Model, Optimizer and return train step or corresponding Loss, this function will be used in training loop
   
   1_2) creating Dataset class ( it includes __init__(self), __len__(self), __get_item__(self, index), using _get_item, you load big dataset on demand) to use in Dataloader . Detaloader will create mini-batches of Data, will shuffle data. 

   1_3) Building Dataloader for test data and evaluation of model with test data


    
