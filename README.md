# Quantum Computing Tutorials

## December 2018

See the event indico pages for [Thursday 12/13](https://indico.fnal.gov/event/19301/) and 
[Tuesday 12/18](https://indico.fnal.gov/event/19302/).

Jupyter notebooks used for the tutorial will be here. You can run them several ways...


* Run locally on your laptop with the `lyonfnal/qc-python-ubuntu` Docker image available from Docker Cloud. See [instructions](https://github.com/lyon-fnal/dockerImages/blob/master/tutorial.md). This method is the most reliable and will run very fast if you have a descent laptop. You only incur the set up timne once. This method is **preferred** but it involves installing Docker on your laptop. 

* Run in `Binder` by clicking on this badge [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lyon-fnal/qc-tutorial-fnal/master). [Binder](https://mybinder.org) is an open-source and **free** cloud platform for running Jupyter Notebooks. This method is very easy as you don't need to install anything on your laptop. However,  `Binder` may take a very long tine to start as it has to install dependencies, will be slower than running locally, and the availability and stability of `Binder` are not guaranteed. 

* Run in Google Colab by clicking on this badge [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lyon-fnal/qc-tutorial-fnal/blob/master) and choose the notebook. See [here](https://colab.research.google.com/notebooks/welcome.ipynb) for more information on Google Colab. You will need to run a cell towards the top of the notebook to install the necessary packages (this will not be required if you are running in Docker or Binder). That will take awhile, and you'll have to do that every time you start the notebook, which is kind of annoying and you should not use this method if there are many of you accessing the notebook at once (e.g. in a tutorial session). Google Colab is like Jupyter, but not exactly the same, so things may look different. 

* Run locally on your laptop by installing lots of stuff into your OS (see `Dockerfiles` at [lyon-fnal/dockerImages](https://github.com/lyon-fnal/dockerImages) for ideas). This is the most difficult way to run, but could be the fastest. Though the Docker image will be very fast. 

## Viewing a notebook as a presentation

Many of the notebooks are actually RISE presentations (see [here](https://rise.readthedocs.io/) for more information on RISE). To view the notebook as a presentation, do the following...

* From Jupyter Lab (e.g. you are using the `lyonfnal/qc-python-ubuntu` Docker image): RISE does not work in Jupyter Lab, unfortunately, Fortunately, you can still run the notebook in "classic" mode where RISE will work. To do this, click on the painters palette icon on the left side of the screen. That will bring up the command palette. In the search box type `classic` and then at the top click on the link for `Launch Classic Notebook`. Then navigate to the notebook you want. Click on the little box on the tool bar, far right, that looks like a plot. 

* From Binder: You are already in the classic notebook mode. Navigate to the notebook you want. Click on the little box on the tool bar, far right, that looks like a plot.

* From Google Colab: RISE does not run in Colab. 

## Viewing the Notebooks read-only and non-interactive

| Notebook | Link | Slides |
|----|-----|-----|
| tutorial_20181213| [![nbviewer](https://img.shields.io/badge/view%20on-nbviewer-brightgreen.svg)](https://nbviewer.jupyter.org/github/lyon-fnal/qc-tutorial-fnal/blob/master/tutorial_20181213.ipynb) | 
[![slides](https://img.shields.io/badge/slides%20on-nbviewer-brightgreen.svg)](https://nbviewer.jupyter.org/format/slides/github/lyon-fnal/qc-tutorial-fnal/blob/master/tutorial_20181213.ipynb) | 
