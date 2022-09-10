# Cross_Mod_Interpretation_CrisisMMD

## Description
This is the readme file for the project associated with the term paper submitted as part of Multimodal Semantic Representation.


## Source of Dataset
Dataset included in the /datasets folder has been taken from this URL: <https://crisisnlp.qcri.org/crisismmd>

## Contents
Contents of the project-

```
.
├── Cross_Modal_Captioning.ipynb
├── README.md
├── Sentence_Pair_Classification.ipynb
└── dataset
    ├── california_wildfires_final_data.tsv
    ├── hurricane_harvey_final_data.tsv
    ├── hurricane_irma_final_data.tsv
    ├── hurricane_maria_final_data.tsv
    ├── iraq_iran_earthquake_final_data.tsv
    ├── mexico_earthquake_final_data.tsv
    └── srilanka_floods_final_data.tsv

```


## Instructions to run:
There are two seperate python notebooks:
- Please run ``` Cross_Modal_Captioning.ipynb``` first, it will generate the train, test and validation splits for the each single tsv associated with a disaster.
- Then run all the cells for ``` Sentence_Pair_Classification.ipynb ``` by passing as inputs the csv files from the previous step.


All the cells of both the notebook have been sufficently commented.

## Results
Please refer to the mansucript for the results of each and indivivual disaster summarised along with the best set of hyper-parameters



