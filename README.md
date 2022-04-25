# WiDS Puget Sound 2022 Dask Workshop
Short workshop (~45 minutes) introducing Dask to Data Scientists. Materials include:

1. Overview: What is Dask and when should I use it?
2. Interactive example using Dask Delayed, Bag, and DataFrame collections.
3. Summary, FAQs, and resources.

## Prerequisites
Participants should be familiar with Python, Jupyter Notebook, and the PyData Ecosystem (e.g. pandas and Scikit-Learn), but no former knowledge of Dask is required.

## Getting set up
There are two options for this workshop:
1. Click on this binder button [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/coiled/micro-dask-tutorial-widsPS22/main?urlpath=lab). This will spin up the necessary software environment to use the notebooks interactively from the browser. Binder is a free service, so resources are not guaranteed. Due to this limitation, sometimes you will not see the same efficiency gains with Dask as you would see otherwise.

2. Create your own environment locally. If you're comfortable with GitHub and creating software environments, then follow the next steps:


    1. **Clone this repository**
        
        In your terminal:

        ```
        git clone https://github.com/coiled/micro-dask-tutorial-widsPS22.git
        ```
        
        If unfamiliar with git, you can download the zip file of this repository at the top of the main page of the repository.
        
    2. **Download Anaconda** 
    
        If you do not have anaconda installed, you will need the Python 3 [Anaconda Distribution](https://www.anaconda.com/products/individual).
    
    3. **Create a conda environment**
        
        In your terminal navigate to the directory where you have cloned the `micro-dask-tutorial-widsPS22` repo and install the required packages by doing:

        ```
        conda env create -f binder/environment.yml
        ```

        This will create a new environment called `micro-dask-tutorial-widsPS22`. To activate the environment run:

        ```
        conda activate micro-dask-tutorial-widsPS22
        ```

    4. **Run Jupyter Lab**
        
        Once your environment has been activated and you are in the `micro-dask-tutorial-widsPS22` repository, in your terminal do:

        ```
        jupyter lab
        ```

        Open the `notebooks` directory for the workshop materials.

## Credit!
This workshop was adapted from the numerous great publicly available Dask materials including the [Dask Binder template from @jrbourbeau](https://github.com/jrbourbeau/dask-binder-template) and the [Dask Live by Coiled tutorial from @ncclementi](https://github.com/coiled/dask-mini-tutorial).

