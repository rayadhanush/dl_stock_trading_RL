## Environment setup

Create and activate conda environment named using the requirements.txt

```sh
conda create --name <env> --file requirements.txt
```

csv files generated as part of results will be saved at `results/`, training log files at `tensorboard_log` and model checkpoints at `trained_models`.

## Acknowledgement

We thank [FinRL team](https://github.com/GongZhengxin/NOD-fmri) for providing finetuned DRL algorithms which we have extensively used in this project.
