This is a classification project that classifies whether the give image is a cat or a dog. The dataset is taken from the Kaggle.
Dataset composition: 1. training set = 20000
                     2. validation set = 3000
                     3. validation set = 2000
                     
I've used different approches to train the model. A simple convolution network with 3 layers and 1 fully connected layer which gives accuracy of 89.97% on validation set and 88.70% on test set. Then i trained another model with pre-trained architecture (MobileNet) which gives accuracy of 97.76 on validation set and 97.95% on test set.


#GRAPH

Convolutional Network vs Pre-trained Architecture (MobileNet)


COVNET loss:

![covnet_loss](https://user-images.githubusercontent.com/60252526/110667695-5f062500-817f-11eb-9cca-8f38b18cde66.png)

MobileNet loss:
![mobilenet_loss](https://user-images.githubusercontent.com/60252526/110667734-688f8d00-817f-11eb-90bf-3b22d7297200.png)




