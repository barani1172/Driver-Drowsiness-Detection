# A study of machine learning-based driver drowsiness detection systems
 
  
Dataset Description   

The Complete System consists of 2 datasets:  
    i)   Dataset for Eye Open/Close state. The source of the dataset is https://www.kaggle.com/datasets/serenaraju/yawn-eye-dataset-new which contains 615 Open and Closed Eye state Images.  
    ii)  The Second dataset used is same as first one which contains about 600 images of Yawn/Not Yawning Driver images taken from Appropriate angle.  
    
    
# Model Training and Results 
 Two CNN models is trained on each of the dataset .Custom Built CNN model is used instead of pretrained and got accuracy of 97% for Eye State Classification Model and    92% for Yawn Detection Model.The Architecture used is a very simple one with 3-4 Conv2D layers followed by Pooling layer after every Conv2D layer and also one Dropout layer.
