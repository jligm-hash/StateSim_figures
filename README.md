# StateSim_figures

This repository contains the code to reproduce figures for the StateSim publication.

## Aim

This repository provides reproducible scripts for generating all figures presented in the StateSim study. The code enables researchers to:
- Reproduce the figures from the original publication
- Adapt the visualization methods for similar analyses
- Verify the results presented in the paper

## Requirements

### R Version
- R version 4.0.0 or higher is recommended

### Required R Packages
To install the required packages, run:
```r
# Core packages
install.packages(c(
  "ggplot2",      # For creating figures
  "dplyr",        # For data manipulation
  "tidyr"         # For data tidying
))

# Additional packages may be needed depending on specific figures
# install.packages(c("package_name1", "package_name2"))
```

## Installation

1. Clone this repository:
```bash
git clone https://github.com/jligm-hash/StateSim_figures.git
cd StateSim_figures
```

2. Open R or RStudio in the project directory

3. Install required packages as listed above

## Usage

[Add specific instructions for running the code, e.g.:]
```r
# Source the main script
source("main_figures.R")

# Or run individual figure scripts
source("figure_1.R")
source("figure_2.R")
```

## Repository Structure

```
StateSim_figures/
├── README.md          # This file
├── LICENSE            # Apache License 2.0
└── [Add your scripts and data directories here]
```

## Citation

If you use this code in your research, please cite:

```
[Add citation information here]
```

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or issues, please:
- Open an issue on GitHub
- Contact: [Add contact information]

## Acknowledgments

[Add any acknowledgments or funding information here]
