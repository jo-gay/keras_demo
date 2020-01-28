# Keras demonstration for Stockholm Machine Learning Club
This repo contains the code used for a demonstration of Keras for beginners.

If you want to follow along then you will need to complete the following setup steps to be able to run the code in the Jupyter notebook (there is a requirements.txt which gives my full setup, but I had a lot of trouble getting it to load into a new environment so I don't recommend it):

- First clone the repo and enter the root folder keras_demo
- Create a python 3.6 environment, and install the given package versions: <code>conda create -c anaconda -n keras_demo python=3.6 numpy=1.16 tensorflow=1.13 keras=2.2.4 matplotlib jupyter nb_conda pillow </code>

If you don't use conda then you need to install 
- tensorflow
- keras
- pillow
- matplotlib
- jupyter

The exact versions shouldn't matter, but depending on the combination of versions of keras, tensorflow and numpy, you may see various warnings in the notebook and / or in your shell. It should still work fine.

Then you will be able to run the jupyter notebook (type <code>jupyter notebook</code> to start the jupyter server (which will open a browser window), and open the file "Keras demo.ipynb".
