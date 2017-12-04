## Training a Deep Learning Language Model Using Keras and Tensorflow
A code pattern focusing on how to train a machine learning language model while using Keras and Tensorflow.

This code pattern will guide you through installing Keras and Tensorflow, downloading yelp data and training a language model using recurrent neural networks, or RNNs, to generate text.

info about keras, tensorflow and generating text

The original yelp data used in this code pattern can be found here: https://www.kaggle.com/c/yelp-recruiting/data as well as in this repository under data/. 

![](doc/source/images/Architecture.png)

## Flow

1. Locally, or on a server, download the yelp data.
2. Download and install Keras and Tensorflow.
3. Learn what you can do using Keras.
4. Train a language model to generate text.
5. Evaluate and learn how else this model can be applied.

## Included components

* [Jupyter Notebook](http://jupyter.org/): An open source web application that allows you to create and share documents that contain live code, equations, visualizations, and explanatory text.
* [Keras](https://keras.io/): The Python Deep Learning library.
* [Tensorflow](https://www.tensorflow.org/): An open-source software library for Machine Intelligence.

## Featured technologies

* [Cloud](https://www.ibm.com/developerworks/learn/cloud/): Accessing computer and information technology resources through the Internet.
* [Data Science](https://medium.com/ibm-data-science-experience/): Systems and scientific methods to analyze structured and unstructured data in order to extract knowledge and insights.
* [Python](https://www.python.org/): Python is a programming language that lets you work more quickly and integrate your systems more effectively.

# Watch the Video
TBD

# Steps

This pattern runs through the steps below. Check out the notebook for the code!

    1. Download yelp data.
    2. Download and install Keras and Tensorflow (and their dependencies).
    3. Start a jupyter notebook.
    4. Follow the notebook provided to run a language model to generate text.
    5. Learn where else this RNN model can be applied.

1. Download yelp data.

Go to the kaggle competition link here: https://www.kaggle.com/c/yelp-recruiting/data and download your data locally or on a server.

2. Download and install Keras and Tensorflow (and their dependencies).

First you must make sure you have the prerequisits:

    Have the python version you want and pip installed.
    Install numpy.
    Install Tensorflow. Go here to follow the directions if you are not on a MacOS: https://www.tensorflow.org/install/
    For Mac users, ```pip install tensorflow-gpu``` will install the gpu version, which is what I used on my server.
    For Keras, you can go to this link: https://keras.io/#getting-started-30-seconds-to-keras. 
    To install you can either sudo pip install or pip install keras. On the other hand, you can use git:
    ```git clone https://github.com/fchollet/keras.git```
    ```cd keras
    sudo python setup.py install```

    
3. Start a jupyter notebook.

       From here you can choose to work in terminal while using python or download jupyter notebook to follow along:
       ```pip install jupyter notebook```
       The notebook containing the code for this pattern is in the repository: 
       Once that is installed you can enter ```jupyter notebook``` in your terminal and a notebook should pop up in your browser.
       If a notebook was not created, go to the url given in your terminal.
   
4. Follow the notebook provided to run a language model to generate text.
5. Learn where else this RNN model can be applied.


## Sample output

Use a final _Analyze the results_ or _Conclusion_ step above, plus sample output to wrap up the code pattern for a developer running it and also for people that are only going to read the README. Sample output format will vary depending on the code pattern technology used.


# Links

* [Create Data Science Experience Notebooks](https://datascience.ibm.com/docs/content/analyze-data/creating-notebooks.html)
* [Bureau of Labor Statistics](https://www.bls.gov/cex/)
* [Food Environment Atlas](https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads/)

# Learn more

* **Data Analytics Code Patterns**: Enjoyed this Code Pattern? Check out our other [Data Analytics Code Patterns](https://developer.ibm.com/code/technologies/data-science/)
* **AI and Data Code Pattern Playlist**: Bookmark our [playlist](https://www.youtube.com/playlist?list=PLzUbsvIyrNfknNewObx5N7uGZ5FKH0Fde) with all of our Code Pattern videos
* **Data Science Experience**: Master the art of data science with IBM's [Data Science Experience](https://datascience.ibm.com/)
* **Spark on IBM Cloud**: Need a Spark cluster? Create up to 30 Spark executors on IBM Cloud with our [Spark service](https://console.bluemix.net/catalog/services/apache-spark)

# License
[Apache 2.0](LICENSE)