# 3D-CNN
These are projects of 3D CNN training and prediction on 3D images like CT Scan or Medical Images, Deep Fields.
Running 3D Convolutional Neural Networks requires a very high-performance GPU and RAM. 
I have resized my train and test images into [150,150,32] from [512,512,42] to run in Google Colab or my PC.
Higher resolution causes a dead kernel and a crash. 
I have used Adam, AdamW, and AdaMAX optimizers, but only got close Accuracy values for the Adam optimizer.
Also, I could not use deeper CNN layers due to computational resource limitations.
The training resulted in a bias towards predicting Class-1 as Viral Pneumonia. 
There is a better scope of development.
Also, I did not have sufficient training data. I have used only 200 samples, which is really very low.
But, resources for learning 3D CNN are also very limited. 
But, at least this project depicts my future research scope to be an expert in 3D CNN model prediction.
