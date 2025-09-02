# Advanced methods in bioimage analysis

This repository contains material for the 2025 [EMBO Practical course "Advanced methods in bioimage analysis"](https://www.embl.org/about/info/course-and-conference-office/events/bia25-01/).

# Data

External data for this session can be found here: 

https://heibox.uni-heidelberg.de/d/99c8794ee78d41b0954e/

Download the data to this repository, so you have following structure:

```bash
embo_bioimage_analysis/
├── data/
```

# Environment

To install the environment:

```conda create -n spatial-stats python==3.10.17```

Activate it:

```conda activate spatial-stats```

Install dependencies:

```pip install -r requirements.txt```


For the optional task in the spatial multi-omics session. Please follow these instruction to create an additional environment.

```conda create -n spatial-mefisto-optional python==3.8.1```

Activate it:

```conda activate spatial-mefisto-optional```

Install dependencies:

```pip install mofapy2 scanpy anndata ipykernel```