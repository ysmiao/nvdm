# Neural Variational Document Model (NVDM) tensorflow implementation

------

This is the tensorflow implementation of NVDM for the paper: 
[Neural Variational Inference for Text Processing][1]. Yishu Miao, Lei Yu, Phil Blunsom. ICML 2016.

The original code is on torch. Since there are quite a few people asked me questions about the implementation, I have reimplemented the model by tensorflow. Please contact me if you find any problem with this implementation. It is able to achieve better results than the ones reported in the paper. 

### RCV1-v2 dataset
Please download and uncompress the [dataset][2] to: 
```
data/rcv1-v2
```
### Train the Model

```
python nvdm.py --data_dir data/20news/
```



  [1]: https://arxiv.org/abs/1511.06038
  [2]: https://drive.google.com/open?id=0ByuyRPR04lmnVzhmT1RoVTZOb1E
  [3]: https://arxiv.org/abs/1511.06038
