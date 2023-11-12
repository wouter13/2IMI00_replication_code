# readme replication study for paper by Wickramanayake et al. (2022)
## Building interpretable models for business process prediction using shared and specialised attention mechanisms

This repository contains the code for the replication study of the paper by Wickramanayake et al. (2022). The code is based on the code provided by the authors of the paper. The original code can be found [here](https://github.com/ZhipengHe/Shared-and-Specialised-Attention-based-Interpretable-Models)

## Requirements
The code is written in Python 3.9.13. To install the required packages, run the following command in the root directory of the project:
```
pip install -r requirements.txt
```

## run experiments

To run the experiments, go to one of the notebooks (files ending on .ipynb) and run the notebook to get the results. 

Notebook clarifications:
- All notebooks beginning with bpic_2012 and bpic_2017 are created by Wickramanayake et al. (2022). 
    - The notebooks ending on PREACCEPTED and Nabellen offertes generate interpretations for a certain decsiion point.
    - The other notebooks generate preformance results for different subsets of the data.

- The two notebooks beginning with BPIC_2020 are created for this replication
    - bpic_2020 generates the performance results for the data
    - bpic_2020_interpretations generates the interpretations for the data on the selected decision point

Other notebooks created for this replication:
- BPIC20/xes_to_csv.ipynb: converts the xes files of BPIC2020 to csv files