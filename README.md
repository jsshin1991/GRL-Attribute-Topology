# Learning Graph Representation with Attribute-Topology Aggregation


## Data & Requirements
Before running the code, the data should be downloaded from the following Dropbox link.
```
https://www.dropbox.com/s/dajg409tgs607gf/data.zip?dl=1
```
See requirements.txt for our running environment. 


## Train Models
To run 10-fold cross-validation for graph classification tasks, run the main_10fold_experiment.py with the following command:
```
python main_scripts/main_10fold_experiment.py --config=configs/10fold_config.json --dataset_name=NCI1
```

To run graph classification tasks on all benchmark datasets, run the run_all_10fold.py with the following command:
```
python main_scripts/run_all_10fold.py
```

To run QM9 experiment for graph regression tasks, run the main_qm9_experiment.py with the following command:
```
python main_scripts/main_qm9_experiment.py --config=configs/qm9_config.json
```

## Experiemtal Results
All the experimental results in the paper can be downloaded from the following Dropbox link.
```
https://www.dropbox.com/sh/pq77pmiqm73lkb9/AADTVJiSGT75nwVPgAmEELy5a?dl=1
```