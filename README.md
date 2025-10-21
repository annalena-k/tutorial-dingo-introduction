# Tutorial: Introduction to DINGO

This tutorial provides a first introduction on how to use the [DINGO package](https://github.com/dingo-gw/dingo) for analyzing gravitational wave data using neural posterior estimation.
It illustrates at a 2D toy example how to train a DINGO model from scratch in a simplified setting. Furthermore, the tutorial shows how to download and use an already trained model to obtain posterior samples for GW150914. 
With this tutorial, We hope to help people get started with DINGO easily.

## Getting started
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/annalena-k/tutorial-dingo-introduction/blob/main/DINGO_Tutorial.ipynb)

To get started quickly, run the tutorial in Google Colab by clicking the button above. 

To run it locally (which may be faster), ensure that you create and activate a Python environment with the `dingo-gw` package. 

With `pip`, this can be done with
```
python3 -m venv dingo-venv
source dingo-venv/bin/activate
pip install dingo-gw jupyterlab
```

If using `conda`, this can be done with
```
conda create -c conda-forge -n venv-dingo dingo-gw jupyterlab
conda activate venv-dingo
```

You can start the jupyter server by executing the command `jupyter lab` in the folder containing the notebook which should open a new browser window. Finally, you can click on the jupyter notebook `DINGO_Tutorial.ipynb` and start with the tutorial!
(Since you have already installed `dingo-gw`, you do not have to execute the notebook cells containing `!pip install ...` commands.)

If you are looking for a more general introduction to posterior estimation of gravitational wave data without DINGO, please check out the tutorial ["GW Parameter Inference with Machine Learning"](https://github.com/stephengreen/gw-school-corfu-2023).

### Updates
* (03.06.2025) Updated to `dingo=0.8.3`; additional minor changes.
* (30.01.2025) Tutorial was updated to be compatible with `dingo` version 0.7.0
