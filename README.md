# CMIP6 Cookbook

[![nightly-build](https://github.com/ProjectPythiaTutorials/cmip6-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythiaTutorials/cmip6-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder-staging.2i2c.cloud/badge_logo.svg)](https://binder-staging.2i2c.cloud/v2/gh/ProjectPythiaTutorials/cmip6-cookbook.git/main)

This Project Pythia Cookbook covers examples of analysis of Google Cloud CMIP6 data using Pangeo tools.

## Motivation



## Structure

### Example workflows



## Running the Notebooks
You can either run the notebook using [Binder](https://mybinder.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://mybinder.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine
If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)   

1. Clone the `https://github.com/ProjectPythiaTutorials/cmip6-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythiaTutorials/cmip6-cookbook.git
    ```  
1. Move into the `cmip6-cookbook` directory
    ```bash
    cd cmip6-cookbook
    ```  
1. Create and activate your conda environment from the `environment.yml` file
    ```bash
    conda env create -f environment.yml
    conda activate cmip6-cookbook-dev
    ```  
1.  Move into the `notebooks` directory and start up Jupyterlab
    ```bash
    cd notebooks/
    jupyter lab
    ```

At this point, you can interact with the notebooks! Make sure to check out the ["Getting Started with Jupyter"](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html) content from the [Pythia Foundations](https://foundations.projectpythia.org/landing-page.html) material if you are new to Jupyter or need a refresher.
