# Semantic Landscape Analysis

## Repositoriy structure

```bash
.
├── datasets
├── graphs
└── notebooks
    ├── dataset-generation
    ├── graph-generation
    └── visualization
```

## Description

- The folder `notebooks` contains all notebook which were used to create and visualize the data and graph structure
    - **dataset-creation:** This folder contains the notebook which was used to create the data and query the LOV API. Data is stored in `datasets/sdm_lov_df.csv`
    - **graph-generation:**  Uses the data and creates the graph structures. Created are stored in `graphs/`.
    - **visualization:** Uses the graoh strcutres and data to create statistical analysis

For graph visualization the program [Gephi](https://gephi.org/) was used. You can directly read in the graphs from the folder `graphs/`.

