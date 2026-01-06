# SDCT
We have made the source code of the SDCT method publicly available. 

# Dataset
We have made our dataset public. The dataset is only used for academic purposes. If you have used our dataset, please refer to our article. Dataset can be found at [BaiduYun Drive](https://pan.baidu.com/s/1Gn1qrD8DvLMGfIS49_04vQ?pwd=wmvx) (code:wmvx ).
# Code
The SDCT Code can be found at [BaiduYun DriveT](https://pan.baidu.com/s/1AC9A6d88Roi05yXgJlGScQ?pwd=SDCT) (code:SDCT)

## 0. Main Environments
```bash
conda create -n SDCT python=3.8
conda activate SDCT
pip install torch==1.13.0 torchvision==0.14.0 torchaudio==0.13.0 --extra-index-url https://download.pytorch.org/whl/cu117
pip install packaging
pip install timm==0.4.12
pip install pytest chardet yacs termcolor
pip install submitit tensorboardX
pip install triton==2.0.0
pip install scikit-learn matplotlib thop h5py SimpleITK scikit-image medpy yacs
```

# Demo and other methods

Our unsupervised static image anomaly detection method https://github.com/aoihd/RSM (It combines the normalizing flow and the reconstruction mechanism. Our initial model, for the first time, applied the unsupervised anomaly detection method to the spiral weld image in practice, and obtained a good detection effect.)

Our unsupervised dynamic image screening method https://github.com/Weld-det/TRDM (This is an iterative version of the static unsupervised anomaly detection method. The proposed model has the ability of dynamic fuzzy weld image screening.  It has the highest screening accuracy and the best effect)

Our multi-task defect detection method https://github.com/SD-Weld/MTDF (This contains a large number of actual on-site videos and practical application cases. A multi-task defect detection method is more conducive to the integration of the model in practical applications and software)

Our fine-grained tiny defect detection method under static Static working condition https://github.com/SD-Weld/SDCT  (It has an outstanding ability to locate porosity and circular inclusion defects.) 



