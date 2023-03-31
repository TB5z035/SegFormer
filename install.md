conda create -n segformer python=3.7

conda install pytorch==1.7.1 torchvision==0.8.2 torchaudio==0.7.2 cudatoolkit=11.0 -c pytorch
pip install -U openmim
mim install mmcv-full==1.3.0
pip install mmsegmentation==0.13.0
pip install timm==0.3.2 attr IPython
pip install -e . --user
