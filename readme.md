# python4lunch_cmip6gc

The simulations of global climate models participating in CMIP6 provide a wealth of information but are challenging to analyse due to the wide variety of models and conventions and the large volume of data, especially when looking at higher resolution simulations or multiple simulation variants per model. Traditional workflows involve locally downloading CMIP6 data from ESGF servers or analysing data directly at those servers. With the introduction of CMIP6 data on Google Cloud, faster and more transparent cloud-based analyses are now also possible. Packages like xmip help analysing the data across models with different conventions in a structured way. In the Python4Lunch talk on 22-01-2026 at IMAU (Utrecht University), I will explain the advantages of using cloud-based CMIP6 data and run you through a basic but neat demo workflow, based on examples available in the Pangeo Gallery and my own experiences.

## How to run
From command window, do the following:
- clone the repository: `git clone https://github.com/Timh37/python4lunch_cmip6gc`
- [Install Pixi](https://pixi.prefix.dev/latest/installation/)
- Run `pixi shell` in your terminal (this is equivalent to "activating" the conda environment)
- Run `jupyter notebook`
