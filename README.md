# historical-text-analysis
follow steps on https://github.com/thunlp/OpenNRE?tab=readme-ov-file
convert required linux file to windows
install pytorch from https://pytorch.org/
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
* change requirements.txt to : 
torch==2.2.2
transformers==3.4.0
pytest==5.3.2
scikit-learn==0.22.1
scipy>1.4.1
nltk>=3.6.4

* install these :
  pip install --upgrade pip setuptools
  pip install scipy==1.7.3
  pip install -r requirements.txt
  pip setup.py install
  pip setup.py develop
  pip install fastcoref
  pip install --upgrade jupyter ipywidgets
  pip install --upgrade tqdm
  pip install scikit-learn
  pip install numpy
  pip install --upgrade nltk

make a folder for pretrain in opennre & install bert and glove from pretrain/OpenNRE
make a folder for benmark and install wiki80 or anyone you like

place r2.ipynb in OpenNRE and run


