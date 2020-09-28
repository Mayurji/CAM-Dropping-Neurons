# **Units-In-Deep-Neural-Networks**
When top neurons of trained neural network of a specific class is dropped gradually, the trained model loses it ability to classify the label correctly.
Interestingly, the model starts focusing on other regions of an Image with probability getting distributed among other classes.

    **For intutitive understanding, Consider you have strong memories of particular events in your life like going to college or the time you met with an 
    accident and it is stored as neuron among  billions of neurons in your brain and now you vaguely remember those events because your neurons have vanished                      
    slowly as the years have passed.**

    Similarly now compare those with neurons of your model which has learnt to identify a scene but as i drop some of those neurons, it starts loses ability to    
    understand its role and vaguely predicts with available neurons. Interest Concepts, Don't you think?


# **Installation**
```python
pip install -r requirements.txt
```

# **How to run IPywidget**
![Watch the video](Media/DNN_Units_Dropped.mkv)

# **Effects Of Units When Dropped**
![Units Dropped](Media/animation.gif)

# **Note**
Top Most Neuron refers to neurons with large weight value and Bottom Most Neuron refers to weights with least value.


# **Prerequisite**

* ipywidgets==7.5.1
* opencv_python==4.2.0.34
* numpy==1.19.1
* torchvision==0.7.0
* matplotlib==3.3.1
* torch==1.6.0
* ipython==7.18.1
* Pillow==7.2.0

# **References**
* [Class Activation Map](http://cnnlocalization.csail.mit.edu/Zhou_Learning_Deep_Features_CVPR_2016_paper.pdf)
* [Role of Individual Units in Deep Neural Networks](https://arxiv.org/abs/2009.05041)
* [Annotated Paper - Role of Individual Units in Deep Neural Networks](https://github.com/Mayurji/Deep-Learning-Papers/tree/master/Investigate%20DNN)
