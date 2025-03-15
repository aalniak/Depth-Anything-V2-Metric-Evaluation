# Depth Anything V2 Metric Depth Evaluation Benchmark on Several Datasets
This forked repository contains scripts under ./metric_depth folder, which downloads and runs the model on the dataset.

Running the scripts requires a correctly-set Depth-Anything-V2 environment, which user follows the original project's installation guide. Further, to use metric depth estimation models, it is a must to 
download and put them under ./metric_depth/checkpoints.

While installation, if environment name is set to anything other than default (Depth-Anything-V2), it is a requirement to change the environment name from .sh scripts.
If environment name is default, one may easily proceed to run the scripts by:
```bash
bash kitti_test.sh
```

