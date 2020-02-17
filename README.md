# pytorch-distributed
Demos of Pytorch training, combining:
- Distributed training
- Horovod
- Spot instances
- Hyperparameter Tuning
- Checkpoints.

The example was based in the PyTorch MNIST SageMaker example.

Demos are in the [pytorch_horovod_mnist](https://github.com/bobbruno/pytorch-distributed/tree/master/pytorch_horovod_mnist) folder.
- [pytorch_mnist_horovod_ckp_hpo.ipynb](https://github.com/bobbruno/pytorch-distributed/blob/master/pytorch_horovod_mnist/pytorch_mnist_horovod_ckp_hpo.ipynb): Full example leveraging all the components above. Due to JupyterLab interface differences, **the final evaluation will only work on classic Jupyter**.
  - The [`code/mnist_ckpoint.py`](https://github.com/bobbruno/pytorch-distributed/blob/master/pytorch_horovod_mnist/code/mnist_ckpoint.py) file contains the training script that implements Horovod and checkpoint saving/recovery.

- [pytorch_mnist_horovod_hyperparam.ipynb](https://github.com/bobbruno/pytorch-distributed/blob/master/pytorch_horovod_mnist/pytorch_mnist_horovod_hyperparam.ipynb): Example containing just distributed, Horovod and Hyperparamenter Tuning. Due to JupyterLab interface differences, **the final evaluation will only work on classic Jupyter**.
  - The [`code/mnist.py`](https://github.com/bobbruno/pytorch-distributed/blob/master/pytorch_horovod_mnist/code/mnist_ckpoint.py) file contains the training script that implements Horovod and checkpoint saving/recovery.
