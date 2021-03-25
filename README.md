# ABM microcarriers

This software is used for the Proof of Concept project by the [CMMC](thecmmc.org).

## About

This repository contains the ABM-only-microcarriers model that is being developed for the GFI bioreactor project from the [Cultivated Meat Modeling Consortium](http://www.thecmmc.org).
To run this model a working installation of Biocellion v3.1 is needed.

## Setup

- Download Biocellion 3.1 (Biocellion 3.1 is currently not available yet)
- Install CGAL: https://doc.cgal.org/latest/Manual/usage.html

## Parameter sweep

- A parameter list (in csv format) is provided to perform a parameter sweep over several model variables. This list was exported from the [online sheet](https://docs.google.com/spreadsheets/d/1vUilJizjnn6fNxQghJ9gVnOYdlbbBw1kTlf4Yeo25Bw/edit#gid=0) to run simulations for the PLOS one compbio publication. 
- To run the simulations for this parameter sweep, use the [parameter sweep script](https://github.com/TheCMMC/biocellion-tools/blob/master/poc_abm_only.sh) that lives in the biocellion-tools repository.
- Other tools for cleaning up the output, checking for failed simulations and plotting the output can also be found in [the biocellion-tools repository](https://github.com/TheCMMC/biocellion-tools).

## Contributing

If you want to contribute to this repository, please create a new branch and a (draft) pull request for this branch.

## Contact

For more information and help see the website [www.thecmmc.org](www.thecmmc.org).
