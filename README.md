# Histone coverage plots

An open-source Python package to visualize PTM coverage of histone mass spectrometry data from the [ProGenTomics](https://www.progentomics.ugent.be/) lab.

## License

This software was developed at the the [ProGenTomics](https://www.progentomics.ugent.be/) lab and is freely available with an [MIT License](LICENSE.txt). Third-party licenses are applicable to external Python packages in the [requirements file](requirements.txt).

## Installation

Installation requires the following steps:
* Create a [conda virtual environment](https://docs.conda.io/en/latest/),
* clone the repository and
* install the [requirements](requirements.txt).

This can be done with e.g. the following commands:

```bashrc
conda create -n coverage_plots python=3.8
conda activate coverage_plots
git clone https://github.com/swillems/coverage_plots.git
cd coverage_plots
pip install -r requirements.txt
# conda deactivate
```

## Test data

Test files can be downloaded from the [release page](https://github.com/swillems/coverage_plots/releases/latest).

## Usage

This software is provided as a single [jupyter notebook](histone_coverage.ipynb).

## How to contribute

This repository is not under active development. Please contact the [ProGenTomics](https://www.progentomics.ugent.be/) lab for any inquiries.
