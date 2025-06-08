# [TRADE: Scalable Configuration Tuning for Efficient Cross-camera Video Processing]

<!-- ## Code Structure
we decribe some core files in the following.
1. detector/yolov5/s_bo.py. 
2. detector/yolov5/bo.py -->


### Datasets
1. CityFlow. A real-world multi-camera video datasets. Due to its data license agreement, we can only download data from its official [website](https://www.aicitychallenge.org/) and put it in ./datasets/. 2.Synthetic. A synthetic multi-camera video benchmark of paper [Visual Road: A Video Data Management Benchmark](https://dl.acm.org/doi/pdf/10.1145/3299869.3324955). Since the 80-camera video data is too large, we present an example video dataset in [this link](https://drive.google.com/drive/folders/1ueVphZwP3T05uWA3qlRkHzU2FeA1anxf).

### Getting Started

```bash
# setup conda and python environment
$ conda create -n env_name python=3.7
$ conda activate env_name

# clone the repo and install the required dependency.
$ git clone  https://github.com/xiayuyang/TRADE.git
$ pip install -r requirements.txt

# run the single-camera tuning and cross-camera tuning
$ python ./detector/yolov5/s_bo.py
$ python ./detector/yolov5/bo.py
```

