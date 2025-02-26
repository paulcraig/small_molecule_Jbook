# Small Molecule RCSB PDB Search

The RCSB PDB is the repository for all publicly available experimentally 
determined protein structures in the world. This notebook is made in order to 
demonstrate and elaborate on how to use the rcsbsearchapi Python library to 
recreate Advanced Searches from the [RCSB PDB] (https://www.rcsb.org/) in Python. Further, this notebook 
will show how to download the files of the results of these searches, also in 
Python. This will be done through searching particularly for different drugs 
represented in the RCSB PDB, with each search demonstrating a different way of 
utilizing the Advanced Search tool.

## Installing Python through Anaconda

[Python] (https://www.python.org/) is a popular language for scientific computing, and great for general-purpose programming
as well. Installing all of its scientific packages individually can be a bit difficult, however, so it is 
recommended to use the all-in-one installer Anaconda.

1. Navigate to the [download page] (https://www.anaconda.com/download) for Anaconda.
2. Download the appropriate installer for your operating system. Make sure you get the installer listed under Python 3 (not 2.7).
3. Double click the installer icon and follow the set-up instructions, keeping most of the default options. If you are in Windows, make sure to choose the option Make Anaconda the default Python during installation.

## Installing JupyterLab with pip

In the terminal, write the following line:

```console
pip install jupyterlab
```

If you wish to instead install JupyterLab with conda or mamba, it is recommended to use the [conda-forge channel] (https://conda-forge.org/).

Once installed, launch JupyterLab with
```console
jupyter lab
```

The following links are to Jupyter Notebooks that include RCSB PDB search examples.


```{tableofcontents}
```
