### Interpretable Deep Learning Sepsis Model
#### A reproducibility study
This repository is a reproducibility study on an interpretable bi-lstm sepsis model with attention as proposed by a paper written by Dongdong Zhang, ChangChang Yin, Kathrin M Hunold, Xiaoqian Jiang, Jeffery M. Caterino and Ping Zhang in 2019.

Reference Paper:
https://doi.org/10.1016/j.patter.2020.100196

Package Requirements:
tqdm
torch
torchvision
sklearn

Run code for the study can be found in both **/originalpaper** as well as **/orginalcode**.

**/originalpaper**
Jupyter notebook found in this section is a re-write of the original code to allow the code to run as the original code had specific hardcoded paths and written in an older version of python.

**/orginalcode**
Jupyter notebook found in this section includes newly coded sections to process new data, however a usuable dataset was not able to be created as the data stucture provided publically by the data challenge is different from the dataset that was used to create this model. Likely some items had to be removed from the dataset to allow for public consumption. The code for the model was left as is to predict at 6 hours.
