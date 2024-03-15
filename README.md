# mlflowdemo



## How to run?

```bash
conda create -n mlflowdemo python=3.9 -y
```

```bash
conda activate mlflowdemo
```

```bash
pip install -r requirements.txt
```

```bash
# first run
Python mlflowdemo.py
mlflow ui

# second run
Python mlflowdemo.py 0.4 0.7

# thrid run
Python mlflowdemo.py 0.3 0.8

# fourth run
Python mlflowdemo.py 0.4 0.9

# fifth run
Python mlflowdemo.py 0.3 0.6

```

MLFLOW_TRACKING_URI=https://dagshub.com/mayankchugh-learning/mlflowdemo.mlflow \
MLFLOW_TRACKING_USERNAME=mayankchugh-learning \
MLFLOW_TRACKING_PASSWORD= \


export MLFLOW_TRACKING_URI=https://dagshub.com/mayankchugh-learning/mlflowdemo.mlflow
export MLFLOW_TRACKING_USERNAME=mayankchugh-learning
export MLFLOW_TRACKING_PASSWORD=


