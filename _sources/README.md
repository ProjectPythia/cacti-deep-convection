<img src="notebooks/images/relampago_cacti_draft_logo-01.png" alt="thumbnail" width="300"/>

# CACTI Deep Convection Initiation

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11265276.svg)](https://doi.org/10.5281/zenodo.11265276)


## Motivation

This cookbook will show CACTI data access, manipulation, and some results regarding a deep convection case study. 

## Authors

[Natalia Roldan](https://github.com/NataliaRoldanHenao)
[Eddie Wolff](https://github.com/EWolffWX)
[Dhwanit J Mise](https://github.com/dhwaniit)
[Victor Ojo](victorojo24), [Alfonso Ladino](https://github.com/aladinor), [Max Grover](https://github.com/mgrover1)
### Contributors

<a href="https://github.com/aladinor/cacti-deep-convection/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=aladinor/cacti-deep-convection" />
</a>

## Structure


### CACTI field campaign

### Radar observations

### Hypothesis and research questions

### Deep convection meteorological conditions

### Microphysical features of deep convection

### LASSO simulations

## Conclusions

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
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

1. Clone the `https://github.com/aladinor/cacti-deep-convection` repository:

   ```bash
    git clone https://github.com/aladinor/cacti-deep-convection
   ```

1. Move into the `cacti-deep-convection` directory
   ```bash
   cd cacti-deep-convection
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate cacti-deep-convection-dev
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
