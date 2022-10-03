# Hunting for Insider Threats Using LSTM-based Anomaly Detection
LADOHD is the anomaly detection framework presented in the paper Hunting for Insider Threats Using LSTM-based Anomaly Detection. This repo contains the utilized version of fast.ai deep learning library and a notebook with examples of how to run LADOHD.
  
## To install
Follow steps in fastai folder as indicated by their authors. You might have to unzip the file fastai.zip within the directory fastai.

## A list of technologies used within the project
* Python version: 3.6.1
* PyTorch version: 0.3.1
* CUDA version   : 9.0.176
* CuDNN version: 7005

## To run experiments
1. Prepare you sequencial data as indicated. Namely, csv files with two columns: (1) timestamp and (2) event_id (categorical).
2. Use the provided notebook to train your model on your data and test it accordingly.
3. Review the examples provided throughout the notebook.

## Paper Citations

### Plaintext Citation:
M. Villarreal-Vasquez, G. Modelo Howard, S. Dube and B. Bhargava, "Hunting for Insider Threats Using LSTM-based Anomaly Detection," in IEEE Transactions on Dependable and Secure Computing, doi: 10.1109/TDSC.2021.3135639.

### BibTeX Citation:
@ARTICLE{9652083,
  author={Villarreal-Vasquez, Miguel and Modelo Howard, Gaspar and Dube, Simant and Bhargava, Bharat},
  journal={IEEE Transactions on Dependable and Secure Computing}, 
  title={Hunting for Insider Threats Using LSTM-based Anomaly Detection}, 
  year={2021},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TDSC.2021.3135639}}
