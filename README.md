# NeRF_2DTo3D
NeRF_Test Ver(0.01)
단일 장면에 대한 신경 표현을 최적화하고 새 보기를 렌더링하는 Tensorflow 구현입니다.

- Python -
Tensorflow 1.15
matplotlib
numpy
imageio
configargparse

TL;DR QuickStart
conda env create -f environment.yml
conda activate nerf
bash download_example_data.sh
python run_nerf.py --config config_fern.txt
tensorboard --logdir=logs/summaries --port=6006

NeRF 최적화
bash download_example_data.sh
