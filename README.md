# Convolutional Network Tutorials (AMMI 2024)

These are the tutorials for the Convolutional Neural Networks class of the African Master's in Machine Intelligence given by Laurens van der Maaten.

The tutorials are iPython Notebooks in which you have to implements missing parts of the code yourself, run small experiments, and answer questions about the results of your experiments. The notebooks should be self-contained.

## Run notebooks on Google Cloud via colab

You can run the notebooks on Google Cloud via colab. The advantage of this approach is that your experiments will run on Google's servers, which are likely faster than your own laptop. You will need a stable wifi connection to use colab. The following links take you to the colab notebooks:

* [Tutorial 1a: Logistic Regression](https://colab.research.google.com/github/lvdmaaten/convnet_tutorials/blob/master/1a_logistic_regression.ipynb)
* [Tutorial 1b: Softmax Function](https://colab.research.google.com/github/lvdmaaten/convnet_tutorials/blob/master/1b_softmax_function.ipynb)
* [Tutorial 1c: Convolution](https://colab.research.google.com/github/lvdmaaten/convnet_tutorials/blob/master/1c_convolution.ipynb)
* [Tutorial 2a: Convolutional Neural Network (CNN)](https://colab.research.google.com/github/lvdmaaten/convnet_tutorials/blob/master/2a_convolutional_neural_network.ipynb)
* [Tutorial 2b: Batch Normalization](https://colab.research.google.com/github/lvdmaaten/convnet_tutorials/blob/master/2b_batch_normalization.ipynb)
* [Tutorial 3: Residual Neural Network (ResNet)](https://colab.research.google.com/github/lvdmaaten/convnet_tutorials/blob/master/3_residual_neural_network.ipynb)

## Run notebooks locally using Jupyter

You can also run the tutorial notebooks locally on your laptop. This way, you do not need an internet connection while you are working on most parts of the tutorial.

Running notebooks locally is done via [Jupyter](https://jupyter.org/). If you do not have Jupyter installed yet, you first we need to create a Conda environment (see [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) for details). To do so, `git clone` this repository and run the following commands in your Terminal from the `convnet_tutorials` directory: 

You can install all packages from conda environment as follows:

```
conda env create -f environment.yaml

conda activate convnet_tutorials
```

You can run `conda env list` to confirm the `convnet_tutorials` environment is activated.

Next, start Jupyter Notebook by going into the `convnet_tutorials` directory in your Terminal and running `jupyter notebook`. This will open a browser window with the Jupyter notebook interface. In this interface, you can navigate to the correct folder and open the tutorial notebooks (with the `.ipynb` extension) to run them.
