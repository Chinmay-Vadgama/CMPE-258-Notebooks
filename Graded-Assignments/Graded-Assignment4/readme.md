a) CNN basics : use KERAS and from scratch (not using existing architecture shipped models) write basic LeNet (mnist) and VGG-16 model (cifar100)  and RESNET (only 8 layers - not 52) architectures - run on gpu - train and report all the stats (see some pointers in slides)

b) CNN basics : use pytorch and from scratch (not using existing architecture shipped models)  write basic LeNet (mnist) and VGG-16 model (cifar100) and and RESNET (only 8 layers - not 52)  architectures - run on gpu  (use .cuda instruction) - train and report all the stats

c) transfer learning with CNN (either keras or fastai or pytorch - use your favorite)  : Kaggle competion : https://www.kaggle.com/c/dog-breed-identification/overview (Links to an external site.)

https://medium.com/nanonets/how-to-easily-build-a-dog-breed-image-classification-model-2fd214419cde (Links to an external site.)

https://towardsdatascience.com/dog-breed-prediction-using-cnns-and-transfer-learning-22d8ed0b16c5 (Links to an external site.)


 create a dog breeds classifier with > 83% validation accuracy (use all techniques - data =augmentation and transfer learning etc.,.) Eg:

https://github.com/fchollet/deep-learning-with-python-notebooks/blob/master/5.3-using-a-pretrained-convnet.ipynb (Links to an external site.)

for all :

 

properly visualize the results, model metrics, samples  etc.,. use tensorboard primitives for showing training progress. 

Visualize what the network for various ways (input sample dog image,random image gradient ascent,  heatmap, etc.,.)  has learnt using various techniques  (see colab and chpater on cnn in prescribed textbook)

Sample code : https://github.com/fchollet/deep-learning-with-python-notebooks/blob/master/5.4-visualizing-what-convnets-learn.ipynb

Try out various hyper parameters. provide detailed comments in colab with various experiments. 

Please implement from scratch and not copy paste.

 

 

Total models to submit : 7 colabs

 

3 keras resnet/vgg/lenet

3 pytorch resnet/vgg/lenet

1 transfer learning 
