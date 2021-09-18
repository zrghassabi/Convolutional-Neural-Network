# Convolutional-Neural-Network

You can write codes in notebook of Googlecolab. (https://colab.research.google.com)

You can work on any dataset, for example go pytorch website, doc, torchvision, imagenet and use dataset  https://pytorch.org/vision/stable/datasets.html#imagenet   



 
 
 Example 1: Class Dataset and how to use Data Loder
 

   1_1) creating Dataset class ( it includes __init__(self), __len__(self), __get_item__(self, index), using _init_ you can download and read data (every thing that you can apply data, apply in this paper). In _len_, you return lenght of data.  using _get_item, you load big dataset on demand) to use in Dataloader . Detaloader will create mini-batches of Data, will shuffle data. Idx was adjusted on indices of mini-batches which in each iteration are distictive.

   1_2) Building Dataloader for test data and evaluation of model with test data
   
   1-3)Generalization of Training step ( A function that get Loss, Model, Optimizer and return train step or corresponding Loss, this function will be used in training loop


    
