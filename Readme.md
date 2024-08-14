
# AquaSolNet

Impelementation of a custom Graph Convolutional Net and an Attentive FP network for predicting aqueous solubility of chemicals. 

## Installation

Start by creating a conda environment(optional to make handling libraries easier.)

```bash
  conda create -n GNN python=3.11
```

The dataset has been taken from [this repo](https://github.com/mcsorkun/AqSolDB).

To install the libraries, run the cells in the jupyter notebook. 
    
## Run Locally

Run the cells in order in the jupyter notebook to train the models and evaluate their performance. 


## Improvements

Planning to add the global features implementation to the GCN network for imrpoved accuracy.  

Also, other feature-engineering techniques can also be explored to capture non-linearity in the data. Any suggestions are always appreciated :)