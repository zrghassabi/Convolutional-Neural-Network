# Convolutional-Neural-Network

How to download datasets? use Torchvision to download popular datasets
use https://pytorch.org/vision/stable/index.html to download datasets.

for example use https://pytorch.org/vision/stable/datasets.html#fashion-mnist

if you set train=true, you will download train folder
if you set train=false, you will download test folder

How to use models? use torchvision https://pytorch.org/vision/stable/models.html
if you set pretrained=True  , you will have weights of pretrained NN

using torchvison.transforms resize, change brightness, crop input images
https://pytorch.org/vision/stable/transforms.html


-You can write codes in notebook of Googlecolab. (https://colab.research.google.com)

-You can work on any dataset, for example go pytorch website, doc, torchvision, imagenet and use dataset  https://pytorch.org/vision/stable/datasets.html#mnist

and

torchvision.datasets.MNIST(root: str, train: bool = True, transform: Optional[Callable] = None, target_transform: Optional[Callable] = None, download: bool = False)

to download dataset and use torch.utils.data.Dataloder to load mini-batches on demand. In next examples we will write Class Dataset ( it includes __init__(self), __len__(self), __get_item__(self, index), using _init_ you can download and read data (every thing that you can apply data, apply in this paper). In _len_, you return lenght of data.  using _get_item, you load big dataset on demand) to use in Dataloader . Detaloader will create mini-batches of Data, will shuffle data. Idx was adjusted on indices of mini-batches which in each iteration are distictive. 

-Dataloader can be build for test data and evaluation of model with test data

-Use nn.Module and write Class of model which includes (__init__ and forward), so that you can creat covolutional layers including Convolution, maxpooling, relu and fully connected layers
   
 -use codes from  https://pytorch.org/tutorials/beginner/finetuning_torchvision_models_tutorial.html
 
-Generalization of Training step ( A function that get Loss, Model, Optimizer and return train step or corresponding Loss, this function will be used in training loop
   

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 


