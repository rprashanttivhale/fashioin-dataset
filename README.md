# fashioin-dataset
Fashion Datasets using keras , we can train and test datasets to  improve the accuracy and decrease the loss.
# How to Download the Datasets
we can Download Fashion datasets  from keras datasets using load_data() and store it into the train and test variable
# Discription of Datasets 
1) 60,000 training examples.
2) 10,000 testing examples
3) 10 classes
  - T-shirt/top
  - Trouser/pants
  - Pullover shirt
  - Dress
  - Coat
  - Sandle
  - Shirt
  - Sneaker
  - Bag
  - Boot
4) 28×28 grayscale/single channel images
5) size of datasets is 

# as you can see your datasets shape is 60000,28,28 we need to add one diamention
using numpy expand function we can add one diamention, now we have 60000,28,28,1 shape train datasets
 # Lets create model or architecture 
 we can create model using Sequential() and add layer using add method .
  we can create convnet using BatchNormalization , Conv2D ,MaxPooling, Dropout  and Flatten
# next step to compile the model 
compile method have three attribute 
1)optimizer
2)loss
3)metrics
# Lets Train and Test the model using fit() method 
we can train and test model using fit method 
it will take time as per your hardware requirment 
if you have loss specification computer system i will suggest you to use google colabs it will provide high performance GPU free .

# How did i see accuracy and loss 
After the train the model output show acuracy and loss
as you can see the notebook acc:0.88 and loss :0.32
you can also import the performance to change the attribute.
 
