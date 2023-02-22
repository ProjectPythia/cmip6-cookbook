<img src="notebooks/images/cmip6-logo.webp" width=500 alt="CMIP6 logo"></img>

# CMIP6 Cookbook

[![nightly-build](https://github.com/ProjectPythia/cmip6-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cmip6-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](http://binder.mypythia.org/badge_logo.svg)](http://binder.mypythia.org/v2/gh/ProjectPythia/cmip6-cookbook.git/main)

This Project Pythia Cookbook covers examples of analysis of Google Cloud CMIP6 data using Pangeo tools.

## Motivation

From the [CMIP6 website](https://esgf-node.llnl.gov/projects/cmip6/):

> The simulation data produced by models under previous phases of CMIP have been used in thousands of research papers ... and the multi-model results provide some perspective on errors and uncertainty in model simulations. This information has proved invaluable in preparing high profile reports assessing our understanding of climate and climate change (e.g., the IPCC Assessment Reports).

With such a large amount of model output produced, moving the data around is inefficient. In this collection of notebooks, you will learn how to access cloud-optimized CMIP6 datasets, in addition to a few examples of using that data to analyze some aspects of climate change.

## Authors

[Ryan Abernathey](https://github.com/rabernat), Henri Drake, [Robert Ford](https://github.com/r-ford)

### Contributors

<a href="https://github.com/ProjectPythia/cmip6-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/cmip6-cookbook" />
</a>

## Structure

### Foundations

This section includes three variations of downloading CMIP6 data from cloud storage.

### Example workflows

There are currently four examples of using this data to 
- Estimate equilibrium climate sensitivity (ECS)
- Plot global mean surface temperature under two different [Shared Socioeconomic Pathways](https://unece.org/fileadmin/DAM/energy/se/pdfs/CSE/PATHWAYS/2019/ws_Consult_14_15.May.2019/supp_doc/SSP2_Overview.pdf)
- Plot changes in precipitation intensity under the SSP585 scenario
- Calculate changes in ocean heat uptake after regridding with xESMF

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

1. Clone the `https://github.com/ProjectPythia/cmip6-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/cmip6-cookbook.git
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
