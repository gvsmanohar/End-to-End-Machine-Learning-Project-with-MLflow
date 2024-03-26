# End-to-End-Machine-Learning-Project-with-MLflow

## WorkFlows
1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml


# How to run?

### STEPS:

Clone the repository

```bash
https://dagshub.com/gvsmanohar/End-to-End-Machine-Learning-Project-with-MLflow
```

### STEP 01 - Create a conda environment after opening the repository

```bash
conda create -n mlproj python=3.8 -y
```

```bash
conda activate mlproj
```

### STEP 02 - install the requirements
```bash
pip install -r requirements.txt
```

```bash
python app.py
```

Now,
```bash
open up the local host and port
```

## Ml flow
[Documentation](https://mlflow.org/docs/latest/index.html)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/gvsmanohar/End-to-End-Machine-Learning-Project-with-MLflow.mlflow \
MLFLOW_TRACKING_USERNAME=gvsmanohar \
MLFLOW_TRACKING_PASSWORD=5b38953f746eb9a3f14ea84fd1dcf8dde814bfc4 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/gvsmanohar/End-to-End-Machine-Learning-Project-with-MLflow.mlflow

export MLFLOW_TRACKING_USERNAME=gvsmanohar

export MLFLOW_TRACKING_PASSWORD=5b38953f746eb9a3f14ea84fd1dcf8dde814bfc4

```