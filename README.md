# SDQ
Official PyTorch implementation for paper "SDQ: Stochastic Differentiable Quantization with Mixed Precision". This work is done by Xijie Huang, Zhiqiang Shen, Shichao Li, Zechun Liu, Xianghong Hu, Jeffry Wicaksana, Eric Xing, and Kwang-Ting Cheng.

![framework](./images/framework.jpg)

### Abstract 

In order to deploy deep models in a computationally efficient manner, model quantization approaches have been frequently used. In addition, as new hardware that supports mixed bitwidth arithmetic operations, recent research on mixed precision quantization (MPQ) begins to fully leverage the capacity of representation by searching optimized bitwidths for different layers and modules in a network. However, previous studies mainly search the MPQ strategy in a costly scheme using reinforcement learning, neural architecture search, etc., or simply utilize partial prior knowledge for bitwidth assignment, which might be biased and sub-optimal.
In this work, we present a novel **S**tochastic **D**ifferentiable **Q**uantization **(SDQ)** method that can automatically learn the MPQ strategy in a more flexible and globally-optimized space with smoother gradient approximation. Particularly, Differentiable Bitwidth Parameters (DBPs) are employed as the probability factors in stochastic quantization between adjacent bitwidth choices. After the optimal MPQ strategy is acquired, we further train our network with entropy-aware bin regularization and knowledge distillation. We extensively evaluate our method for several networks on different hardware (GPUs and FPGA) and datasets. SDQ outperforms all state-of-the-art mixed or single precision quantization with a lower bitwidth and is even better than the full-precision counterparts across various ResNet and MobileNet families, demonstrating the effectiveness and superiority of our method. 

## Preparation



## Quantization Strategy Generation

In Progress



## Post-training with Quantization Strategy

In Progress



## Citation

If you find our work useful in your research, please consider citing:

```
@InProceedings{
  huang2022sdq,
  title={SDQ: Stochastic Differentiable Quantization with Mixed Precision},
  author={Xijie Huang, Zhiqiang Shen, Shichao Li, Zechun Liu, Xianghong Hu, Jeffry Wicaksana, Eric Xing, and Kwang-Ting Cheng},
  booktitle={Proceedings of the 39th International Conference on Machine Learning},
  year={2022}
}
```

## Contact

Xijie Huang (huangxijie1108@gmail.com or xhuangbs@connect.ust.hk)
