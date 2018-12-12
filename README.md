# Quantum Computing Tutorials

## December 2018

See the event indico pages for [Thursday 12/13](https://indico.fnal.gov/event/19301/) and 
[Tuesday 12/18](https://indico.fnal.gov/event/19302/).

Jupyter notebooks used for the tutorial will be here. You can run them several ways...


* Run locally on your laptop with the `lyonfnal/qc-python-ubuntu` Docker image available from Docker Cloud. See [instructions](https://github.com/lyon-fnal/dockerImages/blob/master/tutorial.md). This method is the most reliable and will run very fast if you have a descent laptop.

* Run in `Binder` by clicking on this badge [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lyon-fnal/qc-tutorial-fnal/master). [Binder](https://mybinder.org) is an open-source and **free** cloud platform for running Jupyter Notebooks. This method is very easy as you don't need to install anything on your laptop. However,  `Binder` will be slower than running locally and the availability and stability of `Binder` are not guaranteed. 

* Run in Google Colab by clicking on this badge [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lyon-fnal/qc-tutorial-fnal/blob/master) and choose the notebook. See [here](https://colab.research.google.com/notebooks/welcome.ipynb) for more information on Google Colab. You will need to run a cell at the top of the notebook to install the necessary packages (this will not be required if you are running in Docker or Binder). You'll have to do that every time you start the notebook, which is kind of annoying and you should not use this method if there are many of you accessing the notebook at once (e.g. in a tutorial session). Google Colab is like Jupyter, but not exactly the same, so things may look different. 

* Run locally on your laptop by installing lots of stuff into your OS (see `Dockerfiles` at [lyon-fnal/dockerImages](https://github.com/lyon-fnal/dockerImages) for ideas). This is the most difficult way to run, but could be the fastest. Though the Docker image will be very fast. 