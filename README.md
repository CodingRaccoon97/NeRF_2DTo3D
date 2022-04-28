# NeRF_2DTo3D<br>
NeRF_Test Ver(0.01)<br>
단일 장면에 대한 신경 표현을 최적화하고 새 보기를 렌더링하는 Tensorflow 구현입니다.<br>
<br>
- Python  <br>
Tensorflow 1.15 <br>
matplotlib <br>
numpy <br> 
imageio <br>
configargparse <br>
<br>
TL;DR QuickStart <br>
conda env create -f environment.yml <br>
conda activate nerf <br>
bash download_example_data.sh <br>
python run_nerf.py --config config_fern.txt <br>
tensorboard --logdir=logs/summaries --port=6006 <br>
<br>
NeRF 최적화 <br>
bash download_example_data.sh <br>
