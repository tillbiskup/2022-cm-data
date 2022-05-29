# EPR data and analysis for Järsvall *et al.*, Chem. Mater. 2022

This directory contains both, raw data and analysis "recipes" used to analyse the EPR data for the following manuscript:

 * Emmy Järsvall, Till Biskup, Yadong Zhang, Renee Kroon, Stephen Barlow, Seth Marder, Christian Müller: Double doping of a low-ionization energy polythiophene with a molybdenum dithiolene complex. *Chemistry of Materials*, 2022


## Organisation

All (raw) data and accompanying metadata are contained in the ``data`` directory, and the figures created reside in the ``figs`` directory. The recipes used for data analysis (the YAML files) are located in the root directory.


## Analysis how-to

The analysis of the EPR data relies on the [cwepr Python package](https://doi.org/10.1016/j.jmr.2021.107140) ([documentation](https://docs.cwepr.de/)) that itself is based on the [ASpecD framework](https://doi.org/10.1002/cmtd.202100097) ([documentation](https://docs.aspecd.de/)).

To (re-)run the analysis, install the cwepr Python package (best within a Python virtual environment)

    pip install cwepr

and call

    serve <recipe>

for each of the recipe files (YAML files) in the root directory. This will (re-)run the analysis and store the resulting figures to the ``figs`` directory. Details of the analysis can be found in the automatically created "history recipes" (those with the timestamp suffix).


## License

All files are available under a Creative Commons Attribution 4.0 International license.
