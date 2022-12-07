# CS295RL_miniproj

## Installation instructions
The authors used Linux OS so it is best to use this as well to prevent installation/runtime issues.

Install miniconda/anaconda first if you don't have one.

The environment can be done in 2 ways:



1. Complete library installation through `environment.yml` file.

    `conda env create -f environment.yml`
2. Install the following frameworks:

    1. **FinRL**
        
        

        `sudo apt-get update && sudo apt-get install cmake libopenmpi-dev python3-dev zlib1g-dev libgl1-mesa-glx`

        `pip install git+https://github.com/AI4Finance-Foundation/FinRL.git`

        `git clone https://github.com/AI4Finance-Foundation/FinRL.git`
    
    2. **d3rlpy**

        `pip install d3rlpy`

## Notebooks

1. **CS295RL_MP_Baselines.ipynb**

    This runs training of baseline models. 

2. **CS295RL_visuals_all_RLs.ipynb**
    
    This notebook reads the results files and plots them.

## Dataset
The dataset is located at [stock_prices](https://drive.google.com/file/d/1v2CbML_YQ894zEyt8wb2LOI1G4O8GZLA/view?usp=sharing)

## saved checkpoints
The saved checkpoints for CQL and IQL models are included as they have longer training times. Extract them as necessary.

Format: `IQL**.tar.gz` or `CQL**tar.gz`


