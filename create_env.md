# create conda environment

run the following to create a conda environment with the required packages:
```bash
conda create -n p5 python=3.9.7
conda activate p5
# the following line was taken from pytorch web site:
conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.6 -c pytorch -c nvidia

pip install transformers==4.2.1 sentencepiece
conda install -c anaconda jupyter
conda install -c conda-forge jupyter_contrib_nbextensions matplotlib
conda install pandas scikit-learn tqdm pyyaml
```


