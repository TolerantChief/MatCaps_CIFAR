# Matrix Capsules with EM Routing
A PyTorch implementation of [Matrix Capsules with EM Routing](https://openreview.net/pdf?id=HJWLfGWRb)

El código ha sido obtenido de una implementación realizada por Lei Yang. 
- https://github.com/yl-1993/Matrix-Capsules-EM-PyTorch

## Usage
1. Install [PyTorch](http://pytorch.org/)

2. Start training (default: CIFAR-10)
```bash
python train.py --batch-size 20 --test-batch-size 20
```


## CIFAR-10 experiments

Specific setting is `lr=0.01`, `batch_size=20`, `weight_decay=0`, Adam optimizer, without data augmentation.

Following is the result after 35 epochs training:

| Arch | EM-Iters | Coord Add | Loss  | Test Accuracy |
| ---- |:-----:|:---------:|:----:|:-------------:|
| A=64 B=8 C=16 D=16        | 2 | Y | Spread    |  71.5200   |




## Reference
- https://github.com/shzygmyx/Matrix-Capsules-pytorch
- https://github.com/www0wwwjs1/Matrix-Capsules-EM-Tensorflow
- https://github.com/gyang274/capsulesEM
- https://github.com/yl-1993/Matrix-Capsules-EM-PyTorch
