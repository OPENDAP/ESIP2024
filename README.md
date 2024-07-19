# Tutorial Notebooks for ESIP 2024

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OPENDAP/ESIP2024/main)

OPeNDAP workflows that demonstrate access, visualization and downloading to remote data that is hosted in OPeNDAP servers. Here you will find examples that make of of data from

- NASA (via Earth Data Cloud access)
- ESGF

The goal of this notebooks is to introduce several OPeNDAP concepts from the Client side, and thus involve develop basic understanding of

- Data URLs to access remote dataset.
- Data URLs with constrant expressions (CEs) to subset remove data.
- Understand DAP2 vs DAP4 models of OPeNDAP.
- Lazy inspection of remote data via pydap and xarray.
- Searching through different Portals to find OPeNDAP hosted Data.


## Requirements and Recommended Order of Notebooks
This series of notebooks can be run interactively on a Binder environment [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OPENDAP/ESIP2024/main). This will take care of all the environment installation required to run these notebooks.

You can also clone this repository and run them locally. For that you will need to have [Anaconda](https://www.anaconda.com/download) installed. Then you can follow the next steps:

    $ git clone https://github.com/OPENDAP/ESIP2024.git
    $ cd ESIP2024
    $ mamba env create -f binder/environment.yml
	$ mamba activate ESIP2024	

You can now run the notebooks on your local browser by doing

    $ jupyter lab


**We only recommend start first** with the

- ` GetStarted.ipynb` notebook.

Since many of the notebooks will make use of a `.json` created there with the appropriate EDL token credentials.


