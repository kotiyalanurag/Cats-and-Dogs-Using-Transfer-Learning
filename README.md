# ABOUT THE DATA  
The Cats vs Dogs is a standard computer vision dataset that is easily available on platforms like Kaggle. The dataset consists of 12,500 images of cats and 12,500 images of dogs. But while building our model we will only be looking at a miniscule subset of the actual dataset i.e. 210 images in training data and 120 images in the validation data and lastly 40 images in the testing data. For our task I have manually arranged the data in a folder structure following Train --> Cat | Dog, Validation --> Cat | Dog and Test --> Cat | Dog. The project has been developed using Google Colaboratory.  
  
![Cats vs Dogs](https://storage.googleapis.com/kaggle-competitions/kaggle/3362/media/woof_meow.jpg)  
  
# DEPENDANCIES  
If you want to work on this project using Colaboratory then you don't need to install anything as everything is preinstalled on Colab or can be pip installed there. However, if you plan to work on this using your local machine then you need to have numpy, matplotlib, tensorflow on your machine.  
To pip install the same use the following in the command prompt:  
```html  
pip install numpy  
```  
```html  
pip install matplotlib
```  
We have used the latest version of tensorflow here i.e. tensorflow2.3.0. For installation purpose you can refer [installing tensorflow2.0 for windows](https://www.tensorflow.org/install).  
As we using Keras on Tensorflow backend we don't need to install Keras additionally.  
# DOWNLOADING THE DATA  
The entire dataset is available on kaggle and can be downloaded using the download link i.e. [click here to download the Dogs vs Cats data.](https://www.kaggle.com/c/dogs-vs-cats/data)  
# SCOPE OF THIS PROJECT  
For me this project was a starting step in Transfer Learning models. By working on the practical aspects of this project I was able to solidify a lot of the theoritical concepts. I hope it helps you out too. You can clone this repository on your local machine using  
```html
git clone https://github.com/kotiyalanurag/Cats-and-Dogs-Using-Transfer-Learning.git
```
# LICENSE  
[Apache License 2.0](https://github.com/kotiyalanurag/Cats-and-Dogs-Using-Transfer-Learning/blob/main/LICENSE)
