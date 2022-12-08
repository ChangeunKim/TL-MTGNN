# MTGNN
This is a PyTorch implementation of the paper: [Connecting the Dots: Multivariate Time Series Forecasting with Graph Neural Networks](https://arxiv.org/abs/2005.11650), published in KDD-2020.

## Requirements
The model is implemented using Python3 with dependencies specified in requirements.txt


## Model Training

### US Index data
* Single-step

```
python train_single_step.py --save ./model/model-usindex.pt --data ./data/train_M1.txt --num_nodes 10
```
* Multi-step
```
python train_multi_step.py --save ./model/model-usindex.pt --data ./data/train_M1.txt --num_nodes 10
```



## Citation

```
@inproceedings{wu2020connecting,
  title={Connecting the Dots: Multivariate Time Series Forecasting with Graph Neural Networks},
  author={Wu, Zonghan and Pan, Shirui and Long, Guodong and Jiang, Jing and Chang, Xiaojun and Zhang, Chengqi},
  booktitle={Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery \& Data Mining},
  year={2020}
}
```
