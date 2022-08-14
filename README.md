# Medical Image Classification
Medical Image Classification Project (X-rays and MRI's)

Hello we are [Nikolas](https://github.com/nikolis7) and [Marios](https://github.com/votaldo)
This is a project developed within the course `Deep Learning` for our **[MSc Program in Data Science](http://msc-data-science.iit.demokritos.gr)**. 

The main resources we will use to develop our Medical Image Classification project are:
* [Google Colab](https://colab.research.google.com/?utm_source=scs-index]) and [Jupyter Notebook](https://jupyter.org/) via Anaconda (to deplot code and report our progress)
* [TensorFlow](https://www.tensorflow.org/resources/learn-ml?gclid=Cj0KCQjwqPGUBhDwARIsANNwjV7LnBk3geGnJ7dztoqsaVvw53xXhYAFtLdW47irptwfgUJZrakvo0EaAvxfEALw_wcB) (for our Neural Networks)
* [Pytorch](https://pytorch.org/)(for our Neural Networks)
* [Kaggle](https://www.kaggle.com/datasets) (for our datasets)

Our main goals for this project are:

#### Pneumonia Classification via Xray's  
The pipeline we used to solve the problem is as follows: 
* Successfully preprocess the images
  * Import them   
  * Rescale the images
  * Normalise 
  * Perform data augmentation 
* Apply different CNN architectures 
* Use deep neural network model using transfer learning (ResNet151 & DenseNet 161) 
* Analyze the models results 
* Predict on test set 
* Compare the results 

The data set is available at this [link](https://drive.google.com/drive/folders/1yZoXee6uN7cLmSfh5pDMJtecUiwqig7I?usp=sharing)

#### Brain Segmentation via MRI's
The pipeline we used to solve the problem is as follows: 
* Successfully preprocess the images and masks 
  * Import them   
  * Rescale the images
  * Normalise 
* Use Unet model to solve the problem 
* Predict on test set 
* Visualize the results 

The data set is available at this [link](https://drive.google.com/drive/folders/1tpQSPfnElON-4IppJS0upQVs9lIrgQ4z?usp=sharing)
