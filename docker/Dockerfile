from tensorflow/tensorflow:1.8.0-gpu-py3

run apt-get update && apt-get install -y \
git \
python3-pip

run pip3 install --upgrade setuptools
run pip3 install --upgrade pip

run pip3 install \
numpy==1.14.3 \
scipy==1.0.1 \
scikit-image==0.13.0 \
matplotlib==1.5.1 \
pandas==0.23.1 \
Keras==2.1.2 \
torchvision==0.2.1 \
opencv-python==4.2.0.34 \
ipython==7.4.0

run apt-get update && apt-get install -y \
wget \
unzip

run wget --quiet \
https://download.pytorch.org/whl/cu90/torch-0.4.0-cp35-cp35m-linux_x86_64.whl && \
pip3 install torch-0.4.0-cp35-cp35m-linux_x86_64.whl

run apt-get update && apt-get install -y \
libsm6 \
libxrender1 \
libxext6

run pip3 install \
youtube-dl

run apt-get update && apt-get install -y \
ffmpeg

run pip3 install \
ffmpeg==1.4

env TF_FORCE_GPU_ALLOW_GROWTH=true
