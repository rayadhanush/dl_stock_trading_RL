## Setup

For this project, we need stable baselines-3 which needs the following prerequisites.

```sh
sudo apt-get update && sudo apt-get install cmake libopenmpi-dev python3-dev zlib1g-dev libgl1-mesa-glx swig
```

Install all other dependency packages by creating a conda environment using the requirements.txt

```sh
conda create --name <env> --file requirements.txt
```

## Results

csv files generated as part of results will be saved at `results/`, training log files at `tensorboard_log` and model checkpoints at `trained_models`.
