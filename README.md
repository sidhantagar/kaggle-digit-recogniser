# kaggle-digit-recogniser
In this machine learning project our dataset which has been derived from the famous MNIST dataset consists of 784 data fields which contain pixel values from 0-255 inclusive and a target field "label".Thus in our data set, each image is a handwritten digit converted to greyscale image which is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total given as pixel values from 0-783. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. The taget field contains the digit in the handwritten image.

## This repository contains 4 folders: 

  1. The first one is a tutorial notebook explaining how PCA works and its effects on the dataset.
     You can visit "https://www.kaggle.com/sidagar/pca-explained-with-animated-visuals" to view the notebook.

  2. In this notebook I have implemented a KNN model over PCA.(Score obtained was 0.968). 
     You can visit "https://www.kaggle.com/sidagar/digit-recogniser-using-pca-and-knn" to view the notebook.
  
  3. In this notebok I have implemented a Neural network. (Score obtained was 0.975).
     You can visit "https://www.kaggle.com/sidagar/digit-recognizer-using-simple-neural-network" to view the notebook.
     
  4. In this notebok I have implemented a Convoluted Neural network. (Score obtained was 0.995).
     You can visit "https://www.kaggle.com/sidagar/digit-recognizer-using-a-cnn" to view the notebook.
    
    PS:There are interactive and dynamic plotly charts in these files which are not rendered on the github viewer and 
    therefore I have uploaded the whole notebook in HTML format separately for reference which comes with all the graphs.
    If you only want to see the notebook you can download and view the HTML version or visit the kaggle link to view it.
    
    If you however wish to run the code on your own, you can either:
    
    1. Download the ipynb format of the notebook along with the train and test sets and set the path of train test inside 
       the notebook and run it on your computer. Before running please make sure to install all the relevant libraries.
    
    2. Visit kaggle links provided and fork the pinned version of the notebook and then run the notebook.

**My Kaggle username is "sidagar" without quotes.**
