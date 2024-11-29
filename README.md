# Comprehensive Machine Learning Library to Predict High-yield AAV Variants
This repository is the official implementation for the paper: [Comprehensive Machine Learning Library to Predict High-yield AAV Variants]. This library is used for AAV virus packaging and sequencing to collect training data for ML. We compared several machine learning and Statistical algorithms. Through iterative learning and continuous optimization, we successfully developed a robust and dependable prediction model.



## Usage 

### 1. Install Tensorflow and necessary dependencies.

```
pip install tensorflow == 2.13.0
pip install tensorboard == 2.13.0
pip install protobuf == 4.25.1
pip install keras == 2.13.1
pip install scipy==1.10.1
pip install scikit-learn==1.3.0
pip install xgboost==2.0.2
pip install pandas==2.0.0 
pip install numpy==1.23.5
```

### 2. Available Data 
The data can be obtained and downloaded from [Google Drive](https://drive.google.com/drive/folders/1JE7GwDmfb9-lCQDJGC2A5rHZEM18RaxU?usp=sharing), and makedir path ```/data``` and put dataset in ```/data```. 


### 3. Code Structure  

This Repo trains and evaluates the model. We provide jupyter notebooks for code engineering of comprehensive machine learning repositories under CNN, RNN, VAE, ResNet, and Regression folders. The specific structure is as follows：
```
├── README.md
├── CNN
│   ├── 1st_aa_nor_package.ipynb
│   ├── 1st_seq_nor_package.ipynb
│   ├── 2nd_aa_nor_package.ipynb
│   ├── 2nd_seq_nor_package.ipynb
│   └── utils_f4f.py
├── RNN
│   ├── 1st_aa_nor_package.ipynb
│   ├── 1st_seq_nor_package.ipynb
│   ├── 2nd_aa_nor_package.ipynb
│   ├── 2nd_seq_nor_package.ipynb
│   └── utils_f4f.py
|
├── ResNet
│   ├── 1st_aa_nor_package.ipynb
│   ├── 1st_seq_nor_package.ipynb
│   ├── 2nd_aa_nor_package.ipynb
│   ├── 2nd_seq_nor_package.ipynb
│   └── utils_f4f.py
|
├── Transformer
│   ├── Model.py
│   ├── Train-K-Fold.py
│   ├── Train-K-KL.py
│   ├── Transformer_aa_nor_package.ipynb
│   └── generater.py
│   └── utils_f4f.py
|
├── VAE
│   ├── 1st_aa_nor_package.ipynb
│   ├── 1st_seq_nor_package.ipynb
│   ├── 2nd_aa_nor_package.ipynb
│   ├── 2nd_seq_nor_package.ipynb
│   ├── vae
│   │   ├── train.py
│   │   ├── predict.py
│   │   ├── vae.py
│   ├── utils
│   │   ├── data_processing.py
│   │   ├── loss.py
│   │   ├── fitness.py
│   │   ├── utils_f4f.py
|
├── CatBoost_1st_aa_nor_package.ipynb
|
├── GradientBoost_1st_aa_nor_package.ipynb
|
├── LGBMRegressor_1st_aa_nor_package.ipynb
|
├── LSTM_GRU_1st_aa_nor_package.ipynb
|
├── RandomForest_1st_aa_nor_package.ipynb
|
├── XGBoost_1st_aa_nor_package.ipynb

```

## Citation

If you find this repository helpful for AAV, please cite our paper. 

```
@article{tanchen2024aav,
    title={Comprehensive Machine Learning Library to Predict High-yield AAV Variants},
    author={Fangzhi Tan, Duxin Chen，Jiawen Chen, Li Peng, Jieyu Qi, Siyao Zhu, Lianqiu Wu, Jinjia Li, Yangnan Hu, Shanzhong Zhang, Sijie Sun, Huaien Song, Wenwu Yu, Renjie Chai},
    journal={Under Review},
    year={2024}
}
```