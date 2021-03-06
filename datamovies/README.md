# datamovies: Introduction
This package includes a couple of demo codes for sonifying and animating data, written by [Ben Holtzman](https://www.ldeo.columbia.edu/~benh/) and others.

The codes in this repository are in the form of python scripts, modules and Jupyter Notebooks. 
The easiest way to install Jupyter Notebook is by installing Anaconda. Click [here](https://www.anaconda.com/download/) to download Anaconda. However, there is a new and much improved interface called Jupyter Lab, [here](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) that we highly recommend. 

Once downloaded, run the Jupyter Notebook by typing in a terminal window: (the Mac Terminal, or Command Prompt for Windows):

`jupyter notebook`
or
`jupyter lab`

## Required Python packages for this demo
- [**numpy**        ](https://anaconda.org/anaconda/numpy)
- [**scipy**        ](https://anaconda.org/anaconda/scipy)
- [**matplotlib**   ](https://anaconda.org/conda-forge/matplotlib)
- [**librosa**      ](https://anaconda.org/conda-forge/librosa)
- [**resampy**      ](https://anaconda.org/conda-forge/resampy)

The easiest way to download these packages is using Anaconda (see above). Follow the link for each package name above and copy-paste the corresponding command into a terminal window. For example, to install **numpy** type this into the Mac Terminal:

`conda install -c anaconda numpy`

To make sure the packages were successfully installed, type:

`conda list`

## Clone repository
To access the codes from your machine, open the Mac Terminal and type:

`git clone https://github.com/benholtzman/datamovies`

Alternatively, click *"Clone or download"* at the top right corner of this page and *"Download ZIP"*.

## [1_notebooks](https://github.com/benholtzman/datamovies/1_notebooks): where the magic happens!
This directory contains the demo "notebooks" for sonifying data.

- [**NB00_make_simple_sounds.ipynb**](https://github.com/benholtzman/datamovies/1_notebooks/NB00_make_simple_sounds.ipynb) : Demonstrates sonification of time-varying (sinusoidal) signals
- [**NB01_DirectSonification.ipynb**](https://github.com/benholtzman/datamovies/1_notebooks/NB01_DirectSonification.ipynb) : Reads in a real 14 hour long seismogram (ground motion) from the 2011 Tohoku earthquake and turns it into sound! The .wav soundfile is output to the **3_output** directory and can be played using most audio software such as iTunes or Audacity.

*Note: added .py versions of the notebooks in case Jupyter Notebook is not installed*
